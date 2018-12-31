# ikt442
Fallen persons with YOLO
This project was suggested by the Oslo Police, and was the selected topic for my Seminar 3 (IKT442) 
at University of Agder, ICT department. The project is based on the YOLOv3 Windows implementation by AlexyAB https://github.com/AlexeyAB/darknet, which again 
is derived from the original of Redmon: https://pjreddie.com/darknet/yolo/

Not all files are stored in this git: Not the build files and some of the weight files, as there is a size limit on 
the free acount. Use the original sources to get the pre trained weights.
YOLOv3 requires a GPU with CUDA, which is a NVidia technology. Also OpenCV is required. For detailed installation instrutions, 
see the readme at https://github.com/AlexeyAB/darknet.

There are some tools implemented as Notebook scripts, that is, use the Anaconda Notebook. 
The tools are for:
* Image augmentation tool. Creates a number of augmented images, using some random parameters. Maintains darknets setup files, 
and annotation files.
* Generating randomized test- and verification sets from an image bank with annotated images. Maintaines darknets setup files.
* Testing generated weights using the Darknet map command. Results are written to file, and the best weight file found.
