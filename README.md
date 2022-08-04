# Flask-Image-Stream

 To send an image stream from one's laptop's Web Cam and display this image stream onto a Web Page, we are going to import flask and cv2 and create an object camera, which will be used to input the image stream by calling the VideoCapture() method in cv2.

We will then create a generator called generate_frames() which will consist of a boolean called "success" which tells whether the image is read or not. If success is true then the image stream is encoded in jpg format using  the imencode method in cv2 so that we are able to display the images in the html file.

We will then create a file called index.html which will output the image stream from the webcam.

