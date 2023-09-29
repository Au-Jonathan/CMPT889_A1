# CMPT889_A1

See Miro Board for more details

Customer_value is the key measure of a client's value, I didn't use the score base approach but I compute the monetary value based on interest income and transaction fee, it is the norm for financial sector to assume industry rate, therefore we are using the rate in USA around 2020/2021, feel free to check out the logic in the notebook and suggest any new idea if you have.

Most of the analysis centered around the increment of customer value, between various calling actions and NO calling. 

The rest is to see if you can find any meaningful variables to "predict" the largest increment. For now I just looked at age and payroll based on the 4 calling actions. The quick insight is that, in 
long term (6m data), "call both" works the best, "call 3M" works the worst. To extract the most value, "call both" and the calling order is young people with payroll, middle age with or without payroll, senior with or without payroll. 

Since the value of each customer can be quantified as dollar value, I subtracted the cost of calling in the customer value. So when calculating the incremental, it is the net gain after considering the cost of calling. 

I was solving this in "chart" perspective to reserve maximum "explainability", if it is also possible to solve this in model/statistical perspective. Feel free to implement it and share your idea.













