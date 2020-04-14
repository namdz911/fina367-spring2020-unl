<div class="sidebar">
  <a href="#readme.html"><i class="fa fa-fw fa-home"></i> Home</a>  
  <a class="active">Module 5</a> 
  <a href="credit_risk.html">Credit Risk
  <ul><li><a href="credit_risk.html#credit-ratings">Credit Ratings</a> </li>    
  <li><a href="credit_risk.html#credit-risk-models">Credit Risk Models</a> </li>
  <li><a href="credit_risk.html#bond-factor-models">Bond Factor Models</a> </li>
  <li><a href="credit_risk.html#practice-problems">Practice Problems</a> </li>    
</ul>
  <a class="active">Module 6</a>     
  <a href="call_put_option.html">Callable and Putable Bonds <ul><li><a href="call_put_option.html#introduction-to-options">Introduction to Options</a> </li>    
  <li><a href="call_put_option.html#introduction-to-bonds-with-embedded-options">Introduction to Bonds with Embedded Options</a> </li>
  <li><a href="call_put_option.html#Gains and Loses from Calling a Bond">Gains and Loses from Calling a Bond</a> </li>
  <li><a href="call_put_option.html#Pricing Callable Bonds">Pricing Callable Bonds</a> </li>
  <li><a href="call_put_option.html#Return on Callable Bonds">Return on Callable Bonds</a> </li> 
  <li><a href="call_put_option.html#practice-problems">Practice Problems</a> </li>     
</ul>
  <a href="convertible_bonds.html">Convertible Bonds
  <ul><li><a href="convertible_bonds.html#introduction-to-convertible-bonds">Introduction to Convertible Bonds</a> </li>
  <li><a href="convertible_bonds.html#traditional-analysis-of-convertibles">Traditional Analysis of Convertibles</a> </li>
  <li><a href="convertible_bonds.html#pricing-convertible-bonds">Pricing Convertible Bonds</a> </li>
  <li><a href="convertible_bonds.html#practice-problems">Practice Problems</a> </li> 
</ul>
   
<link rel="stylesheet" type="text/css" href="./sidebar.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">      
</div>





# Callable and Putable Bonds

**Before you start**
- Optional Readings: Chapter 9.2 - 9.4
- <a href="./pdf/intro_to_option.pdf" target="_blank">Link to download PowerPoint Slides!</a>


## Outline

![alt text](./pic/test2.png) <a href="https://use.vg/i2TvPm" target="_blank">Link to Video!</a>

- [Callable and Putable Bonds](#callable-and-putable-bonds)  
  - [Introduction to Options](#introduction-to-options)  
  - [Introduction to Bonds with Embedded Options](#introduction-to-bonds-with-embedded-options)  
  - [Gains and Loses from Calling a Bond](#gains-and-loses-from-calling-a-bond) 
  - [Pricing Callable Bonds](#pricing-callable-bonds)  
  - [Return on Callable Bonds](#return-on-callable-bonds)  
  - [Duration and Convexity of Callable Bonds](#duration-and-convexity-of-callable-bonds) 
  - [Practice Problems](#practice-problems) 

---

<a id='problem-1'></a>
#### ![](./pic/note1515.png) Problem 1
You buy a call option and buy a put option on bond X. The strike price of the call option is \$90 and the strike price of the put option is \$90. The call option premium is \$5 and the put option premium is \$2. Both options can be exercised only on their expiration date, which happens to be the same for the call and the put. If the price of bond X is \$100 on the expiration date, what is your total payoff and then total profit from the options portfolio?

<details>
  <summary>Click for Solution!</summary>
    
#### Solution

 - At \$100, the call option would be exercised and the payoff to the buyer would be **100-90=10**.
 - At \$100, the put option will not be exercised and the payoff to the buyer would be **0**.
 - The total payoff from the options portfolio would be **10**.
 - The total profit from the options portfolio is **10-5-2=3**.

</details>    

([*back to text*](#example-3))

<a id='problem-2'></a>
#### ![](./pic/note1515.png) Problem 2
You sell a call option and buy a put option on bond X. The strike price of the call option is \$90 and the strike price of the put option is \$105. The call option premium is \$5 and the put option premium is \$2. Both options can be exercised only on their expiration date, which happens to be the same for the call and the put. If the price of bond X is \$100 on the expiration date, what is your total payoff and then total profit from the options portfolio?

<details>
  <summary>Click for Solution!</summary>
    
##### ![](./pic/light.png) Solution

 - At \$100, the call option would be exercised and the payoff to the seller would be **–(100-90)=-10**.
 - At \$100, the put option will be exercised and the payoff to the buyer would be **105-100=5**
 - The total payoff from the options portfolio would be **-5**.
 - The total profit from the options portfolio is **-5+5-2=-2**. (loss)
</details>    

([*back to text*](#example-3))

<a id='problem-3'></a>
#### ![](./pic/note1515.png) Problem 3
Consider an 27 year 12.3 % coupon bond with \$1,000 par selling for \$937 (semi-annual coupons). 
 - Suppose that the first par call for this bond is 1 years from now. 
 - Assume that the bond is putable at par in 17 years. 
 - If the call/put dates above are the only ones, what is the bond’s yield to worst? 

<details>
  <summary>Click for Solution!</summary>
    
##### ![](./pic/light.png) Solution
 - Annualized YTM = **13.1562%**
 - Annualized YTFPC = **19.5374%**
 - Annualized YTFPP = **13.2406%**
 - Notice that there is no YTFC. So just compare the yields that you have to get YTWorst = **13.1562%**

</details>    
&nbsp    

([*back to text*](#example-3))

</div>
