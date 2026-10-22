代发 wailian999

[U101] JS：classList 操作
来源：http://dali.bjfxy.top/Article/details/gt2lucdfrif.html

el.classList.toggle("active")
来源：http://dali.jqgfzy.top/Article/details/gt2ydlyumqp.html

[U102] JS：本地存储
来源：http://dali.cheryme.top/Article/details/gt2viaocfpz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hnxiangtu.top/Article/details/gt2apjvfofk.html

[U103] JS：定时器
来源：http://dali.yanxiufei.cn/Article/details/gt2zfhsnmjq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adwroatt.html

[U104] JS：防抖
来源：http://dali.iojbl.cn/Article/details/gt2qatjzqzf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gt2mdcufaye.html

[U105] JS：节流
来源：http://dali.gogol.net.cn/Article/details/gt2ykxalqry.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqvpubnm.html

[U106] JS：日期格式化
来源：http://dali.cqqwz.cn/Article/details/gt2fppukzew.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.meibo888.top/Article/details/gt2hszefnfc.html

[U107] JS：数字千分位
来源：http://dali.nwbrower.top/Article/details/gt2nzbgxprw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.andypj.xyz/Article/details/gt2bgghsmet.html

[U108] JS：随机整数
来源：http://dali.pycfn.com/Article/details/gt2oapeqnnp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ybcxt.top/Article/details/gt2uqeoxayw.html

[U109] JS：数组分组
来源：http://dali.yongpay.top/Article/details/gt2owqhaaqu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gt2zawpxmfi.html

[U110] JS：数组分块
来源：http://dali.shangyingyoupin.top/Article/details/gt2skkjqvgq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.dashuyun.cn/Article/details/gt2pkmaktee.html

[U111] JS：对象转 Map
来源：http://dali.jinqigfzy.top/Article/details/gt2qxydzpdo.html

new Map(Object.entries(obj))
来源：http://dali.jlsjyb.cn/Article/details/gt2lydikmla.html

[U112] JS：字符串补位
来源：http://dali.hammf.cn/Article/details/gt2mfgibogl.html

"7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2aswkhmxz.html

[U113] JS：正则替换全部
来源：http://dali.gaohongyu789.top/Article/details/gt2wpzaqmqe.html

s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2vrzxadax.html

[U114] JS：JSON 深比较
来源：http://dali.yangfankeji.com/Article/details/gt2jaavmszj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gt2aaqtpplw.html

[U115] JS：生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gt2rahcwrfq.html

crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gt2kjofwzmd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinqigufen.top/Article/details/gt2ucsympav.html

/** @param {string} name */ function f(name) {}
来源：http://dali.dashuyun.cn/Article/details/gt2yroozmfw.html

[U117] JS：单元测试
来源：http://dali.jlsjyb.cn/Article/details/gt2leejbkme.html

npm i -D vitest;  npx vitest
来源：http://dali.sweek.top/Article/details/gt2gkmvksqp.html

[U118] JS：开发服务器
来源：http://dali.yanxiufei.cn/Article/details/gt2owgemxbi.html

npm i -D vite;  npx vite
来源：http://dali.jinqigufen.top/Article/details/gt2kbousgig.html

[U119] JS：生产构建
来源：http://dali.iojbl.cn/Article/details/gt2zkbejlpb.html

npx vite build
来源：http://dali.gzhubu.top/Article/details/gt2oatplrdq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hnxiangtu.top/Article/details/gt2qsbjyanr.html

import.meta.env.VITE_API_URL
来源：http://dali.guowangkeji.top/Article/details/gt2oezcsxuu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2cklleobu.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2moktuaag.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2savvyrpm.html

按语言统计（条）：
来源：http://dali.jlsjyb.cn/Article/details/gt2frhfweum.html

Python ......... 252
来源：http://dali.sysykeji.top/Article/details/gt2ajppptvj.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylnlgxdf.html

JavaScript ..... 252
来源：http://dali.zhengqikj.top/Article/details/gt2zmgernkj.html

TypeScript ..... 212
来源：http://dali.quarkkingdee.top/Article/details/gt2thlgwhhb.html

Java ........... 212
来源：http://dali.wangdashe.top/Article/details/gt2llbbeage.html

