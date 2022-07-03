# Tensorflow Object Detection Walkthrough
<p>This set of Notebooks provides a complete set of code to be able to train and leverage your own custom object detection model using the Tensorflow Object Detection API. This accompanies the Tensorflow Object Detection course on my <a href="https://www.youtube.com/c/nicholasrenotte">YouTube channel</a>. 
<img src="https://i.imgur.com/H3tUyKM.png">

## Steps
<br />
<b>Step 1.</b> Clone this repository: https://github.com/abidash2017331544/Realtime-number-plate-Detection.git
<br/><br/>
<b>Step 2.</b> Create a new virtual environment 
<pre>
python -m venv anprsys
</pre> 
<br/>
<b>Step 3.</b> Activate your virtual environment
<pre>
.\tfod\Scripts\activate # Windows 
</pre>
<br/>
<b>Step 4.</b> Install dependencies and add virtual environment to the Python Kernel
<pre>

pip install ipykernel
python -m pip install --upgrade pip
python -m ipykernel install --user --name=anprsys

</pre>
<br/>
<b>Step 5.</b>  ensure you change the kernel to the virtual environment as shown below
<img src="https://github.com/abidash2017331544/Realtime-number-plate-Detection/blob/main/Screenshot%202022-07-03%20233459.png"> 
<br/>
<b>Step  6.</b> Begin training process by opening <a href="https://github.com/abidash2017331544/Realtime-number-plate-Detection/blob/main/Training%20and%20Detection.ipynb">Training and Detection.ipynb</a>, this notebook will walk you through installing Tensorflow Object Detection, making detections, saving and exporting your model. 
<br /><br/>
<b>Step 7.</b> During this process the Notebook will install Tensorflow Object Detection. You should ideally receive a notification indicating that the API has installed successfully at Step 8 with the last line stating OK.  
<br /> <br/>
<b>Step 8.</b> Once you get to step 6. Train the model, inside of the notebook, you may choose to train the model from within the notebook. I have noticed however that training inside of a separate terminal on a Windows machine you're able to display live loss metrics. 
<br />
