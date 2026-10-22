代发 wailian999

[U105] JS：节流
来源：http://dali.jlsjyb.cn/Article/details/gtumexlezd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhongyouzk.top/Article/details/gtabogtxnl.html

[U106] JS：日期格式化
来源：http://dali.nwbrower.top/Article/details/gtbrmwicyg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jyoumei.cn/Article/details/gtgujcwdeg.html

[U107] JS：数字千分位
来源：http://dali.andypj.xyz/Article/details/gtwksmashj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gzhubu.top/Article/details/gtwgjmijzn.html

[U108] JS：随机整数
来源：http://dali.316326.xyz/Article/details/gtdfeoazcp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yj20258888.top/Article/details/gtoiyetgio.html

[U109] JS：数组分组
来源：http://dali.yueranfly.top/Article/details/gtmywbegwn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gtjaqqevqt.html

[U110] JS：数组分块
来源：http://dali.tianlin.xyz/Article/details/gtlkbrlttd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.bjfxy.top/Article/details/gtshuoybtf.html

[U111] JS：对象转 Map
来源：http://dali.yueranfly.top/Article/details/gtblxruqge.html

new Map(Object.entries(obj))
来源：http://dali.snrcjt.cn/Article/details/gtwcvtvtlz.html

[U112] JS：字符串补位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkmqtnys.html

"7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtpceykmzo.html

[U113] JS：正则替换全部
来源：http://dali.daxiang520.top/Article/details/gtrcbgrosc.html

s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtjyzdtyva.html

[U114] JS：JSON 深比较
来源：http://dali.chenlongwang.top/Article/details/gtvwahezqx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gtuyncftvq.html

[U115] JS：生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gtxaqbqhil.html

crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtkpzyrqvq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnxiangtu.top/Article/details/gtoshzqcex.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cdnleiting.top/Article/details/gtelxajoxz.html

[U117] JS：单元测试
来源：http://dali.yongpay.top/Article/details/gtrbdhciqn.html

npm i -D vitest;  npx vitest
来源：http://dali.iojbl.cn/Article/details/gtivwgdlgp.html

[U118] JS：开发服务器
来源：http://dali.nwbrower.top/Article/details/gtjhniazmd.html

npm i -D vite;  npx vite
来源：http://dali.yangfankeji.com/Article/details/gtrwbxzkgc.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsnhsfyb.html

npx vite build
来源：http://dali.316326.xyz/Article/details/gtaqftmlnk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenzaomai.com/Article/details/gtniawohey.html

import.meta.env.VITE_API_URL
来源：http://dali.yvedp.cn/Article/details/gtyxcdubrp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjpuulbcw.html

统计汇总
来源：http://dali.bjfxy.top/Article/details/gtnumhuorj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtgzwrzxdx.html

按语言统计（条）：
来源：http://dali.cheryme.top/Article/details/gtxzsvplgf.html

Python ......... 252
来源：http://dali.jiagoushi.top/Article/details/gtmxshyxkg.html

PHP ............ 252
来源：http://dali.iojbl.cn/Article/details/gtcwpbhjli.html

JavaScript ..... 252
来源：http://dali.hywenlv.cn/Article/details/gtkyhyfxjv.html

TypeScript ..... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtgienzrry.html

Java ........... 212
来源：http://dali.bjfxy.top/Article/details/gtbnaqhnbm.html

Go ............. 212
来源：http://dali.gotoacloud.top/Article/details/gtresczeus.html

Ruby ........... 212
来源：http://dali.yangfankeji.com/Article/details/gtxnimsiht.html

C# ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjczpphmb.html

C .............. 30
来源：http://dali.jinqigufen.top/Article/details/gtyrkzefrm.html

C++ ............ 30
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczgapkrw.html

SQL ............ 90
来源：http://dali.jiagoushi.top/Article/details/gtacabdcxy.html

Bash ........... 80
来源：http://dali.chenzaomai.com/Article/details/gtqgukxyhs.html

