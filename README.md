# data-analysis-scraping
A short exercise on data analysis and web scraping regarding Bond movies

I was following the tutorial given in (https://realpython.com/python-for-data-analysis/) and did the excercises, along with some additional things I was interested to see.

For example, in true Bond fashion, I decided to see if there was a correlation between how attractive the main female character (the "Bond Girl") is, and how happy the audience was with the movie.

To this end I learned the basics of web scraping with requests and beautifulsoup, in order to retreieve the 'Bond Girl' rankings from this website (https://filmschoolrejects.com/bond-girls-ranked/).

Following that, and since I haven't seen a single Bond movie in my life, I did several iterations of data cleansing and analysis mentioned in the tutorial, before I got the results I actually wanted. This turned out to be a neat side quest to practice pandas a little more.

Finally, I used linear regression from scikit-learn to find if there's actually any correlation between the imdb and rotten tomatoes scores, and the 'Bond Girl' attractiveness.

Thankfully, the audience seems less sexist than the movies themselves, as I've found there's basically no correlation between the two.

Seems like people do watch Bond movies for... well... Bond.

The Data Analysis and Cleansing files are mostly uncommented since I just did the excercises from the website, and there's a much neater (and probably more optimized) solution that can be found there. The Data Scraping code is commented, however, since i was mostly on my own for that part, and I wanted to keep everything organized.
