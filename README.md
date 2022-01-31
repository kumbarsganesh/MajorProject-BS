# MajorProject-BS
Detection of Impersonators in Examination Hall

------------------------------------------------------------------------------------------------
Detecting Impersonators in Examination Centres using AI


Abstract:
Detecting impersonators in examination halls is important to provide a better way of examination handling system which can help in reducing malpractices happening in examination centers.  According to the latest news reports, 56 JEE candidates who are potential impersonators were detected by a national testing agency. In order to solve this problem, an effective method is required with less manpower. With the advancement of machine learning and AI technology, it is easy to solve this problem. In this project we are developing an AI system where images of students are collected with names and hall ticket numbers are pre-trained using the KDTree algorithm and the model is saved. Whenever a student enters into classroom, the student should look at the camera and enter class, after the given time or class is filled with student’s information will store in a video file with student name and hall ticket no . The video will have a user with hall ticket no and name on each face. If admin finds any unknown user tag on face admin can recheck and trace impersonators.
 

Problem statement:
Detecting impersonators in examination halls is important to provide a better way of examination handling system which can help in reducing malpractices happening in examination centres.  According to the latest news reports from times of India 56 JEE candidates who are potential impersonators was detected by national testing agency.

Existing system:
		Information given in the hall ticket is used as verification to check if student is exact person or not.  Manual security checks are performed with are not perfect and some time  students can change image from hall ticket.
     
Disadvantages:
           Manual verification methods are used for checking personally for each student which is not possible to check each student personally. 
	 Chances of changing images from hall ticket is possible which doesn’t have verification method.
Proposed system:
In proposed system initially images of each student are collected and each dataset consists of 50 images of each student. These images are trained using kdtree algorithm using image processing technique and model is saved in system this model can be used for automatic prediction of student in exam halls from live video or images.

Advantages:
Student verification process is fast and accurate with least effort. Reduces impersonators issue with live verification.
Time taken for prediction and processing is less and prediction done automatic using trained model. 
Trained model can be used to track live video and automates process of detecting students at exam centers and display in video.

 

SOFTWARE HARDWARE REQUIREMENT:
HARDWARE REQUIREMENTS: 
System		 : Pentium IV 2.4 GHz. 
Hard Disk 	 : 100 GB. 
Monitor	 : 15 VGA Color. 
Mouse		 : Logitech. 
RAM		 : 1 GB. 

5.1.2 SOFTWARE REQUIREMENTS:
Operating system 	: 	Windows XP/7/10
Coding Language	: 	python
Development Kit         	 anaconda
Library			:     keras, OpenCV
 Dataset 		:   any student’s dataset

REFERENCES:

T.-H. Kim, D.-C. Park, D.-M. Woo, T. Jeong, and S.-Y. Min, “Multi-class classifier-based adaboost algorithm,” in Proceedings of the Second Sinoforeign-interchange Conference on Intelligent Science and Intelligent Data Engineering, ser. IScIDE’11. Berlin, Heidelberg: Springer-Verlag, 2012, pp. 122–127.
[3] P. Viola and M. J. Jones, “Robust real-time face detection,” Int. J. Comput. Vision, vol. 57, no. 2, pp. 137–154, May 2004. 
[4] P. Viola and M. Jones, “Rapid object detection using a boosted cascade of simple features,” in Proceedings of the 2001 IEEE Computer Society Conference on Computer Vision and Pattern Recognition. CVPR 2001, vol. 1, Dec 2001, pp. I–I. 
[5] J. Li, J. Zhao, Y. Wei, C. Lang, Y. Li, and J. Feng, “Towards real world human parsing: Multiple-human parsing in the wild,” CoRR, vol. abs/1705.07206. 
[6] A. Krizhevsky, I. Sutskever, and G. E. Hinton, “Imagenet classification with deep convolutional neural networks,” in Advances in Neural Information Processing Systems 25, F. Pereira, C. J. C. Burges, L. Bottou, and K. Q. Weinberger, Eds. Curran Associates, Inc., 2012, pp. 1097–1105.
