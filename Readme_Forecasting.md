# PayPocket visualization
## Phase 1: Sample charts using PowerBI
1. Actual Series
<img width="608" alt="Screen Shot 2022-04-27 at 8 48 50 PM" src="https://user-images.githubusercontent.com/89392789/165654444-504b9ecc-a8c0-4eb2-a745-4b6b6459b4b1.png">

2. Stationarity test
<img width="931" alt="Screen Shot 2022-04-27 at 8 49 42 PM" src="https://user-images.githubusercontent.com/89392789/165654525-0273ff50-ae9b-4747-b993-6eddebcf95df.png">

3. Autocorrelation and Partial autocorrelation plots
<img width="924" alt="Screen Shot 2022-04-27 at 8 50 18 PM" src="https://user-images.githubusercontent.com/89392789/165654582-e8e7e2e8-7130-427d-b445-8f582ff1b8ad.png">

4. Loess Smoothing
<img width="725" alt="Screen Shot 2022-04-27 at 8 50 49 PM" src="https://user-images.githubusercontent.com/89392789/165654627-402bd7c6-ab0c-4cf9-a6a7-b3298336398e.png">

5. Siple Exponential Smoothing
<img width="386" alt="Screen Shot 2022-04-27 at 8 51 14 PM" src="https://user-images.githubusercontent.com/89392789/165654666-d384ad79-1ac2-49db-9a36-dea984fdd409.png">

### Results: 
The Series is already smooth for the given dataset so, smoothening is not required.

6. Stationarity test
### Results:
ADF Test Statistic : -0.99916608535741
p-value : 0.7535683308711256
Number of Lags Used : 12
Number of Observations : 431
Weak evidence against null hypothesis,indicating it is Non-Stationary 

7. First order difference
<img width="422" alt="Screen Shot 2022-04-27 at 8 53 19 PM" src="https://user-images.githubusercontent.com/89392789/165654851-4eb7c831-613f-4653-89fc-d12ef43bd8ff.png">

## * Autocorrelation and Partial autocorrelation plots #
<img width="772" alt="Screen Shot 2022-04-27 at 8 53 44 PM" src="https://user-images.githubusercontent.com/89392789/165654900-878137ff-c3c6-48bd-8dfa-f1ce7cc906ec.png">

8. SARIMAX model of order(1,2,1)
<img width="721" alt="Screen Shot 2022-04-27 at 8 54 42 PM" src="https://user-images.githubusercontent.com/89392789/165654993-2f4dfb91-525b-4808-84b9-6e915d3d7f9a.png">

9. ARIMA model of the order (2,0,3)
<img width="767" alt="Screen Shot 2022-04-27 at 8 55 41 PM" src="https://user-images.githubusercontent.com/89392789/165655071-3387336a-4d1e-49b2-a40d-fcf850340572.png">

10. Encoding of data with two different techniques:
    i.) One hot encoding
    Accuracy: 64.63%
    
    ii.) Ordinal encoding:
    Accuracy: 67.35%
 
 ### Results: 
 On our dataset, Ordinal transform gives better results than One hot encoder.
