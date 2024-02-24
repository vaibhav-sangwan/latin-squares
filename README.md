What is this?
=============

Latin Squares is a mathematical puzzle game for the Sugar desktop.


How to use?
===========

Latin Squares can be run on the Sugar desktop.  Please refer to;

* [How to Get Sugar on sugarlabs.org](https://sugarlabs.org/),
* [How to use Sugar](https://help.sugarlabs.org/)

How to run?
=================

Dependencies:- 
- Python >= 3.10
- PyGObject >= 3.42
- PyGame >= 2.5
  
These dependencies need to be manually installed on Debian, Ubuntu and Fedora distributions.


**Running outside Sugar**


- Install the dependencies

- Clone the repo and run -
```
git clone https://github.com/vaibhav-sangwan/latin-squares.git
cd latin-squares
python main.py
```

**Running inside Sugar**

- Open Terminal activity and change to the Latin Squares activity directory
```
cd activities\LatinSquares.activity
```
- To run
```
sugar-activity3 .
```