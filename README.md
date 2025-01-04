## PHRED Website Development
https://docs.google.com/document/d/1_9ShMT8Ah8ff6_XU04NfC5TPUSU-idwoa5sfJSm06UE/edit?usp=sharing

## How to Make Changes to the PHRED Website

# Download Visual Studio Code
Visual Studio Code (more commonly, VSCode) is a free code editor. It is an industry standard with support for many different coding languages and tools.

  Go to https://code.visualstudio.com/download.
  Click on the large button under your OS (for example, if you are on Windows, click on the button indicated in red by the image below).


# Install Visual Studio Code
Your download should appear in the top right corner of your web browser

  Double-click on the download for VSCodeUserSetup to start the installation.
  Click the option to Accept if you agree to the Microsoft software license terms.
  Continue with the installation accepting the default options and then click Install.
  Once installed, you can run VSCode by searching for the app on your computer or running it from the desktop.



# Get PHRED Website code from GitHub
GitHub is a website where people can work together on projects, especially for writing code or creating software. More technically, it’s version control software for managing code and code changes. 

  To see the PHRED website code, go to https://github.com/PHREDRobotics/phred-website
  In GitHub terms, the PHRED website code is stored in its own repository.
  The Home page of the website is created with the file, index.html.
  Other website pages for PHRED are listed as well (for example, about.html and contact.html)
  Feel free to double-click on the files or folders within the PHRED website in GitHub to explore the code.
  To download the PHRED website code, return to VSCode
  On the top menu, select View, then select Terminal. 
  In the Terminal window, confirm that your current directory is your User directory
  If on windows, you will see something like this: 
  C:\Users\your-user-directory> 
  If you don’t, you can get to this directory by type the following two commands into the terminal and press ENTER after each:
  cd C:\Users\
  dir
  Your user directory should be listed under name. When you find it, type cd followed by the name into the terminal and press ENTER:
   cd your-user-directory
  Now that you are in your user directory, type the following in the Terminal window and press ENTER.
  git clone https://github.com/PHREDRobotics/phred-website.git

		When it is done, you’ll have the PHRED website code on your own computer.
  Open the PHRED website code Visual Studio Code
  On the top menu, select File, then select Open Folder… 
  Find the folder called phred-website. This should be in your user directory.
  If you are on Windows and you can’t find it, you can type C:\Users and select your user directory. The phred-website should be in that location
  Select the phred-website folder and click Select Folder
  If successful, you will see the same files that were on GitHub. Feel free to explore the files. This is a copy of the code from GitHub and nothing you change here will affect the official PHRED website (at least not yet! 😉)
  To see the the website on your computer
  In the Explorer section, right click on the file index.html
  Select Copy Path
  Open a web browser (like Google Chrome or Firefox)
  Paste the path that you copied into the search bar of the browser (it should look something like this: C:\Users\your-user-directory\phred-website\index.html
  If successful, you will be able to navigate around the site in your browser.

# Make a change to the PHRED website code Visual Studio Code
  In the Explorer section, click on the file index.html
  Press CTRL+f to find some text
  Type “Gear up!” in the Find text dialog and press ENTER
  When you find the first place where Gear up!” is mentioned, replace it with your name
  Press CTRL+s to save the index.html file
  Return to your web browser, and click refresh to see the change on the home page

# Resources for learning HTML
  W3Schools: https://www.w3schools.com/html
  W3Schools Video Tutorial: https://www.w3schools.com/videos/index.php
  HTML.com: https://html.com



