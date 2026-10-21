代发 wailian999

[U105] JS：节流
来源：http://dali.yangfankeji.com/Article/details/gthjsktvmh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.svipenyu.cn/Article/details/gthcpfwxqp.html

[U106] JS：日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtxoupfdsw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xylfe.cn/Article/details/gtwxmhcgfm.html

[U107] JS：数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtzcnlycri.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gtdindthwh.html

[U108] JS：随机整数
来源：http://dali.xuetiantiany.cn/Article/details/gteydfkjiq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gtpwyetcjl.html

[U109] JS：数组分组
来源：http://dali.sysykeji.top/Article/details/gthesdtkxk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtmkdhyreo.html

[U110] JS：数组分块
来源：http://dali.pycfn.com/Article/details/gtqmrpybpw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shangyingyoupin.top/Article/details/gtcpbgucsx.html

[U111] JS：对象转 Map
来源：http://dali.hfpthk.cn/Article/details/gtushcmguy.html

new Map(Object.entries(obj))
来源：http://dali.fzhhl.top/Article/details/gtiguqpedi.html

[U112] JS：字符串补位
来源：http://dali.yongpay.top/Article/details/gtnlyhutak.html

"7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtundlqrxm.html

[U113] JS：正则替换全部
来源：http://dali.aibaodan.cn/Article/details/gthwoliulm.html

s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtbcxmfidp.html

[U114] JS：JSON 深比较
来源：http://dali.jqgfzy.top/Article/details/gtlyejnfaa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtakvxvejt.html

[U115] JS：生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gtdvkacrmx.html

crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtdqpznujt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenjidiqi.icu/Article/details/gtbptrxwja.html

/** @param {string} name */ function f(name) {}
来源：http://dali.aizwys.cn/Article/details/gtovlqrhjl.html

[U117] JS：单元测试
来源：http://dali.jianghu66.top/Article/details/gtwxdingsc.html

npm i -D vitest;  npx vitest
来源：http://dali.tanke756.top/Article/details/gtsngneyyi.html

[U118] JS：开发服务器
来源：http://dali.feifeiyinyue.top/Article/details/gttjlguapj.html

npm i -D vite;  npx vite
来源：http://dali.iojbl.cn/Article/details/gtsrizwegk.html

[U119] JS：生产构建
来源：http://dali.sysykeji.top/Article/details/gtfmuohebv.html

npx vite build
来源：http://dali.yongpay.top/Article/details/gtzyefefcz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangdashe.top/Article/details/gtjiziqapq.html

import.meta.env.VITE_API_URL
来源：http://dali.iojbl.cn/Article/details/gthqeagovc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtvebclkqc.html

统计汇总
来源：http://dali.nwbrower.top/Article/details/gtmowkvdbb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtrkmbphbf.html

按语言统计（条）：
来源：http://dali.yonumen.top/Article/details/gtedtgbxai.html

Python ......... 252
来源：http://dali.c1oappe.top/Article/details/gtpwsxbwvo.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqzvgddi.html

JavaScript ..... 252
来源：http://dali.jinqigfzy.top/Article/details/gtzakwpgot.html

TypeScript ..... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwmozhwg.html

Java ........... 212
来源：http://dali.yuanzhike.top/Article/details/gtoydxttvf.html

Go ............. 212
来源：http://dali.nanxinkj.top/Article/details/gtnowzezve.html

Ruby ........... 212
来源：http://dali.jianghu66.top/Article/details/gtkssfrlqy.html

C# ............. 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqyzcgdw.html

C .............. 30
来源：http://dali.zdqjudy.top/Article/details/gttbybeiet.html

C++ ............ 30
来源：http://dali.wangdashe.top/Article/details/gtlzkkxujn.html

SQL ............ 90
来源：http://dali.guowangkeji.top/Article/details/gtjxlvxciu.html

Bash ........... 80
来源：http://dali.tian-w.cn/Article/details/gtsvkkxeft.html

Kotlin ......... 15
来源：http://dali.cashguo.top/Article/details/gtazcytqiz.html

Swift .......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gtpzekalua.html

