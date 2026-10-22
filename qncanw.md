代发 wailian999

[U105] JS：节流
来源：http://dali.ppjwa.cn/Article/details/gtifcjzjlu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinqigufen.top/Article/details/gtbuwkwbha.html

[U106] JS：日期格式化
来源：http://dali.sxryk.cn/Article/details/gthubxluyi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gotoacloud.top/Article/details/gtaugnmcvu.html

[U107] JS：数字千分位
来源：http://dali.yvedp.cn/Article/details/gtrqablpsk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nanxinkj.top/Article/details/gthltoxqdi.html

[U108] JS：随机整数
来源：http://dali.jianghu66.top/Article/details/gtwtdfrlvz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ehwqpu.com/Article/details/gtpsihtoao.html

[U109] JS：数组分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybqntskg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgkavzrt.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknooddph.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hywenlv.cn/Article/details/gtgndwxzae.html

[U111] JS：对象转 Map
来源：http://dali.yuxming.cn/Article/details/gtlavafwkc.html

new Map(Object.entries(obj))
来源：http://dali.xinyue.icu/Article/details/gtesijfxnd.html

[U112] JS：字符串补位
来源：http://dali.yvedp.cn/Article/details/gtculuvlhd.html

"7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gttcqmxunh.html

[U113] JS：正则替换全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjisemaph.html

s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtnmboqigi.html

[U114] JS：JSON 深比较
来源：http://dali.fengsongda.top/Article/details/gtraplkfgd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gthmgtwiua.html

[U115] JS：生成 UUID
来源：http://dali.zhiwuduotai.top/Article/details/gtdubqwgvy.html

crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtsmkymntv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cqqwz.cn/Article/details/gthrkbrypn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenlongwang.top/Article/details/gtwisvwtut.html

[U117] JS：单元测试
来源：http://dali.dashuyun.cn/Article/details/gtmrgozsgm.html

npm i -D vitest;  npx vitest
来源：http://dali.c1oappe.top/Article/details/gtababptpb.html

[U118] JS：开发服务器
来源：http://dali.wangdashe.top/Article/details/gtogukainz.html

npm i -D vite;  npx vite
来源：http://dali.meibo888.top/Article/details/gtuzkeulyg.html

[U119] JS：生产构建
来源：http://dali.jqgfzy.top/Article/details/gtkrchhhwx.html

npx vite build
来源：http://dali.nwbrower.top/Article/details/gtvpstytng.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zdqjudy.top/Article/details/gtzqrwioir.html

import.meta.env.VITE_API_URL
来源：http://dali.tianlin.xyz/Article/details/gthsvdetcp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtjzumbjyl.html

统计汇总
来源：http://dali.zhoulong.xyz/Article/details/gtmpfghrob.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtebcaimzi.html

按语言统计（条）：
来源：http://dali.shanyushiyangtech.top/Article/details/gtszudjllv.html

Python ......... 252
来源：http://dali.tian-w.cn/Article/details/gtmjsjukbx.html

PHP ............ 252
来源：http://dali.shangyingyoupin.top/Article/details/gttnfilrul.html

JavaScript ..... 252
来源：http://dali.cdnleiting.top/Article/details/gtsgdqfbla.html

TypeScript ..... 212
来源：http://dali.tanke756.top/Article/details/gtdohsbkus.html

Java ........... 212
来源：http://dali.zycfv.cn/Article/details/gtaeqfoany.html

Go ............. 212
来源：http://dali.gotoacloud.top/Article/details/gtcslzgqfq.html

Ruby ........... 212
来源：http://dali.pycfn.com/Article/details/gtqptsauir.html

C# ............. 212
来源：http://dali.xziqi.cn/Article/details/gtktywcfze.html

C .............. 30
来源：http://dali.zdqjudy.top/Article/details/gtvqankemu.html

C++ ............ 30
来源：http://dali.fzhhl.top/Article/details/gtzrqkmmow.html

