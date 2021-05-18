# Place context analysis using Natural Language Processing
### :hammer: Exercise
In this exercise, I am using Natural Language Processing to explore a book author's sense of place about Seattle. The tutorial can be found here https://github.com/jakobzhao/geog595/blob/master/06_ai/pe.md

Wordcloud:
![](/assets/gay-seattle/06-points.png)

![](/assets/gay-seattle/06-network.png)

![](/assets/gay-seattle/06-snake.png)

We can see key keywords such as e-commerce, agriculture and business appreard very often in this case. There were also discusssion about ecosystem and climate change which are emergent environmental concerns. Some new words such as agri-tech emerged. Also we see the hot key word such as Covid-19 and Blockchain. Also there were a few discussions about cross-boundary/international trade during this pandemic era.

- geosearch: This python crawler collected twitter data using the twitter API tool in this case. I set the `time limit`to 60 to parse the data, and `time sleep`to 5 to mimic the behavior of a human.

Location are bounded to US, and I got 2831 tweets. The output was saved as csv in the assest folder.


Reference Link [https://github.com/jakobzhao/geog595/tree/master/03_bot]
