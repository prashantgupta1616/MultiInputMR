# MultiInputMR

We use MultipleInputs class which supports MapReduce jobs that have multiple input paths with a different InputFormat and Mapper for each path. To understand the concept more clearly let us take a case where 
we have school data where StudentId is comman in all data files, we have three diffrent data set from diffrent source system , 
1) School details data 
2) Student details data 
3) Student Result data

We will use three diffrent mapper to read three diffrent directories and redcuer pahse we'll get combine result