SQL ............ 90
来源：http://dali.zdqjudy.top/Article/details/gtkkloyjig.html

Bash ........... 80
来源：http://dali.aibaodan.cn/Article/details/gtqrvuzavi.html

Kotlin ......... 15
来源：http://dali.cqqwz.cn/Article/details/gtcwgyjfgu.html

Swift .......... 15
来源：http://dali.jqgufenzy.top/Article/details/gtaetneeqp.html

Lua ............ 10
来源：http://dali.sysykeji.top/Article/details/gtpvibderd.html

Perl ........... 10
来源：http://dali.xinyue.icu/Article/details/gtphmoqemd.html

Scala .......... 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvieilpte.html

------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtjsdapbtm.html

合计 ........... 2106 条
来源：http://dali.ivvv.top/Article/details/gtoqpovbui.html

按章节统计：
来源：http://dali.tian-w.cn/Article/details/gthvcikouu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhengqikj.top/Article/details/gtqeargbwa.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gtkpnhxllw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gtzjltjdeo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenlongwang.top/Article/details/gtwlvkfitg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hongshengwenyu.top/Article/details/gtmonrygks.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gtvuoofsbb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gtokalzoqp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gtluwhjcjp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtybptmmjq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gtaskprcol.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizzjiqkl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtxjiioany.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtzgvprcie.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.nanxuanxn.top/Article/details/gtfvnxhvot.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhongyouzk.top/Article/details/gtjbuasoyh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtfwraqoic.html

Q SQL 专题                              90
来源：http://dali.ydzc1.top/Article/details/gtiuqajxyx.html

R Bash 专题                             80
来源：http://dali.wangshuangyany.cn/Article/details/gtpdvsbfuc.html

S C / C++ 专题                          60
来源：http://dali.yuxming.cn/Article/details/gtumtczapg.html

T 其他语言补充                          60
来源：http://dali.dashuyun.cn/Article/details/gtlzvxfbjd.html

U 高频实用片段                         120
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdykoisnp.html

------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtikwingtt.html

合计                                  2106 条
来源：http://dali.hysaishi.cn/Article/details/gtkzjcslrv.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtwauicxpm.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gtvlrfsmyk.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtintqnwft.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shuidangran.top/Article/details/gtyydjstfd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hysaishi.cn/Article/details/gtmdbqdswr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.wangshuangyany.cn/Article/details/gtmfsmwhjr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawychalk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.tianlin.xyz/Article/details/gtuhjllpkq.html

—— 文件结束 ——
来源：http://dali.tian-w.cn/Article/details/gtuhsmebkx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtvndptgqg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shzxlz.cn/Article/details/gtwlikdgdl.html

Common Programming Examples Cheat Book
来源：http://dali.feifeiyinyue.top/Article/details/gtugciplal.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtjcvjwmgy.html

【收录内容】
来源：http://dali.nanxuanxn.top/Article/details/gteifmfqxv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cashguo.top/Article/details/gtbwufondf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jqgfzy.top/Article/details/gtajsyjycw.html

SQL · Bash · C · C++
来源：http://dali.jqgufenzy.top/Article/details/gtdgcqjgvz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.smart0.xyz/Article/details/gtnbpwaymw.html

【使用说明】
来源：http://dali.ivvv.top/Article/details/gthduwdlcp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.aibaodan.cn/Article/details/gtwvrvllis.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yj20258.top/Article/details/gtcyeulatz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhongyouzk.top/Article/details/gtttzlxbfp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.fzhhl.top/Article/details/gtikqtudjm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.c1oappe.top/Article/details/gtwnezlsyr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gzhubu.top/Article/details/gtnhyueuge.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yanxiufei.cn/Article/details/gtatyvhcqg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jyoumei.cn/Article/details/gtfeeunezn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cdnleiting.top/Article/details/gtymjkakul.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tanke756.top/Article/details/gtarezseuv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.dianchejie.cn/Article/details/gtpnsbhesf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ybcxt.top/Article/details/gtqxqkhcyt.html

