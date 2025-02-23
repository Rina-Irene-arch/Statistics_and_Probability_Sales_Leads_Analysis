# Statistics and Probability Final Assignment: Sales Leads Analysis
In this [project](https://github.com/Rina-Irene-arch/Statistics_and_Probability_Sales_Leads_Analysis/blob/main/Statistics_and_Probability_Sales_Leads_Analysis.ipynb) we analyze data from 10,000 sales leads to examine the company's sales performance of a recently launched health insurance product.
The [data source](https://github.com/Rina-Irene-arch/Statistics_and_Probability_NAYA_Assignment/blob/main/DRA%20Final%20Assignment%20Data.csv) of gathered the data contains the following parameters:
- ID – a unique identifier of each customer
- AGE GROUP – the age group of the customer
- CHANNEL OF SALE – either “internet” or “phone”, depending on where the customers left their contact
details
- SALES – an indicator variable (1 – successful sale, 0 – unsuccessful sale)
### Question 1
- data source: [DRA Final Assignment Data.csv](https://github.com/Rina-Irene-arch/Statistics_and_Probability_NAYA_Assignment/blob/main/DRA%20Final%20Assignment%20Data.csv)
- **1.01 Probability: task 1**
   - PDF of the 10,000 leads by AGE GROUP and by CHANNEL OF SALE
- **1.02 Probability: task 2**
   - Plot the probability distribution function (PDF) for AGE GROU
- **1.03 Combinatorics & Joint distribution: task 1**
   - How many combinations of AGE GROUP and CHANNEL OF SALE do you expect to see?
- **1.04 Combinatorics & Joint distribution: task 2**
   - Calculate the joint distribution of leads by AGE GROUP and CHANNEL OF SALE
- **1.05 Combinatorics & Joint distribution: task 3**
   - Plot the distribution by AGE GROUP for each CHANNEL OF SALE separately
- **1.06 Conditional probability: task 1**
   - Given that a person belongs to a specific age group, calculate the probability that they will choose to use each CHANNEL OF SALE 
- **1.07 Conditional probability: task 2**
   - Comment on your results – is there a recommendation regarding the CHANNEL OF SALE preference of each group that you can give?
- **1.08 Statistical tests – Chi square for independence: task 1**
   - <details>
      The company wishes to examine the dependence/independence between the choice of CHANNEL OF SALE and the SALES indicator.<br>
      Perform a Chi square test of independence between CHANNEL OF SALE and the SALES indicator.<br>
      - What are the null and alternative hypotheses of this test?<br>
      - Calculate the P-value of the test and state your conclusion at a 5% significance level and at a 1% significance level.
- **1.09 Random variables & CLT: task 1**
   - <details>
      The company wishes to calculate its expected profit:<br>
      - It spends 45$ on acquiring each sales lead<br>
      - Price of each sale is 86$<br>
      Calculate the minimal number of sales (out of 10,000 leads) required to make a profit
- **1.10 Random variables & CLT: task 2**
   - <details>
      The company decides to model the total amount of sales using a Binomial random variable<br>
      - Where n=10,000<br>
      - And p is estimated from the SALES column<br>
      Estimate the value of p
- **1.11 Random variables & CLT: task 3**
   - Using the Binomial random variable, calculate the probability of the total amount of sales being smaller than the number required to make a profit
- **1.12 Random variables & CLT: task 4**
   - Using the Normal approximation of the Binomial random variable, calculate the same probability
- **1.13 Random variables & CLT: task 5**
   - <details>
      Plot the two distributions together – Binomial as bars, Normal as line (you may choose the Xaxis range which is best suitable for your plot). Comment on the appropriateness of the approximation
- **1.14 Random variables & CLT: task 6**
   - The risk manager said: “if we have 0 sales we will lose $450,000 which is very risky for a new product!”. Comment on his statement
### Question 2 
- data source: [DRA Final Assignment Data RAND.csv](https://github.com/Rina-Irene-arch/Statistics_and_Probability_NAYA_Assignment_Sales_Leads_Analysis/blob/main/DRA%20Final%20Assignment%20Data%20RAND.csv)
- <details>
     Simulation<br>
     - The company decided to perform 100 simulations of its potential profit using a Binomial random variable (10,000 Bernoulli variables)<br>
     - Find 10000x100 random variables from a Uniform(0,1) distribution
- **2.01 Simulation: task 1**
   - <details>
      Perform 100 simulations of the possible total profit under these 100 simulations<br>
      - Any number smaller than the estimator for p should be 1 (considered a sale), otherwise it should be 0 (considered no sale)
- **2.02 Simulation: task 2**
   - Estimate the probability of the profit being negative
- **2.03 Simulation: task 3**
   - Comment on your result in relation to your answer using the Binomial and Normal probabilities from the previous section
### Question 3
- data source: [DRA_Final_Assignment_Data_AB_testing.csv](https://github.com/Rina-Irene-arch/Statistics_and_Probability_NAYA_Assignment_Sales_Leads_Analysis/blob/main/DRA_Final_Assignment_Data_AB_testing.csv)
- <details>
     Time series & A/B Testing<br>
     The company decided to launch a media campaign to increase leads:
     - It launched an extensive media campaign during January and February of 2022
     - It tracked daily sales leads for 4 months, to assess the prolonging effect of the campaign
- **3.01 Time series & A/B Testing: task 1**
   - Plot the daily sales leads over time
- **3.02 Time series & A/B Testing: task 2**
    - <details>
      Comment on the existence of:<br>
      - Trends<br>
      - Seasonality<br>
      - Random variability<br>
      - Irregularities & Outliers<br>
- **3.03 Time series & A/B Testing: task 3**
   - Summarize your conclusions regarding the success of the media campaign
- **3.04 TiTime series & A/B Testing: task 3**
    - <details>
      The company has also decided to improve sales rates by having sales managers review the sales team’s performance every 2 weeks, starting January 2022.<br>
      The managers will listen to past recorded calls with potential customers, give feedback and present their conclusions regarding possible improvements in the sales process to the staff every 2 weeks.<br>
      In order to test the effect of the potential improvement in sales practices the company has decided to conduct an A/B test, where half of the staff will receive feedback and the other half will not.<br>
      Exclude days where the company is not working and there are no sales
- **3.05 Tme series & A/B Testing: task 4**
    - Suggest a way of selecting which sales representative goes in which group. What biases is the company trying to prevent?
- **3.06 Time series & A/B Testing: task 6**
    - <details>
      Measure the differences in sales performance during the A/B test:<br>
      - By calculating means for both groups<br>
      - By plotting the sales rates over time<br>
      - By suggesting a suitable statistical test
### Documentation
[Report](https://github.com/Rina-Irene-arch/Statistics_and_Probability_NAYA_Assignment_Sales_Leads_Analysis/blob/main/Naya_DRA_Statistics_Final_Assignment_Rina_Rafalski_A_Fin.pdf): a detailed report covering data analysis and insights, visualizations and explanations.       
