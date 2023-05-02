Download Link: https://assignmentchef.com/product/solved-cpsc-483-final-exam
<br>



<ol>

 <li>Perform normalization, the necessary preprocessing step.</li>

</ol>

<ol start="2">

 <li>Use PCA and SVD on the dataset given below. Reduce the dimensionality to 2 dimensions. Display the principal components from both PCA and SVD. Are they the same ? You can answer this in the output. Project the original data instances (points) onto the principal components resulting from both SVD and PCA. Are they the same ? You can answer this in the output. Plot the two principal components from SVD ( PC1, labeled as such, capturing the maximum variance from the data, and PC2, labeled as such, the next one) and the projections onto them of the original data.</li>

</ol>

<ol start="3">

 <li>Project the features (dimensions) onto the principal components and print out the resulting array. Interpret these projections as a short answer, explaining what features’ essence is captured by PC1 and PC2, and what are they signifying. Remember, when you reduce the dimensions, the new dimensions carry the weight or essence of the more than one original dimension or feature.</li>

</ol>

<ol start="4">

 <li>A working program to do all the above, preferably commenting, broadly indicating which part, does what. Don’t waste time commenting each little bit of code. The program output also should have preceding comments like “Printing original data”, and then print data; “After SVD, Printing original data projected onto principal components” and then print…</li>

</ol>

<strong><u>Dataset:</u></strong>

I have uploaded the <strong>cars dataset</strong> both as .xlsx and .mat. <strong>You should use the .mat version in your code</strong>. The .xlsx version has extra instances or data points, and those are missing some features, as you can see, marked with ‘*’. The .dat version has eliminated those missing feature instances. The .xlsx is for looking at and understanding what the data is about. You should be able to retrieve the data exactly in the format as .xlsx in your numpy array. You should note “X = points[‘X’]” in PCA starter code only retrieves the numerical data and not the name of the cars. But for plotting the data, you would need the name of the cars. Also, the columns 2 through 9 in the data are just boolean values. You can see that in the .xlsx. You <strong>should not</strong> consider those columns in PCA and SVD calculations. Only begin from column 10 onwards for the features to be incorporated in the original dataset.





