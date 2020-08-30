# Quantlie Regression workflows lectures

## In brief

The Quantile Regression (QR) lectures outlined below are *to be* recorded for 
[fastcampus.co.kr](https://fastcampus.co.kr) 
in August-November 2020.

The R projects notebooks can be found in this repository.

## The lectures

1. Introducing QR through answering different questions.
   Here is the list:

   - Can we apply Quantile Regression (QR) without the package QRMon?
      - Yes, see the CRAN item [“quantreg”](https://cran.r-project.org/web/packages/quantreg/index.html).
   - Are you computing QR using a moving window?
      - Related, how QR compares to Local regression? Or LOESS?
   - What do you do when the QR fitted curves (regression quantiles) intersect? 
   - How does QR fitted curve looks like over 3 points?
   - What approximation to pick for reconstructing the conditional CDF’s?
   - Why use QR? Is it just for better visualization of the signal?
   - What is the point of using those anomaly detection methods -- a human can easily do it?
   - Can we use Neural Networks instead of QR?
   - Are there implementations in other popular DS languages?
   
2. Basic QR applications
   - Demonstrate how to make 
     [Quantile Regression](https://en.wikipedia.org/wiki/Quantile_regression)
     workflows using the [software monad `QRMon`](https://github.com/antononcube/QRMon-R) 
     and some of the underlying software design principles. 
     (Namely ["monadic programming"](https://github.com/antononcube/R-packages/tree/master/StateMonadCodeGenerator).)

3. Finding outliers, anomalies, and structural breaks  
   - Outliers removal (data cleaning) 
   - Anomaly detection
   - [Structural breaks](https://en.wikipedia.org/wiki/Structural_break)

4. Additional topics

   - Review of previous sessions.
   - Simulations
   - Predict tomorrow from today's data.
   - Using NLP techniques on time series.
   - Generation of QR workflows with natural language commands.
   
   
## Visual aids

Here is a diagram for the QR workflows:

![QR-workflows](https://raw.githubusercontent.com/antononcube/MathematicaForPrediction/master/MarkdownDocuments/Diagrams/A-monad-for-Quantile-Regression-workflows/Quantile-regression-workflow-extended.jpg)
