# British Airways Reviews | Tableau Dashboard
![showcase](https://github.com/user-attachments/assets/04bbc344-f620-4a7e-9dd8-e367f73d5fe7)
A comprehensive analysis of customer reviews for British Airways utilizing a Tableau Dashboard.
## Background and Overview
British Airways, established in 1974, is the second largest airline in the United Kingdom. Headquartered in London with Heathrow Airport as its primary hub, the airline serves as a major global carrier with a diverse customer base spanning leisure travelers, business passengers, and long-haul international routes. Given the competitive nature of the airline industry and the importance of customer loyalty, understanding consumer sentiment is critical for improving service quality and maintaining brand reputation.

This project leverages a Tableau dashboard to analyze customer review data in order to detect patterns, measure satisfaction levels across different service areas, and identify underperforming touchpoints in the customer journey. The dashboard is designed to provide stakeholders with filterable, interactive insights that highlight both strengths and opportunities for improvement.

Insights are provided on the following key areas:
1) Overall Rating and Service Category Scores
- Customer reviews are broken down into an overall satisfaction score and six key service dimensions: Cabin Staff Service, Entertainment, Food, Ground Service, Seat Comfort, and Value for Money.
- Comparing the average ratings across these categories helps uncover which service areas most strongly influence overall satisfaction. For example, high “Cabin Staff Service” ratings may mitigate weaker scores in “Entertainment” or “Food,” while consistently low “Value for Money” ratings may signal pricing perceptions that need to be addressed.
2) Sentiment Trends Over Time and Across Segments
- The dashboard tracks sentiment changes by month, country, and aircraft type, enabling the detection of both long-term patterns and short-term anomalies.
- Geographic analysis helps reveal differences in expectations across markets. For instance, customers departing from North America may prioritize comfort and entertainment differently than those from Europe.
- Aircraft analysis enables the identification of passenger preferences across cabin classes and traveler types, providing valuable insights when evaluating potential fleet expansion or reduction decisions.
3) Traveler Characteristics and Their Relationship to Satisfaction
- Satisfaction levels are segmented by seat type (First, Business, Economy, Premium Economy) and traveler type (Solo, Couple, Family, Business).
- These relationships provide insight into which customer segments are most at risk of dissatisfaction and where tailored improvements or marketing strategies could strengthen brand loyalty.


## Data Structure and Info
|   column name       |     data type     |     column name     | data type           |   
|  -------------------| ------------------| ------------------- |---------------------|           
|   review_title      |    string         |       recommended   |       string        |
|       author        |       string      |     trip_verified   |    string           |
|     date            |     date          |     rating          |     integer         |
|    place            |     string        |      seat_comfort   |      integer        |     
|     content         |character varying  | cabin_staff_service |  integer            |    
|   aircraft          |     string        | food_beverages      | integer             |
| traveller_type      |       string      |  ground_service     | integer             |
|     seat_type       |       string      | value_for_money     | integer             |
|     route           |       string      | entertainment       | integer             |
| date_flown          |        date       |
## Executive Summary 
### Overview of Findings
This dashboard acts as a high-level overview of satisfaction across multiple customer service metrics. While it highlights several actionable insights, its true value lies in identifying areas that warrant deeper investigation. Immediately apparent insights include consistently low ratings in Entertainment and significantly higher quantity of UK reviewers than anyone else. Areas requiring deeper investigation include the perceived value of the 777-200 in premium economy, business class satisfaction volatility in 2022, and geographic differences in expectations (e.g. UK vs US).
### Findings
- Entertainment is consistently rated lowest amongst all other metrics, especially by those traveling in economy class.
- The Boeing 777-200 is rated highest (or tied for highest) for value in every cabin except premium economy where it's rated the lowest.
- In 2022, overall ratings from business class travelers peaked at 8.0 in February, and saw lows of 1.0 in October.
- The highest number of reviews comes from the United Kingdom at 843, followed by the United States at 128.
### Recommendations
1) Enhance In-Flight Entertainment:
- Address the consistently low entertainment ratings by expanding content libraries, improving seatback systems, or offering bring-your-own-device streaming options. To avoid major hardware investments and maintenance upkeep, explore partnerships with popular streaming services to increase perceived value. Once updated, market the new changes to economy class passengers to inform them.
2) Further Surveying:
- Conduct surveys and focus groups with Premium Economy passengers to identify whether dissatisfaction stems from seat design, legroom, cabin layout, or perceived value relative to ticket price. 
- Increase customer feedback from other countries to balance reviews. Ratings may be shaped by how different regions perceive value, comfort, or service quality. More segmented analysis by market could help distinguish drivers of satisfaction.
- Poll Business Class passengers to determine if rating volatility is due to uncontrollable operational issues or the in-flight experience. Many Business Class travelers are professionals traveling for work. Operational issues such as ATC delays can heavily affect the "Overall" rating. While customers are justified in becoming frustrated for missing work due to uncontrollable delays, British Airways is not directly at fault but may still incur negative remarks as a result. If it is determined that in-flight service was to blame, implement stronger quality control and service consistency measures to ensure Business Class customers receive a dependable premium experience.
3) Leverage and Balance Geographic Feedback
- Prioritize addressing concerns raised by UK travelers since they represent the bulk of current feedback and likely form the airline’s core customer base.
- Encourage more reviews from US passengers through incentives such as loyalty program points or post-flight email prompts, and use the resulting data to better understand differences in customer expectations. Focus on fulfilling requests and suggestions shared by both UK and US travelers to enhance satisfaction among the core UK customer base and build trust and loyalty with new US customers.
## Assumptions, Limitations, and Caveats
### Assumptions
- Customer reviews are representative of the broader passenger base and accurately reflect the typical traveler experience.
- Ratings across service categories are comparable and reflect consistent interpretations of scoring scales by customers.
### Limitations
- The dataset may be biased toward customers who are motivated to leave reviews, often those with very positive or very negative experiences.
- Reviews do not capture all aspects of the travel experience. 
### Caveats
- Satisfaction levels may vary with external factors outside British Airways’ control, for example airport facilities or weather disruptions.
- Differences in cultural expectations across regions could skew ratings; what constitutes "good service" in one market may not align with another.
- Customer perceptions may be influenced by comparisons with competing airlines, which could bias satisfaction ratings independently of British Airways’ actual service delivery.

