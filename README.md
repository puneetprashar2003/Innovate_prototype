# innovateX_prototype
# INTRODUCTION
DAK GHAR NIRAYAT KENDRA is a service which has been stareted under the INDIAN POST .The main aim of this is to promote trade between INDIA and other countries and also to enable small scaled businesses and traders to be able to export their products abroad.Although this is already been done by ecommerce services such as amazon but DAK GHAR NIRAYAT KENDRA offers much more .DAK GHAR NIRAYAT KENDRA is a one stop portal where a buyer can buy any product from other country , a seller can sell his product in the international market without going anywhere  and from the screen of his phone . 
# PROBLEMS
In INDIA where nearly 300 million people have thier own businesses , many of them can not take them to the international market. Some of the main reasons are
•	Lack of trust between the seller and private organisations.

•	Extra charges which are currently being taken by third party organisations in private firms.

•	Difficulty in documentation and other formalities.

•	Lack of knowledge about the demand of their product in International Market.

•	Difficulty in dealing with modern technology.

•	BUYER does not trust that whether the product will be delivered in the best condition as seen on website.




# SOLUTIONS
1) There has always been a gap between private firms and local vendors. DAK GHAR NIRAYAT KENDRA being a government organisation will insure that no injustice is done to any buyer and supplier who are using their services.

2) Currently




4) As it has been consistently seen in the market that there is always a supply , demand imbalance in trade. A supplier who does not have an idea about the demand of his product in the outer world can not supply his products throughout the year .To overcome this problem we have developed a Machine Learning model which will predict the demads of a certain product  in a particular month so that the supplier can manufacture his products accordingly.

# ABOUT MACHINE LEARNINIG MODEL
Dataset for trainig -https://www.niryat.gov.in
The machine learning model uses randomforest regressor in order to predict the demand of a product in the given month. It has been trained on various parameters which include the sales of the product in  past years. The use of random forest regresor ensures that no extreme bias and overfitting occurs in the model.
The model also gives an idea about how a certain change in the demand can provide great insights to the seller .
For further refrence kindly see the sih_server->ml_model.

5) Many sellers find it difficult to upload the details of thier products online as they are not comfortable with the present technologies . This problem has been solved in 
our solution where we will be asking the seller to just click the photo of his product to be displayed and he can vocally give the description of his product in the language which he is comfortable in . This will give him ease to make his product page. On the other hand the buyer will be able to see the description in the language which can be chosen by the buyer. This will reduce the language barrier between the seller and the buyer.This has also been done with the help of machine learning where we have used ASR model . ASR stands for automatic speech recognition .
A CHATBOT is used which will solve the query of bith the seller and buyer ,hence providing a better user interaction .
Another problem which is important to be solved is that the review and comments should be analysed so that both buyer and seller are able to get insights from the review.
To solve this problem a machine learning model has been built which uses the BERT MODEL .

# MORE ABOUT SENTIMENT ANALYSIS
The BERT model is Bidirectional Encoder Representations from Transformers. The benifit of using a transformer is that it does not need to process the data  in a certain sequence . Further the bidirectional model is using Masked Language Modeling and Next Sentence Prediction . Thses both algorithms almost play the same role that is that to predict the next word . The pretrained is also fine tuned so that it can analyse the  comments with respect to the product. For any further refrence ,please see the code 
in sentiment analysis.




 
