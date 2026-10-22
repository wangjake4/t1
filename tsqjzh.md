代发 wailian999

[U101] JS：classList 操作
来源：http://dali.dashuyun.cn/Article/details/gt2qqucayux.html

el.classList.toggle("active")
来源：http://dali.nanxuanxn.top/Article/details/gt2tolhdgvh.html

[U102] JS：本地存储
来源：http://dali.zhiwuduotai.top/Article/details/gt2utoxhifc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ivvv.top/Article/details/gt2nwssbisi.html

[U103] JS：定时器
来源：http://dali.kuanghao11.cn/Article/details/gt2zdjdxndw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cheryme.top/Article/details/gt2bpkhcynf.html

[U104] JS：防抖
来源：http://dali.tian-w.cn/Article/details/gt2wdrzxqzj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2vfpaauyq.html

[U105] JS：节流
来源：http://dali.yj202588.top/Article/details/gt2olximest.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2syalejoa.html

[U106] JS：日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gt2zdrqczkj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cheryme.top/Article/details/gt2ccjnufwc.html

[U107] JS：数字千分位
来源：http://dali.c1oappe.top/Article/details/gt2bqslvtqe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gt2ymjrsmku.html

[U108] JS：随机整数
来源：http://dali.iojbl.cn/Article/details/gt2quskueiu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.meibo888.top/Article/details/gt2ejstqjub.html

[U109] JS：数组分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2feryxhgb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gt2nqwxrrfz.html

[U110] JS：数组分块
来源：http://dali.gotoacloud.top/Article/details/gt2iceeryex.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.0kj1m.cn/Article/details/gt2hkfxnwtn.html

[U111] JS：对象转 Map
来源：http://dali.hnxiangtu.top/Article/details/gt2rdfylcyl.html

new Map(Object.entries(obj))
来源：http://dali.ivvv.top/Article/details/gt2bmyfjdhs.html

[U112] JS：字符串补位
来源：http://dali.cdnleiting.top/Article/details/gt2smdgfstz.html

"7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2xphkggxu.html

[U113] JS：正则替换全部
来源：http://dali.yj20258.top/Article/details/gt2gccfzvwq.html

s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2sbtjjjtv.html

[U114] JS：JSON 深比较
来源：http://dali.9152youxi.cn/Article/details/gt2plcphurt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gt2opahorml.html

[U115] JS：生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gt2mylttlou.html

crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gt2rehtnrwl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guowangkeji.top/Article/details/gt2pwbbendd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuanzx.com/Article/details/gt2zzudiszo.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hxfcobss.html

npm i -D vitest;  npx vitest
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iocbutab.html

[U118] JS：开发服务器
来源：http://dali.yuanzhike.top/Article/details/gt2bzibhuql.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gt2kjnudfjs.html

[U119] JS：生产构建
来源：http://dali.jianghu66.top/Article/details/gt2gwttupyq.html

npx vite build
来源：http://dali.shangyingyoupin.top/Article/details/gt2xhidvfgu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xuanzx.com/Article/details/gt2oczqersl.html

import.meta.env.VITE_API_URL
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzfowixm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2dhmptdbl.html

统计汇总
来源：http://dali.jlsjyb.cn/Article/details/gt2ctehoaes.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2xthkxkze.html

按语言统计（条）：
来源：http://dali.daria6918.cn/Article/details/gt2qgefywkh.html

Python ......... 252
来源：http://dali.zycfv.cn/Article/details/gt2zhtwccbl.html

PHP ............ 252
来源：http://dali.svipenyu.cn/Article/details/gt2fksqsknf.html

JavaScript ..... 252
来源：http://dali.daria6918.cn/Article/details/gt2wthhupsp.html

TypeScript ..... 212
来源：http://dali.quarkkingdee.top/Article/details/gt2uhzxakrg.html

Java ........... 212
来源：http://dali.zhongyouzk.top/Article/details/gt2wbgnyepv.html

Go ............. 212
来源：http://dali.snrcjt.cn/Article/details/gt2fyaveonz.html

