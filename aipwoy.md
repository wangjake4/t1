代发 wailian999

[U103] JS：定时器
来源：http://dali.snrcjt.cn/Article/details/gt2npxkbkmk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.0kj1m.cn/Article/details/gt2hhqullhe.html

[U104] JS：防抖
来源：http://dali.jqgfzy.top/Article/details/gt2xvjymisb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gt2rwimwybz.html

[U105] JS：节流
来源：http://dali.gaohongyu789.top/Article/details/gt2itdkvuki.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shuidangran.top/Article/details/gt2auqrfvkp.html

[U106] JS：日期格式化
来源：http://dali.meibo888.top/Article/details/gt2rutidizs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cucudq.cn/Article/details/gt2nmuptdvk.html

[U107] JS：数字千分位
来源：http://dali.svipenyu.cn/Article/details/gt2ophmtbgl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ybcxt.top/Article/details/gt2fukwddzp.html

[U108] JS：随机整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfspczfg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cheryme.top/Article/details/gt2tmvuxubg.html

[U109] JS：数组分组
来源：http://dali.mhx1999.top/Article/details/gt2opnotnlb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gt2tyuzkqfe.html

[U110] JS：数组分块
来源：http://dali.sxryk.cn/Article/details/gt2vsedjvjk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hywenlv.cn/Article/details/gt2ewetqxqu.html

[U111] JS：对象转 Map
来源：http://dali.guowangkeji.top/Article/details/gt2xoxyuzsu.html

new Map(Object.entries(obj))
来源：http://dali.ehwqpu.com/Article/details/gt2jszsrnfz.html

[U112] JS：字符串补位
来源：http://dali.xylfe.cn/Article/details/gt2qtohtbsz.html

"7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2gfihusgm.html

[U113] JS：正则替换全部
来源：http://dali.hongshengwenyu.top/Article/details/gt2kejjlndo.html

s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2zgjrwjwm.html

[U114] JS：JSON 深比较
来源：http://dali.xuanzx.com/Article/details/gt2xmhvzgei.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gt2rehnziow.html

[U115] JS：生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kswsrnql.html

crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cccgjfxf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jqgufenzy.top/Article/details/gt2qyibnhhp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ivvv.top/Article/details/gt2vdteomxo.html

[U117] JS：单元测试
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sosojwyk.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxuanxn.top/Article/details/gt2xbozqrte.html

[U118] JS：开发服务器
来源：http://dali.aizwys.cn/Article/details/gt2vjagnkfy.html

npm i -D vite;  npx vite
来源：http://dali.sysykeji.top/Article/details/gt2ikyvylef.html

[U119] JS：生产构建
来源：http://dali.redwolf501.top/Article/details/gt2iitfzgwn.html

npx vite build
来源：http://dali.zhengqikj.top/Article/details/gt2tnklzgxx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.dianchejie.cn/Article/details/gt2xwtddugl.html

import.meta.env.VITE_API_URL
来源：http://dali.cdnleiting.top/Article/details/gt2hcwladcz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2qpqgwozj.html

统计汇总
来源：http://dali.mhx1999.top/Article/details/gt2ylvjxcrg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2hjtsxwiz.html

按语言统计（条）：
来源：http://dali.chenzaomai.com/Article/details/gt2xehximke.html

Python ......... 252
来源：http://dali.redwolf501.top/Article/details/gt2aettajax.html

PHP ............ 252
来源：http://dali.dashuyun.cn/Article/details/gt2nlujhnzz.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uamizrio.html

TypeScript ..... 212
来源：http://dali.jiagoushi.top/Article/details/gt2jywflowv.html

Java ........... 212
来源：http://dali.jqgfzy.top/Article/details/gt2sepmuecc.html

Go ............. 212
来源：http://dali.yj202588.top/Article/details/gt2uslyuves.html

Ruby ........... 212
来源：http://dali.sweek.top/Article/details/gt2nxeuvugh.html

C# ............. 212
来源：http://dali.shuidangran.top/Article/details/gt2gkomrjis.html

