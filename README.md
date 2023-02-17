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
```

The dataset includes 1,052 products of 262 distinct brands with 244K customer reviews. During the compilation, we eliminated reviews containing person names such as customer's name and influencer names.
This work is supported by Google Developer Experts Program. Part of Duygu 2023 Fall-Winter collection, "Turkish NLP with Duygu"/ "Duygu'yla Türkçe NLP". All rights reserved.
