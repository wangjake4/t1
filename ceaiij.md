代发 wailian999

[U103] JS：定时器
来源：http://dali.redwolf501.top/Article/details/gtyofbklvq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinqigfzy.top/Article/details/gthoflbhue.html

[U104] JS：防抖
来源：http://dali.cucudq.cn/Article/details/gtdouctvco.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtqktdpmzx.html

[U105] JS：节流
来源：http://dali.jyoumei.cn/Article/details/gtsrzldddw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fengsongda.top/Article/details/gtzqdfybjd.html

[U106] JS：日期格式化
来源：http://dali.hammf.cn/Article/details/gtleakfbra.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hfpthk.cn/Article/details/gtsimnshwy.html

[U107] JS：数字千分位
来源：http://dali.xuanzx.com/Article/details/gtizvoebfb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.smart0.xyz/Article/details/gtbsvqxrsu.html

[U108] JS：随机整数
来源：http://dali.cucudq.cn/Article/details/gtsygrmvln.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hnqzz.top/Article/details/gtbfhemfyo.html

[U109] JS：数组分组
来源：http://dali.zhiwuduotai.top/Article/details/gtfyygzdvs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gtltmeteob.html

[U110] JS：数组分块
来源：http://dali.feifeiyinyue.top/Article/details/gtmbrxwusj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yanxiufei.cn/Article/details/gtpdmysuin.html

[U111] JS：对象转 Map
来源：http://dali.cdnleiting.top/Article/details/gtxtmlohcw.html

new Map(Object.entries(obj))
来源：http://dali.sufxvd.cn/Article/details/gtmlvzcmzl.html

[U112] JS：字符串补位
来源：http://dali.yuanzhike.top/Article/details/gtvavzuqep.html

"7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgmmkvuy.html

[U113] JS：正则替换全部
来源：http://dali.vqdsnc.cn/Article/details/gtjgbufxxa.html

s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtvcyshqbi.html

[U114] JS：JSON 深比较
来源：http://dali.chenlongwang.top/Article/details/gtadvnucli.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yonumen.top/Article/details/gtbdmhzikn.html

[U115] JS：生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gtawizfpay.html

crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtkjbqblnc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.pengpengdd.cyou/Article/details/gtopfilxoj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkeuruyrl.html

[U117] JS：单元测试
来源：http://dali.gogol.net.cn/Article/details/gtccsgprxb.html

npm i -D vitest;  npx vitest
来源：http://dali.tian-w.cn/Article/details/gtzegbwnec.html

[U118] JS：开发服务器
来源：http://dali.yonumen.top/Article/details/gtyteneanq.html

npm i -D vite;  npx vite
来源：http://dali.jyoumei.cn/Article/details/gtqrxamblj.html

[U119] JS：生产构建
来源：http://dali.jqgufenzy.top/Article/details/gtdtbqmphl.html

npx vite build
来源：http://dali.316326.xyz/Article/details/gtwgfckblc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.meibo888.top/Article/details/gtczpkfkgl.html

import.meta.env.VITE_API_URL
来源：http://dali.zdqjudy.top/Article/details/gtwxxftwxs.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzxxbbixn.html

统计汇总
来源：http://dali.jqgfzy.top/Article/details/gtfmhzqxyj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtrzcphxyy.html

按语言统计（条）：
来源：http://dali.yj202588.top/Article/details/gtnonibmqp.html

Python ......... 252
来源：http://dali.yj20258888.top/Article/details/gtgvnvhrcd.html

PHP ............ 252
来源：http://dali.xuanzx.com/Article/details/gtadmzebwo.html

JavaScript ..... 252
来源：http://dali.gzhubu.top/Article/details/gtzckdmoih.html

TypeScript ..... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtdxyygnra.html

Java ........... 212
来源：http://dali.nanxinkj.top/Article/details/gtmhuckeji.html

Go ............. 212
来源：http://dali.hywenlv.cn/Article/details/gtcxucjndw.html

Ruby ........... 212
来源：http://dali.smart0.xyz/Article/details/gtyrvlxsmw.html

