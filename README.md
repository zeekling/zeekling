### Hey 👋, I'm [Zeek Ling](https://www.zeekling.cn)! 
![Github Stats](https://github-readme-stats.vercel.app/api?username=zeekling&show_icons=true) 
### 我在[小令童鞋](https://www.zeekling.cn)的近期动态

⭐️ Star [个人主页](https://github.com/zeekling/zeekling) 后会自动更新，最近更新时间：`2020-12-06 12:00:14`

<p align="center"><img alt="ZEEKLING" src="https://img.zeekling.cn/images/2020/02/23/logo.th.png"></p><h2 align="center">ZEEKLING
</h2>

<h4 align="center">Stay simple, stay naive.</h4>
<p align="center"><a title="ZEEKLING" target="_blank" href="https://github.com/zeekling/zeekling"><img src="https://img.shields.io/github/last-commit/zeekling/zeekling.svg?style=flat-square&color=FF9900"></a>
<a title="GitHub repo size in bytes" target="_blank" href="https://github.com/zeekling/zeekling"><img src="https://img.shields.io/github/repo-size/zeekling/zeekling.svg?style=flat-square"></a>
<a title="Hits" target="_blank" href="https://github.com/zeekling/hits"><img src="https://hits.b3log.org/zeekling/zeekling.svg"></a></p>

### 最新

* 📝 [机器学习知识点总结](https://www.zeekling.cn/articles/2019/08/14/1565788128215.html) 
    > <p>主要是为了列个机器学习相关的提纲,方便对已经学过的知识进行整理,相同的知识点,每次或者每个阶段都会有不同的想法,而我需要做的就是把自己的想法写下来.</p>
* 📝 [Redis 学习知识点总结](https://www.zeekling.cn/articles/2020/09/01/1598892381872.html) 
    > <p>本文的主要目的就是对之前看过的Redis相关的文章做一个简单的提纲，方便以后汇总复习。</p>
    > <p>目前主要包含两方面：基础知识和源码解读。</p>
* 📝 [About Me](https://www.zeekling.cn/aboutMe.html) 
    > <p>自己搭建博客的原因是现有的博客系统不满足我的要求，简单来说就是看着现有的博客系统不顺眼，现在博客主要内容就是自己平时看的书以及各种想法总结等等。还有就是希望博客上面记载的东西能够帮助到别人。</p>
* 📝 [【Redis源码】RDB持久化源码实现](https://www.zeekling.cn/articles/2020/11/25/1606235262538.html) 
    > <p>RDB快照有两种触发方式，其一为通过配置参数，例如在配置文件中写入如下配置：</p>
    > <pre><code class="language-cpp highlight-chroma"><span class="highlight-n">save</span> <span class="highlight-mi">60</span> <span class="highlight-mi">1000</span>
    > </code></pre>
    > <p>则在60秒内如果有1000个key发生变化，就会触发一次RDB快照的执行。</p>
    > <p>其二是通过在客户端执行bgsave命令显式触发一次RDB快照的执行。</p>
* 📝 [【Redis源码】Redis 6 ACL源码详解](https://www.zeekling.cn/articles/2020/11/22/1606060178482.html) 
    > <p>本文主要是讲解Redis 6的ACL的实现原理。基本使用详见：<a href="/articles/2020/11/22/1606048977051.html" target="_blank">Redis 6.0新特性——ACLs</a>，以及<a href="https://www.zeekling.cn/articles/2020/09/25/1601041404734.html">Redis启动过程分析</a>。</p>
* 📝 [Redis 6.0新特性——ACLs](https://www.zeekling.cn/articles/2020/11/22/1606048977051.html) 
    > <p>Redis ACL是Access Control List（访问控制列表）的缩写，该功能允许根据可以执行的命令和可以访问的键来限制某些连接。它的工作方式是，在连接之后，要求客户端进行身份验证，以提供用户名和有效密码：如果身份验证阶段成功，则连接与给定用户关联，并且该用户具有限制。可以对Redis进行配置，以使新连接已过“默认”用户进行身份验证（这是默认配置），因此，配置默认用户具有的能力是，仅向连接提供特定功能子集的功能未明确认证。</p>
* 📝 [腾讯云服务器优化](https://www.zeekling.cn/articles/2019/12/21/1576925825908.html) 
    > <p>大概就是在几个月之前本人租了一台服务器用来搭建自己的博客(原来的博客是在阿里云香港服务器上面,在十一期间被和谐了),于是租用了1核1G内存的云服务器(三年800多元),可是在使用的过程中发现cpu和内存占用有点异常,查了下发现以下问题:</p>
    > <ul>
    > <li>服务器上面跑着几个监控软件(并没有什么),占了好多CPU.</li>
    > <li>服务器没有swap分区,1G虽然够用,但是优点不爽</li>
    > <li>内存的缓存部分占得比例比较大</li>
    > <li>磁盘变大了好多,但是本人安装的几个软件都不会占这么多磁盘</li>
    > </ul>
* 📝 [gitea 使用jenkins 自动ci ](https://www.zeekling.cn/articles/2020/09/13/1600002728592.html) 
    > <p>我目前使用的代码仓库是使用 <code>gitea</code>搭建而成的，详细参见<a href="https://git.zeekling.cn/" target="_blank">https://git.zeekling.cn</a>, 最近在看<a href="https://git.zeekling.cn/zeekling/redis" target="_blank">redis源码</a>于是就想着加个自动ci的东西。</p>




