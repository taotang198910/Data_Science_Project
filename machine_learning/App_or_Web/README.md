# Mobile App or Website

You can view `App_or_Web.ipynb` directly on github, or clone the repository.
### Manual 
* Clone the repository
* Install requirements
* Open `App_or_Web.ipynb` on Jupyter Notebook.

### Intro
The Ecommerce company based in New York City that sells clothing online but they also have in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want.
The company is trying to decide whether to focus their efforts on their mobile app experience or their website.

We work with the `Ecommerce Customers` csv file from the company. It has Customer info, suchas Email, Address, and their color Avatar. Then it also has numerical value columns:
* Avg. Session Length: Average session of in-store style advice sessions.
* Time on App: Average time spent on App in minutes
* Time on Website: Average time spent on Website in minutes
* Length of Membership: How many years the customer has been a member. 


### Methods
In this project, I used pandas to import and prepare data. Followed by utilizing Seaborn to do EDA(exploratory data analysis),and find out the correlationships across the entire data set. Then used linear regression model from scikit-learn
to predict the Yearly Amount Spent of customers based on their info. Then by calculating coefficients to indicate the most important feature.