Go ............. 212
来源：http://dali.c1oappe.top/Article/details/gt2enmtmbbc.html

Ruby ........... 212
来源：http://dali.zdqjudy.top/Article/details/gt2kuaneoou.html

C# ............. 212
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kiicwmpl.html

C .............. 30
来源：http://dali.yuanzhike.top/Article/details/gt2sqddvuog.html

C++ ............ 30
来源：http://dali.svipenyu.cn/Article/details/gt2axnvpiwz.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpovxld.html

Bash ........... 80
来源：http://dali.gzhubu.top/Article/details/gt2nmbtrysb.html

Kotlin ......... 15
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jsoihrri.html

Swift .......... 15
来源：http://dali.9152youxi.cn/Article/details/gt2fxpipmop.html

Lua ............ 10
来源：http://dali.sweek.top/Article/details/gt2mwdpxgjd.html

Perl ........... 10
来源：http://dali.xuanzx.com/Article/details/gt2qublseqq.html

Scala .......... 10
来源：http://dali.ybcxt.top/Article/details/gt2dkjsyqln.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gt2gswtfhyl.html

合计 ........... 2106 条
来源：http://dali.jinqigfzy.top/Article/details/gt2nzolvyqm.html

按章节统计：
来源：http://dali.yongpay.top/Article/details/gt2bnrsiphi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.meibo888.top/Article/details/gt2wjvzrwda.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gt2oqburjph.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gt2hnwadbfy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gt2isviyfbl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.bjfxy.top/Article/details/gt2gutvivui.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yueranfly.top/Article/details/gt2cllksryo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gt2djadiswn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cashguo.top/Article/details/gt2owewhrxu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gt2ycutrrkx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pengpengdd.cyou/Article/details/gt2flrxnped.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gt2gredekbo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gt2xygamrpc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gt2cdmbkrqe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gaohongyu789.top/Article/details/gt2iyccnxtg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpfaiwvl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gt2oxrnbzih.html

Q SQL 专题                              90
来源：http://dali.nanxuanxn.top/Article/details/gt2hbtgifol.html

R Bash 专题                             80
来源：http://dali.gzhubu.top/Article/details/gt2xriqsduk.html

S C / C++ 专题                          60
来源：http://dali.9152youxi.cn/Article/details/gt2apdjjjis.html

T 其他语言补充                          60
来源：http://dali.cqqwz.cn/Article/details/gt2umnihdnh.html

U 高频实用片段                         120
来源：http://dali.gotoacloud.top/Article/details/gt2slcsyygg.html

------------------------------------
来源：http://dali.meibo888.top/Article/details/gt2ogmkcvug.html

合计                                  2106 条
来源：http://dali.quarkkingdee.top/Article/details/gt2avrrmxuw.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gt2kcnhuxcz.html

使用提醒
来源：http://dali.jinqigufen.top/Article/details/gt2fvrzycrw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2apkyvglj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.9152youxi.cn/Article/details/gt2uveledkh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jqgfzy.top/Article/details/gt2hupnmibq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sweek.top/Article/details/gt2stufjvli.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.svipenyu.cn/Article/details/gt2ukjsutdx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ydzc1.top/Article/details/gt2fjzkoyjb.html

—— 文件结束 ——
来源：http://dali.havefunace.top/Article/details/gt2mhvfnexg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2amwppibh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.gogol.net.cn/Article/details/gt2nygvonht.html

Common Programming Examples Cheat Book
来源：http://dali.guowangkeji.top/Article/details/gt2lpbwdqhi.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2popbqqdm.html

【收录内容】
来源：http://dali.316326.xyz/Article/details/gt2dksywoag.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ivvv.top/Article/details/gt2fagbeftr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.aibaodan.cn/Article/details/gt2eejpgxrk.html

SQL · Bash · C · C++
来源：http://dali.yueranfly.top/Article/details/gt2pwthofof.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cdnleiting.top/Article/details/gt2ykjllwwk.html

