# Anomalies detection movie abstracts

## About the lecturer

- Same as [this one](./Quantile-Regression-lecture-movies-abstracts.md).

## Introducing Anomalies Detection (AD) through answering different questions

- What kind of anomalies we are going to discuss?

- How are anomalies defined? 

   - What is a relevant classification or taxonomy?
 
- Why consider single time series anomalies separately from multi-dimensional signals anomalies?

- Which packages and method are used?

- How do we defined measures for anomaly detection success?

- What steps are taken when anomaly detection algorithms are developed?

- What are the simplest anomaly detection algorithms?

------

## Preliminary notions

### Anomalies definitions

There are many ways to define anomalies in time series. Here we are going to list the ones we focus on in this presentation.

- **Point Anomaly:** Simply and outlier of the values of the time series.

- **Contextual Anomaly:** An anomaly that is local to some sub-sequence of the time series.

- **Breakpoint / change-point:** A regressor value (time) of a time series where the mean of the values change. (Also, consider (i) shifts in trend, (ii) other changes in trend and/or, (iii) changes in variance.)

- **Structural break:** Unexpected changes of the parameters of regression models.

### Examples of time series with anomalies: Numenta

### Examples of time series with anomalies: NREL

### Tools to use

- Using classifiers

- Using recommenders

- 1D outlier finders

- Quantile regression

------

## Simple algorithms

### Getting outliers from regression errors

### Measuring success

### ROC application


------

## More complicated algorithms

- Structural breaks before components determination

- Structural breaks finding

- Structural breaks vs components

------

## Multi-dimensional anomalies detection

- Definitions

- TBD...

------

## Anomalies within collections

- TBD...