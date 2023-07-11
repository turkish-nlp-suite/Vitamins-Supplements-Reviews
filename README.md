# Vitamins and Supplements Customer Reviews Dataset

Turkish sentiment analysis dataset from customer reviews about supplemen and vitamin products. This dataset is scraped from Vitaminler.com.

This dataset is a Turkish NLU dataset that contains customer reviews and star rating about vitamin and supplement products.
Each dataset instance contains 

- product name
- brand name
- id
- average star rating value
- number of customer ratings
- a list of customer reviews and star ratings

Here's an example annotation for you:

```
{
  "name": "Microfer Şurup 250 ml",
  "brand": "Ocean",
  "rating": {
    "averageRating": 4.521739130434782,
    "totalCount": 69
   },
   "id": 1,
   "reviews": [
    {
      "review_id": 0,
      "star": 5,
      "review": "Bittikçe alıyorum harika bişey kızım tadını da seviyor"
    },
    {
      "review_id": 1,
      "star": 5,
      "review": "minik hediyeleriniz için teşekkürler... ürün güzel paketlenmiş hızlı teslimat 👍"
    },
    {
      "review_id": 2,
      "star": 5,
      "review": "Ben kendim için aldım ama çocuklara içirmek zor olur gibi geldi, demir tadı ağza yayılıyor kötü hissettiriyor. Belki portakal suyuna karıştırılarak kullanılabilir. Yetişkinlerde 2,5 ml günlük ihtiyacı tam karşılamıyor bu arada."
    }
   ]
}
```

The dataset includes 1,052 products of 262 distinct brands with 244K customer reviews. During the compilation, we eliminated reviews containing person names such as customer's name and influencer names.  

This work is supported by Google Developer Experts Program. Part of Duygu 2022 Fall-Winter collection, "Turkish NLP with Duygu"/ "Duygu'yla Türkçe NLP". All rights reserved. If you'd like to use this dataset in your own work, please kindly cite the paper [A Diverse Set of Freely Available Linguistic Resources for Turkish](https://aclanthology.org/2023.acl-long.768/):

```
@inproceedings{altinok-2023-diverse,
    title = "A Diverse Set of Freely Available Linguistic Resources for {T}urkish",
    author = "Altinok, Duygu",
    booktitle = "Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = jul,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.acl-long.768",
    pages = "13739--13750",
    abstract = "This study presents a diverse set of freely available linguistic resources for Turkish natural language processing, including corpora, pretrained models and education material. Although Turkish is spoken by a sizeable population of over 80 million people, Turkish linguistic resources for natural language processing remain scarce. In this study, we provide corpora to allow practitioners to build their own applications and pretrained models that would assist industry researchers in creating quick prototypes. The provided corpora include named entity recognition datasets of diverse genres, including Wikipedia articles and supplement products customer reviews. In addition, crawling e-commerce and movie reviews websites, we compiled several sentiment analysis datasets of different genres. Our linguistic resources for Turkish also include pretrained spaCy language models. To the best of our knowledge, our models are the first spaCy models trained for the Turkish language. Finally, we provide various types of education material, such as video tutorials and code examples, that can support the interested audience on practicing Turkish NLP. The advantages of our linguistic resources are three-fold: they are freely available, they are first of their kind, and they are easy to use in a broad range of implementations. Along with a thorough description of the resource creation process, we also explain the position of our resources in the Turkish NLP world.",
}
```

