# EC500 Heart Monitor Mock application

## Prerequisites

Python 3.5

## Run instructions
python main_app.py

## System Diagram
![](https://github.com/ec500-software-engineering/exercise-1-modularity-heliatbu/blob/master/system_diagram.jpg) 

## Description of the system
5 seperate threads are used in our system to achieve asynchronous reading and processiong. Readers, dataprocessor and AI modules use different threads.

### Pros:
Use resource more sufficiently.

### Cons:
5 threads running at same time may cause overflow.


## Responsibility
Prediction engine module
