# The taxonomy
Li and Roth invented a taxonomy that grew to a standard in answer type detection for a long time. The taxonomy covers 6 master classes and 50 sub classes. The 6 master classes are:

Abbreviation (2)
Description (4)
Entity (22)
Human (4)
Location (5) and
Numeric (13).
The numbers in brackets depicts the number of sub classes for each master class. These classes can be used to cover most cases of answer types acc. to Li and Roth.

# The data
The presented data consists of 1548 questions in the training set and 735 questions in the test/evaluation set. For all master and sub classes the number of samples is uniformly distributed.

Master classes (Train #1548 / Test #735)
Abbreviation (Train #72 / Test #30)
Description (Train #141 / Test #80)
Entity (Train #678 / Test #313)
Human (Train #119 / Test #60)
Location (Train #150 / Test #75)
Numeric (Train #388 / Test #177)





This data was labeled the following way in the master classes file:

Was ist die Hauptstadt von Deutschland?#LOCATION
In the sub classes files the same question is labeled as follows:

Was ist die Hauptstadt von Deutschland?#LOC_CITY
The annotation for the sub classes consists for the first three tokens of the master class followed by an underscore and the name of the sub class.

# List of all sub classes

### ABBREVIATION
ABBREVIATION, EXPANDED ABBREVIATION
### ENTITY
ANIMAL, BODY, COLOR, CREATIVE, CURRENCY, DISEASE/MEDICINE, EVENT, FOOD, INSTRUMENT, LANGUAGE, LETTER, OTHER, PLANT, PRODUCT, RELIGION, SPORT, SUBSTANCE, SYMBOL, TECHNIQUE, TERM, VEHICLE, WORD
### DESCRIPTION
DEFINITION, DESCRIPTION, MANNER, REASON
### HUMAN
GROUP, INDIVIDUAL, TITLE, DESCRIPTION
### LOCATION
CITY, COUNTRY, MOUNTAIN, OTHER, STATE
### NUMERIC
CODE, COUNT, DATE, DISTANCE, MONEY, ORDER, OTHER, PERIOD, PERCENT, SPEED, TEMPERATURE, SIZE, WEIGHT