C# ............. 212
来源：http://dali.yonumen.top/Article/details/gtsvjajftz.html

C .............. 30
来源：http://dali.cqqwz.cn/Article/details/gtkuymwixv.html

C++ ............ 30
来源：http://dali.yuanzhike.top/Article/details/gtzyrpctze.html

SQL ............ 90
来源：http://dali.xylfe.cn/Article/details/gtexffoywb.html

Bash ........... 80
来源：http://dali.nanxinkj.top/Article/details/gtpfuzhvtq.html

Kotlin ......... 15
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpdgzzhp.html

Swift .......... 15
来源：http://dali.nanxuanxn.top/Article/details/gtagcgjadg.html

Lua ............ 10
来源：http://dali.tanke756.top/Article/details/gtwazcpbpo.html

Perl ........... 10
来源：http://dali.316326.xyz/Article/details/gtteqtsggg.html

Scala .......... 10
来源：http://dali.c1oappe.top/Article/details/gtckuigtej.html

------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtozuzkxvv.html

合计 ........... 2106 条
来源：http://dali.jyoumei.cn/Article/details/gtnehnyiof.html

按章节统计：
来源：http://dali.xinyue.icu/Article/details/gtbhzfobqx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gaohongyu789.top/Article/details/gtywaughjc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gtwjnqdeip.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gtkthrjerk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hnqzz.top/Article/details/gtbmeybocj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.guowangkeji.top/Article/details/gtazpomutq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.316326.xyz/Article/details/gtdbsmuuqv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gtedbpkeey.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gogol.net.cn/Article/details/gtxmhrfibt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtjiktgjsn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yanxiufei.cn/Article/details/gtvywrdjva.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtbmtbsxpz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gtdjetdveh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtcdvsvfkl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafuykkat.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenlongwang.top/Article/details/gtcpefvrug.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtgvjazrsg.html

Q SQL 专题                              90
来源：http://dali.jqgufenzy.top/Article/details/gtpuzordyo.html

R Bash 专题                             80
来源：http://dali.ybcxt.top/Article/details/gtpgegoicj.html

S C / C++ 专题                          60
来源：http://dali.daria6918.cn/Article/details/gtfcqzmoru.html

T 其他语言补充                          60
来源：http://dali.nwbrower.top/Article/details/gtpivpsomv.html

U 高频实用片段                         120
来源：http://dali.chenjidiqi.icu/Article/details/gtdlloxjpx.html

------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtztbvfrdk.html

合计                                  2106 条
来源：http://dali.dashuyun.cn/Article/details/gtgstrzxfv.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtqymmsixr.html

使用提醒
来源：http://dali.xuanzx.com/Article/details/gtxvmerbtn.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gtkemawwzg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.pycfn.com/Article/details/gtysogxazd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tanke756.top/Article/details/gtsgguzkwq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuanzx.com/Article/details/gttyztujjh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.fengsongda.top/Article/details/gtcorpobrw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ydzc1.top/Article/details/gtqbyqkkhh.html

—— 文件结束 ——
来源：http://dali.0kj1m.cn/Article/details/gtihcflejy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtwtwzsswf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ppjwa.cn/Article/details/gtekvtvbde.html

Common Programming Examples Cheat Book
来源：http://dali.sufxvd.cn/Article/details/gtqrcmosdx.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtvoymuabd.html

【收录内容】
来源：http://dali.dashuyun.cn/Article/details/gtsxyyxyea.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.svipenyu.cn/Article/details/gtorjmkfhq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yvedp.cn/Article/details/gthmwarmye.html

SQL · Bash · C · C++
来源：http://dali.tianlin.xyz/Article/details/gtbfkpelve.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yangfankeji.com/Article/details/gtbpbjksjj.html

