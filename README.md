# Japanese_word2vec_pretrained_model
This is a word2vec model trained by Wikipedia in Japanese. It uses the training data of various user dictionaries, including Japanese names and place names



We used the Ukiyo-e terminology dictionary, the Dictionary of Japanese Personal Names, and the Dictionary of Ancient Japanese Geographical Names to create a user dictionary and optimize the tokenization of training data. 
The tokenization is shown in Fig.
![](image/tokenization.png)

Table shows the results of Japanese words similarity under our retrained word2vec model

==============================================================================
Input	Similar words (top 5)
神奈川沖浪裏	富嶽三十六景: 0.72 凱風快晴: 0.71浪花百景: 0.66名所江戸百景: 0.63
歌川広重	渓斎英泉: 0.74歌川国芳: 0.73豊原国周: 0.72歌川国輝: 0.72歌川貞秀: 0.71
月岡芳年	山崎年信: 0.84歌川芳豊: 0.83歌川貞秀: 0.83楊斎延一: 0.83歌川芳員: 0.83
日本橋	蛎殻町: 0.63久松町: 0.61日本橋本町: 0.61日本橋人形町: 0.61日本橋堀留町: 0.60
浮世絵	肉筆浮世絵: 0.69肉筆画: 0.67美人画: 0.67名所絵: 0.65菱川師宣: 0.65
==============================================================================
For more information on how to use these models, see：

References
----------
https://www.pytry3g.com/entry/gensim-wikipedia-word2vec
Thanks for sharing! It was great. 


Authors
-------

- @Kangying Li 


License
