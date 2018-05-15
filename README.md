# Annual trends of NIH grant success rates

Wanted to learn Beautifulsoup for webscraping. So as a mini project, decided to scrape annual grant information from NIH website and plot the annual trends in number of grants reviewed, compared to those awarded and the pot of money used. Spoiler alert ! The resulting plot is depressing.

The data is available at [NIH RePORT](https://report.nih.gov/success_rates/) website. However, the options are either (a) website table with pulldown selection for year; (b) excel sheet with some fields highlighted by font adjustments (bold) or (c) downloading the plots (in png format) which may or may not always be what you want. Both formats are not easy to work with without manual manipulation. Hence decided to use beautiful soup to scrape the excel sheet information.

Check out the [jupyter notebook](nihGrant_success-rate.ipynb) for how the plots below were made !

![Alt text](awardedReviewd.png?raw=true "Title")

![Alt text](awardedReviewedR01.png?raw=true "Title")
