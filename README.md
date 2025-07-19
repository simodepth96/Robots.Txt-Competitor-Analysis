# Robots.Txt Competitor Analysis

I’ve always found competitor analysis involving robots.txt files to be a bit of a headache because there's not a heck of a tool out there that just makes the cut. 

But recently I was found responsible for carrying out a competitive analysis from a technical SEO standpoint and I couldn't help but including a breakdown of this infamous txt file for all competitors. 

To streamline the process, I built a Python workflow using Advertools to fetch and parse robots.txt files, and Plotly to visualize disallowed directives across competitors with advanced heatmaps. 


In this repository, you will find access to the raw python exported from Google Colab: 
https://github.com/simodepth96/Robots.Txt-Competitor-Analysis/blob/main/Robots_txt_Competitor_Analysis.ipynb




The script breaks down a sample of 4 competitors from the publishing industry and returns:
- Distribution of Blocked User-Agents: An overview of each site's blocked user-agents
<img width="1307" height="506" alt="image" src="https://github.com/user-attachments/assets/7a6bf2e4-b062-4394-88c7-782addc16a86" />
- Distribution of Disallowed Directives (After Rule-based clustering): A heatmap to visually compare blocked groups of page templates
<img width="1321" height="497" alt="image" src="https://github.com/user-attachments/assets/2f3461fa-a3c5-460a-92a3-293216b45b22" />
 



