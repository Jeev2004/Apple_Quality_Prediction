<h1>
  LabelImg Installation and Working
</h1></br>

<h3>
  Prerequisites
</h3>
<p>1. Install python (version: 3.10.11)</p>
<p>2. Install virtual environment with command <b>‘pip install virtualenv’</b> (version: 20.24.6)</p></br>

<h3>
  Setting Up Virtual Environment
</h3>
<p>1. Create a folder in which all tasks will be carried out.</p>
<p>2. Open the folder in Command prompt.</p>
<p>3. Create a virtual environment with command <b>‘py -m venv myenv’</b> (myenv is the name of the virtual environment</p>
<p>4. Activate virtual environment with command <b>‘myenv\Scripts\activate’</b></p>
<p>5. The virtual environmaent has been created successfully and setup, further packages and any necessary installations can be made inside the virtual environment.</p>
<p><b>NOTE : </b>Make sure to activate virtual environment before installing any packages (step 4)</p></br>

<h3>
  LabelImg Installation
</h3>
<p>1. Once the virtual environment has been activated, run the command <b>‘pip install labelImg’</b> to install Labelimg (Note : The cases need to be same as mentioned).</p>
<p>2. Then run the command <b>‘pip install setuptools’</b></p>
<p>3. Then run the command <b>‘LabelImg’</b></p>
<p>4. If labelimg throws an error, 'package disutils not founf' while running, run <b>'pip install disutils'</b></p>
<p>5. Labelimg has been installed successfully, it can be accessed by running the command ‘labelImg’</p>
<p><b>NOTE : </b>Make sure to activate virtual environment before running Labelimg</p></br>

<h3>
  LabelImg Setup
</h3>
<p>1. While running, the bounding boxes in the library of LabelImg was in float type and is required to be an integer.</p>
<p>2. Typecasting of float into int needs to be done using int(x). Where x is the information that needs to be Typecasted.</p>
<p>3. Open the path <b>“C:\Users\JEEVIKA\myenv\Lib\site-ackages\labelImg\labelImg.py”</b> ,it is the path of the C-drive where virtual environment is created</p>
<p>4. Typecast line 965 to int()</p>
<p>5. Open the path <b>“C:\Users\UserName\myenv\Lib\site-packages\libs\canvas.py” </b></p>
<p>6. Typecast lines 526, 530 and 531 to int()</p>
<p>7. Run command <b>'labelImg'</b></b></p>

<h3>
  Annotation and Labeling
</h3>
<p>1. Open Labelimg</p>
<p>2. Select <b>'Open Dir'</b> and select the folder in which the dataset exists</p>
<p>3. Create a folder to save annotations</p>
<p>4. To save labeled annotations, select <b>'Change Save Dir'</b> and select the folder in which labels need to saved</p>
<p>5. When the folder opens make sure that <b>'yolo'</b> is selected as saving format (It provides labels as .txt format which can further be used for training the model)</p>
<p>6. To make sure the labels are in the required order, pick an image that has all the classes existing in that image and label them in order</p>
<p>7. Once all labels are annotated for the first time, other images can be labeled with pre-existing labels by selecting the labels accordingly during annotation</p>
<p>8. Continue the same procedure for all images. One or more labels can be added in the same image.</p>
<p><b>Note : Go to your annotations file and check if the labels are in .txt format</b></p></br>

<h3>
  File Tree
</h3>
<p>--> Yolo requires three set of data, Train, Test and Validation</p>
<p>--> The images and labels need to be ordered in such a format only</p>
<p>The file tree is as follows :</p>
<pre>Folder_name
|__ dataset
    |__ train
        |__ images
        |__ label
    |__ test
        |__ images
        |__ label
    |__ valid
        |__ images
        |__ label
    |__ data.yaml</pre>
  </br>
  <p><b>Note :</b> 10 – 20 % of total data goes for validation</p>






