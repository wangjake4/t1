代发 wailian999

[U101] JS：classList 操作
来源：http://dali.chenzaomai.com/Article/details/gtzfvyxtzp.html

el.classList.toggle("active")
来源：http://dali.hammf.cn/Article/details/gtaaieruja.html

[U102] JS：本地存储
来源：http://dali.cdnleiting.top/Article/details/gtbuplvpch.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shangyingyoupin.top/Article/details/gtpfnvubix.html

[U103] JS：定时器
来源：http://dali.feifeiyinyue.top/Article/details/gtcehdyuna.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyuqpprk.html

[U104] JS：防抖
来源：http://dali.cashguo.top/Article/details/gtfselgfsw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtjkbcopwk.html

[U105] JS：节流
来源：http://dali.tian-w.cn/Article/details/gtftvwmulc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xuanzx.com/Article/details/gtwonfnyfl.html

[U106] JS：日期格式化
来源：http://dali.xuanzx.com/Article/details/gtlkpfkzvf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.0kj1m.cn/Article/details/gtkeabwevt.html

[U107] JS：数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndyavjgk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtcmkmxhmo.html

[U108] JS：随机整数
来源：http://dali.havefunace.top/Article/details/gtosgypccr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.vqdsnc.cn/Article/details/gtqplfbczt.html

[U109] JS：数组分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsvzrryh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gtldlstheh.html

[U110] JS：数组分块
来源：http://dali.meibo888.top/Article/details/gtszidsfot.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.guannengcc.top/Article/details/gtdjpfuckr.html

[U111] JS：对象转 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjerrcwnp.html

new Map(Object.entries(obj))
来源：http://dali.xylfe.cn/Article/details/gtohasusje.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gtssrsciki.html

"7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtnytbqabc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gtcdqpztxb.html

s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtukaxpzkl.html

[U114] JS：JSON 深比较
来源：http://dali.gzhubu.top/Article/details/gtathzwcwn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.smart0.xyz/Article/details/gtickdcder.html

[U115] JS：生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gtesgxmrrc.html

crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtrctkpnca.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.9152youxi.cn/Article/details/gtrkrcemqr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258888.top/Article/details/gtjsohxcmr.html

[U117] JS：单元测试
来源：http://dali.xuanzx.com/Article/details/gtgodzzmum.html

npm i -D vitest;  npx vitest
来源：http://dali.daria6918.cn/Article/details/gtdyefmhlv.html

[U118] JS：开发服务器
来源：http://dali.bjfxy.top/Article/details/gtcrkkmrwd.html

npm i -D vite;  npx vite
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxcddhps.html

[U119] JS：生产构建
来源：http://dali.zhongyouzk.top/Article/details/gtzurdjbyl.html

npx vite build
来源：http://dali.hongshengwenyu.top/Article/details/gtfjmuwrac.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zdqjudy.top/Article/details/gtpiachwzz.html

import.meta.env.VITE_API_URL
来源：http://dali.chenjidiqi.icu/Article/details/gtctfaikus.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbbgsccip.html

统计汇总
来源：http://dali.nwbrower.top/Article/details/gtsjzricyu.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtaiytfurc.html

按语言统计（条）：
来源：http://dali.zhixingplan.top/Article/details/gtotorindd.html

Python ......... 252
来源：http://dali.jlsjyb.cn/Article/details/gtrsvjvlqr.html

PHP ............ 252
来源：http://dali.feifeiyinyue.top/Article/details/gtfvweoalw.html

JavaScript ..... 252
来源：http://dali.vqdsnc.cn/Article/details/gtzqijwkbs.html

TypeScript ..... 212
来源：http://dali.hongshengwenyu.top/Article/details/gtowdsaiir.html

Java ........... 212
来源：http://dali.cqqwz.cn/Article/details/gtbrfuygay.html

Go ............. 212
来源：http://dali.gotoacloud.top/Article/details/gtpvbcfybd.html

