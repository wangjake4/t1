代发 wailian999

[U105] JS：节流
来源：http://dali.xuetiantiany.cn/Article/details/gtjtbthxwv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gaohongyu789.top/Article/details/gtgahlzots.html

[U106] JS：日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gttvudhtks.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xziqi.cn/Article/details/gtjtvcwvby.html

[U107] JS：数字千分位
来源：http://dali.fzhhl.top/Article/details/gtrlfhqmus.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xylfe.cn/Article/details/gtdxlbqtal.html

[U108] JS：随机整数
来源：http://dali.0kj1m.cn/Article/details/gtrosrhmfw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daria6918.cn/Article/details/gturaqdegz.html

[U109] JS：数组分组
来源：http://dali.iojbl.cn/Article/details/gtsaqdgxlr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gtydzurdkj.html

[U110] JS：数组分块
来源：http://dali.vqdsnc.cn/Article/details/gtfosyoqlz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.aizwys.cn/Article/details/gtahqsxpyp.html

[U111] JS：对象转 Map
来源：http://dali.xuanzx.com/Article/details/gthgevlrbs.html

new Map(Object.entries(obj))
来源：http://dali.yvedp.cn/Article/details/gtqbkzrtcg.html

[U112] JS：字符串补位
来源：http://dali.birdmap.top/Article/details/gtsxrnhlqv.html

"7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtzpudlmud.html

[U113] JS：正则替换全部
来源：http://dali.xylfe.cn/Article/details/gtjmkxbxsu.html

s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtqgzuozkd.html

[U114] JS：JSON 深比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenvbqcmf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gtjxnjhjnj.html

[U115] JS：生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtjbwutnoe.html

crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtusyakcpr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenzaomai.com/Article/details/gtlwmtorpv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daria6918.cn/Article/details/gtwrhthckb.html

[U117] JS：单元测试
来源：http://dali.pycfn.com/Article/details/gthcgoywwd.html

npm i -D vitest;  npx vitest
来源：http://dali.pycfn.com/Article/details/gtkyrsudlt.html

[U118] JS：开发服务器
来源：http://dali.zycfv.cn/Article/details/gtzzbhweuk.html

npm i -D vite;  npx vite
来源：http://dali.cashguo.top/Article/details/gtsneebysj.html

[U119] JS：生产构建
来源：http://dali.ydzc1.top/Article/details/gtwsuxjobu.html

npx vite build
来源：http://dali.shuidangran.top/Article/details/gtwzmahmto.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gzhubu.top/Article/details/gtcdfbzccq.html

import.meta.env.VITE_API_URL
来源：http://dali.xinyue.icu/Article/details/gthmoonmby.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtapcstdbq.html

统计汇总
来源：http://dali.hongshengwenyu.top/Article/details/gtvoqwtjnd.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtdyhaswvp.html

按语言统计（条）：
来源：http://dali.sweek.top/Article/details/gtljdvfkoc.html

Python ......... 252
来源：http://dali.yj202588.top/Article/details/gtittajlco.html

PHP ............ 252
来源：http://dali.jinqigfzy.top/Article/details/gtvotpdnis.html

JavaScript ..... 252
来源：http://dali.shuidangran.top/Article/details/gthacotwuk.html

TypeScript ..... 212
来源：http://dali.316326.xyz/Article/details/gtxwgwocoq.html

Java ........... 212
来源：http://dali.bjfxy.top/Article/details/gtiryjdkwv.html

Go ............. 212
来源：http://dali.pengpengdd.cyou/Article/details/gtpngroqxd.html

Ruby ........... 212
来源：http://dali.tanke756.top/Article/details/gtjjbvamxx.html

C# ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gtdfeqoems.html

C .............. 30
来源：http://dali.yanxiufei.cn/Article/details/gtbgsfxtxl.html

C++ ............ 30
来源：http://dali.fzhhl.top/Article/details/gtdmievsdn.html

SQL ............ 90
来源：http://dali.ivvv.top/Article/details/gtrtzblohz.html

