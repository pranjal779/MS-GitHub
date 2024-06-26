# Insight and automation with projects  
Completed  
100 XP  
8 minutes  
Now let's talk about how Projects can provide you with insights and how to make life a bit easier with automation.  

## Insights with Projects  
In this section we'll talk you through:

- What are insights and how can they be useful
- Current charts and historical charts
- Creating and customizing charts

## What are insights and how can they be useful
Insights with Projects enables you to view, create and customize charts that use items added to your Project as source data. When you create a chart, you set the filters, chart type, the information displayed, and the chart is available to anyone that can view the Project. You can generate two types of charts: current charts and historical charts.

## Current and Historical charts
As mentioned above there are two types of charts you can create from insights: current and historical charts. Below we dive into the differences between the two.

## Current charts
You can create current charts to visualize your Project items. For example, you can create charts to show how many items are assigned to each individual, or how many issues are assigned to each upcoming iteration. You can also use filters to manipulate the data used to build your chart. For example, you can create a chart showing how much upcoming work you have, but limit those results to particular labels or assignees.
![6-current-chart-example](https://github.com/pranjal779/MS-GitHub/assets/50409572/83507138-4323-417b-a2fc-128f459232a9)

## Historical charts
Historical charts are currently available as a feature preview for organizations using GitHub Team and are generally available for organizations using GitHub Enterprise Cloud. Historical charts are time-based charts that allow you to view your Project's trends and progress. You can view the number of items, grouped by status and other fields, over time. The default "Burn up" chart shows item status over time, allowing you to visualize progress and spot patterns over time.
![6-historical-chart-example](https://github.com/pranjal779/MS-GitHub/assets/50409572/46a2687f-5f0a-44c9-958a-4480f241afd9)

## Creating and customizing charts
Creating charts is simple, below are the steps to follow for when you want to create a new chart.

1) Navigate to your Project.
2) In the top-right, to access insights, click the line graph button, when you hover above the button, it will be labeled as Insights.
3) In the menu on the left, click New chart.
4) Above the chart, type filters to change the data used to build the chart.
5) To the right of the filter text box, click Save changes.

Now that you've created a new chart, let's customize your new chart to fit your needs.

1) First, navigate to your Project.
2) In the top-right, to access insights, click the line graph button, labeled Insights.
3) In the menu on the left, click on the chart you would like to configure.
4) On the right side of the page, click Configure. A panel will open on the right.
5) To change the type of chart, select the Layout dropdown and click on the chart type you want to use.
6) To change the field used for your chart's X-axis, select the X-axis dropdown and click the field you want to use.
7) Optionally, to group the items on your X-axis by another field, select Group by and click on the field you want to use, or click "None" to disable grouping.

## Automation with Projects
Work doesn't have to take up too much work, especially when you use Projects. Let GitHub do some of the work for you by automating your Project.

There are three different ways you can automate your Project:

- Built-in automated workflows
- GraphQL API
- GitHub Actions with workflows

The easiest way to automate your Project would be to use Project's built-in workflows, while GraphQL and Actions you have more control over customizing automation. In the following sections we'll walk you through how to utilize Project's built-in automation and briefly go over GraphQL API and GitHub Actions automation.

Let's start with Project's built-in workflows.

## How to configure built-in workflows
With built-in workflows, your Project will take newly created issues or pull requests and automatically put them into your Project with a Todo status, helping you stay aware of all of your work.

To enable automation first go to the top-right corner of your Project and click on the three dots to open the menu.

1) Next, in the menu, click Workflows.
![6-automation-workflows-menu](https://github.com/pranjal779/MS-GitHub/assets/50409572/0f55b8e0-55a0-4dda-bb10-755240f76fb9)

2) In the left column, under Default workflows, select Item added to project.
![6-automation-default-workflows-items](https://github.com/pranjal779/MS-GitHub/assets/50409572/79d56a8c-82de-4a32-8333-3b40881c6e71)

3) Now in the center of the page, where it says When, ensure that both issues and pull requests are selected.

4) Below click on Set and click Status:Todo.

5) Finally in the right corner of the page, ensure the toggle is turned On.

Congratulations! You have just automated your Project!

## GitHub Actions with workflows
GitHub Actions enables the most customization for your Project's automation. You can use GitHub Actions to automate your project management tasks by creating workflows. Each workflow contains a series of tasks that are performed automatically every time the workflow runs. For example, you can create a workflow that runs every time an issue is created to add a label, leave a comment, and move the issue onto a project board.

Learn more about automating workflows for your Project here, see the article, "Automating Projects using Actions" at the end of the module.

## GraphQL API
If you're using GraphQL in GitHub, you can also utilize an API to help automate your Project. For more information on using GraphQL API, see the article, "Using the GraphQL API to automate your projects" at the end of the module.

## Next unit: Knowledge check
