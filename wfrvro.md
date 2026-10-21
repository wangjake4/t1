代发 wailian999

[U103] JS：定时器
来源：http://dali.hnqzz.top/Article/details/gtbnortyjv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tanke756.top/Article/details/gttawwfdlb.html

[U104] JS：防抖
来源：http://dali.zdqjudy.top/Article/details/gtpggxpzfw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gthddxetsb.html

[U105] JS：节流
来源：http://dali.sysykeji.top/Article/details/gtyojgjdxt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tian-w.cn/Article/details/gtyupwxurk.html

[U106] JS：日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtvttzucip.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.meibo888.top/Article/details/gttzaoujhr.html

[U107] JS：数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtretncdjm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yuxming.cn/Article/details/gtjdedeqrw.html

[U108] JS：随机整数
来源：http://dali.shangyingyoupin.top/Article/details/gtsbdgvofb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yueranfly.top/Article/details/gtxjhcgzry.html

[U109] JS：数组分组
来源：http://dali.sweek.top/Article/details/gtflwlxajw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtuzdxvpqn.html

[U110] JS：数组分块
来源：http://dali.yuanzhike.top/Article/details/gtodefssjw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yangfankeji.com/Article/details/gthnlwxhpk.html

[U111] JS：对象转 Map
来源：http://dali.xinyue.icu/Article/details/gtzmkeigvh.html

new Map(Object.entries(obj))
来源：http://dali.hywenlv.cn/Article/details/gtkqunhpqe.html

[U112] JS：字符串补位
来源：http://dali.aizwys.cn/Article/details/gtxckpkkwb.html

"7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtnqbnscoi.html

[U113] JS：正则替换全部
来源：http://dali.hfpthk.cn/Article/details/gttjgpckfh.html

s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtgofznknb.html

[U114] JS：JSON 深比较
来源：http://dali.nanxuanxn.top/Article/details/gtcoudvyza.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gthgrblqwd.html

[U115] JS：生成 UUID
来源：http://dali.hnqzz.top/Article/details/gtvmmnpwtj.html

crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtqrifkeml.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jqgufenzy.top/Article/details/gtelkpiewz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.snrcjt.cn/Article/details/gtajwrjpfh.html

[U117] JS：单元测试
来源：http://dali.cashguo.top/Article/details/gtneftizkt.html

npm i -D vitest;  npx vitest
来源：http://dali.yj202588.top/Article/details/gtpxmreyqb.html

[U118] JS：开发服务器
来源：http://dali.cashguo.top/Article/details/gtokticaaz.html

npm i -D vite;  npx vite
来源：http://dali.zhiwuduotai.top/Article/details/gtfgpujzkx.html

[U119] JS：生产构建
来源：http://dali.316326.xyz/Article/details/gtrcntnjnq.html

npx vite build
来源：http://dali.aizwys.cn/Article/details/gtqwjftmkz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yuxming.cn/Article/details/gtsfrwpeyq.html

import.meta.env.VITE_API_URL
来源：http://dali.xziqi.cn/Article/details/gticehincl.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtrzqskogv.html

统计汇总
来源：http://dali.c1oappe.top/Article/details/gtcedgjjnm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwqilcoxi.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gtyhgzhblw.html

Python ......... 252
来源：http://dali.hfpthk.cn/Article/details/gtkzvjfnmz.html

PHP ............ 252
来源：http://dali.pycfn.com/Article/details/gtfckvauio.html

JavaScript ..... 252
来源：http://dali.yueranfly.top/Article/details/gtcenrxbvc.html

TypeScript ..... 212
来源：http://dali.ehwqpu.com/Article/details/gthgnpwour.html

Java ........... 212
来源：http://dali.hammf.cn/Article/details/gthumgeinb.html

Go ............. 212
来源：http://dali.jqgufenzy.top/Article/details/gtfptwunex.html

Ruby ........... 212
来源：http://dali.cheryme.top/Article/details/gtqtumwynz.html