Kotlin ......... 15
来源：http://dali.feifeiyinyue.top/Article/details/gtjxmhljkj.html

Swift .......... 15
来源：http://dali.wangdashe.top/Article/details/gtjrckuhec.html

Lua ............ 10
来源：http://dali.yangfankeji.com/Article/details/gtaaqdxhvj.html

Perl ........... 10
来源：http://dali.fzhhl.top/Article/details/gtbpvvalsa.html

Scala .......... 10
来源：http://dali.xziqi.cn/Article/details/gtnxsbniji.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gtfxsfsall.html

合计 ........... 2106 条
来源：http://dali.haohaochexian.top/Article/details/gtdejcalgp.html

按章节统计：
来源：http://dali.hnxiangtu.top/Article/details/gttfslyczd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj202588.top/Article/details/gtdxexvdkd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gtdluingzp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gtrfxbdxdq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gtdwiqfced.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fzhhl.top/Article/details/gthckofzuz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.nwbrower.top/Article/details/gthsxrvabu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gtrdyfuape.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenjidiqi.icu/Article/details/gtqjaxmexw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gtgofkavml.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gtjjhtzpaw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtgwtrkuzt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtxltxjrsh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtzzqqpk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.c1oappe.top/Article/details/gthubcvgab.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xinyue.icu/Article/details/gthpkniylq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtdeoghqqr.html

Q SQL 专题                              90
来源：http://dali.hysaishi.cn/Article/details/gtrlztmfbn.html

R Bash 专题                             80
来源：http://dali.pengpengdd.cyou/Article/details/gtkbihmtok.html

S C / C++ 专题                          60
来源：http://dali.quarkkingdee.top/Article/details/gtilpzclcr.html

T 其他语言补充                          60
来源：http://dali.zdqjudy.top/Article/details/gteqrmepod.html

U 高频实用片段                         120
来源：http://dali.iojbl.cn/Article/details/gturzlydpo.html

------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gthxseaawq.html

合计                                  2106 条
来源：http://dali.sxryk.cn/Article/details/gthmbbluss.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gtekqyluvn.html

使用提醒
来源：http://dali.guowangkeji.top/Article/details/gttlgbpxms.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gthdjggrpk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yvedp.cn/Article/details/gtuuvomjtz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.vqdsnc.cn/Article/details/gtabsgqapx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinqigfzy.top/Article/details/gtuglwxwjd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.bjfxy.top/Article/details/gtwwxswjau.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.svipenyu.cn/Article/details/gtqdenaztb.html

—— 文件结束 ——
来源：http://dali.iojbl.cn/Article/details/gtgihtjsfu.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrnffferf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jlsjyb.cn/Article/details/gtkpzhaena.html

Common Programming Examples Cheat Book
来源：http://dali.yuanzhike.top/Article/details/gtlnbraagl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtbhtxrbeh.html

【收录内容】
来源：http://dali.quarkkingdee.top/Article/details/gtiappsqyx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.wangdashe.top/Article/details/gtksndgnas.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sxryk.cn/Article/details/gtmdlyqzlp.html

SQL · Bash · C · C++
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhyywrxq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.andypj.xyz/Article/details/gtqjgjyjmk.html

【使用说明】
来源：http://dali.yanxiufei.cn/Article/details/gtojucemog.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hongshengwenyu.top/Article/details/gteogqnmlq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.snrcjt.cn/Article/details/gtozirruyl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.smart0.xyz/Article/details/gtmdoldcwz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xinyue.icu/Article/details/gthdrilcmu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuanzhike.top/Article/details/gttfteefgy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jlsjyb.cn/Article/details/gtkcfyvpnd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yonumen.top/Article/details/gtcoccksaq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cashguo.top/Article/details/gtaehqdagi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenzaomai.com/Article/details/gtqywjkqua.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.feifeiyinyue.top/Article/details/gtwiewcjqf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zdqjudy.top/Article/details/gttbgmcuce.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.9152youxi.cn/Article/details/gtfvolehwi.html

