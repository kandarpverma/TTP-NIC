README FILE

In order to reproduce the results of the Evolutionary Algorithm follow this steps:

1) Open a terminal or working directory inside the CODE folder

2) Make sure all dependencies listed on the requirements.txt file inside this folder are installed on your python enviroment.

2) Specify the input file name on line 12 of the EA2.py source file (eg. file_name = 'a280-n279.txt')

3) Specify the configuration for the current run of the EA on lines 32, 33,34,35 for population_size, tournament_size, mutation_rate and SEED respectively.

3) Run the Evolutionary Algorithm using command: python EA.py

4) EXAMPLE OUTPUT:

STARTING EXPERIMENT:

Number of nodes 280
Number of items 279
Population Size 30
Tournament Size 6
Mutation rate % 4
*****************************
*****************************

Current Generation 484
Current Evaluation 1000
Current Average Fitness  -12292.595277176264
Current Best Fitness  -17138.555036571022
Current Best time, value  (7121.444963428979, 24260.0)
*********************************

Current Generation 984
Current Evaluation 2000
Current Average Fitness  -12784.940114878777
Current Best Fitness  -17138.555036571022
Current Best time, value  (7121.444963428979, 24260.0)
*********************************
.........


The algorithm will keep printing its evolution until reaching a 10000 fitness evaluations.

A new folder Results is gonna be created with the final solutions and the time and profit tuples inside txt files.

A graph will be created with a paretto front of current EA evaluation.


