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

* 📝 [Redis集群主备缓存区满了导致主备频繁倒换](https://www.zeekling.cn/articles/2022/02/27/1645957902937.html) 
    > <p>问题现象：Redis 频繁进行主备倒换，通过查看主实例的日志：redis.log发现下面报错：</p>
    > <pre><code class="language-bash highlight-chroma">Client <span class="highlight-nv">id</span><span class="highlight-o">=</span><span class="highlight-m">1317049445</span> <span class="highlight-nv">addr</span><span class="highlight-o">=</span>192.168.2.45:8004 <span class="highlight-nv">fd</span><span class="highlight-o">=</span><span class="highlight-m">40</span> <span class="highlight-nv">name</span><span class="highlight-o">=</span> <span class="highlight-nv">age</span><span class="highlight-o">=</span><span class="highlight-m">314</span> <span class="highlight-nv">idle</span><span class="highlight-o">=</span><span class="highlight-m">0</span> <span class="highlight-nv">flags</span><span class="highlight-o">=</span>S <span class="highlight-nv">db</span><span class="highlight-o">=</span><span class="highlight-m">0</span> <span class="highlight-nv">sub</span><span class="highlight-o">=</span><span class="highlight-m">0</span> 
    > <span class="highlight-nv">psub</span><span class="highlight-o">=</span><span class="highlight-m">0</span> <span class="highlight-nv">multi</span><span class="highlight-o">=</span>-1 <span class="highlight-nv">qbuf</span><span class="highlight-o">=</span><span class="highlight-m">0</span> qbuf-free<span class="highlight-o">=</span><span class="highlight-m">32568</span> <span class="highlight-nv">obl</span><span class="highlight-o">=</span><span class="highlight-m">0</span> <span class="highlight-nv">oll</span><span class="highlight-o">=</span><span class="highlight-m">4430</span> <span class="highlight-nv">omem</span><span class="highlight-o">=</span><span class="highlight-m">761143439</span> <span class="highlight-nv">events</span><span class="highlight-o">=</span>rw <span class="highlight-nv">cmd</span><span class="highlight-o">=</span>psync
    >  scheduled to be closed ASAP <span class="highlight-k">for</span> overcoming of output buffer limits
    > </code></pre>
    > <p>其中：<code>psync scheduled to be closed ASAP for overcoming of output buffer limits</code> 明显就是问题所在，那是什么问题呢。于是我在源码中搜索了<code>scheduled to be closed ASAP for overcoming of output buffer limits</code>(psync明显是一个命令，就不用在代码里面搜索了)。</p>
* 📝 [bolo-fantastic皮肤整改](https://www.zeekling.cn/articles/2020/09/04/1599150574976.html) 
    > <p>整改皮肤bolo-fantastic的原因如下：</p>
    > <ul>
    > <li>bolo-fantastic 挺好看的，至少我挺喜欢的。</li>
    > <li>存在一些看起来不那么完美的地方。</li>
    > <li>我有病(可能是最主要的原因)。</li>
    > </ul>
    > <p>于是就有了整改。</p>
* 📝 [Linux sogou输入法显示简体输入却是繁体](https://www.zeekling.cn/articles/2021/03/25/1616675636194.html) 
    > <p>最新linux电脑搜狗输入法老是在输入的时候显示中文简体，但是输入到文件，或者浏览器里面就变成了繁体。很是让人头疼，网上搜了下也没人讲这种事。</p>
* 📝 [Git命令详解](https://www.zeekling.cn/articles/2019/12/01/1575184426144.html) 
    > <p>主要记录自己平时使用的 Git 命令，方便记忆和查找..</p>
* 📝 [Redis知识思维导图总结](https://www.zeekling.cn/articles/2021/11/07/1636295639346.html) 
    > <p>Redis基础知识总结思维导图，系统的学习Redis。不定时更新。</p>
    > <p>主要包括：</p>
    > <ul>
    > <li>基本数据和应用场景</li>
    > <li>常见问题分析</li>
    > <li>性能优化</li>
    > <li>持久化</li>
    > <li>集群模式</li>
    > <li>子模块</li>
    > </ul>
* 📝 [idea卡顿且报错：UI was frozen for xxxxx ms问题解决](https://www.zeekling.cn/articles/2021/04/30/1619715915118.html) 
    > <p>idea 启动并且点击某个菜单之后一点反应也没有，点击关闭也关闭不掉，查看日志报错提示UI was frozen for 12256ms。</p>
* 📝 [Redis实现分布式锁](https://www.zeekling.cn/articles/2022/01/09/1641722558007.html) 
    > <p>Redis被经常用来实现分布式锁，本文主要讲述redis如何实现一个分布式锁的demo。</p>
* 📝 [如何正确执行Jedis单元测试](https://www.zeekling.cn/articles/2021/12/29/1640785618937.html) 
    > <p>引用官方的介绍：</p>
    > <blockquote>
    > <p>Jedis is a Java client for <a href="https://github.com/redis/redis" title="Redis" target="_blank">Redis</a> designed for performance and ease of use.</p>
    > </blockquote>
    > <p>本文主要讲如何在修改完Jedis代码之后完成单元测试。</p>
* 📝 [博客接入Google 广告](https://www.zeekling.cn/articles/2019/12/10/1575989964574.html) 
    > <p>最近可能是闲的蛋疼，所以打算在自己博客上面接入广告。</p>
* 📝 [kali rolling linux 安装BCM43142网卡驱动](https://www.zeekling.cn/articles/2020/09/26/1601091635148.html) 
    > <p>手动迁移CSDN博客。</p>
    > <p>玩linux已经有半年多的时间了，在这半年时间里，我的linux系统重装了已经不下于十次了吧。最近心血来潮，玩了一把kali linux (大学霸)，除了无线网卡驱动没有之外，其他的都很满意，比之前用的ubuntu系列的好多了。我知道有好多人都在用ubuntu系统，主要是因为这个系统用的人多，社区力量比较大，你能遇到的问题别人都已经遇到过了，在网上都可以找到很多关于ubuntu这个系统出问题之后的解决方案。ubuntu的确是入门的好东西。但是他也有好多缺点：不怎么稳定，在ubuntu用过一段时间之后，你会发现电脑开机之后会弹出很多错误信息，我特别讨厌这个，就把这个弹框禁止了，后来开机就没有这个可恶的东西了。但是如果不禁止的话这个就有点不友好了。ubuntu的源太旧了，有好多软件用apt 安装后会发现版本太旧了，根本没办法用，然后的自己从官网上下载，然后编译安装。对于一个想学好linux 的人来说，这些不算什么，但是源太旧的话就失去了源存在的意义了，不是吗。最后我觉着ubuntu的界面实在是不好看，尽管网上有人说ubuntu的界面不错，但是我觉得真的不好看，当然桌面可以自己装，这个不算什么。</p>




