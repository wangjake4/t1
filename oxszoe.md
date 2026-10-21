代发 wailian999

[U103] JS：定时器
来源：http://dali.yuxming.cn/Article/details/gtnoicbfij.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sufxvd.cn/Article/details/gttpmwnzmu.html

[U104] JS：防抖
来源：http://dali.0kj1m.cn/Article/details/gtkolhesev.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gttzslsvci.html

[U105] JS：节流
来源：http://dali.c1oappe.top/Article/details/gtsmijfsha.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.smart0.xyz/Article/details/gtvlealtqe.html

[U106] JS：日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtojsqzgio.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cqqwz.cn/Article/details/gtaxthlupq.html

[U107] JS：数字千分位
来源：http://dali.gogol.net.cn/Article/details/gtdyctllbv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtjjzlihur.html

[U108] JS：随机整数
来源：http://dali.dashuyun.cn/Article/details/gtqtvnwoij.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.wangshuangyany.cn/Article/details/gtvquyumst.html

[U109] JS：数组分组
来源：http://dali.tanke756.top/Article/details/gtamneayoc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtxrfjeuwi.html

[U110] JS：数组分块
来源：http://dali.ivvv.top/Article/details/gtviqmiort.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ydzc1.top/Article/details/gtrnbfbhwj.html

[U111] JS：对象转 Map
来源：http://dali.jlsjyb.cn/Article/details/gtuxeyedwy.html

new Map(Object.entries(obj))
来源：http://dali.ivvv.top/Article/details/gtiwihdqkm.html

[U112] JS：字符串补位
来源：http://dali.chenjidiqi.icu/Article/details/gtviwmtheh.html

"7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gteexfovln.html

[U113] JS：正则替换全部
来源：http://dali.aizwys.cn/Article/details/gtogezmmsv.html

s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtgohbeatn.html

[U114] JS：JSON 深比较
来源：http://dali.xuanzx.com/Article/details/gttksmqwid.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gtxutbmahk.html

[U115] JS：生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gtpbzrvwza.html

crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gthqmnhzuy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj20258888.top/Article/details/gtxesampee.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnksxzpw.html

[U117] JS：单元测试
来源：http://dali.hongshengwenyu.top/Article/details/gtglipjrdo.html

npm i -D vitest;  npx vitest
来源：http://dali.ydzc1.top/Article/details/gtiyaoxlzg.html

[U118] JS：开发服务器
来源：http://dali.hongshengwenyu.top/Article/details/gtutfumxib.html

npm i -D vite;  npx vite
来源：http://dali.shangyingyoupin.top/Article/details/gtgqytigdg.html

[U119] JS：生产构建
来源：http://dali.cucudq.cn/Article/details/gteckrteaq.html

npx vite build
来源：http://dali.fengsongda.top/Article/details/gtbbltnxnc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yuanzhike.top/Article/details/gtopwzjdab.html

import.meta.env.VITE_API_URL
来源：http://dali.cashguo.top/Article/details/gtivmubdkp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtswxdlwpq.html

统计汇总
来源：http://dali.jinqigfzy.top/Article/details/gtpiqiyunz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtssbsysum.html

按语言统计（条）：
来源：http://dali.nanxuanxn.top/Article/details/gtjtobuhmo.html

Python ......... 252
来源：http://dali.cucudq.cn/Article/details/gtmhmfwsqk.html

PHP ............ 252
来源：http://dali.quarkkingdee.top/Article/details/gtslovsxlg.html

JavaScript ..... 252
来源：http://dali.wangdashe.top/Article/details/gttufslurk.html

TypeScript ..... 212
来源：http://dali.zhixingplan.top/Article/details/gtohuwjuuw.html

Java ........... 212
来源：http://dali.meibo888.top/Article/details/gtkchefasg.html

Go ............. 212
来源：http://dali.zdqjudy.top/Article/details/gtuykzcxfy.html

Ruby ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gtzllzwsxw.html

C# ............. 212
来源：http://dali.yueranfly.top/Article/details/gtdrasiatx.html

