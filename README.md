# PT.TransJakarta-Data-Analysis-Focusing-Elderly-Passenger

The success of this analysis will be measured by the ability to provide actionable recommendations that can be implemented to enhance the transportation experience for elderly/senior passengers. Ultimately, the aim is to position Transjakarta as a preferred mode of transport for the elderly, thereby promoting their mobility, independence, and quality of life.

##  BackGround
![Transjakarta](https://img4.icarcdn.com/837611/prev-desktop_dki-jakarta-berstatus-ppkm-level-2-transjakarta-sesuaikan-jam-operasional_cover_2022_spanduk-2_1.jpg)

PT. Transjakarta is a public transportation company that operates various services such as BRT (Bus Rapid Transit), Non BRT, Royal Trans, Mikrotrans, Integrated Tourist Bus, and Transjabodetabek in and around Jakarta. In an effort to continuously improve service quality and operational efficiency, PT. Transjakarta conducts monthly evaluations as a form of continuous improvement. These evaluations are crucial in monitoring and improving the performance of the fleet and the operation of routes and stops, especially as the need for reliable and efficient public transportation increases with the growing mobility of Jakarta’s population.
Moreover, PT. Transjakarta is still faced with several issues such as:

1. Understanding Passenger Flow: Analyzing passenger flow data at high-traffic stops like Senayan can provide critical insights into peak hours and routes experiencing congestion, aiding in scheduling adjustments and resource allocation.

2. Infrastructure Enhancement: Based on citizen feedback, recommending infrastructural improvements can address accessibility challenges and enhance overall service quality.

3. Tailoring Services for Vulnerable Groups: Developing facilities and services specifically designed for the elderly can significantly improve their experience and encourage broader ridership.

4. Ensuring Passenger Safety: It’s crucial to explore strategies to bolster safety measures, especially for vulnerable groups like women, to foster a secure environment across Transjakarta’s operational areas.

5. Optimizing Fleet Performance: Utilizing data-driven insights to optimize fleet allocation, maintenance schedules, and operational routes can enhance efficiency, reduce overcrowding, and improve service reliability.

6. Implementing Customer-Centric Solutions: Implementing strategies tailored to passenger needs and comfort levels is key to positioning Transjakarta as a preferred mode of transport.

7. Continuous Monitoring and Evaluation: Emphasizing the need for ongoing evaluations and adaptations based on changing data trends is vital for maintaining and improving service quality in response to evolving passenger demands.

These strategies can help Transjakarta meet passengers’ needs for a comfortable transportation experience and position itself as a reliable and efficient public transportation option. As a Data Analyst at PT. Transjakarta, you are tasked with providing recommendations for the monthly evaluation to optimize the performance of the fleet and the operation of routes/stops based on available data and existing problems. These strategies can help Transjakarta meet passengers’ needs for a comfortable transportation experience and position itself as a reliable and efficient public transportation option.

### Problem Statement

![Transjakarta](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e4/Transjakarta_Route_per_2016.jpg/2560px-Transjakarta_Route_per_2016.jpg)

As the population of Jakarta continues to age, the number of elderly/senior citizens relying on public transportation, specifically Transjakarta, is expected to increase. Despite the critical role of public transportation in promoting mobility and independence among the elderly, there are several challenges that this demographic faces when using these services. These challenges include but are not limited to accessibility issues, safety concerns, and service reliability.

The goal of this data analysis is to identify and understand the specific needs and preferences of elderly/senior passengers in order to enhance their public transportation experience. This involves analyzing various aspects such as:

1. Usage Patterns: Understanding the frequency, timing, and routes most commonly used by the elderly. This can help in identifying peak hours and high-demand routes for this demographic.

2. Accessibility and Convenience: Evaluating the ease of access to and from Transjakarta stops and stations. This includes analyzing the proximity of stops to residential areas with a high population of elderly residents, availability and condition of facilities such as ramps, seating, and signage, among others.

3. Safety Measures: Assessing the safety measures in place, including but not limited to, ease of boarding and alighting, availability of handrails, and measures to prevent overcrowding.

4. Service Quality: Analyzing the reliability and efficiency of the service, including wait times, travel times, and service disruptions.

The insights derived from this analysis will be instrumental in informing strategies and interventions aimed at improving the public transportation experience for elderly/senior citizens in Jakarta. This aligns with PT. Transjakarta’s commitment to continuous improvement and providing high-quality, accessible, and safe public transportation services for all its passengers.


### Column Description

| **Column Name**  | **Description**                                                          | **Additional Info**                        |
| ---------------- | ------------------------------------------------------------------------ | ------------------------------------------ |
| transID          | Unique transaction IDs consisting of alphanumeric strings                |                                            |
| payCardID        | Unique identifiers for payment cards used in transactions                |                                            |
| payCardBank      | Bank names associated with the payment cards                             |                                            |
| payCardName      | Names associated with the payment card owners                            |                                            |
| payCardSex       | Gender of the payment card owners (M or F)                               |                                            |
| payCardBirthDate | Birthdates of the payment card owners                                    |                                            |
| corridorID       | IDs representing different travel corridors or routes                    |                                            |
| corridorName     | Names of the travel corridors or routes                                  |                                            |
| direction        | Binary (0 or 1) representing direction (could indicate travel direction) |                                            |
| tapInStops       | IDs or codes for tapping in at specific stops                            |                                            |
| tapInStopsName   | Names or descriptions of the tapping-in stops                            |                                            |
| tapInStopsLat    | Latitude coordinates of tapping-in stops                                 | Coordinates (Latitude)                     |
| tapInStopsLon    | Longitude coordinates of tapping-in stops                                | Coordinates (Longitude)                    |
| topStartSeq      | Sequence of stops indicating the order of their appearance or occurrence | Sequence of integers indicating stop order |
| tapInTime        | Timestamps indicating the time of entry or tap-in at stops               | Timestamps                                 |
| tapOutStops      | Identifiers or codes for tap-out stops                                   |                                            |
| tapOutStopsName  | Names or labels corresponding to the tap-out stop identifiers            |                                            |
| tapOutStopsLat   | Latitude coordinates for tap-out stops                                   | Coordinates (Latitude)                     |
| tapOutStopsLon   | Longitude coordinates corresponding to the tap-out stops                 | Coordinates (Longitude)                    |
| stopEndSeq       | Sequence of stop endings, indicating the order of stops' ending          | Sequence of integers indicating stop order |
| tapOutTime       | Timestamps indicating the time of exit or tap-out at stops               | Timestamps                                 |
| payamount        | Numerical column representing payment made for transportation            | Currency or fare units                     |

## Overall Observation from Analysis 


1. Proportion of Elderly Passengers: The data indicates a consistent but comparatively low presence of elderly passengers compared to other age groups.

2. Usage Over Time: Elderly passenger usage remains relatively stable but fluctuates daily, showing peaks and troughs in payment amounts.

3. Policy Compliance: Transportation policies emphasize friendliness towards elderly passengers, which necessitates a focus on their specific needs.

4. Bank Card Usage: Adults primarily dominate the usage across all bank cards, while the elderly user count remains relatively low. DKI is the most utilized card, primarily by adults.

5. Corridor Preference: The Ragunan - Gelora Bung Karno corridor is the most frequented by elderly passengers during rush hours, showing consistency both in the morning and evening. Other corridors like Lebak Bulus - Pelukangan witness increased usage during evening rush hours.

6. Peak Hours: Elderly passengers predominantly utilize Transjakarta during early morning (6 AM) and late afternoon to early evening hours (around 16-18 PM) on weekdays, with noticeable dips in midday usage. Weekends exhibit peaks around midday and late afternoon.

9. Travel Duration: Longer travel durations occur during early morning and late evening hours, particularly on Sundays and Wednesdays.

### Conclusion

1. Usage Patterns: Elderly passengers tend to use Transjakarta during specific hours and corridors, indicating potential commuter patterns and preferences.

2. Bank Card Preferences: Elderly users show less preference for digital payment methods compared to adults, potentially due to familiarity or comfort with traditional banking options.

3. Corridor Preference: Certain corridors like Ragunan - Gelora Bung Karno are consistently popular among elderly passengers, indicating potential residential or activity centers along these routes.

4. Low but Consistent Usage: While the number of elderly passengers using Transjakarta is relatively low compared to other age groups, there's a consistent presence.

5. Variability in Daily Payments: Fluctuations in daily payments suggest varying travel patterns among the elderly, potentially indicating specific days with higher or lower usage.

### Recommendation

1. Awareness Campaigns: Increase awareness among the elderly population about the benefits of using Transjakarta, emphasizing convenience, safety features, and specific benefits for seniors.

2. Improved Accessibility: Enhance facilities at stops and buses catering to elderly passengers, including priority seating, clear route information, and improved physical accessibility.

3. Service Optimization: Schedule additional buses or services during peak hours for the elderly, especially on weekdays during early morning and late afternoon.

4. Banking Accessibility: Simplify and promote digital banking options to cater to the elderly demographic, providing easy-to-understand guides and incentives for using these services.

5. Route Revitalization: Prioritize corridors popular among the elderly for potential stop revitalization or enhancements, ensuring these routes cater well to their needs.

6. Data Validation: Conduct surveys or further studies to validate and understand reasons behind elderly preferences, including banking habits, travel duration, and corridor choices.

7. Accessibility and Facilities: Enhance accessibility features such as ramps, priority seating, and clear signage for the elderly within Transjakarta stations and buses.

8. Incentives and Programs: Introduce incentives like discounted fares, loyalty programs, or special services during peak hours to encourage more elderly passengers to use Transjakarta.

9. Evaluate and Adapt: Continuously evaluate the effectiveness of implemented strategies through feedback mechanisms and surveys from elderly passengers. Adapt strategies based on this feedback for continuous improvement.


## Authors

* **Hieremias Kevin Juwantoro** - *Initial work* - [https://github.com/kevinjuwantoro/PT.TransJakarta-Data-Analysis-Focusing-Elderly-Passenger)


