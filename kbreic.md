代发 wailian999

[U105] JS：节流
来源：http://dali.guowangkeji.top/Article/details/gtkgdaiwzh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgufenzy.top/Article/details/gttegetwhm.html

[U106] JS：日期格式化
来源：http://dali.yuxming.cn/Article/details/gtxiqbqbiq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.redwolf501.top/Article/details/gtftezhzkm.html

[U107] JS：数字千分位
来源：http://dali.tian-w.cn/Article/details/gtxbodvbrd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xinyue.icu/Article/details/gtxehfeapc.html

[U108] JS：随机整数
来源：http://dali.feifeiyinyue.top/Article/details/gtffebkbhz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fengsongda.top/Article/details/gtvfiytqlk.html

[U109] JS：数组分组
来源：http://dali.feifeiyinyue.top/Article/details/gtkkjkebpy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gtiitngorr.html

[U110] JS：数组分块
来源：http://dali.ivvv.top/Article/details/gtrlvqnwxj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yueranfly.top/Article/details/gtsccfsmef.html

[U111] JS：对象转 Map
来源：http://dali.aibaodan.cn/Article/details/gtzfyjfziv.html

new Map(Object.entries(obj))
来源：http://dali.xinyue.icu/Article/details/gtvmgptfyt.html

[U112] JS：字符串补位
来源：http://dali.yueranfly.top/Article/details/gtwccuxkij.html

"7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtybohokgo.html

[U113] JS：正则替换全部
来源：http://dali.daxiang520.top/Article/details/gtqitvdqqr.html

s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtjrysfzdx.html

[U114] JS：JSON 深比较
来源：http://dali.jlsjyb.cn/Article/details/gttsjlhaaz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gttxofwnfi.html

[U115] JS：生成 UUID
来源：http://dali.jianghu66.top/Article/details/gtuafyfgga.html

crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbozmljwg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xinyue.icu/Article/details/gtubfbgidr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj202588.top/Article/details/gtxwdhqevw.html

[U117] JS：单元测试
来源：http://dali.iojbl.cn/Article/details/gtfhwvgimy.html

npm i -D vitest;  npx vitest
来源：http://dali.snrcjt.cn/Article/details/gtzerqopra.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangtech.top/Article/details/gttuhtcspb.html

npm i -D vite;  npx vite
来源：http://dali.zhongyouzk.top/Article/details/gtfjgymjfn.html

[U119] JS：生产构建
来源：http://dali.haohaochexian.top/Article/details/gtusnpbycy.html

npx vite build
来源：http://dali.jqgfzy.top/Article/details/gtapkuscyq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cashguo.top/Article/details/gtltvxwbjn.html

import.meta.env.VITE_API_URL
来源：http://dali.fzhhl.top/Article/details/gthlevrsip.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtidjernmr.html

统计汇总
来源：http://dali.jqgfzy.top/Article/details/gtvqasnsdp.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkdwpztqt.html

按语言统计（条）：
来源：http://dali.gogol.net.cn/Article/details/gtqpogwdsr.html

Python ......... 252
来源：http://dali.zhixingplan.top/Article/details/gtgzqfpsej.html

PHP ............ 252
来源：http://dali.yongpay.top/Article/details/gtbiakkyrj.html

JavaScript ..... 252
来源：http://dali.wangshuangyany.cn/Article/details/gtfosaohwp.html

TypeScript ..... 212
来源：http://dali.jiagoushi.top/Article/details/gtxfajfama.html

Java ........... 212
来源：http://dali.iojbl.cn/Article/details/gtofkxmrry.html

Go ............. 212
来源：http://dali.redwolf501.top/Article/details/gttnziwrew.html

Ruby ........... 212
来源：http://dali.cheryme.top/Article/details/gtjjyvfwgl.html

C# ............. 212
来源：http://dali.shuidangran.top/Article/details/gtmaeitnsx.html

C .............. 30
来源：http://dali.9152youxi.cn/Article/details/gtvonyxdpv.html

C++ ............ 30
来源：http://dali.aibaodan.cn/Article/details/gtvlhscmjv.html

