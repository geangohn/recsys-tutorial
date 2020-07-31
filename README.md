# recsys-tutorial

### Tutorials:
- **implicit**: full data & model pipeline, [article](https://www.ethanrosenthal.com/2016/10/19/implicit-mf-part-1/) 
- **LightFM**: [article](https://www.ethanrosenthal.com/2016/11/07/implicit-mf-part-2/) 
- How to build [Item2Vec](https://www.analyticsvidhya.com/blog/2019/07/how-to-build-recommendation-system-word2vec-python/) (or W2V) for item recommendations in retail

### Classic RecSys:
- **OK.ru**: graph based recsys, [article](https://habr.com/ru/company/odnoklassniki/blog/499192/)
- **HH.ru**: classic 2 level model of search at hh.ru, [article](https://habr.com/ru/company/hh/blog/347276/)
- **Okko competition**: classic 2 level model, [article](https://habr.com/ru/post/447376/) 
- **Yandex.Dzen**: fit ALS -> fit Catboost on warm embeddings to predict warm&cold embeddings, [15-25min in video](https://www.youtube.com/watch?v=TaUqh_CeCPc&t=126s)   
- **Avito**: [FAISS](https://habr.com/ru/company/avito/blog/488658/) for fast similar embedding search
- **TikTok**: No use of popularity features! [post](https://newsroom.tiktok.com/en-us/how-tiktok-recommends-videos-for-you/) 
- **Instagram**: Insights on candidate generation [articles](https://instagram-engineering.com/powered-by-ai-instagrams-explore-recommender-system-7ca901d2a882) 

### Search
- How to use W2V and FastText for search: [Query2Vec](https://medium.com/coursera-engineering/query2vec-2f6070083bda) 
- [Similar vectors](https://m.habr.com/ru/company/mailru/blog/338360/) search with Nmslib, FAISS and Annoy
- [ElasticSearch](https://m.habr.com/ru/post/280488/) basics

### Upsell 
- **Avito**: Recommending additional item - [upsell](https://habr.com/ru/company/avito/blog/491942/) with advanced W2V

### Optimization
- **Avito** [Multi-armed bandits](https://m.habr.com/ru/company/avito/blog/417571/?_ga=2.55507619.909483613.1596129867-1023641029.1575324164) for item2item recommendations
- **Pinterest**: Personal [notification volume](https://medium.com/pinterest-engineering/user-state-based-notification-volume-optimization-7764118f73ff) optimization
- **Uber.Eats**: Multi objective optimisation in recsys, [article](https://eng.uber.com/uber-eats-recommending-marketplace/)
- **Avito**: [Multi-objective optimization](https://www.highload.ru/moscow/2018/abstracts/4182) in search
- **VK**: Directly optimizing business metrics

### Cool articles:
- Measure user surprise by [serendipidy](https://towardsdatascience.com/serendipity-accuracys-unpopular-best-friend-in-recommender-systems-ca079b493f3c) metric