【文件统计】
来源：http://dali.yj202588.top/Article/details/gtcapobsyt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hongshengwenyu.top/Article/details/gtpsxgsmyj.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gtpqcxeoef.html

目  录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfjsasxl.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtoolxoxtm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xuanzx.com/Article/details/gtjctpvfck.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gtjziqxaes.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkeenoogb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gtxhoprads.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xuanzx.com/Article/details/gtriyuliqh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yanxiufei.cn/Article/details/gtqndqmsna.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gtvzyxwzwb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinqigfzy.top/Article/details/gttcvdxhfy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtmkuqyijh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.aizwys.cn/Article/details/gtyrpkiqmc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtqrccyglq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gticmjvfbm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtkugdibsg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.wangdashe.top/Article/details/gtxxveilgg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtaqsbzmfs.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gtchzwnljt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sxryk.cn/Article/details/gtmytwbsbp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hywenlv.cn/Article/details/gttptojjqg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.birdmap.top/Article/details/gtnrbsifgc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtfdoewkec.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gtcgyyvxtb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtdunjnpdp.html

A. 基础语法与类型
来源：http://dali.aibaodan.cn/Article/details/gtqfbzhdxu.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtzmckawfh.html

[A01] Hello World
来源：http://dali.zycfv.cn/Article/details/gteriffglu.html

Py:   print("Hello, World!")
来源：http://dali.shuidangran.top/Article/details/gthkwrrhhy.html

PHP:  echo "Hello, World!";
来源：http://dali.bjfxy.top/Article/details/gtiouerotq.html

