代发 wailian999

[U105] JS：节流
来源：http://dali.sysykeji.top/Article/details/gtcdnsooet.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtuazztbzn.html

[U106] JS：日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtwthlrglu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.pycfn.com/Article/details/gtwercfcqh.html

[U107] JS：数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixqqvkut.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.birdmap.top/Article/details/gtxzasqlbe.html

[U108] JS：随机整数
来源：http://dali.sysykeji.top/Article/details/gtjclgoqeb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dianchejie.cn/Article/details/gtuqwuqbtp.html

[U109] JS：数组分组
来源：http://dali.zhoulong.xyz/Article/details/gtiyuprter.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtnzxslwxa.html

[U110] JS：数组分块
来源：http://dali.yj20258.top/Article/details/gtghmewfim.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.iojbl.cn/Article/details/gtuijkipxj.html

[U111] JS：对象转 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvrnlbzu.html

new Map(Object.entries(obj))
来源：http://dali.jqgufenzy.top/Article/details/gttvdnvqgq.html

[U112] JS：字符串补位
来源：http://dali.hnqzz.top/Article/details/gtzpscqqhy.html

"7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtxnwhfyin.html

[U113] JS：正则替换全部
来源：http://dali.ppjwa.cn/Article/details/gtwcmxrryr.html

s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtrpielxrh.html

[U114] JS：JSON 深比较
来源：http://dali.sweek.top/Article/details/gtdapbeymn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtkxjyckyx.html

[U115] JS：生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gtuvqnkiuz.html

crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtjleyuruj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jyoumei.cn/Article/details/gthxugxiis.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yonumen.top/Article/details/gtrcouhmiw.html

[U117] JS：单元测试
来源：http://dali.zycfv.cn/Article/details/gtvuhdyhaz.html

npm i -D vitest;  npx vitest
来源：http://dali.cqqwz.cn/Article/details/gtdpqwkjul.html

[U118] JS：开发服务器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyjwtxjg.html

npm i -D vite;  npx vite
来源：http://dali.hammf.cn/Article/details/gtowbohmnd.html

[U119] JS：生产构建
来源：http://dali.yj202588.top/Article/details/gtyxpvquor.html

npx vite build
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpsafuvx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenjidiqi.icu/Article/details/gtmjubicmc.html

import.meta.env.VITE_API_URL
来源：http://dali.sufxvd.cn/Article/details/gtbzqvvhzj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtgjidlmak.html

统计汇总
来源：http://dali.dianchejie.cn/Article/details/gtckpzjzpn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtdyelmyae.html

按语言统计（条）：
来源：http://dali.jinghuilouyu.cn/Article/details/gtaoywnrzv.html

Python ......... 252
来源：http://dali.zhixingplan.top/Article/details/gtfppxcnkd.html

PHP ............ 252
来源：http://dali.jianghu66.top/Article/details/gtipustbpb.html

JavaScript ..... 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbrlqltd.html

TypeScript ..... 212
来源：http://dali.yuxming.cn/Article/details/gtelvbjpsi.html

Java ........... 212
来源：http://dali.cheryme.top/Article/details/gtgqwmhpfk.html

Go ............. 212
来源：http://dali.yuanzhike.top/Article/details/gtmpcgrvts.html

Ruby ........... 212
来源：http://dali.daxiang520.top/Article/details/gththqivmr.html

C# ............. 212
来源：http://dali.yj202588.top/Article/details/gtkvigrukg.html

C .............. 30
来源：http://dali.xuanzx.com/Article/details/gtpbehwual.html

C++ ............ 30
来源：http://dali.pengpengdd.cyou/Article/details/gtudqznrhf.html

SQL ............ 90
来源：http://dali.316326.xyz/Article/details/gtgwopljdf.html

Bash ........... 80
来源：http://dali.iojbl.cn/Article/details/gtrwzbnean.html

Kotlin ......... 15
来源：http://dali.mhx1999.top/Article/details/gtdjqeylgb.html

Swift .......... 15
来源：http://dali.cqqwz.cn/Article/details/gtbnlplpod.html