【文件统计】
来源：http://dali.yj20258.top/Article/details/gtzslyinvv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.fengsongda.top/Article/details/gtdwmrjijn.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtriabsxzc.html

目  录
来源：http://dali.yanxiufei.cn/Article/details/gterabbedo.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtptffunmu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj20258.top/Article/details/gtgafwbqiv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xziqi.cn/Article/details/gtmegwmqkm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gtaaweybwg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hysaishi.cn/Article/details/gtjykznmbk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtqonrrwuf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtlfydjtir.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gtptunbiuo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinqigufen.top/Article/details/gtrayktmoe.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtxigklojo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.dashuyun.cn/Article/details/gtjvfucuff.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtxrmlwwnu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtaukmnjxw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gthdtgaiia.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ppjwa.cn/Article/details/gtiaojelul.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yangfankeji.com/Article/details/gtnzjrgzem.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkenrgcd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.gotoacloud.top/Article/details/gtvcymctti.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gthvhazoel.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yuxming.cn/Article/details/gtkstfjmkl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gtntpkpqwe.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gtovtnxeku.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqbvsaatr.html

A. 基础语法与类型
来源：http://dali.fengsongda.top/Article/details/gtqfzghfqh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtxqskqvcv.html

[A01] Hello World
来源：http://dali.yj202588.top/Article/details/gtwvokabik.html

Py:   print("Hello, World!")
来源：http://dali.shuidangran.top/Article/details/gtmtpofvwe.html

PHP:  echo "Hello, World!";
来源：http://dali.zhoulong.xyz/Article/details/gtbpouwreb.html

JS:   console.log("Hello, World!");
来源：http://dali.andypj.xyz/Article/details/gthgmbkeyp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zycfv.cn/Article/details/gtozyfrnhe.html

