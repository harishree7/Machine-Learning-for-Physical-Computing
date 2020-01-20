# Machine Learning for Physical Computing

## COURSE DESCRIPTION

With Machine Learning models are getting smaller, and microcontrollers are getting more computing power, Machine Learning is moving towards edge devices. This class explores the idea of how machine learning algorithms can be used on microcontrollers along with sensor data to build Physical Computing projects.

In this class, we will learn about TensorFlow Lite, a library that allows you to run machine learning algorithms on microcontrollers. We will talk about common machine learning algorithms and techniques and apply them to build hands-on interactive projects that enrich our daily lives.

Students will learn to use pre-trained models, and re-train the models with sensor data. We are going to talk about Image Classification, Transfer Learning, Gesture and Speech Detection. For each topic, we will first discuss its history, theory, datasets, and applications, and then build simple experiments based on the topic.

Prospective students are expected to have taken Introduction to Physical Computing and Introduction to Computational Media course, or have equivalent programming experience with Arduino and JavaScript.

## INFO
- Yining Shi, Tuesday, 6:30PM - 9:00PM, 03/24 - 05/05/2020
- Room 408, 370 Jay Street
- [Office Hours](https://calendar.google.com/calendar/selfsched?sstoken=UUVtNWtYeW9BX3ZhfGRlZmF1bHR8NDIzN2VhZmY5OTQ4MTM2NTRmY2Q4ODQyY2Q3NDZmM2I)

## OUTLINE:
- Week 1 Introduction to Machine Learning
- Week 2 Image Classification and Transfer Learning
- Week 3 Run a model with Tensorflow Lite
- Week 4 Train a model with Tensorflow Lite
- Week 5 Gesture detection
- Week 6 Speech recognition
- Week 7 Final project presentation

### Week 1 Introduction to Machine Learning
#### Notes:
What’s Artificial Intelligence, Machine Learning, Deep learning?
Supervised Learning, Unsupervised Learning, Reinforcement Learning
Machine Learning output types: Regression, Classification, Clustering, Sequence prediction
Existing Machine Learning use cases and creative projects
Introduction to Tensorflow Lite
TensorFlow Lite for Microcontrollers
#### Workshop:
Run Tensorflow Lite Hello world example on Arduino: https://github.com/tensorflow/tensorflow/tree/master/tensorflow/lite/experimental/micro/examples/hello_world

### Week 2 Classification and Transfer Learning
#### Notes:
What is a teachable machine
How does teachable machine work
What is Transfer Learning
Existing projects about transfer learning

#### Workshop:
Run a classifier(image/pose/sound) with Teachable Machine, and send the results to Arduino to light up an LED
Code: https://github.com/yining1023/machine-learning-for-the-web/tree/master/week4-soundClassifier/teachableMachineArduino-sound

### Week 3 Run a model with Tensorflow Lite
#### Notes:
Understand the concept of a “machine learning model.”
What is a “pre-trained model”?
What does it mean to discuss the “architecture” of a machine learning model?
Define and diagram an artificial neural network.
#### Workshop:
Running person_detection example: https://github.com/tensorflow/tensorflow/tree/master/tensorflow/lite/experimental/micro/examples/person_detection

### Week 4 Train a model with Tensorflow Lite
#### Notes:
Understand the full story of building a ML model for classification or regression.
Understand how data is formatted and downloaded including CSV and JSON.
Consider how to frame the problem and collect data.
Understand critical questions to ask (e.g. Who is this for? What’s the context?)
Understand the questions to ask about sourcing and collecting data.
Learn how to prepare a data set, including how to normalize and properly format it.
#### Workshop:
How to Collecting IMU data on Arduino Nano 33 BLE Sense

### Week 5 Gesture detection
Diagram the components of a two layer "vanilla" neural network.
How to build a simple neural network in code
#### Workshop:
Gesture Controlled USB Emoji Keyboard on Arduino Nano 33 BLE Sense

### Week 6 Speech recognition
#### Workshop:
Running the micro_speech example on Arduino Nano 33: https://github.com/tensorflow/tensorflow/tree/master/tensorflow/lite/experimental/micro/examples/micro_speech

## Resources:
- [How-to Get Started with Machine Learning on Arduino](https://medium.com/tensorflow/how-to-get-started-with-machine-learning-on-arduino-7daf95b4157)
- [TensorFlow Lite for Microcontrollers](https://www.tensorflow.org/lite/microcontrollers/overview)
- [TensorFlow Lite example](https://www.tensorflow.org/lite/examples)
- [TinyML Book](https://www.oreilly.com/library/view/tinyml/9781492052036/)
- [Tiny ml workshop](https://github.com/sandeepmistry/aimldevfest-workshop-2019)
- [Intel-Pattern-Matching-Technology, Arduino 101 gesture recognition example](https://github.com/intel/Intel-Pattern-Matching-Technology)
- [Get started with machine learning on Arduino](https://blog.arduino.cc/2019/10/15/get-started-with-machine-learning-on-arduino)
- [Fruit identification using Arduino and TensorFlow](https://blog.arduino.cc/2019/11/07/fruit-identification-using-arduino-and-tensorflow)
- [Machine Learning for Introductory Physical Computing Curricula](http://alimomeni.net/wordpress/wp-content/uploads/2016/01/CHI-2016-ML-for-Phys-Comp.pdf)
- [The Big Benchmarking Roundup Getting started with machine learning and edge computing]()


## EQUIPMENT
You will need a Arduino Nana 33 borad, and a modern laptop (4 years old or younger is a good rule of thumb). Most required software is freely available.

# Policies

## Evaluation

You are required to attend all class meetings and submit all weekly assignments and a final project.

Grading (pass/fail) will be based on a combination of factors:

- Attendance, participation in class discussion, and engagement in other students' projects (40%)
- Assignments (40%)
- Final Project (20%)

Please see ITP's statement on [Pass/Fail](http://help.itp.nyu.edu/academic-policies/pass-fail) which states that a "Pass" is equivalent to an "A" or a "B" while anything less would be considered a "Fail".

Attendance is mandatory. Please inform your teacher via email if you are going to miss a class. Two unexcused absences is cause for failing the class. (An unexcused lateness of 10 minutes or more is equivalent to 1/2 an absence.)

This class will be participatory, you are expected to participate in discussions and give feedback to other students both in class and participate with their projects. This (along with attendance) is 40% of your grade.

Class will culminate with final projects. You are expected to push your abilities to produce something that utilizes what you have learned in the class that is useful in some manner to yourself or the world. This will comprise 20% of your grade.

## Statement of Academic Integrity

Plagiarism is presenting someone else’s work as though it were your own. More specifically, plagiarism is to present as your own: A sequence of words quoted without quotation marks from another writer or a paraphrased passage from another writer’s work or facts, ideas or images composed by someone else.

### USE OF FREE AND OPEN SOURCE CODE EXAMPLES
(The following is adapted from Golan Levin’s Interactivity and Computation Course (Fall 2018) at Carnegie Mellon University.)

#### You must cite the source of any code you use
with the exception of examples specifically provided by the professor that are demonstrated in the videos for this course. Please note the following additional expectations and guidelines:

#### Check the License.
When using others' code, pay attention to the license under which it has been released, and be certain to fulfill the terms and requirements of those licenses. Descriptions of common licenses, and their requirements, can be found at choosealicense.com. Some licenses may require permission. If you are confused or aren’t sure how to credit code, ask one of the course instructors and make your best good faith effort. Not properly citing code sources is grounds for a 0 on an assignment.

#### Use Libraries.
The use of general, repurposable libraries is strongly encouraged. The people who developed and contributed these components to the community worked hard, often for no pay; acknowledge them by citing their name and linking to their repository.

#### Be Careful.
It sometimes happens that an artist places the entire source code for their sketch or artwork online, as a resource from which others can learn. Assignments professors give in new-media arts courses are often similar (e.g. "Clock"); you may also discover the work of a student in some other class or school, who has posted code for a project which responds to a similar assignment. You should probably avoid this code. At the very least, you should be careful about approaching such code for possible re-use. If it is necessary to do so, it is best to extract components that solve a specific technical problem, rather than those parts which operate to create a poetic experience. Your challenge, if and/or when you work with others' code, is to make it your own. It should be clear that downloading an artwork from someone's GitHub and simply changing the colors would be disgracefully lazy. And doing so without proper citation would be outright plagiarism.

## Statement of Principle

The core of the educational experience at the Tisch School of the Arts is the creation of original academic and artistic work by students for the critical review of faculty members. It is therefore of the utmost importance that students at all times provide their instructors with an accurate sense of their current abilities and knowledge in order to receive appropriate constructive criticism and advice. Any attempt to evade that essential, transparent transaction between instructor and student through plagiarism or cheating is educationally self-defeating and a grave violation of Tisch School of the Arts community standards. For all the details on plagiarism, please refer to page 10 of the Tisch School of the Arts, Policies and Procedures Handbook, which can be found online at: http://students.tisch.nyu.edu/page/home.html

## Statement on Accessibility

Please feel free to make suggestions to your instructor about ways in which this class could become more accessible to you. Academic accommodations are available for students with documented disabilities. Please contact the Moses Center for Students with Disabilities at 212 998-4980 for further information.

## Statement on Counseling and Wellness

Your health and safety are a priority at NYU. If you experience any health or mental health issues during this course, we encourage you to utilize the support services of the 24/7 NYU Wellness Exchange 212-443-9999. Also, all students who may require an academic accommodation due to a qualified disability, physical or mental, please register with the Moses Center 212-998-4980. Please let your instructor know if you need help connecting to these resources.

## Statement on use of Electronic Devices

Laptops will be an essential part of the course and may be used in class during workshops and for taking notes in lecture. Laptops must be closed during class discussions and student presentations. Phone use in class is strictly prohibited unless directly related to a presentation of your own work or if you are asked to do so as part of the curriculum.

