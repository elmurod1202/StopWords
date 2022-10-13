# StopWords: Automatic detection of stopwords for Uzbek

Feel free to use the dataset(aka "School Corpus") and the code presented in this repo, a paper about more details with the same title is coming soon.


Stop words are very important for information retrieval and text analysis investigation. This study aimed to automatically analyze and detect stop words in texts in the Uzbek language. Because of the limited availability of methods for automatic search of stop words of texts in Uzbek we analyzed a newly prepared corpus. The Uzbek language belongs to the family of agglutinative languages. As with all agglutinative languages, we can explain that the detection of stop words in Uzbek texts is a more complex process than in inflected languages: In inflected languages, words such as auxiliary words, articles, prepositions can be included in the stop words group. In agglutinative languages, the meanings of such words are hidden in the text. Therefore, it is not appropriate to apply all known methods of stop words detection in inflected languages directly to agglutinative languages.

In this work, the “School corpus” which contains 731156 Uzbek words has been investigated. The bigram method of analysis was applied to the corpus. We proposed the collocation method of detecting stop words of the corpus. We proposed the method of automatically detecting stop words of texts in Uzbek. It is shown that the collocation method is 6 times better than the bigram method.

The "School Corpus" used in this work can also be found at this link: [https://zenodo.org/record/6319953](https://zenodo.org/record/6319953).


The methodology used for this research work:
<div align="center">
<img src="https://github.com/elmurod1202/StopWrords/blob/main/src/schema.jpg?raw=true" width = "600" Alt = "The Methodology">
</div>
Figure: Scheme of the whole process.



The results obtained in this research work:
<div align="center">
<img src="https://github.com/elmurod1202/StopWrords/blob/main/src/results.jpg?raw=true" width = "600" Alt = "The Methodology">
</div>
Figure: Comparison of the methods used.
