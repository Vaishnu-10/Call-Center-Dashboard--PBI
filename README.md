 Call Centre Trends Report

 Overview

This report provides an analysis of the call centre data for PhoneNow. The goal is to identify key performance indicators (KPIs) and trends to help improve customer service and operational efficiency. We analyzed call data to understand overall customer satisfaction, call handling performance, and agent effectiveness.

 Key Findings and Recommendations

 1. Overall Customer Satisfaction
Finding: The average customer satisfaction rating is 3.4 out of 5, below the target of 4.5.
Explanation: Customer satisfaction is influenced by the speed of answer, resolution rate, and agent performance.
Recommendation:
- Action: Implement training programs to improve agent skills and enhance customer interactions.
- Result: Better-trained agents can handle calls more effectively, leading to higher satisfaction ratings.

 2. Calls Answered vs. Abandoned
Finding: 81.08% of calls are answered, while 18.92% are not answered.
Explanation: A significant number of calls are not being answered, which can frustrate customers.
Recommendation:
- Action: Increase staffing during peak times to ensure more calls are answered.
- Result: Reduced call abandonment rates and improved customer satisfaction.

 3. Speed of Answer
Finding: The average speed of answer is 67.52 seconds.
Explanation: Long wait times can lead to customer dissatisfaction and call abandonment.
Recommendation:
- Action: Optimize call routing and reduce wait times by adding more agents during high-traffic periods.
- Result: Faster response times, leading to improved customer satisfaction.

 4. Call Resolution
Finding: 72.92% of calls are resolved, while 27.08% are not resolved.
Explanation: A high resolution rate is crucial for maintaining customer satisfaction.
Recommendation:
- Action: Implement a follow-up process for unresolved calls to ensure issues are addressed.
- Result: Increased resolution rates and enhanced customer trust.

 5. Agent Performance
Finding: Performance varies significantly across agents.
Explanation: Differences in agent performance can impact overall call centre effectiveness.
Recommendation:
- Action: Introduce performance-based incentives and regular performance reviews.
- Result: Motivation for agents to improve, leading to more consistent and higher performance levels.

 Steps Taken, Visuals Used, and DAX Queries

 Steps Taken
1. Data Collection: Gathered call data including call IDs, agent names, dates, times, topics, whether the call was answered, resolution status, speed of answer, average talk duration, and satisfaction ratings.
2. Data Cleaning: Cleaned the data to ensure accuracy, handling missing values and correcting inconsistencies.
3. Data Analysis: Analyzed the data to find key trends and patterns related to call centre performance.
4. Dashboard Creation: Created a Power BI dashboard to visualize the data and make insights easily understandable.

 Visuals Used
1. Slicers: For agent names and call topics to filter the data.
2. Satisfaction Meter: Displays the average satisfaction rating (3.4) against the target (4.5).
3. Answered vs. Not Answered Calls: A pie chart showing the percentage of answered (81.08%) and not answered (18.92%) calls.
4. Resolved vs. Not Resolved Calls: A pie chart showing the resolution rate (72.92%) vs. not resolved (27.08%).
5. Average Speed of Answer: A gauge showing the average speed of answer (67.52 seconds).
6. Agent Stats Table: Detailed performance metrics for each agent.

 DAX Queries
1. Average Satisfaction: `AVERAGE('Call Data'[Satisfaction])`
2. Answered Calls Percentage: `DIVIDE(COUNTROWS(FILTER('Call Data', 'Call Data'[Answered] = "Y")), COUNTROWS('Call Data'))`
3. Not Answered Calls Percentage: `DIVIDE(COUNTROWS(FILTER('Call Data', 'Call Data'[Answered] = "N")), COUNTROWS('Call Data'))`
4. Resolved Calls Percentage: `DIVIDE(COUNTROWS(FILTER('Call Data', 'Call Data'[Resolved] = "Y")), COUNTROWS('Call Data'))`
5. Not Resolved Calls Percentage: `DIVIDE(COUNTROWS(FILTER('Call Data', 'Call Data'[Resolved] = "N")), COUNTROWS('Call Data'))`
6. Average Speed of Answer: `AVERAGE('Call Data'[Speed of answer in seconds])`

 Conclusion

This report highlights the performance of the PhoneNow call centre and provides actionable recommendations to improve customer satisfaction and operational efficiency. Key areas of focus include enhancing agent training, increasing staffing during peak times, optimizing call routing, and implementing follow-up processes for unresolved calls.

By following these recommendations, PhoneNow can achieve better performance, leading to higher customer satisfaction and retention.
