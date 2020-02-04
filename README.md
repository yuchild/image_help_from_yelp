# Image Help From Yelp
***
**Image Processing for Business Insights**
***

Can machine learning help predict ratings based on user text? This project explores that possibility by using Natural Language Processing and various machine learning models to train on that dataset.

Yelp dataset is freely available to the public and can be found [here](http://www.yelp.com/dataset)
The dataset has the following files and features:

| File | Size | Entries | Features |
| :----- | :-----: | :-----: | :----- |
| business.json | 138MB | 192609 | businss_id, name, address, city, etc... |
| review.json | 5.3GB | 6685900 | review_id, user_id, business_id, stars, etc... |
| user.json | 2.5GB | 1636137 | user_id, name, review_count, yep_since, etc... |
| checkin.json | 409MB | 161950 | business_id, date |
| tip.json | 245MB | 1223094 | text, date, compliment_count, business_id, user_id |
| photo.json | 26MB | 200000 | photo_id, business_id, caption, label |
| 200K Photos | 7.2GB | 200000 | photos in .png file format |

**The lay of the land**

Using Stemming and Lemmatization filtering the following top 50 words appeared:

Stemming Words (Chops the ends of words to get to the root word):
<br>
![Top 50 Stemmed Words](top_50_stemming_words.png = 500X400)
<br>

Stemmed Word Cloud:
<br>
![Stemming Word Cloud](yelp_stem_wc.png = 500X500)
<br>

Lemmatizing (Uses a dictionary):
<br>
![Top 50 Lemmatized Words](top_50_lemmatized_words.png = 500X400)

Lemmatized Word Cloud:
<br>
![Stemming Word Cloud](yelp_lem_wc.png = 500X500)
<br>
