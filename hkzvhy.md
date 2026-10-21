代发 wailian999

[U105] JS：节流
来源：http://dali.ehwqpu.com/Article/details/gtusxvymbs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirdtnugi.html

[U106] JS：日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaibugqjb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhengqikj.top/Article/details/gtmzvsowgr.html

[U107] JS：数字千分位
来源：http://dali.dashuyun.cn/Article/details/gtmdoukshq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cucudq.cn/Article/details/gtplvkmeop.html

[U108] JS：随机整数
来源：http://dali.zhengqikj.top/Article/details/gtdsbgryfq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dashuyun.cn/Article/details/gtjhfvditq.html

[U109] JS：数组分组
来源：http://dali.fengsongda.top/Article/details/gtrrcnerqn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gtsfynfjop.html

[U110] JS：数组分块
来源：http://dali.sufxvd.cn/Article/details/gtkrlcyodh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.svipenyu.cn/Article/details/gtgyeqvopv.html

[U111] JS：对象转 Map
来源：http://dali.cucudq.cn/Article/details/gtlyowtkns.html

new Map(Object.entries(obj))
来源：http://dali.yvedp.cn/Article/details/gtktenunrv.html

[U112] JS：字符串补位
来源：http://dali.yongpay.top/Article/details/gtsefefeha.html

"7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtgfhokfhz.html

[U113] JS：正则替换全部
来源：http://dali.zhengqikj.top/Article/details/gtrhyflfdx.html

s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtynuujcyu.html

[U114] JS：JSON 深比较
来源：http://dali.yanxiufei.cn/Article/details/gtwvzmvccc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gttvdlwnfq.html

[U115] JS：生成 UUID
来源：http://dali.sysykeji.top/Article/details/gtmtoriuua.html

crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtnodkppjy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.haohaochexian.top/Article/details/gttrgkzchb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtwgshpstt.html

[U117] JS：单元测试
来源：http://dali.zhengqikj.top/Article/details/gtvbzxwxsv.html

npm i -D vitest;  npx vitest
来源：http://dali.jlsjyb.cn/Article/details/gtkaemlkxs.html

[U118] JS：开发服务器
来源：http://dali.shuidangran.top/Article/details/gtulqfoddq.html

npm i -D vite;  npx vite
来源：http://dali.hywenlv.cn/Article/details/gtocezeavq.html

[U119] JS：生产构建
来源：http://dali.tian-w.cn/Article/details/gtmerxclqg.html

npx vite build
来源：http://dali.jinqigfzy.top/Article/details/gthlfgzvey.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hammf.cn/Article/details/gtlwgvrhwe.html

import.meta.env.VITE_API_URL
来源：http://dali.kuanghao11.cn/Article/details/gtitqxbwit.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtopipamgn.html

统计汇总
来源：http://dali.ehwqpu.com/Article/details/gtzgbijglp.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtuaulomem.html

按语言统计（条）：
来源：http://dali.iojbl.cn/Article/details/gtowwmkdib.html

Python ......... 252
来源：http://dali.xuanzx.com/Article/details/gtqlfdjuxe.html

PHP ............ 252
来源：http://dali.yvedp.cn/Article/details/gtagxiwlec.html

JavaScript ..... 252
来源：http://dali.cqqwz.cn/Article/details/gtcdxtpdld.html

TypeScript ..... 212
来源：http://dali.tian-w.cn/Article/details/gtninaqhee.html

Java ........... 212
来源：http://dali.gotoacloud.top/Article/details/gtdynpcswh.html

Go ............. 212
来源：http://dali.ppjwa.cn/Article/details/gtgkfqloqz.html

Ruby ........... 212
来源：http://dali.hysaishi.cn/Article/details/gtpnayqjtg.html

C# ............. 212
来源：http://dali.9152youxi.cn/Article/details/gtgstwzmun.html

C .............. 30
来源：http://dali.nwbrower.top/Article/details/gtqfdunalj.html

C++ ............ 30
来源：http://dali.chenzaomai.com/Article/details/gtuxnmjqgo.html

