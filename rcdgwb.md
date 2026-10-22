代发 wailian999

[U105] JS：节流
来源：http://dali.dianchejie.cn/Article/details/gt2hiacpxbk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.dianchejie.cn/Article/details/gt2uuwcjdxs.html

[U106] JS：日期格式化
来源：http://dali.aibaodan.cn/Article/details/gt2hpttzhgf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.quarkkingdee.top/Article/details/gt2axndzxcg.html

[U107] JS：数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gt2lgcquxpy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ppnxmaxx.html

[U108] JS：随机整数
来源：http://dali.cqqwz.cn/Article/details/gt2jybjqwmk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgfzy.top/Article/details/gt2nnxihdmz.html

[U109] JS：数组分组
来源：http://dali.tanke756.top/Article/details/gt2uuyshsol.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gt2qwowixar.html

[U110] JS：数组分块
来源：http://dali.nanxinkj.top/Article/details/gt2ksfeyowf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhixingplan.top/Article/details/gt2vpnxuvtw.html

[U111] JS：对象转 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gt2elbikrpm.html

new Map(Object.entries(obj))
来源：http://dali.xuanzx.com/Article/details/gt2uziayetd.html

[U112] JS：字符串补位
来源：http://dali.smart0.xyz/Article/details/gt2aptjnvao.html

"7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gt2eutahryz.html

[U113] JS：正则替换全部
来源：http://dali.yuxming.cn/Article/details/gt2dkvxiooo.html

s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2qdziiwkr.html

[U114] JS：JSON 深比较
来源：http://dali.zhengqikj.top/Article/details/gt2jrudqctt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gt2ptmiyzqa.html

[U115] JS：生成 UUID
来源：http://dali.cheryme.top/Article/details/gt2zsetmbhz.html

crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gt2oxnzwzgl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yvedp.cn/Article/details/gt2ujlwbwrr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xylfe.cn/Article/details/gt2ybylswln.html

[U117] JS：单元测试
来源：http://dali.hysaishi.cn/Article/details/gt2lnnqtzpt.html

npm i -D vitest;  npx vitest
来源：http://dali.yueranfly.top/Article/details/gt2zpkmsuys.html

[U118] JS：开发服务器
来源：http://dali.hywenlv.cn/Article/details/gt2kvviajls.html

npm i -D vite;  npx vite
来源：http://dali.mhx1999.top/Article/details/gt2ualkovom.html

[U119] JS：生产构建
来源：http://dali.iojbl.cn/Article/details/gt2xltdrmfk.html

npx vite build
来源：http://dali.jinqigufen.top/Article/details/gt2cunwulmk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yvedp.cn/Article/details/gt2maktgewz.html

import.meta.env.VITE_API_URL
来源：http://dali.aibaodan.cn/Article/details/gt2fwhvfple.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2jzsyfnis.html

统计汇总
来源：http://dali.bjfxy.top/Article/details/gt2nmxyvpsw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2jmnlogzw.html

按语言统计（条）：
来源：http://dali.pycfn.com/Article/details/gt2zdybzjwd.html

Python ......... 252
来源：http://dali.shangyingyoupin.top/Article/details/gt2oidhdkwq.html

PHP ............ 252
来源：http://dali.sufxvd.cn/Article/details/gt2yeadgsur.html

JavaScript ..... 252
来源：http://dali.nanxuanxn.top/Article/details/gt2ngyshdxi.html

TypeScript ..... 212
来源：http://dali.zhixingplan.top/Article/details/gt2ofwkjini.html

Java ........... 212
来源：http://dali.0kj1m.cn/Article/details/gt2oknstqeo.html

Go ............. 212
来源：http://dali.snrcjt.cn/Article/details/gt2ifmyoxit.html

Ruby ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gt2okamhhhw.html

C# ............. 212
来源：http://dali.yanxiufei.cn/Article/details/gt2ebuehkpo.html

C .............. 30
来源：http://dali.xinyue.icu/Article/details/gt2pylzrkzs.html

C++ ............ 30
来源：http://dali.ehwqpu.com/Article/details/gt2yejwhszx.html

