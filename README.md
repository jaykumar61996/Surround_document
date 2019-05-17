# Surround_document
For better understanidng of surround
# Surround AI
Surround AI  is the python framework which is designed for flexible usage in Artificial Intelligence(AI). It is designed to support data scientist in their progress. Each and every scientist use different algorithm to solve different problems. There are no standard way for them to analyse altogether in a single module. To provide a standard solution surround frame work is built. Evolution of machine learning pipeline  is not possible without re-constructing the coding whereas surround package will provide a pipeline without any alterations.


**There were problems that where addressed at Applied Artificial Intelligence Institute:**

 1. There were same changes required to refactor code again and again,  
    which was written by data scientist to make it ready for implement. 
    That means there was no standard script, no proper way to handle   
    configuration and no standard pipeline architecture.
 2. The models which are existing are serving the model rather than
    end-to-end solution. The model needs to me clubbed with multiple
    models and glue code to tie these models together.
 3. Existing models don’t allow for the evolution of a machine learning
    pipeline without re-engineering the solution. Ex: using a cloud API
    for the first release before training a custom model much later.
 4. Code was commonly being commented out to run other branches.
 
 # Flow-diagram
Here are some components in the library that one can use to build Surround AI solutions.
![flowdigram](https://github.com/jaykumar61996/Surround_document/blob/master/pic.png)

## Components

 - Surround A group of many stages or maybe it can be one stage only,
   helps to transform the data into more meaningful and explainable
   data. You can set orders of stages directly on your implementation or   you may use configuration file. Configuration file allows you to
   define more than 1 pipeline implementation and then you can switch between them effortlessly.
 - Surround Data A sharable object between stages that holds necessary information for each stage. A stage will read some information from Surround Data then will process it and as rend result will put back new information that will be used by other stage or multiple stages.
 
 - In Surround, when you extend classes, you can add as many variables as you need to help you transform input data into output data. But note that there are **four** core variables that are ready for you to utilise.
	
**stage_metadata:** it is information that can be used to identify a stage.

**execution_time:** it is recorded time to complete a process.

**errors:** it is information to identify failure of a stage.

**warnings:** warnings are information when transformation is not 100% correct.

 - Stage an implementation of data transformation. Here is where
   **Surround Data** is modified to archive the result that you need. Each stage is only aimed to perform a set of related actions. In
   stage one where you prepare data to be processed and last stage can
   be where your populated data to be sent back to user.

**Operate** is a function that you need to override when you extend stage class. It must contain data transformation implementation.


# Why surround?
* It is designed to support data scientist in their progress.
*  Each and every scientist use different algorithm to solve different problems. There are no standard way for them to analyse altogether in a single module.
*   To provide a standard solution surround framework is built. 
*  Every machine learning pipeline can be accessed for getting the appropriate solution instead of reffering many machine learning packages.
# Usage
* Helping the data scientists in analytics instead            
using glue codes for their research.
*  Easy interaction between several machine learning pipelines.
* Provides end-to-end solution instead of providing solution for the models.
# Current
Using cloud API for training models for image recognition.
Developing a pipeline for the surround module using machine learning algorithms.
# Surround Working
# Installation guide:
## Windows
* Install the python 3.7.3 in the system  by following the provided link that is given below [https://www.python.org/downloads/](https://www.python.org/downloads/)	
*  Pip3 is installed in your system by default when you install Python.
* Set path in Environment variables for python 3.6.5.
* Type !pip3 install surround in command prompt to install surround in your system.
# How to create a project
After installation of surround using pip3
* **Type** surround -h
* You can see list of help option in surround with **commands** 

![Surround_help](https://github.com/sundararaman9608/sundararaman.github.io/blob/surround/Surround%20help1.PNG)


## create a project
* **Type** surround init
* Enter the project name and enter the purpose of the project

![Surround_init](https://github.com/sundararaman9608/sundararaman.github.io/blob/surround/project_created.PNG)

# Sample for Surround using Yolo 9000:
## Yolo 9000
> Yolo is the object detection system on a Pascal Titan X it processes images at 30 FPs and has a map of 57.9%. It can identify more than 9000 objects using image net classification and COCO detection dataset. 
## Yolo in surround
**Object detection in Image can be done in surround using Yolo 9000.**
> **Note:** we can use yolo in python with the help of openCV DNN(Deep Neural Networks).
### Installing dependencies: 
1.	Python 3.
2.	Numpy.
3.	OpenCV.
4.	Surround.
### Input arguments for image detection:
1.	Read image.
2.	Config file of Yolo.
3.	Use pre trained yolo weights.
4.	Text file containing class names.

**Sample Logo:**

![Surround logo](https://github.com/sundararaman9608/sundararaman.github.io/blob/surround/logo.adobe.png)

# Conclusion:
Surround is under development which as goals to satisfy the needs of data scientists. It completely turns the view of analysing in machine learning and other concepts of AI(Artificial Intelligence).