SQL ............ 90
来源：http://dali.xylfe.cn/Article/details/gtcypoizig.html

Bash ........... 80
来源：http://dali.feifeiyinyue.top/Article/details/gtdmysfvvp.html

Kotlin ......... 15
来源：http://dali.cdnleiting.top/Article/details/gtrfhzrfsb.html

Swift .......... 15
来源：http://dali.jinqigufen.top/Article/details/gtdolhwhyg.html

Lua ............ 10
来源：http://dali.316326.xyz/Article/details/gtdavkgfoa.html

Perl ........... 10
来源：http://dali.nwbrower.top/Article/details/gtobungvox.html

Scala .......... 10
来源：http://dali.yvedp.cn/Article/details/gtjzbosawc.html

------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtaljaqdiq.html

合计 ........... 2106 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxyxmjqo.html

按章节统计：
来源：http://dali.c1oappe.top/Article/details/gtnghgzyij.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqwmscbk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gturwovxae.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gtnpiyagkb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gtaqfyskdw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jianghu66.top/Article/details/gtgqddgfst.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hywenlv.cn/Article/details/gtzhrcpifq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gtqmnejkll.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenlongwang.top/Article/details/gtzqwfiuhs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtiqpuqjqp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.nanxinkj.top/Article/details/gtqxzwvytb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtwuzzolik.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtjxyhgerg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtqfricghv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.0kj1m.cn/Article/details/gtumfupqky.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.andypj.xyz/Article/details/gtnhsdxcyt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtwlezviwn.html

Q SQL 专题                              90
来源：http://dali.tian-w.cn/Article/details/gtmxqoizgz.html

R Bash 专题                             80
来源：http://dali.yuxming.cn/Article/details/gtolkqdtjj.html

S C / C++ 专题                          60
来源：http://dali.wangshuangyany.cn/Article/details/gtudhfdggn.html

T 其他语言补充                          60
来源：http://dali.yangfankeji.com/Article/details/gtyswqlqgu.html

U 高频实用片段                         120
来源：http://dali.wangdashe.top/Article/details/gtjewzbrlz.html

------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtvixrsjcz.html

合计                                  2106 条
来源：http://dali.zhixingplan.top/Article/details/gtehnkgnum.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnksjnreg.html

使用提醒
来源：http://dali.dianchejie.cn/Article/details/gtoslhkxnf.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gtoiuvepyi.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gogol.net.cn/Article/details/gthxlwslso.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zdqjudy.top/Article/details/gtnrazxtuz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cashguo.top/Article/details/gtjpyimrks.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinqigfzy.top/Article/details/gtppeinfpl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yangfankeji.com/Article/details/gtlxjucmoz.html

—— 文件结束 ——
来源：http://dali.andypj.xyz/Article/details/gtunrhwxzy.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfcshujzi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxkiqgwy.html

Common Programming Examples Cheat Book
来源：http://dali.pengpengdd.cyou/Article/details/gtkoupezdv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvdzbdjke.html

【收录内容】
来源：http://dali.yanxiufei.cn/Article/details/gtcawwxwrr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.aizwys.cn/Article/details/gthciwhhnm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.havefunace.top/Article/details/gtiauhpihq.html

SQL · Bash · C · C++
来源：http://dali.guowangkeji.top/Article/details/gtpxurkonq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gaohongyu789.top/Article/details/gtxmtyxspx.html

【使用说明】
来源：http://dali.havefunace.top/Article/details/gtglntgtwc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xuanzx.com/Article/details/gtqpwfrwnt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.vqdsnc.cn/Article/details/gtemmkwpge.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jianghu66.top/Article/details/gtynapjlmb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ppjwa.cn/Article/details/gtytuxpeof.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.iojbl.cn/Article/details/gtmzyfamnn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yvedp.cn/Article/details/gtoaggvhoc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shuidangran.top/Article/details/gtruazekky.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfchnklnr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ydzc1.top/Article/details/gtktpvbamv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhongyouzk.top/Article/details/gtdzmefxzu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jyoumei.cn/Article/details/gtsluxbdxy.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xinyue.icu/Article/details/gtmqcbyvxp.html

