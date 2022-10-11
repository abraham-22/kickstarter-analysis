# Louise’s Crowdfunding Campaign
## 1.	Overview of Project and the purpose of this analysis
Louise wants to raise fund for her up-and-coming playwright called “Fever”. The budget for the playwright is estimated over $10,000. As a result, she become reluctant to begin her fundraising campaign. The purpose of this analysis to help Louise organize, sort, and analyze crowdfunding data specific factors that make a project's campaign successful. In addition help her to see trend and outcomes of all categories by vizualization of the data.


## 2.	Analysis and Challenges
Analysis:
To perform the analysis, first on the new sheet I created a table (Shown Below). I filtered the Kickstarter Spreadsheet, I Copied the Successful Outcomes and the failed Outcomes to a new different Sheet. I named the new Sheets- Successful Outcomes and Failed Outcomes, respectively. Then using =COUNTIFS Excel Function (Example: =COUNTIFS(Kickstarter!D:D,">1000",Kickstarter!D:D,"<=4999") I got the number of Successful, Failed and Canceled Outcomes. Using Excel =SUM function I calculated the Total Projects. The Percentage Successful and Percentage Failed calculated by dividing the Number of Outcomes by the Total projects multiplied by 100. I used Nesting formulas =IFERROR (Example: =IFERRO`R((C3/D3),0)) function to fix error.
