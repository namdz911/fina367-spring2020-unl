# **Callable and Putable Bonds**

**Useful readings**

- Booleans section in [Basics](basics.ipynb)  
- [Collections](collections.ipynb)  

**Learning outcomes**

  - Understand basic principles underlying different models of credit risk 
  - Understand credit rating pricing model 

## **Outline** 

[![alt text](./pic/test2.png)](https://use.vg/i2TvPm)

- [Callable and Putable Bonds](#callable-and-putable-bonds)  
  - [Introduction to options](#introduction-to-options)  
  - [Introduction to bonds with embedded options](#introduction-to-bonds-with-embedded-options)  
  - [Gains and loses from calling a bond](#gains-and-loses-from-calling-a-bond) 
  - [Pricing callable bonds](#pricing-callable-bonds)  
  - [Return on callable bonds](#return-on-callable-bonds)  
  - [Duration and Convexity of callable bonds](#duration-and-convexity-of-callable-bonds) 

## **Introduction to options**

**Learning outcomes**

  - Understand basic principles underlying different models of credit risk 
  - Understand credit rating pricing model 

<a id='example-1'></a>

### Option Payoff/Profit example

[![alt text](./pic/test2.png)](https://use.vg/i2TvPm)

> Consider a call option on bond X with an exercise price of \$112 that expires in 3 months. Today the option price is \$4.
> 1. What is your payoff if you buy the option today and in 3 months bond X is selling for \$100? What is your profit/loss?
> 2. What is your payoff if you sell the option and in 3 months bond X is selling for \$100? What is your profit/loss?
> 3. What is your payoff if you buy the option and in 3 months bond X is selling for \$120? What is your profit/loss?



<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution
- The option will not be exercise because the strike price \$112 is higher than market price \$100. You lose the \$4 you paid for the option.
- In this case, you gain 4 for selling the option.
- The option will be exercise because the strike price \$112 is lower than market price \$120. You lose the \$4 you paid for the option but gain \$8 (120-112) for exercising the option. 
</details>  

#### Practice
- See [Problem 1](#problem-1) for more practice!


### Example 1A

[![alt text](./pic/test2.png)](https://use.vg/i2TvPm)

>Consider a 1-year zero-coupon bond that has a BBB rating. Assume that this bond is senior secured (historical recovery rate = 65.3%). The yield on a 1-year zero-coupon Treasury bond >is 6%. What should be the yield on this BBB-rated bond? (Assume periodicity of 1)

<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution

- Risk adjusted payoff is equal to risk free pay off:

**<center> (1+r<sub>BBB</sub>)p + (1+r<sub>BBB</sub>)(1 - p)RR = 1+r<sub>f</sub> </center>**

- Plug in the numbers and solve for **r<sub>BBB</sub>**
- The yield on this BBB-rated bond is **6.0847**
</details> 

#### Practice
- See [Problem 2](#problem-2) for more practice!

## ![](./pic/note2525.png) **Introduction to bonds with embedded options**

**Learning outcomes**

  - Understand basic principles underlying different models of credit risk 
  - Understand credit rating pricing model 
  

## ![](./pic/note2525.png) **Gains and loses from calling a bond**

**Learning outcomes**

  - Understand basic principles underlying different models of credit risk 
  - Understand credit rating pricing model 

## ![](./pic/note2525.png) **Pricing callable bonds**

**Learning outcomes**

  - Understand basic principles underlying different models of credit risk 
  - Understand credit rating pricing model 

## ![](./pic/note2525.png) **Return on callable bonds**

**Learning outcomes**

  - Understand basic principles underlying different models of credit risk 
  - Understand credit rating pricing model 

## **Duration and Convexity of callable bonds**

**Learning outcomes**

  - Understand basic principles underlying different models of credit risk 
  - Understand credit rating pricing model 

## **Practice Problems**

<a id='problem-1'></a>
**Example 1**

> Consider a call option on bond X with an exercise price of \\$112 that expires in 3 months. Today the option price is \$4.
> 1. What is your payoff if you buy the option today and in 3 months bond X is selling for \$100? What is your profit/loss?
> 2. What is your payoff if you sell the option and in 3 months bond X is selling for \$100? What is your profit/loss?
> 3. What is your payoff if you buy the option and in 3 months bond X is selling for \$120? What is your profit/loss?



<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution
1. The option will not be exercise because the strike price \$112 is higher than market price \$100. You lose the \$4 you paid for the option.
2. In this case, you gain 4 for selling the option.
3. The option will be exercise because the strike price \$112 is lower than market price \$120. You lose the \$4 you paid for the option but gain \$8 (120-112) for exercising the option. 
</details>  

([*back to text*](#example-1))
