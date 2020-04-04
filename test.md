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

<a id='example-1'></a>

**Part 1**

<iframe title="Option Payoff/Profit Example 1" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/jm6QFCvQm9O9"></iframe>

>Consider a call option on bond X with an exercise price of \$112 that expires in 3 months. Today the option’s price is \$4.
> - What is your payoff if you buy the option today and in 3 months bond X is selling for \$100? What is your profit/loss?


<details>
  <summary>Click for Solution!</summary>

##### ![](./pic/light.png) Solution
- Go through this set of questions:
    - Who get to decide? **You**
    - Will it be exercised? **No! you have a call option and because the price at expiration is less than the strike price (100 < 112).**
    - What’s the payoff? **Payoff is 0 because the option is not excercised.**
    - Did you pay or receive the premium? **You paid the premium because you are the buyer.**
    - What is the profit/loss? **0 - 4 = -4**

</details> 

##### Now try to solve the next Parts !

---

<a id='example-2'></a>

**Part 2**

 - Try to solve Part 2 now by following the list of questions and pay attention to the position you are taking now!

>Consider a call option on bond X with an exercise price of \$112 that expires in 3 months. Today the option’s price is \$4.
> - What is your payoff if you sell the option and in 3 months bond X is selling for \$100? What is your profit/loss?


<details>
  <summary>Click for Solution!</summary>

##### ![](./pic/light.png) Solution
- Go through this set of questions:
    - Who get to decide? **Whoever buys the option.**
    - Will it be exercised? **No! because you have a call option and the price at expiration is less than the strike price (100 < 112).**
    - What’s the payoff? **Payoff is 0 because the option is not excercised.**
    - Did you pay or receive the premium? **You receive the premium because you are the seller.**
    - What is the profit/loss? **0 + 4 = 4**

</details> 

---

<a id='example-3'></a>

**Part 3**

 -  Part 3 is different from the other two examples in that the price of the underlying is now different. How would that affect your decision to exercise the option?

>Consider a call option on bond X with an exercise price of \$112 that expires in 3 months. Today the option’s price is \$4.
> - What is your payoff if you buy the option and in 3 months bond X is selling for \$120? What is your profit/loss?



<details>
  <summary>Click for Solution!</summary>

##### ![](./pic/light.png) Solution
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

<a id='example-3'></a>

**Example 1**

<iframe title="Example 1 - Yield Measures" width="512" height="288" allowTransparency="true" mozallowfullscreen webkitallowfullscreen allowfullscreen style="background-color:transparent;" frameBorder="0" src="https://app.vidgrid.com/embed/DeUQk7qsy8nm"></iframe>
  

>Consider  an 18-year 11% coupon bond with \$1,000 par selling for \$1,169 (semi-annual coupons). The first call date is 8 years from today and the call price is $1,055. 
> - What is the bond’s yield to maturity (semiannual BEY)?
> - What is the bond’s yield to first call?
> - Suppose that the first par call for this bond is 13 years from now. What is the bond’s yield to first par call?
> - Assume that the bond is putable at par in 5 years. What is the bond’s yield to put?
> - If the call/put dates above are the only ones, what is the bond’s yield to worst?



<details>
  <summary>Click for Solution!</summary>

##### ![](./pic/light.png) Solution
 - YTM = Y(N =18\*2=36, PMT = 0.11\*1000/2=55, PV=-1169, FV=1000)= **4.5385%**. Annualized YTM = **9.0770%**
 - YTFC = Y(N =8\*2=16, PMT = 0.11\*1000/2=55, PV=-1169, FV=1055)= **4.2675%**. Annualized YTFC = **8.5350%**
 - YTFPC = Y(N =13\*2=26, PMT = 0.11\*1000/2=55, PV=-1169, FV=1000)= **4.3965%**. Annualized YTFPC = **8.7930%**
 - YTFPP = Y(N =5\*2=10, PMT = 0.11\*1000/2=55, PV=-1169, FV=1000)= **3.4709%**. Annualized YTFPP = **6.9418%**
 - YTWorst = YTFPP = **6.9418%**

</details> 

#### Practice
- See [Problem 3](#problem-1) for more practice!

---

## Gains and loses from calling a bond
(To Be Updated)

([*back to top*](#callable-and-putable-bonds)!)

## Pricing callable bonds
(To Be Updated)

([*back to top*](#callable-and-putable-bonds)!) 

## Return on callable bonds
(To Be Updated)

([*back to top*](#callable-and-putable-bonds)!)

## Duration and Convexity of callable bonds
(To Be Updated)

([*back to top*](#callable-and-putable-bonds)!)

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

([*back to text*](#example-3))