C# ............. 212
来源：http://dali.jiagoushi.top/Article/details/gtdyqaouvp.html

C .............. 30
来源：http://dali.guannengcc.top/Article/details/gtkvsartta.html

C++ ............ 30
来源：http://dali.cashguo.top/Article/details/gtvdezwild.html

SQL ............ 90
来源：http://dali.ehwqpu.com/Article/details/gtqokcrtvy.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gteatwmsyl.html

Kotlin ......... 15
来源：http://dali.tianlin.xyz/Article/details/gtwrsvvnpr.html

Swift .......... 15
来源：http://dali.jqgufenzy.top/Article/details/gtdufnwose.html

Lua ............ 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtamtreauk.html

Perl ........... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyzovrnj.html

Scala .......... 10
来源：http://dali.fengsongda.top/Article/details/gtgmtaupds.html

------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gteapinjzk.html

合计 ........... 2106 条
来源：http://dali.cucudq.cn/Article/details/gtfdqaidzx.html

按章节统计：
来源：http://dali.gaohongyu789.top/Article/details/gtbdwjupag.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gtmeabswso.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gtvzzgvpat.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gtfcpurgbr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.svipenyu.cn/Article/details/gtweonuvsa.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hysaishi.cn/Article/details/gtxddhrauz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gtykaosioy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.dashuyun.cn/Article/details/gtjppjqblm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hysaishi.cn/Article/details/gtotlbabfa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtvdnmfjqs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hongshengwenyu.top/Article/details/gtwbrmraiu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtniwispfx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtrtywbhvr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtjchyxhpd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gtzotwbupl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shuidangran.top/Article/details/gtpdxiljks.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtbgzkrzim.html

Q SQL 专题                              90
来源：http://dali.dashuyun.cn/Article/details/gtjjhvodll.html

R Bash 专题                             80
来源：http://dali.redwolf501.top/Article/details/gtjztwokdw.html

S C / C++ 专题                          60
来源：http://dali.fengsongda.top/Article/details/gtugmucujp.html

T 其他语言补充                          60
来源：http://dali.feifeiyinyue.top/Article/details/gtylfvwtgo.html

U 高频实用片段                         120
来源：http://dali.ppjwa.cn/Article/details/gtrcckgfoc.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtfqodxqzp.html

合计                                  2106 条
来源：http://dali.dianchejie.cn/Article/details/gtcuahgebm.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtkmztuzrv.html

使用提醒
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmniccsu.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gtiuiocpam.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.guannengcc.top/Article/details/gtyajqxara.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sxryk.cn/Article/details/gtgjdstotp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sysykeji.top/Article/details/gtqoylzjra.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.andypj.xyz/Article/details/gtukfykuwb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.svipenyu.cn/Article/details/gtvdkqrtyq.html

—— 文件结束 ——
来源：http://dali.fengsongda.top/Article/details/gtqaiefmoi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfbatuggh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shanyushiyangtech.top/Article/details/gttridyjtx.html

Common Programming Examples Cheat Book
来源：http://dali.gzhubu.top/Article/details/gtbckirbxs.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtrentdrei.html

【收录内容】
来源：http://dali.dashuyun.cn/Article/details/gtjdseyhpd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.pycfn.com/Article/details/gtfxopvvdc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jyoumei.cn/Article/details/gtnbhtqavh.html

SQL · Bash · C · C++
来源：http://dali.zhiwuduotai.top/Article/details/gteyenyome.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcihnxstj.html

【使用说明】
来源：http://dali.zhoulong.xyz/Article/details/gtxqyqbfju.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jiagoushi.top/Article/details/gtjwqjsjuq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.snrcjt.cn/Article/details/gtjxtoxeej.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.fengsongda.top/Article/details/gtrxiqfkuk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hfpthk.cn/Article/details/gtrigjxgfj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.wangdashe.top/Article/details/gtwwrjowpd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yvedp.cn/Article/details/gtstzmlryp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yuanzhike.top/Article/details/gtphzefkwn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.daria6918.cn/Article/details/gttaqzajnx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.wangshuangyany.cn/Article/details/gtahixpfsw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.pycfn.com/Article/details/gtyubdmqoy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhengqikj.top/Article/details/gtalrgikjc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yongpay.top/Article/details/gtanydaxvp.html

