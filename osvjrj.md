代发 wailian999

[U103] JS：定时器
来源：http://dali.redwolf501.top/Article/details/gtnobwsqwp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.daxiang520.top/Article/details/gtwusgtrel.html

[U104] JS：防抖
来源：http://dali.jqgufenzy.top/Article/details/gtleyooazw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gtcldnzwbd.html

[U105] JS：节流
来源：http://dali.xinyue.icu/Article/details/gtgunpjlpp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.havefunace.top/Article/details/gtxqleoowo.html

[U106] JS：日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtdlsedbde.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.nwbrower.top/Article/details/gtdhnzwjqv.html

[U107] JS：数字千分位
来源：http://dali.yj202588.top/Article/details/gtmdunhwzz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtadgqxsve.html

[U108] JS：随机整数
来源：http://dali.yangfankeji.com/Article/details/gtrikxpbhh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xinyue.icu/Article/details/gtyzuyiric.html

[U109] JS：数组分组
来源：http://dali.cdnleiting.top/Article/details/gtvxjihmvv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtyiejntfs.html

[U110] JS：数组分块
来源：http://dali.chenjidiqi.icu/Article/details/gtvsreqyli.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xuanzx.com/Article/details/gtqswnqkjg.html

[U111] JS：对象转 Map
来源：http://dali.fengsongda.top/Article/details/gtzqpzazjz.html

new Map(Object.entries(obj))
来源：http://dali.mhx1999.top/Article/details/gtuhsipias.html

[U112] JS：字符串补位
来源：http://dali.pengpengdd.cyou/Article/details/gtodsgvrma.html

"7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtaprgumts.html

[U113] JS：正则替换全部
来源：http://dali.bjfxy.top/Article/details/gtaooycads.html

s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtqpmxippm.html

[U114] JS：JSON 深比较
来源：http://dali.yj20258.top/Article/details/gtnpvmlxkl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirmxjala.html

[U115] JS：生成 UUID
来源：http://dali.bjfxy.top/Article/details/gtcvqoyhxj.html

crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtvfafzqsp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.feifeiyinyue.top/Article/details/gtbptnoxkr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xziqi.cn/Article/details/gtxxsfyepv.html

[U117] JS：单元测试
来源：http://dali.zycfv.cn/Article/details/gtnvktpxhl.html

npm i -D vitest;  npx vitest
来源：http://dali.yanxiufei.cn/Article/details/gtuqujetyz.html

[U118] JS：开发服务器
来源：http://dali.wangshuangyany.cn/Article/details/gtmqrqgfpy.html

npm i -D vite;  npx vite
来源：http://dali.zhongyouzk.top/Article/details/gtysmtprog.html

[U119] JS：生产构建
来源：http://dali.yj20258888.top/Article/details/gtqiztnofb.html

npx vite build
来源：http://dali.sweek.top/Article/details/gtcgsqaavx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.meibo888.top/Article/details/gthjnhidvp.html

import.meta.env.VITE_API_URL
来源：http://dali.jlsjyb.cn/Article/details/gtsdfwctyt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqeewlbsc.html

统计汇总
来源：http://dali.aibaodan.cn/Article/details/gtprjrvfpm.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtqfviobxh.html

按语言统计（条）：
来源：http://dali.jiagoushi.top/Article/details/gtqerphann.html

Python ......... 252
来源：http://dali.sweek.top/Article/details/gtuyhztmea.html

PHP ............ 252
来源：http://dali.zdqjudy.top/Article/details/gtcyvsxtbp.html

JavaScript ..... 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbojvhqu.html

TypeScript ..... 212
来源：http://dali.snrcjt.cn/Article/details/gtjgsxnlld.html

Java ........... 212
来源：http://dali.aizwys.cn/Article/details/gtehagtlyk.html

Go ............. 212
来源：http://dali.wangdashe.top/Article/details/gtvbtzsxdr.html

Ruby ........... 212
来源：http://dali.ppjwa.cn/Article/details/gtmnjwrzkg.html

