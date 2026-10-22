代发 wailian999

[U105] JS：节流
来源：http://dali.cheryme.top/Article/details/gt2ylwmdzlk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgfzy.top/Article/details/gt2selfkisa.html

[U106] JS：日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2hxnzywph.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlcsudy.html

[U107] JS：数字千分位
来源：http://dali.meibo888.top/Article/details/gt2mgvoxpsm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gt2xdcbaidr.html

[U108] JS：随机整数
来源：http://dali.zhiwuduotai.top/Article/details/gt2wblrqduj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tianlin.xyz/Article/details/gt2thgovgde.html

[U109] JS：数组分组
来源：http://dali.iojbl.cn/Article/details/gt2azzxuujh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gt2dngeqmze.html

[U110] JS：数组分块
来源：http://dali.yj202588.top/Article/details/gt2buveqvni.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhiwuduotai.top/Article/details/gt2vvkxlqdf.html

[U111] JS：对象转 Map
来源：http://dali.yangfankeji.com/Article/details/gt2hdyoszpb.html

new Map(Object.entries(obj))
来源：http://dali.quarkkingdee.top/Article/details/gt2rmcwzddi.html

[U112] JS：字符串补位
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtgnbsll.html

"7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gt2bhsvphuz.html

[U113] JS：正则替换全部
来源：http://dali.xziqi.cn/Article/details/gt2lnumctvz.html

s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2gealrdov.html

[U114] JS：JSON 深比较
来源：http://dali.zdqjudy.top/Article/details/gt2fnobezue.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2omopjzhe.html

[U115] JS：生成 UUID
来源：http://dali.cashguo.top/Article/details/gt2qrsrceeo.html

crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2fucbxlar.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.aibaodan.cn/Article/details/gt2jxqrqdtl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2wilkgzrv.html

[U117] JS：单元测试
来源：http://dali.xylfe.cn/Article/details/gt2wegjouxp.html

npm i -D vitest;  npx vitest
来源：http://dali.tianlin.xyz/Article/details/gt2reteyiic.html

[U118] JS：开发服务器
来源：http://dali.svipenyu.cn/Article/details/gt2orqxkiiq.html

npm i -D vite;  npx vite
来源：http://dali.guowangkeji.top/Article/details/gt2pzylvafv.html

[U119] JS：生产构建
来源：http://dali.jlsjyb.cn/Article/details/gt2azzzdufz.html

npx vite build
来源：http://dali.smart0.xyz/Article/details/gt2fnblhvwh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fzhhl.top/Article/details/gt2opcxjmti.html

import.meta.env.VITE_API_URL
来源：http://dali.daxiang520.top/Article/details/gt2fbpwjhch.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2myfjrnvq.html

统计汇总
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwrvidla.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2wfntlhiw.html

按语言统计（条）：
来源：http://dali.pengpengdd.cyou/Article/details/gt2ipccnrkd.html

Python ......... 252
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ucxcwefr.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbxncowp.html

JavaScript ..... 252
来源：http://dali.xuanzx.com/Article/details/gt2pxfmvmcr.html

TypeScript ..... 212
来源：http://dali.ydzc1.top/Article/details/gt2xphkmllc.html

Java ........... 212
来源：http://dali.zhixingplan.top/Article/details/gt2copjrxyd.html

Go ............. 212
来源：http://dali.ppjwa.cn/Article/details/gt2yvxnrhcw.html

Ruby ........... 212
来源：http://dali.ivvv.top/Article/details/gt2pmkskjzs.html

C# ............. 212
来源：http://dali.cucudq.cn/Article/details/gt2nzrowyat.html

C .............. 30
来源：http://dali.wangdashe.top/Article/details/gt2hfpsdpkm.html

C++ ............ 30
来源：http://dali.pengpengdd.cyou/Article/details/gt2dgrzktap.html

SQL ............ 90
来源：http://dali.gaohongyu789.top/Article/details/gt2fwirxaxh.html

Bash ........... 80
来源：http://dali.sxryk.cn/Article/details/gt2dlxkzwjl.html

