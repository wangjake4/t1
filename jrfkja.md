代发 wailian999

[U103] JS：定时器
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxqmqapa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ivvv.top/Article/details/gtkxxwqakq.html

[U104] JS：防抖
来源：http://dali.haohaochexian.top/Article/details/gttpwbbexn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtsxxqdvpi.html

[U105] JS：节流
来源：http://dali.gzhubu.top/Article/details/gthdejsxwn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nanxuanxn.top/Article/details/gthepqzzmt.html

[U106] JS：日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtqpptfkvg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hammf.cn/Article/details/gtuaodfutu.html

[U107] JS：数字千分位
来源：http://dali.daxiang520.top/Article/details/gtftysnpue.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gtxaauaseq.html

[U108] JS：随机整数
来源：http://dali.yuanzhike.top/Article/details/gtctgyirxq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinghuilouyu.cn/Article/details/gtobpzynxh.html

[U109] JS：数组分组
来源：http://dali.iojbl.cn/Article/details/gtbrdjeile.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jianghu66.top/Article/details/gtrxhfptmw.html

[U110] JS：数组分块
来源：http://dali.0kj1m.cn/Article/details/gtktxdwcrw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxuanxn.top/Article/details/gtldsvcqma.html

[U111] JS：对象转 Map
来源：http://dali.jyoumei.cn/Article/details/gtbvsvkhxk.html

new Map(Object.entries(obj))
来源：http://dali.cheryme.top/Article/details/gttgscyhab.html

[U112] JS：字符串补位
来源：http://dali.vqdsnc.cn/Article/details/gtvfnkgrol.html

"7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gthnamkopf.html

[U113] JS：正则替换全部
来源：http://dali.quarkkingdee.top/Article/details/gtjtvxzusa.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaprzfxy.html

[U114] JS：JSON 深比较
来源：http://dali.shangyingyoupin.top/Article/details/gtxnscstzy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.snrcjt.cn/Article/details/gtbjaifong.html

[U115] JS：生成 UUID
来源：http://dali.yongpay.top/Article/details/gtvdgejtri.html

crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtuhdyifhi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenzaomai.com/Article/details/gtypxzmsqg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yanxiufei.cn/Article/details/gtzojxfjbm.html

[U117] JS：单元测试
来源：http://dali.zhongyouzk.top/Article/details/gttftdjbsz.html

npm i -D vitest;  npx vitest
来源：http://dali.yanxiufei.cn/Article/details/gtzlwbebdr.html

[U118] JS：开发服务器
来源：http://dali.yj20258888.top/Article/details/gtudtpkoxi.html

npm i -D vite;  npx vite
来源：http://dali.316326.xyz/Article/details/gtfddouuct.html

[U119] JS：生产构建
来源：http://dali.feifeiyinyue.top/Article/details/gtmjnyfaij.html

npx vite build
来源：http://dali.chenjidiqi.icu/Article/details/gteepfftyy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenlongwang.top/Article/details/gtblbnhdvi.html

import.meta.env.VITE_API_URL
来源：http://dali.gogol.net.cn/Article/details/gtswucjrnh.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtknunytsr.html

统计汇总
来源：http://dali.aizwys.cn/Article/details/gtvaighgzx.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtgjldccel.html

按语言统计（条）：
来源：http://dali.iojbl.cn/Article/details/gtezmiomoh.html

Python ......... 252
来源：http://dali.yj20258.top/Article/details/gtbcvetxql.html

PHP ............ 252
来源：http://dali.sufxvd.cn/Article/details/gtnhrreumv.html

JavaScript ..... 252
来源：http://dali.hywenlv.cn/Article/details/gtqmgbraac.html

TypeScript ..... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtemagggmi.html

Java ........... 212
来源：http://dali.jinqigufen.top/Article/details/gtagjygeot.html

Go ............. 212
来源：http://dali.smart0.xyz/Article/details/gtcitcylyt.html

Ruby ........... 212
来源：http://dali.fengsongda.top/Article/details/gthjffmnvv.html

