代发 wailian999

[U105] JS：节流
来源：http://dali.shzxlz.cn/Article/details/gt2tblbovrv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sysykeji.top/Article/details/gt2nzsbjavz.html

[U106] JS：日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjyqytiy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.quarkkingdee.top/Article/details/gt2szoeovrz.html

[U107] JS：数字千分位
来源：http://dali.jinqigfzy.top/Article/details/gt2corvzqbr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ydzc1.top/Article/details/gt2mxhcpwfb.html

[U108] JS：随机整数
来源：http://dali.gaohongyu789.top/Article/details/gt2tuiglbvi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yueranfly.top/Article/details/gt2dagreflg.html

[U109] JS：数组分组
来源：http://dali.wangdashe.top/Article/details/gt2kbgrzufz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gt2toqxxnjw.html

[U110] JS：数组分块
来源：http://dali.snrcjt.cn/Article/details/gt2gxcwkqwy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2irjjkyav.html

[U111] JS：对象转 Map
来源：http://dali.havefunace.top/Article/details/gt2kvelcllo.html

new Map(Object.entries(obj))
来源：http://dali.mhx1999.top/Article/details/gt2wvfgbtfx.html

[U112] JS：字符串补位
来源：http://dali.316326.xyz/Article/details/gt2pkqcawso.html

"7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gt2vmpiaaij.html

[U113] JS：正则替换全部
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehegoxod.html

s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2xulticix.html

[U114] JS：JSON 深比较
来源：http://dali.gogol.net.cn/Article/details/gt2kgdyesym.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ivvv.top/Article/details/gt2iolbtape.html

[U115] JS：生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gt2xokirtsu.html

crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gt2djhavgwv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guowangkeji.top/Article/details/gt2zxxhqtyq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2zucdydxs.html

[U117] JS：单元测试
来源：http://dali.chenlongwang.top/Article/details/gt2jskvmxbb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrybxwg.html

[U118] JS：开发服务器
来源：http://dali.pengpengdd.cyou/Article/details/gt2chkzvgez.html

npm i -D vite;  npx vite
来源：http://dali.tianlin.xyz/Article/details/gt2zlqwpxqq.html

[U119] JS：生产构建
来源：http://dali.hongshengwenyu.top/Article/details/gt2olapfgtd.html

npx vite build
来源：http://dali.pengpengdd.cyou/Article/details/gt2arrhzlwy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.svipenyu.cn/Article/details/gt2rgszxcut.html

import.meta.env.VITE_API_URL
来源：http://dali.nanxinkj.top/Article/details/gt2gemyskmb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2vripimok.html

统计汇总
来源：http://dali.jqgfzy.top/Article/details/gt2jvazpcjy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2akegrubw.html

按语言统计（条）：
来源：http://dali.haohaochexian.top/Article/details/gt2egqlqjsg.html

Python ......... 252
来源：http://dali.yuxming.cn/Article/details/gt2tqpiprah.html

PHP ............ 252
来源：http://dali.cucudq.cn/Article/details/gt2uuyfhvjk.html

JavaScript ..... 252
来源：http://dali.xziqi.cn/Article/details/gt2mwnighmy.html

TypeScript ..... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zfhmrosu.html

Java ........... 212
来源：http://dali.jqgufenzy.top/Article/details/gt2wnuwtaxo.html

Go ............. 212
来源：http://dali.ivvv.top/Article/details/gt2xcufvlur.html

Ruby ........... 212
来源：http://dali.jyoumei.cn/Article/details/gt2hqxzpdyn.html

C# ............. 212
来源：http://dali.yvedp.cn/Article/details/gt2gmwvdhir.html

C .............. 30
来源：http://dali.ehwqpu.com/Article/details/gt2shgjlwbe.html

C++ ............ 30
来源：http://dali.cdnleiting.top/Article/details/gt2gmffwhho.html

SQL ............ 90
来源：http://dali.nanxinkj.top/Article/details/gt2gdjyoscn.html