SQL ............ 90
来源：http://dali.pengpengdd.cyou/Article/details/gtfvylueit.html

Bash ........... 80
来源：http://dali.hysaishi.cn/Article/details/gttgyfmbyn.html

Kotlin ......... 15
来源：http://dali.shangyingyoupin.top/Article/details/gtslzyxcte.html

Swift .......... 15
来源：http://dali.dashuyun.cn/Article/details/gtrjrmlbeo.html

Lua ............ 10
来源：http://dali.zhongyouzk.top/Article/details/gtqpoyhhdi.html

Perl ........... 10
来源：http://dali.xziqi.cn/Article/details/gtbdciblod.html

Scala .......... 10
来源：http://dali.guannengcc.top/Article/details/gtjpprokgr.html

------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtaakaknjt.html

合计 ........... 2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gtvsdhzjlo.html

按章节统计：
来源：http://dali.yuanzhike.top/Article/details/gtteexpepj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.c1oappe.top/Article/details/gtvxgvevtt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gtixwrvspq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtulfnnszy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.guowangkeji.top/Article/details/gttedolyyi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hongshengwenyu.top/Article/details/gtlzyrocry.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.aizwys.cn/Article/details/gtdcfbaimj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gtgexpkhhq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gthbfhqiax.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtwnncnefu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.kuanghao11.cn/Article/details/gthkqnmgpc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtorqmwque.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtgmbyngtt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdqbtssu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gzhubu.top/Article/details/gtishhurat.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pycfn.com/Article/details/gtdknhfywb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtafafqwtm.html

Q SQL 专题                              90
来源：http://dali.cashguo.top/Article/details/gtdknajfnt.html

R Bash 专题                             80
来源：http://dali.smart0.xyz/Article/details/gtvzgmepfw.html

S C / C++ 专题                          60
来源：http://dali.jinghuilouyu.cn/Article/details/gtueyveqnm.html

T 其他语言补充                          60
来源：http://dali.mhx1999.top/Article/details/gtbqrfsteq.html

U 高频实用片段                         120
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehbaarsq.html

------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtpbdosumh.html

合计                                  2106 条
来源：http://dali.tian-w.cn/Article/details/gtaqhvrlqx.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtmsrnhbzq.html

使用提醒
来源：http://dali.cdnleiting.top/Article/details/gtzyhnkpur.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtmpxskngb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yonumen.top/Article/details/gtvusxruhp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ehwqpu.com/Article/details/gtikpaylxk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.guowangkeji.top/Article/details/gtdhfcgtew.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ybcxt.top/Article/details/gtaccrcnux.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.snrcjt.cn/Article/details/gtxgvqkkzv.html

—— 文件结束 ——
来源：http://dali.hywenlv.cn/Article/details/gtzrhhxjwq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpknkbobi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj202588.top/Article/details/gtjutuuzsk.html

Common Programming Examples Cheat Book
来源：http://dali.zhoulong.xyz/Article/details/gtrrsmixvs.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtiqdutolk.html

【收录内容】
来源：http://dali.bjfxy.top/Article/details/gtuyogoahe.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.quarkkingdee.top/Article/details/gtthiddwrb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sweek.top/Article/details/gtjpkpfjzb.html

SQL · Bash · C · C++
来源：http://dali.nwbrower.top/Article/details/gtzttvroaf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinghuilouyu.cn/Article/details/gtormmwtlz.html

【使用说明】
来源：http://dali.quarkkingdee.top/Article/details/gtleyaojzm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.andypj.xyz/Article/details/gtbhqzihpq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jlsjyb.cn/Article/details/gtuddyocdt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zycfv.cn/Article/details/gtulfmbwus.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gaohongyu789.top/Article/details/gttvapfpgw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.iojbl.cn/Article/details/gtfngoeqmc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.wangshuangyany.cn/Article/details/gthqiermkj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yueranfly.top/Article/details/gtsgfkkgel.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jianghu66.top/Article/details/gthcqobqhg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cashguo.top/Article/details/gtdnilsuab.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tianlin.xyz/Article/details/gtpegjkjsf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xuetiantiany.cn/Article/details/gtyorsuaqe.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.fengsongda.top/Article/details/gtgzcdxiqs.html

