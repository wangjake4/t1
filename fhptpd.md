代发 wailian999

[U105] JS：节流
来源：http://dali.fzhhl.top/Article/details/gtcarmwqaw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sxryk.cn/Article/details/gtlsscdvjh.html

[U106] JS：日期格式化
来源：http://dali.tanke756.top/Article/details/gtamsguyvb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj202588.top/Article/details/gtpkvpiokn.html

[U107] JS：数字千分位
来源：http://dali.pycfn.com/Article/details/gtdysypwnq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gtrjzzprxd.html

[U108] JS：随机整数
来源：http://dali.hfpthk.cn/Article/details/gtkpkwmhbp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.316326.xyz/Article/details/gtomlzbxlk.html

[U109] JS：数组分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadsoshsq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gtkmvvggxo.html

[U110] JS：数组分块
来源：http://dali.c1oappe.top/Article/details/gtgozcjcxy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnxiangtu.top/Article/details/gturrubdij.html

[U111] JS：对象转 Map
来源：http://dali.yangfankeji.com/Article/details/gtxkwubdmt.html

new Map(Object.entries(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gtcgaolpsd.html

[U112] JS：字符串补位
来源：http://dali.ivvv.top/Article/details/gtbgxttjmq.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzrttbgz.html

[U113] JS：正则替换全部
来源：http://dali.cheryme.top/Article/details/gthqjjnwmw.html

s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtpzmjujau.html

[U114] JS：JSON 深比较
来源：http://dali.nanxinkj.top/Article/details/gtodwwtuzk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gtbvgywbhu.html

[U115] JS：生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gteyengiju.html

crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsmglhds.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.haohaochexian.top/Article/details/gtplrxditl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbitccnx.html

[U117] JS：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gtugbkwadk.html

npm i -D vitest;  npx vitest
来源：http://dali.dianchejie.cn/Article/details/gtsuimcaok.html

[U118] JS：开发服务器
来源：http://dali.jlsjyb.cn/Article/details/gteezizezf.html

npm i -D vite;  npx vite
来源：http://dali.hongshengwenyu.top/Article/details/gtqisjpyur.html

[U119] JS：生产构建
来源：http://dali.hongshengwenyu.top/Article/details/gtwdfiuxkn.html

npx vite build
来源：http://dali.chenzaomai.com/Article/details/gtouoabcbm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxuanxn.top/Article/details/gtlakwxnwb.html

import.meta.env.VITE_API_URL
来源：http://dali.cqqwz.cn/Article/details/gtlvmuhiod.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtbyvenysh.html

统计汇总
来源：http://dali.guowangkeji.top/Article/details/gteqewrcws.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtobzgmwoj.html

按语言统计（条）：
来源：http://dali.tian-w.cn/Article/details/gthlkjnobt.html

Python ......... 252
来源：http://dali.chenlongwang.top/Article/details/gtdzvwscrr.html

PHP ............ 252
来源：http://dali.cashguo.top/Article/details/gtmwmbmfln.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gtuimjcmve.html

TypeScript ..... 212
来源：http://dali.hysaishi.cn/Article/details/gtepxsgatt.html

Java ........... 212
来源：http://dali.dianchejie.cn/Article/details/gtdeiexldt.html

Go ............. 212
来源：http://dali.zdqjudy.top/Article/details/gtfwuosbfl.html

Ruby ........... 212
来源：http://dali.nanxuanxn.top/Article/details/gtgoopmqvh.html

C# ............. 212
来源：http://dali.sysykeji.top/Article/details/gttsjutavd.html

C .............. 30
来源：http://dali.aibaodan.cn/Article/details/gtcrlvfpau.html

C++ ............ 30
来源：http://dali.ydzc1.top/Article/details/gtetaoeumg.html

SQL ............ 90
来源：http://dali.hnxiangtu.top/Article/details/gtvsinytcz.html

Bash ........... 80
来源：http://dali.sysykeji.top/Article/details/gtnbxebjhk.html

Kotlin ......... 15
来源：http://dali.cqqwz.cn/Article/details/gtdhgbgodt.html

Swift .......... 15
来源：http://dali.jqgfzy.top/Article/details/gtjvboiqtf.html

Lua ............ 10
来源：http://dali.tian-w.cn/Article/details/gtizdbirfl.html

Perl ........... 10
来源：http://dali.daxiang520.top/Article/details/gtraymlols.html

Scala .......... 10
来源：http://dali.zhiwuduotai.top/Article/details/gtbyasxfcv.html

------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtdfkexovn.html

合计 ........... 2106 条
来源：http://dali.yuanzhike.top/Article/details/gtnxszcoxp.html

按章节统计：
来源：http://dali.yonumen.top/Article/details/gtizwgajwp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.smart0.xyz/Article/details/gthulpsfeu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqqzmgsq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtczlgkyxz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gtlpwaqkwc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aizwys.cn/Article/details/gtexdbdbtx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.birdmap.top/Article/details/gtewdufqrh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gtjnicgalh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.pengpengdd.cyou/Article/details/gttiujuqxx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtngqacqso.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gtkwskwpjc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtjkhbnufr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtgagceayv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtjgwctgkd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xziqi.cn/Article/details/gtccfymrrl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.svipenyu.cn/Article/details/gtiqjqvzzg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtwsqvtdnd.html

Q SQL 专题                              90
来源：http://dali.cucudq.cn/Article/details/gtyfsubznt.html

R Bash 专题                             80
来源：http://dali.yueranfly.top/Article/details/gtlvbjltyg.html

S C / C++ 专题                          60
来源：http://dali.xinyue.icu/Article/details/gtvarhpeus.html

T 其他语言补充                          60
来源：http://dali.xinyue.icu/Article/details/gtztcuhjrz.html

U 高频实用片段                         120
来源：http://dali.zhengqikj.top/Article/details/gtikvyrmuu.html

------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwmcmyyk.html

合计                                  2106 条
来源：http://dali.shuidangran.top/Article/details/gtjyafszkb.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gtbhjojmbw.html

使用提醒
来源：http://dali.wangshuangyany.cn/Article/details/gtpmpanlir.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaacbgdfx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.dianchejie.cn/Article/details/gtjohhonbz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.daria6918.cn/Article/details/gtgwffptyb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hnxiangtu.top/Article/details/gtvsglwjqz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nanxuanxn.top/Article/details/gtyfzysmbp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gaohongyu789.top/Article/details/gtakibhmne.html

—— 文件结束 ——
来源：http://dali.shzxlz.cn/Article/details/gtuspqeuia.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtxgokyvga.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hnqzz.top/Article/details/gtbffqlqmt.html

Common Programming Examples Cheat Book
来源：http://dali.meibo888.top/Article/details/gtzbfwdebq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtzxtcckoh.html

【收录内容】
来源：http://dali.mhx1999.top/Article/details/gtesztbqoj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tian-w.cn/Article/details/gtkpoqqupz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yuanzhike.top/Article/details/gtjjmmnnrs.html

SQL · Bash · C · C++
来源：http://dali.xziqi.cn/Article/details/gtyysiwcvi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xylfe.cn/Article/details/gturooqqwz.html

【使用说明】
来源：http://dali.fzhhl.top/Article/details/gtzcntjfvh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.dashuyun.cn/Article/details/gtwtojdcjb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.feifeiyinyue.top/Article/details/gtsmfzbuvz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jqgufenzy.top/Article/details/gtgxcgpzlm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yj20258.top/Article/details/gtouhaqmaz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.feifeiyinyue.top/Article/details/gtbuxltnhr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jlsjyb.cn/Article/details/gtnjyipvdp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hfpthk.cn/Article/details/gtruomqpdb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.0kj1m.cn/Article/details/gtdmavckac.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jianghu66.top/Article/details/gtuknyenqj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xziqi.cn/Article/details/gtinnbjqct.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.redwolf501.top/Article/details/gtlrovrsbu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj202588.top/Article/details/gtmtmwctbh.html

【文件统计】
来源：http://dali.shanyushiyangtech.top/Article/details/gtwouebnng.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.9152youxi.cn/Article/details/gtumqirajo.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtvqdumnfj.html

目  录
来源：http://dali.shzxlz.cn/Article/details/gtxjwjoakf.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtsxhmwcbj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj20258.top/Article/details/gtzyjjaxfo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gtwxmjbjgk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gtotmflodv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.haohaochexian.top/Article/details/gtuqtyxfgq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ivvv.top/Article/details/gthxgcnwxx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zycfv.cn/Article/details/gtfdhtjlor.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.daria6918.cn/Article/details/gtkutcyrgw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtmwflckoz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gtghtphpbc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cashguo.top/Article/details/gtwqkkxopv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcborxhi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtyewfkxsq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gtsigfbjxm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.316326.xyz/Article/details/gtobbkpsje.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sweek.top/Article/details/gtyhilkxtr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gtghovjqfp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jianghu66.top/Article/details/gtykumviri.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtlmurzcme.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.sysykeji.top/Article/details/gtxfmwjixh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gtjdqtqbud.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtotmflrrp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtolrwwfai.html

A. 基础语法与类型
来源：http://dali.xuanzx.com/Article/details/gtpomdettv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtnaohbtop.html

[A01] Hello World
来源：http://dali.jinqigufen.top/Article/details/gtlibwjxqo.html

Py:   print("Hello, World!")
来源：http://dali.chenlongwang.top/Article/details/gtbwudjxfp.html

PHP:  echo "Hello, World!";
来源：http://dali.sysykeji.top/Article/details/gtnxiayglw.html

JS:   console.log("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gtidtkqfys.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ybcxt.top/Article/details/gtgvtiwuli.html

Java: System.out.println("Hello, World!");
来源：http://dali.shangyingyoupin.top/Article/details/gtfriqynfv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.smart0.xyz/Article/details/gtlavcjbrh.html

Ruby: puts "Hello, World!"
来源：http://dali.yuanzhike.top/Article/details/gtkqvbaypt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.c1oappe.top/Article/details/gtgmteqxbw.html

[A02] 变量声明与赋值
来源：http://dali.zycfv.cn/Article/details/gtcnxviquh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgktyqnkn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yueranfly.top/Article/details/gtmqgtjgif.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gtjktdkfys.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.guannengcc.top/Article/details/gtsmxttrmn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sysykeji.top/Article/details/gtjhrdvytp.html

Go:   name := "Alex"; age := 20
来源：http://dali.xinyue.icu/Article/details/gtpifidcfx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.guannengcc.top/Article/details/gtjhnwqbcm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtqgxkhuvi.html

[A03] 常量定义
来源：http://dali.jinqigfzy.top/Article/details/gtuairyqnz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.0kj1m.cn/Article/details/gtndhsxsqk.html

PHP:  const PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtrturcswc.html

JS:   const PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtamxyfstc.html

TS:   const PI: number = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gthvmmuaal.html

Java: static final double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gthlqseaha.html

Go:   const PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gtghnrldcz.html

Ruby: PI = 3.14159
来源：http://dali.gaohongyu789.top/Article/details/gtwkupgaey.html

C#:   const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtaxrxbujw.html

[A04] 判断变量类型
来源：http://dali.zhiwuduotai.top/Article/details/gtxryicsjt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkldtjtso.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.tian-w.cn/Article/details/gtclmzucem.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenzaomai.com/Article/details/gtywsbmcqi.html

TS:   typeof x; x instanceof Date
来源：http://dali.haohaochexian.top/Article/details/gtwghquuen.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jqgufenzy.top/Article/details/gtldgsgczr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cucudq.cn/Article/details/gtyikerqhu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrmgnerx.html

C#:   x.GetType().Name; x is int
来源：http://dali.yueranfly.top/Article/details/gtjpygjtcy.html

[A05] 整数除法与取模
来源：http://dali.wangdashe.top/Article/details/gtnhbpanso.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gzhubu.top/Article/details/gtnntxyysg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtrjhuiffm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsekvpdfi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gthamlngux.html

Java: 7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtarcommlz.html

Go:   7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtekqftbmg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gtbzyneqpq.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtddoqrnkx.html

[A06] 字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtczehyduo.html

Py:   int("42"); float("3.14")
来源：http://dali.nanxinkj.top/Article/details/gtujcblqqs.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbecolvkt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.mhx1999.top/Article/details/gtvqhwokhv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwqdlatd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ehwqpu.com/Article/details/gteenqnyrw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.tian-w.cn/Article/details/gtyvmcosxf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yongpay.top/Article/details/gtjecwyhfi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jqgfzy.top/Article/details/gtvfzqdaca.html

[A07] 数字转字符串
来源：http://dali.ydzc1.top/Article/details/gtbufuwfvt.html

Py:   str(42)
来源：http://dali.haohaochexian.top/Article/details/gttpnitmbu.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhiwuduotai.top/Article/details/gttywjyyah.html

JS:   String(42); (42).toString()
来源：http://dali.hnqzz.top/Article/details/gtetnopxot.html

TS:   String(42)
来源：http://dali.nanxinkj.top/Article/details/gtcrcujvsu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhoulong.xyz/Article/details/gtmwhmucqa.html

Go:   strconv.Itoa(42)
来源：http://dali.svipenyu.cn/Article/details/gtmvxnixaf.html

Ruby: 42.to_s
来源：http://dali.jlsjyb.cn/Article/details/gtnobgzzyj.html

C#:   42.ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gtocyvdjed.html

[A08] 取整与四舍五入
来源：http://dali.nwbrower.top/Article/details/gtcjgixpoc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.birdmap.top/Article/details/gtnxnbydjg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hywenlv.cn/Article/details/gtaijotscy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shuidangran.top/Article/details/gteivixxww.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.chenjidiqi.icu/Article/details/gtvxhxbrpl.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cheryme.top/Article/details/gtpliwkiin.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtdmtxghyj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xylfe.cn/Article/details/gteookqlws.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtxopmgjov.html

[A09] 绝对值与最大最小值
来源：http://dali.mhx1999.top/Article/details/gtvfksemjr.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtrdauhrtd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtelariklt.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtxvbronel.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtkliatxvx.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.sweek.top/Article/details/gtnpfvqzmm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jqgufenzy.top/Article/details/gtcypcqfzr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.birdmap.top/Article/details/gtpqvogpjt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtrafwwhly.html

[A10] 生成随机数
来源：http://dali.xinyue.icu/Article/details/gttnjomngq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cqqwz.cn/Article/details/gtibpsmsrg.html

PHP:  random_int(1, 100);
来源：http://dali.sysykeji.top/Article/details/gtffcjaanc.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tianlin.xyz/Article/details/gtmniqdfqc.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fzhhl.top/Article/details/gtkftqgmnu.html

Java: new Random().nextInt(100) + 1
来源：http://dali.guannengcc.top/Article/details/gtakfbwhqq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xziqi.cn/Article/details/gtqkygowil.html

Ruby: rand(1..100)
来源：http://dali.dashuyun.cn/Article/details/gtvhezmjsa.html

C#:   new Random().Next(1, 101)
来源：http://dali.andypj.xyz/Article/details/gtvjakovlu.html

[A11] 条件表达式（三元）
来源：http://dali.tanke756.top/Article/details/gtvalijsni.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yvedp.cn/Article/details/gtfhncigfj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefrodpsx.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gtnybviqdm.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwgaerwd.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzalplhd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.wangdashe.top/Article/details/gtncvvmkxu.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtzqetzhyt.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gtkjdpbsel.html

[A12] 字符串插值 / 格式化
来源：http://dali.jlsjyb.cn/Article/details/gtodmzohwe.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavxjqavg.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ybcxt.top/Article/details/gtcayqyppe.html

JS:   `Hello, ${name}!`
来源：http://dali.cheryme.top/Article/details/gtekpxfhbd.html

TS:   `Hello, ${name}!`
来源：http://dali.wangshuangyany.cn/Article/details/gtyrmemarb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jqgfzy.top/Article/details/gtywhfagvf.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.gogol.net.cn/Article/details/gtkajgapio.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhongyouzk.top/Article/details/gtdwwocpgw.html

C#:   $"Hello, {name}!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbkwbqml.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhengqikj.top/Article/details/gtzroammnb.html

Py:   "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gtklfdlucu.html

PHP:  "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtbuhbrdco.html

JS:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtqimqydmz.html

TS:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtrxpubiic.html

Java: "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtgebnmjni.html

Go:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gtwpajdjuv.html

Ruby: "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gtlsbomboq.html

C#:   "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtkrreytyl.html

[A14] 注释写法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxsfuzbe.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.gaohongyu789.top/Article/details/gtfkcnrshb.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gtbhvitned.html

JS:   // 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gtzcwejouc.html

TS:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gtkupmtwdv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.fzhhl.top/Article/details/gtayvhsjey.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhengqikj.top/Article/details/gtcwerujlh.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.sxryk.cn/Article/details/gttwfjvxvc.html

C#:   // 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gthptxexro.html

[A15] 空值判断与默认值
来源：http://dali.0kj1m.cn/Article/details/gtxfckkvwn.html

Py:   value = data or "默认值"
来源：http://dali.jiagoushi.top/Article/details/gthvrimjfb.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yj20258888.top/Article/details/gtzutyukjz.html

JS:   const value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gtntzjfsxr.html

TS:   const value = data ?? "默认值";
来源：http://dali.fengsongda.top/Article/details/gtolkdmcjt.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ppjwa.cn/Article/details/gtgscjtjnb.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.snrcjt.cn/Article/details/gtaovonrwl.html

Ruby: value = data || "默认值"
来源：http://dali.gzhubu.top/Article/details/gtmiltbfim.html

C#:   var value = data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gteryeazpm.html

[A16] 真假值判断规则
来源：http://dali.zycfv.cn/Article/details/gtklxcjmht.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.cdnleiting.top/Article/details/gtenufnjfy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.mhx1999.top/Article/details/gtxbqfzxld.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.316326.xyz/Article/details/gtngqlrrqf.html

TS:   if (!x) {}
来源：http://dali.jianghu66.top/Article/details/gtwadgktvl.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.gogol.net.cn/Article/details/gtiysjlirx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhiwuduotai.top/Article/details/gtiabkabdm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.guannengcc.top/Article/details/gtjmzpiyjs.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yuanzhike.top/Article/details/gtjwwojhwe.html

[A17] 位运算
来源：http://dali.yvedp.cn/Article/details/gtoouwutnl.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gtwgjulxgk.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtbcexwkpu.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gthrhiiajp.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtyazdvjys.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gtsccfmlbe.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtmvdhwpxl.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258888.top/Article/details/gtkdquexnb.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzorqnaf.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shzxlz.cn/Article/details/gtohkhlctn.html

Py:   ord("A"); chr(65)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtguoqqtiw.html

PHP:  ord("A"); chr(65)
来源：http://dali.hfpthk.cn/Article/details/gtmvjlivhj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.havefunace.top/Article/details/gtrypkyywe.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yueranfly.top/Article/details/gtsusmmpzi.html

Java: (int) 'A'; (char) 65
来源：http://dali.bjfxy.top/Article/details/gtduuhzmal.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.chenlongwang.top/Article/details/gtyvksauyh.html

Ruby: "A".ord; 65.chr
来源：http://dali.316326.xyz/Article/details/gtdjetkkcm.html


<!-- 参考信息 -->