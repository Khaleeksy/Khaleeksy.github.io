---
layout: post
title: Corpus Assignment
excerpt: "Exploring Sir Arthur Conan Doyle Corpus"
modified: 04/18/2023, 11:59:24
tags: [intro, beginner, jekyll, tutorial]
comments: true
category: blog
---

# IM-1511- Exploring Textual Data from a Custom Corpus


Sir Arthur Conan Doyle, prior to my exploratory analysis, was unknown to me, however, his fictional character and creation Sherlock Holmes, was not. Through movies, word of mouth and maybe two or three novels, I knew Sherlock Holmes to be an eccentric but brilliant detective who used his sixth and seventh senses of observation and deduction to solve the most complex of crimes. Upon elementary research, Sir Arthur Conan Doyle stood out to be, not only one of the most celebrated authors of detective fiction in history, but also a prolific writer whose contribution to literature and popular culture have been immense and whose legacy continues as the creator of Sherlock Holmes. 

The corpus presented compiles "The Adventures of Sherlock Holmes".  This corpus, which includes works by Sir Arthur Conan Doyle dating back to the 1930s, provides valuable insight into the detective fiction for which Doyle is well-known and adored. However, this information did not come from a linear read, which, to be honest, might have been nearly impossible even given the time constraints for this assignment. So,  how did I gain the confidence to relate the data from this corpus? Computer-Assisted Analysis. More specifically, textual analysis.  I was able to analyze Sir Doyle's corpus and gain a thorough understanding of the information it contained using analytical software tools such as AntConc and Voyant Tools. This gave me the opportunity to study word frequency, correlations, context, and trends, all of which would not have been possible with a linear read. Why? Because at what level can the human brain compare all 45 novels to find the word that appears the most frequently? The accuracy levels are guaranteed to be very low, and the process would take a lot of time. Fortunately, this was all eliminated by the computer-assisted analysis tools used on the corpus.

Following my initial scan of the corpus in an effort to get a sense of my analysis, I observed that the majority of the novels began with "The Adventures of..." My perspective was immediately changed, and I got the bright idea to evaluate all works that contained these words. I was pleasantly surprised by what I found. Without giving it much thought, I assumed that I would find a pattern that represented some of these adventures, perhaps including words like "mystery," "clue," "discover," and even "adventure." To my surprise, however, when the corpus was placed in AntConc their frequency was low or even non-existent in some cases.

![Initial Analysis](/images/adventure.jpg "Word Frequency for 'adventure' across corpus")

Instead, I discovered that throughout these "Adventure" books, the word Holmes was used the most. I mean, given that he is the main character, it does make sense for that word to be a constant throughout these books, so I considered the search to be fruitless and irrelevant.

![Highest Word Frequency-"Holmes"](/images/holmeswadv.jpg "Holmes as Highest Word Frequency in Corpus")

![Highest Word Frequency-"Holmes"](/images/adventurewordcloud.jpg "Holmes as Highest Word Frequency in Corpus")

However, upon using the bubble lines feature in Voyant Tools, I discovered that, compared to the other books in the corpus, "The adventures of Sherlock Holmes" had the highest concentration of the word "Holmes." So, in order to see if the word "Holmes" was truly the most frequently occurring word across the corpus, I removed it from the search. To my surprise, the word frequency of the books changed from "Holmes" to "said," but this particular book still held the top spot.

![Highest Word Frequency-"Said"](/images/woholmes.jpg "Removing Holmes from Word Frequency")

In order to investigate this further, I completely removed "The Adventures of Sherlock Holmes," and, thankfully, the results were as I had anticipated: an even distribution of the most frequently used words across the corpus. This one adventure book contained Sherlock Holmes so frequently that it spoke for the entire set of data. By eliminating this book, the analysis's accuracy levels unquestionably rose because it now represented a truer interpretation of the corpus and wasn't tainted by a single, heavily populated piece of data. Moreover, "Holmes" went from being the first highest frequency word, to the third highest frequency word.This demonstrated to me the fluidity of information and the simplicity with which textual information can be shaped to suit your interests and research. This may not have been a significant change, but it demonstrated how one small sub corpora can have a significant impact on an entire corpus. The frequency of Holmes in this one adventure book was so overwhelming, that it spoke for the entire data set.


![Removing "The Adventures of Sherlock Holmes"](/images/afterrem.jpg "Even distribution of the data in the corpus")

![Holmes as the third highest frequency word](/images/newword.jpg "Holmes is now the third highest frequency")


I was able to see the contexts in which these words were used throughout the books thanks to these tools, as well as the connections to other uses of the words in the book and with other books. Most of the time, the word "Holmes" was used in speech, and the word "said" was used in place of a narrator to relate what each character had said before. Additionally, I was able to determine the emotional tone of the novels and spot patterns of neutral, negative, or positive sentiment through sentimental analysis. This made it easier to comprehend the author's attitudes or beliefs regarding the intended readership.
The provided corpus turned out to be one that was adequate in every way. It was well-organized, the meta-data, which included information about the author, text, and publication date, was clear, and in my opinion, it demonstrated diversity in both its size and the number of readings from Sir Doyle it included. As a result, this sizable amount of data was able to be analysed in a way that adequately reflected his work. When choosing the corpus, the characteristics were carefully taken into account, which increased the analysis's usefulness and validity.

I thoroughly enjoyed the task at hand. This corpus' analysis opened my eyes to a fresh way of looking at reading that transcends the linear perspective. Having said that, would non-English speakers feel the same way? I think it goes further than simply translating the corpus for analysis. I think the textual analysis tools we are using in this case, perhaps using French, need to be set up so they can understand the data being shared as well as identify the change in language. Accuracy is also crucial because the whole point of using these analysis tools is to foster better understanding. However, the availability of resources for each language has an impact on this accuracy. While resources for popular languages may be easily accessible and of high quality, those for other languages may be hard to find and of subpar quality. Language differences would also be significantly influenced by cultural linguistic peculiarities and idiosyncrasies because they may change context and correlation. Therefore, this assignment would depend on the analysis tool's ability to identify these differences for languages other than English, and there I say, think critically. So, the real question is, can a computer-aided assistant provide this?
