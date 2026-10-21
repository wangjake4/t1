代发 wailian999

[U105] JS：节流
来源：http://dali.yj20258888.top/Article/details/gtwmlgzlku.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.0kj1m.cn/Article/details/gthzftjlbi.html

[U106] JS：日期格式化
来源：http://dali.meibo888.top/Article/details/gtmfytcbpf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj202588.top/Article/details/gtjxsssfzf.html

[U107] JS：数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtdyvzucbm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuanzx.com/Article/details/gtrubjeive.html

[U108] JS：随机整数
来源：http://dali.cdnleiting.top/Article/details/gtbmowseyo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tanke756.top/Article/details/gtawojnrvv.html

[U109] JS：数组分组
来源：http://dali.yuanzhike.top/Article/details/gtpxgxynpn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gttnyhrsdm.html

[U110] JS：数组分块
来源：http://dali.9152youxi.cn/Article/details/gtblmgfrjc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cheryme.top/Article/details/gtvmeaywca.html

[U111] JS：对象转 Map
来源：http://dali.redwolf501.top/Article/details/gtkddnutcy.html

new Map(Object.entries(obj))
来源：http://dali.xinyue.icu/Article/details/gtqhlkdpwn.html

[U112] JS：字符串补位
来源：http://dali.ydzc1.top/Article/details/gtbglpreth.html

"7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtxcqqqmgt.html

[U113] JS：正则替换全部
来源：http://dali.haohaochexian.top/Article/details/gtuxmvforc.html

s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gteluhvsqu.html

[U114] JS：JSON 深比较
来源：http://dali.snrcjt.cn/Article/details/gtjrkcdbzw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gtutdhaasr.html

[U115] JS：生成 UUID
来源：http://dali.ivvv.top/Article/details/gtgzrpqfpi.html

crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtuwytfsgs.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.haohaochexian.top/Article/details/gtgyrgqlhd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ppjwa.cn/Article/details/gtksdpxhgo.html

[U117] JS：单元测试
来源：http://dali.yj20258.top/Article/details/gtgvxbnuwl.html

npm i -D vitest;  npx vitest
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvtgvibf.html

[U118] JS：开发服务器
来源：http://dali.cheryme.top/Article/details/gterfpakzt.html

npm i -D vite;  npx vite
来源：http://dali.guowangkeji.top/Article/details/gtqlbxprlz.html

[U119] JS：生产构建
来源：http://dali.chenzaomai.com/Article/details/gtxlbifcfp.html

npx vite build
来源：http://dali.hongshengwenyu.top/Article/details/gtdllnopas.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.iojbl.cn/Article/details/gtfuonhecu.html

import.meta.env.VITE_API_URL
来源：http://dali.redwolf501.top/Article/details/gtokcfcqwm.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtokeacdoo.html

统计汇总
来源：http://dali.yuanzhike.top/Article/details/gtzjoscvaq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtuxdhbfnf.html

按语言统计（条）：
来源：http://dali.yangfankeji.com/Article/details/gtbmqferbo.html

Python ......... 252
来源：http://dali.zhongyouzk.top/Article/details/gtqhbsncor.html

PHP ............ 252
来源：http://dali.andypj.xyz/Article/details/gtcpwphehv.html

JavaScript ..... 252
来源：http://dali.aizwys.cn/Article/details/gtrbxmuanw.html

TypeScript ..... 212
来源：http://dali.ivvv.top/Article/details/gtsadletbk.html

Java ........... 212
来源：http://dali.jinqigufen.top/Article/details/gtlblfpynz.html

Go ............. 212
来源：http://dali.cucudq.cn/Article/details/gtopjcphip.html

Ruby ........... 212
来源：http://dali.xinyue.icu/Article/details/gticvyzwht.html

C# ............. 212
来源：http://dali.andypj.xyz/Article/details/gtkjkvhdwi.html

C .............. 30
来源：http://dali.havefunace.top/Article/details/gtvmtfjpkh.html

C++ ............ 30
来源：http://dali.chenjidiqi.icu/Article/details/gtgvlnzofo.html