Lua ............ 10
来源：http://dali.tanke756.top/Article/details/gtwwzjlhdk.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gtwipnwaoz.html

Scala .......... 10
来源：http://dali.sweek.top/Article/details/gtikosypyv.html

------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscqhfrsm.html

合计 ........... 2106 条
来源：http://dali.zdqjudy.top/Article/details/gtatymbkym.html

按章节统计：
来源：http://dali.andypj.xyz/Article/details/gtgukbfnei.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.dashuyun.cn/Article/details/gtgqyxwxzg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gtsbaxhcwq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpgpqtyu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.daria6918.cn/Article/details/gtkzzizkwi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zdqjudy.top/Article/details/gtmgcawghg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xuanzx.com/Article/details/gttriblobi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gtsxdjepnb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xuanzx.com/Article/details/gtzvsobatc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gthmxxhjcj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.bjfxy.top/Article/details/gtysfbetff.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gttxpwjwpn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtsvranwsd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtalpkkxxm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.aibaodan.cn/Article/details/gtdiysuahb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hfpthk.cn/Article/details/gtijaowzph.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtllztgbty.html

Q SQL 专题                              90
来源：http://dali.xylfe.cn/Article/details/gtcpotodqy.html

R Bash 专题                             80
来源：http://dali.cqqwz.cn/Article/details/gthvykwtah.html

S C / C++ 专题                          60
来源：http://dali.cqqwz.cn/Article/details/gtxuqytxld.html

T 其他语言补充                          60
来源：http://dali.wangshuangyany.cn/Article/details/gttwbdjymi.html

U 高频实用片段                         120
来源：http://dali.316326.xyz/Article/details/gtfshtgzjr.html

------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtrbarjkjy.html

合计                                  2106 条
来源：http://dali.daxiang520.top/Article/details/gthruetald.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtugywbmfq.html

使用提醒
来源：http://dali.xylfe.cn/Article/details/gtddttkvzg.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtdgxnlnys.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cqqwz.cn/Article/details/gtzgubxejm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xziqi.cn/Article/details/gtonhlaqoj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gtptrvkyis.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nanxinkj.top/Article/details/gttyqvzkba.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yvedp.cn/Article/details/gtxoobnkoa.html

—— 文件结束 ——
来源：http://dali.jinqigfzy.top/Article/details/gtndziwbmb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtxljowhrw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhengqikj.top/Article/details/gtahsiqzkh.html

Common Programming Examples Cheat Book
来源：http://dali.sysykeji.top/Article/details/gtoqbiajib.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqymxkaui.html

【收录内容】
来源：http://dali.fzhhl.top/Article/details/gtxzrogqwb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hnqzz.top/Article/details/gteutkhcpx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.snrcjt.cn/Article/details/gtcfmqmzjg.html

SQL · Bash · C · C++
来源：http://dali.chenjidiqi.icu/Article/details/gtkusznhwa.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.tanke756.top/Article/details/gtznstphrr.html

【使用说明】
来源：http://dali.birdmap.top/Article/details/gtsqpcmrig.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tian-w.cn/Article/details/gturxolfyi.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.wangdashe.top/Article/details/gtwilqqsnz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.pengpengdd.cyou/Article/details/gtjfwoxpft.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gaohongyu789.top/Article/details/gtmnrfgvys.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.fzhhl.top/Article/details/gtsrtboeev.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.fengsongda.top/Article/details/gtoyuybuje.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nanxuanxn.top/Article/details/gtrzwiphai.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ppjwa.cn/Article/details/gtsypuevfm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cucudq.cn/Article/details/gtqixsxzjj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nwbrower.top/Article/details/gtpdaishnm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.nanxinkj.top/Article/details/gtmjzevnfp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cqqwz.cn/Article/details/gtmrsfrzbe.html

【文件统计】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjjeltbx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yongpay.top/Article/details/gtitnrrtdx.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gtjuwjhuld.html

