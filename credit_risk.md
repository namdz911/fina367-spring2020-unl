<div class="sidenav">
  <a href="readme.html">Front Page</a>
  <strong>Module 5</strong>
  <a href="credit_risk">Credit Risk</a>
  <strong>Module 6</strong>  
  <a href="call_put_option.html">Callable and Putable Bonds</a>
  <a href="convertible_bonds">Convertible Bonds</a>
</div>

<link rel="stylesheet" type="text/css" href="./sidenav.css">

<div class="main">

# Credit Risk



**Before you start**

- We pick up where we left off before exam 3. We were discussing a new pricing model that is based on risk-adjusted return. Understanding Example 1A is important for Example 3-6 therefore the online course will pick up from there.
- You should practice all the problems provided on this page and make sure you know how to solve them. 
- Optional Readings: Chapter 5, 6
- <a href="./pdf/credit_risk.pdf" target="_blank">Link to download PowerPoint Slides!</a>


## Outline
- [Credit Risk](#credit-risk)  
  - [Credit Ratings](#credit-ratings)  
  - [Credit Risk Models](#credit-risk-models)  
  - [Bond Factor Models](#bond-factor-models) 
  - [Practice Problems](#practice-problems)
- In Class Example List: [1A](#example-1a), [1B](#example-1b), [2](#example-2), [3](#example-3), [4](#example-4), [5](#example-5), [6](#example-6), [7](#example-7)   
---

## Credit Ratings
([*back to top*](#credit-risk))!

<a id='example-1a'></a>
#### ![](./pic/note1515.png) Example 1A

(*Read the Example and think before you watch!*)


<iframe title="Credit Risk - Example 1A" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/UFISRTS4eMtm"></iframe>
  
>Consider a 1-year zero-coupon bond that has a BBB rating. Assume that this bond is senior secured (historical recovery rate = 65.3%). The yield on a 1-year zero-coupon Treasury bond is 6%. What should be the yield on this BBB-rated bond? (Assume periodicity of 1)

<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution

- Risk adjusted payoff is equal to risk free pay off:

**<center> (1+r<sub>BBB</sub>)\*p\*RR + (1+r<sub>BBB</sub>)*(1 - p) = 1+r<sub>f</sub> </center>**

- Plug in the numbers and solve for **r<sub>BBB</sub>**
- The yield on this BBB-rated bond is **6.0847%**
</details> 

#### Practice
- See [Problem 1](#problem-1) for more practice!
---

#### ![](./pic/dollarnew15.png) Credit risk structure of interest rates

<iframe title="Credit Risk - Credit Structure and Yield Spread" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/ssJ3C9JbLQWy"></iframe>

---

<a id='example-1b'></a>

#### ![](./pic/note1515.png) Example 1B

>Consider the 1-year zero-coupon bond with a BBB rating, whose yield we calculated in Example 1A. What is the yield spread on this bond? Assume that the following are yields on Treasury STRIPS of different maturity:
>
>Maturity     | YTM
>------------ | -------------
>1            | 6%            
>2            | 6.2%         
>3            | 6.6%           


<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution
- To calculate the yield spread for a risk bond, we have to use the treasury bond with the same maturity. In this case, it is the 1-year Treasury with YTM = 6%.
</details> 

---

## Credit Risk Models
([*back to top*](#credit-risk))!

- Now we gonna begin our discussion about credit risk models. The purpose of these models is to provide us with an assessment of the ability to pay. You will see that different models take into account different inputs to produce a measure for credit risk. 
- We will study 3 different models of credit scores:
    - Qualitative models: **The 4Cs of Credit Analysis**
    - Quantative Models (Credit-scoring models): **Altman's Z-score**
    - Newer models: **Term-Structured based Method**


---

#### ![](./pic/dollarnew15.png) Qualitative Models (The 4Cs)

<iframe title="Credit Risk - 4Cs" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/IdOKJXvDe6eM"></iframe>
  
---

#### ![](./pic/dollarnew15.png) Quantitative Models (Credit-scoring models)

<iframe title="Credit Risk - Credit Scoring Models" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/jZi4jZnM6Zz3"></iframe>
  
---

<a id='example-2'></a>
#### ![](./pic/note1515.png) Example 2

>Consider a firm with the following characteristics:
> - X1 (Working capital/total assets)=.01
> - X2 (Retained earnings/total assets)=.1
> - X3 (EBIT/total assets)= -0.25
> - X4 (Market value equity/ book value LT debt)=.4
> - X5 (Sales/total assets)=1
>Calculate and interpret the Z score for this firm.


<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution

- We already have the the parameter for Z-score model:

**<center> Z=1.2X<sub>1</sub>+ 1.4X<sub>2</sub> +3.3X<sub>3</sub> + 0.6X<sub>4</sub> + 1.0X<sub>5</sub> </center>**

- Plug in the numbers and solve for Z-score.
</details> 

---

#### ![](./pic/dollarnew15.png) Term Structure Based Method

<iframe title="Credit Risk - Structure Based Method" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/oodZlZwYejAC"></iframe>
  
  
---

<a id='example-3'></a>


#### ![](./pic/note1515.png) Example 3

(*Read the Example and think before you watch!*)


<iframe title="Credit Risk - Example 3" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/LABLrsVdDs71"></iframe>
  
>Consider a firm whose 1-year zero-coupon bonds currently yield 10%. The yield on 1-year zero-coupon Treasury bonds is 8%. What is this firm’s implied probability of default if the recovery rate expected by bondholders is zero?

<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution
       
- Risk adjusted payoff is equal to risk free pay off:

**<center> (1+r<sub>risky</sub>)\*p\*RR + (1+r<sub>risky</sub>)*(1 - p) = 1+r<sub>f</sub> </center>**

- Plug in the numbers and solve for p, which should be equal to **1.8182%**
    
</details> 

#### Practice
- See [Problem 2](#problem-2) for more practice!
---

<a id='example-4'></a>

#### ![](./pic/note1515.png) Example 4

(*Read the Example and think before you watch!*)


<iframe title="Credit Risk - Example 4" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/BH43CWLz9qeU"></iframe>
  
>Consider a firm whose 1-year zero-coupon bonds currently yield 10%. The yield on 1-year zero-coupon Treasury bonds is 8%. What is this firm’s implied probability of default if bondholders expect to recover \$.60 on the dollar if the firm defaults? Assume periodicity of 1.

<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution
       
- Risk adjusted payoff is equal to risk free pay off:

**<center> (1+r<sub>risky</sub>)\*p\*RR + (1+r<sub>risky</sub>)*(1 - p) = 1+r<sub>f</sub> </center>**

- Plug in the numbers and solve for p, which should be equal to **4.5455%**
    
</details> 

---

<a id='example-5'></a>

#### ![](./pic/note1515.png) Example 5

(*Read the Example and think before you watch!*)


<iframe title="Credit Risk - Example 5" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/2VqHy2AA9ndL"></iframe>
  

>Consider a firm whose 1-year zero-coupon bonds currently yield 10%. The yield on 1-year zero-coupon Treasury bonds is 8%. What is this firm’s implied probability of default if when the firm defaults bondholders expect to recover \$.60 on the dollar with probability 1/3 and \$.40 on the dollar with probability 2/3?


<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution
       
- Risk adjusted payoff is equal to risk free pay off:

**<center> (1+r<sub>risky</sub>)\*p\*RR + (1+r<sub>risky</sub>)*(1 - p) = 1+r<sub>f</sub> </center>**

- First calculate the expected RR which should be equal to **46.67%**
    
- Plug in the numbers and solve for p, which should be equal to **3.4093%**
    
</details> 

---

<a id='example-6'></a>

#### ![](./pic/note1515.png) Example 6

(*Read the Example and think before you watch!*)


<iframe title="Credit Risk - Example 6" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/SSAiF0PraoS0"></iframe>
  

>Consider a firm whose 1-year zero-coupon bonds currently yield 10%, and 2-year bonds currently yield 12%. The yields on 1-year and 2-year zero-coupon Treasury bonds (i.e. the 1-year and 2-year spot rates) are 8% and 9% respectively. What is this firm’s implied cumulative probability of default if bondholders do not expect to recover anything in the case of default?


<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution
       
- Risk adjusted payoff is equal to risk free pay off:

**<center> (1+r<sub>risky</sub>)\*p\*RR + (1+r<sub>risky</sub>)*(1 - p) = 1+r<sub>f</sub> </center>**

- The marginal probability of default in year 1 is **1.8182%**
- To apply our risk-neutral valuation technique to the second year, we need to calculate the expected return over that year from corporate and from Treasury bonds, i.e. the 1-year forward rates one year from today (f<sub>1,2</sub>). Use this equation: **(1+r<sub>1</sub>)(1+f<sub>1,2</sub>)=(1+r<sub>2</sub>)^2**
- The forward rate for risky corporate yield is **14.0364%**
- The forward rate for risky-free yield is **10.0093%** 
- The marginal probability of default in year 2 is **3.5314%**   
- The implied cumulative probability of default is **5.2854%**
    
</details> 

#### Practice
- See [Problem 3](#problem-3) for more practice!
---

## Bond Factor Models
([*back to top*](#credit-risk))!

#### ![](./pic/dollarnew15.png) Bond Factors Model

<iframe title="Credit Risk - Factor Models" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/yYQpKWV6wj6b"></iframe>

---

<a id='example-7'></a>


#### ![](./pic/note1515.png) Example 7

>A bond has an expected return of 17.6%, sensitivity to the term factor of 1.45 and to the default factor of 0.86. The current term risk premium is 3.2%. The risk free rate of return is 5%. What is the default risk premium if no arbitrage opportunities exist?


<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution
       
- **Bond Expected Return = Risk-free + Beta_Term * Term_premium + Beta_Default * Default_premium**
    
- Plug in the numbers and solve for Default_premium you should get **9.2558%**
    
</details> 

---

## Practice Problems
([*back to top*](#credit-risk))!

<a id='problem-1'></a>
#### ![](./pic/note1515.png) Problem 1
Consider a 1-year zero-coupon bond that has a CCC rating. Assume that this bond is senior secured (historical recovery rate = 42.7%). The yield on a 1-year zero-coupon Treasury bond is 2%. What should be the yield on this CCC-rated bond? (Assume periodicity of 1 and probability of default 20%)

<details>
  <summary>Click for Solution!</summary>
    
#### ![](./pic/light.png) Solution

- The yield on this CCC-rated bond is **15.02022%**

</details>    
&nbsp 

([*back to text*](#example-1a))

<a id='problem-2'></a>
#### ![](./pic/note1515.png) Problem 2
Consider a firm whose 1-year zero-coupon bonds currently yield 8.2%. The yield on 6-month zero-coupon Treasury bonds is 6%. The yield on 1-year zero-coupon Treasury bonds is 7%. What is this firm’s implied probability of default if the recovery rate expected by bondholders is zero?

<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution
       
- Risk adjusted payoff is equal to risk free pay off:

**<center> (1+r<sub>risky</sub>)\*p\*RR + (1+r<sub>risky</sub>)*(1 - p) = 1+r<sub>f</sub> </center>**
    
- Pick the proper bond yield: **The yield on 1-year zero-coupon Treasury bonds is 7%**

- Plug in the numbers and solve for p, which should be equal to **1.1091%**
    
</details> 
&nbsp 

([*back to text*](#example-3))

<a id='problem-3'></a>
#### ![](./pic/note1515.png) Problem 3
>Consider a firm whose 1-year zero-coupon bonds currently yield 6.7%, and 2-year bonds currently yield 9.6%. The yields on 1-year and 2-year zero-coupon Treasury bonds (i.e. the 1-year and 2-year spot rates) are 5.2% and 7.5% respectively. What is this firm’s implied cumulative probability of default if bondholders do not expect to recover anything in the case of default?


<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution

- The marginal probability of default in year 1 is **1.4058%**
- The forward rate for risky corporate yield is **12.5788%**
- The forward rate for risky-free yield is **9.8503%** 
- The marginal probability of default in year 2 is **2.4237%**   
- The implied cumulative probability of default is **3.7954%**
    
</details> 
&nbsp 

([*back to text*](#example-6))!

([*back to top*](#credit-risk))!