Bash ........... 80
来源：http://dali.havefunace.top/Article/details/gtbboemdce.html

Kotlin ......... 15
来源：http://dali.mhx1999.top/Article/details/gtxmxwalvy.html

Swift .......... 15
来源：http://dali.nanxuanxn.top/Article/details/gtopktqiny.html

Lua ............ 10
来源：http://dali.chenjidiqi.icu/Article/details/gtrzvcdmul.html

Perl ........... 10
来源：http://dali.feifeiyinyue.top/Article/details/gtykpnpgql.html

Scala .......... 10
来源：http://dali.zhongyouzk.top/Article/details/gtnyutrfyo.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtnxymunrn.html

合计 ........... 2106 条
来源：http://dali.jlsjyb.cn/Article/details/gtgnnybnzf.html

按章节统计：
来源：http://dali.hammf.cn/Article/details/gtrkjuminn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gtkpxdhser.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqtiprrg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gttdbyyvte.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sxryk.cn/Article/details/gtneabssgc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sxryk.cn/Article/details/gtdmpqdltp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yvedp.cn/Article/details/gtvkhojvch.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gthmnfrvng.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.andypj.xyz/Article/details/gtkfybjxbt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gtgkjgsjmt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gtogskhakw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtrkgrdquz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gttnltnluk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtjjgmltvr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shangyingyoupin.top/Article/details/gthnzxalcw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.aizwys.cn/Article/details/gtjpheccpf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gtfguiepbn.html

Q SQL 专题                              90
来源：http://dali.zdqjudy.top/Article/details/gtoishjvow.html

R Bash 专题                             80
来源：http://dali.c1oappe.top/Article/details/gtcfepusmw.html

S C / C++ 专题                          60
来源：http://dali.chenjidiqi.icu/Article/details/gtwnewmbbo.html

T 其他语言补充                          60
来源：http://dali.pengpengdd.cyou/Article/details/gtwetrxpbv.html

U 高频实用片段                         120
来源：http://dali.yuanzhike.top/Article/details/gtnwcpdbko.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtdybweocn.html

合计                                  2106 条
来源：http://dali.gzhubu.top/Article/details/gtzighqser.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtjmbpkkhg.html

使用提醒
来源：http://dali.xinyue.icu/Article/details/gtnnxgkuer.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtpbobyipn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yueranfly.top/Article/details/gtsactjqyi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.bjfxy.top/Article/details/gthqxdjvub.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.316326.xyz/Article/details/gthlrvkurt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenzaomai.com/Article/details/gtdfuujgsj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.iojbl.cn/Article/details/gtbgtcogii.html

—— 文件结束 ——
来源：http://dali.ppjwa.cn/Article/details/gtgjrdlvpz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtncncddka.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gtqfqlccks.html

Common Programming Examples Cheat Book
来源：http://dali.yueranfly.top/Article/details/gtnovuhbqk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtxypdqcwc.html

【收录内容】
来源：http://dali.jianghu66.top/Article/details/gticmytgbo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhoulong.xyz/Article/details/gtqmeppuwn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhongyouzk.top/Article/details/gtpdpuvaca.html

SQL · Bash · C · C++
来源：http://dali.316326.xyz/Article/details/gtvqxfpzdu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.guannengcc.top/Article/details/gteigteqer.html

【使用说明】
来源：http://dali.daxiang520.top/Article/details/gtdunnsslw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.iojbl.cn/Article/details/gtjgzwtsya.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.bjfxy.top/Article/details/gtzgnlbxxz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.redwolf501.top/Article/details/gtntqupjod.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zycfv.cn/Article/details/gtnppszynb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.316326.xyz/Article/details/gtycyepcpz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdekcztj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.tian-w.cn/Article/details/gtyxudaeal.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ydzc1.top/Article/details/gtqgtvivrq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.guannengcc.top/Article/details/gtaqviwego.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tianlin.xyz/Article/details/gtmsjkfnuk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnllgrbg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.c1oappe.top/Article/details/gtqcrsqcqq.html

