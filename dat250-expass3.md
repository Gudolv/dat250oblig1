# Dat250 experiment3

## Technical Problems

I had no technical problems installing MongoDb. It was an annoyance that MongoDB had been removed from the offical repositories [wiki](https://wiki.archlinux.org/title/MongoDB),
but I choose to install **mongo-db-bin** package. This seemed to work very well for the experiment.

However this made manualy verifying the package more difficult. In the end I choose to just follow the example from the webpage.

## Validation

As I installed it through a package manager, I didn't have installationfiles to validate.
![Package manager](https://github.com/Gudolv/dat250oblig1/blob/main/Screenshots/PacketHashSum.png)

I did download a file and tried to follow the procedure aswell (yes I know its for macOS, I'm wondering if that is the cause of the errormessage?) 
![Manual verifiy](https://github.com/Gudolv/dat250oblig1/blob/main/Screenshots/SigVerify.png)

## Experiment 1

### Crud - Insert Documents

![Insert](https://github.com/Gudolv/dat250oblig1/blob/main/Screenshots/InsertDoc.png)

### Crud - Query Documents

![Query](https://github.com/Gudolv/dat250oblig1/blob/main/Screenshots/QueryDoc.png)

### Crud - Update Documents

![Update](https://github.com/Gudolv/dat250oblig1/blob/main/Screenshots/UpdateDoc.png)

### Crud  - Remove Documents

![Remove](https://github.com/Gudolv/dat250oblig1/blob/main/Screenshots/RemoveDoc.png)

### Crud - Bulk Write Operations

![Bulk Write](https://github.com/Gudolv/dat250oblig1/blob/main/Screenshots/BulkWriteDoc.png)


## Experiment 2

![MapReduce Function1](https://github.com/Gudolv/dat250oblig1/blob/main/Screenshots/MapReductionAggregateExp.png)

![MapReduce Function2 personal](https://github.com/Gudolv/dat250oblig1/blob/main/Screenshots/MapReduceExp2.png)

This function counts how many times a customer is registered in the database and is usefull for example if you have a reward program or want to know who your return customers are. 

# Pending issues
Manualy verifying the package downloaded with the packet-manager has not been done. 
