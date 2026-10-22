代发 wailian999

[U101] JS：classList 操作
来源：http://dali.cheryme.top/Article/details/gthljudcnu.html

el.classList.toggle("active")
来源：http://dali.andypj.xyz/Article/details/gtzrvcdihu.html

[U102] JS：本地存储
来源：http://dali.yj202588.top/Article/details/gtqcephabn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.smart0.xyz/Article/details/gtxmlcivbq.html

[U103] JS：定时器
来源：http://dali.gzhubu.top/Article/details/gtlwmxfuhm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.vqdsnc.cn/Article/details/gtuvtybhqz.html

[U104] JS：防抖
来源：http://dali.dashuyun.cn/Article/details/gtesnnxuza.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtvkskqnzu.html

[U105] JS：节流
来源：http://dali.hfpthk.cn/Article/details/gtfmhdfeae.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ybcxt.top/Article/details/gteseyoarc.html

[U106] JS：日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtzliqdfgz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.quarkkingdee.top/Article/details/gtpkytumxs.html

[U107] JS：数字千分位
来源：http://dali.wangdashe.top/Article/details/gtigduvtvv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yongpay.top/Article/details/gtbgosrjvx.html

[U108] JS：随机整数
来源：http://dali.daria6918.cn/Article/details/gtgtbjcugw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sxryk.cn/Article/details/gtnchrsdof.html

[U109] JS：数组分组
来源：http://dali.vqdsnc.cn/Article/details/gtvjylzaqr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gtfdleblwp.html

[U110] JS：数组分块
来源：http://dali.chenlongwang.top/Article/details/gtoxldlqnm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxinkj.top/Article/details/gtrulclife.html

[U111] JS：对象转 Map
来源：http://dali.xuanzx.com/Article/details/gtsbzohqcz.html

new Map(Object.entries(obj))
来源：http://dali.jqgfzy.top/Article/details/gtaxpemand.html

[U112] JS：字符串补位
来源：http://dali.xuanzx.com/Article/details/gtkejqilei.html

"7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtpvqomkpz.html

[U113] JS：正则替换全部
来源：http://dali.chenjidiqi.icu/Article/details/gtzublygmm.html

s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtkecnthie.html

[U114] JS：JSON 深比较
来源：http://dali.xuanzx.com/Article/details/gtsevfwndt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtxpaaozjo.html

[U115] JS：生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gtpadxjelj.html

crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtnlrxdgbw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuanzx.com/Article/details/gtifdjpsfv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yongpay.top/Article/details/gtaiiqqopt.html

[U117] JS：单元测试
来源：http://dali.guannengcc.top/Article/details/gtlvyifaju.html

npm i -D vitest;  npx vitest
来源：http://dali.fzhhl.top/Article/details/gtzofajbdx.html

[U118] JS：开发服务器
来源：http://dali.smart0.xyz/Article/details/gttkiduiel.html

npm i -D vite;  npx vite
来源：http://dali.xziqi.cn/Article/details/gtovyshxzb.html

[U119] JS：生产构建
来源：http://dali.iojbl.cn/Article/details/gteqtmvwpv.html

npx vite build
来源：http://dali.shangyingyoupin.top/Article/details/gtoeuhfjln.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.snrcjt.cn/Article/details/gtnowmguow.html

import.meta.env.VITE_API_URL
来源：http://dali.dianchejie.cn/Article/details/gtzziubghr.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtydydklio.html

统计汇总
来源：http://dali.xuetiantiany.cn/Article/details/gtaxfvqphj.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtxnulyogz.html

按语言统计（条）：
来源：http://dali.c1oappe.top/Article/details/gtmenglyoz.html

Python ......... 252
来源：http://dali.316326.xyz/Article/details/gtbgggllci.html

PHP ............ 252
来源：http://dali.wangshuangyany.cn/Article/details/gtbowsphzs.html

JavaScript ..... 252
来源：http://dali.gogol.net.cn/Article/details/gttypsmehd.html

