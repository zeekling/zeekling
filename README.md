### Hey 👋, I'm [ZEEKLING](https://www.zeekling.cn)! 
![Github Stats](https://github-readme-stats.vercel.app/api?username=zeekling&show_icons=true) 
### 我在[小令童鞋](https://www.zeekling.cn)的近期动态

⭐️ Star [个人主页](https://github.com/zeekling/zeekling) 后会自动更新
<p align="center"><img alt="ZEEKLING" src="https://img.zeekling.cn/images/2020/02/23/logo.th.png"></p><h2 align="center">ZEEKLING
</h2>

<h4 align="center">Stay simple, stay naive.</h4>
<p align="center"><a title="ZEEKLING" target="_blank" href="https://github.com/zeekling/zeekling"><img src="https://img.shields.io/github/last-commit/zeekling/zeekling.svg?style=flat-square&color=FF9900"></a>
<a title="GitHub repo size in bytes" target="_blank" href="https://github.com/zeekling/zeekling"><img src="https://img.shields.io/github/repo-size/zeekling/zeekling.svg?style=flat-square"></a>
<a title="Hits" target="_blank" href="https://github.com/zeekling/hits"><img src="https://hits.b3log.org/zeekling/zeekling.svg"></a></p>

### 最新

* 📝 [博客从solo迁移bolo](https://www.zeekling.cn/articles/2019/09/07/1587898561235.html) 
    > <p>solo 博客使用了大概有一年的时间，总体感觉上还不错，但是从在一些其他方面的问题，就是和<a href="https://hacpai.com/" target="_blank">黑客派</a> 绑定的太死了，有时候会因为社区的原因导致博客的访问量不准确，以及同一ip访问次数过频繁的时候会导致博客访问不了。</p>
* 📝 [Gogs迁移Gitea](https://www.zeekling.cn/articles/2020/02/23/1582470250287.html) 
    > <p></p><ul>
    > <li>Gogs 更新功能比 Gitea 少很多，虽然不一定用得到。</li>
    > <li>Gitea 更新快，一些 bug 解决的快一点(虽然我没发现什么 bug)</li>
    > <li>可能是因为我 Gogs 用的时间久了，出现了视觉疲劳？</li>
    > </ul>
    > <p></p>
* 📝 [我的书单](https://www.zeekling.cn/book.html) 
    > <p>本页主要用来记录自己已经读过的书或者是正在读的书，里面的这些书都是个人觉得值得花一点时间去读的书，如果感兴趣的话可以交流下。</p>
* 📝 [Linux sogou输入法显示简体，输入之后却是繁体](https://www.zeekling.cn/articles/2021/03/25/1616675636194.html) 
    > <p>最新linux电脑搜狗输入法老是在输入的时候显示中文简体，但是输入到文件，或者浏览器里面就变成了繁体。很是让人头疼，网上搜了下也没人讲这种事。</p>
* 📝 [理解Redis的内存](https://www.zeekling.cn/articles/2020/07/04/1593860561539.html) 
    > <p>Redis 是一种内存数据库，将数据保存在内存中，读写效率要比传统的将数据保存在磁盘上的数据库要快很多。所以，监控 Redis 的内存消耗并了解 Redis 内存模型对高效并长期稳定使用 Redis 至关重要。</p>
* 📝 [Redis 集群详解](https://www.zeekling.cn/articles/2020/07/21/1595342026052.html) 
    > <p>Redis Cluster 即 Redis 集群，是 Redis 官方在 3.0 版本推出的一套分布式存储方案。完全去中心化，由多个节点组成，所有节点彼此互联。Redis 客户端可以直接连接任何一节点获取集群中的键值对，不需要中间代理，如果该节点不存在用户所指定的键值，其内部会自动把客户端重定向到键值所在的节点。</p>
    > <p>Redis 集群是一个网状结构，每个节点都通过 TCP 连接跟其他每个节点连接。在一个有 N 个节点的集群中，每个节点都有 N-1 个流出的 TCP 连接，和 N-1 个流入的连接，这些 TCP 连接会永久保持。</p>
* 📝 [Redis Sentinel哨兵机制](https://www.zeekling.cn/articles/2020/07/21/1595343778998.html) 
    > <p>Redis的哨兵(sentinel) 系统用于管理多个 Redis 服务器,该系统执行以下三个任务:</p>
    > <p><strong>监控(Monitoring):</strong> 哨兵(sentinel) 会不断地检查你的Master和Slave是否运作正常。</p>
    > <p><strong>提醒(Notification):</strong> 当被监控的某个 Redis出现问题时, 哨兵(sentinel) 可以通过 API 向管理员或者其他应用程序发送通知。</p>
    > <p><strong>自动故障迁移(Automatic failover):</strong> 当一个Master不能正常工作时，哨兵(sentinel) 会开始一次自动故障迁移操作,它会将失效Master的其中一个Slave升级为新的Master, 并让失效Master的其他Slave改为复制新的Master; 当客户端试图连接失效的Master时,集群也会向客户端返回新Master的地址,使得集群可以使用Master代替失效Master。</p>
* 📝 [Redis 慢查询分析](https://www.zeekling.cn/articles/2020/07/23/1595493094855.html) 
    > <p>在慢查询的定义中，统计比较慢的时间段指的是<strong>命令执行</strong>这个步骤。没有慢查询，并不表示客户端没有超时问题，有可能网络传输有延迟，也有可能排队的命令比较多。</p>
    > <p>因为Redis中命令执行的排队机制，慢查询会导致其他命令的级联阻塞，所以当客户端出现请求超时的时候，需要检查该时间点是否有慢查询，从而分析出由于慢查询导致的命令级联阻塞。</p>
* 📝 [【Redis源码】setbit命令](https://www.zeekling.cn/articles/2020/11/14/1605354792615.html) 
    > <p>setbit命令对key所存储的字符串值，设置指定偏移量上的比特位。</p>
    > <p><strong>格式：</strong></p>
    > <pre><code class="language-bash highlight-chroma">setbit key offset value
    > </code></pre>
    > <p>返回值： 返回指定偏移量原来存储的位。</p>
* 📝 [【Redis源码】RDB持久化源码实现](https://www.zeekling.cn/articles/2020/11/25/1606235262538.html) 
    > <p>RDB快照有两种触发方式，其一为通过配置参数，例如在配置文件中写入如下配置：</p>
    > <pre><code class="language-cpp highlight-chroma"><span class="highlight-n">save</span> <span class="highlight-mi">60</span> <span class="highlight-mi">1000</span>
    > </code></pre>
    > <p>则在60秒内如果有1000个key发生变化，就会触发一次RDB快照的执行。</p>
    > <p>其二是通过在客户端执行bgsave命令显式触发一次RDB快照的执行。</p>