Bash ........... 80
来源：http://dali.nanxinkj.top/Article/details/gt2lsrqmufk.html

Kotlin ......... 15
来源：http://dali.cashguo.top/Article/details/gt2jkukinen.html

Swift .......... 15
来源：http://dali.hfpthk.cn/Article/details/gt2zviwfqjf.html

Lua ............ 10
来源：http://dali.c1oappe.top/Article/details/gt2rrmetcba.html

Perl ........... 10
来源：http://dali.jlsjyb.cn/Article/details/gt2wxjmbdtk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hclwmtzj.html

------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gt2ecmrqbkd.html

合计 ........... 2106 条
来源：http://dali.jianghu66.top/Article/details/gt2ciimvtsj.html

按章节统计：
来源：http://dali.yj202588.top/Article/details/gt2tedbpcoa.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.0kj1m.cn/Article/details/gt2nrngoqfm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gt2hjifkena.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gt2pgroglla.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sufxvd.cn/Article/details/gt2vpsbwvkd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shuidangran.top/Article/details/gt2qfeadipm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.havefunace.top/Article/details/gt2ashwgrml.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gt2dvcarvol.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gt2lnachxxz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gt2yismdyja.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gt2vfvuigaw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gt2jmayaqtn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gt2iciwubxo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gt2ciworxfu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yueranfly.top/Article/details/gt2luwkxfam.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.meibo888.top/Article/details/gt2gkaixvtk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gt2amjudtoe.html

Q SQL 专题                              90
来源：http://dali.shuidangran.top/Article/details/gt2zmmwrbke.html

R Bash 专题                             80
来源：http://dali.hywenlv.cn/Article/details/gt2bnnlyvvm.html

S C / C++ 专题                          60
来源：http://dali.ehwqpu.com/Article/details/gt2fqffnydx.html

T 其他语言补充                          60
来源：http://dali.9152youxi.cn/Article/details/gt2eadcspcb.html

U 高频实用片段                         120
来源：http://dali.jianghu66.top/Article/details/gt2oqcgtytu.html

------------------------------------
来源：http://dali.fzhhl.top/Article/details/gt2xexgzksh.html

合计                                  2106 条
来源：http://dali.ivvv.top/Article/details/gt2sjezgkxw.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gt2exturabs.html

使用提醒
来源：http://dali.hywenlv.cn/Article/details/gt2ixydsrjj.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbxrsvpz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.feifeiyinyue.top/Article/details/gt2wscporea.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.iojbl.cn/Article/details/gt2ibgggahi.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yueranfly.top/Article/details/gt2bbepmmps.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urxzitbo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xylfe.cn/Article/details/gt2gcloihml.html

—— 文件结束 ——
来源：http://dali.chenlongwang.top/Article/details/gt2ajzaozvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ccljcduy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhongyouzk.top/Article/details/gt2bldvxpgh.html

Common Programming Examples Cheat Book
来源：http://dali.redwolf501.top/Article/details/gt2pkfjlhsj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gmhrwypo.html

【收录内容】
来源：http://dali.gogol.net.cn/Article/details/gt2zramgjjc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yuxming.cn/Article/details/gt2grbisrxi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdvzdnbe.html

SQL · Bash · C · C++
来源：http://dali.hammf.cn/Article/details/gt2gyygdqbz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.dianchejie.cn/Article/details/gt2eszwmmit.html

【使用说明】
来源：http://dali.hfpthk.cn/Article/details/gt2rwnecaab.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258.top/Article/details/gt2ljceyrkn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.kuanghao11.cn/Article/details/gt2npfivify.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yuxming.cn/Article/details/gt2yyhrjqzy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yuanzhike.top/Article/details/gt2auojdbwq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2irrbjfin.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.iojbl.cn/Article/details/gt2ucvgilul.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.vqdsnc.cn/Article/details/gt2oxzxrsvr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pturvxjy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zdqjudy.top/Article/details/gt2gemcphpn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cdnleiting.top/Article/details/gt2wbrqkzik.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zdqjudy.top/Article/details/gt2abfgztsc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lewhpmtw.html

