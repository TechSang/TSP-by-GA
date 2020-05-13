# TSP-by-GA
![](https://img.shields.io/badge/CNSCC-361-lightgrey) ![](https://img.shields.io/badge/MIT-2020-blue)   
Solve TSP problem by GA  

## Part1 
A GA function class, which can be called in different scenes.  
You just need to choice Selection, Crossover, Mutation Methods and dataset, population number and size that you want.   
You can change Crossover, Mutation rate in class.  

```
ga = GA(data=data['xy'],
            selectType=1,
            crossType=1,
            mutateType=2,
            populationNum=populationNum,
            populationSize=populationSize)
```

## Part2
The driver for running TSP.