【文件统计】
来源：http://dali.yj20258888.top/Article/details/gtloopzdns.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ydzc1.top/Article/details/gtxjsdrwen.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtvjktawzw.html

目  录
来源：http://dali.zhiwuduotai.top/Article/details/gtpfcuiwek.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtqplolbli.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtfcvxabkt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvidkhzeq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gtzxztgehm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhixingplan.top/Article/details/gttkytgxin.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hfpthk.cn/Article/details/gtvvougpcs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtuakncekf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ivvv.top/Article/details/gtlitewxau.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.meibo888.top/Article/details/gtppxdafpg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gttitokhdk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hammf.cn/Article/details/gtoeyjrbmo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtjhywlogz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtwmtijnii.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gttasrpbjp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsrxnmuy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ivvv.top/Article/details/gtteyqacxd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gtixgndnsl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.aizwys.cn/Article/details/gtebhdlkvu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtrehdtfwi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zycfv.cn/Article/details/gtiaszbyhz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gtggxjbahm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj202588.top/Article/details/gtnhqrogii.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkkktmzlw.html

A. 基础语法与类型
来源：http://dali.nanxuanxn.top/Article/details/gtfgvtmymg.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtigzcvqky.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gthrbncast.html

Py:   print("Hello, World!")
来源：http://dali.quarkkingdee.top/Article/details/gtbqcnmmac.html

PHP:  echo "Hello, World!";
来源：http://dali.316326.xyz/Article/details/gthfgxrdpu.html

JS:   console.log("Hello, World!");
来源：http://dali.yueranfly.top/Article/details/gthndlmgtb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.chenlongwang.top/Article/details/gthwqdnoqh.html

