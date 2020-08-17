### Hey 👋, I'm [Zeek Ling](https://www.zeekling.cn)! 
![Github Stats](https://github-readme-stats.vercel.app/api?username=zeekling&show_icons=true) 
### 我在[小令童鞋](https://www.zeekling.cn)的近期动态

⭐️ Star [个人主页](https://github.com/zeekling/zeekling) 后会自动更新，最近更新时间：`2020-08-18 00:00:16`

<p align="center"><img alt="小令童鞋" src="https://img.zeekling.cn/images/2020/02/23/logo.th.png"></p><h2 align="center">小令童鞋
</h2>

<h4 align="center">梅干菜你个小酥饼哦。</h4>
<p align="center"><a title="小令童鞋" target="_blank" href="https://github.com/zeekling/zeekling"><img src="https://img.shields.io/github/last-commit/zeekling/zeekling.svg?style=flat-square&color=FF9900"></a>
<a title="GitHub repo size in bytes" target="_blank" href="https://github.com/zeekling/zeekling"><img src="https://img.shields.io/github/repo-size/zeekling/zeekling.svg?style=flat-square"></a>
<a title="Hits" target="_blank" href="https://github.com/zeekling/hits"><img src="https://hits.b3log.org/zeekling/zeekling.svg"></a></p>

### 最新

* 📝 [个人网站禁止复制站点内容](https://www.zeekling.cn/articles/2020/08/17/1597593928362.html) 
    > <p>一般个人网站都不喜欢别人复制自己的东西，于是与我就研究了下怎么禁用网站的复制。</p>
* 📝 [About Me](https://www.zeekling.cn/aboutMe.html) 
    > <p>本站主要是讲述一个自闭的二逼青年如何自救的一个过程，是一个消费大把大把青春的地方。</p>
* 📝 [Data Source 介绍](https://www.zeekling.cn/articles/2020/05/03/1588494729955.html) 
    > <p>Data Sources 是什么呢？就字面意思其实就可以知道：数据来源。<br>
    > Flink 做为一款流式计算框架，它可用来做批处理，即处理静态的数据集、历史的数据集；也可以用来做流处理，即实时的处理些实时数据流，实时的产生数据流结果，只要数据源源不断的过来，Flink 就能够一直计算下去，这个 Data Sources 就是数据的来源地。</p>
* 📝 [Data Sink 介绍](https://www.zeekling.cn/articles/2020/05/04/1588666906660.html) 
    > <p>Source 就是数据的来源，中间的 Compute 其实就是 Flink 干的事情，可以做一系列的操作，操作完后就把计算后的数据结果 Sink 到某个地方。（可以是 MySQL、ElasticSearch、Kafka、Cassandra 等）。这里我说下自己目前做告警这块就是把 Compute 计算后的结果 Sink 直接告警出来了（发送告警消息到钉钉群、邮件、短信等），这个 sink 的意思也不一定非得说成要把数据存储到某个地方去。其实官网用的 Connector 来形容要去的地方更合适，这个 Connector 可以有 MySQL、ElasticSearch、Kafka、Cassandra RabbitMQ 等。</p>
* 📝 [如何自定义 Data Source ](https://www.zeekling.cn/articles/2020/05/04/1588559095224.html) 
    > <p>在 <a href="https://www.zeekling.cn/articles/2020/05/03/1588494729955.html">Data Source 介绍</a> 文章中，我给大家介绍了 Flink Data Source 以及简短的介绍了一下自定义 Data Source，这篇文章更详细的介绍下，并写一个 demo 出来让大家理解。</p>
* 📝 [自定义Data Sink](https://www.zeekling.cn/articles/2020/05/05/1588680092763.html) 
    > <p>上一篇文章介绍了 Flink Data Sink，也介绍了 Flink 自带的 Sink，那么如何自定义自己的 Sink 呢？这篇文章将写一个 demo 教大家将从 Kafka Source 的数据 Sink 到 MySQL 中去。</p>
* 📝 [Flink 写入数据到 Kafka](https://www.zeekling.cn/articles/2020/05/15/1589474545288.html) 
    > <p>通过Flink官网可以看到Flink里面就默认支持了不少sink，比如也支持Kafka sink connector（FlinkKafkaProducer），那么这篇文章我们就来看看如何将数据写入到Kafka。</p>
* 📝 [Kafka API操作实践](https://www.zeekling.cn/articles/2020/05/17/1589721212901.html) 
    > <p>  Kafka的Producer发送消息采用的是<strong>异步发送</strong>的方式。在消息发送的过程中，涉及到了<strong>两个线程——main线程和Sender线程</strong>，以及<strong>一个线程共享变量——RecordAccumulator</strong>。main线程将消息发送给RecordAccumulator，Sender线程不断从RecordAccumulator中拉取消息发送到Kafka broker。<br>
    > Consumer消费数据时的可靠性是很容易保证的，因为数据在Kafka中是持久化的，故不用担心数据丢失问题。<br>
    >   由于consumer在消费过程中可能会出现断电宕机等故障，consumer恢复后，需要从故障前的位置的继续消费，所以consumer需要实时记录自己消费到了哪个offset，以便故障恢复后继续消费。<br>
    >   所以offset的维护是Consumer消费数据是必须考虑的问题。</p>
* 📝 [Kafka深入解析](https://www.zeekling.cn/articles/2020/05/24/1590327441358.html) 
    > <p>Kafka中消息是以topic进行分类的，生产者生产消息，消费者消费消息，都是面向topic的。<br>
    > topic是逻辑上的概念，而partition是物理上的概念，每个partition对应于一个log文件，该log文件中存储的就是producer生产的数据。Producer生产的数据会被不断追加到该log文件末端，且每条数据都有自己的offset。消费者组中的每个消费者，都会实时记录自己消费到了哪个offset，以便出错恢复时，从上次的位置继续消费。</p>
* 📝 [Kafka概述](https://www.zeekling.cn/articles/2020/05/24/1590324636321.html) 
    > <p>Kafka是<strong>一个分布式的基于发布/订阅模式的消息队列</strong>，主要应用于大数据实时处理领域。</p>




