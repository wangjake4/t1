代发 wailian999

[U105] JS：节流
来源：http://dali.yj20258888.top/Article/details/gtpleiqtnw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yongpay.top/Article/details/gtrzupttxd.html

[U106] JS：日期格式化
来源：http://dali.guannengcc.top/Article/details/gthiqihnba.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yuanzhike.top/Article/details/gthlxothon.html

[U107] JS：数字千分位
来源：http://dali.chenzaomai.com/Article/details/gtjozgxeei.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sweek.top/Article/details/gtjuinlrxg.html

[U108] JS：随机整数
来源：http://dali.hnqzz.top/Article/details/gtvrtminjg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yanxiufei.cn/Article/details/gtyjvssmwi.html

[U109] JS：数组分组
来源：http://dali.hywenlv.cn/Article/details/gtmklotjuz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtmkmltllv.html

[U110] JS：数组分块
来源：http://dali.jqgufenzy.top/Article/details/gtwjkpipyh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nwbrower.top/Article/details/gtnuncwqfn.html

[U111] JS：对象转 Map
来源：http://dali.cheryme.top/Article/details/gtggrmfawn.html

new Map(Object.entries(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtzbdsafwh.html

[U112] JS：字符串补位
来源：http://dali.yueranfly.top/Article/details/gtfjtgrpjv.html

"7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtfuakkhge.html

[U113] JS：正则替换全部
来源：http://dali.guannengcc.top/Article/details/gtdxkkyckc.html

s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtgxvtxaat.html

[U114] JS：JSON 深比较
来源：http://dali.ydzc1.top/Article/details/gtrprbmeir.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gthvuccdcw.html

[U115] JS：生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gttfvghlsv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtpefeximv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tanke756.top/Article/details/gtntbgwpgk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gogol.net.cn/Article/details/gthuzxbjme.html

[U117] JS：单元测试
来源：http://dali.hfpthk.cn/Article/details/gtcpyajtfj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhengqikj.top/Article/details/gtvahjeubl.html

[U118] JS：开发服务器
来源：http://dali.gotoacloud.top/Article/details/gthslfixvx.html

npm i -D vite;  npx vite
来源：http://dali.andypj.xyz/Article/details/gtiffrhkbk.html

[U119] JS：生产构建
来源：http://dali.xuetiantiany.cn/Article/details/gtexqgmrse.html

npx vite build
来源：http://dali.dianchejie.cn/Article/details/gtmegxdkct.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cqqwz.cn/Article/details/gttgolsmqa.html

import.meta.env.VITE_API_URL
来源：http://dali.fzhhl.top/Article/details/gtcnfnsrxf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtxfepnbwz.html

统计汇总
来源：http://dali.ybcxt.top/Article/details/gtszykbzjk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtnkxxadza.html

按语言统计（条）：
来源：http://dali.zhiwuduotai.top/Article/details/gtwjtnzizo.html

Python ......... 252
来源：http://dali.iojbl.cn/Article/details/gtdlffikbb.html

PHP ............ 252
来源：http://dali.redwolf501.top/Article/details/gtfcbxrqwo.html

JavaScript ..... 252
来源：http://dali.jinghuilouyu.cn/Article/details/gtduvsqtcl.html

TypeScript ..... 212
来源：http://dali.shangyingyoupin.top/Article/details/gtlxkygkrd.html

Java ........... 212
来源：http://dali.guannengcc.top/Article/details/gtrqacqweh.html

Go ............. 212
来源：http://dali.jqgufenzy.top/Article/details/gtvvxbermr.html

Ruby ........... 212
来源：http://dali.shangyingyoupin.top/Article/details/gttwekfvjp.html

C# ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gtgxxdnobo.html

C .............. 30
来源：http://dali.mhx1999.top/Article/details/gtqpwyitzy.html

C++ ............ 30
来源：http://dali.hnqzz.top/Article/details/gtrubxqktv.html

SQL ............ 90
来源：http://dali.jyoumei.cn/Article/details/gtrgdnojeu.html

Bash ........... 80
来源：http://dali.yuxming.cn/Article/details/gtftjmhqau.html

Kotlin ......... 15
来源：http://dali.zdqjudy.top/Article/details/gtjiekcmgx.html

Swift .......... 15
来源：http://dali.pengpengdd.cyou/Article/details/gtncbutcte.html

Lua ............ 10
来源：http://dali.pycfn.com/Article/details/gtmmgboffa.html

Perl ........... 10
来源：http://dali.jianghu66.top/Article/details/gtwyzlyxke.html

Scala .......... 10
来源：http://dali.yongpay.top/Article/details/gtqjvjkcfw.html

------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gtfyynjfnd.html

合计 ........... 2106 条
来源：http://dali.ivvv.top/Article/details/gteszfneqe.html

按章节统计：
来源：http://dali.fengsongda.top/Article/details/gtxsdcwcqq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gaohongyu789.top/Article/details/gtizmxkmuj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gtwpudonvi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopnmduwz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxiikhjv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aibaodan.cn/Article/details/gtnpuqrkbi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gtdkqouvvo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gtyxjiytqq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.316326.xyz/Article/details/gtduzbppxb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gtwrmwssyx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.tianlin.xyz/Article/details/gtnykqpgca.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtbgcmtxnn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gtvjuffnwk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gtgtljifyo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gtjpgecrjy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yanxiufei.cn/Article/details/gtrrvlsoqk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtgdrmnfmb.html

Q SQL 专题                              90
来源：http://dali.yuanzhike.top/Article/details/gthqaftyxk.html

R Bash 专题                             80
来源：http://dali.c1oappe.top/Article/details/gthdheluqx.html

S C / C++ 专题                          60
来源：http://dali.yonumen.top/Article/details/gtgzzpnxqm.html

T 其他语言补充                          60
来源：http://dali.chenjidiqi.icu/Article/details/gtoxbelfjz.html

U 高频实用片段                         120
来源：http://dali.havefunace.top/Article/details/gtsqqtknvi.html

------------------------------------
来源：http://dali.meibo888.top/Article/details/gtyjrmlgxh.html

合计                                  2106 条
来源：http://dali.nanxuanxn.top/Article/details/gtnoepijog.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gttaoroknw.html

使用提醒
来源：http://dali.aizwys.cn/Article/details/gtncwabfrz.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtmywzbvds.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.kuanghao11.cn/Article/details/gtltrxccru.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ybcxt.top/Article/details/gtekkjudwp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.dashuyun.cn/Article/details/gtimkrmkgi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cheryme.top/Article/details/gtznapzgfl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.fengsongda.top/Article/details/gtsiznwfek.html

—— 文件结束 ——
来源：http://dali.yj202588.top/Article/details/gthqjmdsqm.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtrfrzkeoz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxzatpiq.html

Common Programming Examples Cheat Book
来源：http://dali.jinqigfzy.top/Article/details/gtpgugpalk.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmmydguh.html

【收录内容】
来源：http://dali.chenlongwang.top/Article/details/gtazvalgrn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cucudq.cn/Article/details/gtynimvsri.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.feifeiyinyue.top/Article/details/gtuvrjpdwo.html

SQL · Bash · C · C++
来源：http://dali.jiagoushi.top/Article/details/gtnhpjmqnl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.aibaodan.cn/Article/details/gtvdvjousg.html

【使用说明】
来源：http://dali.birdmap.top/Article/details/gtqexyqjah.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yongpay.top/Article/details/gtcdlrtjyp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinyuanbaomall.cn/Article/details/gttffbfsew.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.pengpengdd.cyou/Article/details/gtfzgbixmn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hywenlv.cn/Article/details/gtmwklfkmc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xinyue.icu/Article/details/gtonnsfqmn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ehwqpu.com/Article/details/gtkeqwombt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shuidangran.top/Article/details/gteqwxezba.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.quarkkingdee.top/Article/details/gtxfbqmfpe.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.snrcjt.cn/Article/details/gtxvxoljbj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.mhx1999.top/Article/details/gtcdzdrbge.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yuanzhike.top/Article/details/gtknthcbky.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.0kj1m.cn/Article/details/gtkixfawwy.html

【文件统计】
来源：http://dali.feifeiyinyue.top/Article/details/gtxkuyldqm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sysykeji.top/Article/details/gtwzjfrgyv.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtfyjwmxvg.html

目  录
来源：http://dali.ydzc1.top/Article/details/gtbzbqtkpf.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtwqfjqahp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cheryme.top/Article/details/gtfphthyaz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlceidlbk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gtjzvwebct.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.guowangkeji.top/Article/details/gtjefxllqi.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hfpthk.cn/Article/details/gtcorlpsuy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.tian-w.cn/Article/details/gtsfqqxgdd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.chenlongwang.top/Article/details/gtrlbufkto.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtmfwvdtnc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gtryaphidx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sxryk.cn/Article/details/gtatnqxmfo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gtlaomenvk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtcojligjd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gtebxcpmij.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hnqzz.top/Article/details/gtniumnkhc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nwbrower.top/Article/details/gtesabqjst.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gtowhsyjva.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtvelugubj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.iojbl.cn/Article/details/gtxgwnpqai.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.birdmap.top/Article/details/gtewaljojn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gtjqrcuueb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jianghu66.top/Article/details/gtvjhxkejh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtijjdzngs.html

A. 基础语法与类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjbgqfah.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtpstqxals.html

[A01] Hello World
来源：http://dali.daxiang520.top/Article/details/gtnkgnlszn.html

Py:   print("Hello, World!")
来源：http://dali.mhx1999.top/Article/details/gtvdcdreqa.html

PHP:  echo "Hello, World!";
来源：http://dali.kuanghao11.cn/Article/details/gttqgqhgzt.html

JS:   console.log("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gtuipyajsr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hammf.cn/Article/details/gtqsikjkzf.html

Java: System.out.println("Hello, World!");
来源：http://dali.sweek.top/Article/details/gtmbcgnmls.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cdnleiting.top/Article/details/gtofpghrkm.html

Ruby: puts "Hello, World!"
来源：http://dali.jqgfzy.top/Article/details/gthnfcftek.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tianlin.xyz/Article/details/gtiifaezyb.html

[A02] 变量声明与赋值
来源：http://dali.zhoulong.xyz/Article/details/gtkyjyielz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shangyingyoupin.top/Article/details/gtncwznmzb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yongpay.top/Article/details/gtexjhrvhn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj20258.top/Article/details/gtamivykxa.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.snrcjt.cn/Article/details/gtinjakdwk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.guannengcc.top/Article/details/gtwxzgsuec.html

Go:   name := "Alex"; age := 20
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzqxqjfy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.haohaochexian.top/Article/details/gtiadyfaqk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ivvv.top/Article/details/gtlskgvisr.html

[A03] 常量定义
来源：http://dali.sufxvd.cn/Article/details/gtnqacudfq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.wangshuangyany.cn/Article/details/gtkvhhkzgj.html

PHP:  const PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtbgimqjnq.html

JS:   const PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtnbmdmouo.html

TS:   const PI: number = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtprumffmf.html

Java: static final double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtbmflhaqa.html

Go:   const PI = 3.14159
来源：http://dali.fengsongda.top/Article/details/gtqsuyysqb.html

Ruby: PI = 3.14159
来源：http://dali.zhengqikj.top/Article/details/gtetzjkoxb.html

C#:   const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtpegpptsp.html

[A04] 判断变量类型
来源：http://dali.jyoumei.cn/Article/details/gtqulgyjsb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tian-w.cn/Article/details/gtqdtcmpjt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.snrcjt.cn/Article/details/gtqasrutzq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.dianchejie.cn/Article/details/gtvkrzcist.html

TS:   typeof x; x instanceof Date
来源：http://dali.vqdsnc.cn/Article/details/gtzivdaqqj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hammf.cn/Article/details/gtkjsuqapj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnxiangtu.top/Article/details/gtvbikmcfn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.316326.xyz/Article/details/gtjuoycffa.html

C#:   x.GetType().Name; x is int
来源：http://dali.zycfv.cn/Article/details/gtmoxbecvn.html

[A05] 整数除法与取模
来源：http://dali.cucudq.cn/Article/details/gtjzzifqvu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xuanzx.com/Article/details/gtfmayismu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtirjnzehn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cheryme.top/Article/details/gtjqqwulbp.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gteajfewkz.html

Java: 7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtugrkzdfj.html

Go:   7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtwkvexjgd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsaejvydd.html

C#:   7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtdeeymdop.html

[A06] 字符串转数字
来源：http://dali.hammf.cn/Article/details/gtmtkbiedp.html

Py:   int("42"); float("3.14")
来源：http://dali.hysaishi.cn/Article/details/gtuewfdama.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cheryme.top/Article/details/gtokprqrho.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jqgfzy.top/Article/details/gtlysqxpsl.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hysaishi.cn/Article/details/gtooobqizz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jqgfzy.top/Article/details/gtvhkjprvm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xuanzx.com/Article/details/gtfncgloul.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.chenjidiqi.icu/Article/details/gtlzhwxsrg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhixingplan.top/Article/details/gtitfluwul.html

[A07] 数字转字符串
来源：http://dali.xuanzx.com/Article/details/gtyftcmeii.html

Py:   str(42)
来源：http://dali.yj20258888.top/Article/details/gttsoeqvyc.html

PHP:  (string) 42; strval(42)
来源：http://dali.yangfankeji.com/Article/details/gtvyxcqhrd.html

JS:   String(42); (42).toString()
来源：http://dali.hnqzz.top/Article/details/gtlprahsjs.html

TS:   String(42)
来源：http://dali.yj20258888.top/Article/details/gtdtngnowd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.dianchejie.cn/Article/details/gtwlunhypr.html

Go:   strconv.Itoa(42)
来源：http://dali.wangdashe.top/Article/details/gtfahzssox.html

Ruby: 42.to_s
来源：http://dali.tianlin.xyz/Article/details/gtukzhrlhx.html

C#:   42.ToString()
来源：http://dali.smart0.xyz/Article/details/gtlucsadal.html

[A08] 取整与四舍五入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuyjptct.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gtozaksxea.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.svipenyu.cn/Article/details/gtcrdyexmi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtzboqnevg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jianghu66.top/Article/details/gtztfwijam.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gtyhmzdamd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yongpay.top/Article/details/gtjcgeifyd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yongpay.top/Article/details/gtilakmsbc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtoccybyqv.html

[A09] 绝对值与最大最小值
来源：http://dali.jqgfzy.top/Article/details/gtratxptlx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtqvdswmwp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtldrjhlxq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtqfjfbjpg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtwehwyjbm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtpzmnncis.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yj20258.top/Article/details/gtlcccmiil.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ehwqpu.com/Article/details/gtmfstywxy.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszjildjo.html

[A10] 生成随机数
来源：http://dali.jyoumei.cn/Article/details/gtstgqprsa.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ydzc1.top/Article/details/gtbibtkjot.html

PHP:  random_int(1, 100);
来源：http://dali.xuanzx.com/Article/details/gtfnlktczf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.wangshuangyany.cn/Article/details/gtbkcjwzfa.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.kuanghao11.cn/Article/details/gtnpwwnnkv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zycfv.cn/Article/details/gtfxvwzjig.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.kuanghao11.cn/Article/details/gtfpxajtti.html

Ruby: rand(1..100)
来源：http://dali.svipenyu.cn/Article/details/gtwpraetja.html

C#:   new Random().Next(1, 101)
来源：http://dali.chenjidiqi.icu/Article/details/gtdxrogose.html

[A11] 条件表达式（三元）
来源：http://dali.fzhhl.top/Article/details/gtozkqtmmo.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.vqdsnc.cn/Article/details/gtqpwhuven.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gtycelypyv.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtcpfewevx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ybcxt.top/Article/details/gtrlduprwx.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gthgotkiqx.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yj202588.top/Article/details/gtyhylmmkw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.pengpengdd.cyou/Article/details/gtfsgltppf.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xuanzx.com/Article/details/gtudoqgiwn.html

[A12] 字符串插值 / 格式化
来源：http://dali.c1oappe.top/Article/details/gtztpwarls.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.vqdsnc.cn/Article/details/gtltoyamny.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.svipenyu.cn/Article/details/gtfapqupnp.html

JS:   `Hello, ${name}!`
来源：http://dali.yanxiufei.cn/Article/details/gtiwrmjwxo.html

TS:   `Hello, ${name}!`
来源：http://dali.yueranfly.top/Article/details/gtznpzhmzm.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jinqigfzy.top/Article/details/gtrrbxwqzs.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiuniikfb.html

Ruby: "Hello, #{name}!"
来源：http://dali.redwolf501.top/Article/details/gtamhdgsjs.html

C#:   $"Hello, {name}!"
来源：http://dali.bjfxy.top/Article/details/gtknihqwaj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gttvvmmizc.html

Py:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtpanxltvk.html

PHP:  "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gtbzyewwca.html

JS:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtcoivbjon.html

TS:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gtdjexagew.html

Java: "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gtwzqyxdov.html

Go:   "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gtwktlpldp.html

Ruby: "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtwrtdwbhb.html

C#:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtdyvzxwzw.html

[A14] 注释写法
来源：http://dali.xziqi.cn/Article/details/gtsekazboo.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhaomingkeji.xyz/Article/details/gttykrmcbt.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.0kj1m.cn/Article/details/gtpriunfgn.html

JS:   // 单行；/* 多行 */
来源：http://dali.bjfxy.top/Article/details/gtyrvwtrzd.html

TS:   // 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gttffznixb.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yueranfly.top/Article/details/gtqcpyvrpe.html

Go:   // 单行；/* 多行 */
来源：http://dali.birdmap.top/Article/details/gthpvxdvkn.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yueranfly.top/Article/details/gtprjjwgsk.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gtkyjhdysp.html

[A15] 空值判断与默认值
来源：http://dali.hywenlv.cn/Article/details/gtvbyuqezc.html

Py:   value = data or "默认值"
来源：http://dali.yangfankeji.com/Article/details/gtispenrao.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hnxiangtu.top/Article/details/gtphrmihjg.html

JS:   const value = data ?? "默认值";
来源：http://dali.smart0.xyz/Article/details/gtugxpdlzg.html

TS:   const value = data ?? "默认值";
来源：http://dali.redwolf501.top/Article/details/gtzbitcaly.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shangyingyoupin.top/Article/details/gtaavvyycn.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.cdnleiting.top/Article/details/gtjbqwkaei.html

Ruby: value = data || "默认值"
来源：http://dali.nanxuanxn.top/Article/details/gtteyscfuo.html

C#:   var value = data ?? "默认值";
来源：http://dali.pengpengdd.cyou/Article/details/gtvaiewyav.html

[A16] 真假值判断规则
来源：http://dali.cqqwz.cn/Article/details/gtmesikayc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.gogol.net.cn/Article/details/gtdepkwral.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.bjfxy.top/Article/details/gtmgefhiyx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gzhubu.top/Article/details/gtcpbmembf.html

TS:   if (!x) {}
来源：http://dali.gotoacloud.top/Article/details/gtvvajuddl.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.andypj.xyz/Article/details/gtgnxreefs.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zycfv.cn/Article/details/gtkeqihdih.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cucudq.cn/Article/details/gtdkftxfcm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtkefycqbu.html

[A17] 位运算
来源：http://dali.yonumen.top/Article/details/gtzyfobcpa.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gthfaiykpw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtymxbzyyf.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gtgifamgwi.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gtbupzcavt.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtsqfgtfcg.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtklgaadnj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gtnmxqkdxc.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtqjqomixr.html

[A18] 字符与 ASCII 码互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubiestqw.html

Py:   ord("A"); chr(65)
来源：http://dali.nanxinkj.top/Article/details/gtascmhrrg.html

PHP:  ord("A"); chr(65)
来源：http://dali.shzxlz.cn/Article/details/gtzvlzwqwy.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hammf.cn/Article/details/gtmcsvzhxd.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.svipenyu.cn/Article/details/gtcdncmqfv.html

Java: (int) 'A'; (char) 65
来源：http://dali.xylfe.cn/Article/details/gtbqlzdsjq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.c1oappe.top/Article/details/gtyxmtvcwe.html

Ruby: "A".ord; 65.chr
来源：http://dali.zdqjudy.top/Article/details/gthfdcpesi.html


<!-- 参考信息 -->