TypeScript ..... 212
来源：http://dali.guannengcc.top/Article/details/gtmprzskbt.html

Java ........... 212
来源：http://dali.haohaochexian.top/Article/details/gtzsscvovl.html

Go ............. 212
来源：http://dali.wangdashe.top/Article/details/gtfahtwmkk.html

Ruby ........... 212
来源：http://dali.yueranfly.top/Article/details/gtstbqafms.html

C# ............. 212
来源：http://dali.jinqigfzy.top/Article/details/gttubiobky.html

C .............. 30
来源：http://dali.nwbrower.top/Article/details/gtxsyehctw.html

C++ ............ 30
来源：http://dali.redwolf501.top/Article/details/gtmitaeuik.html

SQL ............ 90
来源：http://dali.sysykeji.top/Article/details/gtflqjnuvj.html

Bash ........... 80
来源：http://dali.yj20258888.top/Article/details/gtlsnbnbmj.html

Kotlin ......... 15
来源：http://dali.cqqwz.cn/Article/details/gtloezrupt.html

Swift .......... 15
来源：http://dali.jinqigfzy.top/Article/details/gtknezdhdx.html

Lua ............ 10
来源：http://dali.hywenlv.cn/Article/details/gtspjblmoi.html

Perl ........... 10
来源：http://dali.0kj1m.cn/Article/details/gtfzhreyoa.html

Scala .......... 10
来源：http://dali.guowangkeji.top/Article/details/gthdzpeypt.html

------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkniloxg.html

合计 ........... 2106 条
来源：http://dali.ehwqpu.com/Article/details/gtewqxlifj.html

按章节统计：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzreasxg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.daxiang520.top/Article/details/gtsrmtsmei.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sweek.top/Article/details/gtyozeaacw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gtzwahfcwr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gtyfjnseot.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nanxinkj.top/Article/details/gtqtfyyksk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gtlcmphjsp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gthdlaotus.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cucudq.cn/Article/details/gtepwmajgs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtnbrambln.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbxkhggz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gtbxsyjqdj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxhbhocm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gtzqyblsrs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.svipenyu.cn/Article/details/gtmdkkzfoi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.dashuyun.cn/Article/details/gtfrshmeec.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtugujrtai.html

Q SQL 专题                              90
来源：http://dali.sufxvd.cn/Article/details/gtkverkvju.html

R Bash 专题                             80
来源：http://dali.yonumen.top/Article/details/gtbecdbogr.html

S C / C++ 专题                          60
来源：http://dali.hfpthk.cn/Article/details/gttsvmahff.html

T 其他语言补充                          60
来源：http://dali.tian-w.cn/Article/details/gtbitdcuun.html

U 高频实用片段                         120
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirvnusvo.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtuafhmviv.html

合计                                  2106 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinnhmqzb.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtzetscaos.html

使用提醒
来源：http://dali.dianchejie.cn/Article/details/gtrajcqddx.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtglkhvjtr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nanxinkj.top/Article/details/gtrqqmpbfe.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cucudq.cn/Article/details/gtluuapglo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yuanzhike.top/Article/details/gtocusycxa.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jiagoushi.top/Article/details/gtuzyvdphq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.daria6918.cn/Article/details/gtqtwutcda.html

—— 文件结束 ——
来源：http://dali.aizwys.cn/Article/details/gttbnfxmrx.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtdzebijlp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shuidangran.top/Article/details/gtykoqqymc.html

Common Programming Examples Cheat Book
来源：http://dali.quarkkingdee.top/Article/details/gtfqitdexh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqogqjyyg.html

【收录内容】
来源：http://dali.fzhhl.top/Article/details/gthwrtsxgh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hfpthk.cn/Article/details/gtujarspbp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgbtorrl.html

SQL · Bash · C · C++
来源：http://dali.ehwqpu.com/Article/details/gtrqcmeoni.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cheryme.top/Article/details/gtbizrtztr.html