【文件统计】
来源：http://dali.gzhubu.top/Article/details/gt2qdmaryvg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.kuanghao11.cn/Article/details/gt2xivqemxt.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gt2exrurotq.html

目  录
来源：http://dali.cdnleiting.top/Article/details/gt2ukorvwol.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gt2xfseqqyb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shzxlz.cn/Article/details/gt2anemmmxu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2mpfyhbtk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.svipenyu.cn/Article/details/gt2nwthzgwh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gt2rooagdxp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinqigufen.top/Article/details/gt2pdydoffg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cacwlasz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cdnleiting.top/Article/details/gt2wgmskwzz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.aizwys.cn/Article/details/gt2clfurzpt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gt2mbsfywgn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2upgvobdg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gt2emqglyin.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gt2hlmursmr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gt2xcydotqk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2pggvhbzr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.tian-w.cn/Article/details/gt2nuxjxxpr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gt2nxusfgcl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.svipenyu.cn/Article/details/gt2xbhzpbmo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yvedp.cn/Article/details/gt2kqjzynjh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinqigufen.top/Article/details/gt2wszkhuxp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gt2cowerhgs.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj202588.top/Article/details/gt2rsgislhf.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2krjiqrfl.html

A. 基础语法与类型
来源：http://dali.zdqjudy.top/Article/details/gt2ahrslqlj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2orvwiqvj.html

[A01] Hello World
来源：http://dali.xylfe.cn/Article/details/gt2zaxyrysb.html

Py:   print("Hello, World!")
来源：http://dali.guowangkeji.top/Article/details/gt2lrnfylja.html

PHP:  echo "Hello, World!";
来源：http://dali.jyoumei.cn/Article/details/gt2imkbtbtu.html

