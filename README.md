---
title: 'Project 2: R you having fun?'
author: "Eryn Wali (GL), Krisha Vaishnav, Ashita Kumar"
date: "07/10/2021"
output: html_document
---

![Ashoka University logo](https://www.ashoka.edu.in/admin_assets/global/images/logo/logo-ashoka.png)


## Title 

> Saga of the MPF Corpus

## Introduction + Research Question 

Over the years, many female authors have adopted male (or gender-ambiguous) pseudonyms to publish without prejudice in male-dominated literary circles, encourage male readership, and reach new audiences, among many other reasons. In this short analysis, we intend to bring out differences in both the style and content of such texts published under pseudonyms, with a focus on 19th century English literature. We decided to explore this by observing how characters, their genders, and contexts differed for all 3 types of authors. We also took into account dominating literary themes present and focus on the differences or similarities between them.

## Research Hypothesis 

> There is a statistical difference in the way gender and themes are portrayed when female authors who write under male pseudonyms are compared with their female and male author counterparts.


## Corpus Description
 
We created a corpus where we picked an equal number of works by three categories of authors. The corpus wasn’t exhaustive; it was manually curated making subjective judgments. We chose 4 books each from female authors who wrote under male pseudonyms, female authors, and male authors. As we were focusing on finding the counterparts of pen name authors, we chose counterparts who wrote in the same century as them or even whose work was compared with them. The works we selected by each author were their most famous works present on Gutenberg. 

## Summary Paragraph 



## Sentiment Analysis 
Jocker establishes some of these topics as more ‘masculine’ than others. We tried to find a similar trend in our corpus. We used words such as ‘fashion’, ‘rivalry’, ‘alcohol’, ‘nature’, ‘weapons’, and ‘money’ and saw the frequency of these themes present in all 3 authors.

                      
Observing these tables, we found that:
For the theme of ‘money’, male authors and pen authors wrote at a similar frequency which was comparatively higher than female authors.
For the themes of ‘fashion’, ‘nature’, and ‘weapons’, male authors and pen authors wrote comparatively more about these themes than female authors.
Apart from the above-mentioned instances, we found that female authors and pen authors tended to have similar frequencies on the themes.



## Named Entity Recognition 


We used this to see how many dominant male roles were present in each of the books and the number of characters present for all 3 authors. We found that:


Female and pen authors had comparatively many more characters present than male authors.
The theme of ‘science’ was also heavily dominating the book ‘Behind a Mask’ by A.M. Barnard (pen author).
Pen authors tended to have more male characters present as compared to female authors.
‘Saints’ were present more dominantly in male and pen authors which hints at a more religious representation as compared to female authors.


We used this to see the positive or negative connotations of the characters that were presented in the books. The findings we got after observing the graphs were:

The instances where a negative representation or character was seen in a negative connotation was only in 4 books; Crime and Punishment by Fyodor Dostoyevsky (male author), Jane Eyre by Currer Bell (pen name author), Les Miserables by Victor Hugo (male author) and Monday or Tuesday by Virginia Woolf (female author). From this, we can conclude that male authors tended more towards negative characters than female authors who wrote under real names and male pseudonyms. 
For pen authors, it is observed how female characters tend to have lesser positive representation than especially female authors.
For pen authors, it is also observed how male characters tend to have more or equal positive representation than male authors.



## Conclusion
 
Although a few stark differences were noticed in the themes and characters, there were still many similarities that existed between male and pen authors, and female and pen authors. With the themes, we could say that pen authors wrote in a more negative light as compared to the female authors.

A surprising find was how themes like ‘fashion’, ‘nature’ which are considered more “feminine” as per Jocker and also in the context of a much more patriarchal society that existed back then were actually written more on by pen and male authors.

For the theme of ‘weapons’, we noticed that male and pen authors wrote comparatively more on this, while for the theme of ‘rivalry’ we noticed how male authors wrote more than female and pen authors. But observing both together, we could say male and pen authors hint more at violence, wars, etc. than female authors. 



## Reflection

The first major drawback we encountered was the manual cleaning of data we had to do for NER. Although the process wasn’t a tough one, it was very time-consuming. As our corpora consisted of 12 books, we had to spend hours going through all the words and either clearing it up or changing the ‘kind’ of the word which was present.

It was hard to come with a strong conclusion statement as we lost a few of the NER charts due to the amount of data and hence, we must have missed some key observations.

The second major drawback also stemmed from the abundance of data we had. In NER, the charts (attached below) were not presented clearly as the amount of data couldn’t be depicted clearly. 

The difference from Voyant was that the cleanup was much more time-consuming and as it was manual, there might have been instances where unnecessary data was either left in or necessary data was taken out. 