Lua ............ 10
来源：http://dali.wangdashe.top/Article/details/gtglxwxkrq.html

Perl ........... 10
来源：http://dali.gaohongyu789.top/Article/details/gtwqnvltdl.html

Scala .......... 10
来源：http://dali.feifeiyinyue.top/Article/details/gteezoqgtb.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtyrudexco.html

合计 ........... 2106 条
来源：http://dali.sysykeji.top/Article/details/gttjtkchdn.html

按章节统计：
来源：http://dali.yj20258.top/Article/details/gttpgwjusr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yuxming.cn/Article/details/gtagiovptb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gtndtkrhix.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gtmphcowei.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.316326.xyz/Article/details/gtczqfvdpd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sxryk.cn/Article/details/gtxaibtafs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gtrczxcatr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gtglkgbksh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yangfankeji.com/Article/details/gtymnxlvxd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtdxdpnjqq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ivvv.top/Article/details/gtzenfovqn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gtjyssbjrw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtubtvnigw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtmsfekrvp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.birdmap.top/Article/details/gttrrumqap.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.birdmap.top/Article/details/gtccopakuq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gtytxwhfmq.html

Q SQL 专题                              90
来源：http://dali.daria6918.cn/Article/details/gtfwutuhaq.html

R Bash 专题                             80
来源：http://dali.cashguo.top/Article/details/gthwfjeeqy.html

S C / C++ 专题                          60
来源：http://dali.kuanghao11.cn/Article/details/gtwkxmizxl.html

T 其他语言补充                          60
来源：http://dali.ydzc1.top/Article/details/gtprijvafw.html

U 高频实用片段                         120
来源：http://dali.nwbrower.top/Article/details/gtqalqyfey.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gtpjtuxbri.html

合计                                  2106 条
来源：http://dali.kuanghao11.cn/Article/details/gtxfxbzjzk.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gttzblziom.html

使用提醒
来源：http://dali.sweek.top/Article/details/gtqvotvurm.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtxwvmhpvz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.iojbl.cn/Article/details/gtjyxnelnf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yanxiufei.cn/Article/details/gtgibwrqeh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shuidangran.top/Article/details/gtscejokkn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hongshengwenyu.top/Article/details/gtymrccdqx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yongpay.top/Article/details/gtwpkiylit.html

—— 文件结束 ——
来源：http://dali.yj202588.top/Article/details/gtxlmoqreg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gttctxsvxy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.sufxvd.cn/Article/details/gtxcaixthj.html

Common Programming Examples Cheat Book
来源：http://dali.cdnleiting.top/Article/details/gthvbvabjb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtvbjgbjdi.html

【收录内容】
来源：http://dali.yueranfly.top/Article/details/gtyhlaaggr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.kuanghao11.cn/Article/details/gtvvsuwnar.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.haohaochexian.top/Article/details/gtiqakfxnx.html

SQL · Bash · C · C++
来源：http://dali.0kj1m.cn/Article/details/gtqnreclsu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jqgfzy.top/Article/details/gtetospqjd.html

【使用说明】
来源：http://dali.9152youxi.cn/Article/details/gtscrpabrg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zdqjudy.top/Article/details/gtlizqeash.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sweek.top/Article/details/gtlnuskbzt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zycfv.cn/Article/details/gtqhjhcxtx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hysaishi.cn/Article/details/gtcaamxceq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hammf.cn/Article/details/gtqamtkolr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.aibaodan.cn/Article/details/gtqajpxewr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.pycfn.com/Article/details/gtqqyngrzr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.guowangkeji.top/Article/details/gthquuzemj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hfpthk.cn/Article/details/gtxartslxm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jinqigfzy.top/Article/details/gteilkrkut.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ybcxt.top/Article/details/gtfndafxvh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yangfankeji.com/Article/details/gtvgaxmkdt.html

【文件统计】
来源：http://dali.xziqi.cn/Article/details/gtnwczbntf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sweek.top/Article/details/gtrxcaumrl.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gttyoqmzws.html

