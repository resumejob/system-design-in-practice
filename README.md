## System design in practice

Learn how to do system design with practical examples from Twitter, Instagram, Pinterest etc.

| Category    |  Resources | Tutorial |
| ---------   | -------   | -------  |
| <h4>News Feed</h4>  <ul><li>Twitter</li><li>Instagram</li><li>TikTok</li><li>Pinterest</li></ul>   |  <ul><li>[Real-Time Delivery Architecture at Twitter](https://www.youtube.com/watch?v=J5auCY4ajK8)</li><li>[How We Learned to Stop Worrying and Love Fan-In at Twitter](https://www.youtube.com/watch?v=WEgCjwyXvwc)</li><li>[Sharding & IDs at Instagram](https://instagram-engineering.com/sharding-ids-at-instagram-1cf5a71e5a5c)</li><li>[Video Upload Latency Improvements at Instagram](https://instagram-engineering.com/video-upload-latency-improvements-at-instagram-bcf4b4c5520a)</li><li>[Improving Distributed Caching Performance and Efficiency at Pinterest](https://medium.com/pinterest-engineering/improving-distributed-caching-performance-and-efficiency-at-pinterest-92484b5fe39b)</li></ul>        | <ul><li>[Video: How to build a social media photo sharing app on Google Cloud](https://www.youtube.com/watch?v=BX9BIHRfab0)</li></ul> |
| <h4>GEO Base</h4>  <ul><li>Uber</li><li>Uber Eats</li><li>Grab</li><li>Lyft</li></ul> | <ul><li>[Uber’s Fulfillment Platform: Ground-up Re-architecture to Accelerate Uber’s Go/Get Strategy](https://www.uber.com/blog/fulfillment-platform-rearchitecture/)</li><li>[Building Uber’s Fulfillment Platform for Planet-Scale using Google Cloud Spanner](https://www.uber.com/blog/building-ubers-fulfillment-platform/)</li><li>[Deduping and Storing Images at Uber Eats](https://www.uber.com/blog/deduping-and-storing-images-at-uber-eats/)</li><li>[Uber’s Next Gen Push Platform on gRPC](https://www.uber.com/blog/ubers-next-gen-push-platform-on-grpc/)</li><li>[S2 Geometry](https://s2geometry.io/)</li></ul>| <ul><li>[Video: How does Uber scale to millions of concurrent requests?](https://www.youtube.com/watch?v=DY2AR8Wzg3Y)</li></ul> |
| <h4>IM</h4> <ul><li>WhatsApp</li><li>Facebook Messenger</li><li>WeChat</li><li>LINE</li></ul>   | <ul><li>[Understanding WhatsApp's Architecture & System Design](https://www.cometchat.com/blog/whatsapps-architecture-and-system-design)</li><li>[Understanding the Architecture & System Design of a Chat Application](https://www.cometchat.com/blog/chat-application-architecture-and-system-design)</li><li>[How WhatsApp enables multi-device capability](https://engineering.fb.com/2021/07/14/security/whatsapp-multi-device/)</li><li>[How to build large-scale end-to-end encrypted group video calls](https://www.signal.org/blog/how-to-build-encrypted-group-calls/)</li><li>[* WhatsApp Encryption Overview](https://scontent-nrt1-1.xx.fbcdn.net/v/t39.8562-6/271639644_1080641699441889_2201546141855802968_n.pdf?_nc_cat=108&ccb=1-7&_nc_sid=ad8a9d&_nc_ohc=_wqkNR0nHrQAX8Tva7i&_nc_ht=scontent-nrt1-1.xx&oh=00_AT83SbnIkSMWekcqRci59O5LarlbIqTNHiRLrbRnMTVNiA&oe=632FA9BD)</li></ul>    |
| <h4>Live</h4> <ul><li>Facebook Live</li><li>Twitch</li><li>Zoom</li><li>Google Meets</li></ul>   | <ul><li>[Scaling Facebook Live Videos to a Billion Users](https://www.youtube.com/watch?v=IO4teCbHvZw)</li><li>[Ingesting Live Video Streams at Global Scale](https://blog.twitch.tv/en/2022/04/26/ingesting-live-video-streams-at-global-scale/)</li></ul>    |
| <h4>Video</h4>  <ul><li>YouTube</li><li>Netflix</li><li>Disney Plus</li><li>HBO Max</li></ul>   | <ul><li>[Scaling Time Series Data Storage — Part I](https://netflixtechblog.com/scaling-time-series-data-storage-part-i-ec2b6d44ba39)</li><li>[Netflix Video Quality at Scale with Cosmos Microservices](https://netflixtechblog.com/netflix-video-quality-at-scale-with-cosmos-microservices-552be631c113)</li><li>[Rethinking Netflix’s Edge Load Balancing](https://netflixtechblog.com/netflix-edge-load-balancing-695308b5548c)</li><li>[Timestone: Netflix’s High-Throughput, Low-Latency Priority Queueing System with Built-in Support for Non-Parallelizable Workloads](https://netflixtechblog.com/timestone-netflixs-high-throughput-low-latency-priority-queueing-system-with-built-in-support-1abf249ba95f)</li><li>[Building Netflix’s Distributed Tracing Infrastructure](https://netflixtechblog.com/building-netflixs-distributed-tracing-infrastructure-bb856c319304)</li></ul> |
| <h4>File Sync</h4> <ul><li>Google Drive</li><li>Dropbox</li><li>Sync.Com</li><li>iDrive</li></ul>   | <ul><li>[Rewriting the heart of our sync engine](https://dropbox.tech/infrastructure/rewriting-the-heart-of-our-sync-engine)</li><li>[Boosting Dropbox upload speed and improving Windows’ TCP stack - Dropbox](https://dropbox.tech/infrastructure/boosting-dropbox-upload-speed)</li></ul> |
| <h4>Search</h4>  <ul><li>Google Search</li><li>Bing</li><li>Airbnb Search</li><li>Twitter Search</li></ul> | <ul><li>[How Google Search Works (in 5 minutes)](https://www.youtube.com/watch?v=0eKVizvYSUQ)</li><li>[In-depth guide to how Google Search works](https://developers.google.com/search/docs/fundamentals/how-search-works)</li><li>[How Google organizes information to find what you’re looking for](https://blog.google/products/search/how-google-organizes-information/)</li><li>[Manas Realtime — Enabling changes to be searchable in a blink of an eye](https://medium.com/pinterest-engineering/manas-realtime-enabling-changes-to-be-searchable-in-a-blink-of-an-eye-36acc3506843)</li><li>[Under the Hood: Indexing and ranking in Graph Search](https://engineering.fb.com/2013/03/14/core-data/under-the-hood-indexing-and-ranking-in-graph-search/)</li><li>[Under the Hood: Building out the infrastructure for Graph Search](https://engineering.fb.com/2013/03/06/core-data/under-the-hood-building-out-the-infrastructure-for-graph-search/)</li><li>[Omnisearch index formats](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2016/omnisearch-index-formats)</li></ul>|
| <h4>Ranking</h4> <ul><li>Twitter Top Hashtags</li><li>Spotify Top K Music</li></ul>  | <ul><li>[Trending on Instagram](https://instagram-engineering.com/trending-on-instagram-b749450e6d93)</li><li>[Fast and Reliable Ranking in Datastore](https://cloud.google.com/datastore/docs/articles/fast-and-reliable-ranking-in-datastore)</li><li>[How We Built Infrastructure to Run User Forecasts at Spotify](https://engineering.atspotify.com/2022/06/how-we-built-infrastructure-to-run-user-forecasts-at-spotify/)</li><li>[Changing the Wheels on a Moving Bus — Spotify’s Event Delivery Migration](https://engineering.atspotify.com/2021/10/changing-the-wheels-on-a-moving-bus-spotify-event-delivery-migration/)</li><li>[Spotify’s Event Delivery – The Road to the Cloud (Part II)](https://engineering.atspotify.com/2016/03/spotifys-event-delivery-the-road-to-the-cloud-part-ii/)</li></ul> | <ul></ul> |
| <h4>Trading</h4>  <ul><li>Robinhood</li><li>Webull</li><li>TradeStation</li></ul>   | | <ul><li>[Video: How to build a modern banking app with Google Cloud](https://www.youtube.com/watch?v=0EBCMNoYvfc)</li><li>[Building a Real-Time Trading Platform with Redis](https://redis.com/blog/real-time-trading-platform-with-redis-enterprise/)</li></ul> |
| <h4>Cooperative editing</h4> <ul><li>Google Docs</li><li>Microsoft Office Online</li><li>Quip</li></ul>   | <ul><li>[What’s different about the new Google Docs: Making collaboration fast](https://drive.googleblog.com/2010/09/whats-different-about-new-google-docs.html)</li><li>[What’s different about the new Google Docs: Conflict resolution](https://drive.googleblog.com/2010/09/whats-different-about-new-google-docs_22.html)</li></ul> |
| <h4>Booking</h4> <ul><li>Google Calendar</li><li>Ticketmaster</li><li>StubHub</li></ul>  | |
| <h4>Shopping</h4> <ul><li>Amazon</li><li>eBay</li><li>Etsy</li><li>AliExpress</li></ul> | <ul><li>[Video: How to build digital e-commerce platform on Google Cloud](https://www.youtube.com/watch?v=aOaR4GAcKYU)</li><li>[Avoiding Double Payments in a Distributed Payments System](https://medium.com/airbnb-engineering/avoiding-double-payments-in-a-distributed-payments-system-2981f6b070bb)</li><li>[Rebuilding Payment Orchestration at Airbnb](https://medium.com/airbnb-engineering/rebuilding-payment-orchestration-at-airbnb-341d194a781b)</li><li>[Scaling Airbnb’s Payment Platform](https://medium.com/airbnb-engineering/scaling-airbnbs-payment-platform-43ebfc99b324)</li><li>[Cross shard transactions at 10 million requests per second](https://dropbox.tech/infrastructure/cross-shard-transactions-at-10-million-requests-per-second)</li></ul>  | <ul><li>[Video: How to build digital e-commerce platform on Google Cloud](https://www.youtube.com/watch?v=aOaR4GAcKYU)</li></ul> |
| <h4>CPU-bound</h4> <ul><li>LeetCode</li><li>Video Editor</li></ul>  | | <ul><li>[Video: How to build a three-tier serverless Cloud Run app](https://www.youtube.com/watch?v=4URpj0h3mv8)</li></ul> |
| <h4>Infrastructure</h4> <ul><li>Key Value Store</li><li>Web Crawl</li><li>Object Storage</li><li>Logging</li><li>Monitoring</li></ul> | <ul><li>[Building an Effective Test Pipeline in a Service Oriented World](https://medium.com/airbnb-engineering/building-an-effective-test-pipeline-in-a-service-oriented-world-6968c513c6bd)</li><li>[Dynein: Building an Open-source Distributed Delayed Job Queueing System](https://medium.com/airbnb-engineering/dynein-building-a-distributed-delayed-job-queueing-system-93ab10f05f99)</li><li>[Lessons learned in incident management](https://dropbox.tech/infrastructure/lessons-learned-in-incident-management)</li><li>[How we designed Dropbox ATF: an async task framework](https://dropbox.tech/infrastructure/asynchronous-task-scheduling-at-dropbox)</li><li>[Dropbox traffic infrastructure: Edge network](https://dropbox.tech/infrastructure/dropbox-traffic-infrastructure-edge-network)</li><li>[#ExpandTheEdge: Making Twitter Faster](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2019/expand-the-edge)</li><li>[Building DistributedLog: High-performance replicated log service](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2015/building-distributedlog-twitter-s-high-performance-replicated-log-servic)</li><li>[Infrastructure Behind Twitter: Scale](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2017/the-infrastructure-behind-twitter-scale)</li></ul>  | <ul><li>[Video: How to build a reliable, continuous delivery pipeline for GKE](https://www.youtube.com/watch?v=0BRZFVnSmLc)</li></ul> |
