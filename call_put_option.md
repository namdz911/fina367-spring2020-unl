<div class="sidebar">
  <a href="readme.html" class="module"><i class="fa fa-fw fa-home"></i> Home</a>
  <a> </a>   
  <a href="credit_risk.html" class="module"><strong>Credit Risk</strong>  
  <a href="credit_risk.html#credit-ratings">Credit Ratings</a>    
  <a href="credit_risk.html#credit-risk-models">Credit Risk Models</a>
  <a href="credit_risk.html#bond-factor-models">Bond Factor Models</a>
  <a href="credit_risk.html#practice-problems">Practice Problems</a> 
  <a> </a>       
  <a href="call_put_option.html" class="active"><strong>Callable and Putable Bonds</strong>
  <a href="call_put_option.html#introduction-to-options">Introduction to Options</a>    
  <a href="call_put_option.html#introduction-to-bonds-with-embedded-options">Introduction to Bonds with Embedded Options</a> 
  <a href="call_put_option.html#gains-and-loses-from-calling-a-bond">Gains and Loses from Calling a Bond</a> 
  <a href="call_put_option.html#pricing-callable-bonds">Pricing Callable Bonds</a> 
  <a href="call_put_option.html#return-on-callable-bonds">Return on Callable Bonds</a> 
  <a href="call_put_option.html#practice-problems">Practice Problems</a>
  <a> </a>     
  <a href="convertible_bonds.html" class="module"><strong>Convertible Bonds</strong>
  <a href="convertible_bonds.html#introduction-to-convertible-bonds">Introduction to Convertible Bonds</a> 
  <a href="convertible_bonds.html#traditional-analysis-of-convertibles">Traditional Analysis of Convertibles</a> 
  <a href="convertible_bonds.html#pricing-convertible-bonds">Pricing Convertible Bonds</a> 
  <a href="convertible_bonds.html#practice-problems">Practice Problems</a> 
  <a> </a>
  <a href="mortgage.html" class="module"><strong>Residential Mortgages</strong>
  <a href="mortgage.html#introduction-to-residential-mortgages">Introduction to Residential Mortgages</a> 
  <a href="mortgage.html#risks-associated-with-investing-in-mortgages">Risks Associated with Investing in Mortgages</a>
  <a href="mortgage.html#residential-mortgage-backeds-securities">Residential Mortgage-backed Securities</a>    
  <a> </a>        
<link rel="stylesheet" type="text/css" href="./sidebar.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">      
</div>
      
<div class="main">


# Callable and Putable Bonds

**Before you start**
- Optional Readings: Chapter 9.2 - 9.4
- <a href="./pdf/callable_putable_bonds.pdf" target="_blank">Link to download PowerPoint Slides!</a>


## Outline

