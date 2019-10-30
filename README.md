# trends-national-grid-energy

Analysis of the US Energy consumption, generation, and price (2011 – 2019) inspecting the statistical significance of seasonality. 
-	Data received from the U.S. Energy Information Administration API. 
Final slides: https://docs.google.com/presentation/d/1psjsPQoepz7btcCh_vs4VHV5TJp_xXzh_wPcNyBuboo/edit#slide=id.g62caadd6f4_0_2

Areas of Research:
1. Sources of Electricity  (fuel types)
2. Seasonality of:	
    -Net Generation	
    -Consumption
    -Price

# Question 1: (Consumption)
What is the difference in New York's electricity consumption per season?
    H0: Mean fuel consumption of each season are equal
    H1: Mean fuel consumption of each season are not equal

Final result: We Reject the H0 because the means of fuel consumption are not equal

    **Natural Gas**
        P-value < Alpha = Reject the H0
        NY is consuming much more natural gas in the summer months vs other seasons.
        Natural Gas takes up majority of fossil fuel consumption. 
    **Coal**
        P-value > Alpha = Fail to Reject the H0
        Coal consumption is a bit higher in the winter but fairly similar compared to other months.
    **Petroleum Liquids**
        P-value < Alpha = Reject the H0
        The average petroleum liquid consumption is a bit higher in the winter 
    **Petroleum Coke**
        P-value > Alpha = Fail to Reject the H0
        New york consumes much less petroleum coke then the other 3 Fossil Fuels