Kotlin ......... 15
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgqhjbju.html

Swift .......... 15
来源：http://dali.cdnleiting.top/Article/details/gt2bhvgbqwg.html

Lua ............ 10
来源：http://dali.jlsjyb.cn/Article/details/gt2sgttexya.html

Perl ........... 10
来源：http://dali.meibo888.top/Article/details/gt2rqvapndy.html

Scala .......... 10
来源：http://dali.nwbrower.top/Article/details/gt2rmphbywa.html

------------------------------------
来源：http://dali.pycfn.com/Article/details/gt2trcwizrr.html

合计 ........... 2106 条
来源：http://dali.hnqzz.top/Article/details/gt2fvhdlurv.html

按章节统计：
来源：http://dali.bjfxy.top/Article/details/gt2bthfjfyf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gt2higuiwbc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gt2bliwdbqn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gt2flkvodfe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqdveyfv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shuidangran.top/Article/details/gt2bqnwqrhq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yj20258888.top/Article/details/gt2bccmhaeb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gt2quizamfl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmseghds.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gt2avsyezwr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zdqjudy.top/Article/details/gt2xizohqag.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gt2fmgevwup.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gt2jbajcvby.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gt2bguaagzg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhoulong.xyz/Article/details/gt2mekhswtz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenlongwang.top/Article/details/gt2gbnwqfuj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gt2mixbiqkv.html

Q SQL 专题                              90
来源：http://dali.gogol.net.cn/Article/details/gt2lkjykplj.html

R Bash 专题                             80
来源：http://dali.0kj1m.cn/Article/details/gt2tfvhvlrq.html

S C / C++ 专题                          60
来源：http://dali.xinyue.icu/Article/details/gt2dntgmkda.html

T 其他语言补充                          60
来源：http://dali.vqdsnc.cn/Article/details/gt2ctdubihr.html

U 高频实用片段                         120
来源：http://dali.yj20258.top/Article/details/gt2glcybgfc.html

------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gt2kevvohoe.html

合计                                  2106 条
来源：http://dali.xinyue.icu/Article/details/gt2zayczbbd.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gt2swglrwdj.html

使用提醒
来源：http://dali.daria6918.cn/Article/details/gt2mprxsxso.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gt2ttrkanhf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jlsjyb.cn/Article/details/gt2qvzwtxjt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sxryk.cn/Article/details/gt2awsyxhmw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwsqsgnk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.snrcjt.cn/Article/details/gt2xfnfemlt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.guowangkeji.top/Article/details/gt2ubujgveb.html

—— 文件结束 ——
来源：http://dali.shanyushiyangtech.top/Article/details/gt2akfmpssk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2xziiorox.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.mhx1999.top/Article/details/gt2peajqevi.html

Common Programming Examples Cheat Book
来源：http://dali.zycfv.cn/Article/details/gt2isxprajj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2zvasmoij.html

【收录内容】
来源：http://dali.9152youxi.cn/Article/details/gt2qrrlqerc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.redwolf501.top/Article/details/gt2hbfsnzhv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xylfe.cn/Article/details/gt2iwybdfvw.html

SQL · Bash · C · C++
来源：http://dali.316326.xyz/Article/details/gt2lpskbyjf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.wangshuangyany.cn/Article/details/gt2mklqntia.html

【使用说明】
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brxvycrb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258888.top/Article/details/gt2hwzqrxqd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.haohaochexian.top/Article/details/gt2qlmixqyi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhengqikj.top/Article/details/gt2jnttmgvt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tanke756.top/Article/details/gt2cgnstsmq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.dashuyun.cn/Article/details/gt2zvhhpckk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.kuanghao11.cn/Article/details/gt2alyauepo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cheryme.top/Article/details/gt2elnqngen.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2lvemhyyg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yj20258.top/Article/details/gt2tnpyfmue.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yanxiufei.cn/Article/details/gt2piiodvnm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.iojbl.cn/Article/details/gt2xpzluklq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.vqdsnc.cn/Article/details/gt2rgqacput.html

