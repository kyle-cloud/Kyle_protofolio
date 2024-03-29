# Kaggle

**[1. Titanic - Machine Learning from Disaster](https://www.kaggle.com/kylecloud/titanic-top4percent)**

The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew. While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others. In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

- Achieved Top 4% by exploring Feature Engineering in depth for the data and ensembled different pipelines to predict which passengers survived the Titanic shipwreck with an accuracy of 83.25%.
- Tools: Python, Scikit_learn, Xgboost

**[2. Cassava Leaf Disease Classification](https://www.kaggle.com/kylecloud/cassava-leaf-disease-top11percent)**

As the second-largest provider of carbohydrates in Africa, cassava is a key food security crop grown by smallholder farmers because it can withstand harsh conditions. At least 80% of household farms in Sub-Saharan Africa grow this starchy root, but viral diseases are major sources of poor yields. With the help of data science, it may be possible to identify common diseases so they can be treated. Your task is to classify each cassava image into four disease categories or a fifth category indicating a healthy leaf. With your help, farmers may be able to quickly identify diseased plants, potentially saving their crops before they inflict irreparable damage.

- Achieved Top 11% by researching the papers and articles on Pre-Trained Models for Image Classification and trained and ensembled them to recognize cassava leaf disease with an accuracy of 89.77%.
- Tools: Python, Pandas, PyTorch
        
# courses in ML/DS

**[1. Machine Learning - Andrew NG, Coursera](https://github.com/kyle-cloud/ML_coursera)**

It is one of the greatest online course modules introducing machine learning concepts and techniques. By the end of the course, we would have understood how to apply the most advanced machine learning algorithms to such problems as anti-spam, image recognition, clustering, building recommender systems, and many other problems. we'll also know how to select the right algorithm for the right job, as well as become expert at ‘debugging’ and figuring out how to improve a learning algorithm's performance.

- Finished the course content about the concepts and techniques in machine learning and simple introduction into deep learning.
- Implemented all the courseworks independently and achieved full scores.
- Tools: Python, Octave, Matlab

**[2. Machine Learning with Python - book](https://github.com/kyle-cloud/Machine-Learning-Python-)**

This is one of the best books teaching ML in practical which means instead of only reading there's lots of practices and projects to be done by hand although the concepts and details about all the algorithms are compete and also easy-understanding in the book. To achieve all the algorithms in ML by yourself to have an thorough understanding, Try this book.

- Implemented all the classic algorithms by coding with just basic data structures in Python.
- Obtained a great experience in applying machine learning algorithms to the real-word datasets.
- Tools: Python

**[3. Deep Learning(PyTorch) - BEIJING JIAOTONG UNIVERSITY](https://github.com/kyle-cloud/Deep-learning)**

This course focused on the Deep Learning with its popular concepts, structures and techniques. Except the basic and detailed explanations about DL in the module, there were adequate experienments for students to carry on with PyTorch. We were expected to process and model the real-world datasets given by the course by hand.

- Obtained a thorough understanding about the course content and got familiar with all the popular techniques and structures in deep learning.
- impplemented all the experienments independantly and completely.
- Tools: Python, PyTorch

**[4. Data science - King's College London](https://github.com/kyle-cloud/KCL_DS_projects)**
- Data Mining
- Pattern Recognition, Neural Networks and Deep Learning
- Big Data Technologies
- Simulation and Data Visualisation


# software development

**[1. Dynamic Gesture Recognition in Online Video Communication, BJTU](https://github.com/kyle-cloud/Dynamic_Gesture_Recognition_System)(private currently, MSc project)**

Gesture recognition is to classify gesture data into a finite number of predefined gesture classes. In particular, dynamic gestures help to increase naturalness and variousness as an input alternative in Human-Computer Interaction(HCI). In this work, a real-time system to capture, detect and recognize a set of 26 specific dynamic gestures is developed in the context of online video communication. In terms of the recognizer, the proposed 3DResNet-101 with the weighted sum of raw video and optical flow as input learns from the ’20BN-Jester Dataset V1’ consisted of enormous gesture video clips from the webcam, achieving an accuracy of 90% on the validation set. In addition, this paper proposed detecting the first appearance of a hand to judge the start point of a gesture in a continuous video stream, which maintains the naturalness and achieves a high success rate. Finally, this system is successfully integrated into the popular online conference software - Zoom with a virtual camera and API server. In this way, users can make gesture commands in online meetings, like pushing their hand forward to turn off video or zooming in with two fingers to switch to the active speaker’s view. In actual online conferences, the system shows a high level of fluency and achieves a 100% success rate of detecting gestures and 95% recognition accuracy.

- Constructed 3DResNet-101 neural network model with the weighted sum of raw video and optical flow as input, achieving 90% accuracy on 20BN-Jester validation dataset.
- Developed a real-time dynamic gesture recognition system with 95% accuracy and successfully applied to Zoom meetings with Shortcut keys to make commands and API server to reduce the burden on client machine.
- Proposed detecting the first appearence of hand to judege the start point of a dynamic gesture in real-time system.
- Full details could be seen in the report.


**[2. Localization System based on Mobile Big Data, BJTU](https://github.com/kyle-cloud/findYOU)**

With the rapid development of wireless communication technology, hundreds of millions of mobile data are generated every day in our daily life, and the mobile behavior of objects is diverse while still maintaining regularity. Therefore, this subject switches the big data information according to the base station provided by the mobile base station, excavates its path of action, identifies the petitioner according to it, and provides the petitioner with Real time location information. At the same time, in order to solve the problem of big data storage calculation and track similarity matching, the high-level and low-level models are used. The low-level model combines the segmentation and dimensionality reduction based on MDL (minimum description length) principle with the neighbor grower algorithm (DBSCAN) based on segment clustering to preprocess the track to reduce the system operation time. The high level model combines the two-level planning based on track feature extraction The improved Hausdorff distance based on information entropy, time interpolation and time constraint is combined to match the trajectory to improve the performance of similarity recognition, so as to build a big data processing environment, and finally form a web software that presents the petitioner's trajectory and similar trajectory on the map, and judges the identity information accordingly.

- Reproduced existing papers on clustering and matching trajectories and developed a web application to visualize the process.
- Utilized Tree Data Structure and optimized the dimensionality reduction method to store and preprocess 15 million trajectory points, which reduced total process time by 50%.
- Tools: Java, MongoDB, JavaScript

**[3. weChat - online chat platform, BJTU](https://github.com/kyle-cloud/weChat---)**

Instant online communication is becoming more and more popular and necessary. However, SMS, email and other channels are far from meeting the needs of the public for fast and simple communication. Our product, weChat, meets this condition. The mobile phone has replaced the function of SMS, and replaced the email in the aspect of instant communication, which truly meets the user's point-to-point communication needs. The system is a stand-alone software system and web application.

- Wrote all the development documents required, such as feasibility analysis, software requirements specifications.
- Designed prototype and elegant UI,  implemented the function of chatting with single-person and multi-person, and carried out high concurrency experiments.
- Tools: Java, MySQL, JavaScript

**[4. Fingerprint - cyber security, BJTU](https://github.com/kyle-cloud/fingerprint)(private)**

The black industry chain is rising rapidly. Lawbreakers can cheat and avoid tracking through a series of means, such as tampering with IP. In this context, the device fingerprint identification came into being. Device fingerprint refers to the unique identification that can uniquely identify the device, which can not be set by fraudsters. The device fingerprint can be used to identify the device. At present, the fingerprint of the device has been obtained and in-depth research mainly focuses on the software level, such as the browser fingerprint, but the hardware level device fingerprint acquisition research is not enough. This work is based on the existing device fingerprint acquisition technology to improve, in order to achieve the goal of not infringing the user's privacy, achieve a good balance between security and user experience and ensure stability, compatibility and performance under the premise of catering to technology development. The project combines the new API features provided by HTML5 with Windows system management instrumentation in order to obtain the hardware information of local and remote computers and extract the device fingerprint of the device which belongs to the research of device fingerprint at the hardware level.

- Compared Python, Java, C++, C# programming languages in terms of the feasibility of remote acquisition of device information.
- Accessed device information locally and remotely through browsers' canvas, HTML5+, ClientJS, WMI, etc.
- Used encryption algorithms to achieve similarity comparison, such as SimHash, GenSim and Levenshtein.


**[5. JustFindit - Android application, BJTU](https://github.com/kyle-cloud/JustFindit)(private)**

JustFindit is a convenient navigation app focusing on users' needs for outdoor location and navigation. Through Baidu map API, direction sensor, SQLite database and other tools, this application can mark and archive current map position which means to add position remarks and view it later. The notes can be used to query the recorded location and the information about it.

- Collaborated with another student to develop this software based on map API.
- Designed prototype, initialized configuration and realized back-end functions.
- Tools: C++, JavaScript, SQLite

**[6. Grading System - BJTU](https://github.com/kyle-cloud/student_quality)(private)**

In order to simplify the grading process in university we designed and implemented a platform for students to upload the files and certifications and for lecturers to monitor and grade.

- Identified requirements, set up Node.js environment and designed back-end functions for the product.
- implemented front-end, realized all functions of system and finally put the system into operation.

**[7. Homedisk - Internship, BEIJING TIANXINGYICHEN]()(not uploaded)**

- Completed front-end, back-end and writing development documents for type of SkyDrive

**[8. River Information Management System - Internship, BEIJING TIANXINGYICHEN]()(not uploaded)**

- Optimized database queries and writing documents for software copyright
- Improved query speed and efficiency to application standards and completed final document
