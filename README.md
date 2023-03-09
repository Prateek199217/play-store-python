I prateek chaudhari did this analysis project on play store data alone. 
There are two tables in data set one is play store data and other is user reviews. In play store there are 13 colmuns - App contains name of apps, Category contains in which category app belongs , Rating contains how people rated the app, Reviews contains how people reviewd the app, Size contains actual size of app, Installs contains no of installation, Type shows what type app belongs, Price contains what is the price of app, Content Rating contains what is the age group of people it is related to, Genners shows the theme of app, Last updated contains when the app is updated lastly, Current ver contains the current version of app, Android ver contains android version supported by app and in user reviews there are 5 columns named Apps contain name of app, Translated_review contain reviews after translation by machine, Sentimental contains after reading reviews is postive negative or nutral, Sentimental polarity contains how strong the review is, Sentimental subjectivity contains the subect matter strength of review.All the data avaliable in these tables are till 2018 so analysis has limitiation of year. I try to find a solution for those who plan to launch a new application over google play store for a successful app they must know few things like how many apps are registered, what type of content rating, top apps in that category, avg size of app, no of installs etc. for this I closely check data sets columns and find some nan values, duplicate values, irrelevent data.I also convert the size of apps in bytes. for cleaning and converting such data i use google sheet filters and find and replace method. Then i load the csv files in drive and connect the drive with google colab. I import necessary librery for analysis and mount the drive. I load the csv files. My findings are as fallows-

family category has most no of apps so competition is too tough if one plan to launch an app in this category. For this I use bar chart.

If one decided to launch an app in family category Teh I find top 10 apps based on user reviews which helps one to find what are the size, no of installs, Type, Price, Genners and current version to beat the competiton.

I find name of apps in each category having max no of installs.

I find percentage of content rating of all apps and find that majority of the apps content is for everyone and for this use pie chart.

I find how many apps are updated in each year and find that there is incresing order of app update in year on year bases and rapid growth in 2018 and for this i use line chart.

I find preview of sentimental polarity and find that most of the apps having postive sentiment for this i use bar chart.

I find average size of apps by category which helps one to decide what is the size of apps and find that gaming apps has larger avg size. for this i use bar graph.

I find top rated apps in each category for which i take 4.0 above as top rated.I find family category has max no of apps rated above 4.0. I use bar chart for representation.
