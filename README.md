# Bib-Detection

This Project is for sports.
This is for sports, it will be designed so that it can be in one place around a track and it will capture how many people of each colour bib run past, 
(so that it can figure out lap times, and lap numbers, etc)

This will be using OpenCV to do so.


# To Run:

```pip install -r requirements.txt``` - this is so that you have the correct modules downloaded.

```python Bib-Detection.py``` - This is if you have the camera static, and there are are up to 5 different colored bibs running past.

```python Bib-Detection(2-cameras).py``` - This is if you have both cameras static - either side of the track, and there are are up to 5 different colored bibs running past.

# TODO

- Need to make a gui to input how many teams there are, and be able to link a colour to a inputted team name.
- Need to detect colours.
- Need to detect bibs (this is additional, and it will work without this feature).
- Needs to be able to count how many times a bib colour goes past the camera. {how many times to cross a line.} (Use a people counter for this, as it is already built).
- Using how many times it goes past in a minute, and using an inputted coure length, calculate the average speed of the team. (Use a car speed detector for this, as it is already built).
- Need to be able to save these to a database {only a local one - proabably just a .csv file.}