【文件统计】
来源：http://dali.xziqi.cn/Article/details/gt2etkjtgig.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.svipenyu.cn/Article/details/gt2glmrdcvn.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gt2lpuqhioi.html

目  录
来源：http://dali.yanxiufei.cn/Article/details/gt2rismokdf.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gt2rltbctvm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hammf.cn/Article/details/gt2sdhyclal.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nanxinkj.top/Article/details/gt2kcuvbjsu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gt2jliqfymy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2swnkzqge.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tian-w.cn/Article/details/gt2qnvhihby.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxcomxqe.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gt2zjsubrql.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sweek.top/Article/details/gt2dkgzznex.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gt2goyuqple.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cqqwz.cn/Article/details/gt2bnqbllci.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gt2rmraeoar.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2bijngvmp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2jvvqjoad.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hywenlv.cn/Article/details/gt2ofdiwnlx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.wangdashe.top/Article/details/gt2uhdqyepo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gt2zeygyvrb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xinyue.icu/Article/details/gt2vennmlra.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2jbafopol.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cheryme.top/Article/details/gt2jszpdzmv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gt2chxnbdce.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.bjfxy.top/Article/details/gt2iisgwboq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2bluvhuic.html

A. 基础语法与类型
来源：http://dali.dashuyun.cn/Article/details/gt2pafarmfs.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2adcjjnje.html

[A01] Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2ntqkrkst.html

Py:   print("Hello, World!")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrhhartp.html

PHP:  echo "Hello, World!";
来源：http://dali.ydzc1.top/Article/details/gt2wammyctt.html

