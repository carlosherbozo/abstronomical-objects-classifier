Author Credit: Aritra Ghosh (aritraghsh09 on GitHub)

An Unsupervised Approach to Classify Astronomical Objects

Objective
Develop an unsupervised algorithm that separates astronomical objects based on their type (star, galaxy, quasar)

Background
Different types of astronomical objects emit different amounts of light at different wavelengths. By observing the same object at different wavelengths (through different filters) or by observing the spectrum of an object, astronomers are able to tell what type an object is. The goal of this project is to develop an unsupervised algorithm that can take as an input the brightness of the object at different wavelengths; and then cluster them according to their type.

Data
The data consists of a csv file containing astronomical objects imaged using the Sloan Digital Sky Survey (Data Release 12). The goal of this project is to use the brightness of the astronomical objects at different filters (u,g,r,i,z) to predict their object type -- star, galaxy or quasar. For this, you need to use an unsupervized ML framework.

The file sdss_dr12_objects.csv contains 30,000 object and the relevant columns are :-

u --> Brightness of the object in the u-filter
g --> Brightness of the object in the g-filter
r --> Brightness of the object in the r-filter
i --> Brightness of the object in the i-filter
z --> Brightness of the object in the z-filter
redshift --> How far the object is from us
class --> Classification of the object (STAR,GALAXY,QSO)

Our of the 30,000 objects; use the first 22,000 rows as the training + validation set (split according to your will). Use the last 8,000 rows as the test set.
