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
<p>3. Open the path <b>“C:\Users\JEEVIKA\newenv\Lib\site-ackages\labelImg\labelImg.py”</b>
<p>3. Open the path <b>“C:\Users\UserName\myenv\Lib\site-packages\libs\canvas.py” </b>, it is the path of the C-drive where virtual environment is created</p>