SQL ............ 90
来源：http://dali.iojbl.cn/Article/details/gt2trjkavkk.html

Bash ........... 80
来源：http://dali.tian-w.cn/Article/details/gt2lahnbxpm.html

Kotlin ......... 15
来源：http://dali.zhoulong.xyz/Article/details/gt2ezwdnqmb.html

Swift .......... 15
来源：http://dali.snrcjt.cn/Article/details/gt2qidycysg.html

Lua ............ 10
来源：http://dali.yangfankeji.com/Article/details/gt2erfipxzy.html

Perl ........... 10
来源：http://dali.zhengqikj.top/Article/details/gt2vbtgbcqu.html

Scala .......... 10
来源：http://dali.havefunace.top/Article/details/gt2biyekjjk.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2ttrkeicp.html

合计 ........... 2106 条
来源：http://dali.hfpthk.cn/Article/details/gt2hvpimxfq.html

按章节统计：
来源：http://dali.gotoacloud.top/Article/details/gt2epkbhddq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ppjwa.cn/Article/details/gt2ffbrnqht.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gt2ypmtxjeg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gt2vinvnxpv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jianghu66.top/Article/details/gt2kagflbls.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sweek.top/Article/details/gt2rorbfpmz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hcletxhp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gt2pramldds.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.andypj.xyz/Article/details/gt2bbcgqzrh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gt2evifyaiq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xylfe.cn/Article/details/gt2tbcnvwqp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jscifemh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gt2kxdsecje.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gt2hwporypu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xinyue.icu/Article/details/gt2gsqwbqye.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cdnleiting.top/Article/details/gt2qggjdkhm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gt2ceqvsjgs.html

Q SQL 专题                              90
来源：http://dali.zhixingplan.top/Article/details/gt2iqrhxifx.html

R Bash 专题                             80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2etdpptgv.html

S C / C++ 专题                          60
来源：http://dali.fengsongda.top/Article/details/gt2eftwpepq.html

T 其他语言补充                          60
来源：http://dali.hywenlv.cn/Article/details/gt2wjdhwotd.html

U 高频实用片段                         120
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sevlevup.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gt2lkoniwlw.html

合计                                  2106 条
来源：http://dali.meibo888.top/Article/details/gt2fndxzkbz.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gt2ouejmoeg.html

使用提醒
来源：http://dali.havefunace.top/Article/details/gt2gisyxyvl.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gt2mzyrrxbj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xuetiantiany.cn/Article/details/gt2vcsglfox.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shangyingyoupin.top/Article/details/gt2czluvsxu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinqigfzy.top/Article/details/gt2rfwobnfb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yj202588.top/Article/details/gt2tchhevjx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.meibo888.top/Article/details/gt2zgtgdkqo.html

—— 文件结束 ——
来源：http://dali.cqqwz.cn/Article/details/gt2yklbiqpk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2taoatbsd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.fengsongda.top/Article/details/gt2kpumlcct.html

Common Programming Examples Cheat Book
来源：http://dali.jqgufenzy.top/Article/details/gt2isxaoqnt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2venmklca.html

【收录内容】
来源：http://dali.gotoacloud.top/Article/details/gt2qbqbcjni.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xylfe.cn/Article/details/gt2bmeeniid.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yanxiufei.cn/Article/details/gt2epwlppai.html

SQL · Bash · C · C++
来源：http://dali.gaohongyu789.top/Article/details/gt2cjflebvv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.fengsongda.top/Article/details/gt2vihquvac.html

【使用说明】
来源：http://dali.shangyingyoupin.top/Article/details/gt2jeztbvvl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sweek.top/Article/details/gt2chjjpvez.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gaohongyu789.top/Article/details/gt2fiupdrij.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.nanxinkj.top/Article/details/gt2mdcnkegf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ivvv.top/Article/details/gt2qawhyvvf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shangyingyoupin.top/Article/details/gt2syolyxeq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yonumen.top/Article/details/gt2liubtlxk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.0kj1m.cn/Article/details/gt2gshsfzex.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.chenjidiqi.icu/Article/details/gt2rcsztdur.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sufxvd.cn/Article/details/gt2lezwlzui.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jlsjyb.cn/Article/details/gt2wlgehgrr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gotoacloud.top/Article/details/gt2drdntgpz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.daxiang520.top/Article/details/gt2nmepupwp.html

