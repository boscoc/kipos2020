# KIPOS2020 #

Official repository of the KIPoS2020 shared task on KIParla Part of Speech tagging at Evalita 2020

## 29 May 2020 ##
The DEVELOPMENT SET for KIPOS2020 includes data from the KIParla corpus tagged according to the UD Part of Speech tagset for Italian and manually revised. They can be considered as the gold standard reference for training the systems that participate to the task.

## 3 July 2020 ##
The SILVER SET for KIPOS2020 includes a larger portion of data from the KIParla corpus automatically annotated but not manually revised (except for what concerns some systematic error). They can be also used for training and developing the systems that participate to the task.

## 25 September 2020 ##
## The TEST SET for KIPOS2020 includes data to be used for testing systems that participate to the task. Data are tokenized like in the DEVELOPMENT and SILVER SETs but are released without the lines that in the DEVELOPMENT and SILVER SETs introduce each conversation turn (those preceded by hashtag). ##

## Data Download and License ##
The DEVELOPMENT SET and the SILVER SET for KIPOS2020 are available for donwload (file KIPOS2020-DS_rel290520+silverrel030720.zip in this repository).
These datasets are both covered by the Creative Commons license provided in this repository and they are released with a password-protected zip archive.
By filling in [this form](https://docs.google.com/forms/d/e/1FAIpQLSdNHWAWCAGyJCSA10dVcPjxl2cf5XCV2ZlfaZF0XHc5pPQsVg/viewform) you can accept the license and send us the request for the password for unzip the archive. It will be sent (by email) in a few time after filling in the form.

## How to read file labels of the DEVELOPMENT SET and SILVER SET ##
Data are organized in files that correspond to single conversations. 
The name of each file is composed according to the following pattern:

- the first two letters correspond to the city where the recording was collected: TO (Torino) and BO (Bologna)

- following two characters corresponding to the type of activity: A1 (office hours), A3 (random conversation), C1 (exams), D1 (lessons) and 
D2 (interviews); for the aim of KIPOS2020 C1, A1 and D1 are considered FORMAL, while A3 and D2 are considered INFORMAL.

## Information and Website ##
For more information on the task, see also the guidelines available in this repository (LAST UPDATE JULY 3rd!!!), and the 
[web page](http://www.di.unito.it/~tutreeb/kipos-evalita2020/index.html) of KIPOS2020. 

You can also join our googlegroup at [kipos-evalita2020@googlegroups.com](https://groups.google.com/forum/#!forum/kipos-evalita2020). 
For any question or problem, please start a topic on this mailing list.
