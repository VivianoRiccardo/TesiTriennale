# TesiTriennale

# Data
In Data abbiamo il CIFAR-10 dataset diviso in training set e test set. Bisogna unpaccarlo.

# C

In C così come anche più avanti in Python abbiamo o avremmo due sotto cartelle: fully-connected e Convolutional. Nella prima abbiamo una rete fully-connected composta da 5 layers e nella seconda un modello VGG-like con l'aggiunta di 2 residual layers. Per far partire server.c e client.c è necessario scaricare llab repository: https://github.com/VivianoRiccardo/Learning-Lab-C-Library. Server.c va runnato dandogli un valore (1,2,3,....) che rappresenta il numero di client che si dovranno connettere moltiplicato per dieci. Quindi se do 1 come valore, si dovranno connettere 10 client, se do 2 20 ecc...