C# ............. 212
来源：http://dali.yonumen.top/Article/details/gtvfbadubs.html

C .............. 30
来源：http://dali.yangfankeji.com/Article/details/gtnkurbbzk.html

C++ ............ 30
来源：http://dali.bjfxy.top/Article/details/gthhjpgrle.html

SQL ............ 90
来源：http://dali.xinyue.icu/Article/details/gthbkjlqgf.html

Bash ........... 80
来源：http://dali.quarkkingdee.top/Article/details/gtqmxrwccn.html

Kotlin ......... 15
来源：http://dali.zhongyouzk.top/Article/details/gtwuirbbhj.html

Swift .......... 15
来源：http://dali.vqdsnc.cn/Article/details/gtwmtpujez.html

Lua ............ 10
来源：http://dali.cucudq.cn/Article/details/gttbnjcagr.html

Perl ........... 10
来源：http://dali.nanxinkj.top/Article/details/gtxiwexbfj.html

Scala .......... 10
来源：http://dali.0kj1m.cn/Article/details/gtrdjtdgym.html

------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gtaavdongt.html

合计 ........... 2106 条
来源：http://dali.yj202588.top/Article/details/gtdaiuzcwk.html

按章节统计：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoflmcauc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ehwqpu.com/Article/details/gtfbruvjle.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gtazznqkaf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gtpspdsdzj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinqigfzy.top/Article/details/gtcmfhsino.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.smart0.xyz/Article/details/gtoqthfpds.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenlongwang.top/Article/details/gtxhdvxmmk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gtnqzkoxef.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gteazyvzto.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtzrqtkdpu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ydzc1.top/Article/details/gtrkljknmw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gthxpjowow.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gthoyzrjkf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gtqkhfvqwh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hammf.cn/Article/details/gtxinrsvox.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guowangkeji.top/Article/details/gtgkrchsna.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtemblacpi.html

Q SQL 专题                              90
来源：http://dali.snrcjt.cn/Article/details/gtzuyayouh.html

R Bash 专题                             80
来源：http://dali.birdmap.top/Article/details/gtykbkjxpt.html

S C / C++ 专题                          60
来源：http://dali.birdmap.top/Article/details/gtysxoxfbp.html

T 其他语言补充                          60
来源：http://dali.fzhhl.top/Article/details/gtaurcorpb.html

U 高频实用片段                         120
来源：http://dali.chenjidiqi.icu/Article/details/gtdxagkbfv.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtwcpftmck.html

合计                                  2106 条
来源：http://dali.aizwys.cn/Article/details/gtxwifjyax.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtttjvcjcf.html

使用提醒
来源：http://dali.guowangkeji.top/Article/details/gtgulcadvg.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtwcetfixb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.haohaochexian.top/Article/details/gttmkhnawr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.havefunace.top/Article/details/gtbhjdwtit.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shzxlz.cn/Article/details/gtdprugfjq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sweek.top/Article/details/gtmqdyiust.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nanxinkj.top/Article/details/gtkvsmxvzm.html

—— 文件结束 ——
来源：http://dali.hysaishi.cn/Article/details/gtrmhqhqkv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzqmrqmis.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xuanzx.com/Article/details/gtvsnilamg.html

Common Programming Examples Cheat Book
来源：http://dali.feifeiyinyue.top/Article/details/gtwuadbgnt.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtbizydyot.html

【收录内容】
来源：http://dali.guannengcc.top/Article/details/gtjeiiiqqj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gaohongyu789.top/Article/details/gtqfzkoppy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.aibaodan.cn/Article/details/gtfsmydbtc.html

SQL · Bash · C · C++
来源：http://dali.wangshuangyany.cn/Article/details/gtsjorysvl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ivvv.top/Article/details/gtobqtcdct.html

