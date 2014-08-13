This Class is used for Detecting Motion in video files and 
draw a contour around the movement area, as well give a time stamp of the frame in the log file
some parts of this code was copied i want to thank anyone who uploaded opensource applications and they're actually the reason i'm doing this...
you'll find the full documentation on how to install and make it work on windows platform

tracking data represented in (x,y,minutes,seconds) comma separated to do any text analysis on it

Installing JavaCV on Windows

1.Install the runtime components of Microsoft Visual C++ 2010:

Microsoft Visual C++ 2010 Redistributable Package (x86)

Microsoft Visual C++ 2010 Redistributable Package (x64) 

2.Download OpenCV , version 2.4.8 as it’s the currently tested version I’m working on.

3.Run the installer executable. Extract it into the root directory C:\. It will create a folder C:\opencv.

4.Download the JavaCV binaries. As of fall 2012, version 0.7 works on our test machines (with OpenCV 2.4.8).

5.Unzip the JavaCV zipfile in some place that you'll remember (e.g., a CS10 folder). When you need to use JavaCV in a project, navigate to Project | Properties | Java Build Path | Libraries and click "Add External JARs...". Locate the JavaCV JAR files, select them, and click OK.

6.Set up your Path environment variable so that Eclipse can find the OpenCV libraries (which, from above, are in C:\opencv).

1.Right click on "Computer" in the Windows Explorer and select "Properties".

2.Click "Advanced system settings", go to the "Advanced" tab, and select "Environment Variables..."

3.In the "System variables" panel, go down to "Path" and select "Edit..."

4.Add to the end of the list (don't overwrite what's already there!), separated by semicolons, two folders — for OpenCV and Tbb (you can browse in the Windows Explorer to double check that these folders exist):

1.32 bit:
;C:\opencv\build\x86\vc10\bin;C:\opencv\build\common\tbb\ia32\vc10

2.64 bit:
;C:\opencv\build\x64\vc10\bin;C:\opencv\build\common\tbb\intel64\vc10

If you Faced problems with playing videos install these applications: FFmpeg: is a multimedia framework, able to decode, encode, transcode, mux, demux, stream, filter and play pretty much anything that humans and machines have created. It supports the most obscure ancient formats up to the cutting edge.

http://ffmpeg.org/download.html MinGW: provides a complete Open Source programming tool set which is suitable for the development of native MS-Windows applications, and which do not depend on any 3rd-party C-Runtime DLLs.

http://www.mingw.org/category/wiki/download 

Another helpful links:

http://docs.opencv.org/2.4/doc/tutorials/introduction/windows_install/windows_install.html

https://www.youtube.com/watch?v=9fSsbwey4j4

http://opencvlover.blogspot.com/2012/04/javacv-setup-with-eclipse-on-windows-7.html
