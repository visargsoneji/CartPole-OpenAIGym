# CartPole OpenAI Gym

--Models--<br>
It contains two models namely 'model_t1t2.h5' for task1 and task2 and other one 'model_t3.h5' for task3.<br>

--Training--<br>
The training part is same for task1 and task2 (Training_t1t2.ipynb) which is basically trained on task1 and works good for task2 also.<br>
For task3 we have changed the model to a larger model with a change in some hyperparameters (Training_t3.ipynb).<br>

--Testing--<br>
We have created only one notebook for testing all the three tasks.<br>
Currently Testing.ipynb is ready for task1 and task2.<br>
To test for task3 just change the second argument to 'model_t3.h5' while calling test(). <br>

--versions--<br>
numpy==1.18.2<br>
gym==0.17.1<br>
Keras==2.3.1<br>
Keras-Applications==1.0.8<br>
Keras-Preprocessing==1.1.0<br>
tensorboard==2.1.1<br>
tensorflow==2.1.0<br>
tensorflow-estimator==2.1.0<br>
matplotlib==3.2.1<br>

