# Louise’s Playwright Crowdfunding Campaign
## 1.	Overview of Project and the purpose of this analysis
Louise wants to raise fund for her upcoming playwright called “Fever”. The budget for the playwright is estimated over $10,000. As a result, she become reluctant to begin her fundraising campaign. The purpose of this analysis to help Louise organize, sort, and analyze crowdfunding data specific factors that make a project's campaign successful. In addition help her to see trend and outcomes of all categories by vizualization of the data.


## 2.	Analysis and Challenges

To perform the analysis, first on the new sheet I created a table (Shown Below). I filtered the Kickstarter Spreadsheet, I Copied the Successful Outcomes and the failed Outcomes to a new different Sheet. I named the new Sheets- Successful Outcomes and Failed Outcomes, respectively. Then using =COUNTIFS Excel Function (Example: =COUNTIFS(Kickstarter!D:D,">1000",Kickstarter!D:D,"<=4999") I got the number of Successful, Failed and Canceled Outcomes. However, transfering each outcomes to anew Sheet making this analyisis a bit hectic and took longer time. This was the challenge I was faced doing this analyis. Then I used the =COUNTIFS functions with three/four criteria. This makes life easier and took the data analysis shorter time. This can be shown on the table below. Using Excel =SUM function, I calculated the Total Projects. The Percentage Successful and Percentage Failed calculated by dividing the Number of Outcomes by the Total projects multiplied by 100. I used Nesting formulas =IFERROR (Example: =IFERRO`R((C3/D3),0)) function to fix error.

![This is an image](![image](https://user-images.githubusercontent.com/114262970/195494596-2103153a-993b-40ff-9354-75577250ddbe.png)

## 3. Results and Conclusion:

When we see Theater playwright crowdfunding campaigns outcomes baes on their launch dates, there are a couple of trends obsreved form the chart below. The first one, funding campaign lauched in between April and July have a high successive rate compared to the once lauched ate the end of the year. The other thing, when campaign lauched in February, March and November the failure rate of such fund raising is high unlike other months of the year.

![This is an image](![image](https://user-images.githubusercontent.com/114262970/195495676-0be5e2bc-d76e-467f-9248-fb01cdbab7b9.png)

On the other hand, when we see the outcome of crowdfunding campaign in relation to funding goals. From the chart below , we can conclude that the success of fund raising campaign heavly depends on the amount of funding goal. As you can see on the chart below, there is a downward trend in success rate with the increase in funding goal. The more the aount of funding goal, the higher the failure rate of the fund raising campaign.

![This is an image](![image](https://user-images.githubusercontent.com/114262970/195498083-db0f9898-7198-4f24-b858-3f2f26c3b180.png)