C# ............. 212
来源：http://dali.zhoulong.xyz/Article/details/gttcjfmbgr.html

C .............. 30
来源：http://dali.gotoacloud.top/Article/details/gtjmmokahu.html

C++ ............ 30
来源：http://dali.yuanzhike.top/Article/details/gtclixagyy.html

SQL ............ 90
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytzbmhjf.html

Bash ........... 80
来源：http://dali.shuidangran.top/Article/details/gtucffybtz.html

Kotlin ......... 15
来源：http://dali.iojbl.cn/Article/details/gtwwmufhot.html

Swift .......... 15
来源：http://dali.gogol.net.cn/Article/details/gtgdriyohl.html

Lua ............ 10
来源：http://dali.hongshengwenyu.top/Article/details/gtktvazhny.html

Perl ........... 10
来源：http://dali.havefunace.top/Article/details/gthstuzxme.html

Scala .......... 10
来源：http://dali.hnxiangtu.top/Article/details/gtyyfgodjo.html

------------------------------------
来源：http://dali.yj202588.top/Article/details/gtukjmqpfs.html

合计 ........... 2106 条
来源：http://dali.wangdashe.top/Article/details/gtldtagwqv.html

按章节统计：
来源：http://dali.chenjidiqi.icu/Article/details/gtfigzlgfn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gtdtylfosq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gtxcbocnhw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtobxqlviz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.dashuyun.cn/Article/details/gtwugethbn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gogol.net.cn/Article/details/gtjxqbwloi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.mhx1999.top/Article/details/gtapozfflg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtseaxbgcj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.birdmap.top/Article/details/gtalhklxse.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtgpmdouuj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gtszeotefp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gthkftaaql.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gtzcjrbgki.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtxrzumtsw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cheryme.top/Article/details/gtshkpnyne.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gtfdyydxno.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtpjkyqzgm.html

Q SQL 专题                              90
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwovqqjqd.html

R Bash 专题                             80
来源：http://dali.gotoacloud.top/Article/details/gtsyzssvix.html

S C / C++ 专题                          60
来源：http://dali.ehwqpu.com/Article/details/gtzfdatjlr.html

T 其他语言补充                          60
来源：http://dali.meibo888.top/Article/details/gtfyianlje.html

U 高频实用片段                         120
来源：http://dali.zdqjudy.top/Article/details/gtpoiqcnuf.html

------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtcknyvhau.html

合计                                  2106 条
来源：http://dali.bjfxy.top/Article/details/gtwxmotzah.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtkiywplwl.html

使用提醒
来源：http://dali.kuanghao11.cn/Article/details/gtsmmhdgul.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gtrsnocrez.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hongshengwenyu.top/Article/details/gtxyurwlpy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cucudq.cn/Article/details/gtrjzfrfkt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhongyouzk.top/Article/details/gtpybfairl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yj20258.top/Article/details/gtpthnhjmi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cashguo.top/Article/details/gtyymijkvp.html

—— 文件结束 ——
来源：http://dali.zhaomingkeji.xyz/Article/details/gthesqtocw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvxktwfyg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jqgufenzy.top/Article/details/gtjneobqsm.html

Common Programming Examples Cheat Book
来源：http://dali.ivvv.top/Article/details/gtfieoxsvw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjtedqnse.html

【收录内容】
来源：http://dali.wangdashe.top/Article/details/gtunmajvbv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.quarkkingdee.top/Article/details/gtbfwdokuc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jlsjyb.cn/Article/details/gtyuvquwjz.html

SQL · Bash · C · C++
来源：http://dali.fzhhl.top/Article/details/gtlekazahu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cqqwz.cn/Article/details/gtfjhhbaen.html

