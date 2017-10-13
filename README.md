# MNIST classification by TensorFlow #

- [MNIST For ML Beginners](https://www.tensorflow.org/tutorials/mnist/beginners/)
- [Deep MNIST for Experts](https://www.tensorflow.org/tutorials/mnist/pros/)



### Requirement ###

- Python >=2.7 or >=3.4
  - TensorFlow >=1.0
- Node >=6.9


### How to run ###

    $ pip install -r requirements.txt
    $ npm install
    $ gunicorn main:app --log-file=-


### Deploy to Heroku ###

    $ heroku apps:create [NAME]
    $ heroku buildpacks:add heroku/nodejs
    $ heroku buildpacks:add heroku/python
    $ git push heroku master

or Heroku Button.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)
# Tensor_sample