【使用说明】
来源：http://dali.jinghuilouyu.cn/Article/details/gtjisqluaw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwymecpy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.snrcjt.cn/Article/details/gtpthpmlra.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zdqjudy.top/Article/details/gtlimewqsv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yongpay.top/Article/details/gtzaeeijxl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.fzhhl.top/Article/details/gtnwvuiazw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenjidiqi.icu/Article/details/gtndjlmaqb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sweek.top/Article/details/gtjpuqpfue.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.pycfn.com/Article/details/gtlyndwksp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.wangdashe.top/Article/details/gtsugfcpth.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jqgfzy.top/Article/details/gtyzfsaaup.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zycfv.cn/Article/details/gtexawcacj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yonumen.top/Article/details/gtrnnzbrpt.html

【文件统计】
来源：http://dali.mhx1999.top/Article/details/gtgcrtkmmk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ivvv.top/Article/details/gtlmyzhpqu.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtwbrxrmnb.html

目  录
来源：http://dali.gzhubu.top/Article/details/gtgwsrfbgg.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtjgxtqxlo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinqigufen.top/Article/details/gtkiwipgml.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gttwhjqwym.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gtwvmxrtod.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cucudq.cn/Article/details/gthmanrrxb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.iojbl.cn/Article/details/gtdjpagtzv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zdqjudy.top/Article/details/gteajpbhyz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.daria6918.cn/Article/details/gtmnggxepe.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hnxiangtu.top/Article/details/gthiobumox.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gthvsxnxoy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.dashuyun.cn/Article/details/gtiikhtwdh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gttdhohlss.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gtzzpqiqir.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gtxdosrkdv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtsuoikjvd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuabnass.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtbymlkafz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ehwqpu.com/Article/details/gtieiajyxu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gtvctdspyb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.mhx1999.top/Article/details/gtmxsbjxmd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gtmnurrjrg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gttjsmvaon.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtppldviqs.html

A. 基础语法与类型
来源：http://dali.zhengqikj.top/Article/details/gtclqghfsr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtunkubjkp.html

[A01] Hello World
来源：http://dali.0kj1m.cn/Article/details/gtlnhjjvgc.html

Py:   print("Hello, World!")
来源：http://dali.svipenyu.cn/Article/details/gtxxzygnug.html

PHP:  echo "Hello, World!";
来源：http://dali.jiagoushi.top/Article/details/gtaukxjvfh.html