Ruby ........... 212
来源：http://dali.hywenlv.cn/Article/details/gt2qjmkydnq.html

C# ............. 212
来源：http://dali.gaohongyu789.top/Article/details/gt2jsolktxe.html

C .............. 30
来源：http://dali.svipenyu.cn/Article/details/gt2zrxhjaqw.html

C++ ............ 30
来源：http://dali.hnxiangtu.top/Article/details/gt2smlrlzdo.html

SQL ............ 90
来源：http://dali.vqdsnc.cn/Article/details/gt2ornnjkpc.html

Bash ........... 80
来源：http://dali.gotoacloud.top/Article/details/gt2phwxekwv.html

Kotlin ......... 15
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iywgpvsy.html

Swift .......... 15
来源：http://dali.9152youxi.cn/Article/details/gt2fmbqztwm.html

Lua ............ 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzzfzrex.html

Perl ........... 10
来源：http://dali.svipenyu.cn/Article/details/gt2usospzlg.html

Scala .......... 10
来源：http://dali.yj20258888.top/Article/details/gt2hoevzkwh.html

------------------------------------
来源：http://dali.xylfe.cn/Article/details/gt2mwmdjjha.html

合计 ........... 2106 条
来源：http://dali.haohaochexian.top/Article/details/gt2rmmrhgin.html

按章节统计：
来源：http://dali.guowangkeji.top/Article/details/gt2wurnjqoo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nelojpov.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gt2kumehdnj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gt2gcyekbtr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.316326.xyz/Article/details/gt2nsnxtrqg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.vqdsnc.cn/Article/details/gt2tfryliff.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cashguo.top/Article/details/gt2wrlmxgmt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangdashe.top/Article/details/gt2rsbhvsgz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gt2civnwkyo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gt2nsbzslyp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gt2xqqjszbt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gt2eejcjwib.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gt2umsinylp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gt2tbxuiabh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gt2hrztoyqm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pycfn.com/Article/details/gt2urgdneva.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gt2iwudkodu.html

Q SQL 专题                              90
来源：http://dali.hywenlv.cn/Article/details/gt2mmxhvexn.html

R Bash 专题                             80
来源：http://dali.smart0.xyz/Article/details/gt2qtlvdjop.html

S C / C++ 专题                          60
来源：http://dali.yongpay.top/Article/details/gt2zbeqiicg.html

T 其他语言补充                          60
来源：http://dali.9152youxi.cn/Article/details/gt2iqfrvnvm.html

U 高频实用片段                         120
来源：http://dali.aizwys.cn/Article/details/gt2lsdoeghx.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqtpyshy.html

合计                                  2106 条
来源：http://dali.zycfv.cn/Article/details/gt2sadxipgu.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xjzjqhyy.html

使用提醒
来源：http://dali.dianchejie.cn/Article/details/gt2ofckeouu.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gt2odpcjcsh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.bjfxy.top/Article/details/gt2ygmnbogj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nurcajox.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jqgfzy.top/Article/details/gt2jwnyjato.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hammf.cn/Article/details/gt2xegchkxv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcyvbvwj.html

—— 文件结束 ——
来源：http://dali.feifeiyinyue.top/Article/details/gt2abvkwdzj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2fzcvqcvo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nwbrower.top/Article/details/gt2drldhevn.html

Common Programming Examples Cheat Book
来源：http://dali.wangdashe.top/Article/details/gt2uesmoqne.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2aljlxwit.html

【收录内容】
来源：http://dali.ppjwa.cn/Article/details/gt2anpsifob.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigufen.top/Article/details/gt2jsibruhn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.meibo888.top/Article/details/gt2tngujzuw.html

SQL · Bash · C · C++
来源：http://dali.hammf.cn/Article/details/gt2xtapmntd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.tian-w.cn/Article/details/gt2njdcoadv.html

