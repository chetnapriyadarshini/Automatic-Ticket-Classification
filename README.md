# Automatic-Ticket-Classification

Build a model that is able to classify customer complaints based on the products/services. By doing so, you can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

With the help of non-negative matrix factorization (NMF), an approach under topic modelling, you will detect patterns and recurring words present in each ticket. This can be then used to understand the important features for each cluster of categories. By segregating the clusters, identify the topics of the customer complaints. 

 
I used topic modelling on the .json data. Since this data is not labelled, apply NMF to analyse patterns and classify tickets into the following five clusters based on their products/services:

1) Credit card / Prepaid card
2) Bank account services
3) Theft/Dispute reporting
4) Mortgages/loans
5) Others
