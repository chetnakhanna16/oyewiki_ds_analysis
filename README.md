# Oyewiki Data Science Analysis
  
![Oyewiki - youtube for reading and writing](https://github.com/chetnakhanna16/oyewiki_ds_analysis/blob/master/img/how-oyewiki-works.png)
  
## What is Oyewiki?
#### Oyewiki - Youtube for reading and writing

It was a product that we worked on from June 2016 to Dec 2018. 
We built a product for authors so that they can earn by writing articles. Just like video creator earn by uploading videos on youtube.

[[You can read more about Oyewiki on Quora](https://www.quora.com/search?q=oyewiki)]

![Oyewiki - youtube for reading and writing](https://github.com/chetnakhanna16/oyewiki_ds_analysis/blob/master/img/oyewiki_home_page.png)

## Analysis 1: Analyzing the popular email providers 
We have a list of around 7000 email ids provided by authors while signing up on the platform and we are analyzing this data to see the popular email provider. 

[[Jupyter Notebook Link](https://github.com/chetnakhanna16/oyewiki_ds_analysis/blob/master/email_list_analysis.ipynb)]

![Frequency of Email Providers (with gmail.com)](https://github.com/chetnakhanna16/oyewiki_ds_analysis/blob/master/img/barchart_email.png)

It can be observed from the bar chart that 'gmail.com' is the most popular email provider. As the value of this email provider is very large as compared to others, it is difficult to interpret information about the other email providers. It would be interesting to find what is the second most popular email provider and compare it with others email providers.

![Frequency of Email Providers (without gmail.com)](https://github.com/chetnakhanna16/oyewiki_ds_analysis/blob/master/img/barchart_email_no_gamil.png)

It can be interpreted from the bar chart that 'yahoo.com' is the second most popular email provider after 'gmail.com' and 'rediffmail.com' is the third most popular email provider. It is interesting to note that 'outlook.com', 'hotmail.com' and 'yahoo.co.in' are almost similar in popularity.

## Analysis 2: Analyzing the average length of email ids 

Now we are analyzing the average length of the emails that people create for themselves.

[[Jupyter Notebook Link](https://github.com/chetnakhanna16/oyewiki_ds_analysis/blob/master/email_list_analysis.ipynb)]

![Boxplot for Email Length](https://github.com/chetnakhanna16/oyewiki_ds_analysis/blob/master/img/boxplot_email.png)

It can be interpreted from the boxplot that the average length of an email ID ranges between 21 and 25 characters, with maximum email IDs of length 23. There are very few people who create email ID of length more than 31 characters.

## Analysis 3: Analyzing the articles data submitted by authors.

Here we are analyzing different aspects of columns present in Articles data. Mostly we will play with userid, title, description, body/content of articles and total views recieved on those articles.

![Distribution of average length](https://github.com/chetnakhanna16/oyewiki_ds_analysis/blob/master/img/hist_length_title.png)

It can be interpreted from the histogram that the length of title ranges between 2 and 120. Most of the articles have length less than 60 characters. Let us plot a boxplot to know more about the distribution of the title length.

![Boxplot of title length](https://github.com/chetnakhanna16/oyewiki_ds_analysis/blob/master/img/boxplot_length_title.png)

It can be interpreted from the boxplot that the minimum length of title is 3 characters and the maximum length of title is 125 characters. Also, the median length of title is 35 characters, which clearly indicates that maximum articles have length close to 35 characters. The interquantile range of the length of articles is 24 and 51, which indicates that 50% of the articles have length of title between 24 and 51. There are a few outliers as well which lies above the title length of 75 characters.