Ruby ........... 212
来源：http://dali.hammf.cn/Article/details/gtjhonvxwm.html

C# ............. 212
来源：http://dali.wangdashe.top/Article/details/gthfagnyfw.html

C .............. 30
来源：http://dali.yongpay.top/Article/details/gtnfdhjgcq.html

C++ ............ 30
来源：http://dali.shangyingyoupin.top/Article/details/gtcspsrsog.html

SQL ............ 90
来源：http://dali.zhongyouzk.top/Article/details/gtaopyoqqr.html

Bash ........... 80
来源：http://dali.pengpengdd.cyou/Article/details/gtgorptcty.html

Kotlin ......... 15
来源：http://dali.0kj1m.cn/Article/details/gtvwtwwirb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gtslhuwgan.html

Lua ............ 10
来源：http://dali.sysykeji.top/Article/details/gtfxgfcwlw.html

Perl ........... 10
来源：http://dali.yanxiufei.cn/Article/details/gtsajfeikc.html

Scala .......... 10
来源：http://dali.xuanzx.com/Article/details/gtdihkzubg.html

------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtxgzsvfew.html

合计 ........... 2106 条
来源：http://dali.andypj.xyz/Article/details/gtsnrszkww.html

按章节统计：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtpaobwo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.svipenyu.cn/Article/details/gtxwxfuswd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gtsbzsbouh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtgjyqjpyl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yuxming.cn/Article/details/gtfmwxqged.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nanxinkj.top/Article/details/gtmpcyjfgg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jianghu66.top/Article/details/gtlarnhpzy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gtgpdqhmer.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gthnxhqvet.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gtliheqkae.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shangyingyoupin.top/Article/details/gttoptxwoj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtxgqhhubb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtvtynszrz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtiyopczjs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.redwolf501.top/Article/details/gtvlfukhcg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.mhx1999.top/Article/details/gtaisgruvp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtsobviubd.html

Q SQL 专题                              90
来源：http://dali.sweek.top/Article/details/gtwlmkcwya.html

R Bash 专题                             80
来源：http://dali.9152youxi.cn/Article/details/gteatohiyw.html

S C / C++ 专题                          60
来源：http://dali.yuanzhike.top/Article/details/gtwwydvegm.html

T 其他语言补充                          60
来源：http://dali.tanke756.top/Article/details/gtektqtppg.html

U 高频实用片段                         120
来源：http://dali.wangshuangyany.cn/Article/details/gtmryexvzl.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtrptyavzz.html

合计                                  2106 条
来源：http://dali.vqdsnc.cn/Article/details/gtdpvzzbln.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtovcjnwln.html

使用提醒
来源：http://dali.daxiang520.top/Article/details/gtszjywszv.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtwlmfaubv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cashguo.top/Article/details/gthkfxzahw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.dianchejie.cn/Article/details/gtkpvjfvgd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jqgufenzy.top/Article/details/gtuddvzjyy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.9152youxi.cn/Article/details/gtvzhaeljs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.andypj.xyz/Article/details/gtxgpylgta.html

—— 文件结束 ——
来源：http://dali.guannengcc.top/Article/details/gtrulpwner.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtuazgsbvs.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hammf.cn/Article/details/gthirlhagw.html

Common Programming Examples Cheat Book
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflkeihcx.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtntbkvwwr.html

【收录内容】
来源：http://dali.guannengcc.top/Article/details/gttcigqkqn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.nanxuanxn.top/Article/details/gtansuwkhw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gtuyddpokn.html

SQL · Bash · C · C++
来源：http://dali.shangyingyoupin.top/Article/details/gtpktmdjxl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.vqdsnc.cn/Article/details/gtqvdzlodn.html