目  录
来源：http://dali.vqdsnc.cn/Article/details/gtatcsminj.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gtebdasewt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sxryk.cn/Article/details/gtqmagkswv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvdilqaq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.aibaodan.cn/Article/details/gtkyossuvn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhixingplan.top/Article/details/gtojuidrgx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxuanxn.top/Article/details/gtmcstcjks.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.birdmap.top/Article/details/gtvxvyocwo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sysykeji.top/Article/details/gtsirhakxy.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jiagoushi.top/Article/details/gtfzrojmkg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtyhhyctge.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtpozqnggv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpmlehpe.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gtgretqlei.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gteoxwkgdy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.316326.xyz/Article/details/gtyiypivzi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.daxiang520.top/Article/details/gtpbvmwhcv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtrlmvtfhd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.nwbrower.top/Article/details/gtvwuuabeu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.havefunace.top/Article/details/gtwfeioqlv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yj202588.top/Article/details/gtlggndigl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gtjxvoeflp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqlhodha.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtmaoqosnh.html

A. 基础语法与类型
来源：http://dali.tanke756.top/Article/details/gtfralixke.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuplxtur.html

[A01] Hello World
来源：http://dali.yuanzhike.top/Article/details/gtthtmfjmv.html

Py:   print("Hello, World!")
来源：http://dali.yueranfly.top/Article/details/gtxgovlqmr.html

PHP:  echo "Hello, World!";
来源：http://dali.jqgufenzy.top/Article/details/gtmxevggow.html

