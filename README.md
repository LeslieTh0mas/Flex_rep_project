  At my current employer, I am an operations trainer. The way operations is organized, there are four main groups. Each of those main groups, has a set number of employees spanning across two bi-coastal campuses along with two managers, two work leads, and one operations trainer. There is also a team that consists of six flex reps that can process some work for each group. When an associate calls in sick, or volumes are high in a particular group, the managers are able to request help from a member of the flex team. It is impossible for managers to keep up with what these flex reps are able to process.
  I am creating a program for the two managers I support where they could type in the flex reps name, to see what functions they would be able to help us out in. The managers are also able to search by trainer to see stats on associates they have trained. Also included is a scatterplots featuring training hours by associate, and training hours by trainer. There are series of functions to calculate Sum, Mean, Median, Maximum, and Minimum for training hours.
  
Feature 1: 
Read in data from a local csv, excel file, json, or any other file type. (used excel file)

Feature 2: 
Manipulate and clean your data. Used built-in pandas function to remove rows where training hours where less than 1. 

Feature 3:
Analyze your data. Write custom functions to operate on your data. This function reads a DataFrame, asks for the input of name and saves the name as the variable "selected person. It then searches the "quality" for any mention of “y”, then prints what job functions the associate can help in.  The manager is able to input the flex reps name, and receive the output of a list of queues the can be scheduled in, along with what manager they work for. The manager will be better informed on who the best associate is to request and know what manager they need to contact.
I wrote a custom function that reads a DataFrame, asks for the input of the trainer.  It saves the name as the variable "selected person". It then searches the column "trained" for any mention of “y”, then prints data for associates they have trained and drops duplicates. The manager can use this data to assess the performance of the trainers.
I read in a data frame, then did 5 basic calculations with Pandas, finding the sum(), median(), mean(), maximum(), and minimum() of the column "training_hours". 

Feature 4: 
Visualize your data. The standard choice here is just making a couple visualizations then interpreting them to say something about your data. I created two scatterplots to show training hours by trainer and training hours by associate.

Feature 5:
Interpret your data and graphical output. If your project is in a Jupyter Notebook, this should be between the important cells. Write markdown cells in Jupyter explaining your thought process and code. 
  
  Relevant packages that need to be installed to run the project:
%pip install notebook
%pip install pandas
%pip install matplotlib
%pip install openpyxl
%pip install pylance
