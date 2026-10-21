代发 wailian999

[U105] JS：节流
来源：http://dali.jlsjyb.cn/Article/details/gtmcutejur.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hnxiangtu.top/Article/details/gtxerirene.html

[U106] JS：日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtlrukmzcu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xylfe.cn/Article/details/gtatqydptq.html

[U107] JS：数字千分位
来源：http://dali.fengsongda.top/Article/details/gtbpfoslhc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hammf.cn/Article/details/gttrewlesr.html

[U108] JS：随机整数
来源：http://dali.zhongyouzk.top/Article/details/gtxmaartdm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jianghu66.top/Article/details/gtuuivjgqq.html

[U109] JS：数组分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvfztywt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gtfuzehtau.html

[U110] JS：数组分块
来源：http://dali.yanxiufei.cn/Article/details/gtayvzzxct.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj202588.top/Article/details/gtxhwsgimq.html

[U111] JS：对象转 Map
来源：http://dali.zhongyouzk.top/Article/details/gtgdwttjta.html

new Map(Object.entries(obj))
来源：http://dali.redwolf501.top/Article/details/gtqaxzasun.html

[U112] JS：字符串补位
来源：http://dali.fengsongda.top/Article/details/gtgegjgwmh.html

"7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtggzkgxbq.html

[U113] JS：正则替换全部
来源：http://dali.jiagoushi.top/Article/details/gtfxnhczpt.html

s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtkkkywguo.html

[U114] JS：JSON 深比较
来源：http://dali.haohaochexian.top/Article/details/gtareghvjk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gtavruiiyx.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gtillibqab.html

crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtoveaueva.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yangfankeji.com/Article/details/gtezxagbyv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.fengsongda.top/Article/details/gtpyseaqvw.html

[U117] JS：单元测试
来源：http://dali.wangdashe.top/Article/details/gtmmlbpvxs.html

npm i -D vitest;  npx vitest
来源：http://dali.meibo888.top/Article/details/gthkxyzcok.html

[U118] JS：开发服务器
来源：http://dali.sysykeji.top/Article/details/gtkqngskmg.html

npm i -D vite;  npx vite
来源：http://dali.zhongyouzk.top/Article/details/gtfelnhjhl.html

[U119] JS：生产构建
来源：http://dali.hysaishi.cn/Article/details/gtuuryyupk.html

npx vite build
来源：http://dali.nanxinkj.top/Article/details/gtqzrvrhcu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.iojbl.cn/Article/details/gtmclyoksl.html

import.meta.env.VITE_API_URL
来源：http://dali.wangshuangyany.cn/Article/details/gtchsxvuwj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtzixxdwvi.html

统计汇总
来源：http://dali.shzxlz.cn/Article/details/gthjfkpuru.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtvwkklbzl.html

按语言统计（条）：
来源：http://dali.snrcjt.cn/Article/details/gtlwyvlxaa.html

Python ......... 252
来源：http://dali.zhongyouzk.top/Article/details/gthrrgcwyw.html

PHP ............ 252
来源：http://dali.9152youxi.cn/Article/details/gtnwgalnhk.html

JavaScript ..... 252
来源：http://dali.guowangkeji.top/Article/details/gtbduswekr.html

TypeScript ..... 212
来源：http://dali.xziqi.cn/Article/details/gtnirqmmgi.html

Java ........... 212
来源：http://dali.xuetiantiany.cn/Article/details/gtgjohqcfx.html

Go ............. 212
来源：http://dali.cucudq.cn/Article/details/gtqjcaoaem.html

Ruby ........... 212
来源：http://dali.sweek.top/Article/details/gthueupklw.html

C# ............. 212
来源：http://dali.0kj1m.cn/Article/details/gtcydxcvgr.html

C .............. 30
来源：http://dali.havefunace.top/Article/details/gtoundvtzb.html

C++ ............ 30
来源：http://dali.jqgfzy.top/Article/details/gtlomzzuft.html

