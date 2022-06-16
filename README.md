# FL-REU
This is the repository for an REU (Research Experience for Undergraduates) project at the Department of Mathematics, University of Michigan, Ann Arbor. This project starts on Jun 6th, 2022 and is expected to finish on Aug 5th, 2022. This project is supervised by Professor Maria Han Veiga from the Department of Mathematics, University of Michigan, Ann Arbor.

The `FL.ipynb` file in the repo contains code that I use to do FL on my project. This code is implemented with Pytorch and based on code provided by Professor Maria Han Veiga here at UMich.
The `envrionment.yml` file can be used if you want to run the code locally on your machine.

The code is based on the famous `FedAvg` algorithm proposed in *Communication-Efficient Learning of Deep Networks
from Decentralized Data*. I further implemented funcationalities such as spliting client dataset into training and validation sets and performing further operation on them (under construction), adding Gaussian noise to certain clients to simulate clients with corrupted data etc.