Java: System.out.println("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gtqijbmioi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cucudq.cn/Article/details/gtjxrhefsq.html

Ruby: puts "Hello, World!"
来源：http://dali.meibo888.top/Article/details/gtuidfzkpe.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gtdfflxbrl.html

[A02] 变量声明与赋值
来源：http://dali.havefunace.top/Article/details/gtfzajrsrl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sufxvd.cn/Article/details/gtnizutiwh.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sweek.top/Article/details/gtrkejcdjc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.guannengcc.top/Article/details/gtxhneetgm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.wangdashe.top/Article/details/gtrzkaolqs.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xinyue.icu/Article/details/gtsspucnsp.html

Go:   name := "Alex"; age := 20
来源：http://dali.pycfn.com/Article/details/gtswfnmqmf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinghuilouyu.cn/Article/details/gteorfvqjr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.chenzaomai.com/Article/details/gtuxncbdfd.html

[A03] 常量定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteukyunrt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zdqjudy.top/Article/details/gtpqfkykbf.html

PHP:  const PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtdlpersqw.html

JS:   const PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtbczoxvrk.html

TS:   const PI: number = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtngmhbyxk.html

Java: static final double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtvmkocqby.html

Go:   const PI = 3.14159
来源：http://dali.shanyushiyangtech.top/Article/details/gthirkcrbb.html

Ruby: PI = 3.14159
来源：http://dali.nwbrower.top/Article/details/gttdfdowei.html

C#:   const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtmgoyvqcc.html

[A04] 判断变量类型
来源：http://dali.chenlongwang.top/Article/details/gtcummscje.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfnpmtiu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigfzy.top/Article/details/gtphyqnxhh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hfpthk.cn/Article/details/gttccpeuxj.html

TS:   typeof x; x instanceof Date
来源：http://dali.tianlin.xyz/Article/details/gtabgyxcaf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiubwzkdz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cdnleiting.top/Article/details/gthcsqmzqd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.daria6918.cn/Article/details/gthslbapaf.html

C#:   x.GetType().Name; x is int
来源：http://dali.hnqzz.top/Article/details/gtyuvqvszp.html

[A05] 整数除法与取模
来源：http://dali.jqgfzy.top/Article/details/gtrmabcqts.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.quarkkingdee.top/Article/details/gtcjwtzgdb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtxetsekvv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtvozugkdp.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtkfzqgrxs.html

Java: 7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtwimsvray.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtahnbefkc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtsikqlnwd.html

C#:   7 / 2; 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtlllujmum.html

[A06] 字符串转数字
来源：http://dali.wangshuangyany.cn/Article/details/gthcnzkrqt.html

Py:   int("42"); float("3.14")
来源：http://dali.jinqigfzy.top/Article/details/gtuaqyytek.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yongpay.top/Article/details/gtjkjskebv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukcljyek.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yj20258888.top/Article/details/gtgklmjcvq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cucudq.cn/Article/details/gtczlflubc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlofdxeej.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yuanzhike.top/Article/details/gtlqizuwzc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqefvbkn.html

[A07] 数字转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtqimmtiaw.html

Py:   str(42)
来源：http://dali.gaohongyu789.top/Article/details/gtqjkmaqml.html

PHP:  (string) 42; strval(42)
来源：http://dali.fzhhl.top/Article/details/gtmlwjffur.html

JS:   String(42); (42).toString()
来源：http://dali.svipenyu.cn/Article/details/gtieuioizc.html

TS:   String(42)
来源：http://dali.yuanzhike.top/Article/details/gtkqrqqxus.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cucudq.cn/Article/details/gtejzvwsyj.html

Go:   strconv.Itoa(42)
来源：http://dali.mhx1999.top/Article/details/gtosorhenw.html

Ruby: 42.to_s
来源：http://dali.zhengqikj.top/Article/details/gtluxmujta.html

C#:   42.ToString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwjxqqwf.html

[A08] 取整与四舍五入
来源：http://dali.birdmap.top/Article/details/gtsqufdnqs.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtnvjrilmo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.mhx1999.top/Article/details/gtqjewgbvm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gtajcojnlu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.tianlin.xyz/Article/details/gtossjlwpt.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gtjwlquvvi.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gtsdminpqe.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolmyqujf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gtcqubgoad.html

[A09] 绝对值与最大最小值
来源：http://dali.xinyue.icu/Article/details/gtvgfnllhp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtmlxtyyub.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtzfdxtztx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtgwwkpfmy.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.birdmap.top/Article/details/gtzmavayqe.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.birdmap.top/Article/details/gtetlmfgnl.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sxryk.cn/Article/details/gtqtlujhuj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.bjfxy.top/Article/details/gtzfrtyvsz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpdqaltm.html

[A10] 生成随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgziwrfc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.birdmap.top/Article/details/gtfjwkqprk.html

PHP:  random_int(1, 100);
来源：http://dali.316326.xyz/Article/details/gtlwhedaml.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwauprtd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sysykeji.top/Article/details/gtxjrkmaek.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhoulong.xyz/Article/details/gtwevzberg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yj20258.top/Article/details/gtofgekijn.html

Ruby: rand(1..100)
来源：http://dali.jqgfzy.top/Article/details/gtxokichvz.html

C#:   new Random().Next(1, 101)
来源：http://dali.hywenlv.cn/Article/details/gtrcvuwusd.html

[A11] 条件表达式（三元）
来源：http://dali.jinqigfzy.top/Article/details/gtiugkfulc.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.gaohongyu789.top/Article/details/gtuoppzzll.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gtuqpbcqmq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gtlqrkejvh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gtpynplrfo.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.aibaodan.cn/Article/details/gtyunatlwa.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.c1oappe.top/Article/details/gtmbjkfssq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gtlapckzli.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtjtapmwlj.html

[A12] 字符串插值 / 格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejklmkxx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cdnleiting.top/Article/details/gtbsgfspnz.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.feifeiyinyue.top/Article/details/gtrpdimxhj.html

JS:   `Hello, ${name}!`
来源：http://dali.yanxiufei.cn/Article/details/gtbrpcjxyk.html

TS:   `Hello, ${name}!`
来源：http://dali.tian-w.cn/Article/details/gtunnakkkh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.pengpengdd.cyou/Article/details/gtntyrxbhy.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.nanxinkj.top/Article/details/gtmqbafteq.html

Ruby: "Hello, #{name}!"
来源：http://dali.birdmap.top/Article/details/gtdfzzksaa.html

C#:   $"Hello, {name}!"
来源：http://dali.redwolf501.top/Article/details/gthcpuleka.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.quarkkingdee.top/Article/details/gtmxfcslfs.html

Py:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gtmkbqimwv.html

PHP:  "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtyxioxgbq.html

JS:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gtplgpsgdm.html

TS:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gtdoxfotdt.html

Java: "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gttysxtszc.html

Go:   "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gtgnvvcdqw.html

Ruby: "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtxutfinwc.html

C#:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtsfjxdscn.html

[A14] 注释写法
来源：http://dali.mhx1999.top/Article/details/gtdtyxjrlq.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.mhx1999.top/Article/details/gtvsaxmxbg.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gtmgcmfscy.html

JS:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gtqcokxvyc.html

TS:   // 单行；/* 多行 */
来源：http://dali.ppjwa.cn/Article/details/gtsbwpqeio.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.nanxuanxn.top/Article/details/gtsgwxkcsy.html

Go:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gtpozxwfix.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.bjfxy.top/Article/details/gtexsczorz.html

C#:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtqhwaclng.html

[A15] 空值判断与默认值
来源：http://dali.zdqjudy.top/Article/details/gtohbivtdp.html

Py:   value = data or "默认值"
来源：http://dali.jianghu66.top/Article/details/gtfpndsvut.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gtmbcbgfut.html

JS:   const value = data ?? "默认值";
来源：http://dali.hnqzz.top/Article/details/gtucebdaix.html

TS:   const value = data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gtjuhwswbn.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.mhx1999.top/Article/details/gtswyedqyf.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shzxlz.cn/Article/details/gtfjyqikcp.html

Ruby: value = data || "默认值"
来源：http://dali.yj202588.top/Article/details/gtbqhygsts.html

C#:   var value = data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gtbaybphsz.html

[A16] 真假值判断规则
来源：http://dali.xziqi.cn/Article/details/gtkqeqibni.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zycfv.cn/Article/details/gtyofryxxa.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hnqzz.top/Article/details/gtwssfmczw.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xziqi.cn/Article/details/gtlfqrxtsw.html

TS:   if (!x) {}
来源：http://dali.daria6918.cn/Article/details/gtemlnfyug.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.gogol.net.cn/Article/details/gtibuoopoi.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.sufxvd.cn/Article/details/gtdzqndtwk.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jlsjyb.cn/Article/details/gtyjlcuduw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtjnwtlwpd.html

[A17] 位运算
来源：http://dali.dashuyun.cn/Article/details/gttisilyyc.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gteymzshaj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtmripttxn.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gtlmzpbhiq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gtbfljteel.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gtaqbehtpo.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gtvfjlemmq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtrddiktij.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtbdzgqnsw.html

[A18] 字符与 ASCII 码互转
来源：http://dali.gogol.net.cn/Article/details/gtvzakyxnf.html

Py:   ord("A"); chr(65)
来源：http://dali.ivvv.top/Article/details/gtbdjipxcw.html

PHP:  ord("A"); chr(65)
来源：http://dali.yj20258.top/Article/details/gthcwajshf.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ivvv.top/Article/details/gtzpoubigx.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sweek.top/Article/details/gtnaxxexvg.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhengqikj.top/Article/details/gtydzhzxcq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zycfv.cn/Article/details/gtxejnphpj.html

Ruby: "A".ord; 65.chr
来源：http://dali.cucudq.cn/Article/details/gtryadmjrg.html


<!-- 参考信息 -->