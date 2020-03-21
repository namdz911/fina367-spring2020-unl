# **Credit Risk**


**Useful Readings**

- Booleans section in [Basics](basics.ipynb)  
- [Collections](collections.ipynb) 

## **Outline**

[![alt text](./pic/test2.png)](https://use.vg/i2TvPm)

- [Credit Risk](#credit-cisk)  
  - ![](./pic/note1515.png) [Credit Ratings](#credit-ratings)  
  - ![](./pic/note1515.png) [Credit Risk Models](#credit-risk-models)  
  - ![](./pic/note1515.png) [Bond Factor Models](#bond-factor-models) 
  - ![](./pic/note1515.png) [Practice Problems](#practice-problems) 

## ![](./pic/note2525.png) **Credit Ratings**

**Learning outcomes**

  - Understand basic principles underlying different models of credit risk 
  - Understand credit rating pricing model 
  
[![alt text](./pic/test2.png)](https://use.vg/i2TvPm)

### Example 1A

[![alt text](./pic/test2.png)](https://use.vg/i2TvPm)

>Consider a 1-year zero-coupon bond that has a BBB rating. Assume that this bond is senior secured (historical recovery rate = 65.3%). The yield on a 1-year zero-coupon Treasury bond >is 6%. What should be the yield on this BBB-rated bond? (Assume periodicity of 1)

<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution

- Risk adjusted payoff is equal to risk free pay off:

**<center> (1+r<sub>BBB</sub>)p + (1+r<sub>BBB</sub>)(1 - p)RR = 1+r<sub>f</sub> </center>**

- Plug in the numbers and solve for **r<sub>BBB</sub>**.
- The yield on this BBB-rated bond is **6.0847**.
</details> 

#### Practice
- See [Problem 1](#problem-1) for more practice!

### Example 1B

[![alt text](./pic/test2.png)](https://use.vg/i2TvPm)

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
- The option will not be exercise because the strike price \$112 is higher than market price \$100. You lose the \$4 you paid for the option.
- In this case, you gain 4 for selling the option.
- The option will be exercise because the strike price \$112 is lower than market price \$120. You lose the \$4 you paid for the option but gain \$8 (120-112) for exercising the option. 
</details>  

#### Practice
- See [Problem 2](#problem-2)

## ![](./pic/note2525.png) **Credit Risk Models**


## ![](./pic/note2525.png) **Bond Factors Models**


## ![](./pic/note2525.png) **Practice Problems**


### Problem 1
Consider a 1-year zero-coupon bond that has a CCC rating. Assume that this bond is senior secured (historical recovery rate = 42.7%). The yield on a 1-year zero-coupon Treasury bond is 2%. What should be the yield on this CCC-rated bond? (Assume periodicity of 1)

<details>
  <summary>Click for Solution!</summary>
    
#### Solution

- The yield on this BBB-rated bond is **15.02022**

</details>    

([*back to text*](#example-1a))

### Problem 2
Consider a 1-year zero-coupon bond that has a CCC rating. Assume that this bond is senior secured (historical recovery rate = 42.7%). The yield on a 1-year zero-coupon Treasury bond is 2%. What should be the yield on this CCC-rated bond? (Assume periodicity of 1)

<details>
  <summary>Click for Solution!</summary>
    
#### Solution

- The yield on this BBB-rated bond is **15.02022**

</details>    

([*back to text*](#example-1b))
