# Introduce  
This project use a raspberry pi3 with a camera and a computer to accomplish a deep learning camera.
  
In this project we use raspberry pi3 as a personal computer and use it interface with a server(my computer).<br><br>

When tagert shows in the camera of raspberry pi3, the server will detect it use YOLO and take a picture use rasbperry pi.


# How to use<br><br>
You'll need a few different libraries installed on the Raspberry Pi. Most notably, OpenCV 3 with Python bindings, along with Flask.

The Raspberry Pi runs the Camera-Server code, and sends back images from a webserver.

On another computer, you'll run the inference script, and it will detect whether or not there are birds in your webcam's image.

For this to run, you'll need to download and install the Darkflow weights, along with the YOLO model of your choice. Once that's installed, you should then be able to start doing inferences.

If you're looking for a pretrained model, I used the yolo-voc weights at the Darkflow repo.

thtrieu even linked to a Google Drive copy of his models [here](https://drive.google.com/drive/folders/0B1tW_VtY7onidEwyQ2FtQVplWEU).
