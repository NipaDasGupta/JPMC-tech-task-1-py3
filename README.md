# Software Engineering Virtual Experience Walkthrough

blah blah blah
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
![image](https://user-images.githubusercontent.com/89456649/166106268-4149b2c6-48fa-4f80-8c86-a3c04f811386.png)