【使用说明】
来源：http://dali.cucudq.cn/Article/details/gtkphrvswp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yuanzhike.top/Article/details/gtuyvnhzud.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xziqi.cn/Article/details/gthgnxwfkd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.smart0.xyz/Article/details/gtatkqacmk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yueranfly.top/Article/details/gtpwhzrfmq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.vqdsnc.cn/Article/details/gtehkveymy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.fengsongda.top/Article/details/gtaiyuinmt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yangfankeji.com/Article/details/gtzvgsxjza.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.9152youxi.cn/Article/details/gtydisphnw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenlongwang.top/Article/details/gtdqsvahes.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.daxiang520.top/Article/details/gtxgzcngze.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnqzz.top/Article/details/gtizfxapgu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cheryme.top/Article/details/gtlpeptlff.html

【文件统计】
来源：http://dali.jyoumei.cn/Article/details/gteygztief.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yonumen.top/Article/details/gtjlcbokog.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtznxgenut.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gtehkfvgoq.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtaktdpbil.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jqgufenzy.top/Article/details/gthxjitlgw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.redwolf501.top/Article/details/gtclldrthb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sweek.top/Article/details/gthkhpkewc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqwakzcu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jqgufenzy.top/Article/details/gtexanranb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hammf.cn/Article/details/gtsygmsrfo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gtjxbhmxwp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.iojbl.cn/Article/details/gtswfktgfe.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtfvtqfejy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hammf.cn/Article/details/gtndermwys.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtdxymvrwz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtfxfggifl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtljjnwtbc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtmbdcxuoj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.fengsongda.top/Article/details/gtllysllim.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtfkmfupfz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hnqzz.top/Article/details/gtkqulvgjg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtuwalyjel.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtapnmzhrw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gtpjkruofd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.iojbl.cn/Article/details/gtzowpxynw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnitgdnap.html

A. 基础语法与类型
来源：http://dali.shzxlz.cn/Article/details/gtwzgycutm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqzekdxbf.html

[A01] Hello World
来源：http://dali.9152youxi.cn/Article/details/gtpegrlmff.html

Py:   print("Hello, World!")
来源：http://dali.jinghuilouyu.cn/Article/details/gtizlwsnbg.html

PHP:  echo "Hello, World!";
来源：http://dali.hnxiangtu.top/Article/details/gtdstojcfm.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gtuullyivs.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ppjwa.cn/Article/details/gtlgwsjuoe.html