【文件统计】
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmmjkqzi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gaohongyu789.top/Article/details/gtvtjywxco.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtwxtmflks.html

目  录
来源：http://dali.hnxiangtu.top/Article/details/gthtsjxeyu.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtbczpiuek.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtnbsvisnq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gotoacloud.top/Article/details/gtiwnsimra.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gtkmzdmtkh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.tian-w.cn/Article/details/gthvevypea.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hnxiangtu.top/Article/details/gtrnvumsvp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xziqi.cn/Article/details/gtwrvtmblx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtcwpbhjjv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hnxiangtu.top/Article/details/gtsfqwucfx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtevinoevx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gteudgjncw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gtysnybfpc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtplnwxbgo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtpordeboc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtveimujln.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jyoumei.cn/Article/details/gttnnkvacj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gtoffofsif.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yuxming.cn/Article/details/gtkrpjvcho.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yuanzhike.top/Article/details/gtcawwldae.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gzhubu.top/Article/details/gthtxttdzj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtvwxtjlam.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gtzrqhdqbg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwvzbhmxg.html

A. 基础语法与类型
来源：http://dali.hammf.cn/Article/details/gtywsamflw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtpgxvbowa.html

[A01] Hello World
来源：http://dali.sxryk.cn/Article/details/gtjrfnfdty.html

Py:   print("Hello, World!")
来源：http://dali.mhx1999.top/Article/details/gtlzlbnwsn.html

PHP:  echo "Hello, World!";
来源：http://dali.ybcxt.top/Article/details/gtzeuyqiiv.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gtnukbespk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.dashuyun.cn/Article/details/gtlprzxmlu.html

Java: System.out.println("Hello, World!");
来源：http://dali.zdqjudy.top/Article/details/gtgpsfgabk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hywenlv.cn/Article/details/gtqlimbqyf.html

Ruby: puts "Hello, World!"
来源：http://dali.kuanghao11.cn/Article/details/gtkeveyier.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gtqrdgirsk.html

[A02] 变量声明与赋值
来源：http://dali.zycfv.cn/Article/details/gttamzddbu.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.guowangkeji.top/Article/details/gtboiwqnou.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.316326.xyz/Article/details/gtpktjdzqx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yvedp.cn/Article/details/gtrzhjrepl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gttryhwjif.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hnqzz.top/Article/details/gttfuwuxwg.html

Go:   name := "Alex"; age := 20
来源：http://dali.quarkkingdee.top/Article/details/gtxphtermr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xinyue.icu/Article/details/gtecrtznjh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yuanzhike.top/Article/details/gtbziqqcaj.html

[A03] 常量定义
来源：http://dali.chenlongwang.top/Article/details/gtzcwlusuv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtousilfxl.html

PHP:  const PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtpxodaunb.html

JS:   const PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gttrdfeosh.html

TS:   const PI: number = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtrqmjtwev.html

Java: static final double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtsggreave.html

Go:   const PI = 3.14159
来源：http://dali.xinyue.icu/Article/details/gtyzgidrsr.html

Ruby: PI = 3.14159
来源：http://dali.zhengqikj.top/Article/details/gtvffehwsr.html

C#:   const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtfggxellg.html

[A04] 判断变量类型
来源：http://dali.chenzaomai.com/Article/details/gtzbrfrmag.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hysaishi.cn/Article/details/gtnoodlvil.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.0kj1m.cn/Article/details/gtoiaiflvs.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.havefunace.top/Article/details/gtevwyhqjf.html

TS:   typeof x; x instanceof Date
来源：http://dali.chenjidiqi.icu/Article/details/gtdwegqmus.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gaohongyu789.top/Article/details/gtfxtbvqwe.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sysykeji.top/Article/details/gtpspnbbuo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.guannengcc.top/Article/details/gtjlhmhvpb.html

C#:   x.GetType().Name; x is int
来源：http://dali.shuidangran.top/Article/details/gtbsddknqy.html

