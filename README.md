# LOFLCS

### 1. Architecture

```
- src
  - models 
  - optimizers 
  - trainers
  - utils
  - client.py 
  - cost.py
- args.py
- getdata.py # data processing
- main.py # main function
```



### 2. How to run

```
python main.py 
```

|    parameters    |                 explanations                  |
| :--------------: | :-------------------------------------------: |
|     --is_iid     |           data distribution is iid.           |
|  --dataset_name  |               name of dataset.                |
|   --round_num    |    number of round in communication round.    |
| --num_of_clients |             numer of the clients.             |
|   --c_fraction   | Proportion of clients selected in each round. |
|  --local_epoch   |       local train epoch of each client.       |
|   --dirichlet    |   Delineate the Distribution of Dirichlet.    |
|       ...        |                                               |