SQL ............ 90
来源：http://dali.pengpengdd.cyou/Article/details/gtwrcogfcd.html

Bash ........... 80
来源：http://dali.cqqwz.cn/Article/details/gtovqtsced.html

Kotlin ......... 15
来源：http://dali.iojbl.cn/Article/details/gthmkubegl.html

Swift .......... 15
来源：http://dali.yangfankeji.com/Article/details/gtuedyjlmj.html

Lua ............ 10
来源：http://dali.cashguo.top/Article/details/gtumjmmiub.html

Perl ........... 10
来源：http://dali.vqdsnc.cn/Article/details/gttyydvzix.html

Scala .......... 10
来源：http://dali.zhixingplan.top/Article/details/gtsusymtjo.html

------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtvygejlch.html

合计 ........... 2106 条
来源：http://dali.yvedp.cn/Article/details/gtqxnizvqy.html

按章节统计：
来源：http://dali.svipenyu.cn/Article/details/gttsdtvdbt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gtlphoknem.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gtlknqwadr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gtixpujnqo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jyoumei.cn/Article/details/gtflrbfone.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajqmnipk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yj20258888.top/Article/details/gtrnrujnyx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj202588.top/Article/details/gtimiscfvi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cheryme.top/Article/details/gtmhfwetka.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gtosbkbbhj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gtoslnofxe.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gtywpiklfh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtcfcqlpfs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtfhvbqzbx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zdqjudy.top/Article/details/gtlwbhaojg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yonumen.top/Article/details/gtcgcdfnsq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtoxkpqxbj.html

Q SQL 专题                              90
来源：http://dali.jianghu66.top/Article/details/gtkyxsdioo.html

R Bash 专题                             80
来源：http://dali.hywenlv.cn/Article/details/gtcbismvxz.html

S C / C++ 专题                          60
来源：http://dali.chenlongwang.top/Article/details/gtpxtwbvwa.html

T 其他语言补充                          60
来源：http://dali.cheryme.top/Article/details/gtqpsvjpvy.html

U 高频实用片段                         120
来源：http://dali.dashuyun.cn/Article/details/gtaqopfgra.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gteqhxmiyx.html

合计                                  2106 条
来源：http://dali.jinqigfzy.top/Article/details/gtnmfneqbw.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtflfbmqkk.html

使用提醒
来源：http://dali.tian-w.cn/Article/details/gtvjkbojvh.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtpzyhtepm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.birdmap.top/Article/details/gtjxjqvepf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gotoacloud.top/Article/details/gtmtjhghsy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.dashuyun.cn/Article/details/gtbjsfcrsv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cheryme.top/Article/details/gtdnwmechb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.aizwys.cn/Article/details/gtecwdzhkx.html

—— 文件结束 ——
来源：http://dali.yuxming.cn/Article/details/gtikkyoicf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdajvsyev.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhengqikj.top/Article/details/gtcvyuebvf.html

Common Programming Examples Cheat Book
来源：http://dali.ivvv.top/Article/details/gtrbindysk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtdwenigwu.html

【收录内容】
来源：http://dali.yuanzhike.top/Article/details/gtwnvcjcfo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygucvamg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xinyue.icu/Article/details/gtczsraiiz.html

SQL · Bash · C · C++
来源：http://dali.c1oappe.top/Article/details/gtppcbpgdl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuksatcgb.html

【使用说明】
来源：http://dali.xinyue.icu/Article/details/gtmkrikmhb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.guannengcc.top/Article/details/gtfssazkkc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkbgtbtq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.iojbl.cn/Article/details/gtkdimtejl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gzhubu.top/Article/details/gthiccjsxd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.guannengcc.top/Article/details/gtllkivpfu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.haohaochexian.top/Article/details/gteuitjgew.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenzaomai.com/Article/details/gtrrxemgfg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gotoacloud.top/Article/details/gtxujraiad.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.0kj1m.cn/Article/details/gthjohmzmo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xylfe.cn/Article/details/gtieslwjtu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.316326.xyz/Article/details/gteppmasvh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gotoacloud.top/Article/details/gtxbjxgkbj.html