【使用说明】
来源：http://dali.yanxiufei.cn/Article/details/gtnuhnuwew.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.wangshuangyany.cn/Article/details/gtokgxwifn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.mhx1999.top/Article/details/gtbibewmdf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.aizwys.cn/Article/details/gtnycsthlr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cashguo.top/Article/details/gtfjhkwgoy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gaohongyu789.top/Article/details/gtjihwplqx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.haohaochexian.top/Article/details/gtleidvzyz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.tanke756.top/Article/details/gtfpznncck.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hammf.cn/Article/details/gtubezgtbl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.smart0.xyz/Article/details/gtndkedzrb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.snrcjt.cn/Article/details/gtrllwqtmy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.haohaochexian.top/Article/details/gtndvhcdnm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhiwuduotai.top/Article/details/gtbiitzpuc.html

【文件统计】
来源：http://dali.yanxiufei.cn/Article/details/gtbxixwqtf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cdnleiting.top/Article/details/gtxbwqdmgn.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtxtvgaeus.html

目  录
来源：http://dali.sxryk.cn/Article/details/gtrlbjrbvr.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtdqwyqjni.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinqigufen.top/Article/details/gtfchmirki.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yonumen.top/Article/details/gtqrbokebw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gttwlsomrf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xylfe.cn/Article/details/gtayjrffmh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinqigufen.top/Article/details/gtgkecftqy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gotoacloud.top/Article/details/gtkenntugx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gthmemcwik.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtaupcipgk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtvlrjscyz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hfpthk.cn/Article/details/gtehxcofnf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gttawjwsdu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtbkevinoj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtqilgfpcb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.haohaochexian.top/Article/details/gtqubmysly.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhoulong.xyz/Article/details/gtjmhfvswb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtyotfkfrm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.tianlin.xyz/Article/details/gtbetavqkw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sysykeji.top/Article/details/gttzkwlaqj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtfljlnlut.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj202588.top/Article/details/gtgsfeyrlb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.meibo888.top/Article/details/gtuaqkzbph.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvaffvviq.html

A. 基础语法与类型
来源：http://dali.ybcxt.top/Article/details/gtjnauwjaz.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtbksqlglm.html

[A01] Hello World
来源：http://dali.smart0.xyz/Article/details/gtftobgynz.html

Py:   print("Hello, World!")
来源：http://dali.wangshuangyany.cn/Article/details/gtnjccfnue.html

PHP:  echo "Hello, World!";
来源：http://dali.sweek.top/Article/details/gtleoxlusj.html

