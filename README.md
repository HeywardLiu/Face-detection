# face detection

## Introduction
* This is the final project of python course at NCTU, a prototype of **course roll call system**.
* **Compare faces** to the trained model of dataset through [`haarcascade`](https://github.com/opencv/opencv/tree/master/data/haarcascades) which is provided by  [`opencv`](https://opencv.org/).
* **Roll call results** would be maintained in the database.
---
## Database interface
* Each course has its own database file. e.g. `Calculus.db`
* Inside the database, create a table named `member_list` for roll calling by default. 
* We implement this database interface via [`sqlite3`](https://www.sqlite.org/index.html), which has been pre-installed already.
![](https://i.imgur.com/OmRqoQD.png)

---
## Installation
* packages: [`sqlite3`](https://www.sqlite.org/index.html) /  [`numpy`](https://numpy.org/) / [`pandas`](https://pandas.pydata.org/) / [`opencv-contrib-python`](https://pypi.org/project/opencv-contrib-python/)
* Install packages via [pip](https://en.wikipedia.org/wiki/Pip_(package_manager))
```python=
pip install numpy
pip install pandas
pip install opencv-contrib-python
```
---
## Result
* Multi-face detection 
![](https://i.imgur.com/D0GnWwb.png)
* Before roll call
![](https://i.imgur.com/r0qYbdf.png)
* new student registeration
![](https://i.imgur.com/8CbCP1Y.png)

