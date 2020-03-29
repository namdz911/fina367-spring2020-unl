# Credit Risk



**Before you start**

- We pick up where we left off before exam 3. We were discussing a new pricing model that is based on risk-adjusted return. Understanding Example 1A is important for Example 3-6 therefore the online course will pick up from there.
- Optional Readings: Chapter 11, 12
- <a href="./pdf/credit_risk.pdf" target="_blank">Link to download PowerPoint Slides!</a>


## Outline

![alt text](./pic/test2.png) <a href="https://use.vg/i2TvPm" target="_blank">Link to Video!</a>

- [Credit Risk](#credit-cisk)  
  - [Credit Ratings](#credit-ratings)  
  - [Credit Risk Models](#credit-risk-models)  
  - [Bond Factor Models](#bond-factor-models) 
  - [Practice Problems](#practice-problems) 
---

## Credit Ratings



<a id='example-1a'></a>
#### ![](./pic/note1515.png) Example 1A

![alt text](./pic/test2.png) <a href="https://use.vg/lbJUan" target="_blank">Link to Video!</a>



>Consider a 1-year zero-coupon bond that has a BBB rating. Assume that this bond is senior secured (historical recovery rate = 65.3%). The yield on a 1-year zero-coupon Treasury bond >is 6%. What should be the yield on this BBB-rated bond? (Assume periodicity of 1)

<details>
  <summary>Click for Solution!</summary>

##### ![](./pic/light.png) Solution

- Risk adjusted payoff is equal to risk free pay off:

**<center> (1+r<sub>BBB</sub>)p + (1+r<sub>BBB</sub>)(1 - p)RR = 1+r<sub>f</sub> </center>**

- Plug in the numbers and solve for **r<sub>BBB</sub>**
- The yield on this BBB-rated bond is **6.0847**
</details> 

##### Practice
- See [Problem 1](#problem-1) for more practice!

---

#### ![](./pic/dollarnew15.png) Credit risk structure of interest rates

![alt text](./pic/test2.png) <a href="https://use.vg/i2TvPm" target="_blank">Link to Video!</a>

- Credit risk structure of interest rates
  - Understand basic principles underlying different models of credit risk 
  - Understand credit rating pricing model 
  
- Yield spreads
  - Understand basic principles underlying different models of credit risk 
  - Understand credit rating pricing model 
---

<a id='example-1b'></a>

#### ![](./pic/note1515.png) Example 1B

![alt text](./pic/test2.png) <a href="https://use.vg/i2TvPm" target="_blank">Link to Video!</a>

>Consider the 1-year zero-coupon bond with a BBB rating, whose yield we calculated in Example 1A. What is the yield spread on this bond? Assume that the following are yields on Treasury STRIPS of different maturity:
>
>Maturity     | YTM
>------------ | -------------
>1            | 6%            
>2            | 6.2%         
>3            | 6.6%           


<details>
  <summary>Click for Solution!</summary>

##### ![](./pic/light.png) Solution
- The option will not be exercise because the strike price \$112 is higher than market price \$100. You lose the \$4 you paid for the option.
- In this case, you gain 4 for selling the option.
- The option will be exercise because the strike price \$112 is lower than market price \$120. You lose the \$4 you paid for the option but gain \$8 (120-112) for exercising the option. 
</details>  

##### Practice
- See [Problem 2](#problem-2) for more practice!

---

## Credit Risk Models


#### ![](./pic/dollarnew15.png) Credit risk structure of interest rates

![alt text](./pic/test2.png) <a href="https://use.vg/i2TvPm" target="_blank">Link to Video!</a>

- Credit risk structure of interest rates
  - Understand basic principles underlying different models of credit risk 
  - Understand credit rating pricing model 
  
- Yield spreads
  - Understand basic principles underlying different models of credit risk 
  - Understand credit rating pricing model 
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

##### ![](./pic/light.png) Solution

- We already have the the parameter for Z-score model:

**<center> Z=1.2X<sub>1</sub>+ 1.4X<sub>2</sub> +3.3X<sub>3</sub> + 0.6X<sub>4</sub> + 1.0X<sub>5</sub> </center>**

- Plug in the numbers and solve for Z-score.
</details> 

---

#### ![](./pic/dollarnew15.png) Credit risk structure of interest rates

![alt text](./pic/test2.png) <a href="https://use.vg/i2TvPm" target="_blank">Link to Video!</a>

- Credit risk structure of interest rates
  - Understand basic principles underlying different models of credit risk 
  - Understand credit rating pricing model 
  
- Yield spreads
  - Understand basic principles underlying different models of credit risk 
  - Understand credit rating pricing model 
---

<a id='example-3'></a>


#### ![](./pic/note1515.png) Example 3

![alt text](./pic/test2.png) <a href="https://use.vg/lbJUan" target="_blank">Link to Video!</a>

>Consider a firm whose 1-year zero-coupon bonds currently yield 10%. The yield on 1-year zero-coupon Treasury bonds is 8%. What is this firm’s implied probability of default if the recovery rate expected by bondholders is zero?

<details>
  <summary>Click for Solution!</summary>

##### ![](./pic/light.png) Solution
       
- Risk adjusted payoff is equal to risk free pay off:

**<center> (1+r<sub>BBB</sub>)p + (1+r<sub>BBB</sub>)(1 - p)RR = 1+r<sub>f</sub> </center>**

- Plug in the numbers and solve for **r<sub>BBB</sub>**
- The yield on this BBB-rated bond is **6.0847**
    
</details> 

##### Practice
- See [Problem 1](#problem-1) for more practice!
---

<a id='example-4'></a>

#### ![](./pic/note1515.png) Example 4

![alt text](./pic/test2.png) <a href="https://use.vg/lbJUan" target="_blank">Link to Video!</a>

>Consider a firm whose 1-year zero-coupon bonds currently yield 10%. The yield on 1-year zero-coupon Treasury bonds is 8%. What is this firm’s implied probability of default if bondholders expect to recover \$.60 on the dollar if the firm defaults? Assume periodicity of 1.

<details>
  <summary>Click for Solution!</summary>

##### ![](./pic/light.png) Solution
       
- Risk adjusted payoff is equal to risk free pay off:

**<center> (1+r<sub>BBB</sub>)p + (1+r<sub>BBB</sub>)(1 - p)RR = 1+r<sub>f</sub> </center>**

- Plug in the numbers and solve for **r<sub>BBB</sub>**
- The yield on this BBB-rated bond is **6.0847**
    
</details> 

##### Practice
- See [Problem 1](#problem-1) for more practice!
---

<a id='example-3'></a>

#### ![](./pic/note1515.png) Example 5

![alt text](./pic/test2.png) <a href="https://use.vg/lbJUan" target="_blank">Link to Video!</a>

>Consider a firm whose 1-year zero-coupon bonds currently yield 10%. The yield on 1-year zero-coupon Treasury bonds is 8%. What is this firm’s implied probability of default if when the firm defaults bondholders expect to recover \$.60 on the dollar with probability 1/3 and \$.40 on the dollar with probability 2/3?


<details>
  <summary>Click for Solution!</summary>

##### ![](./pic/light.png) Solution
       
- Risk adjusted payoff is equal to risk free pay off:

**<center> (1+r<sub>BBB</sub>)p + (1+r<sub>BBB</sub>)(1 - p)RR = 1+r<sub>f</sub> </center>**

- Plug in the numbers and solve for **r<sub>BBB</sub>**
- The yield on this BBB-rated bond is **6.0847**
    
</details> 

##### Practice
- See [Problem 1](#problem-1) for more practice!!
---

<a id='example-3'></a>

#### ![](./pic/note1515.png) Example 6

![alt text](./pic/test2.png) <a href="https://use.vg/lbJUan" target="_blank">Link to Video!</a>

>Consider a firm whose 1-year zero-coupon bonds currently yield 10%, and 2-year bonds currently yield 12%. The yields on 1-year and 2-year zero-coupon Treasury bonds (i.e. the 1-year and 2-year spot rates) are 8% and 9% respectively. What is this firm’s implied cumulative probability of default if bondholders do not expect to recover anything in the case of default?


<details>
  <summary>Click for Solution!</summary>

##### ![](./pic/light.png) Solution
       
- Risk adjusted payoff is equal to risk free pay off:

**<center> (1+r<sub>BBB</sub>)p + (1+r<sub>BBB</sub>)(1 - p)RR = 1+r<sub>f</sub> </center>**

- Plug in the numbers and solve for **r<sub>BBB</sub>**
- The yield on this BBB-rated bond is **6.0847**
    
</details> 

##### Practice
- See [Problem 1](#problem-1) for more practice!!
---

## Bond Factor Models


#### ![](./pic/dollarnew15.png) Credit risk structure of interest rates

![alt text](./pic/test2.png) <a href="https://use.vg/i2TvPm" target="_blank">Link to Video!</a>

- Credit risk structure of interest rates
  - Understand basic principles underlying different models of credit risk 
  - Understand credit rating pricing model 
  
- Yield spreads
  - Understand basic principles underlying different models of credit risk 
  - Understand credit rating pricing model 
---

<a id='example-3'></a>


#### ![](./pic/note1515.png) Example 7

![alt text](./pic/test2.png) <a href="https://use.vg/lbJUan" target="_blank">Link to Video!</a>

>A bond has an expected return of 17.6%, sensitivity to the term factor of 1.45 and to the default factor of 0.86. The current term risk premium is 3.2%. The risk free rate of return is 5%. What is the default risk premium if no arbitrage opportunities exist?


<details>
  <summary>Click for Solution!</summary>

##### ![](./pic/light.png) Solution
       
- Risk adjusted payoff is equal to risk free pay off:

**<center> (1+r<sub>BBB</sub>)p + (1+r<sub>BBB</sub>)(1 - p)RR = 1+r<sub>f</sub> </center>**

- Plug in the numbers and solve for **r<sub>BBB</sub>**
- The yield on this BBB-rated bond is **6.0847**
    
</details> 

##### Practice
- See [Problem 1](#problem-1) for more practice!!
---

## Practice Problems


#### ![](./pic/note1515.png) Problem 1
Consider a 1-year zero-coupon bond that has a CCC rating. Assume that this bond is senior secured (historical recovery rate = 42.7%). The yield on a 1-year zero-coupon Treasury bond is 2%. What should be the yield on this CCC-rated bond? (Assume periodicity of 1)

<details>
  <summary>Click for Solution!</summary>
    
#### Solution

- The yield on this BBB-rated bond is **15.02022**

</details>    

([*back to text*](#example-1a))

#### ![](./pic/note1515.png) Problem 2
Consider a 1-year zero-coupon bond that has a CCC rating. Assume that this bond is senior secured (historical recovery rate = 42.7%). The yield on a 1-year zero-coupon Treasury bond is 2%. What should be the yield on this CCC-rated bond? (Assume periodicity of 1)

<details>
  <summary>Click for Solution!</summary>
    
#### Solution

- The yield on this BBB-rated bond is **15.02022**

</details>    

([*back to text*](#example-1b))
