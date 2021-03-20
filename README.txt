Hunter Lee: April 30th 2019
Version: Final Thesis proof of concept

In order to get the full experience, you must first set up these files in your IDE
(Eclipse may work best, but I haven't tested with others)
-bin
-resources
-src
 (The tutorial under appendix a of the thesis paper may help with set up,
 if you run into issues, follow that guide and then copy/paste the Main.java code in)

After this, you should be able to run Main.java which will take care of the speech
recognition and transcription. This should produce a .txt file for the input of the
JFlex/Cup portion of the program.

Once you have this file, download the LexLab folder and place it inside. You should
then be able to run it (apache-ant-1.9.6/bin/ant run) and it will parse through the
file and return an error or a completed parse.
