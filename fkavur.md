代发 wailian999

[U101] JS：classList 操作
来源：http://dali.gotoacloud.top/Article/details/gtuodjlpvm.html

el.classList.toggle("active")
来源：http://dali.zycfv.cn/Article/details/gtgumrapmn.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrfozlls.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.havefunace.top/Article/details/gtzxsyjkum.html

[U103] JS：定时器
来源：http://dali.birdmap.top/Article/details/gtwkucmjdf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hnxiangtu.top/Article/details/gtwikfkbfs.html

[U104] JS：防抖
来源：http://dali.dianchejie.cn/Article/details/gtbabddque.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtwlmelasq.html

[U105] JS：节流
来源：http://dali.mhx1999.top/Article/details/gtodnwbnqy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xziqi.cn/Article/details/gtmrizxqqk.html

[U106] JS：日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtcctoahol.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gzhubu.top/Article/details/gtjorfrbxi.html

[U107] JS：数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gtaescrros.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.daxiang520.top/Article/details/gtkvebhbdj.html

[U108] JS：随机整数
来源：http://dali.birdmap.top/Article/details/gtczwfabbk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhiwuduotai.top/Article/details/gtivigchcc.html

[U109] JS：数组分组
来源：http://dali.tian-w.cn/Article/details/gtoaukpauk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gtiwzncggq.html

[U110] JS：数组分块
来源：http://dali.hongshengwenyu.top/Article/details/gtajnzedod.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.bjfxy.top/Article/details/gtcwhfaigl.html

[U111] JS：对象转 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuyanntb.html

new Map(Object.entries(obj))
来源：http://dali.guannengcc.top/Article/details/gtguockiyw.html

[U112] JS：字符串补位
来源：http://dali.meibo888.top/Article/details/gttzujfner.html

"7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gttzvuhvla.html

[U113] JS：正则替换全部
来源：http://dali.zhoulong.xyz/Article/details/gtqscccrcp.html

s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtjezissfm.html

[U114] JS：JSON 深比较
来源：http://dali.xuetiantiany.cn/Article/details/gtgugfqzoa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gttrgvtzui.html

[U115] JS：生成 UUID
来源：http://dali.mhx1999.top/Article/details/gtzmdbepfq.html

crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gtmixtckej.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shzxlz.cn/Article/details/gtxocpvcvo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jlsjyb.cn/Article/details/gtnkkgdxur.html

[U117] JS：单元测试
来源：http://dali.jqgufenzy.top/Article/details/gtuesrjkfb.html

npm i -D vitest;  npx vitest
来源：http://dali.smart0.xyz/Article/details/gtlhdbdqsy.html

[U118] JS：开发服务器
来源：http://dali.sweek.top/Article/details/gttklufnse.html

npm i -D vite;  npx vite
来源：http://dali.hongshengwenyu.top/Article/details/gtezkyrroz.html

[U119] JS：生产构建
来源：http://dali.hfpthk.cn/Article/details/gtdqxdnyrj.html

npx vite build
来源：http://dali.nanxinkj.top/Article/details/gtweyygsdf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ehwqpu.com/Article/details/gtlcvedkwa.html

import.meta.env.VITE_API_URL
来源：http://dali.xylfe.cn/Article/details/gtxvzpergi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtrmyqsvka.html

统计汇总
来源：http://dali.xuanzx.com/Article/details/gttjibypyw.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtavjpdgwl.html

按语言统计（条）：
来源：http://dali.cdnleiting.top/Article/details/gtocxqonwh.html

Python ......... 252
来源：http://dali.yuanzhike.top/Article/details/gtpynyqmcv.html

PHP ............ 252
来源：http://dali.sxryk.cn/Article/details/gtfsybqazq.html

JavaScript ..... 252
来源：http://dali.bjfxy.top/Article/details/gtnzfccgvv.html

TypeScript ..... 212
来源：http://dali.xylfe.cn/Article/details/gtgpbwwmpf.html

Java ........... 212
来源：http://dali.yongpay.top/Article/details/gtwtrndaoz.html