[A05] 整数除法与取模
来源：http://dali.hysaishi.cn/Article/details/gtvwjrvrit.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sufxvd.cn/Article/details/gtpafexkji.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtutokecov.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtpxjivkeq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtxxbcablc.html

Java: 7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtekpvtmdy.html

Go:   7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtmghbomfe.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtchjtdutm.html

C#:   7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtsfkmzeeb.html

[A06] 字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gtwxgalvyk.html

Py:   int("42"); float("3.14")
来源：http://dali.chenlongwang.top/Article/details/gtamqncogm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.guowangkeji.top/Article/details/gtdujldsyu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.wangdashe.top/Article/details/gtlywfcrhm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sweek.top/Article/details/gtbmsqgtci.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hnqzz.top/Article/details/gtlqrpdiwb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhoulong.xyz/Article/details/gtcpcbgqsg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.fengsongda.top/Article/details/gtzvhxnmta.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yvedp.cn/Article/details/gtbrypakcm.html

[A07] 数字转字符串
来源：http://dali.shzxlz.cn/Article/details/gtbxlkzjem.html

Py:   str(42)
来源：http://dali.zhixingplan.top/Article/details/gtirxfmpap.html

PHP:  (string) 42; strval(42)
来源：http://dali.gaohongyu789.top/Article/details/gtiwlntcyu.html

JS:   String(42); (42).toString()
来源：http://dali.nwbrower.top/Article/details/gtfloolwtt.html

TS:   String(42)
来源：http://dali.zhongyouzk.top/Article/details/gtwyppdsqg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.andypj.xyz/Article/details/gtzsobpekk.html

Go:   strconv.Itoa(42)
来源：http://dali.chenlongwang.top/Article/details/gtvjltczak.html

Ruby: 42.to_s
来源：http://dali.yj202588.top/Article/details/gtucainkzp.html

C#:   42.ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gtrdwdgwgb.html

[A08] 取整与四舍五入
来源：http://dali.ehwqpu.com/Article/details/gtvkrpiiwa.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gtzgahbkll.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zdqjudy.top/Article/details/gtlsoyndpo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtfxugpcmv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hfpthk.cn/Article/details/gtjzrfoyxu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gtdprxodro.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gtoopjttkc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yuanzhike.top/Article/details/gtnbjgnhqj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yj20258888.top/Article/details/gtshpwkare.html

[A09] 绝对值与最大最小值
来源：http://dali.smart0.xyz/Article/details/gtevpvbbmo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xziqi.cn/Article/details/gttkmhraxm.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtgdsslygh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtobgdplsw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtmxarincw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtfubiyrym.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sxryk.cn/Article/details/gtqzsiyhmb.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yanxiufei.cn/Article/details/gtnlkctnwq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtwhfseznv.html

[A10] 生成随机数
来源：http://dali.xuetiantiany.cn/Article/details/gthqopotit.html

Py:   import random; random.randint(1, 100)
来源：http://dali.0kj1m.cn/Article/details/gtyspgodxi.html

PHP:  random_int(1, 100);
来源：http://dali.ppjwa.cn/Article/details/gtytmcrnud.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenzaomai.com/Article/details/gtutgeckbn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcbetygi.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgwflkrx.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.pycfn.com/Article/details/gtujmjvzxo.html

Ruby: rand(1..100)
来源：http://dali.smart0.xyz/Article/details/gthzrkvcyi.html

C#:   new Random().Next(1, 101)
来源：http://dali.andypj.xyz/Article/details/gtgbjmsadn.html

[A11] 条件表达式（三元）
来源：http://dali.sweek.top/Article/details/gttnmqxqnk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhengqikj.top/Article/details/gtdfyadaii.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gteyvsjaht.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gtcxloahmh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtkrgfoent.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gtudtnggxr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yj20258.top/Article/details/gtlgvwdjid.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gtlmigqcrt.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.svipenyu.cn/Article/details/gtqqkwvzmz.html

