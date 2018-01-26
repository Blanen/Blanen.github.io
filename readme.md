# Datascience portfolio

## Presentations

WIP

## Bullshit

### Assignment

I got a 7.0 on the Bullshit in Datascience Assignment assignment. 

[Link here to the document](docs/bullshit.pdf)

## Data gathering

### C# Kinect Application

#### Code Guidelines
The first think I did on this was build a code contribution guideline

[Link to PR](https://github.com/Hans2131/KinectingPepper/pull/4)
I made it because the experience I have with fellow students adding code willy nilly is not always positive.
This enforces peer reviews in code style and buildability. 
I also added a file for the travis build system to ensure that every merge with master would be buildable.
I later removed travis because I couldn't make it work correctly due to a lack of experience with its configuration.

#### CSV Writing
Early on I recognized the handiness of CSVs instead of xmls and other formats.

[Link to PR](https://github.com/Hans2131/KinectingPepper/pull/9/files)
I set on to make the application able to work with CSVs.
First I made it so I could load-in existing xml files and convert them to csvs. This part of the code stayed in my own branch for a while. Later on I made it also output CSVs together with the xmls when saving.
Hans later added a dialogbox so you could select a folder of XMLs to convert instead of having a hardcoded folder.

#### Usabilty
I saw that there were some mistakes going on in recording and made it so it would disable the start button when already started and disable the stop button when it already stopped. [Link here](https://github.com/Hans2131/KinectingPepper/pull/12/files)

## Data manipulation

### CSV Combinator
I created a python package that can combine a folder of folders of Kinect data to a single csv. This is much easier to work with than having hundreds of seperate CSV files.
Link [Here](https://github.com/Blanen/csv_combinator)

### Pepper train

With Boris I designed the process on how a 'train' could be made to work. This combines many steps of data manipulation to raw kinect data. Afterwards I build this into a python package [Here](https://github.com/KinectingPepper/pepper_train)

### Packagize other code

Because most people were making their code in jupyter, it was hard to work with this and almost impossible to do some version management on it. 
I made the jupyter files into Python packages that should be easily installable with pip.

[Pepper_arcs](https://github.com/KinectingPepper/pepper_arcs)
[Data_extraction](https://github.com/KinectingPepper/Data_Extraction)

Sadly, due to serverside user-rights issues and usability concerning people's inexperience with working outside python, these are not able to be used at the moment in jupyter.

## Assignments

### Datacamp

Completed almost all datacamp assignments.

Proof screenshot: WIP

### Coursera

WIP

### PySpark

So close

## Machine learning

### Clustering

WIP

### Neural networks

WIP
