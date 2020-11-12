### Hey 👋, I'm [Zeek Ling](https://www.zeekling.cn)! 
![Github Stats](https://github-readme-stats.vercel.app/api?username=zeekling&show_icons=true) 
### 我在[小令童鞋](https://www.zeekling.cn)的近期动态

⭐️ Star [个人主页](https://github.com/zeekling/zeekling) 后会自动更新，最近更新时间：`2020-11-13 00:00:35`

<p align="center"><img alt="ZEEKLING" src="https://img.zeekling.cn/images/2020/02/23/logo.th.png"></p><h2 align="center">ZEEKLING
</h2>

<h4 align="center">Stay simple, stay naive.</h4>
<p align="center"><a title="ZEEKLING" target="_blank" href="https://github.com/zeekling/zeekling"><img src="https://img.shields.io/github/last-commit/zeekling/zeekling.svg?style=flat-square&color=FF9900"></a>
<a title="GitHub repo size in bytes" target="_blank" href="https://github.com/zeekling/zeekling"><img src="https://img.shields.io/github/repo-size/zeekling/zeekling.svg?style=flat-square"></a>
<a title="Hits" target="_blank" href="https://github.com/zeekling/hits"><img src="https://hits.b3log.org/zeekling/zeekling.svg"></a></p>

### 最新

* 📝 [【Redis源码】mget命令](https://www.zeekling.cn/articles/2020/11/11/1605109223498.html) 
    > <p>通过get命令只能获取单个key的值，如果想获取多个key的值，可以通过mget命令来实现。mget返回所有指定key的值。</p>
    > <p><strong>格式：</strong></p>
    > <pre><code class="language-bash highlight-chroma">mget key <span class="highlight-o">[</span>key …<span class="highlight-o">]</span>
    > </code></pre>
* 📝 [Redis 学习知识点总结](https://www.zeekling.cn/articles/2020/09/01/1598892381872.html) 
    > <p>本文的主要目的就是对之前看过的Redis相关的文章做一个简单的提纲，方便以后汇总复习。</p>
    > <p>目前主要包含两方面：基础知识和源码解读。</p>
* 📝 [【Redis源码】strlen命令](https://www.zeekling.cn/articles/2020/11/11/1605098851638.html) 
    > <p>strlen命令从数据库中获取到value，返回value字符串的长度。</p>
    > <p><strong>格式：</strong></p>
    > <pre><code class="language-bash highlight-chroma">strlen key
    > </code></pre>
* 📝 [人生第一次（上学）](https://www.zeekling.cn/articles/2020/11/08/1604808358057.html) 
    > <p>《人生第一次》是央视网联合上海广播电视台纪录片中心、腾讯视频出品的12集系列人文纪录片，本片撷取的人生断面，时间上贯穿于出生、上学、成家、立业、养老等人生中不同的阶段，空间上分布于医院、学校、军队、房产中介、村庄、工厂、老年大学等不同人生场景。本片旨在通过蹲守拍摄，观察不同人群在人生重要节点的“第一次”，以点带面、见微知著，表达中国人的情感、面临的挑战、坚持的价值观，折射中国当下的时代精神。</p>
* 📝 [【Redis源码】setnx、setex、psetex命令](https://www.zeekling.cn/articles/2020/11/08/1604821520818.html) 
    > <p>在了解了set的原理之后，setnx、setex、psetex命令的原理我们也应该大致了解了，这3个命令也是先调用了tryObjectEncoding将值优化，再调用setGenericCommand将key-value设置到数据库，只不过这3个命令不需要解析额外参数。</p>
* 📝 [【Redis源码】Redis Set命令详解](https://www.zeekling.cn/articles/2020/11/08/1604816679827.html) 
    > <p>set命令用于将key-value设置到数据库。如果key已经设置，则set会用新值覆盖旧值，不管原value是何种类型，如果在设置时不指定EX或PX参数，set命令会清除原有超时时间。</p>
* 📝 [vscode 查看Redis源码](https://www.zeekling.cn/articles/2020/10/20/1603198382711.html) 
    > <p>最近在学习Redis源码，主要是目前负责华为产品<a href="https://support.huawei.com/enterprise/zh/cloud-computing/fusioninsight-hd-pid-21110924" target="_blank">FusionInsight HD</a>中Redis组件的相关事务，不得不学习Redis源码。本文主要讲述的是怎么通过vscode查看Redis的源码(Linux平台下面).</p>
* 📝 [当Redis数据磁盘坏掉之后会发生什么](https://www.zeekling.cn/articles/2020/11/09/1604937462651.html) 
    > <p>当Redis cluster集群数据所在磁盘的RAID卡坏掉了之后会发生什么？集群会不会进行故障迁移，以及怎么快速恢复。</p>