- [Callable and Putable Bonds](#callable-and-putable-bonds)  
  - [Introduction to Options](#introduction-to-options)  
  - [Introduction to Bonds with Embedded Options](#introduction-to-bonds-with-embedded-options)  
  - [Gains and Loses from Calling a Bond](#gains-and-loses-from-calling-a-bond) 
  - [Pricing Callable Bonds](#pricing-callable-bonds)  
  - [Return on Callable Bonds](#return-on-callable-bonds)  
  - [Duration and Convexity of Callable Bonds](#duration-and-convexity-of-callable-bonds) 
  - [Practice Problems](#practice-problems) 
- In Class Example List: Option Payff/Profit Examples([P1](#example-op1), [P2](#example-op1), [P3](#example-op1)), Example [1](#example-1), [2](#example-2), [3](#example-3), [4](#example-1), [5](#example-5), [6](#example-6), [7A](#example-7a), [7B](#example-7b).
---

## Introduction to Options
([*back to top*](#callable-and-putable-bonds)!)

 - For this section, it is crutial to understand how option works? how the decision to exercise is made and what the payoff structure looks like?
 - The section would be the prerequisite for Bonds with Embedded Options.  

#### ![](./pic/dollarnew15.png) What is an Option?

 - Definition and Basic Features of Options

<iframe title="What is an Option?" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/0I1pi5Y0HGHH"></iframe>
  
  
---

#### ![](./pic/dollarnew15.png) Option Payoff/Profit Diagrams

 - The use of diagrams and some assumptions to generate the the ones that we need.

<iframe title="Option Payoff/Profit Diagrams P1" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/c7H9RoVYggEa"></iframe>
  

---

 - How to draw the diagram for 4 option positions: **`Buy a Call`, `Sell a Call`, `Buy a Put`, `Sell A Put`**
     - To navigate within the video to different option positions, click on the **`Chapter`** button on the video (The second button on the top right corner of the video)
  
<iframe title="Option Payoff/Profit Diagrams P2" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/naNuXeunh3b6"></iframe>
  
  
---

#### ![](./pic/note1515.png) Option Payoff/Profit Examples 

<a id='example-op1'></a>

**Part 1**

(*Read the Example and think before you watch!*)


<iframe title="Option Payoff/Profit Example 1" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/jm6QFCvQm9O9"></iframe>


>Consider a call option on bond X with an exercise price of \$112 that expires in 3 months. Today the option’s price is \$4.
> - What is your payoff if you buy the option today and in 3 months bond X is selling for \$100? What is your profit/loss?


<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution
- Go through this set of questions:
    - Who get to decide? **You**
    - Will it be exercised? **No! you have a call option and because the price at expiration is less than the strike price (100 < 112).**
    - What’s the payoff? **Payoff is 0 because the option is not excercised.**
    - Did you pay or receive the premium? **You paid the premium because you are the buyer.**
    - What is the profit/loss? **0 - 4 = -4**

</details> 

##### Now try to solve the next Parts !

---

<a id='example-op2'></a>

**Part 2**

 - Try to solve Part 2 now by following the list of questions and pay attention to the position you are taking now!

>Consider a call option on bond X with an exercise price of \$112 that expires in 3 months. Today the option’s price is \$4.
> - What is your payoff if you sell the option and in 3 months bond X is selling for \$100? What is your profit/loss?


<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution
- Go through this set of questions:
    - Who get to decide? **Whoever buys the option.**
    - Will it be exercised? **No! because you have a call option and the price at expiration is less than the strike price (100 < 112).**
    - What’s the payoff? **Payoff is 0 because the option is not excercised.**
    - Did you pay or receive the premium? **You receive the premium because you are the seller.**
    - What is the profit/loss? **0 + 4 = 4**

</details> 

---

<a id='example-op3'></a>

**Part 3**

 -  Part 3 is different from the other two examples in that the price of the underlying is now different. How would that affect your decision to exercise the option?

>Consider a call option on bond X with an exercise price of \$112 that expires in 3 months. Today the option’s price is \$4.
> - What is your payoff if you buy the option and in 3 months bond X is selling for \$120? What is your profit/loss?



<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution
- Go through this set of questions:
    - Who get to decide? **You**
    - Will it be exercised? **Yes! because you have a call option and the price at expiration is higher than the strike price (120 > 112).**
    - What’s the payoff? **Payoff is 120 - 112 = 8 because the option is excercised.**
    - Did you pay or receive the premium? **You paid the premium because you are the buyer.**
    - What is the profit/loss? **8 - 4 = 4**

</details> 

#### Practice
- See [Problem 1](#problem-1) and [Problem 2](#problem-2) for more practice!



(*You're done with a section! Good Job!*)

---

## Introduction to Bonds with Embedded Options 

([*back to top*](#callable-and-putable-bonds)!)

#### ![](./pic/dollarnew15.png) Callable and Putable bonds 

<iframe title="Bonds With Embedded Options " width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/kkoVdcTWPoRV"></iframe>
  
  
---

#### ![](./pic/dollarnew15.png) Yeild Measures for Callable and Putable Bonds 

<iframe title="Yield Measures " width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/njl3cJqeho8T"></iframe>
   
---

<a id='example-1'></a>

#### ![](./pic/note1515.png) Example 1

(*Read the Example and think before you watch!*)


<iframe title="Example 1 - Yield Measures" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/DeUQk7qsy8nm"></iframe>
  

>Consider  an 18-year 11% coupon bond with \$1,000 par selling for \$1,169 (semi-annual coupons). The first call date is 8 years from today and the call price is $1,055. 
> - What is the bond’s yield to maturity (semiannual BEY)?
> - What is the bond’s yield to first call?
> - Suppose that the first par call for this bond is 13 years from now. What is the bond’s yield to first par call?
> - Assume that the bond is putable at par in 5 years. What is the bond’s yield to put?
> - If the call/put dates above are the only ones, what is the bond’s yield to worst?



<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution
 - YTM = Y(N =18\*2=36, PMT = 0.11\*1000/2=55, PV=-1169, FV=1000)= **4.5385%**. Annualized YTM = **9.0770%**
 - YTFC = Y(N =8\*2=16, PMT = 0.11\*1000/2=55, PV=-1169, FV=1055)= **4.2675%**. Annualized YTFC = **8.5350%**
 - YTFPC = Y(N =13\*2=26, PMT = 0.11\*1000/2=55, PV=-1169, FV=1000)= **4.3965%**. Annualized YTFPC = **8.7930%**
 - YTFPP = Y(N =5\*2=10, PMT = 0.11\*1000/2=55, PV=-1169, FV=1000)= **3.4709%**. Annualized YTFPP = **6.9418%**
 - YTWorst = YTFPP = **6.9418%**

</details> 

#### Practice
- See [Problem 3](#problem-3) for more practice!

(*You're done with a section! Good Job!*)

---

## Gains and loses from calling a bond

([*back to top*](#callable-and-putable-bonds)!)

#### ![](./pic/dollarnew15.png) When should the issuer call a callable bond? 

<iframe title="Gain and Losses from Calling P1" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/QRni97L1KfWc"></iframe>
  
  
---

<a id='example-2'></a>

#### ![](./pic/note1515.png) Example 2

(*Read the Example and think before you watch!*)


<iframe title="Example 2 - Gain &amp; Loses from Calling" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/3CCLHrEjh7Yi"></iframe>

>Consider a bond with the following characteristics: 30 years to maturity, 12% coupon rate, interest paid semi-annually, \$1000 par value, \$1050 call price, and no call protection. If rates fall to 11.5% will the company gain from calling the bond? Assume that there were no transaction costs.



<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution
 - PV of Liability = **\$1041.9596**
 - Call the Bond? **No, Because PV of liability is less than Call Price of \$1055**

</details> 

#### Practice
- See [Problem 4](#problem-4) for more practice!

---

<a id='example-3'></a>

#### ![](./pic/note1515.png) Example 3

(*Read the Example and think before you watch!*)


<iframe title="Example 3 - Gains &amp; Losses from Calling" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/7Fs0BEjRSkfi"></iframe>

>Consider a bond with the following characteristics: 30 years to maturity, 12% coupon rate, interest paid semi-annually, \$1000 par value, \$1050 call price, and no call protection. If rates fall to 9% will the company gain from calling the bond? Assume that there were no transaction costs.
> - What if by calling the bond the company incurred transaction costs of $200 per bond? Would it still call the bond?
> - Where does the benefit/gain come from?
> - You believe that interest rates will fall even more to 8.9% next year. Will you call the issue today or wait until next year? 

<details>
  <summary>Click for Solution!</summary>

#### ![](./pic/light.png) Solution

 - PV of Liability=PV(N=60,Y=4.5,PMT=60,FV=1000)=**\$1309.5703** 
 - Because PV of Liability (1309.5703) is now higher than 1050, **the bond will be called**. 
 - Gains/Loss will be: 1309.5703 – 1050 = **\$259.5703**
 - What if by calling the bond the company incurred transaction costs of \$200 per bond? Would it still call the bond?
     - If there is transaction cost, then Gains/Loss will be: 1309.5703 – 1050 – 200 = **$59.5703**
 - Where does the benefit/gain come from? 
     - **The difference between interest paid for old bond and new bond** (You are responsible for the calculations described in the Video).
 - You believe that interest rates will fall even more to 8.9% next year. Will you call the issue today or wait until next year? 
     - **We should call the bond now!** (You are responsible for the calculations described in the Video).

</details> 

#### Summary for Calling Decision
 - A company will call a bond when the PV of the future liability is greater than the sum of the call price and the transaction cost.
 - A decrease in interest rates (below the coupon rate on the bond) is a necessary but not a sufficient condition for calling a bond.
 - The issuer can issue a new bond at lower interest rate and use the proceed to retire existing bond. 
 - An issue will be called as soon as there is a gain from doing so.

---

#### ![](./pic/dollarnew15.png) From the Bondholders' Perspective?

 - Reinvestment Risk and Price Compression.

<iframe title="Callable Bonds Investors&#039; Risks" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/77IGp1tMavns"></iframe>

  


(*You're done with a section! Good Job!*)

---

## Pricing callable bonds

([*back to top*](#callable-and-putable-bonds)!) 

#### ![](./pic/dollarnew15.png) Pricing Framework for Callable Bonds

<iframe title="Pricing Framework for Callable Bonds" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/FjKN2PY2XAEu"></iframe>
  
  
---

#### ![](./pic/dollarnew15.png) Black-Scholes Option Pricing Model

<iframe title="Black Scholes Option Pricing Model" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/eNBsXcQKMqnM"></iframe>
  
  
---

<a id='example-4'></a>

#### ![](./pic/note1515.png) Example 4

(*Read the Example and think before you watch!*)


<iframe title="Example 4 - Pricing Callable Bonds" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/8uXTPbJJMblN"></iframe>
  

>The term structure of interest rates is flat at 10%, but rates could change immediately to 12% or 8% with equal probability and stay at that level forever. You >purchase a callable bond with 30 years to maturity and 10% coupon paid annually.  
> - What should be the price of the callable bond, if it can be called immediately at \$105?
> - What is the value of the call option embedded in the callable bond?
> - What is the callable bond’s spread over the yield of an otherwise identical non-callable bond?

<details>
  <summary>Click for Solution!</summary>
    
#### ![](./pic/light.png) Solution
 - The price of the callable bond is **\$94.4448**
 - The price of the straight bond is **\$103.2026**
 - The price of the embedded call option is  **\$8.7578**
 - The YTM of the Callable bond is **10.62%** and the YTM of the straight bond is **9.6696%**. The yield spread of the callable bond over the straight bond is **0.9504%** or **95.04 bps**
 
</details>  

#### Practice
- See [Problem 5](#problem-5) for more practice!

---


<a id='example-5'></a>

#### ![](./pic/note1515.png) Example 5

(*Read the Example and think before you watch!*)

<iframe title="Example 5 - Pricing Callable Bonds" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/IaeEEqLJsXVK"></iframe>
  
>The term structure of interest rates is flat at 10%, but rates could change immediately to 12% or 8% with equal probability and stay at that level forever. You >purchase a callable bond with 30 years to maturity and 10% coupon paid annually.  
> - What should be the price of the callable bond, if it has a call price of \$105 and call protection of 5 years?


<details>
  <summary>Click for Solution!</summary>
    
#### ![](./pic/light.png) Solution
 - R = 12%:  Determine if the bond will be called 5 years from now?
    - PV of liability = PV(N=25,Y=12,PMT=10,FV=100)=84.3137 < 105 -> **No Call** 
    - The bond continue to pay like a straight bond thus 
    - Price = PV(N=30,Y=12,PMT=10,FV=100)=**83.8896**
 - R = 8%: Determine if the bond will be called 5 years from now?
    - PV of liability = PV(N=25,Y=8,PMT=10,FV=100)=121.3496 > 105 -> **Call**
    - The bond pays 5 more coupons and then pay the call price at the end of 5 year
    - Price = PV(N=5,Y=8,PMT=10,FV=105)=**111.3883**
 - Price of Callable bond = 0.5\*83.8896 + 0.5\*111.3883 = **97.6390**

 
</details>  

#### Practice
- See [Problem 6](#problem-6) for more practice!

---

#### ![](./pic/dollarnew15.png) Pricing putable Bonds

Base on our discussion of callable bond, try to convince yourself of the followings:
 - Price of Putable Bond = Price of Non-putable Bond + Price of Put Option
     - The price of a putable bond will be higher than that of a straight bond
     - The yeild of a putable bond will be lower than that of a straight bond
     
     
*Hint: Ask yourself who gets to decide/benefit from putable bond? when would they decide to exercise the option?* 
  
---

<a id='example-6'></a>

#### ![](./pic/note1515.png) Example 6

(*Try to solve this Example by yourself with the hint*)

>The term structure of interest rates is flat at 10%, but rates could change immediately to 12% or 8% with equal probability and stay at that level forever. You >purchase a putable bond with 30 years to maturity and 10% coupon paid annually.  What should be the price of the bond, if it can be put immediately at par?
>
> *Hint: Steps are exactly the same as Example 5 except that we have to determine when the bond is put.*


<details>
  <summary>Click for Solution!</summary>
    
#### ![](./pic/light.png) Solution
Now we want to see things from the perspective of the investor because he is the one who makes decisions.
 - R = 12%: 
    - Price = PV(N=30,Y=12,PMT=10,FV=100)=83.8896 < 100 -> **Put** - Investor will sell the bond back at the put price -> p = **100**
 - R = 8%: 
    - Price = PV(N=30,Y=8,PMT=10,FV=100)=122.5156 > 100 -> **No Put** - Investor can sell the bond in the open market for more than 100 -> p = **122.5156**
 - Price of Putable bond = 0.5\*100 + 0.5\*122.5156 = **111.2578**

 
</details>  

#### Practice
- See [Problem 7](#problem-7) for more practice!


(*You're done with a section! Good Job!*)

---

## Return on callable bonds

([*back to top*](#callable-and-putable-bonds)!)

#### ![](./pic/dollarnew15.png) Comparing the expected return and realized return of callable bonds and non-callable bonds

<iframe title="New combined video" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/BpNuGE9zw0h3"></iframe>
  
---

<a id='example-7a'></a>

#### ![](./pic/note1515.png) Example 7A

>Calculate 1-yr expected return for a straight and callable bond with the following characteristics (these are the bonds from Examples 4-5)
> - Rates are expected to immediately change to 12% or 8% with equal probability, and when they change they will stay at that level forever.
> - At purchase, the straight bond has 30 years to maturity, 10% coupon paid annually, \$100 par value and price of \$103.1366. 
> - At purchase, the callable bond has 30 years to maturity, 10% coupon paid annually, \$100 par value, is callable at \$105 and it has call protection of 5 years. Its price is \$97.639. 

<details>
  <summary>Click for Solution!</summary>
    
#### ![](./pic/light.png) Solution
 - **Straight Bond:**
    - At 12%: Price = PV(N=29,Y=12,PMT=10,FV=100)=83.9564
    - At 8%: Price = PV(N=29, Y=8,PMT=10,FV=100)= 122.3168
    - Price = 83.9564\*0.5 + 122.3168\*0.5 = 103.1366
    - Return = (103.1366 + 10 – 103.2026)/103.2026 = 0.0963 = **9.63%**
 - **Callable Bond:**
    - At 12%: Price = PV(N=29,Y=12,PMT=10,FV=100)=83.9564
    - At 8%: Price = PV(N=4, Y=8,PMT=10,FV=105)= 110.2994
    - Price = 83.9564\*0.5 + 110.2994\*0.5 = 97.1279
    - Return = (97.1279 + 10 – 97.6390)/97.6390 = 0.0972 = **9.72%**
 - **Expected return on callable bonds is higher**


 
</details>  

#### Practice
- See [Problem 7](#problem-7) for more practice!

<a id='example-7b'></a>

#### ![](./pic/note1515.png) Example 7B

>How do the realized returns of callable and non-callable bonds in Example 7A compare?


<details>
  <summary>Click for Solution!</summary>
    
#### ![](./pic/light.png) Solution
 - **At 12%:**
    - Ret of Callable = (83.9564 + 10 – 97.6390)/ 97.6390 = -0.0377 = **-3.77%**
    - Ret of Straight = (83.9564 + 10 – 103.2026)/ 103.2026 = -0.0896 = **-8.96%**
 - **At 8%:**
    - Ret of Callable = (110.2994 + 10 – 97.6390)/ 97.6390 = 0.2321 = **23.21%**
    - Ret of Straight = (122.3168 + 10 – 103.2026)/ 103.2026 = 0.2821= **28.21%**
 - **If interest rate goes up to 12%, callable bond outperform straight bond.**
 - **If interest rate goes down to 8%, straight bond outperform callable bond.**



 
</details>  

#### Practice
- See [Problem 7](#problem-7) for more practice!

## Practice Problems

([*back to top*](#callable-and-putable-bonds)!)

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
&nbsp  

([*back to text*](#example-op3))

<a id='problem-2'></a>
#### ![](./pic/note1515.png) Problem 2
You sell a call option and buy a put option on bond X. The strike price of the call option is \$90 and the strike price of the put option is \$105. The call option premium is \$5 and the put option premium is \$2. Both options can be exercised only on their expiration date, which happens to be the same for the call and the put. If the price of bond X is \$100 on the expiration date, what is your total payoff and then total profit from the options portfolio?

<details>
  <summary>Click for Solution!</summary>
    
#### ![](./pic/light.png) Solution

 - At \$100, the call option would be exercised and the payoff to the seller would be **–(100-90)=-10**.
 - At \$100, the put option will be exercised and the payoff to the buyer would be **105-100=5**
 - The total payoff from the options portfolio would be **-5**.
 - The total profit from the options portfolio is **-5+5-2=-2**. (loss)
</details>    
&nbsp  

([*back to text*](#example-op3))

<a id='problem-3'></a>
#### ![](./pic/note1515.png) Problem 3
Consider an 27 year 12.3 % coupon bond with \$1,000 par selling for \$937 (semi-annual coupons). 
 - Suppose that the first par call for this bond is 1 years from now. 
 - Assume that the bond is putable at par in 17 years. 
 - If the call/put dates above are the only ones, what is the bond’s yield to worst? 

<details>
  <summary>Click for Solution!</summary>
    
#### ![](./pic/light.png) Solution
 - Annualized YTM = **13.1562%**
 - Annualized YTFPC = **19.5374%**
 - Annualized YTFPP = **13.2406%**
 - Notice that there is no YTFC. So just compare the yields that you have to get YTWorst = **13.1562%**. Never leave out **YTM** !!

</details>    
&nbsp  

([*back to text*](#example-1))

<a id='problem-4'></a>
#### ![](./pic/note1515.png) Problem 4
Consider a bond with the following characteristics: 19 years to maturity, 10.60% coupon rate, interest paid semi-annually, \$1,000 par value, \$1,030 call price, and no call protection. If rates change to 7.90% will the company gain from calling the bond? Assume that transaction cost is \$273.

<details>
  <summary>Click for Solution!</summary>
    
#### ![](./pic/light.png) Solution
 - PV of Liability = **\$1263.3559**
 - Gains/Losses = **-\$39.6441** (Don't forget to account for transaction cost)
 - Call the Bond? **No**
</details>    
&nbsp  

([*back to text*](#example-2))

<a id='problem-5'></a>
#### ![](./pic/note1515.png) Problem 5

The term structure of interest rates is flat at 7.4 %, but rates could change immediately to 9.4 % or 5.4 % with probability of 0.68 and 0.32 , respectively, and stay at that level forever. You purchase a callable bond with 30 years to maturity and 7.4 % coupon paid annually. The callable bond can be called immediately at \$ 107.

 - What should be the price of the callable bond?
 - What is the value of the call option embedded in the callable bond?
 - What is the callable bond’s spread over the yield of an otherwise identical non-callable bond?

<details>
  <summary>Click for Solution!</summary>
    
#### ![](./pic/light.png) Solution
 - The price of the callable bond is **\$88.7489**
 - The price of the straight bond is **\$95.9142**
 - The price of the embedded call option is  **\$7.1653**
 - The YTM of the Callable bond is **8.4413%** and the YTM of the straight bond is **7.7546%**. The yield spread of the callable bond over the straight bond is **0.6867%** or **68.67 bps**
 
</details>    
&nbsp  

([*back to text*](#example-4))

<a id='problem-6'></a>
#### ![](./pic/note1515.png) Problem 6

The term structure of interest rates is flat at 6.3 %, but rates could change immediately to 8.3 % or 4.3 % with probability of 0.14 and 0.86 , respectively, and stay at that level forever. You purchase a callable bond with 28 years to maturity and 6.3 % coupon paid annually. The callable bond can be called at \$ 121 with a call protection period of 7 years. 

 - What should be the price of the callable bond?
 - What is the value of the call option embedded in the callable bond?
 - What is the callable bond’s spread over the yield of an otherwise identical non-callable bond?

<details>
  <summary>Click for Solution!</summary>
    
#### ![](./pic/light.png) Solution
 - The price of the callable bond is **\$120.6486**
 - The price of the straight bond is **\$124.6828**
 - The price of the embedded call option is  **\$4.0342**
 - The YTM of the Callable bond is **4.9253%** and the YTM of the straight bond is **4.6973%**. The yield spread of the callable bond over the straight bond is **0.2280%** or **22.8 bps**
 
</details>    
&nbsp  

([*back to text*](#example-6))

<a id='problem-7'></a>
#### ![](./pic/note1515.png) Problem 7

The term structure of interest rates is flat at 9.4 %, but rates could change immediately to 11.4 % or 7.4 % with probability of 0.66 and 0.34 , respectively, and stay at that level forever. You purchase a putable bond with 28 years to maturity and 9.4 % coupon paid annually. The putable bond can be put at \$ 97 immediately. 

 - What should be the price of the putable bond?
 - What is the value of the put option embedded in the putable bond?
 - What is the putable bond’s spread over the yield of an otherwise identical non-putable bond?

<details>
  <summary>Click for Solution!</summary>
    
#### ![](./pic/light.png) Solution
 - The price of the putable bond is **\$105.9642**
 - The price of the straight bond is **\$96.9288**
 - The price of the embedded put option is  **\$9.0354**
 - The YTM of the putable bond is **8.8195%** and the YTM of the straight bond is **9.7226%**. The yield spread of the putable bond over the straight bond is **-0.9031%** or **90.31 bps**
 
</details>    
&nbsp  

([*back to text*](#example-6))!

([*back to top*](#callable-and-putable-bonds)!)

</div>
