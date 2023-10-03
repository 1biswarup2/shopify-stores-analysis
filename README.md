# shopify-stores-analysis(based on the dataset given at:https://github.com/TeamDukaan/performance.git)
# Steps followed:
1.At first the I have fetched the dataset using 'git clone'
2.taken top 700 sites only as sample data (due less processing power available)
3.Then via webscraping, I have fetched each sites title and stored it into 'title.txt'
4.Then after eliminarting the errorneous entries,finally prepared a list 'NotNullStr'
5.Then created a list of preprocessed sentences removing stop-words and punctuations from sentences in 'NotNullStr'
6.Then converted each string in tfidf vector and then applied clustering on this to categorize it into 20 categories
7.Then created a bigram graph for each cluster
8.Then using that graph ,finally got a summary or cluster title which defines the genral type of the sites of that cluster
9.Then created a frequency plot for each cluster
# data frame of cluster vs frequency:
![image](https://github.com/1biswarup2/shopify-stores-analysis/assets/56034566/649abb06-82b3-4d44-9df7-d389f8a924c8)

# Exploratory Data analysis:
# 1.
![image](https://github.com/1biswarup2/shopify-stores-analysis/assets/56034566/18e5f3fa-57c1-4ee8-b7a2-3d28b40a323f)
clearly we can see there exists outlier categories. So that clusters' categories are the prime customers/users.
# 2.
![image](https://github.com/1biswarup2/shopify-stores-analysis/assets/56034566/1985375d-53f7-4575-aac7-e1922015d908)
# 3.
![image](https://github.com/1biswarup2/shopify-stores-analysis/assets/56034566/370e8b69-145d-4f1c-bdde-d5bf876b96cd)

# 4.
![image](https://github.com/1biswarup2/shopify-stores-analysis/assets/56034566/c7fee022-c728-470b-a520-9f4fe6fcfd23)
# 5.
![image](https://github.com/1biswarup2/shopify-stores-analysis/assets/56034566/d7d038b5-f654-4369-97c1-acd3d5450971)

# Result:
# The outlier categories are;
1.Cluster0 :  The House Luxury Home Decor Furnishing Furniture
2.Cluster8 :  Best Natural Skin Care Products India Buy Beauty Products
#
we can conclude that the persons who are in the business related to luxury home furnitures and beauty/skin care products are the prime customers of the site.