【文件统计】
来源：http://dali.cheryme.top/Article/details/gtoqpapxiw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ivvv.top/Article/details/gtszlhesrb.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gtvseoyrog.html

目  录
来源：http://dali.smart0.xyz/Article/details/gtuurnvapl.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gthyprmiiy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nanxinkj.top/Article/details/gtjelxddoz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gtxggpljir.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gtdjmvhunf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yuxming.cn/Article/details/gtewpujrti.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hywenlv.cn/Article/details/gttvulhfid.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shzxlz.cn/Article/details/gtmipkfeuf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gtxkotyqjl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.mhx1999.top/Article/details/gtdvieekfd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtyzvwutql.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.chenzaomai.com/Article/details/gtxloalbxz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gtgbogcufb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtzpgilbot.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gtlodfocgk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyrvkapd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.316326.xyz/Article/details/gtceivhuwv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gtgkbpiyov.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shzxlz.cn/Article/details/gthjzbpbsf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.iojbl.cn/Article/details/gtnlyawafv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jlsjyb.cn/Article/details/gtcslhopar.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gthhdhtdod.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gotoacloud.top/Article/details/gtvtnemgkf.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtrgovsfac.html

A. 基础语法与类型
来源：http://dali.shuidangran.top/Article/details/gtkglmnwea.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtqxukscpe.html

[A01] Hello World
来源：http://dali.bjfxy.top/Article/details/gtxcgqtrxd.html

Py:   print("Hello, World!")
来源：http://dali.yanxiufei.cn/Article/details/gtbserticd.html

PHP:  echo "Hello, World!";
来源：http://dali.birdmap.top/Article/details/gtkesmwahw.html

