Description:
------------

This a complete and fully working Viola-Jones face detection algorithm
described in VHDL and verified on the DE2-115 FPGA board.

The work was done during 2015-2016 by a team of students (Peter Irgens, 
Curtis Bader, Theresa Le, and Devansh Saxena) under the supervision of 
Cristinel Ababei.


Target audience:
----------------

We would like to emphasize that the target audience of this design 
includes educators, researchers, and industry practitioners who have 
the minimum necessary background on digital logic design and HDL 
programming. In this context, this design can be used to develop new 
laboratories that deal with image processing concepts and can use this 
design as a platform to showcase the face detection algorithm or to 
verify new ideas. The design can be extended or integrated in larger 
systems for research purposes on computer vision topics as well. 
Practitioners can use it for practical applications too. 


Contents of this repository:
----------------------------

1) RADME.txt
This file.

2) faceDetectSystem_2p3_320x240.zip
A .zip archive of the Quartus II 15.1 project directory.
This includes all VHDL source files as well as the user constraints file.
The user constraints file provides information on how to connect the OV7670
camera module to the general purpose IOs on the board.

3) E50FinalReport.pdf
This is the final report that the team wrote. It provides details on the
design process as well on testing and verification.
