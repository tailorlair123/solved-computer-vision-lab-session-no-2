Download Link: https://assignmentchef.com/product/solved-computer-vision-lab-session-no-2
<br>






<h1>Image filtering and Fourier Transform</h1>




The following items are the steps that you have to do in this lab session:




<ol>

 <li>Add Gaussian (standard deviation=20) and salt &amp; pepper (density=20%) noise to the provided images:

  <ul>

   <li>display the images, the noisy images, and their histograms.</li>

  </ul></li>

</ol>




<ol start="2">

 <li>Remove the noise by using a moving average, a low-pass Gaussian filter and a median filter:

  <ul>

   <li>use two different spatial supports: 3×3 pixels and 7×7 pixels; o display the filters by using <em>imagesc()</em> and <em>surf()</em>; o display the resulting images and their histograms.</li>

  </ul></li>

</ol>




<ol start="3">

 <li>Implement the slides 41-45 “practice with linear filters”:

  <ul>

   <li>use filters with a spatial support of 7×7 pixels. o display the filters by using <em>imagesc()</em> and <em>surf()</em>; o display the resulting images.</li>

  </ul></li>

</ol>




<ol start="4">

 <li>Apply the Fourier Transform (FFT) on the provided images:

  <ul>

   <li>display the magnitude (log) of the transformed images;</li>

   <li>display the magnitude of the transformed low-pass Gaussian filter (spatial support of</li>

  </ul></li>

</ol>

101×101 pixels with sigma=5); o display the magnitude of the transformed sharpening filter, slide 44 (the filter has a spatial support of 7×7 pixels, copy it in the middle of a zeros image of 101×101 pixels).







<strong>Notes: </strong>

<ul>

 <li>You have to write a report that describes your work and the obtained results (please include the figures). In the report you must indicate all the surnames of the participants (not other names, e.g. the teachers).</li>

 <li>About the code:

  <ul>

   <li>You have to use relative paths.</li>

   <li>You have to write and use functions.</li>

   <li>You have to provide us a main script to test your code.</li>

  </ul></li>

 <li>The code must be uploaded as M-files. All the files (M-files, images, and report) have to be compressed in a single file named “surnames_labxx.zip/tgz” (all the surnames of the participants have to be indicated), and then the compressed file has to be uploaded.</li>

</ul>





