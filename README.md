# b9122_homework2
 Homework2_XZ

Author Name:Xiaodan Zhu
UNI:xz3239


HW2_XZ.ipynb contains two tasks:

Q1a 
Extract at least 10 United Nations press releases containing the word “crisis”. Start with the following seed url: https://press.un.org/en. Notice how press release pages have the “PRESS RELEASE” relative link in the top left corner. The “PRESS RELEASE” has the following relative anchor tag:
<a href="/en/press-release" hreflang="en">Press Release</a>
One text file containing the html information will be generated for each url.


Q1b
Crawl the press room of the European Parliament and extract at least 10 press releases that cover the plenary sessions and contain the word “crisis”. Start with the following seed url:
https://www.europarl.europa.eu/news/en/press-room
Notice how press releases related to plenary sessions contain the text “PLENARY SESSIONS” with the following html: <span class="ep_name">Plenary session</span>
One text file containing the html information will be generated for each url.



webcrawler.py

It is the file provided in the class.