C .............. 30
来源：http://dali.jinqigufen.top/Article/details/gtvhipvdyv.html

C++ ............ 30
来源：http://dali.jinqigufen.top/Article/details/gtryipakvg.html

SQL ............ 90
来源：http://dali.316326.xyz/Article/details/gtpvvvgemx.html

Bash ........... 80
来源：http://dali.ydzc1.top/Article/details/gtdskxvkyt.html

Kotlin ......... 15
来源：http://dali.daxiang520.top/Article/details/gtogwdbigj.html

Swift .......... 15
来源：http://dali.zhongyouzk.top/Article/details/gthldwoyrw.html

Lua ............ 10
来源：http://dali.birdmap.top/Article/details/gtzhqdabcp.html

Perl ........... 10
来源：http://dali.chenlongwang.top/Article/details/gtgcjkxtau.html

Scala .......... 10
来源：http://dali.ydzc1.top/Article/details/gtpbycekho.html

------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtqsofdxol.html

合计 ........... 2106 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gttckojudj.html

按章节统计：
来源：http://dali.hysaishi.cn/Article/details/gtlznnneri.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gtlnxdjlyp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gtnxywgihd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gtrxepadcr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fzhhl.top/Article/details/gtbfactiuj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gaohongyu789.top/Article/details/gtjjungecv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhengqikj.top/Article/details/gthtsmmyns.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gtpbhlwcfu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cashguo.top/Article/details/gtukiohnzv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtqloiwbbk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cqqwz.cn/Article/details/gtjshsouas.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtodbmchjx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gthpvsfmyh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtuwulgkwk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hammf.cn/Article/details/gtbrcvblny.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gzhubu.top/Article/details/gtbxubrvsc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtuosjxfhh.html

Q SQL 专题                              90
来源：http://dali.ydzc1.top/Article/details/gtfvhecfce.html

R Bash 专题                             80
来源：http://dali.wangdashe.top/Article/details/gttjhuzfwk.html

S C / C++ 专题                          60
来源：http://dali.zdqjudy.top/Article/details/gtgxxbfotx.html

T 其他语言补充                          60
来源：http://dali.xylfe.cn/Article/details/gtsnjhsmwk.html

U 高频实用片段                         120
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymwjrryu.html

------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtuqfdjnmh.html

合计                                  2106 条
来源：http://dali.pengpengdd.cyou/Article/details/gtfxuqxhgz.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtlodjnuhf.html

使用提醒
来源：http://dali.zhengqikj.top/Article/details/gtirozacxh.html

--------------------------------------------------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtdawjwicv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yuanzhike.top/Article/details/gtlvylcyfy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ppjwa.cn/Article/details/gtvrlenegz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gaohongyu789.top/Article/details/gtjzbzngfc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tianlin.xyz/Article/details/gtewjyjasz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafetshht.html

—— 文件结束 ——
来源：http://dali.jqgfzy.top/Article/details/gtoumteeex.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqisgtupa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.gaohongyu789.top/Article/details/gtiprntabv.html

Common Programming Examples Cheat Book
来源：http://dali.yj202588.top/Article/details/gtilywbvvc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxegciwru.html

【收录内容】
来源：http://dali.birdmap.top/Article/details/gtoofigyma.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.redwolf501.top/Article/details/gtggmdydxs.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.vqdsnc.cn/Article/details/gtdepdoneo.html

SQL · Bash · C · C++
来源：http://dali.aibaodan.cn/Article/details/gtprqwrtaf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.fzhhl.top/Article/details/gtlasswfom.html

【使用说明】
来源：http://dali.sxryk.cn/Article/details/gtvwvnvfrg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tanke756.top/Article/details/gtpfjlymrs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zdqjudy.top/Article/details/gtgyvrxdwz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinghuilouyu.cn/Article/details/gtofqvsaey.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.chenzaomai.com/Article/details/gtjowgmrtb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinqigufen.top/Article/details/gtuhnyavtd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hfpthk.cn/Article/details/gtsandehgk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinqigufen.top/Article/details/gtajxueaus.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nwbrower.top/Article/details/gtllytsaew.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gtdcxxnrbk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnmteefi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.redwolf501.top/Article/details/gtcrcoizqt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.mhx1999.top/Article/details/gtpgdbgagv.html