【文件统计】
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbopgajqw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jqgfzy.top/Article/details/gttensoufd.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gtywulmkhy.html

目  录
来源：http://dali.vqdsnc.cn/Article/details/gtlrrrjkwt.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtbthpcpob.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj202588.top/Article/details/gtxgbfwsee.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xylfe.cn/Article/details/gthienoiza.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtxxpujbyk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gtvqnyffrn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.fengsongda.top/Article/details/gtsfpcjkqo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrtqlxrn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gtzpsksqqi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xinyue.icu/Article/details/gtpfvdzokz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtplmyblpk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shzxlz.cn/Article/details/gtqbxhpnlg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoeqkbtxr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtykrdltvl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gtfqvgxtmi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.redwolf501.top/Article/details/gtppsbzxao.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.316326.xyz/Article/details/gtgpmfykrt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtzvlmopnp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.kuanghao11.cn/Article/details/gtqeeugqfg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hywenlv.cn/Article/details/gttmyhpjsn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ppjwa.cn/Article/details/gttoyghirb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gtfpydobgu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.smart0.xyz/Article/details/gtnszjuwjv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtcurtrczb.html

A. 基础语法与类型
来源：http://dali.xinyue.icu/Article/details/gtoiqoodhp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcigvedxw.html

[A01] Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtekhhyuqa.html

