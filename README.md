# shoppriced
#### Video Demo:  
https://youtu.be/cyR8gnFNnOo
#### Description:
For this project, I wanted to develop a price tracker and comparison website and browser extension for popular local ecommerce sites like Shopee and Lazada. However, I found out early on about the difficulties of scraping on Shopee, which as far as I know does not have an API for readily retrieved prices and has a slew of anti-scraping features (boo...) Hence, I settled for Amazon to learn the basics of scraping.

My focus was not on the front-end or the aesthetics of the website, so I elected to use the basic layout of the templates in Pset Finance. For the backend, I considered Django, but ultimately stuck with Flask to make it easier on myself. Through thinking out the logic of how I want the backend and redirections for my website to work, I finally realised that theres actually many different ways to set up the back logic and that there is no one certain fixed method. I also had to think thoroughly about when to use Get vs Post. 

Finally, I tried to deploy the application onto Oracle's free VM service through Apache and Wsgi. After much troubleshooting, I finally have the webpage displaying, but the website still crashed and the error log shows a segmentation fault whenever a db query is executed (I think.) Still working on that!