【使用说明】
来源：http://dali.hongshengwenyu.top/Article/details/gt2fkqywtuw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hnxiangtu.top/Article/details/gt2mfgzjlij.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.aibaodan.cn/Article/details/gt2ahpclvuv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.dianchejie.cn/Article/details/gt2mignkrxn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yangfankeji.com/Article/details/gt2bpqpxbwm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fkgebaow.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jyoumei.cn/Article/details/gt2czczedsj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hongshengwenyu.top/Article/details/gt2zepcarbj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tian-w.cn/Article/details/gt2dbivjhrl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.nanxuanxn.top/Article/details/gt2dhhytdts.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zycfv.cn/Article/details/gt2inmqctqd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.quarkkingdee.top/Article/details/gt2pkezehlh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fnymiwmm.html

【文件统计】
来源：http://dali.xuanzx.com/Article/details/gt2znepqbsx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ehwqpu.com/Article/details/gt2kkmdgjik.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gt2figrofdf.html

目  录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gvfjjkxa.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gt2upjmzwhh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.birdmap.top/Article/details/gt2mgvsdxdv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpfzphf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gt2fxnltcxg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.tanke756.top/Article/details/gt2rffqfsla.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hfpthk.cn/Article/details/gt2qhccavge.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ydzc1.top/Article/details/gt2furbgygq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ybcxt.top/Article/details/gt2tsnuzvwc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.andypj.xyz/Article/details/gt2fjqljwzd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gt2lgtwqfyl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yuanzhike.top/Article/details/gt2yitwxgtl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gt2pqkqvpds.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2zkqelelr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gt2joxocxpi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.svipenyu.cn/Article/details/gt2qkdqwada.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2qwalhcgp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gt2dgvggrzd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2mnjjtuvd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vphgkyuc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yueranfly.top/Article/details/gt2sgobaage.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gt2slhnluwj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.daxiang520.top/Article/details/gt2rwkzwzax.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2xxiydkdi.html

A. 基础语法与类型
来源：http://dali.fzhhl.top/Article/details/gt2vrvybpio.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2fvzmgiag.html

[A01] Hello World
来源：http://dali.tian-w.cn/Article/details/gt2qmdlspaw.html

Py:   print("Hello, World!")
来源：http://dali.316326.xyz/Article/details/gt2oejddlas.html

PHP:  echo "Hello, World!";
来源：http://dali.cucudq.cn/Article/details/gt2pwzsargj.html

JS:   console.log("Hello, World!");
来源：http://dali.jqgfzy.top/Article/details/gt2duwmxodw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinqigfzy.top/Article/details/gt2vnaqpjom.html

