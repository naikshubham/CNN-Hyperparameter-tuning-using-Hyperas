
# Hyperas

- A very simple convenience wrapper around hyperopt for fast prototyping with keras models. Hyperas lets you use the power of hyperopt without having to learn the syntax of it. Instead, just define your keras model as you are used to, but use a simple template notation to define hyper-parameter ranges to tune. 
</br>


- We have two options for hyperparameter tune our networks.One is scikit-learn GridSearchCV way which can be used by using the sckit-learn API wrapper in keras. This method does not make use of GPU acceleration and hence cannot achieve great speeds even after parallelizing.
</br>



- Hyperas enables us to take advantage of GPU acceleration enabling you to train models atleast 10X faster and is lso easy way to approach hyperparameter tuning.</br>

## Installation 

- pip install hyperas

## References 

- https://github.com/maxpumperla/hyperas


- https://towardsdatascience.com/a-guide-to-an-efficient-way-to-build-neural-network-architectures-part-i-hyper-parameter-8129009f131b
