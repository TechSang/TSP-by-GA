# TSP-by-GA
Solve TSP problem by GA

## Part1 
A GA function class, which can be called in different scenes.  
You just need to choice Selection, Crossover, Mutation Methods and dataset, population number and size that you want.   
You can change Crossover, Mutation rate in class.  

、、、
ga = GA(data=data['xy'],
            selectType=1,
            crossType=1,
            mutateType=2,
            populationNum=populationNum,
            populationSize=populationSize)
、、、

## Part2
The driver for running TSP.
