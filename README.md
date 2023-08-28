# Care-Management-Dashboard-for-Suffolk-City-Council-UK-

Suffolk County Council (United Kingdom)

Summary
The project was built with the Adult Social Care department in mind as the main
user/audience. Data was sourced from the Care Quality Commision (UK). 

Three (3) dashboards were built:

1. Suffolk Adult Care Insights
This dashboard presents an array of interactive visualizations that provides quick
insights into the quality of adult care in Suffolk.
2. Query Dashboard
The Query Dashboard is an intuitive interface for the adult care team to generate
niche insights from the data.
3. Location Specific Info
The drill-down button on the Query Dashboard lands on the ‘Location Specific Info’
interface. Here, all the information needed about the selected provider or Location is
presented.

Overall, the goal was to build a system that caters to the needs of everyone on the
team, regardless of whether it is the busy executive who needs quick insights as
talking point in the next meeting or for the analyst looking for more specific
information about the providers and locations across Suffolk

Methodology
Data Exploration
- Explored the data in Microsoft Excel to get an understanding of the features and
how they relate with each other.
- Found that most of the features are categorical and took note of a few that seem
important.
- Found Provider ID to be a common feature between Location and Providers. With
that, both dataset can be modeled for analysis.

Define Audience
Having taken a look at the data, I defined the audience as the “Adult Social Care) team at
Suffolk County Council (SCC). The team will need insights from the data to provide advisory
for individuals supported by the Council. More importantly, the team wants to keep tabs on
the quality of care delivered across the County.

Case Study
One of the many practical ways SCC could use insights from the dashboard is when
individuals who are supported by the council are looking to choose a provider for their care.
The SCC team can only advice on options to choose from and that advisory process is best
done when it is informed by data. The “Query Dashboard” provides a quick access for the
SCC team to input the care preference of the individual to find the best options available.

What Data points are important to the SCC team?
- Number of providers available
- Number of Locations available
- How often are ratings been done across the county?
- Average rating across towns in the county
- Location/Provider specific information

Data Transformation and Dashboarding
The data is largely categorical and so, not much cleaning could be done as that could mean
fabrication of wrong data, especially in the places where we have null or empty cells.

However, some data transformation process was done:
1. Converting the ‘Latest Rating’ to a scale of 1 to 5 with 5 being the highest
(Outstanding). The numerical ratings scale was then converted to start-shaped scale.
2. Changed Boolean columns with ‘Y/N’ to ‘Yes’ and ‘No’ respectively.

3. The brief explained that the dashboard is focused on adult care therefore some data
category was filtered from the ‘Service/Population Group’, especially does that were
completely focused on children and adolescents. In total, about 7 categories were
filtered.
4. The charts/infographics used across all dashboards were carefully selected to ensure
the insights they carry is intuitive and actionable for the audience.

Limitations
The data is not historical. Lot of trends that could generate new insights were therefor
missed. For instance, it would be very insightful to understand the last rating of each
location and provider. Essentially, we will be able to track whether there was a decline in
the service offered or if the services are becoming better.
