What is this?

This web application is a tutorial to help familiarize WVU students with Linux, and it goes over several of the basic
commands that deal with navigation, creating/manipulating files, and managing processes in the terminal. It was made
specifically to be used with the LOUD virtual machine provided by WVU, and screenshots and examples in the website are
based on it. This web application includes code that was modified from M.Stonebank@surrey.ac.uk.

As of April 2021, all modifications to the original source code were performed by Kollin Labowski as part of an Honors
Contract assignment for CYBE 366 at West Virginia University.

-----------------------------------------------------------------------------------------------------------------------

This web application was made using 8 different HTML files as follows:

index.html - The landing page for the site that allows the user to navigate to any of the sections of the tutorial

intro.html - The HTML page containing the introduction to Linux (used with screenshots in Intro folder)

tutorial1.html - The HTML page containing the first chapter of the tutorial (used with screenshots from P1 folder)

tutorial2.html - The HTML page containing the second chapter of the tutorial (used with screenshots from P2 folder)

tutorial3.html - The HTML page containing the third chapter of the tutorial (used with screenshots from P3 folder)

tutorial4.html - The HTML page containing the fourth chapter of the tutorial (used with screenshots from P4 folder)

tutorial5.html - The HTML page containing the fifth chapter of the tutorial (used with screenshots from P5 folder)

tutorial6.html - The HTML page containing the sixth chapter of the tutorial (used with screenshots from P6 folder)

-----------------------------------------------------------------------------------------------------------------------

Ideas for future implementation:

- Include a section demonstrating how to compile/run code in the terminal. See the P7 folder for example images for
  C, Java, and Python programming in terminal. These images may be used if more sections are added to the tutorial,
  however new images could be produced instead.

- Perhaps include a section on text editors (moving the current VIM section to there would make sense), and go more
  in depth on how to use them. In addition to VI/VIM, EMACS and NANO could be covered potentially.

- Could include a more advanced section on creating and terminating processes, particularly child processes created
  using the fork system call. This would not really make sense unless a full coding section is included though, so
  perhaps not the most realistic addition.

- Include a section on administrative permissions (root user/sudo command). Also could describe what can be found in
  various directories on a Linux machine (such as /etc or /usr).