# E-commerce Website Analytics Dashboard with Google Looker Studio and Google Analytics 4

### Project Overview 
The dashboard below is designed using canva.com and implemented in Google Looker Studio (previously called "Google Data Studio") using data from Google Analytics 4.

### Data Source 
The e-commerce website is for a used computer and electronic store local to Vancouver. It has been a successful business but would like some online exposure. The data used in this data visualization project is from Google Analytics 4. I tagged the e-commerce website using Google Tag Manager and tracked website data for 2 months.

### Proposal 
While Google Analytics 4 offers dashboard customization features, I chose to import the Google Analytics 4 data into Google Looker Studio to build the dashboard for the following reasons: 
- Google Looker Studio allows for more extensive customization options, enabling the creation of more complex and visually appealing dashboards.
- Google Looker Studio offers advanced analytics features, including modeling, calculations, and data exploration, providing deeper insights into the data.
However, an advantage of using the Google Analytics 4 dashboard is that it provides real-time data, whereas Looker Studio processes data in batches. It's important to note that real-time data might be beneficial for websites with highly frequent and time-sensitive activities. However, since the website's activities don't occur very frequently and the focus is on long-term business strategies, real-time data doesn't seem to be extremely necessary for this specific scenario.
#### Proposed metrics and graphs 
**Dashboard 1**: 
***Business questions***:
1. What are the volume of traffic on the website? 
2. Do users find the content of the website engaging? Is it easy to engage with the website?
3. How the sales are performing? 
4. How do customers / users find the website? 
***Related metrics***: 
- Views: 
- Total users: This metric represents the total number of unique users who have initiated at least one session on the website. We want to know how this number changes overtime in the chosen time period and how it compares to the last time period, so we need a line graph to show the changes over time as well as a percentage change comparing to the previous period (which is a feature we can turn on in Google Looker Studio) 
- Engaged sessions: In GA4, this metric represents the number of sessions during which users actively engaged with the website. Meaningful engagements or actions include clicks, scrolls, and form submissions. A high number of engaged sessions is generally a positive sign of user satisfaction and interest. On the other hand, a low number of engaged sessions indicates that users do not find the content engaging. We would like to track this metric to evaluate how interesting the content on the website is.
Since the products on the website are updated on a daily basis, we are keen on understanding how user engagement changes over time and how it compares to the previous periods to gauge the attractiveness of the products. Therefore, I have designed a line graph to visualize these changes and included a percentage change comparison feature to assess how the current engagement level compares to the same time in the previous period.
- Total revenue: This metric represents the total sales within the chosen period of time. We want to know how this number changes over time and how this is comparing to the previous period   
- Session default channel groups: In GA4, these are predefined categories that classify the sources or channels from which traffic to the originates. These default channel groups are automatically assigned to sessions based on the source and medium of the traffic. We would like to know 
- Interactivity:
  - Device category 
  - Default data / data control: 
  - Select data range 
<br>
**Dashboard 2**: 
- Views by day 
- Most visited pages 
- Device category
- Top user locations
- Top age groups 
- Top sources / mediums 
- Interactivity 
  - Default data 
  - Select date range 

#### Proposed Dashboard Sketches
![proposed_page1](proposal_page1.png)
<br>
![proposed_page1](proposal_page2.png)

### Final Dashboards 
**Note:** The final dashboards contain sensitive internal data, so I have covered the actual numbers and metrics, and will only show the structure of the dashboard. 
![final_dashboard1](dashboard1.jpg)
<br>
![final_dashboard1](dashboard2.jpg)

### Insights and Findings 


### Actionable Items  
