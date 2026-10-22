代发 wailian999

[U105] JS：节流
来源：http://dali.xuetiantiany.cn/Article/details/gthjhmuwwe.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gteslsdted.html

[U106] JS：日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtxwgpoykq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jyoumei.cn/Article/details/gtuawlfisv.html

[U107] JS：数字千分位
来源：http://dali.hammf.cn/Article/details/gtbovgsubg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.daria6918.cn/Article/details/gtgkhplaez.html

[U108] JS：随机整数
来源：http://dali.bjfxy.top/Article/details/gtrwgtrqpm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yonumen.top/Article/details/gtkchsmmse.html

[U109] JS：数组分组
来源：http://dali.ivvv.top/Article/details/gtxpnvvnko.html

Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gtmqajlrcj.html

[U110] JS：数组分块
来源：http://dali.zdqjudy.top/Article/details/gtrihtilis.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xuetiantiany.cn/Article/details/gtkxnqcvlf.html

[U111] JS：对象转 Map
来源：http://dali.fzhhl.top/Article/details/gtbpsoqanj.html

new Map(Object.entries(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gtchmronar.html

[U112] JS：字符串补位
来源：http://dali.wangdashe.top/Article/details/gtufwrkksq.html

"7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gthvmcbhpo.html

[U113] JS：正则替换全部
来源：http://dali.shanyushiyangtech.top/Article/details/gtiacttbho.html

s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtfbcbnjoh.html

[U114] JS：JSON 深比较
来源：http://dali.sweek.top/Article/details/gtulpsvtku.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gtqzjmonvo.html

[U115] JS：生成 UUID
来源：http://dali.sysykeji.top/Article/details/gtcauitnds.html

crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtoyloykjg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sysykeji.top/Article/details/gtdsyrtgvm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.aizwys.cn/Article/details/gtauagnykz.html

[U117] JS：单元测试
来源：http://dali.jqgufenzy.top/Article/details/gtsujphbml.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigufen.top/Article/details/gtzkidmqwh.html

[U118] JS：开发服务器
来源：http://dali.feifeiyinyue.top/Article/details/gtvhmxtjin.html

npm i -D vite;  npx vite
来源：http://dali.shzxlz.cn/Article/details/gtnzitazxx.html

[U119] JS：生产构建
来源：http://dali.smart0.xyz/Article/details/gtidteywuu.html

npx vite build
来源：http://dali.jlsjyb.cn/Article/details/gtyinihdnr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.vqdsnc.cn/Article/details/gtvaeaojqy.html

import.meta.env.VITE_API_URL
来源：http://dali.jiagoushi.top/Article/details/gtjznffvlc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtifxizjgh.html

统计汇总
来源：http://dali.redwolf501.top/Article/details/gtjnotvepg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvquhbslg.html

按语言统计（条）：
来源：http://dali.hfpthk.cn/Article/details/gtfmyyrwnb.html

Python ......... 252
来源：http://dali.cqqwz.cn/Article/details/gteujgpkqf.html

PHP ............ 252
来源：http://dali.hfpthk.cn/Article/details/gtazrvgopz.html

JavaScript ..... 252
来源：http://dali.ydzc1.top/Article/details/gtnwopwibu.html

TypeScript ..... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtkewtydni.html

Java ........... 212
来源：http://dali.daria6918.cn/Article/details/gtqxlzacll.html

Go ............. 212
来源：http://dali.xinyue.icu/Article/details/gtqhrwyqfn.html

Ruby ........... 212
来源：http://dali.yangfankeji.com/Article/details/gtceqliyqo.html

C# ............. 212
来源：http://dali.316326.xyz/Article/details/gtivgnzlhn.html

C .............. 30
来源：http://dali.vqdsnc.cn/Article/details/gtrwvxzqxa.html

C++ ............ 30
来源：http://dali.shanyushiyangtech.top/Article/details/gtsupednun.html

SQL ............ 90
来源：http://dali.hysaishi.cn/Article/details/gtcjhebenm.html

Bash ........... 80
来源：http://dali.c1oappe.top/Article/details/gtsovosxne.html

Kotlin ......... 15
来源：http://dali.sweek.top/Article/details/gtxgfcgrfw.html

Swift .......... 15
来源：http://dali.ppjwa.cn/Article/details/gtzlpwpbcg.html

Lua ............ 10
来源：http://dali.sxryk.cn/Article/details/gtchrxzqjx.html

Perl ........... 10
来源：http://dali.hywenlv.cn/Article/details/gtxaisixlf.html

Scala .......... 10
来源：http://dali.cqqwz.cn/Article/details/gtrfwkvhui.html

------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtchjdfjep.html

合计 ........... 2106 条
来源：http://dali.tanke756.top/Article/details/gtpahmvcgh.html

按章节统计：
来源：http://dali.ydzc1.top/Article/details/gtfggmdtaj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.snrcjt.cn/Article/details/gtvnywrosb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gtulmlndal.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtybaufemw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cashguo.top/Article/details/gtoknvpbzb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gtbqthpjzx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gotoacloud.top/Article/details/gtdhjxgwsn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gthdiuxbhk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tanke756.top/Article/details/gteqojnret.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtaywytsmd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gtqjgrvbqm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtutemphwa.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gttqemiybs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtnvceygaf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.nwbrower.top/Article/details/gtomdpdnss.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcwwazxn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtbvyxtdyo.html

Q SQL 专题                              90
来源：http://dali.shuidangran.top/Article/details/gtvpmvplxv.html

R Bash 专题                             80
来源：http://dali.yueranfly.top/Article/details/gtjmshpwhx.html

S C / C++ 专题                          60
来源：http://dali.ydzc1.top/Article/details/gteguphfme.html

T 其他语言补充                          60
来源：http://dali.zhongyouzk.top/Article/details/gtmkumebtj.html

U 高频实用片段                         120
来源：http://dali.nanxinkj.top/Article/details/gtixlsbszw.html

------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtzglfwzsv.html

合计                                  2106 条
来源：http://dali.ybcxt.top/Article/details/gtjaihhhob.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtwifyzcul.html

使用提醒
来源：http://dali.ywan-chungtsiang.top/Article/details/gttshrxnte.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtlbuaohqt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ppjwa.cn/Article/details/gtprgflqdz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuanzx.com/Article/details/gtrwhyphwk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhoulong.xyz/Article/details/gtpuqdratl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shuidangran.top/Article/details/gtgjhbhkof.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.smart0.xyz/Article/details/gtuqjpnaok.html

—— 文件结束 ——
来源：http://dali.yj202588.top/Article/details/gtkrtzutyg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtllfjicuz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj20258.top/Article/details/gtmfmqeanh.html

Common Programming Examples Cheat Book
来源：http://dali.jianghu66.top/Article/details/gtpjkqpbpf.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtqwxubvws.html

【收录内容】
来源：http://dali.yonumen.top/Article/details/gtpkkdazns.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.wangdashe.top/Article/details/gtadlbfobb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhengqikj.top/Article/details/gttbgxhoco.html

SQL · Bash · C · C++
来源：http://dali.zhixingplan.top/Article/details/gtvanbojqd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.feifeiyinyue.top/Article/details/gtuelkysnk.html

【使用说明】
来源：http://dali.ybcxt.top/Article/details/gtjqhspwlg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.gzhubu.top/Article/details/gtekwvvfql.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.fzhhl.top/Article/details/gtjakylpbu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xylfe.cn/Article/details/gtfyqpfekl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.havefunace.top/Article/details/gtmgrakreg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ydzc1.top/Article/details/gthsneucha.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.dashuyun.cn/Article/details/gtynccvixu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.haohaochexian.top/Article/details/gtyjxubpjh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.meibo888.top/Article/details/gtwxizocmu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yj20258.top/Article/details/gtoltlgsft.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gzhubu.top/Article/details/gtbxcsxflg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ppjwa.cn/Article/details/gtljznwzkq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ppjwa.cn/Article/details/gtzjjprdxq.html

【文件统计】
来源：http://dali.sweek.top/Article/details/gtklzvives.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.tian-w.cn/Article/details/gtsgdbwrsh.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtwrqumlxq.html

目  录
来源：http://dali.quarkkingdee.top/Article/details/gtxwuqezmp.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtvyxzxlij.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nwbrower.top/Article/details/gtuhxiuebz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhoulong.xyz/Article/details/gtdjbnayvs.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gogol.net.cn/Article/details/gtouuagxby.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhixingplan.top/Article/details/gteafzqlzp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xziqi.cn/Article/details/gtkasxcgsq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yvedp.cn/Article/details/gtjrpcxtod.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.gogol.net.cn/Article/details/gtugqazwrh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.316326.xyz/Article/details/gtjppvjumv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gtoezfxgwb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.chenzaomai.com/Article/details/gtskboccnd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtwilwidoe.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtylgmulel.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtyoqlpjci.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yuanzhike.top/Article/details/gtojpgpory.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xinyue.icu/Article/details/gtrlbgidwc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gtdkjfhwtc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.tian-w.cn/Article/details/gtfboacjdw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhixingplan.top/Article/details/gtbsubnutr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gaohongyu789.top/Article/details/gtntrrrlyy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gtjqcbywpg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtnlomtmdr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpojhewkb.html

A. 基础语法与类型
来源：http://dali.0kj1m.cn/Article/details/gtyrthyxgl.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthswfmrta.html

[A01] Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtvivrkatd.html

Py:   print("Hello, World!")
来源：http://dali.hnxiangtu.top/Article/details/gtyffprejm.html

PHP:  echo "Hello, World!";
来源：http://dali.cqqwz.cn/Article/details/gtwwsusrtb.html

JS:   console.log("Hello, World!");
来源：http://dali.sweek.top/Article/details/gtooylgier.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ybcxt.top/Article/details/gtxawbafoa.html

Java: System.out.println("Hello, World!");
来源：http://dali.cheryme.top/Article/details/gteigidvnz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyikojoi.html

Ruby: puts "Hello, World!"
来源：http://dali.hnqzz.top/Article/details/gtmbqqxgbd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrkwherp.html

[A02] 变量声明与赋值
来源：http://dali.cucudq.cn/Article/details/gtphpbseba.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.haohaochexian.top/Article/details/gtdtbsfqpz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hammf.cn/Article/details/gtggnhbglx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yuanzhike.top/Article/details/gttawmbpor.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hfpthk.cn/Article/details/gtopgqdsdd.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hywenlv.cn/Article/details/gtoaevjjec.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhoulong.xyz/Article/details/gtfghnlbet.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hfpthk.cn/Article/details/gtagwgqoim.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.redwolf501.top/Article/details/gthodwmnsk.html

[A03] 常量定义
来源：http://dali.shzxlz.cn/Article/details/gtrnsdgbvz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkchtdmoi.html

PHP:  const PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtkzwrgqbc.html

JS:   const PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtjyvimwke.html

TS:   const PI: number = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtsuofmmjy.html

Java: static final double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtptadlbaz.html

Go:   const PI = 3.14159
来源：http://dali.hysaishi.cn/Article/details/gtifymycvv.html

Ruby: PI = 3.14159
来源：http://dali.zhengqikj.top/Article/details/gtlhthtxjq.html

C#:   const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gthgklrypb.html

[A04] 判断变量类型
来源：http://dali.nanxinkj.top/Article/details/gtgbvbzalm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.quarkkingdee.top/Article/details/gtlpbkvrrk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yueranfly.top/Article/details/gtahllbvqx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hnxiangtu.top/Article/details/gtjzavvwwd.html

TS:   typeof x; x instanceof Date
来源：http://dali.jiagoushi.top/Article/details/gtrtqozffo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.snrcjt.cn/Article/details/gtqmfqwlfo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzuesidf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.c1oappe.top/Article/details/gtfauyyjqf.html

C#:   x.GetType().Name; x is int
来源：http://dali.jqgufenzy.top/Article/details/gtzoyjgkxv.html

[A05] 整数除法与取模
来源：http://dali.svipenyu.cn/Article/details/gtqpglgygj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinqigfzy.top/Article/details/gtiwiooyya.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtayvpuoyu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtrfngjmqf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gtsvqdihvo.html

Java: 7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtilusnjuy.html

Go:   7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtktgyeuei.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtbjmzsslt.html

C#:   7 / 2; 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gtyihjxplx.html

[A06] 字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gthbdarahw.html

Py:   int("42"); float("3.14")
来源：http://dali.c1oappe.top/Article/details/gtmvwladeb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jianghu66.top/Article/details/gtnqjaahrq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xziqi.cn/Article/details/gtbzwpkdhy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.nanxinkj.top/Article/details/gtlvodogrb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.tianlin.xyz/Article/details/gtpgptpcjq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhengqikj.top/Article/details/gtzyufjgxv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cqqwz.cn/Article/details/gtrmjrlbno.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.iojbl.cn/Article/details/gtxivlrvyn.html

[A07] 数字转字符串
来源：http://dali.guannengcc.top/Article/details/gtosyqrvdn.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gtcyueyfqg.html

PHP:  (string) 42; strval(42)
来源：http://dali.nanxinkj.top/Article/details/gtjoszdwcr.html

JS:   String(42); (42).toString()
来源：http://dali.ppjwa.cn/Article/details/gtzpipdclg.html

TS:   String(42)
来源：http://dali.316326.xyz/Article/details/gtphthyugy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.dashuyun.cn/Article/details/gtuwanvlhv.html

Go:   strconv.Itoa(42)
来源：http://dali.tianlin.xyz/Article/details/gthxoavuet.html

Ruby: 42.to_s
来源：http://dali.xuetiantiany.cn/Article/details/gtpxnjhieu.html

C#:   42.ToString()
来源：http://dali.hfpthk.cn/Article/details/gtgxwlbekg.html

[A08] 取整与四舍五入
来源：http://dali.xylfe.cn/Article/details/gtbrqpryyg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gtbethnemy.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.bjfxy.top/Article/details/gtdwydefaj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.havefunace.top/Article/details/gtokvymxza.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.wangshuangyany.cn/Article/details/gtiwerngle.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxixdsyvv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.316326.xyz/Article/details/gtdhrvfamm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.c1oappe.top/Article/details/gtxbmcxdqm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtuqpmcoor.html

[A09] 绝对值与最大最小值
来源：http://dali.yuxming.cn/Article/details/gthqconovm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gteeagbjrl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtciceaffm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtpdumrpuw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtullqhrhw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfugvmjz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.kuanghao11.cn/Article/details/gtfkyasvbl.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhixingplan.top/Article/details/gtfcuuzoig.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtofhhcwmk.html

[A10] 生成随机数
来源：http://dali.nanxinkj.top/Article/details/gteknnruzu.html

Py:   import random; random.randint(1, 100)
来源：http://dali.quarkkingdee.top/Article/details/gtxxffmjcv.html

PHP:  random_int(1, 100);
来源：http://dali.wangdashe.top/Article/details/gtkgnjatvs.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guannengcc.top/Article/details/gtarrtipjo.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xuetiantiany.cn/Article/details/gtnrqfxyir.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj20258.top/Article/details/gtrudrnjzd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.sweek.top/Article/details/gtpwzkemak.html

Ruby: rand(1..100)
来源：http://dali.dashuyun.cn/Article/details/gtanzmyuyd.html

C#:   new Random().Next(1, 101)
来源：http://dali.yanxiufei.cn/Article/details/gtxqifewgq.html

[A11] 条件表达式（三元）
来源：http://dali.fengsongda.top/Article/details/gtxktoxxnq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jqgufenzy.top/Article/details/gtqdrqdygp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtvnkcacrc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtvpsmyslc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtmkahycys.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtdkipfizq.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhiwuduotai.top/Article/details/gtpkmugnku.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gtzafntjpl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gtmezttelb.html

[A12] 字符串插值 / 格式化
来源：http://dali.snrcjt.cn/Article/details/gtfyxlerwm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.gotoacloud.top/Article/details/gtwsoncnbe.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.fzhhl.top/Article/details/gtttgntsqd.html

JS:   `Hello, ${name}!`
来源：http://dali.jinghuilouyu.cn/Article/details/gtadgdfuiq.html

TS:   `Hello, ${name}!`
来源：http://dali.tianlin.xyz/Article/details/gtgkirjfln.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.dianchejie.cn/Article/details/gtoauwhyug.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.guowangkeji.top/Article/details/gtbximutep.html

Ruby: "Hello, #{name}!"
来源：http://dali.hongshengwenyu.top/Article/details/gtxmiwhksw.html

C#:   $"Hello, {name}!"
来源：http://dali.zhongyouzk.top/Article/details/gtrilkoqsr.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sufxvd.cn/Article/details/gtjdcgpkwe.html

Py:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtohxldhja.html

PHP:  "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtcldzyokw.html

JS:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gtqxufndxs.html

TS:   "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gtvplijctz.html

Java: "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtbtzprkob.html

Go:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gtzuyrvsqv.html

Ruby: "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gttoyrnfoo.html

C#:   "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gtkbcjhpam.html

[A14] 注释写法
来源：http://dali.jianghu66.top/Article/details/gtzausnywu.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yvedp.cn/Article/details/gtyjgcizqd.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvfyxjpw.html

JS:   // 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gtovskgdxp.html

TS:   // 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gtoirchdxm.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.sweek.top/Article/details/gtaxatdsql.html

Go:   // 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gtuuemdcav.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.sufxvd.cn/Article/details/gtwumiqrqo.html

C#:   // 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gtrijzbpyu.html

[A15] 空值判断与默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahirljid.html

Py:   value = data or "默认值"
来源：http://dali.yueranfly.top/Article/details/gtzwylabpl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gtrvzmuxzg.html

JS:   const value = data ?? "默认值";
来源：http://dali.xziqi.cn/Article/details/gtzmpmbylo.html

TS:   const value = data ?? "默认值";
来源：http://dali.tanke756.top/Article/details/gtivplbubv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hysaishi.cn/Article/details/gtrgigymle.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.cucudq.cn/Article/details/gtcvqcrets.html

Ruby: value = data || "默认值"
来源：http://dali.yonumen.top/Article/details/gtwupygfug.html

C#:   var value = data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpezmxwrs.html

[A16] 真假值判断规则
来源：http://dali.yongpay.top/Article/details/gtkpwrwbcy.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ehwqpu.com/Article/details/gtukhxnqih.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.chenlongwang.top/Article/details/gtwwpgmerm.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zdqjudy.top/Article/details/gterfkkaxo.html

TS:   if (!x) {}
来源：http://dali.nanxuanxn.top/Article/details/gttwbexkkd.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.snrcjt.cn/Article/details/gtbtekxqvr.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.sxryk.cn/Article/details/gtxcgiubpq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhoulong.xyz/Article/details/gtlugalkuk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shuidangran.top/Article/details/gtkhbrhgef.html

[A17] 位运算
来源：http://dali.hnxiangtu.top/Article/details/gtypwcgcal.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gtzpiaebbe.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtyruijfis.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gtpnzhppej.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtpdmdqsvj.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gtiryhtium.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtxovjezrx.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gtwgsepjoo.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtawemqhvk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.iojbl.cn/Article/details/gtmyomkvex.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gtchiaeves.html

PHP:  ord("A"); chr(65)
来源：http://dali.xziqi.cn/Article/details/gtdofbwvuy.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tianlin.xyz/Article/details/gtzcrmqrcq.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhoulong.xyz/Article/details/gtxdobybxo.html

Java: (int) 'A'; (char) 65
来源：http://dali.hammf.cn/Article/details/gtsluyqwgw.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.havefunace.top/Article/details/gtgrtzogap.html

Ruby: "A".ord; 65.chr
来源：http://dali.sweek.top/Article/details/gtunxktvvw.html


<!-- 参考信息 -->