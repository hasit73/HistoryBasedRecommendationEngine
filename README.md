## HistoryBasedRecommendationEngine


### Major Tools used 
    1) Pyspark = for faster data and text preprocessing and provides various libraries for data transformation
    
    2) Pywebio = is used to build interactive UI plateform for our ML model 
    
    
### benefits of using pyspark
 - parallel processing
 
 - high speed for data preprocessing
 
 - provides large functionalites for data transformation
 



### Main Logic 

 - engine takes input keywords from user side (like : black , tshirt , shoes etc) and this input keywords are converted into vectors and all products name are converted into vectors  using tf-idf transformations 

- at the end engine will compute similarity score of input keywords vector with db product name vectors and top 10 products with highest similarity score are selected as recommendation system





#### Demo video
https://user-images.githubusercontent.com/69752829/118664584-36e61280-b80f-11eb-8b5a-da7172b6882b.mp4

