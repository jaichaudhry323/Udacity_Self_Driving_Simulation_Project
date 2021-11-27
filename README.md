# Udacity_Self_Driving_Simulation_Project using Deep Learning (CNN)

Took me 1.5 months :)

Full Video Link: https://drive.google.com/file/d/1rGX95tF-3ixq8wO0nBBdcbLhtv2EGs98/view
<br>

![Working](./udacity.gif)

How to run:
First download the dataset from kaggle https://www.kaggle.com/zaynena/selfdriving-car-simulator <br>
Or alternatively create your own dataset from simulator

Download the simulator from this Repo: https://github.com/udacity/self-driving-car-sim

Now after cloning this repo, run the Track_1.ipynb file: (Remove any minor errors if any) <br>
This will generate a model-xyz.h5 file which is the trained model file

Now open the udacity simulator

Now run this command: `python Run_Simulation.py --path=ABSOLUTE_PATH_TO_MODEL_FILE`

Example:<br>
`python Run_Simulation.py --path=D:/Downloads/model-0.2385.h5`