JS:   console.log("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gt2mzapcbxa.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinqigfzy.top/Article/details/gt2ivhrsdbr.html

Java: System.out.println("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gt2jwsgtbrn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hnqzz.top/Article/details/gt2ppxsbuqg.html

Ruby: puts "Hello, World!"
来源：http://dali.zhongyouzk.top/Article/details/gt2wyvvqhkf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.fengsongda.top/Article/details/gt2lksnkcjm.html

[A02] 变量声明与赋值
来源：http://dali.wangshuangyany.cn/Article/details/gt2trkqofze.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gogol.net.cn/Article/details/gt2inwoighy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yangfankeji.com/Article/details/gt2tyitzevs.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnewtdbc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.smart0.xyz/Article/details/gt2oqkltgkr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhixingplan.top/Article/details/gt2vjrhufgk.html

Go:   name := "Alex"; age := 20
来源：http://dali.xuanzx.com/Article/details/gt2upswgezr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hywenlv.cn/Article/details/gt2pyydwsoo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinqigufen.top/Article/details/gt2gvdnljjh.html

[A03] 常量定义
来源：http://dali.sweek.top/Article/details/gt2dlfkwhbm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yongpay.top/Article/details/gt2mpkkhnjs.html

PHP:  const PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sonyoczl.html

JS:   const PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2mcktobhh.html

TS:   const PI: number = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2zszvhkzx.html

Java: static final double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2ujbdujqn.html

Go:   const PI = 3.14159
来源：http://dali.zhongyouzk.top/Article/details/gt2xjrajylb.html

Ruby: PI = 3.14159
来源：http://dali.birdmap.top/Article/details/gt2pquvarnm.html

C#:   const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2yovejytk.html

[A04] 判断变量类型
来源：http://dali.chenlongwang.top/Article/details/gt2chrzixqq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fzhhl.top/Article/details/gt2griqmopb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hnxiangtu.top/Article/details/gt2qyebfqmy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jianghu66.top/Article/details/gt2zsblvqgw.html

TS:   typeof x; x instanceof Date
来源：http://dali.hnqzz.top/Article/details/gt2aneexpir.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhengqikj.top/Article/details/gt2ntbydltu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.tanke756.top/Article/details/gt2aomouoaq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gzhubu.top/Article/details/gt2jhlqseni.html

C#:   x.GetType().Name; x is int
来源：http://dali.sysykeji.top/Article/details/gt2yoxizmrp.html

[A05] 整数除法与取模
来源：http://dali.cdnleiting.top/Article/details/gt2qqstcmxo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ybcxt.top/Article/details/gt2vduvnidd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gt2btutsbgj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gt2lkfdsafs.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gt2tuivuebm.html

Java: 7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gt2jnsnljqt.html

Go:   7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gt2pqdorvxd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gt2jkhgpxwr.html

C#:   7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gt2xxijhbaz.html

[A06] 字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gt2egennsgm.html

Py:   int("42"); float("3.14")
来源：http://dali.hnqzz.top/Article/details/gt2licmwmnf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhongyouzk.top/Article/details/gt2mihlvfpg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.fzhhl.top/Article/details/gt2ndroxppu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.iojbl.cn/Article/details/gt2dybohftv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xinyue.icu/Article/details/gt2skorpwhu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npcgcchj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.vqdsnc.cn/Article/details/gt2hekvqdbn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.316326.xyz/Article/details/gt2akvjmksa.html

[A07] 数字转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2qdgnxrpk.html

Py:   str(42)
来源：http://dali.xylfe.cn/Article/details/gt2gpyuldag.html

PHP:  (string) 42; strval(42)
来源：http://dali.guannengcc.top/Article/details/gt2tvuiumjc.html

JS:   String(42); (42).toString()
来源：http://dali.ivvv.top/Article/details/gt2yqhpdqcs.html

TS:   String(42)
来源：http://dali.bjfxy.top/Article/details/gt2wszrqqna.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.dianchejie.cn/Article/details/gt2afxqbqbu.html

Go:   strconv.Itoa(42)
来源：http://dali.cashguo.top/Article/details/gt2xfudimuv.html

Ruby: 42.to_s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2znlmbxeu.html

C#:   42.ToString()
来源：http://dali.nanxuanxn.top/Article/details/gt2mbmlifep.html

[A08] 取整与四舍五入
来源：http://dali.316326.xyz/Article/details/gt2czsbyskl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eoqdmadv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.dianchejie.cn/Article/details/gt2yviofgkq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gt2ryiqmaaj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yboxbjig.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gt2wqxmfoke.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gt2oqzjeeff.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzsjmoaj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zdtfjhqt.html

[A09] 绝对值与最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gt2hmshfhpx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yvedp.cn/Article/details/gt2qzusggqq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.meibo888.top/Article/details/gt2qhkrolhl.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2digknzqv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2hsbayylo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2hygkaoan.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yuanzhike.top/Article/details/gt2hsppzdnv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gotoacloud.top/Article/details/gt2thlmcsed.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xylfe.cn/Article/details/gt2bxbhxgjd.html

[A10] 生成随机数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ryihynls.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2kshohjnz.html

PHP:  random_int(1, 100);
来源：http://dali.yueranfly.top/Article/details/gt2kkclixep.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sxryk.cn/Article/details/gt2ppabubfz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.pycfn.com/Article/details/gt2opkxxroz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj20258.top/Article/details/gt2dzrguhxx.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.fengsongda.top/Article/details/gt2naruwkeg.html

Ruby: rand(1..100)
来源：http://dali.guowangkeji.top/Article/details/gt2mnzlpnag.html

C#:   new Random().Next(1, 101)
来源：http://dali.sysykeji.top/Article/details/gt2eqptqlge.html

[A11] 条件表达式（三元）
来源：http://dali.iojbl.cn/Article/details/gt2odalisgs.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yvedp.cn/Article/details/gt2aggvyxjq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgqgvmek.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gt2alreokbk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gt2dbioasfm.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gt2gnkbpwfy.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.chenlongwang.top/Article/details/gt2iqtjpedi.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhongyouzk.top/Article/details/gt2spxpoznr.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gt2mhsnnlmg.html

[A12] 字符串插值 / 格式化
来源：http://dali.yuxming.cn/Article/details/gt2burebhpk.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbqyqhna.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yuanzhike.top/Article/details/gt2yjhnobhn.html

JS:   `Hello, ${name}!`
来源：http://dali.svipenyu.cn/Article/details/gt2mxifspwv.html

TS:   `Hello, ${name}!`
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulfunjll.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jinqigfzy.top/Article/details/gt2kkohxwgf.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2odzrhceb.html

Ruby: "Hello, #{name}!"
来源：http://dali.sxryk.cn/Article/details/gt2vpmtwroe.html

C#:   $"Hello, {name}!"
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsxnkaso.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sxryk.cn/Article/details/gt2dmettipm.html

Py:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gt2puhrzrkx.html

PHP:  "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gt2tkonktxh.html

JS:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gt2ebhrvekk.html

TS:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gt2zohspuyk.html

Java: "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gt2bdwivowz.html

Go:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gt2tokahlrj.html

Ruby: "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gt2xcecbkql.html

C#:   "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfnlmxzn.html

[A14] 注释写法
来源：http://dali.ivvv.top/Article/details/gt2whhuxuqr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yangfankeji.com/Article/details/gt2drkuenfd.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.dashuyun.cn/Article/details/gt2othdddvl.html

JS:   // 单行；/* 多行 */
来源：http://dali.ehwqpu.com/Article/details/gt2imxinhqb.html

TS:   // 单行；/* 多行 */
来源：http://dali.sysykeji.top/Article/details/gt2mqgxtbmz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.316326.xyz/Article/details/gt2rsitovcp.html

Go:   // 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gt2hbpoylgk.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hfpthk.cn/Article/details/gt2xxiipbjr.html

C#:   // 单行；/* 多行 */
来源：http://dali.dianchejie.cn/Article/details/gt2gsotzxpx.html

[A15] 空值判断与默认值
来源：http://dali.guannengcc.top/Article/details/gt2xxftabti.html

Py:   value = data or "默认值"
来源：http://dali.ehwqpu.com/Article/details/gt2ngdagtcr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.sxryk.cn/Article/details/gt2cbggewlm.html

JS:   const value = data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gt2dvmcxquz.html

TS:   const value = data ?? "默认值";
来源：http://dali.jqgufenzy.top/Article/details/gt2vqilejnf.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xuanzx.com/Article/details/gt2qxajbxms.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.gogol.net.cn/Article/details/gt2kuaskqbm.html

Ruby: value = data || "默认值"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kqgvbhqr.html

C#:   var value = data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gt2qucesrlm.html

[A16] 真假值判断规则
来源：http://dali.ivvv.top/Article/details/gt2uqnugiag.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yj20258888.top/Article/details/gt2hhcxkzwc.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.nanxinkj.top/Article/details/gt2nyorotuj.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.iojbl.cn/Article/details/gt2rppbjxuf.html

TS:   if (!x) {}
来源：http://dali.gogol.net.cn/Article/details/gt2puhquzwb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.meibo888.top/Article/details/gt2bhhsawbc.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.9152youxi.cn/Article/details/gt2dbnnlavj.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yvedp.cn/Article/details/gt2zafqudtb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.meibo888.top/Article/details/gt2ymulwyuo.html

[A17] 位运算
来源：http://dali.meibo888.top/Article/details/gt2ycpbmkkc.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gt2kqbpacnv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2otcfcudj.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gt2rletwmqh.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iuuorbmp.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gt2emixjxcv.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2zsirfxgf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uyyvottd.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gt2zyzebdbc.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cdnleiting.top/Article/details/gt2qhlhfdfv.html

Py:   ord("A"); chr(65)
来源：http://dali.jiagoushi.top/Article/details/gt2cwnghwlz.html

PHP:  ord("A"); chr(65)
来源：http://dali.ybcxt.top/Article/details/gt2zssuetjg.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ydzc1.top/Article/details/gt2fwoxdpih.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tianlin.xyz/Article/details/gt2lolnktue.html

Java: (int) 'A'; (char) 65
来源：http://dali.tian-w.cn/Article/details/gt2cjvtspbg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.tanke756.top/Article/details/gt2lbiuxapa.html

Ruby: "A".ord; 65.chr
来源：http://dali.birdmap.top/Article/details/gt2lmsdmfbb.html


<!-- 参考信息 -->