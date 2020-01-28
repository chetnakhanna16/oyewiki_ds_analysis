# Oyewiki Data Science Analysis
  
## What is Oyeiwki?
#### Oyewiki - Youtube for reading and writing

It was a product that we worked on from June 2016 to Dec 2018. 
We built a product for authors so that they can earn by writing articles. Just like video creator earn by uploading videos on you tube.

[[You can read more about Oyewiki on Quora](https://www.quora.com/search?q=oyewiki)]

![Oyewiki - youtube for reading and writing](https://qph.fs.quoracdn.net/main-qimg-753cc4a2173d162881f15abe2e862ca4)

## Project 1: Analyzing the popular email providers 
We have a list of around 7000 email ids provided by authors while signing up on the platform and we are analyzing this data to see the popular email provider. 

[[Jupyter Notebook Link](https://github.com/chetnakhanna16/oyewiki_ds_analysis/blob/master/email_list_analysis.ipynb)]

![Frequency of Email Providers (with gmail.com)](https://github.com/chetnakhanna16/oyewiki_ds_analysis/blob/master/img/barchart_email.png)

It can be observed from the bar chart that 'gmail.com' is the most popular email provider. As the value of this email provider is very large as compared to others, it is difficult to interpret information about the other email providers. It would be interesting to find what is the second most popular email provider and compare it with others email providers.

![Frequency of Email Providers (without gmail.com)](https://github.com/chetnakhanna16/oyewiki_ds_analysis/blob/master/img/barchart_email_no_gamil.png)

It can be interpreted from the bar chart that 'yahoo.com' is the second most popular email provider after 'gmail.com' and 'rediffmail.com' is the third most popular email provider. It is interesting to note that 'outlook.com', 'hotmail.com' and 'yahoo.co.in' are almost similar in popularity.

## Project 2: Analyzing the average length of email ids [Jupyter Notebook Link](https://github.com/chetnakhanna16/oyewiki_ds_analysis/blob/master/email_list_analysis.ipynb)

Now we are analyzing the average length of the emails that people create for themselves.

[[Jupyter Notebook Link](https://github.com/chetnakhanna16/oyewiki_ds_analysis/blob/master/email_list_analysis.ipynb)]

![Boxplot for Email Length](https://github.com/chetnakhanna16/oyewiki_ds_analysis/blob/master/img/boxplot_email.png)

It can be interpreted from the boxplot that the average length of an email ID ranges between 21 and 25 characters, with maximum email IDs of length 23. There are very few people who create email ID of length more than 31 characters.
