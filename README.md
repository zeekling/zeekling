### Hey 👋, I'm [Zeek Ling](https://www.zeekling.cn)! 
![Github Stats](https://github-readme-stats.vercel.app/api?username=zeekling&show_icons=true) 
### 我在[小令童鞋](https://www.zeekling.cn)的近期动态

⭐️ Star [个人主页](https://github.com/zeekling/zeekling) 后会自动更新，最近更新时间：`2020-11-09 12:00:21`

<p align="center"><img alt="ZEEKLING" src="https://img.zeekling.cn/images/2020/02/23/logo.th.png"></p><h2 align="center">ZEEKLING
</h2>

<h4 align="center">Stay simple, stay naive.</h4>
<p align="center"><a title="ZEEKLING" target="_blank" href="https://github.com/zeekling/zeekling"><img src="https://img.shields.io/github/last-commit/zeekling/zeekling.svg?style=flat-square&color=FF9900"></a>
<a title="GitHub repo size in bytes" target="_blank" href="https://github.com/zeekling/zeekling"><img src="https://img.shields.io/github/repo-size/zeekling/zeekling.svg?style=flat-square"></a>
<a title="Hits" target="_blank" href="https://github.com/zeekling/hits"><img src="https://hits.b3log.org/zeekling/zeekling.svg"></a></p>

### 最新

* 📝 [Redis 学习知识点总结](https://www.zeekling.cn/articles/2020/09/01/1598892381872.html) 
    > <p>本文的主要目的就是对之前看过的Redis相关的文章做一个简单的提纲，方便以后汇总复习。</p>
    > <p>目前主要包含两方面：基础知识和源码解读。</p>
* 📝 [【Redis源码】setrange命令](https://www.zeekling.cn/articles/2020/11/08/1604841590957.html) 
    > <p>setrange命令主要用于设置value的部分子串，设置时将值从偏移量offset开始覆盖成value值。如果偏移值大于原值的长度，则偏移量之前的字符串由“\x00”填充。</p>
    > <p>命令格式：</p>
    > <pre><code class="language-bash highlight-chroma">setrange key offset value
    > </code></pre>
* 📝 [【Redis源码】append命令](https://www.zeekling.cn/articles/2020/11/08/1604838367145.html) 
    > <p>数据库已经有了key，它的值为value。当我们发现value值需要追加字符串却又不想直接用set命令覆盖原值时，可以用append命令来实现。</p>
    > <p>命令格式：</p>
    > <pre><code class="language-cpp highlight-chroma"><span class="highlight-n">append</span> <span class="highlight-n">key</span> <span class="highlight-n">value</span>
    > </code></pre>
    > <ul>
    > <li>说明： 将value追加到原值的末尾，如果key不存在，此命令等同<br>
    > 于set key value命令。</li>
    > </ul>
* 📝 [【Redis源码】mset命令](https://www.zeekling.cn/articles/2020/11/08/1604831354258.html) 
    > <p>通过set、setex等命令只能设置单个字符串到数据库，当我们想一次性设置多个字符串时，可以使用mset或msetnx命令来解决。</p>
    > <p>格式：</p>
    > <pre><code class="language-bash highlight-chroma">mset key value <span class="highlight-o">[</span>key value ...<span class="highlight-o">]</span>
    > msetnx key value <span class="highlight-o">[</span>key value ...<span class="highlight-o">]</span>
    > </code></pre>
* 📝 [【Redis源码】Redis 启动过程分析](https://www.zeekling.cn/articles/2020/09/25/1601041404734.html) 
    > <p>由于本人目前是华为<a href="https://support.huawei.com/enterprise/zh/cloud-computing/fusioninsight-hd-pid-21110924" target="_blank">FusionInsight HD</a> 中Redis组件的Owner，所以要对Redis进行深入的了解，这对于C语言水平不咋地的我来讲还是有点难度的，于是我决定先从Redis的启动开始看，了解其基本原理。</p>
* 📝 [【Redis源码】Redis事件监听](https://www.zeekling.cn/articles/2020/10/06/1601975298948.html) 
    > <p>Redis服务器是典型的事件驱动程序，而事件又分为文件事件（socket的可读可写事件）与时间事件（定时任务）两大类。无论是文件事件还是时间事件都封装在结构体aeEventLoop中：</p>
* 📝 [【Redis源码】Redis命令执行过程](https://www.zeekling.cn/articles/2020/10/09/1602258239840.html) 
    > <p>需要了解Redis命令执行过程，请先了解Redis启动过程和Redis事件监听。</p>
    > <blockquote>
    > <p><a href="/articles/2020/09/25/1601041404734.html" target="_blank">Redis启动过程分析</a></p>
    > <p><a href="/articles/2020/10/06/1601975298948.html" target="_blank">Redis事件监听</a></p>
    > </blockquote>
    > <p>在Redis事件监听中我们了解到在创建文件监听事件的时候 <code>acceptTcpHandler</code>就是的执行函数。</p>
* 📝 [【Redis源码】Redis Set命令详解](https://www.zeekling.cn/articles/2020/11/08/1604816679827.html) 
    > <p>set命令用于将key-value设置到数据库。如果key已经设置，则set会用新值覆盖旧值，不管原value是何种类型，如果在设置时不指定EX或PX参数，set命令会清除原有超时时间。</p>




