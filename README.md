# Election candidate finder

Final project for the Building AI course (https://buildingai.elementsofai.com/).

## Summary

Election candidate finder is an application that uses existing social media messages, networks and keywords in finding suitable election candidates for specific political party based on given parameters such as party's values.


## Background

It is difficult task to find enough suitable election candidates for a political party. Even with help of vast social networks it might be that some suitable candidates may not be asked for candidacy.  Election candidate finder can be used as a helper tool to ensure that plenty of good candidates are found.

Problem of finding candidates occurs yearly as there are always some political elections (be they local or national) being held yearly. Candidates should be found from different social and economical backgrounds as no specific group should be ruled out or discriminated.

Election candidate finder is a possible time saver for the party personnel whose task is to find and contact all the suitable candidates before the upcoming election.

Topic of finding candidates is interesting because it is in the essence of democracy that people choose their governing legislators. Therefore, it is important for every political party to find best possible electoral candidates for the people to choose from.


## How is it used?

Election candidate finder should have mandatory settings that need to be configured. Such as
* should the candidates be searched from local or national level,
* language should be also one thing to configure (e.g. Finnish, Swedish and English could be supported),
* defining of the core values and the keywords (hashtags and such),
* defining coefficients for the aforementioned values and keywords,
* optional: defining unwanted characteristics such as values and or keywords,
* optional: filtering results based on only 1st, 2nd or 3rd level of contacts from a given person (similar way as in LinkedIn's people search).

Based on the aforementioned configurations, the Election candidate finder should be able to perform rating process in order to decide whether a person would make a good candidate or not.

The user group of Election candidate Finder should be strictly controlled to include only the party personnel who are responsible for the task of gathering enough candidates for their political party.

Election candidate finder should be able to store the potential candidate results for further analysis. The candidate results could be later updated by running the election candidate finder again (e.g. a week later or with modified settings) to see whether there are any new candidates found. All the candidate results must be stored securely according to general data protection regulation (GDPR).


## Data sources and AI methods

Data source for Election candidate finder should be most popular social media platforms that exist such Twitter, Facebook, LinkedIn and so on. Data gathering should be automatized by using bots via APIs offered by different social media platforms.

The key AI method to use is Natural Language Processing (NLP) as AI should recognize whether certain topic is written in positive or negative context and whether the writer is for or against the topic. Neural network might be good for classification process. Also word embeddings might be helpful asset.


## Challenges

Election candidate finder works only with the data that is freely available from the Internet. That is, it is not able to find possible candidates whom are not active online in social media or hide behind anonymity. Therefore, it is still important use the personal social networks and human interaction in finding the candidates.

Election candidate finder might not be able to detect fake accounts and fake news from the social media feeds and thus the results might be biased or contain fake accounts. Therefore, it is crucial to be critical when inspecting the results given by the Election candidate finder.

Ethical considerations should be taken into account when Election candidate finder is implemented. That is, Election candidate finder should not be biased to find e.g. only highly educated people for candidates or only candidates that are in specific age group or any such discrimination. Therefore it is advisable to keep the source code of the project as open source and have it regularly inspected by other AI and ethic experts.


## What next?

Next the minimum viable product for the first version of Election candidate finder should be drafted. Then suitable software people should be gathered based on the drafted idea. Also people from some political party should be contacted whether they would like to volunteer in testing the Election candidate finder in future and to get the feedback from the actual client when implemting.


## Acknowledgments

Inspiration for creation of this AI project was the upcoming municipal elections that are being held in the spring of 2021.