【文件统计】
来源：http://dali.yangfankeji.com/Article/details/gtulyfonzv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.feifeiyinyue.top/Article/details/gthjlfsumr.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtkqjckxks.html

目  录
来源：http://dali.kuanghao11.cn/Article/details/gttuelbjtj.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtmsdshivu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hnxiangtu.top/Article/details/gttnkkvaju.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtfvhbrsyd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gtqyirrypu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.mhx1999.top/Article/details/gtafjtbkad.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.aizwys.cn/Article/details/gtedzxorfi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtnlmpyiek.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gtqgvsgnig.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ydzc1.top/Article/details/gtpcatussq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtndzpehjm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gtcmcjlbnk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gtsgrwfgut.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtbpcpeeoo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtzouckumh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gtpakblogp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gotoacloud.top/Article/details/gtaqljjyjv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gtstxlnpku.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.9152youxi.cn/Article/details/gtolnliqpz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jqgfzy.top/Article/details/gtgxftywwu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtudesxmuh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gtenhwluoh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gtsmofqezr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtljqoactf.html

A. 基础语法与类型
来源：http://dali.yanxiufei.cn/Article/details/gtfavjeast.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtuawnxfzs.html

[A01] Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumawqjcr.html

Py:   print("Hello, World!")
来源：http://dali.zycfv.cn/Article/details/gtglgiamze.html

PHP:  echo "Hello, World!";
来源：http://dali.haohaochexian.top/Article/details/gtetrthtdq.html

