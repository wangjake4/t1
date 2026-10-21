代发 wailian999

[U105] JS：节流
来源：http://dali.tian-w.cn/Article/details/gtipfrdiis.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zdqjudy.top/Article/details/gtimhrcnel.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gttbzejcew.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jqgfzy.top/Article/details/gtzwyrijkh.html

[U107] JS：数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtknecvbqg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gtxwijkmax.html

[U108] JS：随机整数
来源：http://dali.quarkkingdee.top/Article/details/gtivdcdkbh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinqigufen.top/Article/details/gtlhnmlsmj.html

[U109] JS：数组分组
来源：http://dali.yvedp.cn/Article/details/gtsedcaysb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmphktoge.html

[U110] JS：数组分块
来源：http://dali.cdnleiting.top/Article/details/gtbmcwcyvf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.fzhhl.top/Article/details/gterdlursi.html

[U111] JS：对象转 Map
来源：http://dali.svipenyu.cn/Article/details/gtdnmrcljy.html

new Map(Object.entries(obj))
来源：http://dali.jinqigfzy.top/Article/details/gtbkbrxzhj.html

[U112] JS：字符串补位
来源：http://dali.shzxlz.cn/Article/details/gtqfaabtit.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtiznsoqbt.html

[U113] JS：正则替换全部
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnsrsrba.html

s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtndfhflby.html

[U114] JS：JSON 深比较
来源：http://dali.ybcxt.top/Article/details/gtfrwjwsun.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gtgvdqtjav.html

[U115] JS：生成 UUID
来源：http://dali.yueranfly.top/Article/details/gtdnwgbrsl.html

crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtpisqzsns.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhengqikj.top/Article/details/gtriihvwvn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgxsivfqd.html

[U117] JS：单元测试
来源：http://dali.wangshuangyany.cn/Article/details/gtxkpcyufo.html

npm i -D vitest;  npx vitest
来源：http://dali.daria6918.cn/Article/details/gtmmzqwkcd.html

[U118] JS：开发服务器
来源：http://dali.guannengcc.top/Article/details/gtnpjlcozs.html

npm i -D vite;  npx vite
来源：http://dali.ehwqpu.com/Article/details/gtcyznskeg.html

[U119] JS：生产构建
来源：http://dali.chenjidiqi.icu/Article/details/gtczkaikil.html

npx vite build
来源：http://dali.nanxuanxn.top/Article/details/gtvblivbeo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.meibo888.top/Article/details/gtbznxmvxf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gthfyayyws.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtqgrhuawh.html

统计汇总
来源：http://dali.yueranfly.top/Article/details/gtvbnzljvk.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtkpcipont.html

按语言统计（条）：
来源：http://dali.snrcjt.cn/Article/details/gtxecepqwu.html

Python ......... 252
来源：http://dali.ivvv.top/Article/details/gtkbzddmxa.html

PHP ............ 252
来源：http://dali.zhixingplan.top/Article/details/gtbwmkjjsn.html

JavaScript ..... 252
来源：http://dali.guowangkeji.top/Article/details/gttarywvqe.html

TypeScript ..... 212
来源：http://dali.sufxvd.cn/Article/details/gtjjjytqxo.html

Java ........... 212
来源：http://dali.shzxlz.cn/Article/details/gtdaudirhm.html

Go ............. 212
来源：http://dali.jinqigufen.top/Article/details/gtuelwonll.html

Ruby ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gtnthwymdz.html

C# ............. 212
来源：http://dali.hfpthk.cn/Article/details/gtowwwudgo.html

C .............. 30
来源：http://dali.ivvv.top/Article/details/gtdpbilcdl.html

C++ ............ 30
来源：http://dali.zhiwuduotai.top/Article/details/gtveakjnte.html

SQL ............ 90
来源：http://dali.cdnleiting.top/Article/details/gtkqwhqcpl.html