JS:   console.log("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gt2qekrlqfr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhengqikj.top/Article/details/gt2nyzbfapd.html

Java: System.out.println("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2etknadsm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gaohongyu789.top/Article/details/gt2swgrfruw.html

Ruby: puts "Hello, World!"
来源：http://dali.cqqwz.cn/Article/details/gt2togtsrqg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gt2likrxzxo.html

[A02] 变量声明与赋值
来源：http://dali.jlsjyb.cn/Article/details/gt2jaqlqlwh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ppjwa.cn/Article/details/gt2rtdlbbvc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gt2zxnoafyx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xinyue.icu/Article/details/gt2xqnbpyye.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xylfe.cn/Article/details/gt2mlvxkxye.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xuanzx.com/Article/details/gt2zjpguina.html

Go:   name := "Alex"; age := 20
来源：http://dali.chenlongwang.top/Article/details/gt2mgvzodil.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenjidiqi.icu/Article/details/gt2sscfslsk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cashguo.top/Article/details/gt2faqnsjyf.html

[A03] 常量定义
来源：http://dali.vqdsnc.cn/Article/details/gt2sdcwyllz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhengqikj.top/Article/details/gt2kwnuptly.html

PHP:  const PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gt2yzltwfbx.html

JS:   const PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2pdwdwche.html

TS:   const PI: number = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2odoemalk.html

Java: static final double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gt2vqjjkkwc.html

Go:   const PI = 3.14159
来源：http://dali.yj20258.top/Article/details/gt2hihmvokh.html

Ruby: PI = 3.14159
来源：http://dali.birdmap.top/Article/details/gt2cvifqebu.html

C#:   const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2wqxmwwxh.html

[A04] 判断变量类型
来源：http://dali.nwbrower.top/Article/details/gt2qpwetzcq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fzhhl.top/Article/details/gt2ocpfbuju.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cashguo.top/Article/details/gt2opvwtios.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ydzc1.top/Article/details/gt2wrkhbzlh.html

TS:   typeof x; x instanceof Date
来源：http://dali.cqqwz.cn/Article/details/gt2bfvdpdrj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yuanzhike.top/Article/details/gt2cynkrslz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.tian-w.cn/Article/details/gt2rmdoliqn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bsojgjpu.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinqigufen.top/Article/details/gt2ihjuuwxt.html

[A05] 整数除法与取模
来源：http://dali.jinqigfzy.top/Article/details/gt2xggwrlij.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.fzhhl.top/Article/details/gt2kluzetys.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gt2unjegzdd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrtuknhv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258888.top/Article/details/gt2gencugrz.html

Java: 7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gt2fuymjuzv.html

Go:   7 / 2; 7 % 2
来源：http://dali.birdmap.top/Article/details/gt2dngwjaos.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xztkmjgf.html

C#:   7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gt2dprclcpr.html

[A06] 字符串转数字
来源：http://dali.havefunace.top/Article/details/gt2ukbgdewc.html

Py:   int("42"); float("3.14")
来源：http://dali.cheryme.top/Article/details/gt2ouzveiia.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.fengsongda.top/Article/details/gt2ojcroaix.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.meibo888.top/Article/details/gt2rbihgqcd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sweek.top/Article/details/gt2buijqwoo.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.quarkkingdee.top/Article/details/gt2ybfpsxaw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sysykeji.top/Article/details/gt2wiqthyft.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinqigfzy.top/Article/details/gt2pexjjsum.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xslblhjl.html

[A07] 数字转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2jynyolvq.html

Py:   str(42)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ortzwqrt.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhongyouzk.top/Article/details/gt2gbvnokwf.html

JS:   String(42); (42).toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2nvzowuyo.html

TS:   String(42)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vduxccor.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xylfe.cn/Article/details/gt2cfobpdqq.html

Go:   strconv.Itoa(42)
来源：http://dali.wangdashe.top/Article/details/gt2opcymlvo.html

Ruby: 42.to_s
来源：http://dali.xylfe.cn/Article/details/gt2phvbqwyx.html

C#:   42.ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2comkdlxc.html

[A08] 取整与四舍五入
来源：http://dali.yj20258.top/Article/details/gt2qipijmvs.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gt2lnlghyet.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hfpthk.cn/Article/details/gt2hcithztf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tznputru.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ainjtqwk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gt2vunribgk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gt2dydpsibs.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yonumen.top/Article/details/gt2qdfogjjz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gt2rtenhepu.html

[A09] 绝对值与最大最小值
来源：http://dali.sweek.top/Article/details/gt2kweacdei.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2gbdylvef.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2ejjrebbh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2ydcfsvdv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2iayojyiq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2sbqyxvxz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.chenjidiqi.icu/Article/details/gt2oejhfuke.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sysykeji.top/Article/details/gt2gonlbemz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2rwutgwin.html

[A10] 生成随机数
来源：http://dali.zhoulong.xyz/Article/details/gt2gvsnmqph.html

Py:   import random; random.randint(1, 100)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hkhuqxbp.html

PHP:  random_int(1, 100);
来源：http://dali.yangfankeji.com/Article/details/gt2mjrpbumf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sufxvd.cn/Article/details/gt2dooadpui.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sxryk.cn/Article/details/gt2tpohgksg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.daxiang520.top/Article/details/gt2nuyupiqh.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.mhx1999.top/Article/details/gt2oqlttksq.html

Ruby: rand(1..100)
来源：http://dali.redwolf501.top/Article/details/gt2qqfjnwjc.html

C#:   new Random().Next(1, 101)
来源：http://dali.nanxuanxn.top/Article/details/gt2afhhdjmz.html

[A11] 条件表达式（三元）
来源：http://dali.gzhubu.top/Article/details/gt2qtiuzxmu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rewtkkyk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gt2filwvhak.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gt2tjtgeslm.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gt2znlsbqfr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.aibaodan.cn/Article/details/gt2lwlwnwqb.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xuanzx.com/Article/details/gt2qzvmfkny.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gt2rvrbxxwj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gt2suxpcxsf.html

[A12] 字符串插值 / 格式化
来源：http://dali.ppjwa.cn/Article/details/gt2mzpbjckd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.wangdashe.top/Article/details/gt2kliqsovu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sgsqrdzg.html

JS:   `Hello, ${name}!`
来源：http://dali.cashguo.top/Article/details/gt2gzqjwxux.html

TS:   `Hello, ${name}!`
来源：http://dali.c1oappe.top/Article/details/gt2xxbenzjw.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.andypj.xyz/Article/details/gt2ydnihevo.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.meibo888.top/Article/details/gt2xdyzifyy.html

Ruby: "Hello, #{name}!"
来源：http://dali.sxryk.cn/Article/details/gt2rkywsbjk.html

C#:   $"Hello, {name}!"
来源：http://dali.hfpthk.cn/Article/details/gt2njxjyeyn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shuidangran.top/Article/details/gt2kdxoladd.html

Py:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gt2lgwvvxur.html

PHP:  "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gt2gwnryhsv.html

JS:   "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gt2bnbeinzs.html

TS:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gt2rmpncges.html

Java: "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gt2wvoagquy.html

Go:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gt2eidcwcoz.html

Ruby: "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gt2acshprep.html

C#:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gt2kabdjdnb.html

[A14] 注释写法
来源：http://dali.sweek.top/Article/details/gt2mncgtoob.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.redwolf501.top/Article/details/gt2qfmkqhpe.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yvedp.cn/Article/details/gt2vdoksrbr.html

JS:   // 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gt2ognqwyjb.html

TS:   // 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gt2tuzjuxsx.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.nanxinkj.top/Article/details/gt2gmizxdzf.html

Go:   // 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pidodlfj.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hfpthk.cn/Article/details/gt2ngstrsfv.html

C#:   // 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gt2mrrpxblj.html

[A15] 空值判断与默认值
来源：http://dali.vqdsnc.cn/Article/details/gt2dihimswn.html

Py:   value = data or "默认值"
来源：http://dali.hammf.cn/Article/details/gt2ctymqlhg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gt2rukysgda.html

JS:   const value = data ?? "默认值";
来源：http://dali.yongpay.top/Article/details/gt2yvcadnxl.html

TS:   const value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gt2puqsaetx.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.316326.xyz/Article/details/gt2fjllvmns.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.havefunace.top/Article/details/gt2nvskqxeo.html

Ruby: value = data || "默认值"
来源：http://dali.snrcjt.cn/Article/details/gt2zhoizxqb.html

C#:   var value = data ?? "默认值";
来源：http://dali.haohaochexian.top/Article/details/gt2ajooxpej.html

[A16] 真假值判断规则
来源：http://dali.yuxming.cn/Article/details/gt2fplxdayu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.chenzaomai.com/Article/details/gt2pesgqffd.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.daria6918.cn/Article/details/gt2dwzhwgek.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.daxiang520.top/Article/details/gt2nrzmdxlk.html

TS:   if (!x) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnutrdaa.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.fzhhl.top/Article/details/gt2dlpmevmk.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqpaevqw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinqigufen.top/Article/details/gt2yifpaqaq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.andypj.xyz/Article/details/gt2wbeyehag.html

[A17] 位运算
来源：http://dali.zhengqikj.top/Article/details/gt2ywaqwfcm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gt2kbwzyplx.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gt2irsilyeg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gt2pzybywtf.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jojlkzrk.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gt2yswbsehq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gt2xgfwukdt.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xcigzktq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gt2vzilolzk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.pycfn.com/Article/details/gt2dqrxqcra.html

Py:   ord("A"); chr(65)
来源：http://dali.jlsjyb.cn/Article/details/gt2hvzprfrp.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hltgdyee.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymwudaub.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cashguo.top/Article/details/gt2uggrxfvx.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhoulong.xyz/Article/details/gt2abkubuou.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhixingplan.top/Article/details/gt2xyiwfpup.html

Ruby: "A".ord; 65.chr
来源：http://dali.fzhhl.top/Article/details/gt2ycpjycza.html


<!-- 参考信息 -->