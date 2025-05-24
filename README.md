# Probability Distribution Problems & Solutions

### 1. Exponential Distribution  
**Problem**: Pizza delivery averages 15 minutes. What's the chance your order arrives in under 10 minutes?  
**Solution**:  
`P(X < 10) = 1 - e^(-10/15) ≈ 0.4866`  
**Answer**: 48.7% chance

### 2. Normal Distribution  
**Problem**: IQ scores average 100 (σ=15). What percentage score above 130?  
**Solution**:  
`Z = (130-100)/15 = 2 → P(X > 2) ≈ 0.0228`  
**Answer**: 2.28%

### 3. Poisson Distribution  
**Problem**: A hospital averages 4 births/night. What's P(7 births)?  
**Solution**:  
`P(X=7) = (e^-4 * 4^7)/7! ≈ 0.0595`  
**Answer**: 5.95%

### 4. Binomial Distribution  
**Problem**: Biased coin (60% heads) flipped 20 times. P(12 heads)?  
**Solution**:  
`C(20,12)*(0.6)^12*(0.4)^8 ≈ 0.1797`  
**Answer**: 17.97%

### 5. Triangular Distribution  
**Problem**: Task duration: min=8d, max=12d, likely=10d. Expected time?  
**Solution**:  
`(8+10+12)/3 = 10`  
**Answer**: 10 days

### 6. Lognormal Distribution  
**Problem**: Stock has μ=0.1, σ=0.2. P(return > 20%)?  
**Solution**:  
`Z = (ln(1.2)-0.1)/0.2 ≈ 0.4055 → P ≈ 0.3427`  
**Answer**: 34.27%

### 7. Gamma Distribution  
**Problem**: Website gets 500 visits/day. P(1000 visits in 1 day)?  
**Solution**:  
`Gamma CDF(k=1000, λ=500) ≈ 0.9999`  
**Answer**: 99.99%

### 8. Weibull Distribution  
**Problem**: Machine part (shape=1.5, scale=1000h). P(failure < 500h)?  
**Solution**:  
`1 - e^-(500/1000)^1.5 ≈ 0.2978`  
**Answer**: 29.78%

### 9. Beta Distribution  
**Problem**: Batter hits .300 historically. After 10/30, P(true > .250)?  
**Solution**:  
`Beta(α=11, β=21) → P ≈ 0.9104`  
**Answer**: 91.04%

### 10. Uniform Distribution  
**Problem**: Lottery number (100-200). P(120 ≤ X ≤ 140)?  
**Solution**:  
`(140-120)/(200-100) = 0.2`  
**Answer**: 20%