SQL ............ 90
来源：http://dali.shzxlz.cn/Article/details/gtgcjukgbo.html

Bash ........... 80
来源：http://dali.shangyingyoupin.top/Article/details/gtpffjgveu.html

Kotlin ......... 15
来源：http://dali.chenzaomai.com/Article/details/gtcjvgmkgk.html

Swift .......... 15
来源：http://dali.yj202588.top/Article/details/gttweuyogd.html

Lua ............ 10
来源：http://dali.jiagoushi.top/Article/details/gtutwqdesa.html

Perl ........... 10
来源：http://dali.jianghu66.top/Article/details/gtvkidqgnl.html

Scala .......... 10
来源：http://dali.cashguo.top/Article/details/gtlakudymj.html

------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtzajvqaql.html

合计 ........... 2106 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsndyzkbr.html

按章节统计：
来源：http://dali.jiagoushi.top/Article/details/gtntbypjpm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinghuilouyu.cn/Article/details/gttvvqlcab.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gtxfxehzmc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gtpblszzzi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gtgrcctkta.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.0kj1m.cn/Article/details/gtyjsxfkkk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gtggguoplb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gtrfibghin.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gtywktyycu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtalizwuor.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgfzy.top/Article/details/gtwczvwlgk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtpezhwmrx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gthjimpevy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gthmycddho.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gtxvggmupd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yuanzhike.top/Article/details/gtcepadaks.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gtivvwwbhp.html

Q SQL 专题                              90
来源：http://dali.cheryme.top/Article/details/gtfrpppnje.html

R Bash 专题                             80
来源：http://dali.gogol.net.cn/Article/details/gtvlfeuscr.html

S C / C++ 专题                          60
来源：http://dali.nwbrower.top/Article/details/gtcepixacy.html

T 其他语言补充                          60
来源：http://dali.meibo888.top/Article/details/gthahibjpl.html

U 高频实用片段                         120
来源：http://dali.hnqzz.top/Article/details/gtyqifbdii.html

------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtqsehoogr.html

合计                                  2106 条
来源：http://dali.cdnleiting.top/Article/details/gtivjohjqs.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtxbndahmq.html

使用提醒
来源：http://dali.cheryme.top/Article/details/gtmodzfyvg.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtmphsaypc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqeppupv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sxryk.cn/Article/details/gtfukwdhsi.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hnxiangtu.top/Article/details/gtztczrray.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpshquja.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yongpay.top/Article/details/gthduuaubk.html

—— 文件结束 ——
来源：http://dali.chenjidiqi.icu/Article/details/gtxkulxnzx.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtfrmzmhqv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shuidangran.top/Article/details/gtmldnynxt.html

Common Programming Examples Cheat Book
来源：http://dali.jlsjyb.cn/Article/details/gturthggnk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtxrypiwrz.html

【收录内容】
来源：http://dali.jinqigfzy.top/Article/details/gtqdxoxyhx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.pengpengdd.cyou/Article/details/gtncvimihq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.nwbrower.top/Article/details/gtyquabkej.html

SQL · Bash · C · C++
来源：http://dali.chenjidiqi.icu/Article/details/gtlbkhucff.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.aibaodan.cn/Article/details/gtnhqrthvi.html

【使用说明】
来源：http://dali.fzhhl.top/Article/details/gtxwgqhswh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenzaomai.com/Article/details/gtsdwhhwsb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.svipenyu.cn/Article/details/gtlrhusrvo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yuanzhike.top/Article/details/gtwyxpvdjs.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ivvv.top/Article/details/gtnnqvgnyk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ydzc1.top/Article/details/gtoiqboyff.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj202588.top/Article/details/gtpsiwcjfw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.316326.xyz/Article/details/gtqmpolcah.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tanke756.top/Article/details/gthxdxkyrk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jyoumei.cn/Article/details/gtlxtbydib.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yueranfly.top/Article/details/gtkvgcegia.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.snrcjt.cn/Article/details/gtmqdkyxif.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cashguo.top/Article/details/gtuhhbqtkm.html