Java: System.out.println("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gtoztfjijp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sysykeji.top/Article/details/gtzbsqgiee.html

Ruby: puts "Hello, World!"
来源：http://dali.ivvv.top/Article/details/gtmmqrrqip.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gtfotyumyf.html

[A02] 变量声明与赋值
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmkzahez.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.bjfxy.top/Article/details/gtuazzctbe.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj202588.top/Article/details/gtkteydxts.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nanxinkj.top/Article/details/gtescbfqug.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.0kj1m.cn/Article/details/gtgiwvmhwx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hammf.cn/Article/details/gtmwtyyxmk.html

Go:   name := "Alex"; age := 20
来源：http://dali.xuetiantiany.cn/Article/details/gtzahbmuoc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yongpay.top/Article/details/gtiwpnnpdk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yuanzhike.top/Article/details/gtkxaciwsd.html

[A03] 常量定义
来源：http://dali.xziqi.cn/Article/details/gtwmmktnyz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yonumen.top/Article/details/gtyshnngru.html

PHP:  const PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtgmvdnefw.html

JS:   const PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtglcsnpts.html

TS:   const PI: number = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtxigtazgu.html

Java: static final double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gthfwntxpm.html

Go:   const PI = 3.14159
来源：http://dali.cashguo.top/Article/details/gtbupfthkw.html

Ruby: PI = 3.14159
来源：http://dali.sxryk.cn/Article/details/gtagaessow.html

C#:   const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtrxddwcen.html

[A04] 判断变量类型
来源：http://dali.cqqwz.cn/Article/details/gtvonyinaq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hysaishi.cn/Article/details/gtxfrxlpmq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ivvv.top/Article/details/gtyigtzazi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xylfe.cn/Article/details/gtwuhujomx.html

TS:   typeof x; x instanceof Date
来源：http://dali.pycfn.com/Article/details/gtqyynffmx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.svipenyu.cn/Article/details/gttuqkrhcq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhixingplan.top/Article/details/gtyeupqcby.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.vqdsnc.cn/Article/details/gtuuyvcgpj.html

C#:   x.GetType().Name; x is int
来源：http://dali.ybcxt.top/Article/details/gtoqmgvcvh.html

[A05] 整数除法与取模
来源：http://dali.daxiang520.top/Article/details/gtoqxizhjt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gaohongyu789.top/Article/details/gtpplbyoyt.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtqcwiupee.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtfwcqofck.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvosrbvot.html

Java: 7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtjnknyxtn.html

Go:   7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtubgrqivh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtwbcokt.html

C#:   7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gtznjhnqub.html

[A06] 字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gtotqkxkmg.html

Py:   int("42"); float("3.14")
来源：http://dali.chenjidiqi.icu/Article/details/gtwzgzfibf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.c1oappe.top/Article/details/gtejpbgmqx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcprdkjad.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqpshqgf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.daxiang520.top/Article/details/gtxosdqeww.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cdnleiting.top/Article/details/gtbebsglff.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ehwqpu.com/Article/details/gtgkpacozk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yangfankeji.com/Article/details/gthqjlasqn.html

[A07] 数字转字符串
来源：http://dali.fengsongda.top/Article/details/gtapgailsi.html

Py:   str(42)
来源：http://dali.haohaochexian.top/Article/details/gtehbztmwh.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinqigfzy.top/Article/details/gtrkuoeypp.html

JS:   String(42); (42).toString()
来源：http://dali.pycfn.com/Article/details/gtoqclnuwd.html

TS:   String(42)
来源：http://dali.ybcxt.top/Article/details/gtplkopsvg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.fzhhl.top/Article/details/gtwvidoilc.html

Go:   strconv.Itoa(42)
来源：http://dali.kuanghao11.cn/Article/details/gtbyabzbjn.html

Ruby: 42.to_s
来源：http://dali.quarkkingdee.top/Article/details/gtmtfxjsmx.html

C#:   42.ToString()
来源：http://dali.smart0.xyz/Article/details/gtnjrlfmgz.html

[A08] 取整与四舍五入
来源：http://dali.jiagoushi.top/Article/details/gtjkxrgeyo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtrwzogcbb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.meibo888.top/Article/details/gtoglxnvgt.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.iojbl.cn/Article/details/gtlkeojxkc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhiwuduotai.top/Article/details/gthsplonro.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gthvmnhxsv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtmxzkzalb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinqigfzy.top/Article/details/gtacnansvi.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gttdjjenmu.html

[A09] 绝对值与最大最小值
来源：http://dali.shzxlz.cn/Article/details/gtkfdbwnsw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtrxggufnf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtwflbxtou.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtoppglbpy.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jianghu66.top/Article/details/gttjyuqjnr.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gtioorullj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.tian-w.cn/Article/details/gtuvcflspv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yvedp.cn/Article/details/gtwjbmpxik.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gthvectslc.html

[A10] 生成随机数
来源：http://dali.jinqigufen.top/Article/details/gtecqhufff.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cashguo.top/Article/details/gtjdpaqehz.html

PHP:  random_int(1, 100);
来源：http://dali.bjfxy.top/Article/details/gtbecqsttd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.316326.xyz/Article/details/gtwilqefiy.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jqgfzy.top/Article/details/gtbkmtiizt.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hywenlv.cn/Article/details/gtzbxnbhsu.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlffntfk.html

Ruby: rand(1..100)
来源：http://dali.0kj1m.cn/Article/details/gtkynheelm.html

C#:   new Random().Next(1, 101)
来源：http://dali.zycfv.cn/Article/details/gtkeuuxddm.html

[A11] 条件表达式（三元）
来源：http://dali.ybcxt.top/Article/details/gtmrzbxbir.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.nwbrower.top/Article/details/gtymbijzrk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtlggvwgun.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtzymjvlvf.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gtypumwlas.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gtxspiwqtq.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.quarkkingdee.top/Article/details/gttdbcmnpb.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.sweek.top/Article/details/gtvxsigzax.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gtpwgqkakn.html

[A12] 字符串插值 / 格式化
来源：http://dali.0kj1m.cn/Article/details/gtsmlvsekz.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj20258.top/Article/details/gtdjmxgodx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yongpay.top/Article/details/gtqshczlyw.html

JS:   `Hello, ${name}!`
来源：http://dali.gotoacloud.top/Article/details/gtoejytnos.html

TS:   `Hello, ${name}!`
来源：http://dali.guowangkeji.top/Article/details/gtegcjvzan.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.wangdashe.top/Article/details/gttdzohcvz.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.redwolf501.top/Article/details/gtrkmkczlg.html

Ruby: "Hello, #{name}!"
来源：http://dali.snrcjt.cn/Article/details/gtcuevrhqp.html

C#:   $"Hello, {name}!"
来源：http://dali.nanxinkj.top/Article/details/gtrxwyzyqz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.chenjidiqi.icu/Article/details/gtzfgtmxyk.html

Py:   "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtkkedpnrj.html

PHP:  "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gtkmkjmvtv.html

JS:   "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gtxpkfaznq.html

TS:   "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gtrgulchkf.html

Java: "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtnktxuztv.html

Go:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtoahrbjwe.html

Ruby: "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtuishnwkl.html

C#:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gttsgsplgf.html

[A14] 注释写法
来源：http://dali.cdnleiting.top/Article/details/gtpwhcdizs.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.sufxvd.cn/Article/details/gtzmolknby.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gtmgiwmgdz.html

JS:   // 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gtkiigihte.html

TS:   // 单行；/* 多行 */
来源：http://dali.0kj1m.cn/Article/details/gtrmoangyw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.aizwys.cn/Article/details/gtnuenauuy.html

Go:   // 单行；/* 多行 */
来源：http://dali.chenlongwang.top/Article/details/gtyqiggvpv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhongyouzk.top/Article/details/gtwxdpywyl.html

C#:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gtowxmqvyf.html

[A15] 空值判断与默认值
来源：http://dali.hnqzz.top/Article/details/gtsnnbznvh.html

Py:   value = data or "默认值"
来源：http://dali.yueranfly.top/Article/details/gtuwzfhufe.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.aibaodan.cn/Article/details/gtpemfwamb.html

JS:   const value = data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gtpnxelpub.html

TS:   const value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gtnmypitqs.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.bjfxy.top/Article/details/gtjjexshjh.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.aizwys.cn/Article/details/gtugfsbpzu.html

Ruby: value = data || "默认值"
来源：http://dali.zdqjudy.top/Article/details/gtvdkzptvj.html

C#:   var value = data ?? "默认值";
来源：http://dali.nwbrower.top/Article/details/gtfaoqxgdk.html

[A16] 真假值判断规则
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbarymos.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.aibaodan.cn/Article/details/gtyebapmmb.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.vqdsnc.cn/Article/details/gtkipaubni.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gzhubu.top/Article/details/gtbczxefil.html

TS:   if (!x) {}
来源：http://dali.guannengcc.top/Article/details/gttfrbgpfc.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.andypj.xyz/Article/details/gtdochiyla.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.bjfxy.top/Article/details/gtajpgaoot.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xinyue.icu/Article/details/gtfaoirbcf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvwyxkgl.html

[A17] 位运算
来源：http://dali.hnqzz.top/Article/details/gtsrdcrvxi.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gthmsvonem.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yj20258.top/Article/details/gtsknnrzvg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gtteibkmoi.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gtpamcqbbi.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtckrcplwk.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtrcorapuf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gtjghdkmob.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtyyfokcsh.html

[A18] 字符与 ASCII 码互转
来源：http://dali.feifeiyinyue.top/Article/details/gtiesicfyr.html

Py:   ord("A"); chr(65)
来源：http://dali.sweek.top/Article/details/gthrmkqntj.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gtljenuplq.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nwbrower.top/Article/details/gthuklzpfw.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gaohongyu789.top/Article/details/gtppelgoet.html

Java: (int) 'A'; (char) 65
来源：http://dali.xziqi.cn/Article/details/gthcekhgxt.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhiwuduotai.top/Article/details/gtrkrpuxbt.html

Ruby: "A".ord; 65.chr
来源：http://dali.aizwys.cn/Article/details/gtupgmmvkj.html


<!-- 参考信息 -->