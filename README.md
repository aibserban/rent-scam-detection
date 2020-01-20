# rent-scam-detection
A data science project with the main objective of detecting rental scamming adverts.

This project is meant to showcase my ability to form an typical data science and analysis project in Python, similar to a Kaggle competition, using a database of housing listings from a Dutch rental platform. 

**The objective** is to train a machine learning algorithm - or an ensemble of algorithms - to detect whether an ad is in fact legitimate or a fake offering and a method to defraud the users of the platform.

The model employed will therefore be a fraud detection algorithm implemented through supervised learning (as we have already labeled data).

The dataset contains 16,762 data points and each of the instances has the following features:

|Feature|Description|
|:-:|---|
|LISTING_KIND|0 - entire place; 1 - private room; 2 - shared room|
|LISTING_CITY|The city where the listing is located|
|LISTING_PRICE|The monthly rent (€) of the listing|
|IS_ARCHIVED|If the advertiser creating the listing has been archived or not.|
|ARCHIVE_REASON|The reason why the advertiser creating the listing has been (possibly) archived.|
|LOGIN_COUNTRY_CODE|The (last) country where the advertiser logged in from.|
|LISTING_COUNTRY_CODE|The country where the listing is located.|
|LISTING_REGISTRATION_POSSIBLE|If it’s possible to use listing’s address for registering at the city's municipality.|
|ADVERTISER_COMPLETENESS_SCORE|Percentage of completeness of the advertiser’s profile.|
|MANAGED_ACCOUNT|If the advertiser creating the listing is managed by our employees or not.|
|HAS_PROFILE_PIC|If the advertiser creating the listing has a profile pic or not.|
|BROWSER|The browser used to create the listing.|
|OS|The operating system used to create the listing.|
|ANONYMISED_EMAIL|The email address (anonymised) of the advertiser. Letters have been changed with random letters, numbers have been changed with random numbers, all the other characters have been maintained. The email domain has been maintained.|
|IS_SCAMMER|[Outcome] Whether the listing is a scam (1 - bad) or not (0).|
