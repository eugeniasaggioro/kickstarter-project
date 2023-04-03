# Kickstarter Project

This is the final project of the Machine Learning course. 

Kickstarter is a crowdfunding platform that allows people to support creative projects. Film, gaming, and music, as well as art, design, and technology projects, are all covered.

The dataset at hand was crawled from the platform and contains detailed information about all current and historic projects on Kickstarter, as well as their status (successful, failed, canceled, live, suspended). 

Every project creator establishes a financing target (funding goal) and a deadline for their project. People can donate money to help make the concept a reality if they like it. Funding on Kickstarter is “all-or-nothing”. If the project meets its funding goal, all backers' credit cards will be charged after the deadline passes and Kickstarter deducts a 5% fee from pledged amount. On the other hand, if the projects fall short of its funding goal, no one is charged. 

Project creators retain complete ownership of their work. After a project is deemed successful, Kickstarter cannot be used to seek loans or to give financial returns or equity. Backers can support projects to help them come to life, not to profit monetarily. 

Kickstarter has a great potential to bring ideas to fruition. At the same time, Kickstarter's project have few risky characteristics for backers and creators who want to invest or launch successful projects.

During the course of this project, we will take the perspective of project creators to assist them with an evaluation of how probable the project is to reach the funding goal with given features at launch. With a realistic evaluation creators can be preserved from wasting valuable resources on projects with a low probability to succeed.

For a project’s success or failure on crowdfunding platforms, it’s important to consider the influence of all the factors characterizing that project. Some of these factors can be measured or classified, allowing for the development of a model to forecast whether a project will succeed or fail. 

Some projects are more successful than others and our intuition is that this does not always depend on the key idea. Some projects might fail because they don’t hit the target (backers) due to wrong descriptions, uncommon topic, too high funding goal or simply the project doesn’t seem trustworthy. We will try to find the main patterns and the odds of a project’s success. Thanks to this model, decision makers (project creators) will gain useful insights before publishing their project on the platform.

In order to achieve the goal explained above, we will use a dataset crawled from Kickstarter, which contains detailed information about all current and historic projects on Kickstarter, as well as their status (successful, failed, canceled, live, suspended). The dataset contains all the projects hosted between 2009 and 18 October 2018.

Given the **large amount** of original data available (205696 projects with more than 37 variables), and the reasons explained below, it is reasonable to involve automation to solve this problem. 
- There is no **existing formula** to understand a priori if a project will be successful based on specific characteristics.The features of each project set on the platform contribute in different ways to its success and this cannot be translated into simple rules.
- Analyzing the probability of success and which are the main drivers of the end result, project by project, would **not** be **feasible**. 
- Some columns like the description of the project (blurb, slug) contain **unstructured text** which needs to be analyzed in depth with Natural language Processing. 

All in all, there is a big potential for data to be **represented in a meaningful way**, with both numbers and categorical values (e.g. state, status, location). In the next sections, we will explain these reasoning better.