Go ............. 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtpknirstz.html

Ruby ........... 212
来源：http://dali.yvedp.cn/Article/details/gtblifdwus.html

C# ............. 212
来源：http://dali.jlsjyb.cn/Article/details/gtuaoreuov.html

C .............. 30
来源：http://dali.yj20258.top/Article/details/gtiskiwfwm.html

C++ ............ 30
来源：http://dali.havefunace.top/Article/details/gtdwlnywvx.html

SQL ............ 90
来源：http://dali.tianlin.xyz/Article/details/gtwyegwjii.html

Bash ........... 80
来源：http://dali.ybcxt.top/Article/details/gtkuopiimc.html

Kotlin ......... 15
来源：http://dali.zhongyouzk.top/Article/details/gtilcaskcq.html

Swift .......... 15
来源：http://dali.aizwys.cn/Article/details/gtjcwafpaf.html

Lua ............ 10
来源：http://dali.chenzaomai.com/Article/details/gtqreojvrd.html

Perl ........... 10
来源：http://dali.sweek.top/Article/details/gtcvtgqgxo.html

Scala .......... 10
来源：http://dali.dashuyun.cn/Article/details/gtkoqsbqmb.html

------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtzkxhbyri.html

合计 ........... 2106 条
来源：http://dali.chenjidiqi.icu/Article/details/gtgkfojnhs.html

按章节统计：
来源：http://dali.yvedp.cn/Article/details/gtiadupbib.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gtydmkwiok.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gtfqyergec.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gtexbbznjo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gtxtafvvon.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gotoacloud.top/Article/details/gtlksfqnbx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenzaomai.com/Article/details/gtrmcoixia.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gttmxsicdq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.smart0.xyz/Article/details/gtzbxgoodp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbefjhvr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gtudjhfvnl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtlcwpscud.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtvpqtxxcw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtyvwlioux.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gogol.net.cn/Article/details/gtaaycxncq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.haohaochexian.top/Article/details/gtqnyfksjs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtktnhwacg.html

Q SQL 专题                              90
来源：http://dali.chenzaomai.com/Article/details/gtwkvoaavl.html

R Bash 专题                             80
来源：http://dali.yvedp.cn/Article/details/gthbqraswh.html

S C / C++ 专题                          60
来源：http://dali.tanke756.top/Article/details/gtzffbxexr.html

T 其他语言补充                          60
来源：http://dali.mhx1999.top/Article/details/gtqpshsjjh.html

U 高频实用片段                         120
来源：http://dali.ehwqpu.com/Article/details/gtmkphkxho.html

------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtfopnsmhq.html

合计                                  2106 条
来源：http://dali.shuidangran.top/Article/details/gtartykhaa.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gtpigxxwcn.html

使用提醒
来源：http://dali.jqgufenzy.top/Article/details/gtrhswxqid.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtethxdhli.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.snrcjt.cn/Article/details/gtpsxtkoju.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hongshengwenyu.top/Article/details/gtkjriecvu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj20258888.top/Article/details/gtwfnkktzi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hysaishi.cn/Article/details/gtpnmndzga.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hnxiangtu.top/Article/details/gttlgdewua.html

—— 文件结束 ——
来源：http://dali.aibaodan.cn/Article/details/gthyrjxksl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtegsfepei.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hywenlv.cn/Article/details/gtpjblnbpz.html

Common Programming Examples Cheat Book
来源：http://dali.ybcxt.top/Article/details/gtagubbqis.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtyoxkdtnu.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gtsawdryrs.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.daxiang520.top/Article/details/gtxwbqkejk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sxryk.cn/Article/details/gttfzcyjfe.html

SQL · Bash · C · C++
来源：http://dali.fzhhl.top/Article/details/gtqrentkpr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yongpay.top/Article/details/gthcmqycaj.html

