
## Increased Limits Model
### Occurance Limit = Claim Limit ex 500/500 or 500CSL:
<div align="center"><img src="https://latex.oncodecogs.com/png.image?ILF=e^{(1-e^{(\frac{-L}{S})})}-1"/></div>

### Occurance Limit = 2xClaim Limit ex 250/500:
<div align="center"><img src="https://latex.oncodecogs.com/png.image?ILF=(e^{(1-e^{(\frac{-2L}{S})})}-1)-(e^{(\frac{-L}{S})}-e^{(\frac{-2L}{S})})*(e^{(e^{(\frac{-L}{S})}-e^{(\frac{-2L}{S})})})"/></div>

### Occurance Limit = 3xClaim Limit ex 100/300:
<div align="center"><img src="https://latex.codecogs.com/gif.latex?\tiny&space;ILF=(e^{(1-e^{(\frac{-3L}{S})})}-1)-(e^{(\frac{-L}{S})}-e^{(\frac{-3L}{S})})*(e^{(e^{(\frac{-L}{S})}-e^{(\frac{-3L}{S})})})&plus;\frac{1}{2}((e^{(\frac{-L}{S})}-e^{(\frac{-2L}{S})})^2)*(e^{(e^{({-L}{S})}-e^{({-2L}{S})})})" /></div>

<br>
<br>
<br>
<br>

## Homeowners Catastrophe Model (aggregate)
### Mean of aggregate distribution = mean(f)*mean(s)
<div align="center"><img src="https://latex.oncodecogs.com/png.image?mean(F)*mean(S)=E(F)*E(S)"/></div>
<div align="center"><img src="https://latex.oncodecogs.com/png.image?E(F)*E(S)=\frac{rp}{1-p}(\alpha*AOI)(\Gamma(1+\frac{1}{d}))"/>
</div>

#### Assume: 
#### The frequency follows a negative binomial distribution.
#### The severity follows a weibull distribution - behaves like a fractal...
### Variance of aggregate distribution:
<div align="center"><img src="https://latex.codecogs.com/gif.latex?\dpi{150}&space;\tiny&space;Var(AggDist)=\sum_{n=1}^{\infty}(nE(S^2)&plus;n(n-1)E(S)^2-2nE(S)(E(F)*E(S))&plus;(E(F)*E(S))^2)\binom{r&plus;n-1}{n}p^n(1-p)^r" /></div>

#### Where:  
#### E(S) = Mean of Severity distribution.
#### E(S^2) = Second Moment of the Severity Distribution about the origin.
#### n = number of events 
#### r = number of successes.

<br>
<br>
<br>
<br>

## Price implementation model
#### Many times we can only move toward the proposed from current due to disruption.
#### The following optimizes it and assumes that the rates will be in effect for a year. 
<div align="center"><img src="https://latex.oncodecogs.com/png.image?Filed-Factor=\frac{(PC)}{(C+(P-C)e^{(-\alpha)})}"/></div> 

Where P is the Modeled Factor, C is the Current Factor and we are solving for <img src = "https://latex.oncodecogs.com/png.image?\alpha" >.  

<br>
<br>
<br>
<br>