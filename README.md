# Food Waste Analysis and Prevention

## Overview
This project analyzes food consumption and wastage patterns at events to help reduce food waste and prevent potential shortages. The analysis identifies key factors driving waste and provides actionable insights for better food planning.

## About the Data
The data comes from a food company and contains records about various events where food was provided. The data provides information about factors like the type of food served, the number of guests, the event's location and season, and importantly, how much food was wasted.

## Goal of the Analysis 
The Analysis aims to reduce the food wastage and prevent potential food shortages at events, ensuring there is always enough food for everyone and nothing goes to waste. It would help in understanding the reasons for wastage, and help guide the company to control and prevent it.

## Overview of the data and variables involved in the dataset :
The dataset consists of 1782 records and 11 columns. Of the 11 columns - 7 are of categorical type and other 3 are numeric.

- **Type of Food:** Meat, fruits, baked goods, dairy, etc. (categorical)  
- **Number of Guests:** Attendees at the event (numeric)  
- **Event Type:** Corporate, wedding, birthday, social gatherings (categorical)  
- **Quantity of Food:** Amount ordered for an event (numeric)  
- **Storage Conditions:** Room temperature or refrigerated (categorical)  
- **Purchase History:** Regular or occasional customer (categorical)  
- **Seasonality:** Winter, summer, or all seasons (categorical)  
- **Preparation Method:** Sit-down dinner, buffet, or finger food (categorical)  
- **Geographical Location:** Suburban, urban, or rural (categorical)  
- **Pricing:** Low, moderate, high (categorical)  
- **Wasted Food Amount:** Total food thrown away (numeric)  


## How do the variables relate with one another?
From the plots like the heatmap we can say that : 
● The total amount of food prepared is also strongly related to the number of guests. More guests mean more food was prepared.
● However, a weak relationship was observed between the number of guests and the food waste per person. This suggests that simply having a bigger or smaller event doesn't necessarily mean each individual person will waste more or less.

## Research Questions Addressed
**Question 1: What is the most common event type and location in our data?**
Answer: The majority of the events are corporate gatherings, and they primarily take place in suburban areas. Hence, we can say that the food is most often being consumed in the suburban area and where our focus should be for making improvements.

**Question 2: Which food types are most at risk for being wasted?**
Answer: The plots show that fruits and baked goods are the most frequently wasted food types. Fruits, in particular, show a very high percentage of wastage in some cases, with one event having nearly 16% of fruits wasted. Hence, better planning is required for these specific food items.

**Question 3: How does the way in which food is being served affects the overall amount of waste?**
Answer: The most common preparation method for all events is a sit-down dinner, especially for corporate events and weddings. Whereas, buffets are the least common. Hence, we can say that clients prefer more formal dining styles, and hence have more control over food portions being wasted.

**Question 4: Does storing food differently or holding an event in a different season have a big impact on waste?**
Answer: The average percentage of food wasted is nearly the same for both refrigerated and room-temperature items, irrespective of the seasons. Therefore, changing the storage conditions will not significantly reduce overall waste.

**Question 5: How does the number of events compare between different storage conditions?**
Answer: As per the analysis, a higher number of events involve the food stored at room temperature as compared to events with refrigerated food. Hence, a large portion of the company’s data involves events where food that isn't refrigerated.

**Question 6: What's the relationship between the number of guests and the amount of food prepared?**
Answer: We can say that there is a very strong, positive relationship between the number of guests and the total amount of food prepared, as more people require more food.

**Question 7: Do different types of events have different waste patterns depending on the season?**
Answer: Although the average waste percentage is similar across all seasons, there is a little difference within each event type. For example, the average percentage of waste for social gatherings is higher in the summer and winter compared to all-season. Hence we can say that, seasonality might have a small effect on waste for specific types of events.

## Conclusion
The analysis provides a view into the company’s food wastage patterns. The food company should focus on corporate events in suburban areas, with a special focus on managing fruits and baked goods. While changing storage conditions might not have a major impact on waste, understanding the relationships between factors like the number of guests and food quantity can help the food company plan more effectively and achieve the goal of preventing food shortages.

Implementing these insights can help reduce waste and ensure sufficient food at all events.