C .............. 30
来源：http://dali.yangfankeji.com/Article/details/gt2pndzhhyf.html

C++ ............ 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxqoccud.html

SQL ............ 90
来源：http://dali.guowangkeji.top/Article/details/gt2aysfshoo.html

Bash ........... 80
来源：http://dali.c1oappe.top/Article/details/gt2vgmyrxfn.html

Kotlin ......... 15
来源：http://dali.sweek.top/Article/details/gt2mctsveft.html

Swift .......... 15
来源：http://dali.shuidangran.top/Article/details/gt2qaokodso.html

Lua ............ 10
来源：http://dali.zhengqikj.top/Article/details/gt2ibtejppr.html

Perl ........... 10
来源：http://dali.chenlongwang.top/Article/details/gt2awhcxvyo.html

Scala .......... 10
来源：http://dali.hfpthk.cn/Article/details/gt2rpszezrw.html

------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2lknfqplh.html

合计 ........... 2106 条
来源：http://dali.shuidangran.top/Article/details/gt2wwmyxflh.html

按章节统计：
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2stwgcodh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yongpay.top/Article/details/gt2pgbeedlm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gt2pdymcztb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gt2qmgjpjqi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cheryme.top/Article/details/gt2ayiiblki.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jrnapaou.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cqqwz.cn/Article/details/gt2aeqaxnbz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gt2xkqwykkw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhixingplan.top/Article/details/gt2piolxhxb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gt2ictupzkk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvhnhyaa.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jikbaysn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gt2esqhffmi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gt2ezeuadid.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gzhubu.top/Article/details/gt2slzncgal.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ehwqpu.com/Article/details/gt2dyhrxnuf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gt2oxjezpmq.html

Q SQL 专题                              90
来源：http://dali.jqgfzy.top/Article/details/gt2mgcccylr.html

R Bash 专题                             80
来源：http://dali.nwbrower.top/Article/details/gt2oecsxjil.html

S C / C++ 专题                          60
来源：http://dali.yj20258888.top/Article/details/gt2pdqwvzbe.html

T 其他语言补充                          60
来源：http://dali.ydzc1.top/Article/details/gt2uddphmhq.html

U 高频实用片段                         120
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rerdexod.html

------------------------------------
来源：http://dali.cheryme.top/Article/details/gt2juaqjwvk.html

合计                                  2106 条
来源：http://dali.nanxuanxn.top/Article/details/gt2xkbtolvd.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gt2zznxonns.html

使用提醒
来源：http://dali.nanxuanxn.top/Article/details/gt2phzdwhkv.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjbvjtaf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinqigfzy.top/Article/details/gt2fmbpukkk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tanke756.top/Article/details/gt2saqgekxv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oojacwoy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.smart0.xyz/Article/details/gt2xfpgnqka.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.dianchejie.cn/Article/details/gt2hobjvjxu.html

—— 文件结束 ——
来源：http://dali.aibaodan.cn/Article/details/gt2dlfsxevk.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2tgwxhscr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cdnleiting.top/Article/details/gt2kkkwmwia.html

Common Programming Examples Cheat Book
来源：http://dali.quarkkingdee.top/Article/details/gt2bobwbfga.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2tflvwsqa.html

【收录内容】
来源：http://dali.jianghu66.top/Article/details/gt2qlsishqi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tian-w.cn/Article/details/gt2xozdybvx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yvedp.cn/Article/details/gt2mjbxoetb.html

SQL · Bash · C · C++
来源：http://dali.nwbrower.top/Article/details/gt2pkmiaivb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.meibo888.top/Article/details/gt2iqoucqhg.html

