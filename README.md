# Software Engineering Virtual Experience :walking:

![0001](https://user-images.githubusercontent.com/89456649/166150516-79bb1826-a7b9-4c9e-bbec-e6aa4160eb90.jpg)

## Tasks
<br />

<b>Task 1:</b> Interface with a stock price data feed 
</br>
* Clone the "JPMC-tech-task-1-py3" repository using this command:
<pre>
git clone https://github.com/insidesherpa/JPMC-tech-task-1-py3.git
</pre>

* Follow the Python 3 Installation Guide on Windows: https://phoenixnap.com/kb/how-to-install-python-3-windows. Once installation is completed successfully, execute this command on the command prompt:
<pre>
python --version
</pre>

* For local setup, run the command prompt as <i>Administrator mode</i> on two different window and run this command to start server and client script at the same time and you should get something similar to the pic below:
<pre>
cd JPMC-tech-task-1-py3
python server3.py
python client3.py
</pre>
![image](https://user-images.githubusercontent.com/89456649/166102697-2e5eff89-8002-45e9-a3a8-8d5b8ad86b49.png)
* Make Changes to code using VSCode or SublimeText editor in 'Client3.py' in three areas.
* Write Unit test cases in 'client_test.py' and add more unit tests
<pre>
for quote in quotes:
self.assertEqual(getDataPoint(quote), (quote['stock'], quote['top_bid']['price'], quote['top_ask']['price'], (quote['top_bid']['price'] + quote['top_ask']['price'])/2))
</pre>
* Make a patch file by using this command:
<pre>
cd JPMC-tech-task-1-py3
git init
git add -A
git config user.email "your_email_address"
git config user.name "your_name"
git commit -m 'Create Patch File'
git format-patch -1 HEAD
</pre>
* Share the patch file on the right module page
<br/>
<b>Task 2:</b> Use JPMorgan Chase frameworks and tools

* Clone the "JPMC-tech-task-2-py3" repository using this command:
<pre>
git clone https://github.com/insidesherpa/JPMC-tech-task-2-py3.git
</pre>
* Start the server application in one terminal using this command:
<pre>
cd JPMC-tech-task-2-PY3
python datafeed/server3.py
</pre>
* For local setup, install the other remaining dependencies i.e. Node and Npm. To install node and npm and be able to manage versions seamlessly you will install NVM (node version manager) from https://github.com/coreybutler/nvm-windows and then run the command prompt as <i>Administrator mode</i> and you should get something similar to the pic below:
<pre>
nvm install latest
</pre>
![image](https://user-images.githubusercontent.com/89456649/166103492-36e3570c-37f9-4d99-947d-468a19179b24.png)
</br>Type 'nvm use 18.0.0', the version may update and check the nvm list use this command:
<pre>
nvm list
</pre>
Once installation is completed successfully, execute this command on the command prompt:
<pre>
node -v
npm -v
</pre>
![image](https://user-images.githubusercontent.com/89456649/166104012-0109dc2e-c1b1-4870-af54-9015275b89e7.png)
* Install Visual C++ Build Tool and select "Visual C++ build tool" to install, then run this on command prompt:
<pre>
npm config set msvs_version 2017
npm install
npm start
</pre>
It'll open index page called 'Bank & Merge Co Task 2" in a localhost portal 3000  :tada:, then click the <b>'Start Streaming Data'</b> button as shown below:  
![image](https://user-images.githubusercontent.com/89456649/166106636-d4e3761e-e7de-4a08-bd50-2d25ee983a39.png)
* Time to open VSCode to alter the 'App.tsx' to the client side react application, make changes in 'App.tsk' in three areas and make changes in 'Graph.tsk'. Refresh the website and click <b>'Start Streaming Data'</b> button :tada: as shown below:
![image](https://user-images.githubusercontent.com/89456649/166136593-32291ab2-2487-4baa-9301-1313fad69756.png)
* Create a patch file by following this command:
<pre>
cd JPMC-tech-task-2-PY3
git add -A
git config user.email "your_email_address"
git config user.name "your_name"
git commit -m 'Create Patch File'
git format-patch -1 HEAD
</pre>
* Share your patch file on the right module page
</br>
<b>Task 3:</b> Display data visually for traders

* Clone the "JPMC-tech-task-3-py3" repository using this command:
<pre>
git clone https://github.com/insidesherpa/JPMC-tech-task-3-py3.git
</pre>
* Start the server application in one terminal using this command:
<pre>
cd JPMC-tech-task-3-py3
python datafeed/server3.py
</pre>
* For the local setup, use these commands and if you go through an error, then follow the <a href="https://github.com/NipaDasGupta/TechTask/blob/main/Error%20Guide.md">Error Guide.md</a>:
<pre>
cd JPMC-tech-task-3-py3
npm start
</pre>
* Time to open VSCode to alter the 'Graph.tsx' to the client side react application, make changes in 'Graph.tsk' in three areas and make changes in 'DataManipulator.ts'. Refresh the website and click <b>'Start Streaming Data'</b> button :tada: as shown below:
![image](https://user-images.githubusercontent.com/89456649/166147077-00b02e7d-3521-4951-a57b-2a6189906a72.png)
* Submit your patch file on the right module page
<br/> 
<p align="center">
<a href="https://www.insidesherpa.com/virtual-internships/prototype/R5iK7HMxJGBgaSbvk/Technology%20Virtual%20Experience" target="_blank">
<img src="https://insidesherpa-assets.s3-ap-southeast-2.amazonaws.com/icons/jpmorgan/github+repo+images/jpmc+github+img.png">
	</a>
</p>

<p align="center"> 
	<b><a href="#task">Task Overview</a></b>
	|
	<b><a href="#installation">Installation Instructions</a></b>
	| 
	<b><a href="https://www.insidesherpa.com/modules/R5iK7HMxJGBgaSbvk/88AisH7iuw3L5N5ig" target="_blank">Link to Module 2</a></b>

<h1> Introduction</h1> 
<b> Experience Technology at JP Morgan Chase </b>
<p>Try out what real work is like in the technology team JP Morgan Chase. Fast track to the tech team with your work.</p>

<h2 id="task"> Module 2 Task Overview </h2>
<p>Use JP Morgan Chase's frameworks and tools
Implement JP Morgan Chase’s Perspective open source code in preparation for data visualization</p>
<p> <b>Aim:</b>Take an incomplete setup of Perspective, i.e. a graph that updates manually, and make it work with the code from Task 1 such that it now updates automatically by continuously requesting from the server application</p>

<ol>
	<li>Please clone this repository to start the task</li>
	<li>[goal-a] In the client application, observe that when new data feed is retrieved whenever you click the 'Start Streaming Data' button, the previous entry is re-entered into the table. Update the application so that the table does not have duplicated entries</li>
	<li>[goal-b] We also want the react app to keep continuosly requesting data from the python server. Currently, the data feed is called only once every time the 'Start Streaming' button is clicked. Change the application to continuously query the datafeed every 100ms when the 'Start Streaming' is clicked.</li>
	<li>[goal-c] Currently, the Perspective element only shows the data in table view after the data loads. Add Perspective configurations so that when the data is loaded, it shows the historical data of ask_price ABC in the Y line chart.</li>
	<li>Upload a git patch file as the submission to this task</li>	
</ol>

<h2 id="installation" >Set up / Installation</h2>
<p>In order to get the server and client application code working on your machine, <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/setup_devenv_m2_v8.pdf">follow the setup here</a></p>

<p><b>Note</b>:This is the version of the JPM 2 exercise that uses Python 3. The Python 2.7 version is in <a href="https://github.com/insidesherpa/JPMC-tech-task-2">this other repo</a></p>

<h2>How to Run</h2>

<p>Similar to Task 1, start the data feed server by running the python server.</p> 
<p>Make sure your terminal / command line is in the repository first before doing any of this.</p>
<p>If you are using Windows, make sure to run your terminal/command prompt as administrator.</p>

<code> python datafeed/server3.py </code>

If you encounter an issue with `datautil.parser`, run this command: 

	pip install python-dateutil

If you don't have pip, you can install it from: https://pip.pypa.io/en/stable/installing/

Run <code>npm install && npm start</code> to start the React application.

It's okay to have audit warnings when installing/running the app.

If you don't have `npm` (although you should if you followed the set up / installation part), you can install the recommended version alongside NodeJS from: https://nodejs.org/en/

The recommended version are node v11.0.0 and npm v6.4.1

Open http://localhost:3000 to view the app in the browser. The page will reload if you make edits.


<h2>Known Issues</h2>
Some users seem to be having trouble with the unzipped version of the node_modules back up for windows. 
This is the alternative unzipped version:
https://drive.google.com/drive/folders/1wzIlt-OeiK6nYEHidsOGlpJ_KmeoPVXz

Note: You may need to (hard) refresh the link to the public gdrive to see all of the files/folders e.g. @jpmorganchase/perspective as it takes gdrive a bit to load them for you.


<h2>How to fix the code to meet the objectives</h2>
<p>To make the changes necessary to complete the objectives of this task, <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/making_changes_m2_v2.pdf">follow this guide</a>.</p>

<h2>How to submit your work</h2>
<p>A patch file is what is required from you to submit.