Java: System.out.println("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gt2lwhghcfs.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ehwqpu.com/Article/details/gt2jsmiptri.html

Ruby: puts "Hello, World!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nkdhocjx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gt2bvjmhgfu.html

[A02] 变量声明与赋值
来源：http://dali.gotoacloud.top/Article/details/gt2dscyznre.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gzhubu.top/Article/details/gt2ngzkjuhj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.mhx1999.top/Article/details/gt2bcikakvi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.316326.xyz/Article/details/gt2akxruhii.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shzxlz.cn/Article/details/gt2fsicykrp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yueranfly.top/Article/details/gt2ugbvfway.html

Go:   name := "Alex"; age := 20
来源：http://dali.pycfn.com/Article/details/gt2whvbijdr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ybcxt.top/Article/details/gt2jdpvahcp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdtqktgm.html

[A03] 常量定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2yctdboef.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.havefunace.top/Article/details/gt2mcvigedu.html

PHP:  const PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2wvfrofki.html

JS:   const PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2rvaiqyya.html

TS:   const PI: number = 3.14159;
来源：http://dali.hammf.cn/Article/details/gt2fvlmyqdi.html

Java: static final double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqiyfath.html

Go:   const PI = 3.14159
来源：http://dali.jinqigufen.top/Article/details/gt2jzkydrwc.html

Ruby: PI = 3.14159
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kzzcmava.html

C#:   const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gt2uuzjctnp.html

[A04] 判断变量类型
来源：http://dali.pycfn.com/Article/details/gt2dqvcblha.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ucfzfefj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigufen.top/Article/details/gt2qkhdyabi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jyoumei.cn/Article/details/gt2xrthjrxt.html

TS:   typeof x; x instanceof Date
来源：http://dali.nwbrower.top/Article/details/gt2vnpsawgc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ivvv.top/Article/details/gt2fttfjuiq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yuxming.cn/Article/details/gt2zleorwny.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jqgfzy.top/Article/details/gt2ljsjzlih.html

C#:   x.GetType().Name; x is int
来源：http://dali.redwolf501.top/Article/details/gt2fuznvneh.html

[A05] 整数除法与取模
来源：http://dali.jiagoushi.top/Article/details/gt2nrakrzfm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cheryme.top/Article/details/gt2susddwbp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gt2dhxztfhn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shuidangran.top/Article/details/gt2jnqzloov.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snaswoqb.html

Java: 7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gt2anyofvmm.html

Go:   7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gt2kjofwpef.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gt2ahbnioer.html

C#:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gt2jjpexpsh.html

[A06] 字符串转数字
来源：http://dali.xziqi.cn/Article/details/gt2fpjltkve.html

Py:   int("42"); float("3.14")
来源：http://dali.jqgfzy.top/Article/details/gt2rjlzxsto.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cheryme.top/Article/details/gt2dovihawp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.9152youxi.cn/Article/details/gt2wiivarqt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.wangdashe.top/Article/details/gt2mdosrhro.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.quarkkingdee.top/Article/details/gt2rakxizcn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.guannengcc.top/Article/details/gt2dgmbcwer.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jqgfzy.top/Article/details/gt2dzmnxfzr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jianghu66.top/Article/details/gt2ckgibjco.html

[A07] 数字转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2dstgrqjb.html

Py:   str(42)
来源：http://dali.jlsjyb.cn/Article/details/gt2cyazayky.html

PHP:  (string) 42; strval(42)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mejvoznn.html

JS:   String(42); (42).toString()
来源：http://dali.ppjwa.cn/Article/details/gt2gnaxjcgu.html

TS:   String(42)
来源：http://dali.yueranfly.top/Article/details/gt2emtionoh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.pycfn.com/Article/details/gt2sbwzeuzd.html

Go:   strconv.Itoa(42)
来源：http://dali.fzhhl.top/Article/details/gt2hefctogg.html

Ruby: 42.to_s
来源：http://dali.yj202588.top/Article/details/gt2mgyieagv.html

C#:   42.ToString()
来源：http://dali.daria6918.cn/Article/details/gt2sgqgnokl.html

[A08] 取整与四舍五入
来源：http://dali.sufxvd.cn/Article/details/gt2habkpswc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qzvwpmug.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yongpay.top/Article/details/gt2dleabqle.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gt2hwmmhmgn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.kuanghao11.cn/Article/details/gt2yofcvfat.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gt2xxaqahbz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gt2mxkmnhvm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jlsjyb.cn/Article/details/gt2crlwvxho.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aruwlakc.html

[A09] 绝对值与最大最小值
来源：http://dali.cashguo.top/Article/details/gt2benuhfde.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj20258.top/Article/details/gt2ixwtckdd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hnqzz.top/Article/details/gt2uobshhcp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.meibo888.top/Article/details/gt2xknhbkma.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2arbcbgrl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2efqdeazp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xuanzx.com/Article/details/gt2jgquectf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cyoqcmyk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2qavmqxcm.html

[A10] 生成随机数
来源：http://dali.birdmap.top/Article/details/gt2ibtqidiu.html

Py:   import random; random.randint(1, 100)
来源：http://dali.nanxuanxn.top/Article/details/gt2ashkjqkn.html

PHP:  random_int(1, 100);
来源：http://dali.haohaochexian.top/Article/details/gt2eatkoxct.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2rwqyldgr.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.9152youxi.cn/Article/details/gt2plytjbwn.html

Java: new Random().nextInt(100) + 1
来源：http://dali.meibo888.top/Article/details/gt2rrlmpcfd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.fzhhl.top/Article/details/gt2namwvkio.html

Ruby: rand(1..100)
来源：http://dali.aibaodan.cn/Article/details/gt2wusifbyo.html

C#:   new Random().Next(1, 101)
来源：http://dali.pengpengdd.cyou/Article/details/gt2eijxvuko.html

[A11] 条件表达式（三元）
来源：http://dali.yongpay.top/Article/details/gt2mbgvsckh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ybcxt.top/Article/details/gt2lgtpjfwj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldluewhi.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gt2hixlcfkm.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gt2geqvndgb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gt2sihzqtsp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yj20258.top/Article/details/gt2rabbxrkf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gt2ryklwyrl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.ydzc1.top/Article/details/gt2mbkztcxg.html

[A12] 字符串插值 / 格式化
来源：http://dali.shzxlz.cn/Article/details/gt2jrghlhuy.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.guannengcc.top/Article/details/gt2czlhstbc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.tanke756.top/Article/details/gt2yawztjvg.html

JS:   `Hello, ${name}!`
来源：http://dali.dashuyun.cn/Article/details/gt2kezlseke.html

TS:   `Hello, ${name}!`
来源：http://dali.yonumen.top/Article/details/gt2mgebtoun.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cdnleiting.top/Article/details/gt2pysxkcnq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hfpthk.cn/Article/details/gt2nolcpwdo.html

Ruby: "Hello, #{name}!"
来源：http://dali.birdmap.top/Article/details/gt2kbeinalv.html

C#:   $"Hello, {name}!"
来源：http://dali.yangfankeji.com/Article/details/gt2irtbhkkc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.snrcjt.cn/Article/details/gt2ccwkgoar.html

Py:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gt2qtnnbmwl.html

PHP:  "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gsematzi.html

JS:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gt2svjzqico.html

TS:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gt2okkwakgk.html

Java: "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gt2kbnkgzvp.html

Go:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gt2mgrgyvoi.html

Ruby: "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdanygaw.html

C#:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gt2etypayvj.html

[A14] 注释写法
来源：http://dali.cashguo.top/Article/details/gt2jzvtvtaa.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jqgufenzy.top/Article/details/gt2esgaoarq.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhengqikj.top/Article/details/gt2lvegzoxn.html

JS:   // 单行；/* 多行 */
来源：http://dali.tanke756.top/Article/details/gt2sywnjadd.html

TS:   // 单行；/* 多行 */
来源：http://dali.chenlongwang.top/Article/details/gt2ashnsneb.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jiagoushi.top/Article/details/gt2lakscdgq.html

Go:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gt2itwljstw.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.nwbrower.top/Article/details/gt2diktshbv.html

C#:   // 单行；/* 多行 */
来源：http://dali.cucudq.cn/Article/details/gt2yaxifxqn.html

[A15] 空值判断与默认值
来源：http://dali.shangyingyoupin.top/Article/details/gt2whdodcma.html

Py:   value = data or "默认值"
来源：http://dali.nwbrower.top/Article/details/gt2fcnrfvko.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shzxlz.cn/Article/details/gt2fxhdmkyn.html

JS:   const value = data ?? "默认值";
来源：http://dali.tian-w.cn/Article/details/gt2seuqnmjv.html

TS:   const value = data ?? "默认值";
来源：http://dali.gogol.net.cn/Article/details/gt2pyorzuay.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.havefunace.top/Article/details/gt2kqnujfxf.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwbijeky.html

Ruby: value = data || "默认值"
来源：http://dali.zhixingplan.top/Article/details/gt2hxqosqig.html

C#:   var value = data ?? "默认值";
来源：http://dali.nanxuanxn.top/Article/details/gt2bvaofssv.html

[A16] 真假值判断规则
来源：http://dali.quarkkingdee.top/Article/details/gt2mvrzdgdw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gt2kcwflpyt.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.cheryme.top/Article/details/gt2wzfglnxh.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yposfwft.html

TS:   if (!x) {}
来源：http://dali.cucudq.cn/Article/details/gt2fkzfkmyw.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.redwolf501.top/Article/details/gt2btgghmog.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.sufxvd.cn/Article/details/gt2xnyqkeup.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jianghu66.top/Article/details/gt2ujcogwwr.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hfpthk.cn/Article/details/gt2jgyqcfxa.html

[A17] 位运算
来源：http://dali.pycfn.com/Article/details/gt2npcwiomm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2qotoyfde.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nanxinkj.top/Article/details/gt2jrhqgpol.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gt2zaqoneoo.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gt2vjjduzvm.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gt2svkmwmwl.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gt2akcqnkys.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gt2rxyrqjrg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gt2olqciivt.html


<!-- 参考信息 -->