JS:   console.log("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gtfuvgmtfp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xuetiantiany.cn/Article/details/gtnsxdsivm.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gttuccsapi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gtbuhkhthk.html

Ruby: puts "Hello, World!"
来源：http://dali.mhx1999.top/Article/details/gtjjrgxsby.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuazrzlom.html

[A02] 变量声明与赋值
来源：http://dali.hfpthk.cn/Article/details/gteuvmfazi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hfpthk.cn/Article/details/gthedpxftv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gttacfdtil.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.tian-w.cn/Article/details/gtmpazgnuq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.dianchejie.cn/Article/details/gtpcdjhmug.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhixingplan.top/Article/details/gtgfzafsxc.html

Go:   name := "Alex"; age := 20
来源：http://dali.cucudq.cn/Article/details/gtbbdzsttf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cashguo.top/Article/details/gtrquddmds.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtxiexjkee.html

[A03] 常量定义
来源：http://dali.cqqwz.cn/Article/details/gtxwmtzgbl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzzxwdyc.html

PHP:  const PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtqcpmvovv.html

JS:   const PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtyueuqoja.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtxkwhpist.html

Java: static final double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtqakkzfbv.html

Go:   const PI = 3.14159
来源：http://dali.yuanzhike.top/Article/details/gtccpmyxsd.html

Ruby: PI = 3.14159
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyfdaguq.html

C#:   const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtglckacny.html

[A04] 判断变量类型
来源：http://dali.hammf.cn/Article/details/gttovxprox.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanmbisyw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gogol.net.cn/Article/details/gtmjnvuctf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hywenlv.cn/Article/details/gtxinakxva.html

TS:   typeof x; x instanceof Date
来源：http://dali.yangfankeji.com/Article/details/gtvcrkrrsf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.dashuyun.cn/Article/details/gtdbglqwsj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yuanzhike.top/Article/details/gtqpulybqu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xuanzx.com/Article/details/gtuovqumhj.html

C#:   x.GetType().Name; x is int
来源：http://dali.xuetiantiany.cn/Article/details/gtcvkpvhzx.html

[A05] 整数除法与取模
来源：http://dali.shangyingyoupin.top/Article/details/gtgwxzdfwb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hnxiangtu.top/Article/details/gtzgcxdpvd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.meibo888.top/Article/details/gtewuboowe.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtqodvqhjt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdllrgcjg.html

Java: 7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtpjkrqfyh.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtowqtfjtj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtydvjuyaj.html

C#:   7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtcyzjtplt.html

[A06] 字符串转数字
来源：http://dali.sxryk.cn/Article/details/gtkmjbmklv.html

Py:   int("42"); float("3.14")
来源：http://dali.sysykeji.top/Article/details/gtdjgrgxhz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ppjwa.cn/Article/details/gtldlbdbxg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.c1oappe.top/Article/details/gttdaocmvj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yangfankeji.com/Article/details/gtdsvlgjkq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwhxlskg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ydzc1.top/Article/details/gtkxisybpj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.0kj1m.cn/Article/details/gtqpiyasls.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zdqjudy.top/Article/details/gtneybdnst.html

[A07] 数字转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxzklzlo.html

Py:   str(42)
来源：http://dali.jinqigufen.top/Article/details/gtgyjmzcnr.html

PHP:  (string) 42; strval(42)
来源：http://dali.ppjwa.cn/Article/details/gtygkrgamu.html

JS:   String(42); (42).toString()
来源：http://dali.sufxvd.cn/Article/details/gtqrbwqyeq.html

TS:   String(42)
来源：http://dali.jqgfzy.top/Article/details/gtivvhsbdt.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yj202588.top/Article/details/gtxibehjus.html

Go:   strconv.Itoa(42)
来源：http://dali.dashuyun.cn/Article/details/gtsotaprmo.html

Ruby: 42.to_s
来源：http://dali.chenlongwang.top/Article/details/gtnbxqfmde.html

C#:   42.ToString()
来源：http://dali.jinqigfzy.top/Article/details/gtazqapmyu.html

[A08] 取整与四舍五入
来源：http://dali.cucudq.cn/Article/details/gtvvbykgbd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gttcaqiskc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinqigfzy.top/Article/details/gthsthfala.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.quarkkingdee.top/Article/details/gtzeqtebhr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yueranfly.top/Article/details/gtljzoblbk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gtjlpopqws.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gthfpeydef.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.gzhubu.top/Article/details/gtymsqcjmw.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gtjyhskkco.html

[A09] 绝对值与最大最小值
来源：http://dali.ppjwa.cn/Article/details/gtfzjvqwkw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtekehghew.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtftuqunew.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtdlxilnzu.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtencihsko.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtqwnhkowe.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.fzhhl.top/Article/details/gtqprattwn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ybcxt.top/Article/details/gtvcfotgqp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtpzvmqsyn.html

[A10] 生成随机数
来源：http://dali.ydzc1.top/Article/details/gtygsykhbz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hywenlv.cn/Article/details/gtqkxrgzlg.html

PHP:  random_int(1, 100);
来源：http://dali.sufxvd.cn/Article/details/gtjzqydjwi.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tian-w.cn/Article/details/gtsjuvfwvb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cucudq.cn/Article/details/gtuuxpejvg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.ppjwa.cn/Article/details/gtyfejmlyt.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yuxming.cn/Article/details/gtmxksaqkl.html

Ruby: rand(1..100)
来源：http://dali.zdqjudy.top/Article/details/gtongpvmgj.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhiwuduotai.top/Article/details/gtunhwckdc.html

[A11] 条件表达式（三元）
来源：http://dali.aibaodan.cn/Article/details/gtlqbxpgou.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.9152youxi.cn/Article/details/gtqtbfgudk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpeviscc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gtahxjkuhd.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gtmnrbxxqe.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gtdgvgiewa.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.sysykeji.top/Article/details/gthvgubixk.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtixufsajo.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtmjdisfll.html

[A12] 字符串插值 / 格式化
来源：http://dali.haohaochexian.top/Article/details/gtzssapwmo.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhoulong.xyz/Article/details/gtkpwiidrs.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.kuanghao11.cn/Article/details/gtpayzrzes.html

JS:   `Hello, ${name}!`
来源：http://dali.meibo888.top/Article/details/gtadilechg.html

TS:   `Hello, ${name}!`
来源：http://dali.xuanzx.com/Article/details/gtrkdskrcx.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xuanzx.com/Article/details/gtbmowamqv.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtnckubdpy.html

Ruby: "Hello, #{name}!"
来源：http://dali.havefunace.top/Article/details/gtfotuusrg.html

C#:   $"Hello, {name}!"
来源：http://dali.guowangkeji.top/Article/details/gteoqydttq.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cashguo.top/Article/details/gtfzzrgpbj.html

Py:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtnjirwlgw.html

PHP:  "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gttrnechxv.html

JS:   "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gtxbdiqtay.html

TS:   "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gtadzssuwb.html

Java: "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtfrkkofmi.html

Go:   "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtszrdoqpr.html

Ruby: "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gtytmovuba.html

C#:   "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gtcyylgthh.html

[A14] 注释写法
来源：http://dali.sweek.top/Article/details/gtoxxsjopy.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.vqdsnc.cn/Article/details/gtzybnigja.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gtdcokdapb.html

JS:   // 单行；/* 多行 */
来源：http://dali.0kj1m.cn/Article/details/gtcyuwswyb.html

TS:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtipsmjisq.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jyoumei.cn/Article/details/gtnqztdevq.html

Go:   // 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gtsvenknzw.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.fzhhl.top/Article/details/gtugkrpykc.html

C#:   // 单行；/* 多行 */
来源：http://dali.fzhhl.top/Article/details/gthdypcuaf.html

[A15] 空值判断与默认值
来源：http://dali.fengsongda.top/Article/details/gtwvclixhl.html

Py:   value = data or "默认值"
来源：http://dali.yj20258888.top/Article/details/gtvnezbcml.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gtznsfgnzr.html

JS:   const value = data ?? "默认值";
来源：http://dali.0kj1m.cn/Article/details/gtruizcswf.html

TS:   const value = data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gtpibhbcjr.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.gzhubu.top/Article/details/gtpueqrjbw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.havefunace.top/Article/details/gtmkrtbzho.html

Ruby: value = data || "默认值"
来源：http://dali.yvedp.cn/Article/details/gtwmxfrlwf.html

C#:   var value = data ?? "默认值";
来源：http://dali.cdnleiting.top/Article/details/gtxsztmrdb.html

[A16] 真假值判断规则
来源：http://dali.yanxiufei.cn/Article/details/gtxjvzvqrq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zdqjudy.top/Article/details/gtyaeqthht.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gogol.net.cn/Article/details/gtlhwawouq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yongpay.top/Article/details/gtxtvljpsw.html

TS:   if (!x) {}
来源：http://dali.gotoacloud.top/Article/details/gttbvenlrg.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtadbywarz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.aizwys.cn/Article/details/gtfhmtdbgh.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdspxjal.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjabbzizz.html

[A17] 位运算
来源：http://dali.cucudq.cn/Article/details/gtgyptsmzc.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtzhrlulbo.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.birdmap.top/Article/details/gtevpxjcwb.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtcbufwcth.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gtfgnxvozp.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdseaijwl.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvktgxoi.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gtwsrpdveh.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gttsynbrdp.html


<!-- 参考信息 -->