# Beyond the Lights: Charting Los Angeles' Entertainment Scene

### Overview
- An in-depth exploration of Los Angeles' entertainment scene, leveraging data from SeatGeek to weave a narrative that delves into event popularity, venue significance, and pricing dynamics, providing insights into the heartbeat of LA's vibrant entertainment pulse.

![](https://i.postimg.cc/GhZw6kYR/Dashboard2.png)

### Objective
- The project aimed to showcase data analysis and visualization skills using Python and Excel, addressing key questions about the entertainment scene in Los Angeles. This data was consolidated and presented in an interactive Excel dashboard, offering a rich narrative and actionable insights for event organizers, marketers, or any stakeholder interested in the pulse of LA's entertainment landscape.

---

### Data Understanding
- **Stakeholder(s)**: The primary stakeholders for this project are event organizers, marketers, and entertainment enthusiasts who wish to gain insights into Los Angeles' dynamic entertainment scene.

- **Business Problem**: The objective was to decipher the underlying patterns of event popularity, venue significance, and pricing dynamics in the LA entertainment market. By analyzing these aspects, the goal was to offer insights that can guide event strategy, marketing campaigns, and understand the consumer pulse in the realm of live entertainment.

- **Data Source**: The primary data was sourced from the SeatGeek Platform API, which provided detailed information about events, venues, performers, and related metrics for the Los Angeles area. This data served as the foundation for the exploration and narrative crafted in the project.

![](https://i.postimg.cc/tJcQq6Mh/Drill-Down1.png)
- *A first drill down into understanding live events from the view of 'scores' which attribute estimated sales volumes at the event, performer, venue level.*

![](https://i.postimg.cc/W32PXTZJ/Drill-Down2.png)
- *A drill down specifically around Price and it's impact across various aspects of event data such as venue, performer, and over time.*

![](https://i.postimg.cc/sXwCLqPH/Drill-Down3.png)
- *Data here focused around lead times, and how that may have an impact on price over time*

![](https://i.postimg.cc/L4QM3d8n/Pivot3.png)
![](https://i.postimg.cc/tC1GrrsD/Pivot1.png)
- *Invidial worksheets were leveraged to organize the dashboard and individual drill downs, this is one example of it. Leveraging pivot tables, and pivot charts to refine the visual needed before moving it to its final location.*

### Evaluation
- Data Analysis Tools: The project's analysis was intricately carried out using Excel, leveraging a diverse range of functions and features. Key tools and functions include:
    - **PIVOT TABLES** for data summarization and categorization.
    - **DATA VALIDATION** for creating interactive dropdown menus to guide user navigation.
    - **VLOOKUP & XLOOKUP** for cross-referencing and data retrieval across tables.
    - **AVERAGE, AVERAGEIFS, COUNTIFS** to calculate metrics and filter data based on specific criteria.
    - Text manipulation through **LEFT, MID, RIGHT, CONCATENATE**.
    - **Macros & VBA** for automation and enhanced workbook interactivity.
    - **DATE FUNCTIONS** like **MONTH, YEAR, DAY** to dissect and understand time-based trends.
    - Various charting tools, from bar charts to scatter plots, to visualize the data and craft the narrative.

- Key Insights Derived:
    - Music events, in terms of volume, lead the entertainment sector, yet demand intricacies are shaped by both the artist and the venue characteristics.
    - Event prices display seasonality, with distinct trends appearing during festive periods and at the onset of summer.
    - The prominence of venues in determining event allure was evident, with specific venues distinctly influencing demand and attendance.

- Visualization & Presentation: Excel's visualization tools were harnessed to present the data. From bar charts representing event distribution to scatter plots detailing pricing dynamics, the visuals offered a comprehensive perspective of LA's entertainment dynamics. Interactivity was emphasized with clickable elements and buttons, guiding the user seamlessly through the narrative.

---

### Conclusion
- This project encapsulates a comprehensive exploration of Los Angeles's entertainment scene through a detailed analysis of event data. By dissecting the intricate relationships between event types, pricing dynamics, venue influence, and temporal patterns, a vivid picture of the city's entertainment pulse emerges. The Excel dashboard serves as a storytelling medium, providing a user-friendly interface that not only presents data but also provokes questions and curiosity.

- Key actionable insights from this analysis can guide:
    - **Event Organizers** in understanding when to announce events for maximum impact, and how pricing strategies might differ based on the type of event and venue.
    - **Marketers** in identifying peak periods for specific events, aiding in more targeted promotional campaigns.
    - **Venue Owners** in understanding their standing and influence in attracting audiences and how to enhance the venue experience further.
    
**Future Considerations**:
  
   1. **Deeper Dive into Outliers**: A focused analysis on events that deviate significantly from the norm, like those with exceptionally high prices or popularity scores, to understand the unique factors driving their success.
   2. **External Factors Analysis**: Integrate external datasets like social media trends, citywide events, or tourism data to see how they influence entertainment demand.
   3. **Demographic Analysis**: By pairing with demographic or audience data, one could analyze preferences by age, gender, or other factors, offering a deeper understanding of the audience landscape.
   4. **Feedback Loop**: Sharing the dashboard with actual event organizers, marketers, or venue owners for feedback can offer new perspectives and refinement areas.
   5. **Regular Updates**: As with any dynamic sector, the entertainment scene will evolve. Periodic data refreshes and analyses can track these changes, ensuring the insights remain relevant and timely.
   6. **Integration with Other Data Platforms**: Explore the possibility of combining this data with other platforms like Spotify for music events or sports analytics tools for sports events to offer a more holistic view.

Through the journey of this project, the narrative approach not only provides insights but also showcases the potential of data in telling captivating stories, making it an essential tool for decision-makers in the entertainment sector.

#### Credit
- [SeatGeek API Documentation](https://platform.seatgeek.com/)
