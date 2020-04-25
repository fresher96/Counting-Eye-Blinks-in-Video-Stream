# Counting Eye Blinks in Video Stream
Python notebook that detects eye blinks of a person in a video stream using dlib and opencv.


## Run Instructions

Download [this file](https://drive.google.com/open?id=19Xz-Ly2LXofgpUGt-AHFTyM71z_RvzDL) to the working directory.

Run the command:  
`dlib='./shape_predictor_68_face_landmarks.dat' runipy main.ipynb`

For more options, run:  
`input='path/to/input-file'
output='path/to/output-file'
fps=10
dlib='./shape_predictor_68_face_landmarks.dat'
runipy main.ipynb`  

where:
- input: if you want to input a video file. If not provided it uses the webcam.
- output: if provided, the output video file will be saved.
- fps: frame per second rate. In case input file is specified the fps will be derived from the input. Otherwise, this value will be used. Default value is 10.
- dlib: the path to dlib's pre-trained facial landmark detector ([download link](https://drive.google.com/open?id=19Xz-Ly2LXofgpUGt-AHFTyM71z_RvzDL)).

## Demos
- [Online](https://i.imgur.com/DoV0fKy.mp4) (using webcam)
- [Offline](https://imgur.com/ALyi4b3.mp4) (using a video file)


