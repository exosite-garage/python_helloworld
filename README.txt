========================================
About
========================================
python_helloworld.py is a simple python script that demonstrates how to send data to
the Exosite over HTTP.  

License is BSD, Copyright 2011, Exosite LLC

Built/tested with Python 2.6.5

========================================
Quick Start
========================================
****************************************
1) install python
****************************************
http://www.python.org/download/
http://www.python.org/download/releases/2.6.5/
http://www.python.org/ftp/python/2.6.5/python-2.6.5.msi

****************************************
2) test it out
****************************************
edit python script "python_helloworld.py" 
--) update the default device CIK -> Get your CIK (KEY) from your Portals account
--) add two data sources to your device in your portals account
-----) Data Source 1 should be called 'message', type is string, resource is 'message'-----) Data Source 2 should be called 'number', type is integer, resource is 'number'
--) run the script (> python python_helloworld.py)
--) verify the app connects, sends data (no errors should be generated, should see 204 Response), and reads the data back (number = 1, message = hello world!)
--) log into exosite.com and verify the data sources were updated

****************************************
3) tweak it
****************************************
--) add a 'print' command or something 
--) play around, use it, extend it!