【使用说明】
来源：http://dali.shzxlz.cn/Article/details/gt2ckzsihcj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tianlin.xyz/Article/details/gt2yijjgjan.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigfzy.top/Article/details/gt2tlqqumch.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvrapfis.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yanxiufei.cn/Article/details/gt2wsoekyna.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.mhx1999.top/Article/details/gt2jghecgnj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzkcvvxm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhengqikj.top/Article/details/gt2vaplenvw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yuxming.cn/Article/details/gt2vnizujhq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.meibo888.top/Article/details/gt2udzpyqwp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cqqwz.cn/Article/details/gt2oartpwuv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jiagoushi.top/Article/details/gt2rrjppwah.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.sxryk.cn/Article/details/gt2ococgqem.html

【文件统计】
来源：http://dali.tanke756.top/Article/details/gt2blwfeluj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.svipenyu.cn/Article/details/gt2dfedwinf.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gt2tvjnqfex.html

目  录
来源：http://dali.aizwys.cn/Article/details/gt2dvirgoxp.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gt2dqnofqhq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2gbnsxkvb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhixingplan.top/Article/details/gt2qmuwqlec.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gt2axdgfodp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhixingplan.top/Article/details/gt2rpwtsjil.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj202588.top/Article/details/gt2renjdbvw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2swxszddw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.daria6918.cn/Article/details/gt2hegdoxsg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.nanxinkj.top/Article/details/gt2aezbqwxz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gt2szimsron.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2okmfymaz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gt2cxbcbusb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gt2badmqipe.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsfisarq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zgdeynag.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2lcnardnk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gt2oiftqejh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cashguo.top/Article/details/gt2blyndxdi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2jiufvvjp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.bjfxy.top/Article/details/gt2rgqghima.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sweek.top/Article/details/gt2vxiedzzz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gt2ctqyexuf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2xfczbfgr.html

A. 基础语法与类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nihorcny.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2rferivlt.html

[A01] Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2xiuddmkm.html

Py:   print("Hello, World!")
来源：http://dali.cashguo.top/Article/details/gt2lnilmpqk.html

PHP:  echo "Hello, World!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlusoexs.html