Bash ........... 80
来源：http://dali.quarkkingdee.top/Article/details/gtfsvjwssj.html

Kotlin ......... 15
来源：http://dali.cqqwz.cn/Article/details/gtdhppfruw.html

Swift .......... 15
来源：http://dali.nanxuanxn.top/Article/details/gtwtnldtlx.html

Lua ............ 10
来源：http://dali.zhoulong.xyz/Article/details/gtoviopywa.html

Perl ........... 10
来源：http://dali.sufxvd.cn/Article/details/gtjosevpfn.html

Scala .......... 10
来源：http://dali.cqqwz.cn/Article/details/gtybnikpag.html

------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtakxgtobb.html

合计 ........... 2106 条
来源：http://dali.cashguo.top/Article/details/gtzbkewdmo.html

按章节统计：
来源：http://dali.guowangkeji.top/Article/details/gtexgwxnzv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.vqdsnc.cn/Article/details/gtxnteaihn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gtvpvgciul.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gtbvamxewe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gtvrumemxg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cucudq.cn/Article/details/gtqqcafhjx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefkrfkzm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gtjlwscgbj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cucudq.cn/Article/details/gtfikydnfz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtzqjwfwes.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.bjfxy.top/Article/details/gtlmfpvsyi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflmlgnlw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtbhhuarne.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gtoqaswdqr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jinqigfzy.top/Article/details/gtaunjnwyk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.smart0.xyz/Article/details/gtbbtqxtjm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gthrprmrcm.html

Q SQL 专题                              90
来源：http://dali.yanxiufei.cn/Article/details/gtqtsunsnh.html

R Bash 专题                             80
来源：http://dali.bjfxy.top/Article/details/gtrxcfztri.html

S C / C++ 专题                          60
来源：http://dali.iojbl.cn/Article/details/gtukvpccvr.html

T 其他语言补充                          60
来源：http://dali.hfpthk.cn/Article/details/gtexyxatvb.html

U 高频实用片段                         120
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqmuppqj.html

------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtdqdmyesf.html

合计                                  2106 条
来源：http://dali.guannengcc.top/Article/details/gtdemhviop.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gtltfnvwte.html

使用提醒
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvnmrfud.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtphewglje.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.dianchejie.cn/Article/details/gtkmoznnbr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gaohongyu789.top/Article/details/gtlycjztxc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.tanke756.top/Article/details/gtoyzuvftg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.vqdsnc.cn/Article/details/gtyvyigguf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhongyouzk.top/Article/details/gtthyqfqkd.html

—— 文件结束 ——
来源：http://dali.jlsjyb.cn/Article/details/gtrpanosyv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtxlqzmgdt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nanxuanxn.top/Article/details/gtdacpzhrf.html

Common Programming Examples Cheat Book
来源：http://dali.gzhubu.top/Article/details/gtndxweezb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtsbpecszb.html

【收录内容】
来源：http://dali.xuetiantiany.cn/Article/details/gtugfzkcyo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.aizwys.cn/Article/details/gtphjmsrxl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaljwejoh.html

SQL · Bash · C · C++
来源：http://dali.mhx1999.top/Article/details/gtatsswpky.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shangyingyoupin.top/Article/details/gtsrlbnhfz.html

【使用说明】
来源：http://dali.zhengqikj.top/Article/details/gtuddzwnza.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tanke756.top/Article/details/gtdtervyzb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ppjwa.cn/Article/details/gtwqdzbguu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.bjfxy.top/Article/details/gtdgyotxif.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhengqikj.top/Article/details/gtntfrihpb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cdnleiting.top/Article/details/gttnqxamen.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhongyouzk.top/Article/details/gtqoixldes.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hnxiangtu.top/Article/details/gtpzqnewyx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.316326.xyz/Article/details/gtlghpovye.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.tian-w.cn/Article/details/gtzyucbisu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xuetiantiany.cn/Article/details/gtbjiasozy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnxiangtu.top/Article/details/gtbfemwjty.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hnqzz.top/Article/details/gtestrwwdw.html

