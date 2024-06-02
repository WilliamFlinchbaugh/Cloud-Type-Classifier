# Cloud Type Classifier
This was *meant* to be made into an app which could classify the type of clouds by taking a picture on your phone.

However, there's no dataset that I could find which had cloud labels, so the only way I could think to make a dataset was to webscrape images with a query for each type of cloud.

Unfortunately, my proof-of-concept approach didn't end up working very well because the data is pretty poor quality and there tends to be a lot of co-mingleing of types within each query. There's also just a lot of challenges with this problem considering that different conditions can make certain types of clouds look wildly different, and it's also very hard to gauge depth of clouds through images.

There's probably a way to use unsupervised learning, but there's still a lot of challenges to face there, so I decided to put this one on the backburner for now.
