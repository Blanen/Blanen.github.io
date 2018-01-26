# Datascience portfolio

## Presentations

During this course I worked on five presentations.

[Link here](presentations)

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
In order to work with the kinect data easily, I started working on a way to combine all generated CSV into a single CSV.
The Person's ID was in the folder name and the Exercise ID didn't exist in the data but could be gotten by taking the csv in alphabetical order. 
Link [Here](https://github.com/Blanen/csv_combinator)

### Pepper train
When we wanted to start doing real analysis we needed a way to proccess new people recordings quickly. Other people started working on this but I saw that this was going to go wrong. The problem was that they each had their own Jupyter notebooks for their part of the analysis. What ended up happening was that person-A's code was getting called inside person-B's functions. The problem with this is that person-B's code is now dependant on Person-A's code, while there is no real way of doing version control.

With Boris I designed the process on how a 'train' could be made to work. This combines many steps of data manipulation to raw kinect data. I build this into a python command line application [Here](https://github.com/KinectingPepper/pepper_train)

#### Packagize other code

I made the other people's jupyter files into Python packages that should be easily installable with pip.

[Pepper_arcs](https://github.com/KinectingPepper/pepper_arcs)
[Data_extraction](https://github.com/KinectingPepper/Data_Extraction)

Sadly, due to serverside user-rights and usability issues concerning people's inexperience with working outside jupyter, these are not able to be used at the moment in jupyter, and the writers haven't updated them. 

These are currently in working condition last time I tested them.

#### BACK TO JUPYTER

Later on, the command-line-application was partly re-ported back to a jupyter application.

## Assignments

### Datacamp

Proof screenshot: [Link](images/datacamp.png)

### Coursera

Proof screenshot: [Link](images/coursera.png)

### PySpark

Completed all assignments... In a more correct way than the supplied answers. (It didn't add up the count in the babynames-counties)
[Link](tutorial_spark/)

### Exploratory Data Analysis

Completed all assignments.
[Link](
## Machine learning

### Clustering

WIP

### Neural networks

WIP