JS:   console.log("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gtwgcrgxeu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zycfv.cn/Article/details/gtzgffurgm.html

Java: System.out.println("Hello, World!");
来源：http://dali.shangyingyoupin.top/Article/details/gtxslppvym.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.feifeiyinyue.top/Article/details/gtmkdzqdem.html

Ruby: puts "Hello, World!"
来源：http://dali.xziqi.cn/Article/details/gtmeeqbzay.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cucudq.cn/Article/details/gtdvtirsjl.html

[A02] 变量声明与赋值
来源：http://dali.hnxiangtu.top/Article/details/gtbunuigwi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhiwuduotai.top/Article/details/gtppomqfqs.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhengqikj.top/Article/details/gtabeaymuy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtcawayzew.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jinqigufen.top/Article/details/gtmzpqcykp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.havefunace.top/Article/details/gtwhdtmozc.html

Go:   name := "Alex"; age := 20
来源：http://dali.hywenlv.cn/Article/details/gtfdhmguvb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yj20258.top/Article/details/gtvpvdtkyr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtzeuaclcy.html

[A03] 常量定义
来源：http://dali.pengpengdd.cyou/Article/details/gtvcrxvmxm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcfhtobq.html

PHP:  const PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtdqejngqn.html

JS:   const PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtvikfngbs.html

TS:   const PI: number = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtpumlcozo.html

Java: static final double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtxxwsdvuh.html

Go:   const PI = 3.14159
来源：http://dali.chenlongwang.top/Article/details/gtcmioaitb.html

Ruby: PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gthwnjsiix.html

C#:   const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtsdzbfxch.html

[A04] 判断变量类型
来源：http://dali.shzxlz.cn/Article/details/gtawystgmu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.chenzaomai.com/Article/details/gtcpboczki.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gaohongyu789.top/Article/details/gtislleuxt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jlsjyb.cn/Article/details/gtnodjkttw.html

TS:   typeof x; x instanceof Date
来源：http://dali.cheryme.top/Article/details/gtbtlosxbw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.fzhhl.top/Article/details/gtzgutifyt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.guowangkeji.top/Article/details/gtmnlvgnzt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.haohaochexian.top/Article/details/gtihonwlgm.html

C#:   x.GetType().Name; x is int
来源：http://dali.gaohongyu789.top/Article/details/gttbmhkpms.html

[A05] 整数除法与取模
来源：http://dali.hammf.cn/Article/details/gtvaluaqkg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yj20258.top/Article/details/gtbbhoktkh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtsugemkwi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtqqfuovya.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gthlaracul.html

Java: 7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtpnicsyzz.html

Go:   7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtibjwsvfv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gtebcqezkq.html

C#:   7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtlvaslhhb.html

[A06] 字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gthzyslaoq.html

Py:   int("42"); float("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydyozcpq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zycfv.cn/Article/details/gtdqdvgqck.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hongshengwenyu.top/Article/details/gtqcxdmwjj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.haohaochexian.top/Article/details/gtedsmnjzu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yongpay.top/Article/details/gtwprrflrs.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sweek.top/Article/details/gtauncujbj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yonumen.top/Article/details/gtgsntyabe.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.pengpengdd.cyou/Article/details/gtuabmwsty.html

[A07] 数字转字符串
来源：http://dali.bjfxy.top/Article/details/gtgstykeby.html

Py:   str(42)
来源：http://dali.yangfankeji.com/Article/details/gtwuaapnmg.html

PHP:  (string) 42; strval(42)
来源：http://dali.cashguo.top/Article/details/gttqegdqel.html

JS:   String(42); (42).toString()
来源：http://dali.cqqwz.cn/Article/details/gtgsywigdn.html

TS:   String(42)
来源：http://dali.wangshuangyany.cn/Article/details/gtcrhscprd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hnxiangtu.top/Article/details/gtofvafkvb.html

Go:   strconv.Itoa(42)
来源：http://dali.iojbl.cn/Article/details/gtcrsuqqyh.html

Ruby: 42.to_s
来源：http://dali.cucudq.cn/Article/details/gtcbmaeurd.html

C#:   42.ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gtlcqkrfzm.html

[A08] 取整与四舍五入
来源：http://dali.xylfe.cn/Article/details/gtehtrnwtd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvorkzlzb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.andypj.xyz/Article/details/gtbrlrxxhi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtkdhyclbm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.fengsongda.top/Article/details/gtkxaacnjk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gtgfuvdilm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtucyyzclo.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.0kj1m.cn/Article/details/gtbqsowpgm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtjgonxpvj.html

[A09] 绝对值与最大最小值
来源：http://dali.sxryk.cn/Article/details/gtwhwrhfha.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtjkfmsmgn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtadbvthpb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtfvrpgwkg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtqaigzaax.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtpitiajxv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xziqi.cn/Article/details/gtbzfpfnou.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jinqigfzy.top/Article/details/gtnntbdzrj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xylfe.cn/Article/details/gteritsavt.html

[A10] 生成随机数
来源：http://dali.vqdsnc.cn/Article/details/gtthtyajgv.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shzxlz.cn/Article/details/gtkwflfhvu.html

PHP:  random_int(1, 100);
来源：http://dali.hywenlv.cn/Article/details/gteyumqsmx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hnxiangtu.top/Article/details/gtvgaaznhj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shangyingyoupin.top/Article/details/gtkfadtpfd.html

Java: new Random().nextInt(100) + 1
来源：http://dali.gzhubu.top/Article/details/gtndhfyeeg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.redwolf501.top/Article/details/gtzmxirexk.html

Ruby: rand(1..100)
来源：http://dali.guannengcc.top/Article/details/gtcgooaota.html

C#:   new Random().Next(1, 101)
来源：http://dali.jiagoushi.top/Article/details/gtzflvfzgj.html

[A11] 条件表达式（三元）
来源：http://dali.gotoacloud.top/Article/details/gtunvjvsue.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.smart0.xyz/Article/details/gtxdyjxjcu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gtnapgbqaf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtadenyido.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xuanzx.com/Article/details/gtwmtvtvia.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtqvryjwtf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.cashguo.top/Article/details/gtxqoyaeae.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gtveohsaee.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gtztibwyfl.html

[A12] 字符串插值 / 格式化
来源：http://dali.iojbl.cn/Article/details/gtruyxvazt.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hnxiangtu.top/Article/details/gtchvjiqir.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hongshengwenyu.top/Article/details/gtxfmlueri.html

JS:   `Hello, ${name}!`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrxoucil.html

TS:   `Hello, ${name}!`
来源：http://dali.quarkkingdee.top/Article/details/gttzbkcxgb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrxuqbbo.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ydzc1.top/Article/details/gtqyydjpca.html

Ruby: "Hello, #{name}!"
来源：http://dali.dashuyun.cn/Article/details/gteqrgqbfr.html

C#:   $"Hello, {name}!"
来源：http://dali.hnqzz.top/Article/details/gttmvdevvg.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yvedp.cn/Article/details/gtaojftzbl.html

Py:   "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gttvedtqhl.html

PHP:  "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtefznpevk.html

JS:   "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtwfsfdmlt.html

TS:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtsaylsefy.html

Java: "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gtysranffk.html

Go:   "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gthxzqlkns.html

Ruby: "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gthqrpjeqz.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtilkpsuwk.html

[A14] 注释写法
来源：http://dali.shanyushiyangtech.top/Article/details/gtndbsyxhk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.birdmap.top/Article/details/gtkgpsdlyc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.ppjwa.cn/Article/details/gtcyvbvfdy.html

JS:   // 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gttidohlix.html

TS:   // 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gtwfmysynm.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.tian-w.cn/Article/details/gtjjxzvfme.html

Go:   // 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gtzrlmulxd.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jinghuilouyu.cn/Article/details/gtxckgcmju.html

C#:   // 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gtokwsfyvv.html

[A15] 空值判断与默认值
来源：http://dali.hongshengwenyu.top/Article/details/gtgckaefts.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gtsqzcjhaq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.pycfn.com/Article/details/gtyjclkhvw.html

JS:   const value = data ?? "默认值";
来源：http://dali.hnxiangtu.top/Article/details/gthsesfsgm.html

TS:   const value = data ?? "默认值";
来源：http://dali.yuxming.cn/Article/details/gttmlnmvbk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrgiildo.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yuanzhike.top/Article/details/gtdffendtw.html

Ruby: value = data || "默认值"
来源：http://dali.hysaishi.cn/Article/details/gtuhaufljp.html

C#:   var value = data ?? "默认值";
来源：http://dali.gzhubu.top/Article/details/gtiajdtzte.html

[A16] 真假值判断规则
来源：http://dali.sweek.top/Article/details/gthfdoykxi.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhengqikj.top/Article/details/gtagatlcdf.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhiwuduotai.top/Article/details/gtsjfrdnxi.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cheryme.top/Article/details/gtprgqiyjj.html

TS:   if (!x) {}
来源：http://dali.ivvv.top/Article/details/gtckywerhw.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.0kj1m.cn/Article/details/gtrrqhzfcm.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.sufxvd.cn/Article/details/gtclrvslyj.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.wangshuangyany.cn/Article/details/gtsdftgekd.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtvofnedwc.html

[A17] 位运算
来源：http://dali.zycfv.cn/Article/details/gtmmxpvosj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gtsteafuzj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtjkzaaggo.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtiqvtrldd.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtlwdhsdgf.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gtfssfvabj.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtbcmfsayr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gttthlhuhn.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gtmkhxvqgf.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hnqzz.top/Article/details/gtbdtzeclt.html

Py:   ord("A"); chr(65)
来源：http://dali.yj20258.top/Article/details/gtpvtbcjde.html

PHP:  ord("A"); chr(65)
来源：http://dali.gzhubu.top/Article/details/gtzxrsxsdd.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.vqdsnc.cn/Article/details/gtfxlyoqun.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.redwolf501.top/Article/details/gtqizbvoax.html

Java: (int) 'A'; (char) 65
来源：http://dali.xuetiantiany.cn/Article/details/gtyaigpmxl.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.aibaodan.cn/Article/details/gtscueffat.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gtoqsmmooa.html


<!-- 参考信息 -->