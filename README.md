# trends-national-grid-energy
**Hypothesis Testing**

Analysis of the US Energy consumption, generation, and price (2001 – 2019) inspecting the statistical significance of seasonality.
-	Data received from the U.S. Energy Information Administration API.
Final slides: https://docs.google.com/presentation/d/1psjsPQoepz7btcCh_vs4VHV5TJp_xXzh_wPcNyBuboo/edit#slide=id.g62caadd6f4_0_2

Areas of Research:
1. Sources of Electricity  (fuel types)
2. Seasonality of:
    -Net Generation
    -Consumption
    -Price

**Question 1:** (Consumption)
What is the difference in New York's electricity consumption per season?

    H0: Mean fuel consumption of each season are equal
    H1: Mean fuel consumption of each season are not equal

    ***Tests Used:***
    - ANOVA where we compare means across multiple groups (seasons).
    - Tukeys HSD which provided us with multiple comparisons of the mean.

    ***IV:***  Seasons - Discrete
    ***DV:*** Fossil Fuels Consumption(thsnd tons) - Continuous

![image](images/naturalgas_consumption.png = 100x100)
![image](images/coal_consumption.png = 100x100)
![image](images/petliq_consumption.png = 100X100)
![image](images/petcoke_consumption.png = 100X100)
