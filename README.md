# EVA5S13

link to the Yolov3 Custom object detection
https://youtu.be/ndrh-RhIrko


Data annotation :
Go to the TSAI GitHub repo mentioned in the corse notes. From there, go to the other GitHub repo containing the annotator tool (linked in TSAI's GitHub). Clone that repo to your local drive. There will be a folder called "images" inside it. Dump your images (make sure they are of 1300*800 resolution or less). Open the "class.txt" file and include the name of your classes one below the other. Then run "main.py", which will open a tool. Click on"load" if you have dumped the images to the "image" folder directly. If you have created another folder inside the "images" folder and uploaded it, key in the relative path to that directory from the "images" folder and then click on "load". Once it loads the images, annotate them one by one by clicking on "next" to load the next image. Once you have annotated all the images, check the "labels" folder to make sure that a text file is created for every file with the 
<class id>(based upon the order of classes you have entered in the class.txt) <the four annotation values>.

Then run "process.py" to populate the train.txt and val.txt files in that cloned repo folder.


