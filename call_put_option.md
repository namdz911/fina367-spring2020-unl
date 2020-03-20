# Callable and Putable Bonds

---

**Useful readings**

- Booleans section in [Basics](basics.ipynb)  
- [Collections](collections.ipynb)  

**Learning outcomes**

  - Understand basic principles underlying different models of credit risk 
  - Understand credit rating pricing model 

## Outline 

[![alt text](./pic/test1.png)](https://use.vg/i2TvPm)


- [Credit Risk](#Credit-Risk)  
  - [Introduction to options](##Introduction-to-options)  
  - [Introduction to bonds with embedded options](##Introduction-to-bonds-with-embedded-options)  
  - [Gains and loses from calling a bond](##Gains-and-loses-from-calling-a-bond) 
  - [Pricing callable bonds](##Pricing-callable-bonds)  
  - [Return on callable bonds](##Return-on-callable-bonds)  
  - [Duration and Convexity of callable bonds](##Duration-and-Convexity-of-callable-bonds) 
  
<details>
  <summary>Click to expand!</summary>
  
  ## Heading
  1. A numbered
  2. list
     * With some
     * Sub bullets
</details>  
  


## Introduction to Options
If an asset pays a stream of payoffs over multiple time periods, then we
can use a discount rate to calculate the value to the consumer of a entire
sequence of payoffs.

<a id='exerciselist-1'></a>

### Option Payoff/Profit example

[![alt text](./pic/test2.png)](https://use.vg/i2TvPm)

> Consider a call option on bond X with an exercise price of \\$112 that expires in 3 months. Today the option price is \$4.
> 1. What is your payoff if you buy the option today and in 3 months bond X is selling for \$100? What is your profit/loss?
> 2. What is your payoff if you sell the option and in 3 months bond X is selling for \$100? What is your profit/loss?
> 3. What is your payoff if you buy the option and in 3 months bond X is selling for \$120? What is your profit/loss?



<details>
  <summary>Click to expand!</summary>

#### Solution
1. The option will not be exercise because the strike price \$112 is higher than market price \$100. You lose the \$4 you paid for the option.
2. In this case, you gain \$4 for selling the option.
3. The option will be exercise because the strike price \$112 is lower than market price \$120. You lose the \$4 you paid for the option but gain \$8 ($$120-112$$) for exercising the option. 
</details>  

<a id='exerciselist-1'></a>

### Option Payoff/Profit example

[![alt text](./pic/test2.png)](https://use.vg/i2TvPm)

> Consider a call option on bond X with an exercise price of \\$112 that expires in 3 months. Today the option price is \$4.
> 1. What is your payoff if you buy the option today and in 3 months bond X is selling for \$100? What is your profit/loss?
> 2. What is your payoff if you sell the option and in 3 months bond X is selling for \$100? What is your profit/loss?
> 3. What is your payoff if you buy the option and in 3 months bond X is selling for \$120? What is your profit/loss?



<details>
  <summary>Click to expand!</summary>

#### Solution
> 1. What is your payoff if you buy the option today and in 3 months bond X is selling for \$100? What is your profit/loss?
> 2. What is your payoff if you sell the option and in 3 months bond X is selling for \$100? What is your profit/loss?
> 3. What is your payoff if you buy the option and in 3 months bond X is selling for \$120? What is your profit/loss?
</details>  

>See practice problem 1A-1 in the [*Problem List*](#problemlist-1)

## Introduction to bonds with embedded options

## Gains and loses from calling a bond

## Pricing callable bonds

## Return on callable bonds

## Duration and Convexity of callable bonds

<a id='exerciselist-1'></a>

### Example 1A

> Consider a 1-year zero-coupon bond that has a BBB rating. Assume that this bond is senior secured (historical recovery rate = 63.5%). The yield on a 1-year zero-coupon Treasury bond is 6%. What should be the yield on this BBB-rated bond? (Assume periodicity of 1)

[Walk-through](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)

- **Step 1**: Calculate the payoff 
- **Step 2**: Calculate the payoff 
- **Step 3**: Calculate the payoff

>See practice problem 1A-1 in the [*Problem List*](#problemlist-1)

<a id='exerciselist-1'></a>

### Example 1B

> Consider a 1-year zero-coupon bond that has a BBB rating. Assume that this bond is senior secured (historical recovery rate = 63.5%). The yield on a 1-year zero-coupon Treasury bond is 6%. What should be the yield on this BBB-rated bond? (Assume periodicity of 1)

[Walk-through](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)

- **Step 1**: Calculate the payoff 
- **Step 2**: Calculate the payoff 
- **Step 3**: Calculate the payoff

>See practice problem 1A-1 in the [*Problem List*](#problemlist-1)


<a id='exerciselist-1'></a>

### Example 1B

> Consider a 1-year zero-coupon bond that has a BBB rating. Assume that this bond is senior secured (historical recovery rate = 63.5%). The yield on a 1-year zero-coupon Treasury bond is 6%. What should be the yield on this BBB-rated bond? (Assume periodicity of 1)

[Walk-through](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)

- **Step 1**: Calculate the payoff 
- **Step 2**: Calculate the payoff 
- **Step 3**: Calculate the payoff

>See practice problem 1A-1 in the [*Problem List*](#problemlist-1)


<a id='exerciselist-1'></a>

**EXAMPLE 1A**

> Consider a 1-year zero-coupon bond that has a BBB rating. Assume that this bond is senior secured (historical recovery rate = 63.5%). The yield on a 1-year zero-coupon Treasury bond is 6%. What should be the yield on this BBB-rated bond? (Assume periodicity of 1)

[Walk-through](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)

- **Step 1**: Calculate the payoff 
- **Step 2**: Calculate the payoff 
- **Step 3**: Calculate the payoff

>See practice problem 1A-1 in the [*Problem List*](#problemlist-1)

### Practice Problems


<a id='problemlist-1'></a>
**Example 1**

What happens if we try different inputs in our Cobb-Douglas production

function?

([*back to text*](#exercise-1))

<a id='exerciselist-7'></a>

> **EXAMPLE 7**
>
> A bond has an expected return of 17.6%, sensitivity to the term factor of 1.45 and to the default factor of 0.86. The current term risk pr
emium is 3.2%. The risk free rate of return is 5%. What is the default risk premium if no arbitrage opportunities exist?


<details>
  <summary>Click for solution!</summary>
  
  > First Calculate the Price
$$
\begin{aligned}
\sum_{t=0}^{\infty} \beta^t & = \frac{1}{1-\beta}\\
\sum_{t=0}^{\tau} \beta^t &= \frac{1- \beta^{\tau+1}}{1-\beta}\\
\sum_{t=\tau}^{\infty} \beta^t &=  \frac{\beta^{\tau}}{1-\beta}
\end{aligned} \tag{2}
$$
    
  > First Calculate the Price
$$
\begin{aligned}
\sum_{t=0}^{\infty} \beta^t & = \frac{1}{1-\beta}\\
\sum_{t=0}^{\tau} \beta^t &= \frac{1- \beta^{\tau+1}}{1-\beta}\\
\sum_{t=\tau}^{\infty} \beta^t &=  \frac{\beta^{\tau}}{1-\beta}
\end{aligned} \tag{2}
$$
</details>

([*back to text*](#exercise-7))