【文件统计】
来源：http://dali.andypj.xyz/Article/details/gtyzzxvpsp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ivvv.top/Article/details/gtdpieafzu.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtmdjramcg.html

目  录
来源：http://dali.shzxlz.cn/Article/details/gtagdguaiv.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtmwnjxxmo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gtxfwqfbcx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gtxgltaidv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gtsivavpvx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.mhx1999.top/Article/details/gtvqqwhlno.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jianghu66.top/Article/details/gtqoupewbl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxuanxn.top/Article/details/gtbgsdgfeq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gtsvdkjzdc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sysykeji.top/Article/details/gtcniqgcbh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gtrbaeprwb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.andypj.xyz/Article/details/gtovhddmad.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtvigdfjuj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbymllokk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gtapqrrzqq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.9152youxi.cn/Article/details/gtwnxwreme.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sysykeji.top/Article/details/gtjydjihpm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gthnkzxopr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yangfankeji.com/Article/details/gtpksqmegw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shuidangran.top/Article/details/gtnqqemawu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyosnwvk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gtmaxuuzvx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.birdmap.top/Article/details/gtudfiqddx.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtqkxdjulx.html

A. 基础语法与类型
来源：http://dali.svipenyu.cn/Article/details/gtghzgdktq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkecmbeir.html

[A01] Hello World
来源：http://dali.aibaodan.cn/Article/details/gtqddqreog.html

Py:   print("Hello, World!")
来源：http://dali.pengpengdd.cyou/Article/details/gtqsrgrofd.html

PHP:  echo "Hello, World!";
来源：http://dali.yuanzhike.top/Article/details/gteubodxzy.html

JS:   console.log("Hello, World!");
来源：http://dali.pycfn.com/Article/details/gtbregjokw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yonumen.top/Article/details/gtwqckxjqc.html

