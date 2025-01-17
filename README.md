- Uploading a Video
Endpoint: /videos/upload
Method: POST
Parameters: Upload a video file using a form with the key file.
Usage: Use an HTTP client like Postman or cURL to make a POST request to the /videos/upload endpoint with the video file as the form data.

- Cutting a Video
Endpoint: /videos/cut
Method: POST
Parameters: Upload a video file using a form with the key files. Additionally, specify the duration of each segment in seconds using the form field dur.
Usage: Make a POST request to the /videos/cut endpoint with the video file and duration specified.
Inserting a Logo into a Video

Endpoint: /videos/insert-logo
Method: POST
Parameters: Upload the video file and logo file using forms with keys file and logo, respectively. Optionally, specify the position (1 by default) to insert the logo.
Usage: Send a POST request to the /videos/insert-logo endpoint with the video file, logo file, and position (if required).

- Concatenating Videos
Endpoint: /videos/concat
Method: POST
Parameters: Upload multiple video files using a form with the key files. Optionally, specify the target platform (0 for mobile, 1 for Windows) as a form field.
Usage: Send a POST request to the /videos/concat endpoint with multiple video files to concatenate.

- Blurring a Video
Endpoint: /videos/blurr
Method: POST
Parameters: Upload a video file using a form with the key file. Additionally, specify the blur strength and the number of jobs (optional).
Usage: Make a POST request to the /videos/blurr endpoint with the video file and blur strength specified.

- Changing the Speed of a Video
Endpoint: /videos/speedchange
Method: POST
Parameters: Upload a video file using a form with the key file. Additionally, specify the speed factor (2 by default).
Usage: Send a POST request to the /videos/speedchange endpoint with the video file and speed factor specified.

- Retrieving a Video by ID
Endpoint: /videos/{id}
Method: GET
Parameters: Specify the ID of the video to retrieve in the URL path.
Usage: Make a GET request to the /videos/{id} endpoint, replacing {id} with the ID of the desired video.
#   V i d e o P r o c e s s i n g A P I  
 