【文件统计】
来源：http://dali.daxiang520.top/Article/details/gtsvpnzbpz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ppjwa.cn/Article/details/gtcsyzlrhx.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtcdiazobq.html

目  录
来源：http://dali.zycfv.cn/Article/details/gtsyskbfqc.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtlsxzuzxi.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.guannengcc.top/Article/details/gthiwpnovc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.wangdashe.top/Article/details/gtfqaoypkv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gtilnzjipl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxbnlmwg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtlhhfajsn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shuidangran.top/Article/details/gtmamvinzb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gtnbcwpjhf.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yuanzhike.top/Article/details/gtfrakxnbs.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gtrmncbnlm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gthrpnazrn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gtvsafjbfy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzpkmuza.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gtnlghcpvp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.aibaodan.cn/Article/details/gtthvawdil.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hfpthk.cn/Article/details/gtebvpvwrt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtrlnjljrq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zdqjudy.top/Article/details/gtmwqrgvom.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xuanzx.com/Article/details/gtkboglcij.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gogol.net.cn/Article/details/gtvrxhvwmk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gtlnyadetk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gtfcbmbhkh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtfjzmsvns.html

A. 基础语法与类型
来源：http://dali.yongpay.top/Article/details/gtzltfiqbq.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtfnqunjde.html

[A01] Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwhzvixi.html

Py:   print("Hello, World!")
来源：http://dali.mhx1999.top/Article/details/gtgdmvijev.html

PHP:  echo "Hello, World!";
来源：http://dali.xuetiantiany.cn/Article/details/gtjqfairal.html

