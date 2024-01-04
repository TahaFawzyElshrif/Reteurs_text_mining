# RETURES-DATA ANALYSIS

## about:
RETURES-DATA ANALYSISBig data of many topics of retures magazine articles

## PreProcess:
- to easy computation we worked on a sample (to use all data can make sample more big )
```
sample = data.sample(n=500, replace=True,random_state=123) 
```
or just `sample=data`
- delete null columns rows have strange values ex (IS RETURS TOPIC is just five so removed those rows)
- to make text more accessible Stemming,Lemmitizeing,Lower case
Delete stopwords
- tf idf to explore data

## visulaization : 
- by word count :
![Word count plot](readme_images/wordCount.png)

- and barplot for count


## Processing
### NN for predicating topic type (can be used to fit null values in rows) of 89% accuracy

### markovify model to generate text look like feeted data









## team:
Taha fawzy,Mostafa hussien ,Andrew Zakaria fawzy, Omar Ahmed taha,Ahmed Ibrahim hassan , Mohab emad ,Ahmed ali ,Adham abdelsalam mohammed Omar tarek Mahmoud





### compiled model and data csv:
https://drive.google.com/drive/folders/1NyOX55Iu8zjd-WeO2p-YMB03oatrRbf6?usp=sharing