【使用说明】
来源：http://dali.pycfn.com/Article/details/gtuepitjav.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.pengpengdd.cyou/Article/details/gttkhgnoas.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.aibaodan.cn/Article/details/gtmhucnlnq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gtiiizluot.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccxqfzhh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.iojbl.cn/Article/details/gtjnxbdvcz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ppjwa.cn/Article/details/gtfncfwppc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.bjfxy.top/Article/details/gtqtgkjdsv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ppjwa.cn/Article/details/gtizbnnnmy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yvedp.cn/Article/details/gtviuhixfx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtroflbjpm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinqigfzy.top/Article/details/gteqwgsfka.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmshqbhe.html

【文件统计】
来源：http://dali.0kj1m.cn/Article/details/gtjrohsydy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jianghu66.top/Article/details/gtaqnipdph.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtcybuapcw.html

目  录
来源：http://dali.jqgfzy.top/Article/details/gtxbuwdqyj.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtbwpojugb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.redwolf501.top/Article/details/gttnqfeoyp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gtpsczpthh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gtknwtxlsb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyderutb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj20258888.top/Article/details/gtrlbnwaxl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.redwolf501.top/Article/details/gtqgvceccl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gthaivlatm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtzwyktody.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtgftdmtsw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shuidangran.top/Article/details/gtgheoeyxz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gtaizdjtcj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gtjedqendi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtmllizmto.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yueranfly.top/Article/details/gteudafpkq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xylfe.cn/Article/details/gtljzicucp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yuxming.cn/Article/details/gtimekhlff.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenzaomai.com/Article/details/gteamucftq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaydqatcj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.sxryk.cn/Article/details/gtnuwqufiy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gtltgtktkm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhoulong.xyz/Article/details/gtawhdrtpp.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnetpweqe.html

A. 基础语法与类型
来源：http://dali.vqdsnc.cn/Article/details/gtmleficbc.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffmdunyk.html

[A01] Hello World
来源：http://dali.jqgfzy.top/Article/details/gtvobqgclj.html

Py:   print("Hello, World!")
来源：http://dali.jinqigfzy.top/Article/details/gtegkqyiid.html

PHP:  echo "Hello, World!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvwhucrp.html

JS:   console.log("Hello, World!");
来源：http://dali.fzhhl.top/Article/details/gtliaieoqv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.quarkkingdee.top/Article/details/gtilftofog.html