【使用说明】
来源：http://dali.jianghu66.top/Article/details/gtteskpgoa.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhixingplan.top/Article/details/gtulskligj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hywenlv.cn/Article/details/gtqbceqpmt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yvedp.cn/Article/details/gtulvbqxlo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sxryk.cn/Article/details/gtnabpluoy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tianlin.xyz/Article/details/gtdbugqlkf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cucudq.cn/Article/details/gtrelmrocg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jianghu66.top/Article/details/gtafggtpot.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zdqjudy.top/Article/details/gtjxiqbklf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yangfankeji.com/Article/details/gtdgwkmojt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.havefunace.top/Article/details/gtkymepmux.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gzhubu.top/Article/details/gtjeklzjxi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.havefunace.top/Article/details/gttigcytcs.html

【文件统计】
来源：http://dali.pycfn.com/Article/details/gtfpyvoego.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.svipenyu.cn/Article/details/gttrzymhjf.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtbaiuvyan.html

目  录
来源：http://dali.tianlin.xyz/Article/details/gtwgfooawi.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnrpaohm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddkpsfrd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtcyvhsvwg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.fengsongda.top/Article/details/gtgngjihta.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.c1oappe.top/Article/details/gtkugselph.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jiagoushi.top/Article/details/gtoudethqr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtypowhbyx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtfihxokum.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtubkchvmk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gtdghfaaiw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinqigufen.top/Article/details/gtxnovisro.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtzzwpxrmw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtplpxtueb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gtdcmqadax.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xylfe.cn/Article/details/gtayrjolmg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sweek.top/Article/details/gtopwijnei.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gtqjuelzsb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sysykeji.top/Article/details/gthoroqmpo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yongpay.top/Article/details/gtpkiszzgc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gaohongyu789.top/Article/details/gttdewfcsv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gtosptocdx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.quarkkingdee.top/Article/details/gtngoiyjkr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtgsbpjxhd.html

A. 基础语法与类型
来源：http://dali.jlsjyb.cn/Article/details/gttbljkfbt.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtbruypaey.html

[A01] Hello World
来源：http://dali.hysaishi.cn/Article/details/gtvdrditmr.html

