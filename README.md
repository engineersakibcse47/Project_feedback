# Build Face Recognition Attendance System using Python

## Genarel Overview
This git repository contain a Face Recognition Attendance System using Python.
Face recognition systems can be implemented by using facial characteristics as biometrics. Attendance tracking is the most difficult task in any organization. Face recognition is a biometric technique that determines whether the image of a person’s face matches any of the face images stored in a database.

The primary goal was of this project is to build a face recognition-based attendance monitoring system for employees working in an organization in order to improve and upgrade the current attendance system to make it more efficient and effective than before. The employee should be in an area containing light so that the detection can be clearly made.

The facial recognition feature embedded in the attendance monitoring system not only ensures accurate attendance but also eliminates flaws. Using a system to overcome defects not only saves resources but also reduces human intervention in the overall process by delegating all complex tasks to the system.

### Prerequisites
The installation process for this project is a bit more than usual. First I download a C++ compiler. I tried installing Visual Studios. I
downloaded the community version for free from their website (https://visualstudio.microsoft.com/downloads/). Once the installer I
run it and select the ‘Desktop development with C++’.
The download and installation took some time as it is a few Gbs.
After completing and restarting the computer, I head on to Pycharm project. Here, I install the required packages. Below is the list.
- cmake 
- dlib 
- face_recognition 
- numpy opencv-python 
- Install pybuilder pip install pybuilder
- Build the project pyb publish

[Here](https://github.com/engineersakibcse47/Project_feedback/blob/main/requirement.txt) is my requirement file.

## Project Documentation (Still Working)

###  Git
I used Git to frequently commit and push my code to GitHub. I also used GitHub action for continuous delivery. My git times can be seen at the [Github Contribution](https://github.com/engineersakibcse47) in GitHub. 

###  Unified Model Language (Still Working On it)

For the UML diagrams I decided to show 4 different diagram but for now, I chose to present the following two:

- [Use case diagram](https://github.com/engineersakibcse47/Project_feedback/blob/main/tasks) displays the different real world problems the software should fulfill next
to the different users of this software.
- [Sequence diagram](https://github.com/engineersakibcse47/Project_feedback/blob/main/tasks) displays the different real world problems the software should fulfill next to the different users of this software.

### Build Management

For build management I had used pybuilder, which is a powerful tool when using python. It is the first time that I configured a build management tool myself. You can find 3 files created for this purpose:

- Build file [build.py](https://github.com/engineersakibcse47/Project_feedback/blob/main/build.py) 
- Setup file [setup.py](https://github.com/engineersakibcse47/Project_feedback/blob/main/setup.py) 
- toml file [pyproject.tolm](https://github.com/engineersakibcse47/Project_feedback/blob/main/pyproject.toml) 

### IDE

I had used PyCharm 2022.2.4 (Community Edition) using Anaconda Python 3.8 as interpreter. I find very useful to use it this way for an easier environment and package management even if I deside to use other tools like Jupyter Notebook or Google collab, Anaconda as interpreter will save time not having to install save packages everywhere. The integration with Git using this IDE was straight forward and I was able to commit, pull and push updates without facing an issue, would be interesting to start trying it with multiple branches for more complex project.
Another feature I like very much about this IDE, is the new package manager for PyCharm that allows you to install and update packages within few click, no pip is needed. My most used shortcuts are:

- Ctrl + K to show commit window
- Ctrl + Shift + C to cpy document path
- Alt + Shift + F9 to run selected

Full short-cut list could be found [Here](https://resources.jetbrains.com/storage/products/pycharm/docs/PyCharm_ReferenceCard.pdf)

