## Builing Spam Filter with Naive Bayes

In this project, we're going to build a spam filter specifically directed at preventing mobile phone spam. Spam is most commonly associated with emails. Spamming, however, occurs in ways and environments that don't necessarily relate to emails:

* Articles or blog posts can be spammed with comments — the comments are ads or they are repetitive.
* An educational forum may be spammed with posts that are, in fact, ads.
* Mobile phone users may receive unwanted and unsolicited SMS messages, usually about advertising.

The filter we are going to build in this project will analyze new messages and tell whether they are spam or not — this way, we might be able to prevent spam from bothering mobile phone users. To build the spam filter, we'll apply the multinomial Naive Bayes algorithm to a dataset of 5,572 SMS messages stored in `SMSSpamCollection.txt` file.
