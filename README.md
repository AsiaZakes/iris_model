# iris_model

Run in cmd:

docker build -t <image_name> .

docker run -p 5000:5000 <image_name>



Open in browser:

http://127.0.0.1:5000/api/v1.0/predict?&sl=4.5&pl=1.3  

predicted class should be "-1"

change request parameters to see different results.
