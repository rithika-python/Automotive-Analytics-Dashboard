<h1>Automotive-Analytics-Dashboard</h1>

<H2>OBJECTIVE OF THE DASHBOARD</H2>
To analyze car resale market trends and key factors influencing vehicle value, mileage, and performance to optimize pricing strategies and inventory management.

<h2>ABOUT THE DATASET</h2>
The dataset provides detailed information about used cars, designed for analysis related to car sales. It contains 7,906 rows and 12 columns, covering various attributes of vehicles. Key features include the car's name, year of manufacture, selling_price (indicative of the resale value), and km_driven (distance covered). Additional attributes include the type of fuel (e.g., petrol, diesel), seller_type (such as individual or dealer), transmission type (manual or automatic), and the owner category (e.g., first, second, or third owner). Technical specifications such as mileage_kmpl, engine_cc, max_power, and the number of seats provide insights into vehicle performance and capacity. This dataset is valuable for understanding trends in the used car market and performing predictive analyses.

<H2>DASHBOARD</H2>

![Dashboard Screenshot 1](https://github.com/user-attachments/assets/750f4bd6-bbef-4d81-b5c7-4a9c4b7bd5bf)
![Dashboard Screenshot 2](https://github.com/user-attachments/assets/38fe98a2-0c02-42d7-8962-f41eba052638)
![Dashboard Screenshot 3](https://github.com/user-attachments/assets/0df3d783-e22d-412b-aeea-36a3d0914133)
![Dashboard Screenshot 4](https://github.com/user-attachments/assets/afdc47c5-108a-43fd-be94-d7b1c70ecf80)

<H2>QUESTIONS AND INTERPRETATIONS</H2>
Q1. What is the distribution of cars among different owner types (first owner, second owner, etc.)? 

Graph name: Average Selling Price by Owner Type

Interpretation: 
- First-owner vehicles have the highest average selling price at ₹751,663, indicating that vehicles owned by the original buyer retain higher value.
- Second-owner vehicles show a significant drop in average price (₹415,127), followed by third-owner vehicles (₹315,969), and fourth-and-above-owner vehicles (₹227,529). 
- This suggests a declining trend in value as the number of ownerships increases, likely due to perceived usage and wear.
<br>
Q2. What is the trend in total kilometers driven for cars of different manufacturing years? 

Graph name: Cars Driven vs. Year

Interpretation:
- The bar chart reveals a trend in the number of cars driven over time, grouped by manufacturing year (2012–2020).
- There is higher activity or usage for cars manufactured in recent years (e.g., 2018–2020), as shown by their larger contribution to total "cars driven."
- Older cars (e.g., from 2012) show lower activity levels, possibly due to reduced use or removal from active circulation.
<br>
Q3. How does the average selling price fluctuate over time in 30-minute intervals?

Graph name: Average Selling Price Over Time (30-minute intervals)

Interpretation: 
- The line chart demonstrates fluctuations in the average selling price over the course of the day in 30-minute intervals.
- Peaks occur at certain times, indicating potential high-demand or active selling windows where prices are higher.
- There is an observable dip around 17:00, suggesting reduced demand or activity during this interval.
<br>
Q4.  How does the average selling price vary between different transmission types (Manual, Automatic)?

Graph name: Average Selling Price by Transmission Type

Interpretation:
- Vehicles with manual transmission have a higher representation (79%) and an average selling price of ₹461,779.
- Automatic vehicles represent 21% of the data but have a higher average selling price of ₹176,3115.
- This indicates that while manual transmission vehicles are more common, automatic transmission cars are perceived as premium and command a higher price.
<br>
Q5. Which fuel type supports higher maximum power in cars?

Graph name: Maximum Power Consumption between Fuel Types

Interpretation: 
- Vehicles using Diesel have the highest maximum power (671 units), indicating Diesel-powered vehicles are typically more powerful.
- Petrol vehicles rank second in terms of maximum power, with a value of 280 units.
- CNG and LPG vehicles have relatively low maximum power, with CNG at 258 units and LPG at 68.1 units.
- Diesel vehicles dominate in maximum power output, followed by Petrol, with alternative fuels like CNG and LPG being less powerful.
<br>
Q6. How does the average mileage vary between manual and automatic transmission cars?

Graph name: Average Mileage by Transmission Type

Interpretation: 
- Manual transmission vehicles have a slightly higher average mileage (19.7) compared to Automatic transmission vehicles (17.6).
- Manual transmission vehicles are marginally more fuel-efficient than their automatic counterparts in this dataset.
<br>
Q7. How does the average maximum power vary across different fuel types?

Graph name: Average Maximum Power by Fuel Type 

Interpretation: 
- Diesel vehicles lead with the highest average maximum power, slightly exceeding 100 units.
Petrol and CNG vehicles follow, with average maximum power values around 80 and 60 units, respectively.
- LPG vehicles have the lowest average maximum power, well below 60 units.
- Diesel vehicles have both the highest maximum and average power, while LPG vehicles are consistently the least powerful.
<br>
Q8. How does the average selling price vary between different owner types?

Graph name: Distribution of Car Ownership Types

Interpretation:
- The majority (66%) of the vehicles are First Owner, suggesting they are primarily owned by their original buyers.
- Second Owner vehicles account for 26%, indicating a moderate share of used car ownership.
- Third Owner and Fourth & Above Owners collectively make up only 8% (6% and 2%, respectively).
- The dataset is dominated by vehicles owned by their first owners, reflecting a market skewed towards newer or single-owner cars.
<br>
Q9. How does the average engine capacity vary across different seat configurations?

Graph name: Average Engine Capacity by Number of Seats 

Interpretation:
- Vehicles with 9 seats have the highest average engine capacity (2447 units), followed by 10-seater vehicles (2315 units).
- Vehicles with 5, 6, and 7 seats have moderate average engine capacities, ranging from 1300 to 2082 units.
- Smaller vehicles, like those with 4 seats, have the lowest average engine capacity (1118 units).
- Engine capacity increases with the number of seats, suggesting larger vehicles (e.g., buses or vans) require more powerful engines.
<br>
Q10. How does the average number of kilometers driven vary between different owner types?

Graph name: Average Kilometers Driven by Owner Type 

Interpretation:
- Vehicles owned by Fourth & Above Owners have the highest average kilometers driven (106,571), followed closely by Third Owner vehicles (101,066).
- Second Owner vehicles have an average of 94,788 kilometers, and First Owner vehicles have the lowest average (56,391).
- Vehicles pass through multiple owners as they accumulate higher mileage. Older or heavily used vehicles tend to be owned by later owners.
<br>
Q11. Which fuel type has the highest average selling price? 

Graph name: Selling Price by Fuel Type 

Interpretation:
- Vehicles using Diesel have the highest average selling price, significantly outpacing other fuel types.
- Petrol vehicles come second in average selling price but are much lower than Diesel vehicles.
- Vehicles running on CNG and LPG have the lowest average selling prices, with CNG slightly higher than LPG.
- Diesel vehicles retain higher resale value, likely due to their durability and efficiency, whereas alternative fuel vehicles like CNG and LPG have lower resale demand.
<br>
Q12. Which are the Top 15 most fuel-efficient cars with mileage greater than 20 kmpl, and what are their fuel types?

Graph name: Top 15 Cars with Highest Mileage Above 20 KMPL

Interpretation:
- The Skoda Rapid 1.5 TDI Ambition has the highest mileage (nearly 25 KMPL).
- Other cars like Hyundai i20 Sportz Diesel, Toyota Etios VXD, and Maruti Alto 800 LXi also feature prominently, with mileage consistently above 20 KMPL.
- Most cars in the list are diesel variants, indicating their dominance in fuel efficiency.
- Diesel cars continue to be the most fuel-efficient, making them a top choice for mileage-conscious buyers.
- Models such as the Skoda Rapid and Hyundai i20 set benchmarks for high mileage in the market.
<br>
Q13.How has the maximum power of petrol cars evolved over the years? 

Graph name: Maximum Power Trend for Petrol Cars Over the Years 

Interpretation:
- Cars from the late 1990s to early 2000s had maximum power outputs below 100 BHP.
- Post-2010, petrol cars saw a noticeable increase in power outputs, with newer models (e.g., 2015-2019) exceeding 150 BHP and even nearing 200 BHP.
- There is a clear upward trend in power capabilities as newer models are introduced.
- Advancements in engine technology have led to higher power outputs in recent years.
- Petrol cars are no longer just about efficiency but also offer enhanced performance, catering to a broader consumer base.
<br>
Q14. How does the number of seats in a car impact its average selling price?

Graph name: Average Selling Price by Seat Capacity 

Interpretation:
- Cars with a 7-seating capacity have the highest average selling price (~815k), reflecting their premium nature.
- Smaller cars, such as 2-seaters, are the least expensive (~300k).
- The selling price increases steadily with seating capacity, peaking for 7-seaters, while 6-seaters (~602k) and 5-seaters (~596k) fall in the mid-range.
- Larger cars, like 7-seaters (SUVs or MPVs), are positioned as premium offerings, appealing to buyers seeking utility and space.
- Compact cars are priced to cater to budget-friendly buyers.
<br>
Q15. How does the average mileage differ between individual sellers and dealers?

Graph name: Average Mileage by Seller Type 

Interpretation:
- The average mileage distribution is similar across seller types:
Dealers: 34%,
Individuals: 34%,
Trustmark Dealers: 32%.
- No significant variation exists in mileage based on the seller type.
- Buyers can expect comparable mileage regardless of whether they purchase from dealers, individuals, or Trustmark-certified dealers.
Seller type is not a key determinant of mileage performance.

<H2>MANAGERIAL INSIGHTS</H2>

1. Ownership Impact on Value:
- First-owner vehicles retain the highest resale value, while value significantly declines with successive ownership. Focus on acquiring and promoting first-owner cars to attract higher-paying buyers.

2. Transmission Preference:
- Despite their smaller market share, automatic vehicles command significantly higher average prices, indicating demand for premium features. Highlight automatic options in premium customer segments.

3. Fuel Efficiency and Mileage Trends:
- Diesel cars dominate in fuel efficiency and retain higher selling prices, making them attractive for both resale and fleet operations. However, highlight CNG for eco-conscious buyers.

4. Power and Performance:
- Diesel vehicles lead in power output, with rising trends in petrol car performance. Invest in models that balance performance with efficiency to cater to diverse buyer preferences.

5. Seat Capacity and Premium Positioning:
- Seven-seater vehicles are priced the highest, showing demand for family-oriented or multi-passenger vehicles. Promote SUVs and MPVs as luxury offerings.

6. Age and Usage Trends:
- Recent model-year vehicles show higher activity and retention of value. Focus inventory sourcing on newer models to align with buyer preferences for reliability and longevity.

7. Market Segmentation by Seller Type:
- Similar mileage performance across seller types suggests buyers may prioritize other factors, such as trust and certification. Promote Trustmark Dealer vehicles for credibility and assurance.

8. High-Mileage Cars and Resale Demand:
- Vehicles with higher mileage are predominantly owned by later owners. For high-mileage cars, target price-sensitive or specific-use customers.

9. Timing for Optimal Sales:
- Average selling prices fluctuate throughout the day, with specific time slots showing peaks. Leverage this data to schedule promotions and auctions during peak demand hours.
<br></br>