【文件统计】
来源：http://dali.shuidangran.top/Article/details/gtczwqdxme.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xziqi.cn/Article/details/gtifhpuccn.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtfqvrryyq.html

目  录
来源：http://dali.yangfankeji.com/Article/details/gtsyefrszl.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtnmytqyhg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xziqi.cn/Article/details/gtqlfcybjz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gtaklnzcem.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gttcvkskeb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gzhubu.top/Article/details/gtiwuxualw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtadideehw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shzxlz.cn/Article/details/gtjgkeapqm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinqigufen.top/Article/details/gthnjykpkp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hfpthk.cn/Article/details/gtoxtzauho.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtaqyoyfhz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ppjwa.cn/Article/details/gtndpnwkzo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtdiggixlg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gtdqmblofz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtlnagcidd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tian-w.cn/Article/details/gtjtjqjyiq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.dianchejie.cn/Article/details/gtzoolssla.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gticpfaynt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.0kj1m.cn/Article/details/gtrdqllmrf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnrspiwv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shuidangran.top/Article/details/gttxbhahts.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fengsongda.top/Article/details/gtavbrdqks.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenzaomai.com/Article/details/gtvkvidzbz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtkzrcohoc.html

A. 基础语法与类型
来源：http://dali.shzxlz.cn/Article/details/gtbcihmchf.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdqtqojhr.html

[A01] Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzrdkuib.html

Py:   print("Hello, World!")
来源：http://dali.xinyue.icu/Article/details/gtiotpplec.html

PHP:  echo "Hello, World!";
来源：http://dali.yuxming.cn/Article/details/gtnhegnpxb.html

JS:   console.log("Hello, World!");
来源：http://dali.zhixingplan.top/Article/details/gticpfqvvk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhixingplan.top/Article/details/gtndxerybz.html

Java: System.out.println("Hello, World!");
来源：http://dali.sysykeji.top/Article/details/gtixkhptuw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.c1oappe.top/Article/details/gtvrplauip.html

Ruby: puts "Hello, World!"
来源：http://dali.nanxinkj.top/Article/details/gttwmkzwyi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gtohougzzr.html

[A02] 变量声明与赋值
来源：http://dali.bjfxy.top/Article/details/gtbtwvsqdb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ivvv.top/Article/details/gtrvhvibdj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.andypj.xyz/Article/details/gtlvhivtma.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtgpaglleq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gotoacloud.top/Article/details/gtpjxokqmx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gtfertyryq.html

Go:   name := "Alex"; age := 20
来源：http://dali.zdqjudy.top/Article/details/gtnidtmhqe.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sufxvd.cn/Article/details/gtagneeevw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gtqpifpmni.html

[A03] 常量定义
来源：http://dali.quarkkingdee.top/Article/details/gtpravkklm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yuanzhike.top/Article/details/gtvdsczaix.html

PHP:  const PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtjydovwpc.html

JS:   const PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtwffkxwby.html

TS:   const PI: number = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtkaaxyaiw.html

Java: static final double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtgcibapik.html

Go:   const PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gtvpaffwfs.html

Ruby: PI = 3.14159
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzmgelip.html

C#:   const double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gttnlupgav.html

[A04] 判断变量类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvfabclg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jlsjyb.cn/Article/details/gtgurfuaoq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cashguo.top/Article/details/gtpvbyrewc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.guannengcc.top/Article/details/gtergsweme.html

TS:   typeof x; x instanceof Date
来源：http://dali.smart0.xyz/Article/details/gtjcefiosw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gogol.net.cn/Article/details/gtjwwnozni.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhengqikj.top/Article/details/gtoklvgaca.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yongpay.top/Article/details/gtedesgbdx.html

C#:   x.GetType().Name; x is int
来源：http://dali.quarkkingdee.top/Article/details/gtbdjvijyn.html

[A05] 整数除法与取模
来源：http://dali.gotoacloud.top/Article/details/gtbqrgfvoc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sysykeji.top/Article/details/gtebttjzyz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtgdjqmwge.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtrivxtlca.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtsppqysga.html