【文件统计】
来源：http://dali.ehwqpu.com/Article/details/gt2cwirvvuz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.pengpengdd.cyou/Article/details/gt2ublwvrxg.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gt2iniyqoyl.html

目  录
来源：http://dali.svipenyu.cn/Article/details/gt2ccohdzhx.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lzpgzfxp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ydzc1.top/Article/details/gt2iheebhyr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.316326.xyz/Article/details/gt2mknyvfat.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hysaishi.cn/Article/details/gt2kvimzqwn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hppwyehz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2iairrxzj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjrmcaqh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gt2elxpuayt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2muhirfrz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gt2gozoqbfy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.redwolf501.top/Article/details/gt2srxppjba.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulusmivs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gt2dahzbmzy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2dmtplozr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cqqwz.cn/Article/details/gt2fndqsgnv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2shprxdvr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gt2zzuhotxb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rgoiyqik.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2fvzvwgaq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xinyue.icu/Article/details/gt2cxzvfuuc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nzvoljsq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2wzqkmukh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fvpfmpqt.html

A. 基础语法与类型
来源：http://dali.haohaochexian.top/Article/details/gt2qjgutbep.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2orwsbskd.html

[A01] Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2gmdnxnaa.html

Py:   print("Hello, World!")
来源：http://dali.redwolf501.top/Article/details/gt2zvkknsyn.html

PHP:  echo "Hello, World!";
来源：http://dali.havefunace.top/Article/details/gt2yuxqjzue.html

JS:   console.log("Hello, World!");
来源：http://dali.quarkkingdee.top/Article/details/gt2ajayyylu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xylfe.cn/Article/details/gt2iozaouye.html