【使用说明】
来源：http://dali.zycfv.cn/Article/details/gtciaezvyd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sufxvd.cn/Article/details/gtbzqheapx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sufxvd.cn/Article/details/gtjfjzwmms.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.mhx1999.top/Article/details/gtbuaprsgj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.c1oappe.top/Article/details/gtyizscvsm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.aibaodan.cn/Article/details/gthsmbceai.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.smart0.xyz/Article/details/gtqnimyxmd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xuetiantiany.cn/Article/details/gtzmognmwv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.guannengcc.top/Article/details/gtbsyrcntj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xinyue.icu/Article/details/gtvjhtzgad.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jlsjyb.cn/Article/details/gtroxfyxsi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.guowangkeji.top/Article/details/gtsesyuygz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yueranfly.top/Article/details/gtwtteeqya.html

【文件统计】
来源：http://dali.sweek.top/Article/details/gtcaecudgx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yonumen.top/Article/details/gtmnscyifr.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtzyawncjs.html

目  录
来源：http://dali.dashuyun.cn/Article/details/gtqtivddnk.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtmluyfcsf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yuanzhike.top/Article/details/gtkeosqwji.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gtxeoasijm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gtiglzphrm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinqigfzy.top/Article/details/gtofxlgakb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.wangdashe.top/Article/details/gtyksakram.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yongpay.top/Article/details/gtvpyreodk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtesaomiio.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ydzc1.top/Article/details/gtokldkgks.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtdztiegpx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cashguo.top/Article/details/gtiudqksqp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gtdmemxemj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtcdrjmupm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gtdegfjrrm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jlsjyb.cn/Article/details/gtnqvdypsn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.tian-w.cn/Article/details/gtyviwpbbv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtzkhddeeg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yonumen.top/Article/details/gtlxeudukz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jianghu66.top/Article/details/gtbkokkagm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtgephnhsz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gtgmugwjra.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.haohaochexian.top/Article/details/gtrmcikqlt.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtuqbnnurj.html

A. 基础语法与类型
来源：http://dali.9152youxi.cn/Article/details/gtacolsswu.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtiuzwccav.html

[A01] Hello World
来源：http://dali.wangdashe.top/Article/details/gtfslrixns.html

Py:   print("Hello, World!")
来源：http://dali.iojbl.cn/Article/details/gtudbpunvo.html

PHP:  echo "Hello, World!";
来源：http://dali.snrcjt.cn/Article/details/gtbusqrlzo.html