JS:   console.log("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gthqzqtowk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinghuilouyu.cn/Article/details/gtywxscwoa.html

Java: System.out.println("Hello, World!");
来源：http://dali.xziqi.cn/Article/details/gturruskmt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gtrsxtqhfj.html

Ruby: puts "Hello, World!"
来源：http://dali.redwolf501.top/Article/details/gtdiqnjkdo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.fzhhl.top/Article/details/gtpexrfsxy.html

[A02] 变量声明与赋值
来源：http://dali.hfpthk.cn/Article/details/gtxfypttde.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.guowangkeji.top/Article/details/gtyhchacwz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gthfdzkhux.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.daria6918.cn/Article/details/gtslipuqmk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.wangdashe.top/Article/details/gtypfvrkut.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cqqwz.cn/Article/details/gtbmanjnlr.html

Go:   name := "Alex"; age := 20
来源：http://dali.ppjwa.cn/Article/details/gtncejjwpu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jqgfzy.top/Article/details/gtfzajubkw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jyoumei.cn/Article/details/gtmdzqsahi.html

[A03] 常量定义
来源：http://dali.smart0.xyz/Article/details/gtwppsvyyh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hnxiangtu.top/Article/details/gtmcflovqx.html

PHP:  const PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtfblujaax.html

JS:   const PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gttubxpsic.html

TS:   const PI: number = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtgapywfke.html

Java: static final double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtdihhuwlg.html

Go:   const PI = 3.14159
来源：http://dali.xuetiantiany.cn/Article/details/gtgddqevih.html

Ruby: PI = 3.14159
来源：http://dali.zhiwuduotai.top/Article/details/gtohizxfbn.html

C#:   const double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtqojzcixm.html

[A04] 判断变量类型
来源：http://dali.gzhubu.top/Article/details/gtpdvlbnwx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cheryme.top/Article/details/gtkytusnsh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jqgfzy.top/Article/details/gtjjgdqfbh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.smart0.xyz/Article/details/gtewqdqbnq.html

TS:   typeof x; x instanceof Date
来源：http://dali.hammf.cn/Article/details/gtouscummx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yuanzhike.top/Article/details/gtzbozusaj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yj202588.top/Article/details/gttopzipuj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhiwuduotai.top/Article/details/gtnvvypgdf.html

C#:   x.GetType().Name; x is int
来源：http://dali.hysaishi.cn/Article/details/gtmxzshyrq.html

[A05] 整数除法与取模
来源：http://dali.fzhhl.top/Article/details/gtgrsmowdv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.tian-w.cn/Article/details/gtobsdiaho.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.tanke756.top/Article/details/gtwbhnmvaj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtjahuhrcs.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pycfn.com/Article/details/gtgthnnlpi.html

Java: 7 / 2; 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtsdfulomh.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtwcipobmw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtwbekppri.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtzmazumlw.html

[A06] 字符串转数字
来源：http://dali.guannengcc.top/Article/details/gtpupyxoqs.html

Py:   int("42"); float("3.14")
来源：http://dali.chenlongwang.top/Article/details/gtptdektzb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ybcxt.top/Article/details/gtjilpynsw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.0kj1m.cn/Article/details/gtrspsatkc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.vqdsnc.cn/Article/details/gtaeioxtmj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jqgufenzy.top/Article/details/gtlamkqctl.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgdzwkuv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hywenlv.cn/Article/details/gtpnkdpwof.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jlsjyb.cn/Article/details/gthdvphwro.html

[A07] 数字转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrknrlyo.html

Py:   str(42)
来源：http://dali.hongshengwenyu.top/Article/details/gtquadkpfo.html

PHP:  (string) 42; strval(42)
来源：http://dali.aibaodan.cn/Article/details/gtinginmgs.html

JS:   String(42); (42).toString()
来源：http://dali.jqgfzy.top/Article/details/gtpbwmocaz.html

TS:   String(42)
来源：http://dali.tian-w.cn/Article/details/gtccmqctcr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ehwqpu.com/Article/details/gtfbpmkgbw.html

Go:   strconv.Itoa(42)
来源：http://dali.gotoacloud.top/Article/details/gtlxwuiwlz.html

Ruby: 42.to_s
来源：http://dali.sysykeji.top/Article/details/gtuduldtag.html

C#:   42.ToString()
来源：http://dali.tian-w.cn/Article/details/gtjecdvyyh.html

[A08] 取整与四舍五入
来源：http://dali.xylfe.cn/Article/details/gtuqkgtuyt.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gtougqixhp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.guowangkeji.top/Article/details/gtrjqlipdi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gtrtvjuhnb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.nanxuanxn.top/Article/details/gtisczkulq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtfmsryprg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.meibo888.top/Article/details/gtmqzrjmta.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.nwbrower.top/Article/details/gtvpuaasqf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.c1oappe.top/Article/details/gtpkkhogvy.html

[A09] 绝对值与最大最小值
来源：http://dali.yvedp.cn/Article/details/gtzciicpjs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gtfvoctnhx.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtfmogycsz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gttrqwvvbv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gtpqzkgfqm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtrncommmo.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.havefunace.top/Article/details/gtfmsqlaph.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cucudq.cn/Article/details/gtjojcsezu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtyemaygcf.html

[A10] 生成随机数
来源：http://dali.yj20258.top/Article/details/gtyjhsxblp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.c1oappe.top/Article/details/gtycjuzjlf.html

PHP:  random_int(1, 100);
来源：http://dali.yj202588.top/Article/details/gtuzzboxru.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gtuxyzbpni.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sysykeji.top/Article/details/gtflkheicj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.dianchejie.cn/Article/details/gtwfdyfqps.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.nwbrower.top/Article/details/gtdixqxzoj.html

Ruby: rand(1..100)
来源：http://dali.cucudq.cn/Article/details/gtqwldrnci.html

C#:   new Random().Next(1, 101)
来源：http://dali.meibo888.top/Article/details/gtvvhhrlhi.html

[A11] 条件表达式（三元）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpejxcvbz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.havefunace.top/Article/details/gtrbiuahtw.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gtgjsbvfzz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gtlvoxmxlx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gtpqnshvsj.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnkaouqi.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.sufxvd.cn/Article/details/gtotsukrqr.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtqryxpttr.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtvmflybaf.html

[A12] 字符串插值 / 格式化
来源：http://dali.yongpay.top/Article/details/gtdgeeltky.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.tian-w.cn/Article/details/gtvraovzkl.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ivvv.top/Article/details/gtdlhrsshm.html

JS:   `Hello, ${name}!`
来源：http://dali.jqgufenzy.top/Article/details/gtytgqsoje.html

TS:   `Hello, ${name}!`
来源：http://dali.cucudq.cn/Article/details/gtqwxoowau.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.chenjidiqi.icu/Article/details/gtinvpoden.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.snrcjt.cn/Article/details/gtsrbygpzh.html

Ruby: "Hello, #{name}!"
来源：http://dali.nwbrower.top/Article/details/gtaewsjhyt.html

C#:   $"Hello, {name}!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazwmbdtk.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.redwolf501.top/Article/details/gtrwdwiolu.html

Py:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtcqywfaiq.html

PHP:  "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gtsjemqpiq.html

JS:   "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gtzzybhfcb.html

TS:   "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtyvbjfnnf.html

Java: "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtibhpwyop.html

Go:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtojkuaghy.html

Ruby: "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtaqmtcqse.html

C#:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtiurdnizg.html

[A14] 注释写法
来源：http://dali.iojbl.cn/Article/details/gtsepiewor.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zycfv.cn/Article/details/gtzhpkbbap.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gtvpkhsqaw.html

JS:   // 单行；/* 多行 */
来源：http://dali.kuanghao11.cn/Article/details/gttwnhdmdw.html

TS:   // 单行；/* 多行 */
来源：http://dali.andypj.xyz/Article/details/gtfqizwmiw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shuidangran.top/Article/details/gtanusisoy.html

Go:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gtahmgftgm.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhengqikj.top/Article/details/gtkermdnzd.html

C#:   // 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gtoaiwwvhy.html

[A15] 空值判断与默认值
来源：http://dali.jqgufenzy.top/Article/details/gttixxekqe.html

Py:   value = data or "默认值"
来源：http://dali.jinqigufen.top/Article/details/gtyomxruie.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gteqejhwqo.html

JS:   const value = data ?? "默认值";
来源：http://dali.meibo888.top/Article/details/gtvkgmtwrq.html

TS:   const value = data ?? "默认值";
来源：http://dali.havefunace.top/Article/details/gtiuffnssy.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hfpthk.cn/Article/details/gtwjqxiurm.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.guannengcc.top/Article/details/gtlvgyitxd.html

Ruby: value = data || "默认值"
来源：http://dali.guannengcc.top/Article/details/gtdvfdcrhu.html

C#:   var value = data ?? "默认值";
来源：http://dali.hongshengwenyu.top/Article/details/gtloalrouq.html

[A16] 真假值判断规则
来源：http://dali.hnxiangtu.top/Article/details/gtsdvtjtmb.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.snrcjt.cn/Article/details/gtklgolpfh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.sysykeji.top/Article/details/gtblvnqxhq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cashguo.top/Article/details/gtgnivcils.html

TS:   if (!x) {}
来源：http://dali.jqgufenzy.top/Article/details/gtglsncwzo.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtwpjrnmvk.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhoulong.xyz/Article/details/gtmlnnjoif.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hongshengwenyu.top/Article/details/gtkhcvtwtk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cashguo.top/Article/details/gtzadokaen.html

[A17] 位运算
来源：http://dali.hfpthk.cn/Article/details/gttdgxjdwt.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gtwgphsxdk.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.wangdashe.top/Article/details/gtiklhthfx.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtxtdhjrld.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtluzmjszl.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gtyjvmrags.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gthmizrplg.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gtqfdoypsl.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtqrusrecv.html

[A18] 字符与 ASCII 码互转
来源：http://dali.wangshuangyany.cn/Article/details/gtszsjhgld.html

Py:   ord("A"); chr(65)
来源：http://dali.jianghu66.top/Article/details/gtduaacouz.html

PHP:  ord("A"); chr(65)
来源：http://dali.chenjidiqi.icu/Article/details/gtoohrrcya.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sufxvd.cn/Article/details/gtbbxbnxca.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jlsjyb.cn/Article/details/gtdmvjevsm.html

Java: (int) 'A'; (char) 65
来源：http://dali.gaohongyu789.top/Article/details/gtnkcunqwi.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacuvgoze.html

Ruby: "A".ord; 65.chr
来源：http://dali.iojbl.cn/Article/details/gtkswruacf.html


<!-- 参考信息 -->