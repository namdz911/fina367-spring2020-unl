# Credit Risk

---

**Useful Readings**

- Booleans section in [Basics](basics.ipynb)  
- [Collections](collections.ipynb) 

## Outline

[![alt text](./pic/test2.png)](https://use.vg/i2TvPm)

- [Credit Risk](#credit-cisk)  
  - [Credit Ratings](#credit-ratings)  
  - [Credit Risk Models](#credit-risk-models)  
  - [Bond Factor Models](#bond-factor-models) 

## Credit Rating

If an asset pays a stream of payoffs over multiple time periods, then we
can use a discount rate to calculate the value to the consumer of a entire
sequence of payoffs.

### Example 1A

[![alt text](./pic/test2.png)](https://use.vg/i2TvPm)

>Consider a 1-year zero-coupon bond that has a BBB rating. Assume that this bond is senior secured (historical recovery rate = 65.3%). The yield on a 1-year zero-coupon Treasury bond >is 6%. What should be the yield on this BBB-rated bond? (Assume periodicity of 1)

#### Solution
h<sub>&theta;</sub>(x) = &theta;<sub>o</sub> x + &theta;<sub>1</sub>x

- Risk adjusted payoff is equal to risk free pay off:

<div class="math">
\begin{equation}
 (1+r_{BBB})p + (1+r_{BBB})(1 - p)RR = 1+r_{f} 
\end{equation}
</div>
 
- Plug in the numbers and solve for $ r_{BBB} $. 
- The yield on this BBB-rated bond is **6.0847**

#### Practice
- See [Problem 1](#problem-1)!

### Example 1B

[![alt text](./pic/test2.png)](https://use.vg/i2TvPm)

>Consider the 1-year zero-coupon bond with a BBB rating, whose yield we calculated in Example 1A. What is the yield spread on this bond? Assume that the following are yields on Treasury STRIPS of different maturity:
>
>| Maturity      | YTM           | 
>| ------------- |:-------------:| 
>| 1             | 6%            | 
>| 2             | 6.2%          |
>| 3             | 6.6%          |  


<details>
  <summary>Click for Solution!</summary>

#### Solution
1. The option will not be exercise because the strike price \$112 is higher than market price \$100. You lose the \$4 you paid for the option.
2. In this case, you gain 4 for selling the option.
3. The option will be exercise because the strike price \$112 is lower than market price \$120. You lose the \$4 you paid for the option but gain \$8 (120-112) for exercising the option. 
</details>  

#### Practice
>See [Problem 1](#problem-1)

## Credit Risk Models

If an asset pays a stream of payoffs over multiple time periods, then we
can use a discount rate to calculate the value to the consumer of a entire
sequence of payoffs.

<a id='equation-eq-infinite-sums'></a>
$$
\begin{aligned}
\sum_{t=0}^{\infty} \beta^t & = \frac{1}{1-\beta}\\
\sum_{t=0}^{\tau} \beta^t &= \frac{1- \beta^{\tau+1}}{1-\beta}\\
\sum_{t=\tau}^{\infty} \beta^t &=  \frac{\beta^{\tau}}{1-\beta}
\end{aligned} \tag{2}
$$

<a id='exerciselist-1'></a>

**EXAMPLE 1A**

> Consider a 1-year zero-coupon bond that has a BBB rating. Assume that this bond is senior secured (historical recovery rate = 63.5%). The yield on a 1-year zero-coupon Treasury bond is 6%. What should be the yield on this BBB-rated bond? (Assume periodicity of 1)

[Walk-through](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)

- **Step 1**: Calculate the payoff 
- **Step 2**: Calculate the payoff 
- **Step 3**: Calculate the payoff

>See practice problem 1A-1 in the [*Problem List*](#problemlist-1)

## Practice Problems

### Problem 1
Consider a 1-year zero-coupon bond that has a CCC rating. Assume that this bond is senior secured (historical recovery rate = 42.7%). The yield on a 1-year zero-coupon Treasury bond is 2%. What should be the yield on this CCC-rated bond? (Assume periodicity of 1)

<details>
  <summary>Click for Solution!</summary>
    
#### Solution

- The yield on this BBB-rated bond is **15.02022**

</details>    

([*back to text*](#example-1a))
