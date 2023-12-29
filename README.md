# Globox-A-B

# Project Overview
In this project, you will analyze the results of an A/B test and create a presentation of data-driven recommendations based on your findings. You will choose which tools you use.

# Project Logistics
The project features three parts, each being one sprint:

Review inferential statistics and create your analysis plan
Analyze the A/B test results to determine whether or not the experiment was successful
Record a presentation of the A/B test results and create a written report
For the first two sprints, you will need to pass a quiz before moving on. The third sprint will require the submission of your presentation and report.

Students who pass the quizzes and submit the presentation before the deadline at the end of the unit will receive feedback from their School Master. The feedback will be provided 2 weeks after the submission deadline.

# Project Background
An A/B test is an experimentation technique used by businesses to compare two versions of a webpage, advertisement, or product feature to determine which one performs better. By randomly assigning customers or users to either the A or B version, the business can determine which version is more effective at achieving a particular goal.

You are a Data Analyst for an e-commerce company called GloBox. GloBox is an online marketplace that specializes in sourcing unique and high-quality products from around the world.

We believe that shopping should be an adventure, and we want to bring the world to your doorstep. From exotic spices and rare teas to handmade jewelry and textiles, we have a curated selection of products that you won't find anywhere else.
GloBox is primarily known amongst its customer base for boutique fashion items and high-end decor products. However, their food and drink offerings have grown tremendously in the last few months, and the company wants to bring awareness to this product category to increase revenue.

The Growth team decides to run an A/B test that highlights key products in the food and drink category as a banner at the top of the website. The control group does not see the banner, and the test group sees it as shown below:


# The setup of the A/B test is as follows:

The experiment is only being run on the mobile website.
A user visits the GloBox main page and is randomly assigned to either the control or test group. This is the join date for the user.
The page loads the banner if the user is assigned to the test group, and does not load the banner if the user is assigned to the control group.
The user subsequently may or may not purchase products from the website. It could be on the same day they join the experiment, or days later. If they do make one or more purchases, this is considered a “conversion”.
Your task is to analyze the results of the A/B test and provide a recommendation to your stakeholders about whether GloBox should launch the experience to all users. The group that you will be presenting to includes the following:

Growth Product & Engineering Team: This is the team that you work with at GloBox. The team is made up of a product manager, a user experience designer, an engineering manager and several software engineers, and you, the data analyst. The team develops features for the GloBox website that drive growth in users and revenue.
Leila Al-Farsi, Product Manager, Growth: Leila is the product manager for the Growth product and engineering team. Alongside Alejandro, she leads the Growth team by deciding their goals and projects, measuring their success against defined KPIs, and communicating results to other company leaders like Mei.
Alejandro Gonzalez, User Experience Designer, Growth: Alejandro is the designer for the Growth product and engineering team. He conducts user research and designed the experience that the A/B test is evaluating.
Mei Kim, Head of Marketing: Mei oversees the Marketing team, which works on targeting audiences with effective marketing campaigns to drive customers to the GloBox website. She collaborates frequently with Leila and Alejandro to design website experiences that will align well with the current marketing efforts.
Together, Leila, Alejandro, and Mei will decide whether or not to launch the experiment based on the results.

# The Dataset
GloBox stores its data in a relational database, which you will access below:




Connect to the GloBox database

Paste the following URL using the “Import from URL” option mentioned in the instructions linked above:

postgres://Test:bQNxVzJL4g6u@ep-noisy-flower-846766-pooler.us-east-2.aws.neon.tech/Globox
\
