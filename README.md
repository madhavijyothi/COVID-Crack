# Crack_The_Covid_2020
Submission for competetion Crack the Covid 2020 held at Beatest

[Chatbots and Data](https://github.com/rishabh-karmakar/Crack_The_Covid_2020/tree/master/Chatbot%20data)

[Map and Inventory Supplier](https://github.com/rishabh-karmakar/Crack_The_Covid_2020/tree/master/Maps%20and%20Inventory%20Supplier)

[Login and ML](https://github.com/rishabh-karmakar/Crack_The_Covid_2020/tree/master/ML%20and%20Login)

## Solution Description:

Right now, amid this COVID crisis, we live in times of food insecurity. We live in times where we are uncertain if we are going to get our food supplies or even if we have grocery stores open in our area. The suppliers are also uncertain as to which products they should bring and how much as too much inventory in the warehouse means more risk of wastage, and not enough could lead to out-of-stocks - and push customers to seek solutions from your competitors. This creates a huge supply-demand gap and more enormous consumer-supplier gap.

The goal is to provide a mobile application, along with server-side components, that serves as the basis for both suppliers and consumers, which addresses local needs for food, equipment, and resources. It would allow both "Suppliers" (such as a store or a community member who has produce they can sell or distribute) to make people aware of what they have; and Consumers ("Recipients") to locate where these supplies are, and, if necessary, guide them to the appropriate locations to pick them up.

![WhatsApp Image 2020-05-24 at 6 48 50 PM](https://user-images.githubusercontent.com/48029688/83050361-1820c600-a06a-11ea-8000-3f16d4de153c.jpeg)
 
For the consumers: We have a map which shows the closest suppliers and their information on what all they have and the opening/closing timings. 

**Chatbot:** Can be implemented using Watson Assistant which gives latest Covid-19 information along with the ability to query for nearby suppliers. Also equipped with speech to text, text to speech and language translator for convenience.

**For the suppliers:** We have an inventory system as well a warehouse prediction management where we could predict the demand of goods in the future, based on data as well as user stats information.

**Backend:** Making of user profile and using the user data to provide a recommender system as well as feed that data to the warehouse prediction and optimisation system.

The goal is to create a system of delivery chains where the user can get information on where and what supplies are available as well as the supplier can get all the information on what all should they actually buy and are in demand, deployed on IBM cloud and assisted with Watson assistant, this app really has the potential on helping to curb this pandemic that we are going through.

## Novelty/ Uniqueness

Chatbot to clarify the FAQ, Natural language translator, and text to speech attached.
Regional Language understanding and translator.
Machine Learning Model to predict the demand for goods for the next 10 weeks or in the future so that the suppliers are neither in short of raw material nor in the case which will lead to wastage, just enough amount to survive from the post-pandemic food insecurity.
A separate interface for both Consumer and Supplier.
Real-time updates on available supplies.
Request Supplies.
Notifications as soon as requested supplies come.
Recommender System to recommend users and supplies.
Assistant providing with latest corona data as well as search for supplies query.

## Business / Social Impact

With COVID-19 now spreading in India, massive consequences to health and livelihoods are feared. Given the precarious livelihoods of many Indians, agriculture, food security, and safety net policy and program responses are also urgently required. 

The best way to address this urgent need is to use social safety nets extensively to stabilize their lives with food and cash. Alarmed by a potential rise in food insecurity during the COVID-19 pandemic, many countries and organizations are mounting special efforts to keep agriculture safely running as essential business, markets well supplied in affordable and nutritious food, and consumers still able to access and purchase food despite movement restrictions and income losses.


Also keeping the consumer informed on the supplies and suppliers near them as well as keeping the supplier informed on the demand near them. Knowing the demand also helps the supplier to have an optimum inventory of both perishable and non-perishable.
 
The measures we plan to take will keep supply chains functioning well is crucial to food security. As lockdown measures have increased, demand has risen for home delivery of groceries and E-commerce. This trend should be encouraged and promoted. 

## Technology Stack:

![WhatsApp Image 2020-05-24 at 6 54 21 PM](https://user-images.githubusercontent.com/48029688/83050586-67ff8d00-a06a-11ea-82e8-76ce8db58590.jpeg)

The flow can be seen in the solution description information.

## Usable Technologies:

Python 3, IBM Watson Studio, Watson Assistant, IBM Cloud for Deployment, Node-RED/ Web Framework, React-Native/ Mobile Framework, HERE Location Services


## Scope of work:

A Supplier (who may be a regular resident, a small business, a voluntary organization, etc.) that has food, supplies, resources, or other essentials they can provide opens the web/mobile application and fills out a brief form that indicates what they have. This information is then stored in a database in the IBM Cloud.

A Recipient, who is in the need of food, supplies, resources, or other essentials, opens the web/ mobile application and can use the chat interface to locate supplies near them. For instance, they might type "Where can I find bread?" or "Can someone collect my shopping for me?" The web/mobile application then accesses the database (after first understanding the question via Watson Assistant) and then displays a map showing locally where they can find what they are looking for.

This solution idea combines a chat interface (Watson Assistant), data storage to hold the status of supplies available, and location services with real-time information to get users the information they need.

1.	The Recipient launches the web/mobile app and can access information across multiple services.
2.	The Recipient can ask questions to Watson Assistant and get answers on food/service availability questions.
3.	The Supplier can post the availability of stock or services they can provide, as well as locate the items they need.
4.	The Recipient can obtain geolocation data to plot routes to collect (or drop off) supplies using HERE Location Services.
5.	The supplier can get the predicted demand.
6.	The recipient has a recommendation system.

We also include a Dashboard to show how the extended lockdowns/post lockdown situations can impact the food security of people. Dashboards are a data visualization tool that allows all users to understand the analytics that matter to their business. 