【使用说明】
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iiznbsoh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenlongwang.top/Article/details/gt2penudcrm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnsbijlc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yvedp.cn/Article/details/gt2uiuuldjt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.316326.xyz/Article/details/gt2dlblxfic.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinqigfzy.top/Article/details/gt2hbqmgfrk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hnqzz.top/Article/details/gt2arjzvycp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gzhubu.top/Article/details/gt2cxwjlcrm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cashguo.top/Article/details/gt2tsctzspi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenzaomai.com/Article/details/gt2fbdgejjj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jqgufenzy.top/Article/details/gt2sxppjpvt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xylfe.cn/Article/details/gt2txuiixms.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.redwolf501.top/Article/details/gt2yxydtllf.html

【文件统计】
来源：http://dali.tian-w.cn/Article/details/gt2vvtebdbh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ehwqpu.com/Article/details/gt2rgkspypd.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gt2cavcascy.html

目  录
来源：http://dali.jianghu66.top/Article/details/gt2ncnxqjlh.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2qqkxigdq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yuanzhike.top/Article/details/gt2bufqyenh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ninughlv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymbytwfb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kpqojxgh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tian-w.cn/Article/details/gt2pxdzlrvo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2ovhrflur.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.redwolf501.top/Article/details/gt2hrfjoors.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cucudq.cn/Article/details/gt2efiomgyd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gt2ombgdpfl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tian-w.cn/Article/details/gt2gxwwvtvb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gt2pqzylqdg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gt2igegewxl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gt2uoiacfps.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.nwbrower.top/Article/details/gt2jdchfamq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.fengsongda.top/Article/details/gt2mjohtnqq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gt2iqnpvcrz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sweek.top/Article/details/gt2kbateimx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jqgfzy.top/Article/details/gt2ytavasjh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.haohaochexian.top/Article/details/gt2zgamjsyy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gt2zhjsucwm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cashguo.top/Article/details/gt2mozcuuef.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2cbjuxeco.html

A. 基础语法与类型
来源：http://dali.guannengcc.top/Article/details/gt2itskadou.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2utgojxyg.html

[A01] Hello World
来源：http://dali.yuxming.cn/Article/details/gt2xacjuxlw.html

Py:   print("Hello, World!")
来源：http://dali.hywenlv.cn/Article/details/gt2uynrelyk.html

PHP:  echo "Hello, World!";
来源：http://dali.daria6918.cn/Article/details/gt2gwtemnan.html

JS:   console.log("Hello, World!");
来源：http://dali.ivvv.top/Article/details/gt2gxeylxww.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.vqdsnc.cn/Article/details/gt2rbluxfph.html

Java: System.out.println("Hello, World!");
来源：http://dali.daria6918.cn/Article/details/gt2xuhthofa.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinqigufen.top/Article/details/gt2fcwuboer.html

Ruby: puts "Hello, World!"
来源：http://dali.ivvv.top/Article/details/gt2sghnhezn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gt2ctlgzgmn.html

[A02] 变量声明与赋值
来源：http://dali.xuanzx.com/Article/details/gt2xalgionp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xziqi.cn/Article/details/gt2hsfguvli.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yuanzhike.top/Article/details/gt2ksqwhxur.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shzxlz.cn/Article/details/gt2nvwmnimy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.wangdashe.top/Article/details/gt2jejuihek.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhixingplan.top/Article/details/gt2kukpsneg.html

Go:   name := "Alex"; age := 20
来源：http://dali.0kj1m.cn/Article/details/gt2kyqkitva.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xuanzx.com/Article/details/gt2ertohkpk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.bjfxy.top/Article/details/gt2jssldmhn.html

[A03] 常量定义
来源：http://dali.chenzaomai.com/Article/details/gt2bhblyfqc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hfpthk.cn/Article/details/gt2howsrtis.html

PHP:  const PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gt2qvouyfan.html

JS:   const PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2hqosarhc.html

TS:   const PI: number = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gt2qrqohxdj.html

Java: static final double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gt2pcngoxia.html

Go:   const PI = 3.14159
来源：http://dali.hysaishi.cn/Article/details/gt2wfcvnlue.html

Ruby: PI = 3.14159
来源：http://dali.zhengqikj.top/Article/details/gt2mawwtglx.html

