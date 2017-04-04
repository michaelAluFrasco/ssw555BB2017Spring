# ssw555BB2017Spring
This repo is created for coursework assignment of SSW555-Agile Methods for Software Development
The goal of this coursework is to utilize Agile methodologies in a collaborative development project

Below you will find descriptions of the code written for the team project

The code contained in this repository is used to parse data from a GEDCOM file, which is standard format for geneology data
GEDCOM can contain information about individuals such as
  name, gender, DOB, death date, ID of child and parents
GEDCOM can contain information about families such as
  unique family ID, spouse, marriage & divorce date, children uniqueID

GEDCOM is a line-oriented text file and many examples can be found on the internet

This repo contains code that parses a GEDCOM file in parser.py

UserStory.py contains code that summarizes the GEDCOM into a viewable table

UserStory.py is used to detect instances of errors, anomolies, and significant upcoming dates as described below
Detects errors for impossible situations such as an individual being born in a future date
Detects anamolies for unlikely situations such as a child being born after their parents divorce
Detects significant upcoming dates such as birthdays and anniversaries

The code written is aimed to provide a user the ability to identify mistakes in a family tree and provide information without requiring them to dive into excessive data
