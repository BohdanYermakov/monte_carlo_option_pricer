# Monte Carlo Simulation for Option Pricing

This project was created using Python to price  call and put options through Monte Carlo simulation. It plays a crucial role in understanding the behaviour and valuation of financial derivatives under uncertain market conditions. By simulating thousands of potential future stock price paths with Geometric Brownian Motion, this tool provides a robust and adaptable method for estimating option prices under various scenarios.

## Why this project is important 
In the financial markets, accurate option pricing is essential for allowing traders and investors to take well-informed positions and efficiently manage risk. The Black-Scholes formula is one example of a traditional analytical method. It has limits and frequently makes simplifying assumptions that could not hold true in real-world markets. Contrarily, Monte Carlo simulation is a flexible and potent method that can handle a variety of random processes and represent intricate market dynamics, and instead of requiring the equations describing the system's behaviour to be written down, the Monte Carlo approach can solve a problem by directly replicating the actual process.(Pellegrino, 2012)

## Representation of possible outcomes you could have
### Case of the high volatility
![image](https://github.com/BohdanYermakov/monte_carlo_option_pricer/assets/115155367/ccc733c9-529e-4df5-809f-36526049cb64)
![output](https://github.com/BohdanYermakov/monte_carlo_option_pricer/assets/115155367/b3cdbc14-a644-4e23-bba3-60a91a8c4466)
We should outline that the estimated call option price is 21.38. we could state that the standard deviation of the discounted payoffs is 36.61, indicating the variability in the simulation outcomes. The 95% would be a confidence interval for the estimated option price is (19.11, 23.64)This interval means that we are 95% confident that the true option price lies within this range.

Analysis
we can say that estimated price of the call option suggests that it has a value of 21.38 based on the current market conditions.
additionally, the high standard deviation of 36.61 indicates significant variability in the simulation outcomes, reflecting uncertainty in the market.
to add up, 95% confidence interval ranges from 19.11 to 23.64, providing a range within which the true option price is likely to fall.
because, in that case, the estimated option price is lower than the strike price, therefore it would suggests that buying the option might not be profitable unless market conditions improve.

### Case of the low volatility
![image](https://github.com/BohdanYermakov/monte_carlo_option_pricer/assets/115155367/db750743-738f-4e4b-b487-1b2a2c9d3bcf)
![image](https://github.com/BohdanYermakov/monte_carlo_option_pricer/assets/115155367/59696d0c-64a1-4a25-858f-8a2b6c8f1131)

We should outline that the estimated call option price is 6.56. we could state that the standard deviation of the discounted payoffs is 7.60, indicating the variability in the simulation outcomes. The 95% would be a confidence interval for the estimated option price is (6.09, 7.03)This interval means that we are 95% confident that the true option price lies within this range.

Analysis
we can say that estimated price of the call option suggests that it has a value of 6.56 based on the current market conditions.
additionally, the high standard deviation of 7.60 indicates significant variability in the simulation outcomes, reflecting uncertainty in the market.
to add up, 95% confidence interval ranges from 6.09 to 7.03, providing a range within which the true option price is likely to fall.
because, in that case, the estimated option price is lower than the strike price, therefore it would suggests that buying the option might not be profitable unless market conditions improve.

### Case of the long time to maturity
![image](https://github.com/BohdanYermakov/monte_carlo_option_pricer/assets/115155367/3e6e824a-fbb1-4eb7-939c-04fa009f774e)
![output](https://github.com/BohdanYermakov/monte_carlo_option_pricer/assets/115155367/dd8a01f2-b07c-4237-bdde-70f4d15ab257)

We should outline that the estimated call option price is 27.68. we could state that the standard deviation of the discounted payoffs is 38.97, indicating the variability in the simulation outcomes. The 95% would be a confidence interval for the estimated option price is (25.26, 30.09)This interval means that we are 95% confident that the true option price lies within this range.

Analysis
we can say that estimated price of the call option suggests that it has a value of 27.68 based on the current market conditions.
additionally, the high standard deviation of 38.97 indicates significant variability in the simulation outcomes, reflecting uncertainty in the market.
to add up, 95% confidence interval ranges from 25.26 to 30.09, providing a range within which the true option price is likely to fall.
because, in that case, the estimated option price is lower than the strike price, therefore it would suggests that buying the option might not be profitable unless market conditions improve.

### Case of the short time to maturity
![image](https://github.com/BohdanYermakov/monte_carlo_option_pricer/assets/115155367/856c98c7-fac6-4215-8bef-aa743384fe5b)
![output](https://github.com/BohdanYermakov/monte_carlo_option_pricer/assets/115155367/babb0ed7-4560-4d00-8d44-8f47fa33bf24)

We should outline that the estimated call option price is 4.50. we could state that the standard deviation of the discounted payoffs is 6.50, indicating the variability in the simulation outcomes. The 95% would be a confidence interval for the estimated option price is (4.09, 4.90)This interval means that we are 95% confident that the true option price lies within this range.

Analysis
we can say that estimated price of the call option suggests that it has a value of 4.50 based on the current market conditions.
additionally, the high standard deviation of 6.50 indicates significant variability in the simulation outcomes, reflecting uncertainty in the market.
to add up, 95% confidence interval ranges from 4.09 to 4.90, providing a range within which the true option price is likely to fall.
because, in that case, the estimated option price is lower than the strike price, therefore it would suggests that buying the option might not be profitable unless market conditions improve.

### Case of the high risk-free rate
![image](https://github.com/BohdanYermakov/monte_carlo_option_pricer/assets/115155367/52cdffc9-ead3-4fe0-b020-839d91d8b9ca)
![output](https://github.com/BohdanYermakov/monte_carlo_option_pricer/assets/115155367/89617b62-17a0-4a79-8d41-e63e50f33f16)

We should outline that the estimated call option price is 13.25. we could state that the standard deviation of the discounted payoffs is 16.11, indicating the variability in the simulation outcomes. The 95% would be a confidence interval for the estimated option price is (12.25, 14.25)This interval means that we are 95% confident that the true option price lies within this range.

Analysis
we can say that estimated price of the call option suggests that it has a value of 13.25 based on the current market conditions.
additionally, the high standard deviation of 16.11 indicates significant variability in the simulation outcomes, reflecting uncertainty in the market.
to add up, 95% confidence interval ranges from 12.25 to 14.25, providing a range within which the true option price is likely to fall.
because, in that case, the estimated option price is lower than the strike price, therefore it would suggests that buying the option might not be profitable unless market conditions improve.

### Case of the low risk-free rate
![image](https://github.com/BohdanYermakov/monte_carlo_option_pricer/assets/115155367/c7bb8ea0-d14a-4860-85c6-2a0e1828a323)
![output](https://github.com/BohdanYermakov/monte_carlo_option_pricer/assets/115155367/434bd2eb-04e8-44eb-bc2a-ec29ffc6ddcd)

We should outline that the estimated call option price is 8.53. we could state that the standard deviation of the discounted payoffs is 14.20, indicating the variability in the simulation outcomes. The 95% would be a confidence interval for the estimated option price is (7.65, 9.41)This interval means that we are 95% confident that the true option price lies within this range.

Analysis
we can say that estimated price of the call option suggests that it has a value of 8.53 based on the current market conditions.
additionally, the high standard deviation of 14.20 indicates significant variability in the simulation outcomes, reflecting uncertainty in the market.
to add up, 95% confidence interval ranges from 7.65 to 9.41, providing a range within which the true option price is likely to fall.
because, in that case, the estimated option price is lower than the strike price, therefore it would suggests that buying the option might not be profitable unless market conditions improve.
### Case of the put option
![image](https://github.com/BohdanYermakov/monte_carlo_option_pricer/assets/115155367/9d298989-c9a8-43d7-90a4-653e152b3f8a)
![output](https://github.com/BohdanYermakov/monte_carlo_option_pricer/assets/115155367/9b25182a-c7d6-49ab-aba2-1e4d17e3b31b)

We should outline that the estimated put option price is 6.03. we could state that the standard deviation of the discounted payoffs is 9.00, indicating the variability in the simulation outcomes. The 95% would be a confidence interval for the estimated option price is (5.47, 6.58)This interval means that we are 95% confident that the true option price lies within this range.

Analysis
we can say that estimated price of the put option suggests that it has a value of 6.03 based on the current market conditions.
additionally, the high standard deviation of 9.00 indicates significant variability in the simulation outcomes, reflecting uncertainty in the market.
to add up, 95% confidence interval ranges from 5.47 to 6.58, providing a range within which the true option price is likely to fall.
because, in that case, the estimated option price is lower than the strike price, therefore it would suggests that buying the option might not be profitable unless market conditions improve.

## References

Pellegrino, Roberta & Costantino, Nicola. (2012). A Monte Carlo Simulation and Fuzzy Delphi-Based Approach to Valuing Real Options in Engineering Fields. 10.5772/32513. 

https://www.youtube.com/watch?v=pR32aii3shk

https://www.youtube.com/watch?v=6-dhdMDiYWQ

https://www.youtube.com/watch?v=Bi4HMe3-VV4