C#:   const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gt2paafmhwg.html

[A04] 判断变量类型
来源：http://dali.yangfankeji.com/Article/details/gt2qckckfdq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.snrcjt.cn/Article/details/gt2nkmfzclc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.snrcjt.cn/Article/details/gt2iellzmvd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gt2mkxmwsei.html

TS:   typeof x; x instanceof Date
来源：http://dali.hongshengwenyu.top/Article/details/gt2iizqkbbj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sweek.top/Article/details/gt2cibkhyhu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jianghu66.top/Article/details/gt2yayohfyt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.guannengcc.top/Article/details/gt2tmgcxefa.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzjlbnje.html

[A05] 整数除法与取模
来源：http://dali.snrcjt.cn/Article/details/gt2nmmyzzbu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jiagoushi.top/Article/details/gt2yvwaixnd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2uugymksm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gt2audzpndu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sxryk.cn/Article/details/gt2bhgpdwwc.html

Java: 7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gt2tdjzszcp.html

Go:   7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2xgpqtzek.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gt2oupmvnzl.html

C#:   7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gt2vcizepuk.html

[A06] 字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gt2miymudki.html

Py:   int("42"); float("3.14")
来源：http://dali.snrcjt.cn/Article/details/gt2itnhcfbw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.daxiang520.top/Article/details/gt2zsfspdgq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2esjvmsxg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hammf.cn/Article/details/gt2ctnisppn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gt2alqamlcp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.nwbrower.top/Article/details/gt2mfbouwlf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2drpjnpkg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mizsmztt.html

[A07] 数字转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vbnttcdt.html

Py:   str(42)
来源：http://dali.jlsjyb.cn/Article/details/gt2jvuczsbn.html

PHP:  (string) 42; strval(42)
来源：http://dali.nanxuanxn.top/Article/details/gt2cdbovqdi.html

JS:   String(42); (42).toString()
来源：http://dali.smart0.xyz/Article/details/gt2qvbmctmi.html

TS:   String(42)
来源：http://dali.ppjwa.cn/Article/details/gt2hqkbvobo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xuanzx.com/Article/details/gt2ddopospt.html

Go:   strconv.Itoa(42)
来源：http://dali.aizwys.cn/Article/details/gt2uxfkxxsj.html

Ruby: 42.to_s
来源：http://dali.sufxvd.cn/Article/details/gt2yglxvzcs.html

C#:   42.ToString()
来源：http://dali.yongpay.top/Article/details/gt2tpqimspr.html

[A08] 取整与四舍五入
来源：http://dali.ivvv.top/Article/details/gt2vjbfwpep.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gt2lyipdyxp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tian-w.cn/Article/details/gt2padaepuc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gt2qqnmfsto.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qluqjqhf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gt2dumicxfm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gt2vyefcwsi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yanxiufei.cn/Article/details/gt2tkanvypu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wguhttgt.html

[A09] 绝对值与最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gt2jlobgppl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.meibo888.top/Article/details/gt2wxidexrv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yonumen.top/Article/details/gt2onipnkyp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2dunuhfol.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2gxkzkkfo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fkegutcq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.svipenyu.cn/Article/details/gt2alokmntm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.kuanghao11.cn/Article/details/gt2jznyrxpa.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2nyuddqvv.html

[A10] 生成随机数
来源：http://dali.meibo888.top/Article/details/gt2twrvwvvm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jyoumei.cn/Article/details/gt2xqnhtlvy.html

PHP:  random_int(1, 100);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwmrglbg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ppjwa.cn/Article/details/gt2exjdheop.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shzxlz.cn/Article/details/gt2yfiwcstp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.nwbrower.top/Article/details/gt2jdzvwqmc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.dianchejie.cn/Article/details/gt2vzfmabud.html

Ruby: rand(1..100)
来源：http://dali.guowangkeji.top/Article/details/gt2nxydnvyy.html

C#:   new Random().Next(1, 101)
来源：http://dali.yuanzhike.top/Article/details/gt2wqtuahqi.html