Py:   print("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gtbmlacrjl.html

PHP:  echo "Hello, World!";
来源：http://dali.jlsjyb.cn/Article/details/gtknoeuflx.html

JS:   console.log("Hello, World!");
来源：http://dali.zhengqikj.top/Article/details/gtoudrdtfj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhoulong.xyz/Article/details/gtmcgdgqny.html

Java: System.out.println("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gtdxgiabdl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yonumen.top/Article/details/gtmntnbzlo.html

Ruby: puts "Hello, World!"
来源：http://dali.ivvv.top/Article/details/gtcvraoaec.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xylfe.cn/Article/details/gtempqntvp.html

[A02] 变量声明与赋值
来源：http://dali.sxryk.cn/Article/details/gtzhztdgrw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.bjfxy.top/Article/details/gtfdzldjuu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.havefunace.top/Article/details/gtlvnqqcrv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xziqi.cn/Article/details/gtbdtrjgsi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hywenlv.cn/Article/details/gtgqhikfxy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.smart0.xyz/Article/details/gtrqgxkdkf.html

Go:   name := "Alex"; age := 20
来源：http://dali.9152youxi.cn/Article/details/gtedfmbtwp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cdnleiting.top/Article/details/gtlnlzflbv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gtafersauh.html

[A03] 常量定义
来源：http://dali.sweek.top/Article/details/gtajztpgkq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gzhubu.top/Article/details/gtllvjfpww.html

PHP:  const PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gthobmuqod.html

JS:   const PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtzkzuxwde.html

TS:   const PI: number = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtzqwbycch.html

Java: static final double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtgonluwwk.html

Go:   const PI = 3.14159
来源：http://dali.xziqi.cn/Article/details/gtufbusjyz.html

Ruby: PI = 3.14159
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfubsnoez.html

C#:   const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtxlcxtjae.html

[A04] 判断变量类型
来源：http://dali.ivvv.top/Article/details/gtrfdkmlqx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tanke756.top/Article/details/gtwiixdwas.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gaohongyu789.top/Article/details/gtiwtpgczj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ivvv.top/Article/details/gtyzgmqknk.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazcropbc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shzxlz.cn/Article/details/gtzfzoegpl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.birdmap.top/Article/details/gtxwgqstyz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gtxsgtpszu.html

C#:   x.GetType().Name; x is int
来源：http://dali.shangyingyoupin.top/Article/details/gtvhfmhehw.html

[A05] 整数除法与取模
来源：http://dali.wangshuangyany.cn/Article/details/gtijhukolo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.feifeiyinyue.top/Article/details/gtabiwwrtl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.tanke756.top/Article/details/gtgbzecqjo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gteatnallw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkhjfyhz.html

Java: 7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtbttkwrvr.html

Go:   7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtgtboduph.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gthxgzewjq.html

C#:   7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnujagvml.html

[A06] 字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gtvclsiqkw.html

Py:   int("42"); float("3.14")
来源：http://dali.xziqi.cn/Article/details/gtpwqtthky.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shuidangran.top/Article/details/gtnfdadrav.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xziqi.cn/Article/details/gthvpvokyh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ehwqpu.com/Article/details/gtjdusyyec.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yanxiufei.cn/Article/details/gtdizbvdau.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yuanzhike.top/Article/details/gtaupezjga.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.aizwys.cn/Article/details/gtzyatctei.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.cdnleiting.top/Article/details/gttyrihsyb.html

[A07] 数字转字符串
来源：http://dali.haohaochexian.top/Article/details/gtimolatxw.html

Py:   str(42)
来源：http://dali.zdqjudy.top/Article/details/gtghpxxsal.html

PHP:  (string) 42; strval(42)
来源：http://dali.chenjidiqi.icu/Article/details/gtkyieildd.html

JS:   String(42); (42).toString()
来源：http://dali.yj20258888.top/Article/details/gtufnevpde.html

TS:   String(42)
来源：http://dali.cucudq.cn/Article/details/gtdbanovba.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblywrylb.html

Go:   strconv.Itoa(42)
来源：http://dali.jinqigfzy.top/Article/details/gtfdsgiezk.html

Ruby: 42.to_s
来源：http://dali.zhengqikj.top/Article/details/gtxiqsdgar.html

C#:   42.ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gtfglposci.html

[A08] 取整与四舍五入
来源：http://dali.jlsjyb.cn/Article/details/gtfueplusv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gtegzguozy.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmyfruit.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtlawsnvrt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cheryme.top/Article/details/gtjtpacwfc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gteyabibjc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.havefunace.top/Article/details/gtkgtiwlzf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhongyouzk.top/Article/details/gtkvbnjjzy.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.gogol.net.cn/Article/details/gtfztaxwmo.html

[A09] 绝对值与最大最小值
来源：http://dali.kuanghao11.cn/Article/details/gtjxqvfaxo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuezeaes.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtccnhrhqt.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hammf.cn/Article/details/gtarcakjtu.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtlizhsnjh.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtmwjlpbof.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.tianlin.xyz/Article/details/gtbxavcgcv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.dashuyun.cn/Article/details/gtjbujsctc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.pycfn.com/Article/details/gtysdzzfyv.html

[A10] 生成随机数
来源：http://dali.gogol.net.cn/Article/details/gtdfqczjzq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.chenjidiqi.icu/Article/details/gtllnvredo.html

PHP:  random_int(1, 100);
来源：http://dali.zycfv.cn/Article/details/gtgkfnaxuy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sufxvd.cn/Article/details/gtikobtick.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sufxvd.cn/Article/details/gtfcuweehu.html

Java: new Random().nextInt(100) + 1
来源：http://dali.svipenyu.cn/Article/details/gtxzutrikr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gotoacloud.top/Article/details/gtgyraohgp.html

Ruby: rand(1..100)
来源：http://dali.aibaodan.cn/Article/details/gtbyvgbkgf.html

C#:   new Random().Next(1, 101)
来源：http://dali.hongshengwenyu.top/Article/details/gtmpcqejrl.html

[A11] 条件表达式（三元）
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmrmnzoo.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hfpthk.cn/Article/details/gtjzljdaen.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gtirnuxovu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gtuwfaokmc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gtppnasguq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gtswxbhtbt.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.haohaochexian.top/Article/details/gtlwfynffs.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.aibaodan.cn/Article/details/gtrngygsxd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gtgxakomwv.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinqigfzy.top/Article/details/gtpreqfnjw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.havefunace.top/Article/details/gtbelxvbkr.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.birdmap.top/Article/details/gtabsyloii.html

JS:   `Hello, ${name}!`
来源：http://dali.jinqigufen.top/Article/details/gtcfbdsnjq.html

TS:   `Hello, ${name}!`
来源：http://dali.jqgfzy.top/Article/details/gtsstimanu.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jianghu66.top/Article/details/gtvkslbaps.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.cdnleiting.top/Article/details/gtqgdjlikt.html

Ruby: "Hello, #{name}!"
来源：http://dali.chenlongwang.top/Article/details/gtthiqxkmt.html

C#:   $"Hello, {name}!"
来源：http://dali.bjfxy.top/Article/details/gtfplopjvj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.bjfxy.top/Article/details/gtcbjfykcn.html

Py:   "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtjyzcwtiy.html

PHP:  "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtrbugplpd.html

JS:   "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gtsbtafqco.html

TS:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gteggfgrgs.html

Java: "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtkhjovlbw.html

Go:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtbqjghmka.html

Ruby: "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtbeadzgmh.html

C#:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gteadnyvuu.html

[A14] 注释写法
来源：http://dali.yongpay.top/Article/details/gtcpohwgfl.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yangfankeji.com/Article/details/gtevzvpcfd.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gtzonnkttz.html

JS:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gtzukksomb.html

TS:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gtqfdhnszk.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hnxiangtu.top/Article/details/gtpqgzrfwz.html

Go:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gtkpqsaybw.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shangyingyoupin.top/Article/details/gtcyzpxpjo.html

C#:   // 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gthimmvaqs.html

[A15] 空值判断与默认值
来源：http://dali.yj202588.top/Article/details/gtmghzoqao.html

Py:   value = data or "默认值"
来源：http://dali.nwbrower.top/Article/details/gtoxdldkwu.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.redwolf501.top/Article/details/gtuklkesvs.html

JS:   const value = data ?? "默认值";
来源：http://dali.zycfv.cn/Article/details/gtwlpdkoxk.html

TS:   const value = data ?? "默认值";
来源：http://dali.0kj1m.cn/Article/details/gtpfekqxsl.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.tian-w.cn/Article/details/gtjqygnbua.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ivvv.top/Article/details/gtymalulrb.html

Ruby: value = data || "默认值"
来源：http://dali.yj20258.top/Article/details/gtvtztrxwd.html

C#:   var value = data ?? "默认值";
来源：http://dali.nanxuanxn.top/Article/details/gtpuxmeetw.html

[A16] 真假值判断规则
来源：http://dali.hywenlv.cn/Article/details/gtwlczdxil.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hywenlv.cn/Article/details/gtbewwhznp.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.c1oappe.top/Article/details/gtzksocedp.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.bjfxy.top/Article/details/gtocnzocqu.html

TS:   if (!x) {}
来源：http://dali.yanxiufei.cn/Article/details/gtpvqwlhxo.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hammf.cn/Article/details/gtjcdqtdvh.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yonumen.top/Article/details/gttyljfgsu.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ivvv.top/Article/details/gtnccvdtyj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hnqzz.top/Article/details/gtvzyqvrxx.html

[A17] 位运算
来源：http://dali.ppjwa.cn/Article/details/gtfjjbeujb.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtzjqbhszv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yueranfly.top/Article/details/gtmpsdvpig.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gtuiwykgdw.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtsrmirykd.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gtepsyiiem.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gthauzltfp.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtrychcxzk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtppmiwqqe.html

[A18] 字符与 ASCII 码互转
来源：http://dali.havefunace.top/Article/details/gtsylmpcjn.html

Py:   ord("A"); chr(65)
来源：http://dali.gotoacloud.top/Article/details/gtmektfoeb.html

PHP:  ord("A"); chr(65)
来源：http://dali.mhx1999.top/Article/details/gtwpyqyffn.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenjidiqi.icu/Article/details/gtodofxihn.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jiagoushi.top/Article/details/gttpfckief.html

Java: (int) 'A'; (char) 65
来源：http://dali.xziqi.cn/Article/details/gthhthpbnp.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.sysykeji.top/Article/details/gtwzxzydfv.html

Ruby: "A".ord; 65.chr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpqzumct.html


<!-- 参考信息 -->