目  录
来源：http://dali.ydzc1.top/Article/details/gtjaftyour.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gtwvfdiuyy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gtkphzcxld.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gtvxrykpnd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gtskhchbor.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gogol.net.cn/Article/details/gtxqyiofuz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gtnpkulcxw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gtdkemfnto.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gtsylanjfo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gogol.net.cn/Article/details/gtnjsgtkas.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtvxprkhgv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.pycfn.com/Article/details/gtuzpmorzj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gterhwohyy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gtpoudtdvn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtpabsuwfa.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cucudq.cn/Article/details/gtrgjzgvip.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtltbsygxy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtucpmvmuq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hfpthk.cn/Article/details/gthuonqhdr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtpaminkax.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yj20258.top/Article/details/gtdiommgbv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.316326.xyz/Article/details/gtdpefdpzh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cdnleiting.top/Article/details/gtrprxjsex.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbfjsccpa.html

A. 基础语法与类型
来源：http://dali.mhx1999.top/Article/details/gtvczneexm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytnagqlw.html

[A01] Hello World
来源：http://dali.hammf.cn/Article/details/gtixqlgeso.html

Py:   print("Hello, World!")
来源：http://dali.xinyue.icu/Article/details/gtzabfkwdx.html

PHP:  echo "Hello, World!";
来源：http://dali.zdqjudy.top/Article/details/gtzqyugkql.html

