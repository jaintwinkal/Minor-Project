# Minor-Project
It is a Facial Recognition based Attendance system via Open cv 


openCV (Opensource Computer Vision)
-Python
-tkinter GUI 

How it works :
1) When we run train.py a window is opened and ask for Enter Id and Enter Name. 
2) After enter name and id then we have to click Take Images button. 
3) By clicking Take Images camera of running computer is opened and it start taking image sample of person.
4) This Id and Name is stored in folder StudentDetails and file name is StudentDetails.csv. 
It takes 60 images as sample and store them in folder TrainingImage.
5) After completion it notify that iamges saved.
6) After taking image sample we have to click Train Image button.
7) Now it take few seconds to train machine for the images that are taken by clicking Take Image button and creates a Trainner.yml file and store in TrainingImageLabel folder.
8) Now all initial setups are done. 
9) By clicking Track Image button camera of running machine is opened again. 
--> If face is recognised by system then Id and Name of person is shown on Image. 
--> Press Q(or q) for quit this window.
10) After quitting it attendance of person will be stored in Attendance folder as csv file with name, id, date and time.

Thanks.
