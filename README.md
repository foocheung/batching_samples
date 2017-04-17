# batching_samples

This app uses functions from the R package OSAT

A simple Shiny app to help allocate batches. File format must be tab delimited and have column names, example can be seen here

ID	SampleType	Race	AgeGrp
1	Case	Hispanic	(60,100]
2	Case	Hispanic	(60,100]
3	Case	European	(60,100]
4	Control	European	(50,60]
5	Control	European	(50,60]

How To

Step1) Upload your tab delimited file

Step2) Select the number of batches you are using from the slider "# of Batches:"

Step3) press GO

A recommendation for practice is to put the variable of primary interest as the first of the list.

Output: "Sample distribution by plates can also be visualized (Figure 1). It shows that samples with different characteristics were distributed across batches with only small variations. The small variation is largely due to the trade off in block randomizing multiple variables. The last plot is the index of optimization steps versus value of the objective function. The blue diamond indicate the starting point, and the red diamond mark the final optimal setup. It is clear that final setup is more optimal than the starting setup." 
This app uses functions from the R package OSAT

<img src="https://raw.githubusercontent.com/foocheung/batching_samples/master/batches.png">