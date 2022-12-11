# Play_Store_Review_Analysis

## ABOUT
 In this project,we are going to analyse the dataset of Google Play Store,
 Google Play , formally known as android market, is the official distribution storefront for Android Applications and other digital media such as music, movies and books from google.
The Google Play store launched on march 6th, 2012 consolidating the android market and other digital services, like Google Music and Google eBookstore, into one offering. Currently storefront is available in over 190 countries and territories.
Android is dominant mobile operating system today more than 85% of all mobile devices running Google’s OS. The Google Play Store is largest and most popular Android app store.
There are more than 3.04 million apps found on Google Play Store.
The purpose of our project is to gather and analyze details information on apps in the Google Play Store in order to provide insight on app features and the current state of the Android app market.

## DATA INFO-
### Feature 
    It gives the information about the different properties of the APPS which is independent of each other like 
    1-Name
    2-Category
    3-Size
    4-Type
    5-Price
    6-Content Rating
    7-Android Version .

### Result
   It is the result and success of the Apps,due to its various properties
   1-Rating
   2-Reviews
   3-Installs
   
## STEP OF ANALYSIS

### Data Cleaning-
  1-Here we size,price,rating,reviews,Installs are in Object Datatype,so first we converted them into Numerical format of Int(Price,Reviews,Installs) or Float(Size,Rating).
  2-Then after we have filled the Null Value with Mean or Medians and Mode.
  3-Outliers removed.
  
 ### Data Exploration-
    In exploring,we went to find some of the answer of the questions like-
      1-Which Category Apps is available in quantity?
      2-Which category has the highest number of Installs?
      3-How much average rating ,every category got?
      4-What is the average rating given by users?
      5-Which Category got the highest number of reviews?
      6-How much percentage of Apps are free?If paid,then which is the most expensive App?
      7-What is the mean size of each category  ?
      8-What is the distribution of Apps suitable to particular age?
      9-Which Android Version is compatible to the most number of Apps?
      10-What is the correlation among different attributes of Apps?
      
      
## CONCLUSION
After several operation we come to know about the various aspect of the Dataset of Play Store. like Which Category of Apps are most available,their Installs Quantity,Reviews numbers as well as Size and Ratings they got and found the Games related Apps are the dominant one.

1-Family and Game related Apps are most available category.
2-Most Installed Category of Apps is Games and Communication. Family related Apps not comes in even top5.
3-If we go through the Category of 'Art and Design',Sketch,draw & Paint is most installed Apps much more than its followed Apps.
4-All Category of Apps got more or less same rating in between 4 & 5. The Event and Education Category got the maximum rating nearly 4.4.
5-By analysing Rating Density,we come to know that most number of user given rating between 4 & 5.
6-Communication and Social category of Apps got most number of reviews. Might be duty to the sensitivity of privacy which user see befor using these Apps.
7-Nearly 93% of Apps are free thus make Android Market more popular store than others.
8-By looking at Category Wise Size,the most number of Category have average size in between 10MB and 20 MB.
           Games occupies the maximum amount of space upto 40 MB still have a maximum number of Installs.
9-Most of the Apps are suitable for Everyone,as we increase the suitable age less and less number of Apps are targeted.
10-Most of the Apps are compatible with Android Version of 4.0 and 4.1.
           Version of 8.0 despite being latest,not comes even in top 10 in compatibility with other Apps.
11-I'm Rich developed by Armin Heinrich of lifestyle genre topped the most expensive app of nearly 400$ cost. Its other genre like of finance also very expensive.
12-By analysing heatmap,we can point out that Reviews and Installs are most closely related in a positive way.
            Price relation with every feature is near zero because for most of the Apps price are free.
   
   
   