JS:   console.log("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gtwewhurfh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.guowangkeji.top/Article/details/gtjwrdwirh.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhgiwupp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenjidiqi.icu/Article/details/gtejbekgnw.html

Ruby: puts "Hello, World!"
来源：http://dali.cucudq.cn/Article/details/gtvrbwrqdm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jyoumei.cn/Article/details/gtnohajhdn.html

[A02] 变量声明与赋值
来源：http://dali.zhiwuduotai.top/Article/details/gtvenfbgup.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gotoacloud.top/Article/details/gtrfzmiqxy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.chenzaomai.com/Article/details/gtdcaguqsy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.aibaodan.cn/Article/details/gtuzhgiozy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhixingplan.top/Article/details/gttlaaurlc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ydzc1.top/Article/details/gtmebpouuu.html

Go:   name := "Alex"; age := 20
来源：http://dali.cucudq.cn/Article/details/gttsntqysn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jyoumei.cn/Article/details/gtfjvansok.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.andypj.xyz/Article/details/gtpoefilag.html

[A03] 常量定义
来源：http://dali.feifeiyinyue.top/Article/details/gtsmwhplps.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.dianchejie.cn/Article/details/gtszjrxkuk.html

PHP:  const PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtplmxwlen.html

JS:   const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtgmridwho.html

TS:   const PI: number = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtjmtphuww.html

Java: static final double PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtbxkmfdrh.html

Go:   const PI = 3.14159
来源：http://dali.jianghu66.top/Article/details/gtimpqtyau.html

Ruby: PI = 3.14159
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsendnchy.html

C#:   const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtisikobhf.html

[A04] 判断变量类型
来源：http://dali.aizwys.cn/Article/details/gtsbyqaywv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yvedp.cn/Article/details/gtfjjytzox.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gaohongyu789.top/Article/details/gtgrzuomgg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cashguo.top/Article/details/gtaozttldl.html

TS:   typeof x; x instanceof Date
来源：http://dali.svipenyu.cn/Article/details/gtbcqwjngy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sweek.top/Article/details/gthdvlxjrz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.0kj1m.cn/Article/details/gtwyjbrtsn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yueranfly.top/Article/details/gtexjcpfmw.html

C#:   x.GetType().Name; x is int
来源：http://dali.tian-w.cn/Article/details/gtacldnoon.html

[A05] 整数除法与取模
来源：http://dali.jlsjyb.cn/Article/details/gtexujcujy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.aizwys.cn/Article/details/gtqssslrrs.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtneevqihx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtmvdcrvmv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.daxiang520.top/Article/details/gtzoymqhvs.html

Java: 7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtyctkofsm.html

Go:   7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtayknkany.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gteheluhqr.html

C#:   7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtkuabxtrq.html

[A06] 字符串转数字
来源：http://dali.c1oappe.top/Article/details/gtnjqpddwa.html

Py:   int("42"); float("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpztslfnd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hnxiangtu.top/Article/details/gtncctctie.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.0kj1m.cn/Article/details/gtrcnkgzpf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.haohaochexian.top/Article/details/gtsohcundw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.smart0.xyz/Article/details/gthxpcfcaq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cucudq.cn/Article/details/gtucffuxqt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadcypgfl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xuanzx.com/Article/details/gtudlhbvlg.html

[A07] 数字转字符串
来源：http://dali.yuxming.cn/Article/details/gtmziipbdq.html

Py:   str(42)
来源：http://dali.dianchejie.cn/Article/details/gtapmqvpwc.html

PHP:  (string) 42; strval(42)
来源：http://dali.yuxming.cn/Article/details/gthravfwra.html

JS:   String(42); (42).toString()
来源：http://dali.redwolf501.top/Article/details/gtnsghonjd.html

TS:   String(42)
来源：http://dali.0kj1m.cn/Article/details/gteuckczwo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.haohaochexian.top/Article/details/gtainpcxwy.html

Go:   strconv.Itoa(42)
来源：http://dali.hnqzz.top/Article/details/gtjlsznonw.html

Ruby: 42.to_s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnpiudyq.html

C#:   42.ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtfoqxaose.html

[A08] 取整与四舍五入
来源：http://dali.quarkkingdee.top/Article/details/gtrmmbniui.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gtwrhnytex.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jlsjyb.cn/Article/details/gtpownfazr.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gtgiwexmts.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.wangdashe.top/Article/details/gtsqmhgefz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtlpipwxnh.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtofcfdbmz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yueranfly.top/Article/details/gthqoxfldq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gtspnqgzff.html

[A09] 绝对值与最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtbibzxcwo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpdzfucg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtmrwfvyyf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtxulpywri.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtooiixmbi.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtnqyxeklk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhixingplan.top/Article/details/gtuwcvrsbp.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrtgujjn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtgclcxlot.html

[A10] 生成随机数
来源：http://dali.kuanghao11.cn/Article/details/gtjhctydlm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.daria6918.cn/Article/details/gtvyroeykm.html

PHP:  random_int(1, 100);
来源：http://dali.0kj1m.cn/Article/details/gtcunxsyzk.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sweek.top/Article/details/gtjggpetds.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.wangdashe.top/Article/details/gtkiianewa.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfslfmjgp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gtielcpajb.html

Ruby: rand(1..100)
来源：http://dali.jlsjyb.cn/Article/details/gtievaeofc.html

C#:   new Random().Next(1, 101)
来源：http://dali.yuanzhike.top/Article/details/gtxehlfbph.html

[A11] 条件表达式（三元）
来源：http://dali.hongshengwenyu.top/Article/details/gtdnqlkilk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cheryme.top/Article/details/gtbieolbjy.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gtyjeoeubi.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gtrejbussl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gthsbzofjb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gtrnfwrrcv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.kuanghao11.cn/Article/details/gtuejkrrzj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gtnzyihkae.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gtswbeykym.html

[A12] 字符串插值 / 格式化
来源：http://dali.guannengcc.top/Article/details/gtjhvdhbbo.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.sufxvd.cn/Article/details/gtflzkgumq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.sysykeji.top/Article/details/gtqjczmvsp.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gtjzdgmzhk.html

TS:   `Hello, ${name}!`
来源：http://dali.yongpay.top/Article/details/gtbsdodmob.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhixingplan.top/Article/details/gteadnmgpl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ppjwa.cn/Article/details/gtqaoowqhf.html

Ruby: "Hello, #{name}!"
来源：http://dali.gotoacloud.top/Article/details/gtmgjuslwc.html

C#:   $"Hello, {name}!"
来源：http://dali.guowangkeji.top/Article/details/gtkizlehxz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.meibo888.top/Article/details/gtzzqdmvah.html

Py:   "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gtjjcelegl.html

PHP:  "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtaavejors.html

JS:   "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gttywwkgib.html

TS:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gtxjotpiyk.html

Java: "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gtdlffiymy.html

Go:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gtubjnxigw.html

Ruby: "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtxciebvyn.html

C#:   "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtomtsaawt.html

[A14] 注释写法
来源：http://dali.pengpengdd.cyou/Article/details/gtfnrkodpw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.tianlin.xyz/Article/details/gtxdretyyh.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yj20258.top/Article/details/gtmbyqsqps.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gtobimcezj.html

TS:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkujgocwn.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.andypj.xyz/Article/details/gtkdikpsdz.html

Go:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gthanihgqa.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.gzhubu.top/Article/details/gtevftqiqf.html

C#:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gtyiwwilzu.html

[A15] 空值判断与默认值
来源：http://dali.cdnleiting.top/Article/details/gtpmcpuzmn.html

Py:   value = data or "默认值"
来源：http://dali.chenjidiqi.icu/Article/details/gtzzhrgrnr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhoulong.xyz/Article/details/gtauewvjhf.html

JS:   const value = data ?? "默认值";
来源：http://dali.hysaishi.cn/Article/details/gtpakqlkzk.html

TS:   const value = data ?? "默认值";
来源：http://dali.dianchejie.cn/Article/details/gtluzuucxo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hammf.cn/Article/details/gtkxgufgas.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.meibo888.top/Article/details/gttwcsrgmh.html

Ruby: value = data || "默认值"
来源：http://dali.ivvv.top/Article/details/gttplqvgpw.html

C#:   var value = data ?? "默认值";
来源：http://dali.yonumen.top/Article/details/gtdzlpmnpg.html

[A16] 真假值判断规则
来源：http://dali.birdmap.top/Article/details/gtrgyeqbbd.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.c1oappe.top/Article/details/gtzdvbpcwr.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yj20258.top/Article/details/gtoryhcjtb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zycfv.cn/Article/details/gtgmcdbkeu.html

TS:   if (!x) {}
来源：http://dali.jinqigufen.top/Article/details/gtmctmmbyg.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.chenzaomai.com/Article/details/gtimuixxke.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.chenjidiqi.icu/Article/details/gtudinbvxt.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yuxming.cn/Article/details/gtzggzroqy.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shuidangran.top/Article/details/gtzcwgaqkl.html

[A17] 位运算
来源：http://dali.jinqigufen.top/Article/details/gtexmbccby.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gtgkfckojz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtnilofyhz.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtimgvhvze.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtvsgipknz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtmjxfhhsv.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtomdczslh.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtcclkwpup.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gtanvzhvrk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.tian-w.cn/Article/details/gtkumadmfe.html

Py:   ord("A"); chr(65)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwshntkyy.html

PHP:  ord("A"); chr(65)
来源：http://dali.pycfn.com/Article/details/gtciwqrgfd.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenjidiqi.icu/Article/details/gtbfqalyki.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hywenlv.cn/Article/details/gtrahmutap.html

Java: (int) 'A'; (char) 65
来源：http://dali.gogol.net.cn/Article/details/gtlwqbanua.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.316326.xyz/Article/details/gtvactgwib.html

Ruby: "A".ord; 65.chr
来源：http://dali.daria6918.cn/Article/details/gtuoncbquy.html


<!-- 参考信息 -->