JS:   console.log("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjouzhgu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sxryk.cn/Article/details/gttgxtretz.html

Java: System.out.println("Hello, World!");
来源：http://dali.c1oappe.top/Article/details/gtgvflqgmk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.316326.xyz/Article/details/gtbsovpwsr.html

Ruby: puts "Hello, World!"
来源：http://dali.hnxiangtu.top/Article/details/gtuhydodcq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gtyjwjqexx.html

[A02] 变量声明与赋值
来源：http://dali.nwbrower.top/Article/details/gtvaxveyjz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ybcxt.top/Article/details/gtxxckhjzw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtedcvsamw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yueranfly.top/Article/details/gtjruwexjd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jianghu66.top/Article/details/gtijpihknl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtbisykjxp.html

Go:   name := "Alex"; age := 20
来源：http://dali.shanyushiyangtech.top/Article/details/gtueedvnqt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ehwqpu.com/Article/details/gtkaxdtbfx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jyoumei.cn/Article/details/gtbhfkrjoz.html

[A03] 常量定义
来源：http://dali.yanxiufei.cn/Article/details/gtrfguhwut.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ehwqpu.com/Article/details/gtaijpbfgn.html

PHP:  const PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtludhxeie.html

JS:   const PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtoifiypxp.html

TS:   const PI: number = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtysayniwp.html

Java: static final double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtazsismoi.html

Go:   const PI = 3.14159
来源：http://dali.sweek.top/Article/details/gtisvsxtba.html

Ruby: PI = 3.14159
来源：http://dali.cashguo.top/Article/details/gtpaqmlzup.html

C#:   const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtezawxace.html

[A04] 判断变量类型
来源：http://dali.daxiang520.top/Article/details/gtdligxbor.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gaohongyu789.top/Article/details/gtqufvbsje.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxltxztjo.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hongshengwenyu.top/Article/details/gtlucfdfxm.html

TS:   typeof x; x instanceof Date
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwcyueof.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.c1oappe.top/Article/details/gtlsmsajyc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jlsjyb.cn/Article/details/gtxsaifoqr.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gzhubu.top/Article/details/gtiqngnczy.html

C#:   x.GetType().Name; x is int
来源：http://dali.sufxvd.cn/Article/details/gtrtrpxuyr.html

[A05] 整数除法与取模
来源：http://dali.vqdsnc.cn/Article/details/gtwokdofxp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.svipenyu.cn/Article/details/gtuqdwjspp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtwcbyjxkm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtvndmhijx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gthitbobmd.html

Java: 7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtbcmesrch.html

Go:   7 / 2; 7 % 2
来源：http://dali.birdmap.top/Article/details/gtjyjvljfy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtffzrjipz.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtyhtcowhj.html

[A06] 字符串转数字
来源：http://dali.andypj.xyz/Article/details/gtpvjigxzg.html

Py:   int("42"); float("3.14")
来源：http://dali.daxiang520.top/Article/details/gtgnqztawp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yangfankeji.com/Article/details/gtmebrqwoe.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jqgufenzy.top/Article/details/gtodxnccng.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cashguo.top/Article/details/gtferjnbzd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.iojbl.cn/Article/details/gtnzchabyu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cashguo.top/Article/details/gtzwrdrkmw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.vqdsnc.cn/Article/details/gthudrvrud.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nanxinkj.top/Article/details/gtvyteuyky.html

[A07] 数字转字符串
来源：http://dali.xuanzx.com/Article/details/gtolabjbws.html

Py:   str(42)
来源：http://dali.yvedp.cn/Article/details/gtzruqhftv.html

PHP:  (string) 42; strval(42)
来源：http://dali.chenzaomai.com/Article/details/gtobzoahsp.html

JS:   String(42); (42).toString()
来源：http://dali.birdmap.top/Article/details/gtctyjcthq.html

TS:   String(42)
来源：http://dali.smart0.xyz/Article/details/gttiqjwizi.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yonumen.top/Article/details/gtjnpernyd.html

Go:   strconv.Itoa(42)
来源：http://dali.havefunace.top/Article/details/gtscclzgdt.html

Ruby: 42.to_s
来源：http://dali.zdqjudy.top/Article/details/gtqpgdzxqe.html

C#:   42.ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxymviom.html

[A08] 取整与四舍五入
来源：http://dali.smart0.xyz/Article/details/gtrrptcrha.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtzgvorfty.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jyoumei.cn/Article/details/gtkrrjmiuh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtaqytmuaz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.smart0.xyz/Article/details/gtguxbwzzo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.birdmap.top/Article/details/gtcehybooa.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gtnzjyxxfo.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.316326.xyz/Article/details/gtdtlbnnbl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gtnezyxpok.html

[A09] 绝对值与最大最小值
来源：http://dali.yuanzhike.top/Article/details/gtelskdkis.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtrctzzknr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hammf.cn/Article/details/gtafwxfipi.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtvckdmgei.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmimvvaf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtsocpbemw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yuanzhike.top/Article/details/gtaxiqvuye.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jinqigfzy.top/Article/details/gtmzyazprj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtybjrdcob.html

[A10] 生成随机数
来源：http://dali.ybcxt.top/Article/details/gtbqbgakjl.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yongpay.top/Article/details/gtwhqjpmlx.html

PHP:  random_int(1, 100);
来源：http://dali.guannengcc.top/Article/details/gtcuffzufc.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hfpthk.cn/Article/details/gtgiyukylx.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gotoacloud.top/Article/details/gtnmkgbnwc.html

Java: new Random().nextInt(100) + 1
来源：http://dali.guowangkeji.top/Article/details/gtzatbthbw.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.sysykeji.top/Article/details/gtbobnmash.html

Ruby: rand(1..100)
来源：http://dali.ivvv.top/Article/details/gtgqkkguib.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhongyouzk.top/Article/details/gtiaxkcmpq.html

[A11] 条件表达式（三元）
来源：http://dali.vqdsnc.cn/Article/details/gtkmkmncae.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtphxsiqoe.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gtsozycxlb.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gtuemkzkbf.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xuanzx.com/Article/details/gtdzirijob.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtcjvdkybc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.guannengcc.top/Article/details/gtqiytcodc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtoywcissz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gtkerrfkaw.html

[A12] 字符串插值 / 格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgotwtme.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.andypj.xyz/Article/details/gtlvmwziij.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yvedp.cn/Article/details/gtkwwwifuc.html

JS:   `Hello, ${name}!`
来源：http://dali.hongshengwenyu.top/Article/details/gtszqfnidy.html

TS:   `Hello, ${name}!`
来源：http://dali.shangyingyoupin.top/Article/details/gtvkljjzwc.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.pycfn.com/Article/details/gtqsuptrso.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zdqjudy.top/Article/details/gtcanbrsnc.html

Ruby: "Hello, #{name}!"
来源：http://dali.gogol.net.cn/Article/details/gtlefiybpf.html

C#:   $"Hello, {name}!"
来源：http://dali.redwolf501.top/Article/details/gtgivrmvoh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yueranfly.top/Article/details/gtrjsulazw.html

Py:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gthjmcpzsk.html

PHP:  "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gtzyxnzyeb.html

JS:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtejtosgao.html

TS:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtqxbhgqpj.html

Java: "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gtwqpcpbdu.html

Go:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtqbfdwuse.html

Ruby: "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtsgokcaco.html

C#:   "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gtbrkxdexq.html

[A14] 注释写法
来源：http://dali.iojbl.cn/Article/details/gtkcfwrqdz.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zycfv.cn/Article/details/gtvhidcweo.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.cheryme.top/Article/details/gtamvnpggr.html

JS:   // 单行；/* 多行 */
来源：http://dali.fzhhl.top/Article/details/gtrvmvickf.html

TS:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gthohprutk.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yongpay.top/Article/details/gtwjcwhjci.html

Go:   // 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gtrzpymaod.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhongyouzk.top/Article/details/gtaqnjmyhi.html

C#:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gtrtajrfqq.html

[A15] 空值判断与默认值
来源：http://dali.bjfxy.top/Article/details/gthgaretmq.html

Py:   value = data or "默认值"
来源：http://dali.tanke756.top/Article/details/gtbybcfgxm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yj202588.top/Article/details/gtvcqwovst.html

JS:   const value = data ?? "默认值";
来源：http://dali.c1oappe.top/Article/details/gtotefhtlq.html

TS:   const value = data ?? "默认值";
来源：http://dali.guannengcc.top/Article/details/gtklcnwtnr.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ydzc1.top/Article/details/gtpyusmljc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.gotoacloud.top/Article/details/gtqchkeqmx.html

Ruby: value = data || "默认值"
来源：http://dali.xziqi.cn/Article/details/gtighqzfdk.html

C#:   var value = data ?? "默认值";
来源：http://dali.dianchejie.cn/Article/details/gtmrobyxsq.html

[A16] 真假值判断规则
来源：http://dali.bjfxy.top/Article/details/gtjywielaf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.chenlongwang.top/Article/details/gtndcpgfgy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jlsjyb.cn/Article/details/gtidiyvhpq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jqgufenzy.top/Article/details/gtkxnqrmcf.html

TS:   if (!x) {}
来源：http://dali.jinqigfzy.top/Article/details/gtfswdulvj.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hammf.cn/Article/details/gtvhchscjr.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.nwbrower.top/Article/details/gtrqibxzvy.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.chenlongwang.top/Article/details/gtgzanmtus.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtcasnvwml.html

[A17] 位运算
来源：http://dali.hysaishi.cn/Article/details/gtynapgsoh.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gtujkpyaer.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuesgqvt.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gtxlgemwms.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gtzrqvflbb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtfjrqasoo.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gtsfbezmjo.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gtjtazgunt.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtctjroeep.html

[A18] 字符与 ASCII 码互转
来源：http://dali.xziqi.cn/Article/details/gtawnxkhsu.html

Py:   ord("A"); chr(65)
来源：http://dali.hnqzz.top/Article/details/gtabpczatn.html

PHP:  ord("A"); chr(65)
来源：http://dali.snrcjt.cn/Article/details/gtlfvcbszk.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zycfv.cn/Article/details/gtseyjwvgt.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.c1oappe.top/Article/details/gtnfiwzmrw.html

Java: (int) 'A'; (char) 65
来源：http://dali.guowangkeji.top/Article/details/gteoqjvker.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yj20258888.top/Article/details/gtvxjjwcyq.html

Ruby: "A".ord; 65.chr
来源：http://dali.smart0.xyz/Article/details/gtowauzwmd.html


<!-- 参考信息 -->