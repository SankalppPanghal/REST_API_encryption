# REST_API_evervault

Successfully created a REST API, for evervault coding test.
This was my first time using
1. Flask to create working APIs
2. Using crypto libraries

## Requirements (How to run)

1. Create your python virtual environment using anaconda or something else you prefer (virtualenv)
2. Activate you environment
3. pip install flask
4. pip install pycryptodome
5. pip install shutil

This should be good to go

Now run
> python evervault_rest_api.py

API should now be live at 127.0.0.1:6362 
Now you can test working of this API

## Task

<img src="task_api.png" height="800">


## Result

You can check with POSTMAN software, all endpoints are working fine

1. /encrypt
<img src="ever_encrypt.png" width="600"> 

2. /decrypt
<img src="ever_decrypt.png" width="600"> 

3. /sign
Sign with SHA256 hashing and our private key 
<img src="ever_sign.png" width="600"> 

4. /verify
If provided with correct signature, returns 204 response code
<img src="ever_verify1.png" width="600">

Or else 400 response code
<img src="ever_verify2.png" width="600"> 