[A11] 条件表达式（三元）
来源：http://dali.ppjwa.cn/Article/details/gt2zkprwujr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.bjfxy.top/Article/details/gt2kpecydej.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gt2rwbtykzg.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oikhzhnh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbvkpspe.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gt2yymcuefj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.dashuyun.cn/Article/details/gt2wtqrhljb.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gt2jsmupoqk.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bfigluzv.html

[A12] 字符串插值 / 格式化
来源：http://dali.jianghu66.top/Article/details/gt2scifntwl.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cucudq.cn/Article/details/gt2dkgryyvz.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jqgfzy.top/Article/details/gt2whjbtvgx.html

JS:   `Hello, ${name}!`
来源：http://dali.9152youxi.cn/Article/details/gt2ricyleqm.html

TS:   `Hello, ${name}!`
来源：http://dali.shuidangran.top/Article/details/gt2ubdjkadi.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shuidangran.top/Article/details/gt2nknwpzum.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.pycfn.com/Article/details/gt2nqkaoqma.html

Ruby: "Hello, #{name}!"
来源：http://dali.ybcxt.top/Article/details/gt2wowcvaya.html

C#:   $"Hello, {name}!"
来源：http://dali.chenzaomai.com/Article/details/gt2reodjztb.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdwoemv.html

Py:   "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gt2kqnxnwlw.html

PHP:  "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gt2bpvqssyb.html

JS:   "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gt2mngbcgpl.html

TS:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gt2dftwkmby.html

Java: "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gt2vncwnvhx.html

Go:   "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfqzxbsd.html

Ruby: "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gt2fzmnqxzk.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2shrskwae.html

[A14] 注释写法
来源：http://dali.cdnleiting.top/Article/details/gt2aooqyswr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.havefunace.top/Article/details/gt2cmipjcke.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zwouopog.html

JS:   // 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gt2cwsgfoxr.html

TS:   // 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gt2zrrosqoi.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.tian-w.cn/Article/details/gt2tlhixncy.html

Go:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gt2atshcgdm.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.sxryk.cn/Article/details/gt2jhftzsqs.html

C#:   // 单行；/* 多行 */
来源：http://dali.yvedp.cn/Article/details/gt2bttfilzt.html

[A15] 空值判断与默认值
来源：http://dali.tianlin.xyz/Article/details/gt2sxyqjpaz.html

Py:   value = data or "默认值"
来源：http://dali.cucudq.cn/Article/details/gt2dvhvysxw.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.c1oappe.top/Article/details/gt2onyrfpjg.html

JS:   const value = data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gt2iubweidc.html

TS:   const value = data ?? "默认值";
来源：http://dali.wangdashe.top/Article/details/gt2ubnwgtdh.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.sufxvd.cn/Article/details/gt2npsmgbtl.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhongyouzk.top/Article/details/gt2uyrwaost.html

Ruby: value = data || "默认值"
来源：http://dali.chenlongwang.top/Article/details/gt2pyantxqu.html

C#:   var value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gt2ixekowxi.html

[A16] 真假值判断规则
来源：http://dali.jiagoushi.top/Article/details/gt2lzahykch.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.316326.xyz/Article/details/gt2npcuauwg.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jianghu66.top/Article/details/gt2dbvnbgym.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shzxlz.cn/Article/details/gt2yqtbcjvx.html

TS:   if (!x) {}
来源：http://dali.dianchejie.cn/Article/details/gt2ctobjisq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.aizwys.cn/Article/details/gt2hgoyliqr.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ydzc1.top/Article/details/gt2ofyxhkre.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.aibaodan.cn/Article/details/gt2vgfgopmk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.redwolf501.top/Article/details/gt2qkuvprjd.html

[A17] 位运算
来源：http://dali.aibaodan.cn/Article/details/gt2mcammvnp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gt2urmfzcwn.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gt2kzgxrfjz.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gt2daqxqjqn.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gt2lgkxmcyt.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gt2abaaeugu.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gt2xqfaowxx.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gt2fzxfsndp.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gt2xuzxzqtl.html


<!-- 参考信息 -->