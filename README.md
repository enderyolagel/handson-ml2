Edits on Aurélien Geron's handson-ml2 repo
==========================

The repo is edited to run only the second part **Neural Networks and Deep Learning** of the book **Hands-on Machine Learning with Scikit-Learn, Keras and TensorFlow** on a local machine.

**The list of edits**

* `docker/` directory is removed.

* `apt.txt` and `requirements.txt` files are removed.
  
* Notebooks are moved in `notebooks/`.

* Tutorials and extras are moved in `extras/`.

* `environment.yml` is edited to keep packages only related to the second part. All jupyter related packages are replaced with `ipykernel` to run notebooks in text editors.

**About the book**

> _The project aims at teaching you the fundamentals of Machine Learning in python. It contains the example code and solutions to the exercises in the second edition of my O'Reilly book [Hands-on Machine Learning with Scikit-Learn, Keras and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/):_

<img src="https://images-na.ssl-images-amazon.com/images/I/51aqYc1QyrL._SX379_BO1,204,203,200_.jpg" title="book" width="150" />

**The environment**

    $ git clone https://github.com/enderyolagel/handson-ml2.git
    $ cd handson-ml2
    $ conda env create -f environment.yml
    $ conda activate tf2