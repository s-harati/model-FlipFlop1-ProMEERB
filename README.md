# model-RecogSIM-SES
A coupled Social-Ecological System model

This repository contains code files of a model described in the paper titled: 
"Emergence of environmentally responsible behavior through a recognition mechanism – insights from a conceptual social-ecological model"
by Saeed Harati, Liliana Perez and Roberto Molowny-Horas

The model is built by coupling two independently developed models that were written in Java (repast-simphony) and R.
The two parts of the model interact with each other through a mechanism that we named flip-flop. They take turns and send messages to each other.

To run the coupled model:
First, create the folder structure that is used in the flip-flop mechanism (use the link below)
Next, download or prepare data required for running each part of the model (use the link below)
Finally, enter the paths of the above-said folders and datasets in the codes.
In R codes, these paths should be entered in identified lines at the beginning of the files named "share*.r" 
In Java codes, these paths should be entered in identified lines at the beginning of the files named "AgentG.java" and "Registrar.java"

Model calibration, input, and results datasets are available at https://osf.io/x8huq/

This README file will be updated upon publication of the paper.