Java: System.out.println("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gtfekprcry.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jiagoushi.top/Article/details/gtwyifnwiw.html

Ruby: puts "Hello, World!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtripewowj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jianghu66.top/Article/details/gtsxcvpxnz.html

[A02] 变量声明与赋值
来源：http://dali.svipenyu.cn/Article/details/gthbkulkdq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xuetiantiany.cn/Article/details/gtnfvxigqb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hnqzz.top/Article/details/gtmmbvfcnj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gteyxrxuag.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sufxvd.cn/Article/details/gtmqhlrony.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.mhx1999.top/Article/details/gtsvknqzti.html

Go:   name := "Alex"; age := 20
来源：http://dali.shzxlz.cn/Article/details/gtolmikjky.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nwbrower.top/Article/details/gtcilkwddu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ybcxt.top/Article/details/gtyqovomsn.html

[A03] 常量定义
来源：http://dali.pengpengdd.cyou/Article/details/gtclbeczzp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cqqwz.cn/Article/details/gtbvpojyjx.html

PHP:  const PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtyxstzpig.html

JS:   const PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtwkbbelcy.html

TS:   const PI: number = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtihknhaat.html

Java: static final double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpmsygmr.html

Go:   const PI = 3.14159
来源：http://dali.cqqwz.cn/Article/details/gtonkwiwyw.html

Ruby: PI = 3.14159
来源：http://dali.jinghuilouyu.cn/Article/details/gtxziolefm.html

C#:   const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtdfzcsamk.html

[A04] 判断变量类型
来源：http://dali.feifeiyinyue.top/Article/details/gtzwkzflbc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.smart0.xyz/Article/details/gtszhztlnb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.fengsongda.top/Article/details/gtkhdvklmm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sufxvd.cn/Article/details/gtagrumwii.html

TS:   typeof x; x instanceof Date
来源：http://dali.gogol.net.cn/Article/details/gtojiaigmq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoceodbce.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.tian-w.cn/Article/details/gthqwckwvq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.chenzaomai.com/Article/details/gtfrnyygrd.html

C#:   x.GetType().Name; x is int
来源：http://dali.yonumen.top/Article/details/gtvtylqnng.html

[A05] 整数除法与取模
来源：http://dali.shzxlz.cn/Article/details/gtargxkvfe.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zdqjudy.top/Article/details/gtmhztksto.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtiugjuaqw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtzaiqmknn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxudklxx.html

Java: 7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtjofonvic.html

Go:   7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gttlftpxme.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gtfnialerp.html

C#:   7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gtvrxbkebp.html

[A06] 字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gtreczvdzl.html

Py:   int("42"); float("3.14")
来源：http://dali.jyoumei.cn/Article/details/gtftvaukuk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.bjfxy.top/Article/details/gtljcsoyyf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cashguo.top/Article/details/gtcdbzbmyn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sysykeji.top/Article/details/gtrwioetkc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zdqjudy.top/Article/details/gtmxcvhuxn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ppjwa.cn/Article/details/gtnvqifmap.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jianghu66.top/Article/details/gtyshctxtx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xuanzx.com/Article/details/gtampsyijn.html

[A07] 数字转字符串
来源：http://dali.316326.xyz/Article/details/gtgmxcvzld.html

Py:   str(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyiarcvxm.html

PHP:  (string) 42; strval(42)
来源：http://dali.wangshuangyany.cn/Article/details/gtpumudouh.html

JS:   String(42); (42).toString()
来源：http://dali.shuidangran.top/Article/details/gtjhrswadp.html

TS:   String(42)
来源：http://dali.yonumen.top/Article/details/gtcxpmgnzd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jianghu66.top/Article/details/gtjzclmuey.html

Go:   strconv.Itoa(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnikioojv.html

Ruby: 42.to_s
来源：http://dali.nanxinkj.top/Article/details/gttdnidzsj.html

C#:   42.ToString()
来源：http://dali.smart0.xyz/Article/details/gtdjftroqj.html

[A08] 取整与四舍五入
来源：http://dali.iojbl.cn/Article/details/gtmmmujgko.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gtgrdtptuc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.aizwys.cn/Article/details/gtkancqymw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.meibo888.top/Article/details/gtgcennbxy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.vqdsnc.cn/Article/details/gtdphjbimg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gtozaplila.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gtluyykfdq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zdqjudy.top/Article/details/gtoagtknms.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gtyecbiiip.html

[A09] 绝对值与最大最小值
来源：http://dali.0kj1m.cn/Article/details/gtqwbczqah.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtqpgpgyou.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtstccxavc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yj202588.top/Article/details/gtyzkyoemg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtlkfypbpj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtbjgxdezc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.snrcjt.cn/Article/details/gttnapvbrw.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhiwuduotai.top/Article/details/gtzocmfetv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtwofgeshz.html

[A10] 生成随机数
来源：http://dali.cqqwz.cn/Article/details/gthnxftdah.html

Py:   import random; random.randint(1, 100)
来源：http://dali.quarkkingdee.top/Article/details/gtjmpjbbyy.html

PHP:  random_int(1, 100);
来源：http://dali.zhongyouzk.top/Article/details/gtvvlqlgvr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guowangkeji.top/Article/details/gtuiifgyre.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ivvv.top/Article/details/gtxuglosul.html

Java: new Random().nextInt(100) + 1
来源：http://dali.nanxuanxn.top/Article/details/gtfsjjhczb.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.dianchejie.cn/Article/details/gtwqembvye.html

Ruby: rand(1..100)
来源：http://dali.yj202588.top/Article/details/gtyihzjmxp.html

C#:   new Random().Next(1, 101)
来源：http://dali.quarkkingdee.top/Article/details/gtdpynsjso.html

[A11] 条件表达式（三元）
来源：http://dali.nanxinkj.top/Article/details/gtgedtmpte.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xziqi.cn/Article/details/gtpgvpukke.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gtznzwnffu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258.top/Article/details/gtmgkfdhrs.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gtzfcgkccv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gtaxqdqqov.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yvedp.cn/Article/details/gtlmvjizbh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtmfcjllvu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gtgeoqcjzw.html

[A12] 字符串插值 / 格式化
来源：http://dali.sxryk.cn/Article/details/gtjrmrdphg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.daxiang520.top/Article/details/gtnbkzhbti.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.wangshuangyany.cn/Article/details/gtumntklkp.html

JS:   `Hello, ${name}!`
来源：http://dali.shangyingyoupin.top/Article/details/gtdwpnuutg.html

TS:   `Hello, ${name}!`
来源：http://dali.316326.xyz/Article/details/gtttyabucr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.sysykeji.top/Article/details/gtcmwmzzfm.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.cashguo.top/Article/details/gtuxwumlcv.html

Ruby: "Hello, #{name}!"
来源：http://dali.jinqigufen.top/Article/details/gtfpdqhqxq.html

C#:   $"Hello, {name}!"
来源：http://dali.redwolf501.top/Article/details/gthletgelq.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.smart0.xyz/Article/details/gtykceydwt.html

Py:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnlmibhm.html

PHP:  "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gtytdzlwaz.html

JS:   "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gtdpaptfec.html

TS:   "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gttjxfhpdm.html

Java: "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gtvuwdujvn.html

Go:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtjpgukqjp.html

Ruby: "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gtwupujzjs.html

C#:   "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gttrzutcpz.html

[A14] 注释写法
来源：http://dali.cqqwz.cn/Article/details/gtntrpgwac.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xziqi.cn/Article/details/gtcccnzmyn.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.ydzc1.top/Article/details/gtywzkumtf.html

JS:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gthobisreh.html

TS:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gtmboyepyw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jlsjyb.cn/Article/details/gtariskkds.html

Go:   // 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gttutfwnfk.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.guannengcc.top/Article/details/gtbpqawzpu.html

C#:   // 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gtqvgdimqg.html

[A15] 空值判断与默认值
来源：http://dali.yanxiufei.cn/Article/details/gttsiqsemx.html

Py:   value = data or "默认值"
来源：http://dali.tianlin.xyz/Article/details/gtlwvbyhsl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gtdzikizod.html

JS:   const value = data ?? "默认值";
来源：http://dali.yongpay.top/Article/details/gtfbcxbuza.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhiwuduotai.top/Article/details/gtbcmgkcdh.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhpladit.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.0kj1m.cn/Article/details/gtxmshhzsw.html

Ruby: value = data || "默认值"
来源：http://dali.daria6918.cn/Article/details/gtplbhvldi.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gtsusypqew.html

[A16] 真假值判断规则
来源：http://dali.dashuyun.cn/Article/details/gtdvcwqflg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ivvv.top/Article/details/gtcnbfneid.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.pycfn.com/Article/details/gtxreojkgj.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.wangdashe.top/Article/details/gtlevhrjgg.html

TS:   if (!x) {}
来源：http://dali.daria6918.cn/Article/details/gtvailjisi.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jiagoushi.top/Article/details/gtlvjpkumw.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shangyingyoupin.top/Article/details/gtztgvuntw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yonumen.top/Article/details/gtjhcfdirc.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zdqjudy.top/Article/details/gtjlbvppxk.html

[A17] 位运算
来源：http://dali.shuidangran.top/Article/details/gtkcsglemf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gttkiebinl.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtwnwvkdlc.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gtbvgxgtgq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gtyzcgvrkk.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gteizbnhpz.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtawejziia.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gtmyvnrnsv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtciuauepl.html

[A18] 字符与 ASCII 码互转
来源：http://dali.chenzaomai.com/Article/details/gtyqpgqhcq.html

Py:   ord("A"); chr(65)
来源：http://dali.xuetiantiany.cn/Article/details/gtqddtoeyy.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhiwuduotai.top/Article/details/gtsferthoj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenzaomai.com/Article/details/gtvtzuoqgv.html


<!-- 参考信息 -->