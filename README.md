## Scenario:
You have been hired as a data analyst for a cybersecurity company. The company wants to improve its security posture by better understanding recent cybersecurity incidents. Your task is to create a Power BI dashboard that provides key insights into the frequency, types, and impact of cybersecurity incidents over the past year. The dashboard will be used by senior management to make informed decisions about security investments and priorities.

## Dataset:
The dataset you will create includes information about different cybersecurity incidents that have occurred over a 12-month period. The dataset should include the following fields:

| Month      | Incident Type | Number of Incidents | Affected Systems | Average Downtime (Hours) | Financial Impact (€) | Severity (1-5) |
|------------|---------------|---------------------|------------------|--------------------------|----------------------|----------------|
| January    | Phishing      | 25                  | 10               | 5                        | 10,000               | 3              |
| February   | Ransomware    | 10                  | 8                | 24                       | 100,000              | 5              |
| March      | DDoS Attack   | 15                  | 5                | 6                        | 50,000               | 4              |
| April      | Phishing      | 10                  | 2                | 1                        | 200,000              | 4              |
| May        | Ransomware    | 7                   | 10               | 8                        | 70,000               | 5              |
| June       | Malware       | 20                  | 15               | 8                        | 30,000               | 4              |
| July       | Phishing      | 18                  | 8                | 5                        | 18,000               | 3              |
| August     | Ransomware    | 5                   | 4                | 20                       | 75,000               | 5              |
| September  | DDoS Attack   | 12                  | 7                | 10                       | 120,000              | 4              |
| October    | Phishing      | 8                   | 3                | 3                        | 40,000               | 3              |
| November   | Ransomware    | 14                  | 12               | 15                       | 90,000               | 5              |
| December   | Malware       | 20                  | 15               | 8                        | 30,000               | 4              |

This dataset includes:
- **Incident Type:** The type of cybersecurity incident (e.g., phishing, ransomware, malware, DDoS).
- **Number of Incidents:** The total number of incidents of that type in the given month.
- **Affected Systems:** The number of systems affected by the incidents.
- **Average Downtime (Hours):** The average number of hours systems were offline or affected by the incident.
- **Financial Impact (€):** The estimated financial impact of the incidents, including costs of remediation, lost revenue, etc.
- **Severity (1-5):** A severity score (1 = low, 5 = critical) based on the impact and urgency of the incident.

## Steps:

### 1. Data Preparation:
- Import the dataset into Power BI and clean up the data if necessary (e.g., handling missing values or inconsistencies).

### 2. Specific Analysis:
- **Incident Frequency Analysis:** Analyze the total number of monthly incidents. Is there a noticeable trend over time (e.g., are incidents increasing towards the end of the year)?
- **Incident Type Impact:** Compare the frequency of each type of incident (e.g., phishing vs ransomware) and analyze which type has caused the most downtime and financial impact.
- **Severity Analysis:** Compare the severity of incidents and identify patterns between the most severe incidents and their impact (both financial and operational).
- **Cost and Downtime Analysis:** Evaluate the financial cost and average downtime per type of incident. Are there any types of incidents that are particularly costly or disruptive?
- **System Impact:** Look at how many systems were affected by different incidents. Which incidents tend to affect the most systems?

### 3. Create a Power BI Dashboard:
Design a dashboard in Power BI that includes the following visualizations:
- **Total Incidents Over Time:** A line graph showing the number of incidents per month. Add a trendline if necessary.
- **Incidents by Type:** A bar chart comparing the number of incidents for each type of cyberattack.
- **Financial Impact per Incident Type:** A stacked column chart showing the financial impact for each incident type over time, allowing the company to understand which incidents are the most costly.
- **Downtime and Severity:** A scatter plot or bubble chart showing the relationship between average downtime and severity, to see which incidents cause the longest disruptions.
- **Affected Systems:** A pie chart or bar graph showing which types of incidents affected the most systems.

### 4. Conclusion and Recommendations:
- In the dashboard, provide a short written summary or key insights section where you explain the most important findings. For example:
  - Are certain types of incidents becoming more frequent over time?
  - Which types of incidents are costing the company the most money or causing the most downtime?
  - Are there particular months where incident frequency spiked?
