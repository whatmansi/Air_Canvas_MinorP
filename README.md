The project focuses on developing a motion-to-text converter that can potentially serve as software for intelligent wearable devices for writing from the air. This project is a reporter of occasional gestures. It will use computer vision to trace the path of the finger. The generated text can also be used for various purposes, such as sending messages, emails, etc. It will be a powerful means of communication for the deaf. It is an effective communication method that reduces mobile and laptop usage by eliminating the need to write. 


Explain to me like I am 5
Bead setup, setup for blue here, mask->contour->center detect->coordinates are stored
Wherever the blue colour is tracked, a mask is created there in that black screen using cv2.inRange function
The centre of the bead is calculating the coordinated of the bead and deciding whether the colour needs to be changed or draw 
Those rectangles depicting colours are buttons reserved for changing colours
