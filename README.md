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

* For local setup, run the command prompt as <i>Administrator mode</i> on two different window and run this command to start server and client script at the same time:
<pre>
cd JPMC-tech-task-1-py3
python server3.py
python client3.py
</pre>

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
