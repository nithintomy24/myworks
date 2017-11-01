 To automatically download and install Oracle Java JDK6 / JDK7 / JDK8 from oracle website
 
 To get started:

Press Ctrl+Alt+T on your keyboard to open a terminal window. When it opens, copy and paste the command below and hit enter. Input your user password when prompts and it will add the PPA repository into your system.

sudo add-apt-repository ppa:webupd8team/java
After that, update package lists via:

sudo apt-get update
To install Oracle Java 8, run:

sudo apt-get install oracle-java8-installer
Change the number 8 to 6 (or 7) in the code to install Java 6 (or 7).

While installation, you’ll be asked to agree the license and then the installer start downloading Java file from oracle website and install it on your system.

To set the default Java, run:

sudo apt-get install oracle-java8-set-default
Also change number 8 to the Java version you want.

Finally check whether everyting is OK:

java -version
