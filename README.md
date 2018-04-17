## (MASS) Motion Activated Surveillance System

by 

Ashwini Singh

Faraz Husain

Vivek Singh



Here is a list of used classed and links to the documentation if you are looking forward to implementing your own javafx+opencv project.



- BufferedImage  [See here](https://docs.oracle.com/javase/7/docs/api/java/awt/image/BufferedImage.html)

* DataBufferByte [See here](https://docs.oracle.com/javase/7/docs/api/java/awt/image/DataBufferByte.html)
* ClassArrayList  [See here](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)
* List [See here](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)
* Executors [See here](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/Executors.html)
* ScheduledExecutorService [See here](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/ScheduledExecutorService.html)
* Time Unit [See her](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/TimeUnit.html)
* SwingFXUtils [See here](https://docs.oracle.com/javase/8/javafx/api/javafx/embed/swing/SwingFXUtils.html)
* JavaFXevent [See here](http://www.java2s.com/Tutorials/Java/JavaFX/1100__JavaFX_Events.htm)
* FXML [See here](https://docs.oracle.com/javafx/2/fxml_get_started/why_use_fxml.htm#CHDCHIBE)
* Image [See here](https://docs.oracle.com/javafx/2/api/javafx/scene/image/Image.html)
* ImageView [See here](https://docs.oracle.com/javase/8/javafx/api/javafx/scene/image/ImageView.html)



## org.opencv.core Class Core

<https://docs.opencv.org/java/2.4.9/org/opencv/core/Core.html>

 

## org.opencv.core Class Mat



<https://docs.opencv.org/java/2.4.2/org/opencv/core/Mat.html>

 

## org.opencv.core Class MatOfPoint



<https://docs.opencv.org/java/2.4.7/org/opencv/core/MatOfPoint.html>

 

## org.opencv.core Class Point



<https://docs.opencv.org/java/2.4.2/org/opencv/core/Point.html>



## org.opencv.core Class Scalar



<https://docs.opencv.org/java/2.4.2/org/opencv/core/Scalar.html>



## org.opencv.core Class Size



<https://docs.opencv.org/java/2.4.2/org/opencv/core/Size.html>



## Class Imgproc



<https://docs.opencv.org/java/2.4.9/org/opencv/imgproc/Imgproc.html>



### Class VideoCapture



<https://docs.opencv.org/java/3.0.0/org/opencv/videoio/VideoCapture.html>



### Class Videoio 



https://docs.opencv.org/java/3.0.0/org/opencv/videoio/Videoio.html



# Steps to Detect Motion



### Black and white Conversion



![Black and White Converison](C:\Users\Vivek\Documents\bw.gif)



### Blurring the video to reduce noise if any

![](C:\Users\Vivek\Documents\blur.gif)



### Compute absolute Difference 

![](C:\Users\Vivek\Documents\diff.gif)

###  

### Calculate Threshold

![](C:\Users\Vivek\Documents\thresh.gif)



### Calculating and Drawing Contours

![](C:\Users\Vivek\Documents\contour.gif)



* If the area of the contour is more than the specified threshold it treats it as motion.