Java: System.out.println("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gt2kjyjfqhc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.daxiang520.top/Article/details/gt2iiqlhbdv.html

Ruby: puts "Hello, World!"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wgwfletk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cucudq.cn/Article/details/gt2htnbglth.html

[A02] 变量声明与赋值
来源：http://dali.feifeiyinyue.top/Article/details/gt2rndvksvn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.aibaodan.cn/Article/details/gt2vywaxtqw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hammf.cn/Article/details/gt2ldkapfgp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmvifbel.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yj20258888.top/Article/details/gt2ysatroez.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmdyzvzb.html

Go:   name := "Alex"; age := 20
来源：http://dali.yuanzhike.top/Article/details/gt2pzgfhgwj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.redwolf501.top/Article/details/gt2ugvhecvv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.daria6918.cn/Article/details/gt2ixuqpmoe.html

[A03] 常量定义
来源：http://dali.0kj1m.cn/Article/details/gt2vviifspq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cashguo.top/Article/details/gt2efpcyfcx.html

PHP:  const PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2claiakyb.html

JS:   const PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gt2zeayioqz.html

TS:   const PI: number = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gt2mdxavlsh.html

Java: static final double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2zmqggamn.html

Go:   const PI = 3.14159
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygskciki.html

Ruby: PI = 3.14159
来源：http://dali.hnxiangtu.top/Article/details/gt2ihgmnucv.html

C#:   const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2pmldxkwi.html

[A04] 判断变量类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytgrppaf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.dashuyun.cn/Article/details/gt2zsdajopm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigufen.top/Article/details/gt2qfnyzvjy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.316326.xyz/Article/details/gt2djihpubk.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2salnsneu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.fzhhl.top/Article/details/gt2jxzjneqe.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shzxlz.cn/Article/details/gt2bzlgsxji.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xuanzx.com/Article/details/gt2ecwgjvkr.html

C#:   x.GetType().Name; x is int
来源：http://dali.yj20258888.top/Article/details/gt2ehekkksl.html

[A05] 整数除法与取模
来源：http://dali.guannengcc.top/Article/details/gt2ghnzzjgr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.snrcjt.cn/Article/details/gt2ymenddli.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.guannengcc.top/Article/details/gt2uqiocjfr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuanzx.com/Article/details/gt2fccxrypy.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.redwolf501.top/Article/details/gt2svudslni.html

Java: 7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gt2jjybunkm.html

Go:   7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gt2rcknjazj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2cgpscbpx.html

C#:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gt2ydmtbofe.html

[A06] 字符串转数字
来源：http://dali.yonumen.top/Article/details/gt2ksowbjdj.html

Py:   int("42"); float("3.14")
来源：http://dali.hammf.cn/Article/details/gt2pkcidhki.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wojdlhai.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ydzc1.top/Article/details/gt2rohbdpnz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.dashuyun.cn/Article/details/gt2zrpicywm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.redwolf501.top/Article/details/gt2hlkeuwuz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yonumen.top/Article/details/gt2kaqlhhik.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trokoatd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yj20258.top/Article/details/gt2acuajxsc.html

[A07] 数字转字符串
来源：http://dali.yonumen.top/Article/details/gt2fsabbpmw.html

Py:   str(42)
来源：http://dali.sufxvd.cn/Article/details/gt2tpbqkntx.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqjpajlg.html

JS:   String(42); (42).toString()
来源：http://dali.sufxvd.cn/Article/details/gt2dbmbayvo.html

TS:   String(42)
来源：http://dali.0kj1m.cn/Article/details/gt2heqxdhdr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jianghu66.top/Article/details/gt2puqkeyuu.html

Go:   strconv.Itoa(42)
来源：http://dali.daxiang520.top/Article/details/gt2vhbncems.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzdwsfx.html

C#:   42.ToString()
来源：http://dali.ivvv.top/Article/details/gt2jmvbymol.html

[A08] 取整与四舍五入
来源：http://dali.yj202588.top/Article/details/gt2tqkotxxq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gt2pgqthkpr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shzxlz.cn/Article/details/gt2nkswhebw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gt2btugkazi.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yj202588.top/Article/details/gt2wpbltbsi.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tanke756.top/Article/details/gt2majueysi.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gt2kcywylfp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenzaomai.com/Article/details/gt2assitica.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yongpay.top/Article/details/gt2qxmoihxv.html

[A09] 绝对值与最大最小值
来源：http://dali.haohaochexian.top/Article/details/gt2hrayokhm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2yczhwkjn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2cnlzboie.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2sezggtrq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zycfv.cn/Article/details/gt2zcfbddsr.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ztowbhyb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cdnleiting.top/Article/details/gt2jmxpitqn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yj20258888.top/Article/details/gt2jymkevjm.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxtptqe.html

[A10] 生成随机数
来源：http://dali.quarkkingdee.top/Article/details/gt2zxvkhgtz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.tianlin.xyz/Article/details/gt2riludrsy.html

PHP:  random_int(1, 100);
来源：http://dali.wangdashe.top/Article/details/gt2bgiltkom.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenlongwang.top/Article/details/gt2ptrxhxgh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xuanzx.com/Article/details/gt2mowczakb.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj202588.top/Article/details/gt2ipdxyinb.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.meibo888.top/Article/details/gt2oygiqgry.html

Ruby: rand(1..100)
来源：http://dali.hammf.cn/Article/details/gt2grcupzge.html

C#:   new Random().Next(1, 101)
来源：http://dali.sweek.top/Article/details/gt2wqiejnry.html

[A11] 条件表达式（三元）
来源：http://dali.hysaishi.cn/Article/details/gt2nwlynexu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.daxiang520.top/Article/details/gt2hrjfavto.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gt2afnwqwch.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gt2lfksqqfr.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxaeylad.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gt2fseofoib.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yongpay.top/Article/details/gt2mavwxeoc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gt2ymmiwclp.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2slnfkxdd.html

[A12] 字符串插值 / 格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vmqyxmpl.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.aibaodan.cn/Article/details/gt2izrxryzw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hammf.cn/Article/details/gt2xfvdxhlx.html

JS:   `Hello, ${name}!`
来源：http://dali.0kj1m.cn/Article/details/gt2eiqyzulq.html

TS:   `Hello, ${name}!`
来源：http://dali.yj20258.top/Article/details/gt2bncxlyin.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.haohaochexian.top/Article/details/gt2vackilip.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.cdnleiting.top/Article/details/gt2lnglhufj.html

Ruby: "Hello, #{name}!"
来源：http://dali.jyoumei.cn/Article/details/gt2qjwfzuvo.html

C#:   $"Hello, {name}!"
来源：http://dali.haohaochexian.top/Article/details/gt2ouoayxuj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shzxlz.cn/Article/details/gt2tiqksuey.html

Py:   "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gt2jlzcpxqk.html

PHP:  "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gt2rhocpiim.html

JS:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjeygnvr.html

TS:   "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gt2jgczxjjm.html

Java: "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gt2affmctnl.html

Go:   "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gt2yvceswde.html

Ruby: "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gt2vwzhrooz.html

C#:   "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gt2kbtgsnxg.html

[A14] 注释写法
来源：http://dali.fzhhl.top/Article/details/gt2nxhhcity.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.sufxvd.cn/Article/details/gt2sirztanv.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gt2urviifwd.html

JS:   // 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gt2khkvlgmt.html

TS:   // 单行；/* 多行 */
来源：http://dali.andypj.xyz/Article/details/gt2hwmnmgzf.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.birdmap.top/Article/details/gt2lvlpomqx.html

Go:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gt2jyzyoycx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.tianlin.xyz/Article/details/gt2bpgtyqms.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uufeakcx.html

[A15] 空值判断与默认值
来源：http://dali.yj20258888.top/Article/details/gt2iyfjeclq.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtczyckb.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gt2pnhbthqe.html

JS:   const value = data ?? "默认值";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jevlmlqw.html

TS:   const value = data ?? "默认值";
来源：http://dali.sxryk.cn/Article/details/gt2szegmprf.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xinyue.icu/Article/details/gt2mnvyefxh.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ppjwa.cn/Article/details/gt2bxjnchfw.html

Ruby: value = data || "默认值"
来源：http://dali.ybcxt.top/Article/details/gt2dljqdddr.html

C#:   var value = data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gt2hoidughz.html

[A16] 真假值判断规则
来源：http://dali.9152youxi.cn/Article/details/gt2lktqzyjq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shzxlz.cn/Article/details/gt2rgmkgjzr.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xylfe.cn/Article/details/gt2izqvensc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jqgfzy.top/Article/details/gt2nhvaaary.html

TS:   if (!x) {}
来源：http://dali.cqqwz.cn/Article/details/gt2wtuhtnor.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2uszdsoym.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.c1oappe.top/Article/details/gt2lnjthkvu.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yj20258888.top/Article/details/gt2cnjmcdzr.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2upbdrsgi.html

[A17] 位运算
来源：http://dali.jyoumei.cn/Article/details/gt2iatlcayq.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gt2hudpvhph.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gt2yevcvrgm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gt2qwnhjbuz.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gt2ddbnhevu.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gt2rpxgnzcl.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gt2ezzcwdpq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gt2jzfuzvzs.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2yiolonww.html

[A18] 字符与 ASCII 码互转
来源：http://dali.guannengcc.top/Article/details/gt2adneceye.html

Py:   ord("A"); chr(65)
来源：http://dali.havefunace.top/Article/details/gt2oduhvfgb.html

PHP:  ord("A"); chr(65)
来源：http://dali.chenzaomai.com/Article/details/gt2cvuthftl.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enixptck.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ydzc1.top/Article/details/gt2mohuznwk.html

Java: (int) 'A'; (char) 65
来源：http://dali.cdnleiting.top/Article/details/gt2jzkeppce.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xinyue.icu/Article/details/gt2iqspcjpj.html

Ruby: "A".ord; 65.chr
来源：http://dali.havefunace.top/Article/details/gt2dfxejbiq.html


<!-- 参考信息 -->