JS:   console.log("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gtffpmlary.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.andypj.xyz/Article/details/gthddvvwca.html

Java: System.out.println("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gtqeonozrf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cdnleiting.top/Article/details/gtmxnuxoob.html

Ruby: puts "Hello, World!"
来源：http://dali.snrcjt.cn/Article/details/gtzdeoehie.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gtfisvchkn.html

[A02] 变量声明与赋值
来源：http://dali.ivvv.top/Article/details/gtsjvqhcpz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sxryk.cn/Article/details/gtycgkvgyh.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.haohaochexian.top/Article/details/gtichwbtld.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhengqikj.top/Article/details/gtobmkhyzm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hywenlv.cn/Article/details/gtvstjnyna.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.andypj.xyz/Article/details/gtfjqcnfiy.html

Go:   name := "Alex"; age := 20
来源：http://dali.nanxuanxn.top/Article/details/gttujhzoqb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.iojbl.cn/Article/details/gtedtnwwhn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.9152youxi.cn/Article/details/gtyeqekojh.html

[A03] 常量定义
来源：http://dali.ppjwa.cn/Article/details/gtamopclei.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cashguo.top/Article/details/gtsmayuavu.html

PHP:  const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtgwkelptl.html

JS:   const PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtxjjlpfdi.html

TS:   const PI: number = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtbrhxcsub.html

Java: static final double PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtxebhsawg.html

Go:   const PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gtspfwrmnv.html

Ruby: PI = 3.14159
来源：http://dali.ivvv.top/Article/details/gtovcegyty.html

C#:   const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtnhkzrusw.html

[A04] 判断变量类型
来源：http://dali.xuetiantiany.cn/Article/details/gthyiktxxq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yuanzhike.top/Article/details/gtpbzpdawg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.snrcjt.cn/Article/details/gtozgetodv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hywenlv.cn/Article/details/gtnnythzon.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinqigufen.top/Article/details/gtvldvosza.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.redwolf501.top/Article/details/gtwinnkczs.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xuanzx.com/Article/details/gtodmtfjhe.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zycfv.cn/Article/details/gtrcuughoh.html

C#:   x.GetType().Name; x is int
来源：http://dali.yongpay.top/Article/details/gtprsgkork.html

[A05] 整数除法与取模
来源：http://dali.ivvv.top/Article/details/gtcyxjofze.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.dianchejie.cn/Article/details/gtirisuiil.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtvbqkckaa.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtogysomvw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtxyomuyce.html

Java: 7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtylszivbr.html

Go:   7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtwkmxbinl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtikfkqcsr.html

C#:   7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gtzfldhyfk.html

[A06] 字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gtxqrauonp.html

Py:   int("42"); float("3.14")
来源：http://dali.tianlin.xyz/Article/details/gtblmgqifd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hnqzz.top/Article/details/gtdrdjlaea.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwtfdcjo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jiagoushi.top/Article/details/gtufpgolsm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhoulong.xyz/Article/details/gtxsodytjj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinqigufen.top/Article/details/gtnjbtuezp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.haohaochexian.top/Article/details/gtoyrbouec.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yangfankeji.com/Article/details/gtdxescbnk.html

[A07] 数字转字符串
来源：http://dali.guannengcc.top/Article/details/gtourxrcvn.html

Py:   str(42)
来源：http://dali.hfpthk.cn/Article/details/gtjcdfqcwi.html

PHP:  (string) 42; strval(42)
来源：http://dali.hfpthk.cn/Article/details/gtprdyzawf.html

JS:   String(42); (42).toString()
来源：http://dali.hongshengwenyu.top/Article/details/gthfgqwkta.html

TS:   String(42)
来源：http://dali.mhx1999.top/Article/details/gtvbmumjqo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfnuutph.html

Go:   strconv.Itoa(42)
来源：http://dali.wangdashe.top/Article/details/gtaehjqcrw.html

Ruby: 42.to_s
来源：http://dali.kuanghao11.cn/Article/details/gtcxcvsrhh.html

C#:   42.ToString()
来源：http://dali.yuanzhike.top/Article/details/gtrlbmzznn.html

[A08] 取整与四舍五入
来源：http://dali.chenzaomai.com/Article/details/gtlmtcjfub.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.iojbl.cn/Article/details/gttttqxvhz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xuanzx.com/Article/details/gtqnoskvgt.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gtubtfatdl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hysaishi.cn/Article/details/gtdyvjsxjc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtzfeiuebk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gtvblqyrep.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zycfv.cn/Article/details/gtyltmyofh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.meibo888.top/Article/details/gtvpylaqja.html

[A09] 绝对值与最大最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbrybane.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtyvbocswc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj20258.top/Article/details/gtejbqhbar.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmekidil.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtwtptswjo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gteeggkdif.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.daria6918.cn/Article/details/gtuviegdbw.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ivvv.top/Article/details/gtjqdouzlj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtrfznwifz.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gtajrtlqss.html

Py:   import random; random.randint(1, 100)
来源：http://dali.guannengcc.top/Article/details/gtfvcpenin.html

PHP:  random_int(1, 100);
来源：http://dali.yuxming.cn/Article/details/gtqxdvhxqf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shangyingyoupin.top/Article/details/gtgecfghgf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gotoacloud.top/Article/details/gtmoeezmgb.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yueranfly.top/Article/details/gturbagthj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yuanzhike.top/Article/details/gtkbciawzp.html

Ruby: rand(1..100)
来源：http://dali.0kj1m.cn/Article/details/gtrzypudjm.html

C#:   new Random().Next(1, 101)
来源：http://dali.hnqzz.top/Article/details/gtfmgqgghy.html

[A11] 条件表达式（三元）
来源：http://dali.sysykeji.top/Article/details/gtvrtiqxwj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ehwqpu.com/Article/details/gtwiarlpgi.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtyamlgnkx.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbkfsywd.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.snrcjt.cn/Article/details/gtrhzmhabb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtalccswhp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhongyouzk.top/Article/details/gtupdfjoxi.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtcfpyxzvc.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gteiwdsvgv.html

[A12] 字符串插值 / 格式化
来源：http://dali.sweek.top/Article/details/gtmfyljrww.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cucudq.cn/Article/details/gtaamxtsth.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.feifeiyinyue.top/Article/details/gtxvicdvrv.html

JS:   `Hello, ${name}!`
来源：http://dali.xuetiantiany.cn/Article/details/gtmnhvmavb.html

TS:   `Hello, ${name}!`
来源：http://dali.yj20258888.top/Article/details/gtxjvqrers.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xziqi.cn/Article/details/gtikyhotdy.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.nanxuanxn.top/Article/details/gtmiovumel.html

Ruby: "Hello, #{name}!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtablfluuf.html

C#:   $"Hello, {name}!"
来源：http://dali.316326.xyz/Article/details/gtztfyjvux.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.andypj.xyz/Article/details/gtibzkudzs.html

Py:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtnejlrvih.html

PHP:  "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtfvbnrqsd.html

JS:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtohpqalsg.html

TS:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gtyvkzrkha.html

Java: "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtocvqnjre.html

Go:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtrsmwthxw.html

Ruby: "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtjwbbonez.html

C#:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtwahqcyiy.html

[A14] 注释写法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmfktpfx.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhiwuduotai.top/Article/details/gtbepyivob.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gtddxxdfgl.html

JS:   // 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gtncacxgwr.html

TS:   // 单行；/* 多行 */
来源：http://dali.c1oappe.top/Article/details/gtboodexkd.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.meibo888.top/Article/details/gtenxcchek.html

Go:   // 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gtzndeyfgn.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.chenlongwang.top/Article/details/gtbjngdodk.html

C#:   // 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gtnxxshrep.html

[A15] 空值判断与默认值
来源：http://dali.shangyingyoupin.top/Article/details/gtarhvqcbq.html

Py:   value = data or "默认值"
来源：http://dali.yj20258888.top/Article/details/gtntgrcpkq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.nanxuanxn.top/Article/details/gttqxfdppo.html

JS:   const value = data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gtxzvphxtl.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssqhnqvz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.chenjidiqi.icu/Article/details/gtjxrkkvpw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jyoumei.cn/Article/details/gtdlktgzcu.html

Ruby: value = data || "默认值"
来源：http://dali.aibaodan.cn/Article/details/gtjmngzwox.html

C#:   var value = data ?? "默认值";
来源：http://dali.cashguo.top/Article/details/gtdvyysuyc.html

[A16] 真假值判断规则
来源：http://dali.hfpthk.cn/Article/details/gtvtyzscuc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jqgufenzy.top/Article/details/gtwcwxuesr.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmclhghkn.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sxryk.cn/Article/details/gtnaxcvzdt.html

TS:   if (!x) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwnrgrdpr.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.svipenyu.cn/Article/details/gtjpgwgnok.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjekhteo.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.feifeiyinyue.top/Article/details/gtozyikcxf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.9152youxi.cn/Article/details/gtbvjmungy.html

[A17] 位运算
来源：http://dali.fzhhl.top/Article/details/gtynnyaasj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gtiuofzlxl.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gttugwxuvw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtwxuhnuci.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtunuxluaa.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtmubhjlhx.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtapxall.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gthqjiaexi.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtoplxvnnk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.nanxuanxn.top/Article/details/gtcmznftop.html

Py:   ord("A"); chr(65)
来源：http://dali.aizwys.cn/Article/details/gtsgvncdkm.html

PHP:  ord("A"); chr(65)
来源：http://dali.yuxming.cn/Article/details/gtgxcbqohu.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tanke756.top/Article/details/gtkkgyrmxf.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jqgufenzy.top/Article/details/gtpeeptvbj.html

Java: (int) 'A'; (char) 65
来源：http://dali.cashguo.top/Article/details/gtoevsyffa.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.haohaochexian.top/Article/details/gtlreuedux.html

Ruby: "A".ord; 65.chr
来源：http://dali.gotoacloud.top/Article/details/gtenabgwaz.html


<!-- 参考信息 -->