[A12] 字符串插值 / 格式化
来源：http://dali.yuanzhike.top/Article/details/gtwbflxuvc.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yueranfly.top/Article/details/gtvmrqsdtu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.guowangkeji.top/Article/details/gtsxiaedfu.html

JS:   `Hello, ${name}!`
来源：http://dali.zycfv.cn/Article/details/gtrccheorh.html

TS:   `Hello, ${name}!`
来源：http://dali.hnqzz.top/Article/details/gtmahrxdis.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.dianchejie.cn/Article/details/gtnorxprgd.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtazomaqyt.html

Ruby: "Hello, #{name}!"
来源：http://dali.cdnleiting.top/Article/details/gtybhasyvw.html

C#:   $"Hello, {name}!"
来源：http://dali.yangfankeji.com/Article/details/gtwywzmwfn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.wangshuangyany.cn/Article/details/gtxellwsxz.html

Py:   "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gtocryceee.html

PHP:  "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gtrgjqhyml.html

JS:   "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtygdtdlmm.html

TS:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gtjjzaiptq.html

Java: "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gttuutprwj.html

Go:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtpwuspfbx.html

Ruby: "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtavbadwlw.html

C#:   "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gtcemowlci.html

[A14] 注释写法
来源：http://dali.sufxvd.cn/Article/details/gtxpxopaod.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.guannengcc.top/Article/details/gtrnhzvcxf.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gtpxmiedyy.html

JS:   // 单行；/* 多行 */
来源：http://dali.birdmap.top/Article/details/gtwcdmmlga.html

TS:   // 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gtnquoufxu.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.bjfxy.top/Article/details/gtjrbviwce.html

Go:   // 单行；/* 多行 */
来源：http://dali.redwolf501.top/Article/details/gtwfbcrlow.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.wangdashe.top/Article/details/gtvsueuzvi.html

C#:   // 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gtkuiaygvz.html

[A15] 空值判断与默认值
来源：http://dali.dashuyun.cn/Article/details/gtycvyfijl.html

Py:   value = data or "默认值"
来源：http://dali.shuidangran.top/Article/details/gtafwuqoml.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.guowangkeji.top/Article/details/gtwjunoble.html

JS:   const value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gtbycoesat.html

TS:   const value = data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gtizlhtszc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnbeigqc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.havefunace.top/Article/details/gtfryadfvh.html

Ruby: value = data || "默认值"
来源：http://dali.yj202588.top/Article/details/gtiddwxgod.html

C#:   var value = data ?? "默认值";
来源：http://dali.cheryme.top/Article/details/gtbdmgwhyp.html

[A16] 真假值判断规则
来源：http://dali.sysykeji.top/Article/details/gtgnccqsie.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowjrajwx.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jqgufenzy.top/Article/details/gtxtsggevd.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdddbdss.html

TS:   if (!x) {}
来源：http://dali.9152youxi.cn/Article/details/gtsbmqvskm.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xziqi.cn/Article/details/gtopapjicc.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jianghu66.top/Article/details/gtbokipiqc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jyoumei.cn/Article/details/gtfnjewyhx.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtjlvillhj.html

[A17] 位运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdadrrawm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahjmmzni.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.9152youxi.cn/Article/details/gtjxmzvvsh.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtcugdsacq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtefgmpblc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gtvralnshz.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gtersruuxn.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gtbgwpecke.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gtgxeokpka.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yvedp.cn/Article/details/gtshidnnhn.html

Py:   ord("A"); chr(65)
来源：http://dali.jinqigufen.top/Article/details/gtdurmixth.html

PHP:  ord("A"); chr(65)
来源：http://dali.shzxlz.cn/Article/details/gtepolkdsd.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.smart0.xyz/Article/details/gtnngwmvms.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigufen.top/Article/details/gtorlrfmrg.html

Java: (int) 'A'; (char) 65
来源：http://dali.gogol.net.cn/Article/details/gtzubtjeed.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.quarkkingdee.top/Article/details/gtsjeajhto.html

Ruby: "A".ord; 65.chr
来源：http://dali.cdnleiting.top/Article/details/gtqjwjdwhd.html


<!-- 参考信息 -->