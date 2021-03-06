# Current Class-by-Class Schedule

## Introduction and Overview

8/20 – [SYNCHRONOUS](https://emory.zoom.us/j/97982394236)
##### What does it mean to be practical?

* In class: syllabus overview, intro/transcription exercise
  
8/25 – [SYNCHRONOUS](https://emory.zoom.us/j/97707116544)
##### What can you do with text?

* Before class:
	* Read: Li-Young Lee, “[Persimmons](https://www.poetryfoundation.org/poems/43011/persimmons)”
	* Read: Michael Whitmore, “[Text: A Massively Addressable Object](https://dhdebates.gc.cuny.edu/read/untitled-88c11800-9446-469b-a3be-3fdb36bfbd1e/section/402e7e9a-359b-4b11-8386-a1b48e40425a)”
	* [Canvas: Discussion of "text"](https://canvas.emory.edu/courses/76593/discussion_topics/422564)
	* [Discussion Forum guidelines](../docs/DiscussionForum.pdf)

* In class: Close reading and [Voyant](https://voyant-tools.org/) exercise 


## Unit 1: Turning Text into Data

8/27 – [SYNCHRONOUS](https://emory.zoom.us/j/97982394236)
##### JupyterHub & GPT-3
* Before class:
	* Log in to our course's [JupyterHub](https://qtm340.ecdsdev.org/):
		* Your ID is your Emory NetID
		* Whatever you enter as your password the first time will become your password
		* After you have logged in, return here and click on [this link](https://bit.ly/2QklTdO) to load course materials
		* The site will take a moment to load. When it's finished, click [here](https://qtm340.ecdsdev.org/) 
		* You should arrive at JupyterHub with access to our course materials
		* If you have any problems: **come to class early, at 4PM Eastern, to troubleshoot**
	* Read Farhad Manjoo's [How Do You Know a Human Wrote This?](https://www.nytimes.com/2020/07/29/opinion/gpt-3-ai-automation.html)
	* Spend at least 30 minutes playing [AI Dungeon](https://play.aidungeon.io/)
	* Canvas: Use GPT-2 to write your post. Go [here](https://transformer.huggingface.co/doc/gpt2-large). Delete the given text. Write the first 30-50 words of your post, then use tab and choose selections to let GPT-2 finish it.

9/1 - ASYNCHRONOUS
##### Platforms and People

* Read: Lilly Irani, “[Justice for ‘Data Janitors’](https://www.publicbooks.org/justice-for-data-janitors/)”
* Canvas: Discussion of Irani
* Notebook: Intro to Jupyter | [notebook](../notebooks/class4-jupyter-intro-ds.ipynb)

9/3 – [SYNCHRONOUS](https://emory.zoom.us/j/97982394236)
##### Web Scraping

* Before class:
	* Read: Astead Herndon et al.,, “[What Do Rally Playlists Say About the Candidates?](https://www.nytimes.com/interactive/2019/08/19/us/politics/presidential-campaign-songs-playlists.html)”
	* Hanah Anderson and Matt Daniels, “[Film Dialogue](https://pudding.cool/2017/03/film-dialogue/)”
  * Canvas: Discussion of Anderson and Daniels
* In class: Web scraping and HTML parsing using Beautiful Soup ([class notebook](../notebooks/class5-web-scraping-inclass-ds.ipynb))

9/8 – ASYNCHRONOUS
##### APIs

* Read Xavier Adam, “[An Illustrated Introduction to APIs](https://medium.com/epfl-extension-school/an-illustrated-introduction-to-apis-10f8000313b9)” and “[API Whispering 101](https://medium.com/epfl-extension-school/api-whispering-101-e04fbb5a08fd)”
* Work through the notebooks "class6-accessing-apis-inclass.ipynb," and More with APIs (accessing APIs: [class notebook](../notebooks/class6-accessing-apis-inclass-ds.ipynb) | Genius API [class notebook](../notebooks/class6-genius-api-inclass-ds.ipynb))

9/10 - [SYNCHRONOUS](https://emory.zoom.us/j/97982394236)
##### Text Parsing / Regular Expressions

* [**HW1 Due**:](../docs/hw1-ds.pdf) Scrape the song lyrics of one of the candidate's songs from genius.com using Beautiful Soup [(assignment on Canvas)](https://canvas.emory.edu/courses/76593/assignments)

* Before class:
	* Read: David Zentgraf, [“What Every Programmer Absolutely, Positively Needs to Know about Encodings and Character Sets to Work with Text”](https://kunststube.net/encoding/)
	* Read: Scott Weingart, ["The Route of a Text Message"](https://scottbot.net/the-route-of-a-text-message/)
	* Canvas: Discussion of Weingart

* In class: Text parsing and regex with our candidate song lyrics (regex: [class notebook](../notebooks/class7-regex-intro-inclass-ds.ipynb), [complete notebook]| cleaning song lyrics: [class notebook](../notebooks/class7-regex-with-song-lyrics-inclass-ds.ipynb), [complete notebook])

## Unit 2: Operationalizing Text as Data

9/15 – ASYNCHRONOUS
##### Sentiment Analysis 

* Read: Ethan Reed, “[Measured Unrest in the Poetry of the Black Arts Movement](https://scholarslab.lib.virginia.edu/blog/measured-unrest-in-the-poetry-of-the-black-arts-movement/)”, ["Poems with Pattern and VADER, Part 1: Quincy Troupe"](https://scholarslab.lib.virginia.edu/blog/poems-with-pattern-and-vader-part-1-quincy-troupe/), ["Poems with Pattern and VADER, Part 2: Nikki Giovanni"](https://scholarslab.lib.virginia.edu/blog/poems-with-pattern-and-vader-part-2-nikki-giovanni/)
* Read: Catherine D’Ignazio and Lauren Klein, “[The Numbers Don’t Speak for Themselves](https://bookbook.pubpub.org/pub/6ui5n4vo)”
* Canvas: Discussion of Reed, and D'Ignazio and Klein
* Notebook: [song lyric corpus](../notebooks/class8-lyrics-scraping-inclass-ds.ipynb) | [sentiment analysis](../notebooks/class8-sentiment-analysis-inclass-ds.ipynb)

9/17 – [SYNCHRONOUS](https://emory.zoom.us/j/97982394236)
##### Natural Language Processing 101 (NER, POS tagging)

* Before class:
	* Read: Lauren Klein, “[The Image of Absence: Archival Silence, Data Visualization, and James Hemings](https://read-dukeupress-edu.proxy.library.emory.edu/american-literature/article-pdf/85/4/661/393292/AL854_03Klein_Fpp.pdf)”
	* Read: Ishan Misra et al., “[Seeing through the Human Reporting Bias: Visual Classifiers from Noisy Human-Centric Labels](https://arxiv.org/pdf/1512.06974.pdf?fbclid=IwAR2OwfGEBmPR2ngyN0Hu2JYIEa7rwUe2VTGV8x3laDp89KxL1o6LBERXb9M)”
	* Canvas: discussion of Klein and Mishra
* In class: Part-of-Speech (POS) tagging, Named Entity Recognition (NER) ([class notebook](../notebooks/class11-nlp-spacy-inclass.ipynb), [complete notebook](../notebooks/class11-nlp-spacy-complete.ipynb))

9/22 – ASYNCHRONOUS
##### Turning Words into Numbers

* Read: Aurelie Herbelot, ["Distributional Semantics: A Light Introduction"](https://aurelieherbelot.net/research/distributional-semantics-intro/)
* Read: Daniel Jurafsky & James H. Martin, ["Vector Semantics & Embeddings": SECTIONS 6-6.3](https://web.stanford.edu/~jurafsky/slp3/6.pdf)
* Notebook: [intro to sklearn]

9/24 – [SYNCHRONOUS](https://emory.zoom.us/j/97982394236)
##### Word counts, tf-idf

* Before class:
	* Read: Charlie Smart, “[The Differences in How CNN, MSNBC, & Fox Cover the News](https://pudding.cool/2018/01/chyrons/)”
	* Read: Daniel Jurafsky & James H. Martin, ["Vector Semantics & Embeddings": SECTIONS 6.5-6.6](https://web.stanford.edu/~jurafsky/slp3/6.pdf)

* In class: word counts, tf-idf ([class notebook](../notebooks/class10-counting-words-inclass.ipynb), [complete notebook])
* intro of final project 
* **HW 2 Due:** 

9/29 - ASYNCHRONOUS
##### Topic Modeling

* Before class:
	* Read: Cameron Blevins, “[Topic Modeling Martha Ballard’s Diary](http://www.cameronblevins.org/posts/topic-modeling-martha-ballards-diary/)”
	* Read: Lisa Rhody, “[Topic Modeling and Figurative Language](http://journalofdigitalhumanities.org/2-1/topic-modeling-and-figurative-language-by-lisa-m-rhody/)”
	
* In class: topic modeling ([class notebook](../notebooks/class9/class9-topic-modeling-inclass.ipynb), [complete notebook](../notebooks/class9-topic-modeling-complete.ipynb)) 	

10/1 - [SYNCHRONOUS](https://emory.zoom.us/j/97982394236)
##### Word vectors 

* Read: Sarah Connell, “[Word Embedding Models are the New Topic Models](https://web.northeastern.edu/nulab/word-embedding-model/)”
* Read: Ben Schmidt, “[Gendered Language in Teacher Reviews](http://benschmidt.org/profGender)”
* Canvas: discussion of Connell and Schmidt
* Notebook: word vectors ([class notebook](../notebooks/class12-word-vectors-inclass.ipynb), [complete notebook](../notebooks/class12-word-vectors-complete.ipynb))

10/6 – ASYNCHRONOUS
##### BERT (Bidirectional Encoder Representations from Transformers)

* TBD

10/8 - [SYNCHRONOUS](https://emory.zoom.us/j/97982394236)
##### Unit 2 Wrap-up

* Final Project Brainstorming Session

## Unit 3: (More) Modeling Textual Data
10/13 – ASYNCHRONOUS
##### Pandas 

* Notebook: pandas ([class notebook](../notebooks/class13-pandas-inclass.ipynb), [complete notebook](../notebooks/class13-pandas-complete.ipynb))
* **HW 3 Due:** TBD

10/15 - [SYNCHRONOUS](https://emory.zoom.us/j/97982394236)
##### Another Look at Data
* Before Class:
	* Read: Heather Krause, “[Data Biographies: Getting to Know Your Data](https://gijn.org/2017/03/27/data-biographies-getting-to-know-your-data/)”
	* Read: Timnit Gebru et al., “[Datasheets for Datasets]"(https://arxiv.org/pdf/1803.09010.pdf)
* Notebook: more pandas ([class notebook](../notebooks/class14-pandas-in-action-inclass.ipynb), [complete notebook](../notebooks/class14-pandas-in-action-complete.ipynb))

10/20 – ASYNCHRONOUS
##### Language Models
* Read: David Smith and Ryan Cordell, [“Mass Digitization”](https://manifold.umn.edu/read/untitled-883630b9-c054-44e1-91db-d053a7106ecb/section/ea1f849a-bac1-4e9d-85f4-149d0083a6a4) and [“What is Text, Probably?”](https://manifold.umn.edu/read/8ddd9c7c-c2db-44be-91a6-732d1d08ec47/section/4cb9d511-6870-4108-ba4e-2726d106dd39#ch03)

10/22 – [SYNCHRONOUS](https://emory.zoom.us/j/97982394236)
##### Similarity

* Before Class:
	* Read: Patrick Juola, “[How a Computer Program Helped Show J.K. Rowling Wrote A Cuckoo’s Calling](https://www.scientificamerican.com/article/how-a-computer-program-helped-show-jk-rowling-write-a-cuckoos-calling/)” (and [more technical version](https://languagelog.ldc.upenn.edu/nll/?p=5315) if you're curious)

* In class: classification ([class notebook](../notebooks/class15-classification-inclass.ipynb), [complete notebook](../notebooks/class15-classification-complete.ipynb))

* **FPP 1 Due: Datasheet OR Project Proposal**

10/27 – ASYNCHRONOUS
##### Classificartion

* Read: Terra Blevins et al., “[Automatically Processing Tweets from Gang-Involved Youth: Towards Detecting Loss and Aggression](https://www.aclweb.org/anthology/C16-1207)”
* Notebook: classification ([class notebook and required files](../notebooks/class16.zip), [complete notebook](../notebooks/class16/class16-clustering-complete.ipynb))

10/29 – [SYNCHRONOUS](https://emory.zoom.us/j/97982394236)
##### Neural Networks
* TBD

11/3 - ASYNCHRONOUS
# **ELECTION DAY—VOTE!!**
##### Clustering
* Read: Matt Daniels, “[The Language of Hip Hop](https://pudding.cool/2017/09/hip-hop-words/)”
* Read: Alexis Madrigal, “[How Netflix Reverse Engineered Hollywood](https://www.theatlantic.com/technology/archive/2014/01/how-netflix-reverse-engineered-hollywood/282679/)”
* Notebook: more classification ([class notebook](../notebooks/class17-more-classifying-inclass.ipynb) and more clustering ([class notebook](../notebooks/class17-more-clustering-inclass.ipynb))

* **FPP 2 Due: Datasheet OR Project Proposal**

## Unit 4: Arguing with Textual Data

11/5 – [SYNCHRONOUS](https://emory.zoom.us/j/97982394236)
##### Making arguments

* Before Class:
	* Read: Dong Nguyen et al., “[How we do things with words: Analyzing text as social and cultural data](https://arxiv.org/pdf/1907.01468.pdf)”
	* Read: Ted Underwood, David Bamman, and Sabrina Lee, [“The Transformation of Gender in English Language Fiction”](https://culturalanalytics.org/article/11035-the-transformation-of-gender-in-english-language-fiction)
* In class: discussion of Nguyen et al, Underwood et al, and final project

11/10 – ASYNCHRONOUS
##### Validation, day 1

* Read: Matthew Salganik, “Moving Beyond Simple Experiments,” from Bit by Bit: Social Research in the Digital Age (on Canvas)
* Canvas: discussion of assigned papers (and a few other examples) ([class slides](../slides/class18-slides.pdf))

* **FPP 3 Due: Exploratory Analysis**

11/12 – [SYNCHRONOUS](https://emory.zoom.us/j/97982394236)
##### Validation day 2

* Before Class:
	* Read: Richard Jean So, “[All Models are Wrong](https://www-mlajournals-org.proxy.library.emory.edu/doi/pdf/10.1632/pmla.2017.132.3.668)”
	* Read: Safiya Noble, “Introduction” and “Searching for Black Girls” from Algorithms of Oppression: How Search Engines Reinforce Racism (on Canvas)
* Canvas: discussion of So and Noble
* In class: overview of methods of validation ([class slides](../slides/class19-slides.pdf))

11/17 – SYNCHRONOUS
##### Project presentations

11/19 – [SYNCHRONOUS](https://emory.zoom.us/j/97982394236)
##### Project presentations

11/24 – SYNCHRONOUS
##### Course wrap-up and assessment

### FINAL PROJECTS DUE TBD

*Lauren F. Klein wrote and designed the first version of this syllabus, inspired by the courses of [Jinho Choi](https://github.com/emory-courses/data-science), [Alison Parrish](http://www.decontextualize.com/teaching/), [David Mimno](https://mimno.infosci.cornell.edu/info3350/), [David Bamman](http://people.ischool.berkeley.edu/~dbamman/info256.html), [Ryan Cordell](http://s17hda.ryancordell.org), and [Ben Schmidt](http://benschmidt.org/HDA19/), as well as suggestions and other input from Heather Froehlich, Ted Underwood, Jacob Eisenstein, Jim Casey, Taylor Arnold, Lauren Tilton, Lisa Rhody, Eileen Clancy, and the Colored Conventions Project Team. I supplemented the syllabus with inspiration from Melanie Walsh.*
