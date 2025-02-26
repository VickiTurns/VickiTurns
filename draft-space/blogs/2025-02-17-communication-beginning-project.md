# Building a report or solving a problem: the importance of communication at the beginning of a data project
Vicki Turner : First published on blog.arkahna.io, Feb 17, 2025 12:46:52 PM

tags power platform data


Building a report or solving a problem: the importance of communication at the beginning of a data project
As a Data Analyst, when given the initial brief for a report that has been requested, the first instinct can be to open Power BI, hook up to the data source and start developing.

Often it is wise to spend some time in conversation with the product owner (the one requesting the report) and other consumers of the report (those who are using or are the subjects of the report) and finding the subject matter experts to understand the request from a wider angle.

This can allow the consumers to explore what they are really looking for and ensure you have the information to build what they need. When a product owner comes requesting a solution, sometimes they haven’t spent the time working out what the problem is yet and this is where some curious questioning can help bring this to light.

banner question

The Scenario
To explore this concept, I will use a fictional scenario. You work as a Data Analyst at a medium sized business that has an inbound call centre to handle and transfer enquiries to various departments within the business. This area is managed by the Call Centre Manager and Call Centre Officers are taking the calls.

You are approached by the Call Centre Manager as they have received complaints of the queue times for callers being too long. The Manager is asking for a Power BI report to show how long callers are waiting to speak to someone and the average time Call Centre Operators spend on each inbound call.

You likely have two options at this point of how you approach this issue:

go ahead and build the report showing the average times callers are queuing and average time of inbound calls for each operator,

or

ask a few more questions to understand what is required and why before getting into the developing. Potentially this could save you from spending many hours building a beautiful report that doesn’t even answer the underlying question!

caller and operators

What is the product owner asking for?
It is valuable to spend some time listening, without jumping to solutions. What is the product owner and consumers of the report asking for? Ask questions to delve into the reasons why they’ve asked for the particular report they came to you about. What are their frustrations and pain points?

Make sure that they feel heard in giving you their time. A powerful way of doing this is reflect back your understanding of what they have told you in your own words to ensure you have understood correctly. Work on framing this with a positive perspective so the tone of the project is towards what needs to be done rather the negative things that have happened.

In our scenario, the Call Centre Manager starts with wanting to see the numbers for queues and how long Officers stay on calls. After some questioning and exploring it seems the Manager is actually wanting to know why the callers are unhappy.

people around table

What is the question that needs answering?
Often a report is built because people want to see some numbers, but coming from the angle of deriving what the question is that should be answered by those numbers will give more insight into what should be shown in the report.

It can be useful to ask if there are KPIs that are needing to be reported on. It would make sense to ensure that you are providing indicators of how these are being achieved.

Is there a wider view that needs to be taken into consideration? Taking a step back and talking to not only the product owner, but also those who are consuming the report and those who’s actions are contributing to the data to understand a broader context. They may not be influencing the content as such but will allow you to gather a context in which the parts of the data you are reporting on sit. These people are often the subject matter experts and will be able to provide a more nuanced view of how all aspects tie together. They are often able to answer those more detailed questions when you are trying to understand the data source also.

Another area to explore is how this report will be used to make decisions. Are there particular cut-offs or indicators that can aid the decision-making process?

In the scenario we are working through, asking these questions uncovers a few things:

There is a KPI that 90% of calls need to be answered by the Call Centre Officers within 3 minutes.

Call Centre Officers have a value they work to of ensuring that callers are not transferred to a voicemail if at all possible.

Conversations with the Call Centre Officers shows they have a general frustration with not being able to transfer calls to a department and have someone answer the call. This highlighted that the data about what happens to the call after it is transferred could also be useful.

The Call Centre Manager also tells you that they want to use this report to understand the workload of the Call Centre Officers so they can make decisions around training and staffing levels, particularly during peak times.

Where does the data come from?
Looking at the source data might give more information into what information could be put into a report. There also might be more than one source which will give a fuller picture. This of course could be a rabbit warren of information but within the scope provided, you may obtain some interesting insights.

For example in this scenario, the primary source of data will be the soft phone system that is used by the call centre staff. There is also the complaints submitted via the company website which may give some context to when issues occurred and be able to get a number of complaints over periods of time. There could be an opportunity to capture data through an automated 2-question survey system at the end of calls that the Call Centre Manager has been considering implementing to have a richer set of data going forward.

Who is the audience for the report, and how will they use it?
Discussing with the product owner who they are expecting will use the report will give you the opportunity to explore at a high-level the type of layout expected, and granularity of detail required. This will help inform your design of the report. If it’s designed to give an indication at a glance of whether benchmarks are being met, then clear and uncluttered visualisations would be the way to go. However, if it is being used to go into greater detail on specific numbers or categories, then it might be useful to have drill through pages from a main dashboard that provide that greater detail.

In our scenario, the Call Centre Manager wants to be able to see trends in queuing and call times. They also want to see these sliced in a few ways to understand outliers as well as averages. They would also like to see data by Call Centre Officer.

What also comes to light is that the soft phone system has the ability to provide a real time output of current number of calls queued and wait times. This could be presented in a real time dashboard to the Call Centre Officers for them to have better visibility of callers waiting and manage their workload more efficiently.

demonstration

Communication is not just for the beginning of a project
This blog post has covered some of the initial questions that might take place in the early stages of a project. However, this is certainly not the extent of the communication that needs to happen. Throughout the phases of a project, regular communication with the product owner will ensure that you are both on the same page with expectations, and this will also give the product owner more confidence that the product being built will be suitable.

Communication should not just be verbally through the project - if you can provide brief written updates this will be helpful for time-poor managers, and also screenshots, demonstrations of progress or preliminary versions of the report for them to test will really help with getting constructive feedback.

Take-aways
Key take-aways from this post are to ensure you are talking to the right people, and asking open questions in a way that gets you and your consumers thinking more widely about the impact of the report being built. The aim of asking the questions is to establish a common understanding so it is definitely a two-way process.

Be sure to reflect back to the product owner after this questioning phase what you have found to allow them to make final decisions on what is to be built with guidance from your findings and recommendations.