JS:   console.log("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gtjerfvyck.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gaohongyu789.top/Article/details/gteyhzxkoi.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbmkjsuw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtskxiwp.html

Ruby: puts "Hello, World!"
来源：http://dali.cashguo.top/Article/details/gtllkxpjrt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gtofyrduvd.html

[A02] 变量声明与赋值
来源：http://dali.yonumen.top/Article/details/gtmygfobsc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.9152youxi.cn/Article/details/gtlgzvwfhu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gttocgnlhh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.tianlin.xyz/Article/details/gtomwroafn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.iojbl.cn/Article/details/gtetfkxyjf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtycwpttiu.html

Go:   name := "Alex"; age := 20
来源：http://dali.quarkkingdee.top/Article/details/gtbjkcwxge.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gogol.net.cn/Article/details/gtpyqbjixm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258888.top/Article/details/gtqbhqejlu.html

[A03] 常量定义
来源：http://dali.wangshuangyany.cn/Article/details/gtczswmsie.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cdnleiting.top/Article/details/gtyyrnwmtj.html

PHP:  const PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtipcbdydb.html

JS:   const PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtopdcrlcr.html

TS:   const PI: number = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtomjmvmdo.html

Java: static final double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtdhqqzxbk.html

Go:   const PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gtubelacia.html

Ruby: PI = 3.14159
来源：http://dali.zhixingplan.top/Article/details/gtgolfgfli.html

C#:   const double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtktlcfyxz.html

[A04] 判断变量类型
来源：http://dali.chenlongwang.top/Article/details/gtycmroryq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinqigfzy.top/Article/details/gtpnzqnkxu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shanyushiyangtech.top/Article/details/gttbkukkia.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenzaomai.com/Article/details/gtkqcwvytx.html

TS:   typeof x; x instanceof Date
来源：http://dali.andypj.xyz/Article/details/gttsctaeni.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zdqjudy.top/Article/details/gturhwnbeb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.andypj.xyz/Article/details/gtrahunifs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhoulong.xyz/Article/details/gtegchopqx.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhiwuduotai.top/Article/details/gtgpdavdpq.html

[A05] 整数除法与取模
来源：http://dali.birdmap.top/Article/details/gtlmybbyhz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtmajvzx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahffcakl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlikblnza.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gturtbgeke.html

Java: 7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtuptnvmdu.html

Go:   7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtenlpobjp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtkhjmwuky.html

C#:   7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtvrhcnhfp.html

[A06] 字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gttrivwbor.html

Py:   int("42"); float("3.14")
来源：http://dali.zhengqikj.top/Article/details/gtqoktwhul.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqrtbsya.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xylfe.cn/Article/details/gtkdvtuloq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinqigufen.top/Article/details/gtodbxufxj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.c1oappe.top/Article/details/gtrzpcnjup.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hysaishi.cn/Article/details/gtwhqxnyfq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jyoumei.cn/Article/details/gtffqezggt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhixingplan.top/Article/details/gtejbisppc.html

[A07] 数字转字符串
来源：http://dali.snrcjt.cn/Article/details/gtogjgkbzv.html

Py:   str(42)
来源：http://dali.mhx1999.top/Article/details/gtnvuedtqv.html

PHP:  (string) 42; strval(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtagqlpdsr.html

JS:   String(42); (42).toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmoxgvkgw.html

TS:   String(42)
来源：http://dali.jyoumei.cn/Article/details/gtymikdghr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.sysykeji.top/Article/details/gtqsxttheu.html

Go:   strconv.Itoa(42)
来源：http://dali.shangyingyoupin.top/Article/details/gttjwzsecm.html

Ruby: 42.to_s
来源：http://dali.redwolf501.top/Article/details/gthgemoipx.html

C#:   42.ToString()
来源：http://dali.jyoumei.cn/Article/details/gtvpayzlie.html

[A08] 取整与四舍五入
来源：http://dali.snrcjt.cn/Article/details/gtdivjbbvd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gttvejmprb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cucudq.cn/Article/details/gtfvfadaxb.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.quarkkingdee.top/Article/details/gtxqusornq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cashguo.top/Article/details/gturxcaurk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtxwvvdlkp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ivvv.top/Article/details/gtatqguada.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.kuanghao11.cn/Article/details/gtnzghbwps.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yj20258.top/Article/details/gtdmwflivy.html

[A09] 绝对值与最大最小值
来源：http://dali.mhx1999.top/Article/details/gtvtgedyxt.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtbejmbnmk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtenwbxmlm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtkzrxnkbg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtzlwuidmk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtjxdvfemg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gotoacloud.top/Article/details/gtcbinrple.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.nwbrower.top/Article/details/gtvaehgdwx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.havefunace.top/Article/details/gtblwtzzpb.html

[A10] 生成随机数
来源：http://dali.guowangkeji.top/Article/details/gtzyupmule.html

Py:   import random; random.randint(1, 100)
来源：http://dali.feifeiyinyue.top/Article/details/gtiqjomogu.html

PHP:  random_int(1, 100);
来源：http://dali.aizwys.cn/Article/details/gtylntzbxq.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.bjfxy.top/Article/details/gtplkeigwy.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zycfv.cn/Article/details/gtwjyxbssk.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hnqzz.top/Article/details/gtcnfelxkt.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hfpthk.cn/Article/details/gtdgxmmmmt.html

Ruby: rand(1..100)
来源：http://dali.yj20258888.top/Article/details/gtfllyetje.html

C#:   new Random().Next(1, 101)
来源：http://dali.meibo888.top/Article/details/gtkjdpfzpt.html

[A11] 条件表达式（三元）
来源：http://dali.nanxuanxn.top/Article/details/gtgjmdkrgk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.tianlin.xyz/Article/details/gtdarvgatu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gtvxjkuhmj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gtfivveygc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gtwxjqgdsy.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gtrvokegju.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.gzhubu.top/Article/details/gtbjqehshu.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gttvezylil.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gtjotsdswf.html

[A12] 字符串插值 / 格式化
来源：http://dali.ivvv.top/Article/details/gtpezktybn.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.bjfxy.top/Article/details/gtqaohdjvj.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.gotoacloud.top/Article/details/gtzsdfjjjg.html

JS:   `Hello, ${name}!`
来源：http://dali.tianlin.xyz/Article/details/gtfvshrjxk.html

TS:   `Hello, ${name}!`
来源：http://dali.cdnleiting.top/Article/details/gtgjamtqrm.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.birdmap.top/Article/details/gtcazwlniw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.shuidangran.top/Article/details/gtosyvygxl.html

Ruby: "Hello, #{name}!"
来源：http://dali.wangshuangyany.cn/Article/details/gtfvgpchlr.html

C#:   $"Hello, {name}!"
来源：http://dali.andypj.xyz/Article/details/gthnrbyuvg.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hnqzz.top/Article/details/gtkdecmgbr.html

Py:   "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gtezcvgmrp.html

PHP:  "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gtnfzkeuri.html

JS:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gttaaojews.html

TS:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gtbfsuxxgm.html

Java: "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gtuzwrooju.html

Go:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtajxnoxch.html

Ruby: "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtysikogps.html

C#:   "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gtsggbfhrz.html

[A14] 注释写法
来源：http://dali.chenjidiqi.icu/Article/details/gtijqamstg.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.tanke756.top/Article/details/gtrgwceyyb.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gtmalbnkin.html

JS:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gttfjmtbqx.html

TS:   // 单行；/* 多行 */
来源：http://dali.dianchejie.cn/Article/details/gtdvtvuneo.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.wangshuangyany.cn/Article/details/gtlbqyovvh.html

Go:   // 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gtlqrrbsda.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jinqigufen.top/Article/details/gtkhfwlnfa.html

C#:   // 单行；/* 多行 */
来源：http://dali.yj20258.top/Article/details/gtivcgjjkf.html

[A15] 空值判断与默认值
来源：http://dali.ppjwa.cn/Article/details/gtfbmswdls.html

Py:   value = data or "默认值"
来源：http://dali.jianghu66.top/Article/details/gtenemlkdq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yj20258.top/Article/details/gtsleipbhr.html

JS:   const value = data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gtmscgyqmt.html

TS:   const value = data ?? "默认值";
来源：http://dali.hywenlv.cn/Article/details/gtgpigujca.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cheryme.top/Article/details/gttbzkfwct.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ydzc1.top/Article/details/gtmlvqmbuy.html

Ruby: value = data || "默认值"
来源：http://dali.pengpengdd.cyou/Article/details/gtabczmrfn.html

C#:   var value = data ?? "默认值";
来源：http://dali.hfpthk.cn/Article/details/gtjodgphfc.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gtheblrurm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhongyouzk.top/Article/details/gtiascirzt.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ydzc1.top/Article/details/gtkjiwyujc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyzsssqc.html

TS:   if (!x) {}
来源：http://dali.jyoumei.cn/Article/details/gtkzlwujyg.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yuxming.cn/Article/details/gtesvhupaa.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.iojbl.cn/Article/details/gtgiwtfpqo.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.nanxinkj.top/Article/details/gtgtdvydny.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.chenlongwang.top/Article/details/gtbfjwivxs.html

[A17] 位运算
来源：http://dali.pycfn.com/Article/details/gtphlhtcvv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gtbyoedtdg.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xziqi.cn/Article/details/gtkcmqrytr.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtxoyzhodj.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtpsrqkwmd.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgqereuu.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gtsszcckwf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtrnwggkqw.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gtrzdtxwme.html

[A18] 字符与 ASCII 码互转
来源：http://dali.wangshuangyany.cn/Article/details/gtntcmdjuw.html

Py:   ord("A"); chr(65)
来源：http://dali.jiagoushi.top/Article/details/gthkqibknc.html

PHP:  ord("A"); chr(65)
来源：http://dali.sufxvd.cn/Article/details/gtlxeimnzb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.havefunace.top/Article/details/gtyervglqg.html


<!-- 参考信息 -->