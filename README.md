# **Predicting Catalog Demand**
## **Project Introduction & Overview**

In this project, a business problem in the mail-order catalog business will be analyzed. The task is to predict how much money the company can expect to earn from sending out a catalog to new customers. This task will involve building the model and applying the results in order to provide a recommendation to management.

### **How do I Complete this Project?**

This project uses skills learned in the "Problem Solving with Advanced Analytics" course. To complete this project:

- Go through the course.
- Apply the skills learned in the course to solve the business problem given in the project details section.
- Use the guidelines and rubric to help build the project.
- When ready, submit it for review using the submission template.


### **Skills Required**
In order to complete this project, you must be able to build a linear regression model and apply the results to a business problem.

An understanding of the Problem Solving Framework will also be important to success in this project.

## **The Business Problem**
You recently started working for a company that manufactures and sells high-end home goods. Last year the company sent out its first print catalog, and is preparing to send out this years catalog in the coming months. The company has 250 new customers from their mailing list that they want to send the catalog to.

Your manager has been asked to determine how much profit the company can expect from sending a catalog to these customers. You, the business analyst, are assigned to help your manager run the numbers. While fairly knowledgeable about data analysis, your manager is not very familiar with predictive models.

You've been asked to predict the expected profit from these 250 new customers. Management does not want to send the catalog out to these new customers unless the expected profit contribution exceeds $10,000.

## **Details**

- The costs of printing and distributing is $6.50 per catalog.
- The average gross margin (price - cost) on all products sold through the catalog is 50%.
- Make sure to multiply your revenue by the gross margin first before you subtract out the $6.50 cost when calculating your profit.

Write a short report with your recommendations outlining your reasons why the company should go with your recommendations to your manager.

### **Steps to Success**

**Step 1: Business and Data Understanding**

Your project should include a description of the key business decisions that need to be made.

**Step 2: Analysis, Modeling, and Validation**

Build a linear regression model, then use it to predict sales for the 250 customers. Use Alteryx to build the best linear model with your data.

**Note** : For those using software other than Alteryx, if you decide to use Customer Segment as one of your predictor variables, please set the base case to Credit Card Only.
However, feel free to use any tool you'd like. You should create your linear regression model and come up with a linear regression equation.
Once you have your linear regression equation, you should use your linear regression equation to predict sales for the individual people in your mailing list.

**Step 3: Writeup**

Once you have your predicted or expected profit, write a brief report with your recommendation to whether the company should send the catalog or not.

**Hint:**  We want to calculate the expected revenue from these 250 people in order to get expected profit. This means we need to multiply the probability that a person will buy our catalog as well. For example, if a customer were to buy from us, we predict this customer will buy $450 worth of products. At a 30% chance that this person will actually buy from us, we can expect revenue to be $450 x 30% = $135.

## **Supporting Materials**

### **Review**

Use the [project rubric](https://review.udacity.com/#!/rubrics/186/view) to review your project. If you are happy with your submission, then you're ready to submit your project. If you see room for improvement, keep working to improve your project.

## **Data**

- _p1-customers.xlsx_ - This dataset includes the following information on about 2,300 customers. You should build your model on this dataset


- _p1-mailinglist.xlsx_ - This dataset is the 250 customers that you need to predict sales. This is the list of customers that the company would send a catalog to. Use this dataset to estimate how much revenue the company can expect if they send out the catalog. It includes all of the fields from *P1_Customers.xlsx* except for `Responded_to_Last_Catalog`  **so this variable cannot be used in the linear regression model since it could not be applied to the mailing list data set**. It also includes two additional variables.

- Score\_No: The probability that the customer WILL NOT respond to the catalog and not make a purchase.
- Score\_Yes: The probability that the customer WILL respond to the catalog and make a purchase.

**Hint:**  We want to calculate the expected revenue from these 250 people in order to get expected profit. This means we need to multiply the probability that a person will buy our catalog as well. For example, if a customer were to buy from us, we predict this customer will buy $450 worth of products. At a 30% chance that this person will actually buy from us, we can expect revenue to be $450 x 30% = $135.

**Supporting Materials**
- [Mailing List](https://video.udacity-data.com/topher/2017/February/58b0c6aa_p1-mailinglist/p1-mailinglist.xlsx))
- [Last Year's Customers](https://github.com/KOdoi-OJ/Predicting-Catalog-Demand/blob/main/datasets/p1-customers.xlsx)

## **Key Notes**
- All following questions have been answered: What decisions need to be made? What data is needed to inform those decisions?

- Each predictor variable is shown to have a linear relationship between the target variable whenever appropriate. Each predictor variable should be significant

- p-values and R-squared values are used to justify how well the linear model works.

- The regression equation given is correct. Each coefficient should have up to 2 digits after the decimal figures (ex: 1.28).

- Ensure that all questions have been answered and the recommendations are well justified. What is your recommendation? How did you come up with your recommendation? What is the expected profit from the new catalog (assuming the catalog is sent to these 250 customers)?

## **Results**
The final submission for this project is the [Final Submission](https://github.com/KOdoi-OJ/Predicting-Catalog-Demand/blob/main/Final%20Submission%20-%20Predicting%20Catalog%20Demand.pdf) document. 

Key screenshots from the Alteryx workflows used for the project can also be found [here](https://github.com/KOdoi-OJ/Predicting-Catalog-Demand/tree/main/key%20screenshots)


---
*This project was completed, with final review and approval, on March 3, 2022*