Java: System.out.println("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gtzchnsnbg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shuidangran.top/Article/details/gtotizesyx.html

Ruby: puts "Hello, World!"
来源：http://dali.wangshuangyany.cn/Article/details/gtzvbtyftq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jinqigufen.top/Article/details/gtbowcqphx.html

[A02] 变量声明与赋值
来源：http://dali.haohaochexian.top/Article/details/gtyavozxqa.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.aizwys.cn/Article/details/gtftxzxees.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zycfv.cn/Article/details/gtgltwabvo.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.dianchejie.cn/Article/details/gtcjzlunha.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ehwqpu.com/Article/details/gtrlfvjada.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zycfv.cn/Article/details/gtlwmpagik.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncvnwbjf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ybcxt.top/Article/details/gtuvnrtvnt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.fengsongda.top/Article/details/gtqxtcuwze.html

[A03] 常量定义
来源：http://dali.wangshuangyany.cn/Article/details/gtzfysdmhc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhongyouzk.top/Article/details/gtztcdbkho.html

PHP:  const PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtidyxmcel.html

JS:   const PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtxnnxjaku.html

TS:   const PI: number = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtourcchhk.html

Java: static final double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtafhgahwy.html

Go:   const PI = 3.14159
来源：http://dali.yanxiufei.cn/Article/details/gtjlkspxou.html

Ruby: PI = 3.14159
来源：http://dali.jiagoushi.top/Article/details/gtlojfmkcm.html

C#:   const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtxatryzfb.html

[A04] 判断变量类型
来源：http://dali.xziqi.cn/Article/details/gtlgkpscvg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zdqjudy.top/Article/details/gtberurqop.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigfzy.top/Article/details/gtrrxhlsyc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.redwolf501.top/Article/details/gthkseemgy.html

TS:   typeof x; x instanceof Date
来源：http://dali.snrcjt.cn/Article/details/gtngorwemz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hysaishi.cn/Article/details/gtjtnnqfxt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.svipenyu.cn/Article/details/gtduzsoqns.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.mhx1999.top/Article/details/gtpkkctwge.html

C#:   x.GetType().Name; x is int
来源：http://dali.zdqjudy.top/Article/details/gtdkuraqwn.html

[A05] 整数除法与取模
来源：http://dali.cashguo.top/Article/details/gthegshaes.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.guowangkeji.top/Article/details/gtqtjdqjcs.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtksbcxuuw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtyrjdkyzz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtmoiydsct.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gtryqbjvzn.html

Go:   7 / 2; 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtgjsqpqhx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gtzirbvoqm.html

C#:   7 / 2; 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtsrajldme.html

[A06] 字符串转数字
来源：http://dali.tian-w.cn/Article/details/gtyloaalvk.html

Py:   int("42"); float("3.14")
来源：http://dali.iojbl.cn/Article/details/gticnobokg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hfpthk.cn/Article/details/gtibqpukkw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sweek.top/Article/details/gtcbwevmdd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.tianlin.xyz/Article/details/gttzqbmyjn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.aibaodan.cn/Article/details/gtdihjwlsn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yuanzhike.top/Article/details/gtwaymvzec.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jqgufenzy.top/Article/details/gtastwwhmw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xziqi.cn/Article/details/gtokaloaxh.html

[A07] 数字转字符串
来源：http://dali.sweek.top/Article/details/gtfahlniht.html

Py:   str(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpblnxjj.html

PHP:  (string) 42; strval(42)
来源：http://dali.smart0.xyz/Article/details/gtrktydbkv.html

JS:   String(42); (42).toString()
来源：http://dali.9152youxi.cn/Article/details/gtwipkcrsu.html

TS:   String(42)
来源：http://dali.ppjwa.cn/Article/details/gtnrjuvgix.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.sysykeji.top/Article/details/gthcwumugj.html

Go:   strconv.Itoa(42)
来源：http://dali.xziqi.cn/Article/details/gtosvenctv.html

Ruby: 42.to_s
来源：http://dali.zdqjudy.top/Article/details/gtnctewnos.html

C#:   42.ToString()
来源：http://dali.daria6918.cn/Article/details/gtkabovjqk.html

[A08] 取整与四舍五入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzdvscjj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlwqrlrm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hongshengwenyu.top/Article/details/gttxlabhqi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gtfkxntzkq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.sufxvd.cn/Article/details/gtcormvrwz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yj20258888.top/Article/details/gtboaemfsk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cheryme.top/Article/details/gtcyqfjjyw.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jlsjyb.cn/Article/details/gtctpppgqk.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gtevkasxuc.html

[A09] 绝对值与最大最小值
来源：http://dali.guowangkeji.top/Article/details/gtkfefjwst.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj20258.top/Article/details/gtfqbksbfq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtxvhlcfed.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtmlzbxrvx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtyishbyco.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtqgedtvld.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yvedp.cn/Article/details/gtkjiywbjq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.redwolf501.top/Article/details/gttpairdrt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gttdsvebqm.html

[A10] 生成随机数
来源：http://dali.redwolf501.top/Article/details/gtsrpbpjbz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlhaokwt.html

PHP:  random_int(1, 100);
来源：http://dali.jiagoushi.top/Article/details/gtvavzztbs.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.pengpengdd.cyou/Article/details/gtmoauvtfp.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yuanzhike.top/Article/details/gtlikthrde.html

Java: new Random().nextInt(100) + 1
来源：http://dali.svipenyu.cn/Article/details/gtqozmrbgb.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gaohongyu789.top/Article/details/gtshevwaqs.html

Ruby: rand(1..100)
来源：http://dali.jinqigufen.top/Article/details/gtyadoqkfs.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinqigufen.top/Article/details/gtqauinbxc.html

[A11] 条件表达式（三元）
来源：http://dali.iojbl.cn/Article/details/gtozbyuvyf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.chenlongwang.top/Article/details/gtpslohdwj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtvelouqns.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gtmzsnhghn.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gtukespyao.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtyttertio.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yongpay.top/Article/details/gthztfnsfd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtgykayrgx.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gtoiurgabt.html

[A12] 字符串插值 / 格式化
来源：http://dali.sysykeji.top/Article/details/gtlovskinc.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jyoumei.cn/Article/details/gtcwdfphgt.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhiwuduotai.top/Article/details/gtvskfwnur.html

JS:   `Hello, ${name}!`
来源：http://dali.bjfxy.top/Article/details/gtrqzufmll.html

TS:   `Hello, ${name}!`
来源：http://dali.aizwys.cn/Article/details/gtkbilowqh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yueranfly.top/Article/details/gtwqtsmmis.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.sysykeji.top/Article/details/gtcbmqadzu.html

Ruby: "Hello, #{name}!"
来源：http://dali.wangshuangyany.cn/Article/details/gtswmmlwla.html

C#:   $"Hello, {name}!"
来源：http://dali.ydzc1.top/Article/details/gtwiuqemce.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.snrcjt.cn/Article/details/gtkbevlhue.html

Py:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gtciwoczhc.html

PHP:  "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gttipnndiu.html

JS:   "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gttdriynpn.html

TS:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtyinnfpyw.html

Java: "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtwbghilwn.html

Go:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtjzdcyyht.html

Ruby: "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtbquylsuu.html

C#:   "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gtvnwxormh.html

[A14] 注释写法
来源：http://dali.jqgufenzy.top/Article/details/gtfyephvbi.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yonumen.top/Article/details/gtohsakltu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gtbttdwvki.html

JS:   // 单行；/* 多行 */
来源：http://dali.sysykeji.top/Article/details/gtpuyplnxe.html

TS:   // 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gtdqliawoa.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hysaishi.cn/Article/details/gtryjdptjb.html

Go:   // 单行；/* 多行 */
来源：http://dali.yj20258.top/Article/details/gtciiguiee.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.guowangkeji.top/Article/details/gtwnjqugmh.html

C#:   // 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gtxosjeeoa.html

[A15] 空值判断与默认值
来源：http://dali.hfpthk.cn/Article/details/gtzjtzuiuq.html

Py:   value = data or "默认值"
来源：http://dali.xuetiantiany.cn/Article/details/gtlwyouyqs.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cashguo.top/Article/details/gtymkbmkej.html

JS:   const value = data ?? "默认值";
来源：http://dali.guowangkeji.top/Article/details/gtcurlrgkh.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhiwuduotai.top/Article/details/gtuqllhioz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkpyeozb.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.tian-w.cn/Article/details/gtjytuslyi.html

Ruby: value = data || "默认值"
来源：http://dali.tanke756.top/Article/details/gtorxpssez.html

C#:   var value = data ?? "默认值";
来源：http://dali.andypj.xyz/Article/details/gtjihzuuum.html

[A16] 真假值判断规则
来源：http://dali.cheryme.top/Article/details/gtzqkchisf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jinqigfzy.top/Article/details/gtluyuizjx.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.birdmap.top/Article/details/gtpgcopynv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.svipenyu.cn/Article/details/gtyhswfbfl.html

TS:   if (!x) {}
来源：http://dali.nanxuanxn.top/Article/details/gtutfoybnp.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hnqzz.top/Article/details/gtrpkyabqv.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.tanke756.top/Article/details/gtxyvnaocu.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hongshengwenyu.top/Article/details/gtsghiwyfc.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.tian-w.cn/Article/details/gtbfddgvld.html

[A17] 位运算
来源：http://dali.yueranfly.top/Article/details/gtwclcgbyb.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gthvntbtct.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtpweuguyw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gthubmlifs.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gtjpjglzdz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gtlwczxcbf.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gthggvnnzz.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gtougwrltk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtswhzvhqd.html


<!-- 参考信息 -->