## System Design In Practice

Get ready for System Design Interviews using practical examples from Twitter, Instagram, TikTok, etc.

### Table of contents

#### SWE (Software Engineering)
- [News Feed](#news-feed)
- [GEO Base](#geo-base)
- [IM](#im)
- [Live](#live)
- [Video](#video)
- [File Sync](#file-sync)
- [Search](#search)
- [Ranking](#ranking)
- [Trading](#trading)
- [Cooperative editing](#cooperative-editing)
- [Booking](#booking)
- [Shopping](#shopping)
- [CPU-bound](#cpu-bound)
- [Infrastructure](#infrastructure)

#### ML/AI Engineer (Machine Learning / AI Engineering)
- [Recommendation Systems](#recommendation-systems)
- [Search & Ranking](#search--ranking)
- [Advertising system](#advertising-system)
- [Computer Vision Systems](#computer-vision-systems)
- [Model Versioning & MLOps](#model-versioning--mlops)
- [ML Data Infrastructure](#ml-data-infrastructure)
- [LLM related](#llm-related)

---

## SWE (Software Engineering)

### News Feed

*Examples: Twitter, Instagram, TikTok, Pinterest*

#### Basic
- [Video: How to build a social media photo sharing app on Google Cloud](https://www.youtube.com/watch?v=BX9BIHRfab0) (Google)

#### Advanced
- [Real-Time Delivery Architecture at Twitter](https://www.youtube.com/watch?v=J5auCY4ajK8) (Twitter)
- [How We Learned to Stop Worrying and Love Fan-In at Twitter](https://www.youtube.com/watch?v=WEgCjwyXvwc) (Twitter)
- [Sharding & IDs at Instagram](https://instagram-engineering.com/sharding-ids-at-instagram-1cf5a71e5a5c) (Instagram)
- [Video Upload Latency Improvements at Instagram](https://instagram-engineering.com/video-upload-latency-improvements-at-instagram-bcf4b4c5520a) (Instagram)
- [Improving Distributed Caching Performance and Efficiency at Pinterest](https://medium.com/pinterest-engineering/improving-distributed-caching-performance-and-efficiency-at-pinterest-92484b5fe39b) (Pinterest)

### GEO Base

*Examples: Uber, Uber Eats, Grab, Lyft*

#### Basic
- [Video: How does Uber scale to millions of concurrent requests?](https://www.youtube.com/watch?v=DY2AR8Wzg3Y) (Google)

#### Advanced
- [Uber's Fulfillment Platform: Ground-up Re-architecture to Accelerate Uber's Go/Get Strategy](https://www.uber.com/blog/fulfillment-platform-rearchitecture/) (Uber)
- [Building Uber's Fulfillment Platform for Planet-Scale using Google Cloud Spanner](https://www.uber.com/blog/building-ubers-fulfillment-platform/) (Uber)
- [Deduping and Storing Images at Uber Eats](https://www.uber.com/blog/deduping-and-storing-images-at-uber-eats/) (Uber)
- [Uber's Next Gen Push Platform on gRPC](https://www.uber.com/blog/ubers-next-gen-push-platform-on-grpc/) (Uber)
- [S2 Geometry](https://s2geometry.io/) (Google)

### IM

*Examples: WhatsApp, Facebook Messenger, WeChat, LINE*

#### Basic
- [Understanding WhatsApp's Architecture & System Design](https://www.cometchat.com/blog/whatsapps-architecture-and-system-design) (CometChat)
- [Understanding the Architecture & System Design of a Chat Application](https://www.cometchat.com/blog/chat-application-architecture-and-system-design) (CometChat)

#### Advanced
- [How WhatsApp enables multi-device capability](https://engineering.fb.com/2021/07/14/security/whatsapp-multi-device/) (Meta)
- [How to build large-scale end-to-end encrypted group video calls](https://www.signal.org/blog/how-to-build-encrypted-group-calls/) (Signal)
- [WhatsApp Encryption Overview](https://scontent-nrt1-1.xx.fbcdn.net/v/t39.8562-6/271639644_1080641699441889_2201546141855802968_n.pdf?_nc_cat=108&ccb=1-7&_nc_sid=ad8a9d&_nc_ohc=_wqkNR0nHrQAX8Tva7i&_nc_ht=scontent-nrt1-1.xx&oh=00_AT83SbnIkSMWekcqRci59O5LarlbIqTNHiRLrbRnMTVNiA&oe=632FA9BD) (Meta)

### Live

*Examples: Facebook Live, Twitch, Zoom, Google Meets*

#### Basic
*(none)*

#### Advanced
- [Scaling Facebook Live Videos to a Billion Users](https://www.youtube.com/watch?v=IO4teCbHvZw) (Meta)
- [Ingesting Live Video Streams at Global Scale](https://blog.twitch.tv/en/2022/04/26/ingesting-live-video-streams-at-global-scale/) (Twitch)

### Video

*Examples: YouTube, Netflix, Disney Plus, HBO Max*

#### Basic
*(none)*

#### Advanced
- [Scaling Time Series Data Storage — Part I](https://netflixtechblog.com/scaling-time-series-data-storage-part-i-ec2b6d44ba39) (Netflix)
- [Netflix Video Quality at Scale with Cosmos Microservices](https://netflixtechblog.com/netflix-video-quality-at-scale-with-cosmos-microservices-552be631c113) (Netflix)
- [Rethinking Netflix's Edge Load Balancing](https://netflixtechblog.com/netflix-edge-load-balancing-695308b5548c) (Netflix)
- [Timestone: Netflix's High-Throughput, Low-Latency Priority Queueing System with Built-in Support for Non-Parallelizable Workloads](https://netflixtechblog.com/timestone-netflixs-high-throughput-low-latency-priority-queueing-system-with-built-in-support-1abf249ba95f) (Netflix)
- [Building Netflix's Distributed Tracing Infrastructure](https://netflixtechblog.com/building-netflixs-distributed-tracing-infrastructure-bb856c319304) (Netflix)

### File Sync

*Examples: Google Drive, Dropbox, Sync.Com, iDrive*

#### Basic
*(none)*

#### Advanced
- [Rewriting the heart of our sync engine](https://dropbox.tech/infrastructure/rewriting-the-heart-of-our-sync-engine) (Dropbox)
- [Boosting Dropbox upload speed and improving Windows' TCP stack - Dropbox](https://dropbox.tech/infrastructure/boosting-dropbox-upload-speed) (Dropbox)

### Search

*Examples: Google Search, Bing, Airbnb Search, Twitter Search*

#### Basic
- [How Google Search Works (in 5 minutes)](https://www.youtube.com/watch?v=0eKVizvYSUQ) (Google)
- [In-depth guide to how Google Search works](https://developers.google.com/search/docs/fundamentals/how-search-works) (Google)
- [How Google organizes information to find what you're looking for](https://blog.google/products/search/how-google-organizes-information/) (Google)

#### Advanced
- [Manas Realtime — Enabling changes to be searchable in a blink of an eye](https://medium.com/pinterest-engineering/manas-realtime-enabling-changes-to-be-searchable-in-a-blink-of-an-eye-36acc3506843) (Pinterest)
- [Under the Hood: Indexing and ranking in Graph Search](https://engineering.fb.com/2013/03/14/core-infra/under-the-hood-indexing-and-ranking-in-graph-search/) (Meta)
- [Under the Hood: Building out the infrastructure for Graph Search](https://engineering.fb.com/2013/03/06/core-data/under-the-hood-building-out-the-infrastructure-for-graph-search/) (Meta)
- [Omnisearch index formats](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2016/omnisearch-index-formats) (Twitter)
- [Reducing search indexing latency to one second](https://blog.x.com/engineering/en_us/topics/infrastructure/2020/reducing-search-indexing-latency-to-one-second) (X)
- [Nebula as a Storage Platform to Build Airbnb's Search Backends](https://medium.com/airbnb-engineering/nebula-as-a-storage-platform-to-build-airbnbs-search-backends-ecc577b05f06) (Airbnb)

### Ranking

*Examples: Twitter Top Hashtags, Spotify Top K Music*

#### Basic
- [Fast and Reliable Ranking in Datastore](https://cloud.google.com/datastore/docs/articles/fast-and-reliable-ranking-in-datastore) (Google)

#### Advanced
- [Trending on Instagram](https://instagram-engineering.com/trending-on-instagram-b749450e6d93) (Instagram)
- [How We Built Infrastructure to Run User Forecasts at Spotify](https://engineering.atspotify.com/2022/06/how-we-built-infrastructure-to-run-user-forecasts-at-spotify/) (Spotify)
- [Changing the Wheels on a Moving Bus — Spotify's Event Delivery Migration](https://engineering.atspotify.com/2021/10/changing-the-wheels-on-a-moving-bus-spotify-event-delivery-migration/) (Spotify)
- [Spotify's Event Delivery – The Road to the Cloud (Part II)](https://engineering.atspotify.com/2016/03/spotifys-event-delivery-the-road-to-the-cloud-part-ii/) (Spotify)

### Trading

*Examples: Robinhood, Webull, TradeStation*

#### Basic
- [Video: How to build a modern banking app with Google Cloud](https://www.youtube.com/watch?v=0EBCMNoYvfc) (Google)

#### Advanced
- [Building a Real-Time Trading Platform with Redis](https://redis.com/blog/real-time-trading-platform-with-redis-enterprise/) (Redis)

### Cooperative editing

*Examples: Google Docs, Microsoft Office Online, Quip*

#### Basic
- [What's different about the new Google Docs: Making collaboration fast](https://drive.googleblog.com/2010/09/whats-different-about-new-google-docs.html) (Google)
- [What's different about the new Google Docs: Conflict resolution](https://drive.googleblog.com/2010/09/whats-different-about-new-google-docs_22.html) (Google)

#### Advanced
*(none)*

### Booking

*Examples: Google Calendar, Ticketmaster, StubHub*

#### Basic
*(none)*

#### Advanced
*(none)*

### Shopping

*Examples: Amazon, eBay, Etsy, AliExpress*

#### Basic
- [Video: How to build digital e-commerce platform on Google Cloud](https://www.youtube.com/watch?v=aOaR4GAcKYU) (Google)

#### Advanced
- [Avoiding Double Payments in a Distributed Payments System](https://medium.com/airbnb-engineering/avoiding-double-payments-in-a-distributed-payments-system-2981f6b070bb) (Airbnb)
- [Rebuilding Payment Orchestration at Airbnb](https://medium.com/airbnb-engineering/rebuilding-payment-orchestration-at-airbnb-341d194a781b) (Airbnb)
- [Scaling Airbnb's Payment Platform](https://medium.com/airbnb-engineering/scaling-airbnbs-payment-platform-43ebfc99b324) (Airbnb)
- [Cross shard transactions at 10 million requests per second](https://dropbox.tech/infrastructure/cross-shard-transactions-at-10-million-requests-per-second) (Dropbox)

### CPU-bound

*Examples: LeetCode, Video Editor*

#### Basic
- [Video: How to build a three-tier serverless Cloud Run app](https://www.youtube.com/watch?v=4URpj0h3mv8) (Google)

#### Advanced
*(none)*

### Infrastructure

*Examples: Distributed Cache, Rate Limit, Key Value Store, Web Crawl, Object Storage, Logging, Monitoring*

#### Basic
- [Video: How to build a reliable, continuous delivery pipeline for GKE](https://www.youtube.com/watch?v=0BRZFVnSmLc) (Google)

#### Advanced
- [Building an Effective Test Pipeline in a Service Oriented World](https://medium.com/airbnb-engineering/building-an-effective-test-pipeline-in-a-service-oriented-world-6968c513c6bd) (Airbnb)
- [Dynein: Building an Open-source Distributed Delayed Job Queueing System](https://medium.com/airbnb-engineering/dynein-building-a-distributed-delayed-job-queueing-system-93ab10f05f99) (Airbnb)
- [Lessons learned in incident management](https://dropbox.tech/infrastructure/lessons-learned-in-incident-management) (Dropbox)
- [How we designed Dropbox ATF: an async task framework](https://dropbox.tech/infrastructure/asynchronous-task-scheduling-at-dropbox) (Dropbox)
- [Dropbox traffic infrastructure: Edge network](https://dropbox.tech/infrastructure/dropbox-traffic-infrastructure-edge-network) (Dropbox)
- [#ExpandTheEdge: Making Twitter Faster](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2019/expand-the-edge) (Twitter)
- [Building DistributedLog: High-performance replicated log service](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2015/building-distributedlog-twitter-s-high-performance-replicated-log-servic) (Twitter)
- [Infrastructure Behind Twitter: Scale](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2017/the-infrastructure-behind-twitter-scale) (Twitter)
- [ZippyDB: A Distributed Key-Value Store](https://engineering.fb.com/2021/08/06/core-infra/zippydb/) (Meta)
- [Async: A Distributed System for Handling Billions of Asynchronous Requests](https://engineering.fb.com/2020/08/17/production-engineering/async/) (Meta)
- [FOQS: Scaling a Distributed Priority Queue](https://engineering.fb.com/2021/02/22/production-engineering/foqs-scaling-a-distributed-priority-queue) (Meta)
- [MetricsDB: TimeSeries Database for storing metrics at Twitter](https://blog.x.com/engineering/en_us/topics/infrastructure/2019/metricsdb) (X)
- [PinCompute: A Kubernetes Backed General Purpose Compute Platform for Pinterest](https://medium.com/pinterest-engineering/pincompute-a-kubernetes-backed-general-purpose-compute-platform-for-pinterest-8ad408df2d6f) (Pinterest)
- [Building a Next-Generation Key-Value Store at Airbnb](https://medium.com/airbnb-engineering/building-a-next-generation-key-value-store-at-airbnb-0de8465ba354) (Airbnb)

---

## ML/AI Engineer (Machine Learning / AI Engineering)

### Recommendation Systems

*Examples: Netflix, YouTube, Amazon, Spotify, TikTok, Instagram, Pinterest*

#### Basic
- [On the value of diversified recommendations](https://engineering.fb.com/2020/12/17/ml-applications/diversified-recommendations/) (Meta)
- [How Instagram suggests new content](https://engineering.fb.com/2020/12/10/web/how-instagram-suggests-new-content/) (Meta)

#### Advanced
- [Journey to 1000 Models: Scaling Instagram's Recommendation System](https://engineering.fb.com/2025/05/21/production-engineering/journey-to-1000-models-scaling-instagrams-recommendation-system) (Meta)
- [Twitter's Recommendation Algorithm](https://blog.x.com/engineering/en_us/topics/open-source/2023/twitter-recommendation-algorithm) (X)
- [Modernizing Home Feed Pre-Ranking Stage](https://medium.com/pinterest-engineering/modernizing-home-feed-pre-ranking-stage-e636c9cdc36b) (Pinterest)
- [Building Airbnb Categories with ML and Human-in-the-Loop](https://airbnb.tech/ai-ml/building-airbnb-categories-with-ml-and-human-in-the-loop/) (Airbnb)

### Search & Ranking

*Examples: Google Search, Bing, Etsy Search, Airbnb Search, Twitter Search, LinkedIn Search*

#### Basic
- [How machine learning powers Facebook's News Feed ranking algorithm](https://engineering.fb.com/2021/01/26/core-infra/news-feed-ranking/) (Meta)

#### Advanced
- [Using Deep Learning at Scale in Twitter's Timelines](https://blog.x.com/engineering/en_us/topics/insights/2017/using-deep-learning-at-scale-in-twitters-timelines) (X)
- [Embedding-Based Retrieval for Airbnb Search](https://medium.com/airbnb-engineering/embedding-based-retrieval-for-airbnb-search-aabebfc85839) (Airbnb)
- [Transforming Location Retrieval at Airbnb: A Journey from Heuristics to Reinforcement Learning](https://medium.com/airbnb-engineering/transforming-location-retrieval-at-airbnb-a-journey-from-heuristics-to-reinforcement-learning-d33ffc4ddb8f) (Airbnb)
- [Machine Learning-Powered Search Ranking of Airbnb Experiences](https://medium.com/airbnb-engineering/machine-learning-powered-search-ranking-of-airbnb-experiences-110b4b1a0789) (Airbnb)
- [Beyond A/B Test: Speeding up Airbnb Search Ranking Experimentation through Interleaving](https://airbnb.tech/data/beyond-a-b-test-speeding-up-airbnb-search-ranking-experimentation-through-interleaving/) (Airbnb)

### Advertising system

*Examples: Google Ads, Facebook Ads, Amazon Advertising, LinkedIn Ads*

#### Basic
*(none)*

#### Advanced
- [A SplitNet architecture for ad candidate ranking](https://blog.x.com/engineering/en_us/topics/infrastructure/2019/splitnet-architecture-for-ad-candidate-ranking) (X)

### Computer Vision Systems

*Examples: Image Classification, Object Detection, Face Recognition, Image Search (Google Lens, Pinterest Lens), Video Analysis*

#### Basic
*(none)*

#### Advanced
*(none)*

### Model Versioning & MLOps

*Examples: Model Registry (MLflow, Weights & Biases), Model Deployment, CI/CD for ML, Model Lifecycle Management*

#### Basic
*(none)*

#### Advanced
*(none)*

### ML Data Infrastructure

*Examples: Data Lake for ML, Feature Engineering Platform, Data Labeling Infrastructure, Data Validation Systems*

#### Basic
*(none)*

#### Advanced
*(none)*

### LLM related

*Examples: Large Language Models, Generative AI, LLM Infrastructure*

#### Basic
*(none)*

#### Advanced
- [Meta's Generative Ads Model (GEM): The Central Brain Accelerating Ads Recommendation AI Innovation](https://engineering.fb.com/2025/11/10/ml-applications/metas-generative-ads-model-gem-the-central-brain-accelerating-ads-recommendation-ai-innovation/) (Meta)
