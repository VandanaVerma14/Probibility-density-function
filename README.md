# probability-density-function
## Objective
Estimate the parameters of a probability density function using a roll-number-based non-linear transformation on NO₂ data.

## Dataset
- India Air Quality Dataset (Kaggle)
- Feature used: NO₂

## Methodology
1. From the dataset selected no2 values.
2. Applied non-linear transformation:
   z = x + 0.30 sin(1.5x)  
   (Roll No: 102303443)
3. Modeled transformed data using:
   p̂(z) = c · exp(−λ(z − μ)²)
4. Estimated μ, λ, and c using statistical moments.

## Results
 μ = 25.819751672076507 
 λ =  0.001461926988966829 
 c = 0.021571875520386332 # Probibility-density-function
