This repo Consists of the projects that I did while learning basic opencv
1. Motion Detection
  The program first subtracts the second frame from the first then stores the absolute values then Canny Edge detection is used
  to find the edges in the frames. Then using findContours function countours are found out. If no contours are found then 
  movement is not detected otherwise movement is detected. The contours are then plotted over the frame and and then the process 
  is repeated.