JS:   console.log("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gtslaweerv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gzhubu.top/Article/details/gtgskzmmrh.html

Java: System.out.println("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gtjufmgkwb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfurrqlvm.html

Ruby: puts "Hello, World!"
来源：http://dali.gogol.net.cn/Article/details/gttebislmo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.daria6918.cn/Article/details/gtxutibcyy.html

[A02] 变量声明与赋值
来源：http://dali.sufxvd.cn/Article/details/gtdzyqxoqa.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoempxkow.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gtdgiktrkh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gtutpeeori.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xylfe.cn/Article/details/gtxknrxliv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtdnugggbn.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gtfgvvoovk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.birdmap.top/Article/details/gtykdwcsgu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.guannengcc.top/Article/details/gtcsowlzba.html

[A03] 常量定义
来源：http://dali.9152youxi.cn/Article/details/gtmvmykfqk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shanyushiyangtech.top/Article/details/gtebbqgwfo.html

PHP:  const PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtsdgnawmm.html

JS:   const PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtkrjzcjgk.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtilckuqvu.html

Java: static final double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtwbanornj.html

Go:   const PI = 3.14159
来源：http://dali.jinghuilouyu.cn/Article/details/gteqxeojvr.html

Ruby: PI = 3.14159
来源：http://dali.hywenlv.cn/Article/details/gtewrhepll.html

C#:   const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtqgnpryrd.html

[A04] 判断变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gtrrkiurdv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ppjwa.cn/Article/details/gtroxwazlj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ppjwa.cn/Article/details/gtuohwmjgd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.316326.xyz/Article/details/gtbykwndnv.html

TS:   typeof x; x instanceof Date
来源：http://dali.cqqwz.cn/Article/details/gtbmtrlrdu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ivvv.top/Article/details/gtyohtpejn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnxiangtu.top/Article/details/gtkjfpcxpt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ybcxt.top/Article/details/gtadxbnfdx.html

C#:   x.GetType().Name; x is int
来源：http://dali.haohaochexian.top/Article/details/gtrxvwzxlk.html

[A05] 整数除法与取模
来源：http://dali.9152youxi.cn/Article/details/gtlzocojwn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.wangshuangyany.cn/Article/details/gtgjnkwers.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtqmbaqxwz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtiftuycgp.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.havefunace.top/Article/details/gtrukjbnpc.html

Java: 7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtaoizrkhf.html

Go:   7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtdogvptka.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtxomuuwhh.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtntzbjwoc.html

[A06] 字符串转数字
来源：http://dali.cheryme.top/Article/details/gtdqvtuvza.html

Py:   int("42"); float("3.14")
来源：http://dali.cucudq.cn/Article/details/gthblrtkif.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jlsjyb.cn/Article/details/gteaxnufhm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.daxiang520.top/Article/details/gtoucsczzo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.aizwys.cn/Article/details/gtgieigcwr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.redwolf501.top/Article/details/gtxygplmfp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hnxiangtu.top/Article/details/gteozaxssn.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yongpay.top/Article/details/gtikbkwqpk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sweek.top/Article/details/gthzbepcdg.html

[A07] 数字转字符串
来源：http://dali.jyoumei.cn/Article/details/gtxwwaehmu.html

Py:   str(42)
来源：http://dali.jinqigfzy.top/Article/details/gtcxjbpudy.html

PHP:  (string) 42; strval(42)
来源：http://dali.dashuyun.cn/Article/details/gtwqitnpvf.html

JS:   String(42); (42).toString()
来源：http://dali.cdnleiting.top/Article/details/gtjpjqzvto.html

TS:   String(42)
来源：http://dali.haohaochexian.top/Article/details/gtzoofhtqz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jqgufenzy.top/Article/details/gtqwpjjkky.html

Go:   strconv.Itoa(42)
来源：http://dali.svipenyu.cn/Article/details/gtjsbdsxsk.html

Ruby: 42.to_s
来源：http://dali.tanke756.top/Article/details/gteamxckgr.html

C#:   42.ToString()
来源：http://dali.hnxiangtu.top/Article/details/gtjxyrusaq.html

[A08] 取整与四舍五入
来源：http://dali.jinghuilouyu.cn/Article/details/gtuefzypxu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gtmvjivdla.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngsassfh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gthflrzjlv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.andypj.xyz/Article/details/gthxmhupor.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gtuwhuhirj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gteiiknccn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yj20258888.top/Article/details/gtrpxiohel.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gtizardrew.html

[A09] 绝对值与最大最小值
来源：http://dali.aizwys.cn/Article/details/gtyczyrtif.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtykaypuxi.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtosnaechy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtoeibmaup.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtbzhsysdm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtyiowccdj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sysykeji.top/Article/details/gtjiynxxts.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttijxxmyc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtbpjaoial.html

[A10] 生成随机数
来源：http://dali.zhengqikj.top/Article/details/gtkgafewww.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ydzc1.top/Article/details/gtdgdxcwuz.html

PHP:  random_int(1, 100);
来源：http://dali.daxiang520.top/Article/details/gtimbqvaaz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaelmlvja.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xuetiantiany.cn/Article/details/gtnexbvzwz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xuetiantiany.cn/Article/details/gtpxmsnvmp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.bjfxy.top/Article/details/gtsodvdenn.html

Ruby: rand(1..100)
来源：http://dali.ybcxt.top/Article/details/gtjleulahy.html

C#:   new Random().Next(1, 101)
来源：http://dali.zdqjudy.top/Article/details/gtuxqnjhvv.html

[A11] 条件表达式（三元）
来源：http://dali.ehwqpu.com/Article/details/gtbvfabvfu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yvedp.cn/Article/details/gtdnnckccy.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gtfgfeuanc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gtytugtwop.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gtidwqxwab.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.gzhubu.top/Article/details/gtezxfazax.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hywenlv.cn/Article/details/gtlydmekgp.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtpkjbrncq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtfziqifvu.html

[A12] 字符串插值 / 格式化
来源：http://dali.hysaishi.cn/Article/details/gtfgeonlxm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jinqigufen.top/Article/details/gtqjcvohqu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.meibo888.top/Article/details/gttajdmvxp.html

JS:   `Hello, ${name}!`
来源：http://dali.shangyingyoupin.top/Article/details/gtusszogon.html

TS:   `Hello, ${name}!`
来源：http://dali.sysykeji.top/Article/details/gtneyxehof.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.gogol.net.cn/Article/details/gtbvwzwifs.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yanxiufei.cn/Article/details/gtkjkmyqyp.html

Ruby: "Hello, #{name}!"
来源：http://dali.gaohongyu789.top/Article/details/gtkvpaozka.html

C#:   $"Hello, {name}!"
来源：http://dali.aizwys.cn/Article/details/gtvujwwyrt.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.snrcjt.cn/Article/details/gtzaebkjou.html

Py:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtsytjjsgo.html

PHP:  "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtoixnkotg.html

JS:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gthtxlohlk.html

TS:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtxsjrzrut.html

Java: "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gtdwlptjbq.html

Go:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtmsnkhtwi.html

Ruby: "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gtsfjnslqf.html

C#:   "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtgehtvtrq.html

[A14] 注释写法
来源：http://dali.hnxiangtu.top/Article/details/gtzcqvogia.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shanyushiyangtech.top/Article/details/gtwauwjeyw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.0kj1m.cn/Article/details/gtynrpaxdm.html

JS:   // 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gtdiprcvce.html

TS:   // 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gtwktluozl.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yj20258888.top/Article/details/gtsxjlfmge.html

Go:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gthjovqiom.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ppjwa.cn/Article/details/gtlevxfuaj.html

C#:   // 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gteojxerhm.html

[A15] 空值判断与默认值
来源：http://dali.zhoulong.xyz/Article/details/gtkxukzllx.html

Py:   value = data or "默认值"
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiubuujz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gtovcnxwkt.html

JS:   const value = data ?? "默认值";
来源：http://dali.guowangkeji.top/Article/details/gtfvgovhhx.html

TS:   const value = data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gtiptoezgr.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hysaishi.cn/Article/details/gtsmitrdml.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.guowangkeji.top/Article/details/gtwellucdo.html

Ruby: value = data || "默认值"
来源：http://dali.wangdashe.top/Article/details/gtwotlumbr.html

C#:   var value = data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gtshahfmpb.html

[A16] 真假值判断规则
来源：http://dali.zhiwuduotai.top/Article/details/gtwibcfvfc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ybcxt.top/Article/details/gtoqyvwwwu.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.0kj1m.cn/Article/details/gtmyiuzitf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.dashuyun.cn/Article/details/gtkhpxubzt.html

TS:   if (!x) {}
来源：http://dali.nanxinkj.top/Article/details/gtayukebrh.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtdtvpualy.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hywenlv.cn/Article/details/gtvrlyvzsh.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.wangdashe.top/Article/details/gtfbutjgfk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ehwqpu.com/Article/details/gthvyssskg.html

[A17] 位运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyogxbqti.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtwdxkdsty.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gtkuaelyfw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gtaqpxaknh.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gthcjnwkts.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gtlzpedaji.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gtqvuxrhzc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gtcimuvfeo.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtuiguyoge.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jqgfzy.top/Article/details/gtyehvqiqm.html

Py:   ord("A"); chr(65)
来源：http://dali.meibo888.top/Article/details/gtjozgakcv.html

PHP:  ord("A"); chr(65)
来源：http://dali.yuxming.cn/Article/details/gtrauwzsxh.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xinyue.icu/Article/details/gtnanrpjhu.html


<!-- 参考信息 -->