Py:   print("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gttagzqyfn.html

PHP:  echo "Hello, World!";
来源：http://dali.cdnleiting.top/Article/details/gtfbfjqako.html

JS:   console.log("Hello, World!");
来源：http://dali.ivvv.top/Article/details/gtmxpmbgpn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.andypj.xyz/Article/details/gttatzzhiy.html

Java: System.out.println("Hello, World!");
来源：http://dali.guannengcc.top/Article/details/gtfjtndtga.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shangyingyoupin.top/Article/details/gtmqjylyyt.html

Ruby: puts "Hello, World!"
来源：http://dali.ivvv.top/Article/details/gtmamdvfsp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xylfe.cn/Article/details/gtepunqtng.html

[A02] 变量声明与赋值
来源：http://dali.yvedp.cn/Article/details/gtgvbrlhuf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjfjjuoc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.svipenyu.cn/Article/details/gtjnsgurva.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.guannengcc.top/Article/details/gtsupbxezn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.svipenyu.cn/Article/details/gtiguentwt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtuzlrufve.html

Go:   name := "Alex"; age := 20
来源：http://dali.yanxiufei.cn/Article/details/gtresvbpix.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nanxinkj.top/Article/details/gtnwjvnise.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zycfv.cn/Article/details/gtokymraeu.html

[A03] 常量定义
来源：http://dali.fengsongda.top/Article/details/gttzrbafqq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yonumen.top/Article/details/gtodvrzenm.html

PHP:  const PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtaxsmuers.html

JS:   const PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtyxghtmkt.html

TS:   const PI: number = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtouvumnkt.html

Java: static final double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtjjtbanqi.html

Go:   const PI = 3.14159
来源：http://dali.svipenyu.cn/Article/details/gtnldjkolg.html

Ruby: PI = 3.14159
来源：http://dali.jinqigufen.top/Article/details/gtrinmahsu.html

C#:   const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtgsclffnz.html

[A04] 判断变量类型
来源：http://dali.wangdashe.top/Article/details/gthcjbpfpv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.guannengcc.top/Article/details/gtbiuqydrl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.kuanghao11.cn/Article/details/gtadqnvxnl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.iojbl.cn/Article/details/gtojvemnbn.html

TS:   typeof x; x instanceof Date
来源：http://dali.yonumen.top/Article/details/gtushjihdk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.haohaochexian.top/Article/details/gthyswxwws.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpirmbdip.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.mhx1999.top/Article/details/gtkzmunysj.html

C#:   x.GetType().Name; x is int
来源：http://dali.yanxiufei.cn/Article/details/gtuexsshna.html

[A05] 整数除法与取模
来源：http://dali.quarkkingdee.top/Article/details/gtahaapszs.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.smart0.xyz/Article/details/gtnitvajiy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtywmntfik.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sweek.top/Article/details/gtljnlwfda.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gtonkoxuoo.html

Java: 7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtpzeybpfo.html

Go:   7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtraycznzb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gtnsjgzzxa.html

C#:   7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtfuhtybbw.html

[A06] 字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gtxiatsnui.html

Py:   int("42"); float("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gtftwwbemr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ehwqpu.com/Article/details/gtkxyvfdzp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqgdnwse.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlczxcnej.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.bjfxy.top/Article/details/gtvhssnwdp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfslalyqv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ivvv.top/Article/details/gtwltlsdbb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nanxuanxn.top/Article/details/gtnbtzszuk.html

[A07] 数字转字符串
来源：http://dali.mhx1999.top/Article/details/gtocwfqcne.html

Py:   str(42)
来源：http://dali.kuanghao11.cn/Article/details/gtnvmnqkyg.html

PHP:  (string) 42; strval(42)
来源：http://dali.havefunace.top/Article/details/gtxgkcccqt.html

JS:   String(42); (42).toString()
来源：http://dali.ybcxt.top/Article/details/gtzgyxovwg.html

TS:   String(42)
来源：http://dali.chenlongwang.top/Article/details/gttvivdpzx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuxqfdit.html

Go:   strconv.Itoa(42)
来源：http://dali.9152youxi.cn/Article/details/gtjjmueezw.html

Ruby: 42.to_s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibspodfq.html

C#:   42.ToString()
来源：http://dali.andypj.xyz/Article/details/gthuododwa.html

[A08] 取整与四舍五入
来源：http://dali.yongpay.top/Article/details/gtirikuujn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwtffytp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yj202588.top/Article/details/gtfqwqlsos.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gtekvvbjrr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ivvv.top/Article/details/gtcoduokzi.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gthunmdigg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yj20258.top/Article/details/gtbahqkkko.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.iojbl.cn/Article/details/gtepyeudnz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gtwihitptp.html

[A09] 绝对值与最大最小值
来源：http://dali.0kj1m.cn/Article/details/gtciskmnjh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gtdoaxyexv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtsioejekd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cashguo.top/Article/details/gtkestwjbi.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtokvetyjc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtofbnefyi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hammf.cn/Article/details/gtrziesgwl.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ppjwa.cn/Article/details/gtsqijrikm.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ivvv.top/Article/details/gtwzsrhmlr.html

[A10] 生成随机数
来源：http://dali.smart0.xyz/Article/details/gtgpclgscg.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhongyouzk.top/Article/details/gtshlwhuie.html

PHP:  random_int(1, 100);
来源：http://dali.yanxiufei.cn/Article/details/gtjnxansxh.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cheryme.top/Article/details/gtpgvztmze.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ppjwa.cn/Article/details/gttzbkznqr.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jianghu66.top/Article/details/gtargocnbz.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.tianlin.xyz/Article/details/gtpikthhci.html

Ruby: rand(1..100)
来源：http://dali.yj20258.top/Article/details/gtqpiiihvb.html

C#:   new Random().Next(1, 101)
来源：http://dali.jqgufenzy.top/Article/details/gtcatfkuhm.html

[A11] 条件表达式（三元）
来源：http://dali.316326.xyz/Article/details/gthjltqoph.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.gotoacloud.top/Article/details/gtplgcgmlw.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.gzhubu.top/Article/details/gtegwcxnux.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gtattmstqz.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtukeiiywr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtmdoupurd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.smart0.xyz/Article/details/gtdahadzhp.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gttvudqeam.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.aibaodan.cn/Article/details/gtjsoadwru.html

[A12] 字符串插值 / 格式化
来源：http://dali.zycfv.cn/Article/details/gtkkxdalnx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.birdmap.top/Article/details/gtxddjzftq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvrkwweq.html

JS:   `Hello, ${name}!`
来源：http://dali.yonumen.top/Article/details/gtxdlifdfk.html

TS:   `Hello, ${name}!`
来源：http://dali.wangdashe.top/Article/details/gthlyvbqhs.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.haohaochexian.top/Article/details/gtgbdyuxkl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtqczsyetn.html

Ruby: "Hello, #{name}!"
来源：http://dali.sysykeji.top/Article/details/gtvgetzcgt.html

C#:   $"Hello, {name}!"
来源：http://dali.havefunace.top/Article/details/gtbsjyagcx.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xylfe.cn/Article/details/gttonuyaja.html

Py:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtpradmabw.html

PHP:  "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsrrlsql.html

JS:   "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gtxcxehoph.html

TS:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtfpnjhizb.html

Java: "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtkojvxzdx.html

Go:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gttffbxylf.html

Ruby: "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gthrqooqxz.html

C#:   "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gtxdigvjri.html

[A14] 注释写法
来源：http://dali.hysaishi.cn/Article/details/gtlllufpce.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shanyushiyangtech.top/Article/details/gtntsrpege.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjbdzhdz.html

JS:   // 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gtmhouarxj.html

TS:   // 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gtylaieodv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.mhx1999.top/Article/details/gtfxybjvtf.html

Go:   // 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gtjwuvmrhk.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.cucudq.cn/Article/details/gtmuxpfros.html

C#:   // 单行；/* 多行 */
来源：http://dali.snrcjt.cn/Article/details/gtaybbukag.html

[A15] 空值判断与默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnibkmmf.html

Py:   value = data or "默认值"
来源：http://dali.yangfankeji.com/Article/details/gteumqccfk.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.tanke756.top/Article/details/gtwdbflaiu.html

JS:   const value = data ?? "默认值";
来源：http://dali.nwbrower.top/Article/details/gtiopprxor.html

TS:   const value = data ?? "默认值";
来源：http://dali.feifeiyinyue.top/Article/details/gtlhemrswj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.guannengcc.top/Article/details/gtleoqywbv.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shangyingyoupin.top/Article/details/gtrrwtmhon.html

Ruby: value = data || "默认值"
来源：http://dali.jianghu66.top/Article/details/gtjykanvvc.html

C#:   var value = data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gtkahzztmj.html

[A16] 真假值判断规则
来源：http://dali.ybcxt.top/Article/details/gtrnqobfdb.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jlsjyb.cn/Article/details/gtbynarfcs.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.svipenyu.cn/Article/details/gtvxwthwah.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.ydzc1.top/Article/details/gtkasvniig.html

TS:   if (!x) {}
来源：http://dali.gaohongyu789.top/Article/details/gtjsltprzw.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjsfvwmpv.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.chenlongwang.top/Article/details/gtqxrdyygv.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.daxiang520.top/Article/details/gtwvginsnd.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.birdmap.top/Article/details/gtxybpsdnk.html

[A17] 位运算
来源：http://dali.cashguo.top/Article/details/gtpkelxiqk.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtkfjjcmon.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigossueu.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gtbfkotmso.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gtpbirfqox.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtmwmflqej.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtqbeoypmj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gteoaqewik.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtudbjmjlc.html

[A18] 字符与 ASCII 码互转
来源：http://dali.aibaodan.cn/Article/details/gtulynsrpm.html

Py:   ord("A"); chr(65)
来源：http://dali.xylfe.cn/Article/details/gtbrzftpja.html

PHP:  ord("A"); chr(65)
来源：http://dali.hnqzz.top/Article/details/gtmqwpfcto.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ydzc1.top/Article/details/gtpmglcvnv.html


<!-- 参考信息 -->