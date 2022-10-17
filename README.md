# UK Government Public Services Dataset Catalogue

This page catalogues datasets on UK public services available under a [Open Government Licence](https://en.wikipedia.org/wiki/Open_Government_Licence). They may be useful for analysing trends in use of central government services, linking data, and training models to detect the use of AI technologies. 

The list was created by [Vincent Straub](https://www.turing.ac.uk/people/researchers/bertie-vidgen), ..., and maintained by the AI for Public Services team at the Alan Turing Institute.

It provides background information on accessing UK government open data, a list of [datasets](#Datasets-header), as well as instructions on how to contribute in the[instructions for contributing](#Contributing-header).

<!--  If you use these resources, please cite (and read!) our paper: [Directions in Abusive Language Training Data: Garbage In, Garbage Out](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0243300). And if you would like to find other resources for researching online hate, visit The Alan Turing Institute's [Online Hate Research Hub](https://www.turing.ac.uk/research/research-programmes/public-policy/online-hate-research-hub) or read The Alan Turing Institute's [Reading List on Online Hate and Abuse Research](https://docs.google.com/document/d/1WVkVGp29Jt6d-4fBnZ5OWVYuFn_03rzz-KBqPsu6gTM/edit?usp=sharing). -->

Please send contributions via github pull request. You can do this by visiting the [source code] (link to be added) on github and clicking the edit icon (a pencil, above the text, on the right) - more details [below](#Contributing-header). There's a commented-out markdown template at the top of this file. Accompanying [data statements](https://www.mitpressjournals.org/doi/abs/10.1162/tacl_a_00041) preferred for all corpora.

<a id="Arabic-header"></a>
### Arabic
#### Are They our Brothers? Analysis and Detection of Religious Hate Speech in the Arabic Twittersphere
* Link to publication: [https://ieeexplore.ieee.org/document/8508247](https://ieeexplore.ieee.org/document/8508247)
* Link to data: [https://github.com/nuhaalbadi/Arabic_hatespeech](https://github.com/nuhaalbadi/Arabic_hatespeech)
* Task description: Binary (Hate, Not) 
* Details of task: Religious subcategories 
* Size of dataset: 6,136 
* Percentage abusive: 0.45 
* Language: Arabic 
* Level of annotation: Posts 
* Platform: Twitter 
* Medium: Text 
* Reference: Albadi, N., Kurdi, M. and Mishra, S., 2018. Are they Our Brothers? Analysis and Detection of Religious Hate Speech in the Arabic Twittersphere. In: International Conference on Advances in Social Networks Analysis and Mining. Barcelona, Spain: IEEE, pp.69-76. 


---
<a id="Keywords-header"></a>
# Lists of abusive keywords

1. __The Weaponized Word__
   * "The Weaponized Word offers several thousand discriminatory, derogatory and threatening terms across 125+ languages, available through a RESTful API. Access is free for most academic researchers and registered humanitarian nonprofits."
   * Data link: [weaponizedword.org](https://weaponizedword.org)

1. __Hurtlex__
   * "HurtLex is a lexicon of offensive, aggressive, and hateful words
   in over 50 languages. The words are divided into 17 categories, plus a
   macro-category indicating whether there is stereotype involved."
   * Data link: [github.com/valeriobasile/hurtlex](https://github.com/valeriobasile/hurtlex)
   * Reference: [Hurtlex: A Multilingual Lexicon of Words to Hurt](http://ceur-ws.org/Vol-2253/paper49.pdf), Proc. CLiC-it 2018

1. __Gorrell et al.__
   * Data link: [http://staffwww.dcs.shef.ac.uk/people/G.Gorrell/publications-materials/abuse-terms.txt](http://staffwww.dcs.shef.ac.uk/people/G.Gorrell/publications-materials/abuse-terms.txt)
   * Reference: [Twits, Twats and Twaddle: Trends in Online Abuse towards UK Politicians](https://gate-socmedia.group.shef.ac.uk/wp-content/uploads/2019/07/Gorrell-Greenwood.pdf), Proc. ICWSM
   * You can also use the GATE abuse tagger, available at [https://cloud.gate.ac.uk/shopfront/displayItem/gate-hate](https://cloud.gate.ac.uk/shopfront/displayItem/gate-hate)

1. __Wiegand et al.__
   * Data link: [https://github.com/uds-lsv/lexicon-of-abusive-words](https://github.com/uds-lsv/lexicon-of-abusive-words)
   * Reference: [Inducing a Lexicon of Abusive Words – A Feature-Based Approach](https://www.aclweb.org/anthology/N18-1095.pdf), Proc. NAACL-HLT 2018

1. __Chandrasekharan et al.__
   * Data link: [Reddit hate lexicon](https://www.dropbox.com/sh/5ud4fwxvb6q7k20/AAAH_SN8i5cfmJRKJteEW2b2a?dl=0)
   * Reference: [You can't stay here: the efficacy of Reddit's 2015 ban examined through hate speech](http://comp.social.gatech.edu/papers/cscw18-chand-hate.pdf), Proc. ACL Hum-Comput Interact. 

1. __Jiang et al.__
   * SexHateLex is a Chinese lexicon of hateful and sexist words.
   * Data link: [SexHateLex](https://doi.org/10.5281/zenodo.4773875)
   * Size of lexicon: 3,016
   * Reference: [SWSR: A Chinese Dataset and Lexicon for Online Sexism Detection](https://www.sciencedirect.com/science/article/abs/pii/S2468696421000604#fn1), Journal of OSNEM, Vol.27, 2022, 100182, ISSN 2468-6964.

<a id="Contributing-header"></a>
# How to Contribute

We accept entries to our catalogue based on pull requests to the `README.md` file. The dataset must be avaliable for download to be included in the list.
If you want to add an entry, follow these steps!

* Please send just one dataset addition/edit at a time - edit it in, then save. This will make everyone's life easier (including yours!)
* Go to the README.md file and click the edit button in the top right corner of the file.

<img width="1239" alt="Pasted Graphic" src="https://user-images.githubusercontent.com/22522221/150790020-ecbc6eea-3cf1-4134-ad51-a8a6334cfc2f.png">


* Edit the markdown file. Please first go the correct language. The items are then sorted by their publication date (newest first). Add your item by copy and pasting the following template and adding all the details:


```
#### Title
* Link to publication: [url](url) - link to the documentation and/or a data statement about the data
* Link to data: [url](url) - direct download is preferred, e.g. a link straight to a .zip file
* Task description: How the task is framed in this data, e.g. "Binary (Hate, Not)", "Hierarchical", "Three-class (Hate speech, Offensive language, None)"
* Details of task: Free-text description of the task this data models, e.g. "Misogyny detection on social media in Danish"
* Size of dataset: Give the number of instances of abusive/non-abusive/other items
* Percentage abusive: e.g. 1.2%
* Language: e.g. Arabic
* Level of annotation: What is an "instance", in this dataset? e.g. Posts, User, Conversation, ... 
* Platform: e.g. twitter, snapchat, ..
* Medium: text / image / audio / ...
* Reference: Give a bibliographic reference for the data (if there is one), with title, author, year, venue etc
```

* Check the “Preview Changes” tab to confirm everything is good to go!
* If you’re ready to submit, propose the changes. Make sure you give some brief detail on the proposed change.

<img width="1243" alt="Pasted Graphic 1" src="https://user-images.githubusercontent.com/22522221/150790254-c4c004cb-567d-4401-95ba-7b7be6de53fd.png">

* Submit the pull request on the next page when prompted.

---

This page is [http://hatespeechdata.com/](http://hatespeechdata.com/).
