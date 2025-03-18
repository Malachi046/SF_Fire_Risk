1)Open the "Assignment 1" file through KNIME 
2)Upload the "SF Flood Risk" on the lower CSV reader tagged as "Risk"
3)Run the CSV writer
	You can run the Numeric Solver to see their linear regression results
	You can run the Table View to view the t values of the parameters
4)Upload the "SF Blockgroups" in the other upper CSV reader
5)On the CSV writer hit the settings bubble and set the download address
	default name should be 'Assignment 1 Export.csv'

*A Picture of KNIME was provided and the CSV output file was provided incase its easier to skip those steps"

6)Open the Jupyter file "Multi-Linear Regression" preferably through google Colab)
7)If in colab go to the file tab on the left and upload the file you saved on step 5 
	leave default if you used the premade file provided
8)On line 8 you can add the name of the file you uploaded. Example is below
	df = pd.read_csv('Assignment 1 Export.csv'.....
9)Run the file to view the homemade multi-linear regression
	you can view the convergence and the error at the bottom