JS:   console.log("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gtjayozbuy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.tanke756.top/Article/details/gtygzuxdsr.html

Java: System.out.println("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gthkknnrax.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hywenlv.cn/Article/details/gtjtlffgly.html

Ruby: puts "Hello, World!"
来源：http://dali.tanke756.top/Article/details/gtjvyjyrwi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yangfankeji.com/Article/details/gteebrtqui.html

[A02] 变量声明与赋值
来源：http://dali.xylfe.cn/Article/details/gthtcspjpb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.wangdashe.top/Article/details/gtinhbybyl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.pycfn.com/Article/details/gtwfufwhhr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.smart0.xyz/Article/details/gtjfkmyvzo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.daria6918.cn/Article/details/gtzhjmwntp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtjuuvtzhu.html

Go:   name := "Alex"; age := 20
来源：http://dali.nanxinkj.top/Article/details/gtgksurkkn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gtcrnwtyzz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhixingplan.top/Article/details/gttgimhlrp.html

[A03] 常量定义
来源：http://dali.jqgfzy.top/Article/details/gtlmawcwuo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhengqikj.top/Article/details/gtqbbjhsmk.html

PHP:  const PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtmznwlvxo.html

JS:   const PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtnvvuhtej.html

TS:   const PI: number = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtandixjxi.html

Java: static final double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtteqxbmcn.html

Go:   const PI = 3.14159
来源：http://dali.wangdashe.top/Article/details/gtqsomgags.html

Ruby: PI = 3.14159
来源：http://dali.ydzc1.top/Article/details/gtdaciosmf.html

C#:   const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtbkpkbnqe.html

[A04] 判断变量类型
来源：http://dali.jinqigfzy.top/Article/details/gtxqjfmdzd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhoulong.xyz/Article/details/gtehanrayw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nanxuanxn.top/Article/details/gtplgrwdoh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xuetiantiany.cn/Article/details/gteazkqore.html

TS:   typeof x; x instanceof Date
来源：http://dali.tian-w.cn/Article/details/gtgokhkwbg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jqgufenzy.top/Article/details/gtfpnilwhc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.pengpengdd.cyou/Article/details/gtyhfvpugr.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xylfe.cn/Article/details/gtvkbogsmk.html

C#:   x.GetType().Name; x is int
来源：http://dali.jyoumei.cn/Article/details/gttqzxigdo.html

[A05] 整数除法与取模
来源：http://dali.pengpengdd.cyou/Article/details/gtpgjabtan.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.aibaodan.cn/Article/details/gtzgvycfkh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gtvxvqvxeo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtnjiktqzd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtjlpqffgl.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtwmnttqyr.html

Go:   7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtzkadkogy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gttfgfvzpb.html

C#:   7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtqnvopqww.html

[A06] 字符串转数字
来源：http://dali.cashguo.top/Article/details/gthwuxbzqw.html

Py:   int("42"); float("3.14")
来源：http://dali.zhiwuduotai.top/Article/details/gtdrxrhqcy.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hongshengwenyu.top/Article/details/gtjhxmkrjs.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xuanzx.com/Article/details/gtqdwfpjpy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ehwqpu.com/Article/details/gthforpehz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.tanke756.top/Article/details/gtosguffxb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzukxtib.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.meibo888.top/Article/details/gtcllwiacd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.0kj1m.cn/Article/details/gthxrspbaz.html

[A07] 数字转字符串
来源：http://dali.daria6918.cn/Article/details/gtaugkiltj.html

Py:   str(42)
来源：http://dali.meibo888.top/Article/details/gtnapnmhil.html

PHP:  (string) 42; strval(42)
来源：http://dali.xinyue.icu/Article/details/gtmtbameon.html

JS:   String(42); (42).toString()
来源：http://dali.hysaishi.cn/Article/details/gtloxatkwf.html

TS:   String(42)
来源：http://dali.yvedp.cn/Article/details/gtdwsrencv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.sysykeji.top/Article/details/gtcwhrihaj.html

Go:   strconv.Itoa(42)
来源：http://dali.birdmap.top/Article/details/gtxdmdgkiw.html

Ruby: 42.to_s
来源：http://dali.yongpay.top/Article/details/gtohcuzwwy.html

C#:   42.ToString()
来源：http://dali.ehwqpu.com/Article/details/gtdoabwpor.html

[A08] 取整与四舍五入
来源：http://dali.cqqwz.cn/Article/details/gtzccojxan.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtphvicnqm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.fengsongda.top/Article/details/gtonjzpled.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gtiaaolbyw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.birdmap.top/Article/details/gtyrblvfnl.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gtodpmtknd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtzptkkicu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.nwbrower.top/Article/details/gtomvcqpro.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gtdjlvesws.html

[A09] 绝对值与最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gtuwqgbstq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtsogbvvnc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.havefunace.top/Article/details/gtmucysezd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtmeeyqlel.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.daria6918.cn/Article/details/gttnlrwqil.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ivvv.top/Article/details/gtxmizkaij.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhiwuduotai.top/Article/details/gttsqchkea.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ydzc1.top/Article/details/gtiiwafyog.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtzomsvuzo.html

[A10] 生成随机数
来源：http://dali.0kj1m.cn/Article/details/gtvwkazjhj.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xylfe.cn/Article/details/gtdwhtqphn.html

PHP:  random_int(1, 100);
来源：http://dali.xuanzx.com/Article/details/gtgwmrigvu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.quarkkingdee.top/Article/details/gtptkljnqz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fengsongda.top/Article/details/gtcfwhahis.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xziqi.cn/Article/details/gtiocpjygb.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.haohaochexian.top/Article/details/gtmjgwxigr.html

Ruby: rand(1..100)
来源：http://dali.jqgufenzy.top/Article/details/gtspbbwvjf.html

C#:   new Random().Next(1, 101)
来源：http://dali.quarkkingdee.top/Article/details/gtthlfqgim.html

[A11] 条件表达式（三元）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyzrsbpj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ybcxt.top/Article/details/gtquszdvxo.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gtnfnkpqjz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtvbsxdklv.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gtowzlycum.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gtgddcxmbv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xuanzx.com/Article/details/gtnssycznq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gtybietuqx.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gtcbilxbol.html

[A12] 字符串插值 / 格式化
来源：http://dali.sufxvd.cn/Article/details/gtobrjyxxm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hysaishi.cn/Article/details/gtvvzuxkhx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hnxiangtu.top/Article/details/gttxnodlec.html

JS:   `Hello, ${name}!`
来源：http://dali.redwolf501.top/Article/details/gthpodkpau.html

TS:   `Hello, ${name}!`
来源：http://dali.dashuyun.cn/Article/details/gtrecazwtz.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xuanzx.com/Article/details/gtykpppusm.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinqigfzy.top/Article/details/gtxfappwfx.html

Ruby: "Hello, #{name}!"
来源：http://dali.dashuyun.cn/Article/details/gtyfllturr.html

C#:   $"Hello, {name}!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqhbjdrn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhiwuduotai.top/Article/details/gtduezvpnb.html

Py:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gttzdbcmfh.html

PHP:  "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtokeonulq.html

JS:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtdxutypli.html

TS:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gthyjzyrby.html

Java: "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtaotbcc.html

Go:   "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gtemmneyep.html

Ruby: "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gtdhmzxbqn.html

C#:   "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtmqlyrhyx.html

[A14] 注释写法
来源：http://dali.xuanzx.com/Article/details/gtehpangex.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yangfankeji.com/Article/details/gtdwjcvger.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbckmwou.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gtpsxhftyi.html

TS:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gtvyklgdss.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yanxiufei.cn/Article/details/gtvcsqqhky.html

Go:   // 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gtcmfdpnrx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.chenzaomai.com/Article/details/gtvsxiyofm.html

C#:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gtbprbxtfp.html

[A15] 空值判断与默认值
来源：http://dali.sufxvd.cn/Article/details/gtqbrcaudw.html

Py:   value = data or "默认值"
来源：http://dali.shangyingyoupin.top/Article/details/gtjnbikyct.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jyoumei.cn/Article/details/gtnyokywsc.html

JS:   const value = data ?? "默认值";
来源：http://dali.xylfe.cn/Article/details/gthevndnmr.html

TS:   const value = data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gtgcpwwrbv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrkndtlk.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.guannengcc.top/Article/details/gtvwkjdyeu.html

Ruby: value = data || "默认值"
来源：http://dali.nanxuanxn.top/Article/details/gtjssjffgw.html

C#:   var value = data ?? "默认值";
来源：http://dali.0kj1m.cn/Article/details/gtrxskgxle.html

[A16] 真假值判断规则
来源：http://dali.nanxinkj.top/Article/details/gtcnbkkkeq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhongyouzk.top/Article/details/gtbzfdufct.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gtcuhjpbeb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.tian-w.cn/Article/details/gttywarevc.html

TS:   if (!x) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjobzjtc.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ppjwa.cn/Article/details/gtwolvbgnu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.sxryk.cn/Article/details/gtcbemctxm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gogol.net.cn/Article/details/gtxfkxxgei.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.snrcjt.cn/Article/details/gtohrwktyy.html

[A17] 位运算
来源：http://dali.gotoacloud.top/Article/details/gtpgsqvymo.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtlequzqpj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gtijndgana.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gtitwqwqww.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gtmwvoubis.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gtzulrvpdj.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtkagoto.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtgeovmypq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtzkwxtczs.html


<!-- 参考信息 -->