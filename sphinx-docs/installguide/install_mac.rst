Mac Installation Guide
===========================

Macintosh installation uses the command line, but if you follow the instructions carefully, you should have no problem installing KA Lite. KA Lite uses the `git` program to distribute its software to developers and other users.

1. Download and install `Python 2.7.9 <https://www.python.org/downloads/mac-osx/>`_ for Mac

.. warning:: Even if Python is already installed on your Mac by default, it is *highly* recommended that you ensure you are using the latest version. Using older versions of Python with KA Lite can result in errors.

2. You need to open the Terminal app. There are many ways to do this. We suggest the following:
	* Click the magnifier icon on the upper right corner and search "terminal".
	* Press *'Enter'* with the "Terminal" app selected and it should open.
3. In the Terminal, enter *Python -V* and press *'Enter'*. **The version number should reflect the Python version you just installed.**
4. Create the folder where you would like to install KA Lite.
	* In the Terminal, type *cd* and then drag the folder you created into the Terminal.
	* This will copy the path name into the Terminal window.
	* Press *'Enter'*.
5. Now you can copy and paste this command into the terminal and press *'Enter'*.
	* *git clone https://github.com/learningequality/ka-lite.git*
6. Once it finishes downloading, enter *cd ka-lite* to move into the folder that was just downloaded.
7. To begin installation enter *./bin/kalite manage setup*
8. During installation, you will be prompted to make an Admin account. Go ahead and follow along with the instructions.
9. To begin running the server.
	* Enter *./bin/kalite start*	
10. KA lite should be accessible from http://127.0.0.1:8008/
	* Replace *127.0.0.1* with the computer's external IP address or domain name to access it from another computer.
	

**Using KA-Lite Monitor App.**

Download and install `KA-Lite Monitor.dmg` probably from this source: *https://learningequality.org/downloads/ka-lite/0.14/content/*.

**Launching the KA-Lite Monitor**

1. Launch KA-Lite Monitor from the application
2. Enter Username and Password from the preference dialog.
3. Click on the `KA-Lite icon` and then `Start Ka Lite menu`
4. Click on `Open in Browser`, this will load the KA Lite in browser.