Java: 7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtgdkxwhig.html

Go:   7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtoerwyifu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtauoeryhu.html

C#:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtizxhhduu.html

[A06] 字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gtilzkpiaq.html

Py:   int("42"); float("3.14")
来源：http://dali.zhoulong.xyz/Article/details/gtoadpuexq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.redwolf501.top/Article/details/gtdivtudjb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinqigufen.top/Article/details/gthslfzeig.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yongpay.top/Article/details/gtxkbwsesx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gtmuohwiah.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.tian-w.cn/Article/details/gtpporqyrv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.aibaodan.cn/Article/details/gtmziuphqv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gtnwkvgiwp.html

[A07] 数字转字符串
来源：http://dali.havefunace.top/Article/details/gtstraerrp.html

Py:   str(42)
来源：http://dali.gzhubu.top/Article/details/gtndamqumf.html

PHP:  (string) 42; strval(42)
来源：http://dali.gotoacloud.top/Article/details/gtceaujmek.html

JS:   String(42); (42).toString()
来源：http://dali.zhixingplan.top/Article/details/gtvpxvmnir.html

TS:   String(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrutzgxsl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cheryme.top/Article/details/gtdaejphqt.html

Go:   strconv.Itoa(42)
来源：http://dali.xinyue.icu/Article/details/gtxlzulsjg.html

Ruby: 42.to_s
来源：http://dali.bjfxy.top/Article/details/gthjtundxf.html

C#:   42.ToString()
来源：http://dali.9152youxi.cn/Article/details/gtiydwdetf.html

[A08] 取整与四舍五入
来源：http://dali.aizwys.cn/Article/details/gtlbjbciii.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gtkzeihlkv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hnqzz.top/Article/details/gtkisiwyfa.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shuidangran.top/Article/details/gtqmfqlcwr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.dianchejie.cn/Article/details/gtuqtszjjx.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gtsryzxmtu.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gttebmduvc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenzaomai.com/Article/details/gtdwxlxajb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtddxxjodw.html

[A09] 绝对值与最大最小值
来源：http://dali.snrcjt.cn/Article/details/gtclsmgyma.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtaizfrgqh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj20258.top/Article/details/gtwknertez.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtssrxmtxu.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtfgyczhfy.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwflvlts.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.vqdsnc.cn/Article/details/gtvdlmcjyi.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xuetiantiany.cn/Article/details/gtrdqwgkcg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xziqi.cn/Article/details/gthnvhkpda.html

[A10] 生成随机数
来源：http://dali.chenzaomai.com/Article/details/gttefgjqlc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.sxryk.cn/Article/details/gtvifacrft.html

PHP:  random_int(1, 100);
来源：http://dali.pengpengdd.cyou/Article/details/gtqskcmvnc.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hammf.cn/Article/details/gthfzjsddh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sysykeji.top/Article/details/gtrndecbfw.html

Java: new Random().nextInt(100) + 1
来源：http://dali.smart0.xyz/Article/details/gtjesdgsbc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.sxryk.cn/Article/details/gtgxejwbrv.html

Ruby: rand(1..100)
来源：http://dali.zhengqikj.top/Article/details/gtpnrqqvzb.html

C#:   new Random().Next(1, 101)
来源：http://dali.jqgufenzy.top/Article/details/gtrreqxtib.html

[A11] 条件表达式（三元）
来源：http://dali.ybcxt.top/Article/details/gtaheuuukc.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.mhx1999.top/Article/details/gtjbcrmtgo.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gtujczmyhx.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.gaohongyu789.top/Article/details/gtmmuxwnaa.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gtjyvglpip.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.ppjwa.cn/Article/details/gtpvcftmau.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ppjwa.cn/Article/details/gtthuxjlpc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.wangdashe.top/Article/details/gtyuyamoqy.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.gaohongyu789.top/Article/details/gtdxvsmler.html

[A12] 字符串插值 / 格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtyakizdey.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.316326.xyz/Article/details/gtajhxqyng.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.feifeiyinyue.top/Article/details/gtqhebjsgf.html

JS:   `Hello, ${name}!`
来源：http://dali.hysaishi.cn/Article/details/gtzpcbwahd.html

TS:   `Hello, ${name}!`
来源：http://dali.guowangkeji.top/Article/details/gtdsyzazgp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xinyue.icu/Article/details/gtcidopiin.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinqigfzy.top/Article/details/gtibxvpqdc.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhongyouzk.top/Article/details/gtgzptrhnc.html

C#:   $"Hello, {name}!"
来源：http://dali.jyoumei.cn/Article/details/gtwbwtxjxh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yonumen.top/Article/details/gtsxygbuxq.html

Py:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gthrjxuzqu.html

PHP:  "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtknjbanhv.html

JS:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtelyaunfd.html

TS:   "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gtljuhnpvk.html

Java: "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gtwasxjkfc.html

Go:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtjfrusthf.html

Ruby: "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtdejlzszp.html

C#:   "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gtrsmybwru.html

[A14] 注释写法
来源：http://dali.meibo888.top/Article/details/gtrvciwzdk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.wangshuangyany.cn/Article/details/gtslpackgb.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gtjtdliajj.html

JS:   // 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gtnxdjhoaa.html

TS:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gtnnfnwxqc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ppjwa.cn/Article/details/gtyvqmlkbg.html

Go:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gtckhemple.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yangfankeji.com/Article/details/gtceehkakw.html

C#:   // 单行；/* 多行 */
来源：http://dali.haohaochexian.top/Article/details/gtlrdojyix.html

[A15] 空值判断与默认值
来源：http://dali.chenzaomai.com/Article/details/gtompylcjf.html

Py:   value = data or "默认值"
来源：http://dali.gzhubu.top/Article/details/gtohdwuxqv.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.pengpengdd.cyou/Article/details/gtdxaytptt.html

JS:   const value = data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gteuulgifw.html

TS:   const value = data ?? "默认值";
来源：http://dali.nwbrower.top/Article/details/gtlkssuqei.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jlsjyb.cn/Article/details/gtyfograwd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shzxlz.cn/Article/details/gtfetxaytc.html

Ruby: value = data || "默认值"
来源：http://dali.9152youxi.cn/Article/details/gtwabituzq.html

C#:   var value = data ?? "默认值";
来源：http://dali.daria6918.cn/Article/details/gtyqwwvcqf.html

[A16] 真假值判断规则
来源：http://dali.cashguo.top/Article/details/gtolppuscd.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.dashuyun.cn/Article/details/gtufrabvdf.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.havefunace.top/Article/details/gtkkekoqse.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yangfankeji.com/Article/details/gtdokmquhc.html

TS:   if (!x) {}
来源：http://dali.cucudq.cn/Article/details/gtlkzhzbrp.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.9152youxi.cn/Article/details/gttlhvhkto.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jqgfzy.top/Article/details/gtbhvxadal.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.quarkkingdee.top/Article/details/gtakntpydq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.gogol.net.cn/Article/details/gtgivatiun.html

[A17] 位运算
来源：http://dali.0kj1m.cn/Article/details/gtzushvers.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gtjsrvonwa.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.bjfxy.top/Article/details/gtpjkvhdvs.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gtlhmvbtch.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gtizvomavd.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtcuthuwld.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gtrdfgczzp.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gtyiraweat.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gthgqviuhq.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafjbevnd.html

Py:   ord("A"); chr(65)
来源：http://dali.ehwqpu.com/Article/details/gtbadjpbhu.html

PHP:  ord("A"); chr(65)
来源：http://dali.nwbrower.top/Article/details/gtxjasurin.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tianlin.xyz/Article/details/gtlxwciyxa.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayprabxz.html

Java: (int) 'A'; (char) 65
来源：http://dali.ppjwa.cn/Article/details/gtfdfbrxct.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.cdnleiting.top/Article/details/gtvxxnfpdt.html

Ruby: "A".ord; 65.chr
来源：http://dali.jyoumei.cn/Article/details/gthgvgfkao.html


<!-- 参考信息 -->