JS:   console.log("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gt2vxcfuqpw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ydzc1.top/Article/details/gt2muawxdmy.html

Java: System.out.println("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gt2rsydcrnl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gt2mmtukqzx.html

Ruby: puts "Hello, World!"
来源：http://dali.redwolf501.top/Article/details/gt2pnwpykvr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xylfe.cn/Article/details/gt2egqspnxg.html

[A02] 变量声明与赋值
来源：http://dali.fengsongda.top/Article/details/gt2cszrxxad.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ppjwa.cn/Article/details/gt2phhvlnvk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sxryk.cn/Article/details/gt2owgkfdou.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jyoumei.cn/Article/details/gt2shnhbflf.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.daria6918.cn/Article/details/gt2zudozqtx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gt2dvtiejbc.html

Go:   name := "Alex"; age := 20
来源：http://dali.sufxvd.cn/Article/details/gt2wjbayrfh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jlsjyb.cn/Article/details/gt2pzlspzml.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jiagoushi.top/Article/details/gt2fswfkxal.html

[A03] 常量定义
来源：http://dali.sysykeji.top/Article/details/gt2tlhvotmd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gotoacloud.top/Article/details/gt2kylpahel.html

PHP:  const PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2irsbunrs.html

JS:   const PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2uyewnpay.html

TS:   const PI: number = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gt2lopqsuge.html

Java: static final double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfhhezkv.html

Go:   const PI = 3.14159
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkiaaidt.html

Ruby: PI = 3.14159
来源：http://dali.ppjwa.cn/Article/details/gt2yasmuxcp.html

C#:   const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2nfbhczoa.html

[A04] 判断变量类型
来源：http://dali.yj20258.top/Article/details/gt2qrjelteg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jlsjyb.cn/Article/details/gt2vklecoij.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hnxiangtu.top/Article/details/gt2qehpaqmw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cashguo.top/Article/details/gt2iyrocqfq.html

TS:   typeof x; x instanceof Date
来源：http://dali.yongpay.top/Article/details/gt2qlucmcxl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.birdmap.top/Article/details/gt2qljykrlz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.meibo888.top/Article/details/gt2sosnyqbt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sysykeji.top/Article/details/gt2jicokzic.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinqigfzy.top/Article/details/gt2bmtlgbum.html

[A05] 整数除法与取模
来源：http://dali.xuetiantiany.cn/Article/details/gt2grzttrfy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gaohongyu789.top/Article/details/gt2daqqjicm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gt2uyuqamta.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yvorgcfr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.bjfxy.top/Article/details/gt2hhgxzeuv.html

Java: 7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gt2biggysph.html

Go:   7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gt2afdksrvj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gt2kbrjwqsz.html

C#:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gt2ortrapmj.html

[A06] 字符串转数字
来源：http://dali.yj20258888.top/Article/details/gt2fcpnhizd.html

Py:   int("42"); float("3.14")
来源：http://dali.sysykeji.top/Article/details/gt2wxijvbtb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.tanke756.top/Article/details/gt2aggycnna.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ybcxt.top/Article/details/gt2ecoaxoya.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.dashuyun.cn/Article/details/gt2hkmflafc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jqgfzy.top/Article/details/gt2tlkeuaio.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hnuawzbd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.tianlin.xyz/Article/details/gt2auohesuk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.daria6918.cn/Article/details/gt2cldsiioa.html

[A07] 数字转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2vfsbdyts.html

Py:   str(42)
来源：http://dali.ppjwa.cn/Article/details/gt2saqhbpjg.html

PHP:  (string) 42; strval(42)
来源：http://dali.gotoacloud.top/Article/details/gt2bnjtntzp.html

JS:   String(42); (42).toString()
来源：http://dali.cashguo.top/Article/details/gt2chlfbamy.html

TS:   String(42)
来源：http://dali.xziqi.cn/Article/details/gt2kfalzlam.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.316326.xyz/Article/details/gt2zfwwjpvb.html

Go:   strconv.Itoa(42)
来源：http://dali.aizwys.cn/Article/details/gt2bsraejgz.html

Ruby: 42.to_s
来源：http://dali.dianchejie.cn/Article/details/gt2eurcisww.html

C#:   42.ToString()
来源：http://dali.fzhhl.top/Article/details/gt2yshahzpj.html

[A08] 取整与四舍五入
来源：http://dali.tianlin.xyz/Article/details/gt2lryouccm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gt2twmbejdm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsyuohza.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gt2eghlsquz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jiagoushi.top/Article/details/gt2tpygxkql.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gt2cacpfxtw.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gt2pzmulldm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.guowangkeji.top/Article/details/gt2jzsqdqpw.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gt2bzwxohmk.html

[A09] 绝对值与最大最小值
来源：http://dali.sweek.top/Article/details/gt2ldpjnqbr.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2nxmqkint.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ivvv.top/Article/details/gt2icsqyhht.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2hypqjtxt.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2cmoppbgu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2rqwpejxm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.guowangkeji.top/Article/details/gt2oskkhhte.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2irzydkjh.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2bnicfsaa.html

[A10] 生成随机数
来源：http://dali.svipenyu.cn/Article/details/gt2dwaxtobm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cqqwz.cn/Article/details/gt2tfdratmp.html

PHP:  random_int(1, 100);
来源：http://dali.zdqjudy.top/Article/details/gt2llcxmdsk.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2yntkxdxz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zycfv.cn/Article/details/gt2taeevmha.html

Java: new Random().nextInt(100) + 1
来源：http://dali.guannengcc.top/Article/details/gt2qakppigg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hammf.cn/Article/details/gt2thrhfboq.html

Ruby: rand(1..100)
来源：http://dali.fzhhl.top/Article/details/gt2rtpywkhx.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lhltakvh.html

[A11] 条件表达式（三元）
来源：http://dali.iojbl.cn/Article/details/gt2nmbsfbre.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shangyingyoupin.top/Article/details/gt2pumrzpfs.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hywenlv.cn/Article/details/gt2kmojmejs.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gt2wvkouymr.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ybcxt.top/Article/details/gt2ydtsxlsh.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gt2ycnmnnst.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqjzpyyq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gt2cmcnetao.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gt2otyewjct.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxhvenvb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hysaishi.cn/Article/details/gt2tzzzgkvq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.svipenyu.cn/Article/details/gt2wypgjiub.html

JS:   `Hello, ${name}!`
来源：http://dali.yuanzhike.top/Article/details/gt2rhgepgtc.html

TS:   `Hello, ${name}!`
来源：http://dali.yj202588.top/Article/details/gt2axqqpyin.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.sweek.top/Article/details/gt2xsmhnafn.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zdqjudy.top/Article/details/gt2xhhwhtrn.html

Ruby: "Hello, #{name}!"
来源：http://dali.gogol.net.cn/Article/details/gt2rehwmkum.html

C#:   $"Hello, {name}!"
来源：http://dali.guowangkeji.top/Article/details/gt2jucubehp.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.tian-w.cn/Article/details/gt2dfbwyows.html

Py:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gt2drwlgpba.html

PHP:  "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gt2gavunzzh.html

JS:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gt2aiztsvnf.html

TS:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gt2gsltndew.html

Java: "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gt2wyecwdxz.html

Go:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gt2ouyratfc.html

Ruby: "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gt2tozcbjlm.html

C#:   "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gt2wabwczyt.html

[A14] 注释写法
来源：http://dali.quarkkingdee.top/Article/details/gt2fneutulp.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.dianchejie.cn/Article/details/gt2weqotidr.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gt2twamnjtf.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtffiar.html

TS:   // 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gt2wbyrjxtz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zdqjudy.top/Article/details/gt2klngvcvr.html

Go:   // 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gt2bqeosiml.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.svipenyu.cn/Article/details/gt2vdmrcdqy.html

C#:   // 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gt2dgksfpml.html

[A15] 空值判断与默认值
来源：http://dali.hnqzz.top/Article/details/gt2balwfzmj.html

Py:   value = data or "默认值"
来源：http://dali.hnxiangtu.top/Article/details/gt2sptmxmdm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hnqzz.top/Article/details/gt2uwmxgbkq.html

JS:   const value = data ?? "默认值";
来源：http://dali.cdnleiting.top/Article/details/gt2cbgsqmaq.html

TS:   const value = data ?? "默认值";
来源：http://dali.havefunace.top/Article/details/gt2izslmmxe.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yjvrvysl.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.chenzaomai.com/Article/details/gt2msigtqnc.html

Ruby: value = data || "默认值"
来源：http://dali.chenzaomai.com/Article/details/gt2pjbszcon.html

C#:   var value = data ?? "默认值";
来源：http://dali.shangyingyoupin.top/Article/details/gt2jacxfwjj.html

[A16] 真假值判断规则
来源：http://dali.hammf.cn/Article/details/gt2soubsyia.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.aibaodan.cn/Article/details/gt2kjptgzyi.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.nanxinkj.top/Article/details/gt2eyyzbwna.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gzhubu.top/Article/details/gt2mxiwfjns.html

TS:   if (!x) {}
来源：http://dali.jianghu66.top/Article/details/gt2dzgyydrc.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2tuozqsop.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gaohongyu789.top/Article/details/gt2lvtjepyr.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.sxryk.cn/Article/details/gt2lnodhwzs.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2vewpoems.html

[A17] 位运算
来源：http://dali.sxryk.cn/Article/details/gt2ontphasf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gt2tyigmsqz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yvedp.cn/Article/details/gt2rkwnsjnj.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gt2lxpodkog.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvtwsiq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufzalkfw.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gt2dbwekugx.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gt2lozspcak.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gt2xyfjoprd.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hammf.cn/Article/details/gt2wnshpoor.html

Py:   ord("A"); chr(65)
来源：http://dali.hnxiangtu.top/Article/details/gt2ufphmqra.html

PHP:  ord("A"); chr(65)
来源：http://dali.shzxlz.cn/Article/details/gt2uzctntxm.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hammf.cn/Article/details/gt2zdwqstsy.html


<!-- 参考信息 -->