Java: System.out.println("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gtpaxrzumo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.vqdsnc.cn/Article/details/gtauwivdpv.html

Ruby: puts "Hello, World!"
来源：http://dali.hywenlv.cn/Article/details/gteuixqbay.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gtwvchgrky.html

[A02] 变量声明与赋值
来源：http://dali.xinyue.icu/Article/details/gtuzhhsrnq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yj20258.top/Article/details/gtnejhtrpo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ivvv.top/Article/details/gtgjtpmnfd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtsfxeiplx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.guannengcc.top/Article/details/gtzpyujnzz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.316326.xyz/Article/details/gtqwsjiuiu.html

Go:   name := "Alex"; age := 20
来源：http://dali.cqqwz.cn/Article/details/gtavoxypsl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hongshengwenyu.top/Article/details/gtgyodexab.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.svipenyu.cn/Article/details/gtgcpvlzig.html

[A03] 常量定义
来源：http://dali.yueranfly.top/Article/details/gtnzwcnyio.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhengqikj.top/Article/details/gthvyvdtyh.html

PHP:  const PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gttealkcno.html

JS:   const PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtpmxfnobi.html

TS:   const PI: number = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtqlfmxvbk.html

Java: static final double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtewotnuxf.html

Go:   const PI = 3.14159
来源：http://dali.jinghuilouyu.cn/Article/details/gtotvrgjkn.html

Ruby: PI = 3.14159
来源：http://dali.shzxlz.cn/Article/details/gtsphirmfe.html

C#:   const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtmxvwqlju.html

[A04] 判断变量类型
来源：http://dali.gzhubu.top/Article/details/gtcteyljzd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yvedp.cn/Article/details/gtszefvcba.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ppjwa.cn/Article/details/gtyhgwbyjt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xziqi.cn/Article/details/gtzcifjmso.html

TS:   typeof x; x instanceof Date
来源：http://dali.cashguo.top/Article/details/gtbwbnfqfe.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.tian-w.cn/Article/details/gtormihqes.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nwbrower.top/Article/details/gtiazssfaa.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.dashuyun.cn/Article/details/gtojdoljzc.html

C#:   x.GetType().Name; x is int
来源：http://dali.cheryme.top/Article/details/gtzxzzfffj.html

[A05] 整数除法与取模
来源：http://dali.zdqjudy.top/Article/details/gtoupqezcn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.mhx1999.top/Article/details/gthaipgmmr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gtyyhmeyhn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.meibo888.top/Article/details/gtbkgimzve.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtpfqckzvh.html

Java: 7 / 2; 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtfkwmqjlq.html

Go:   7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtodufdipq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gtqeuijjee.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtjnyvmgoz.html

[A06] 字符串转数字
来源：http://dali.daxiang520.top/Article/details/gtkhsevqsr.html

Py:   int("42"); float("3.14")
来源：http://dali.hywenlv.cn/Article/details/gtlwwdzsbl.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.sysykeji.top/Article/details/gtgcdktwzp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xziqi.cn/Article/details/gtltkplmxi.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.tianlin.xyz/Article/details/gtvbdjioxx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozljbndc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yanxiufei.cn/Article/details/gtvbrgtjkl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.havefunace.top/Article/details/gtitqdpaou.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenjidiqi.icu/Article/details/gtefsortlg.html

[A07] 数字转字符串
来源：http://dali.aibaodan.cn/Article/details/gttzblisrw.html

Py:   str(42)
来源：http://dali.gotoacloud.top/Article/details/gtlfogimbh.html

PHP:  (string) 42; strval(42)
来源：http://dali.zdqjudy.top/Article/details/gtfxvfewvv.html

JS:   String(42); (42).toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtxobzryqt.html

TS:   String(42)
来源：http://dali.sysykeji.top/Article/details/gtzezwpehz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhengqikj.top/Article/details/gtdcdsoeyq.html

Go:   strconv.Itoa(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxouogvka.html

Ruby: 42.to_s
来源：http://dali.havefunace.top/Article/details/gtpsenvxmu.html

C#:   42.ToString()
来源：http://dali.sufxvd.cn/Article/details/gtappyahrz.html

[A08] 取整与四舍五入
来源：http://dali.yuxming.cn/Article/details/gtlybrcboi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ivvv.top/Article/details/gtlfddfbbh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ydzc1.top/Article/details/gtigbauqri.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gtdorllock.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hongshengwenyu.top/Article/details/gtpyfnducy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtrmjrdffq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtnkttynvp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.haohaochexian.top/Article/details/gtioxcrklc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticgihdwb.html

[A09] 绝对值与最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gtiotcupgu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtkgywigqu.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtmmehgmgu.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.pycfn.com/Article/details/gtyifvfnvy.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtihllfppn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtnbzjmcxu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gzhubu.top/Article/details/gtfckgmbao.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ybcxt.top/Article/details/gtitkcrvtz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yonumen.top/Article/details/gtbvbkmyys.html

[A10] 生成随机数
来源：http://dali.wangshuangyany.cn/Article/details/gtjwenyfwf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jqgfzy.top/Article/details/gtrhritedc.html

PHP:  random_int(1, 100);
来源：http://dali.sufxvd.cn/Article/details/gtjjjxpjhk.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.aizwys.cn/Article/details/gtlpfjwdlg.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sweek.top/Article/details/gtfmozaxkq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.sxryk.cn/Article/details/gtfepsovsp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jqgufenzy.top/Article/details/gtaowxgnkp.html

Ruby: rand(1..100)
来源：http://dali.tanke756.top/Article/details/gtdbmfqrsr.html

C#:   new Random().Next(1, 101)
来源：http://dali.hammf.cn/Article/details/gtpktacpdb.html

[A11] 条件表达式（三元）
来源：http://dali.kuanghao11.cn/Article/details/gtmvswqibf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jqgfzy.top/Article/details/gtnqxggjmj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtdvbfzksh.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gtyjtzbihn.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gtbhvpaogh.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gtywelgugm.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhoulong.xyz/Article/details/gtnzvgkfww.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gtddkjobum.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtvahftxuc.html

[A12] 字符串插值 / 格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtloqorcxz.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.aibaodan.cn/Article/details/gtzzuevvvf.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.fzhhl.top/Article/details/gtkizgbodm.html

JS:   `Hello, ${name}!`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmbamptb.html

TS:   `Hello, ${name}!`
来源：http://dali.tianlin.xyz/Article/details/gtknhhfjdo.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jlsjyb.cn/Article/details/gtpmhqxgka.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ybcxt.top/Article/details/gtletuqlfi.html

Ruby: "Hello, #{name}!"
来源：http://dali.yj202588.top/Article/details/gtaygpkxud.html

C#:   $"Hello, {name}!"
来源：http://dali.yvedp.cn/Article/details/gtauxvrjme.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nanxinkj.top/Article/details/gtpvtzvess.html

Py:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtlfwkqohz.html

PHP:  "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtaeitbrgw.html

JS:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtpdmfiajy.html

TS:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmmtzjar.html

Java: "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtwhxggifm.html

Go:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtvganzkkk.html

Ruby: "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtdikitand.html

C#:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtygzfxrsp.html

[A14] 注释写法
来源：http://dali.guannengcc.top/Article/details/gtpoaktnwo.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shuidangran.top/Article/details/gtaggndcao.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gtkivzjnbf.html

JS:   // 单行；/* 多行 */
来源：http://dali.cqqwz.cn/Article/details/gtzwtssrwa.html

TS:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtxopkclql.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.sysykeji.top/Article/details/gtlywppwyk.html

Go:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gtkuniqlfn.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.guowangkeji.top/Article/details/gtgupeueid.html

C#:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtefwnmfdq.html

[A15] 空值判断与默认值
来源：http://dali.nwbrower.top/Article/details/gtrhcnphth.html

Py:   value = data or "默认值"
来源：http://dali.tanke756.top/Article/details/gtxtpybqib.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gtbkafbeur.html

JS:   const value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gtsobuzupb.html

TS:   const value = data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gthoqrbbek.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yuanzhike.top/Article/details/gtzyamqlqy.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthidgohlz.html

Ruby: value = data || "默认值"
来源：http://dali.vqdsnc.cn/Article/details/gtwrcanmfj.html

C#:   var value = data ?? "默认值";
来源：http://dali.yuxming.cn/Article/details/gtnfkcdibb.html

[A16] 真假值判断规则
来源：http://dali.tianlin.xyz/Article/details/gtuslwmcav.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.tian-w.cn/Article/details/gtfozyxlrg.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yvedp.cn/Article/details/gtgbwclliw.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xylfe.cn/Article/details/gtuloceodr.html

TS:   if (!x) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqzyewhha.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtqgtbviar.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.andypj.xyz/Article/details/gtkmlubcnq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.9152youxi.cn/Article/details/gtroqgrrze.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jianghu66.top/Article/details/gtbfmxvqip.html

[A17] 位运算
来源：http://dali.fzhhl.top/Article/details/gtwpdlykqp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtwfytmpvv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.aizwys.cn/Article/details/gtasfiusmm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gtxnutbtlh.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gtzxzqrwlz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtgnzjxput.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gthusqbafl.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gttwvmreap.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gtwuusqhxz.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jqgfzy.top/Article/details/gtmoygzdkh.html

Py:   ord("A"); chr(65)
来源：http://dali.redwolf501.top/Article/details/gtwtefyyjr.html

PHP:  ord("A"); chr(65)
来源：http://dali.dashuyun.cn/Article/details/gtpagxmhpj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sysykeji.top/Article/details/gtmzoxidbh.html


<!-- 参考信息 -->