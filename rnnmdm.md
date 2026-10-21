代发 wailian999

[U103] JS：定时器
来源：http://dali.tianlin.xyz/Article/details/gtuzljoaan.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hysaishi.cn/Article/details/gtztuuwnnt.html

[U104] JS：防抖
来源：http://dali.0kj1m.cn/Article/details/gtwclrdorp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnquriebb.html

[U105] JS：节流
来源：http://dali.daria6918.cn/Article/details/gtdnmtxbub.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cucudq.cn/Article/details/gtysovhdgl.html

[U106] JS：日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtpseqpalc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.snrcjt.cn/Article/details/gtqgjlbupv.html

[U107] JS：数字千分位
来源：http://dali.chenzaomai.com/Article/details/gtmowqcswd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gzhubu.top/Article/details/gtigwfdwpo.html

[U108] JS：随机整数
来源：http://dali.sufxvd.cn/Article/details/gtfmvhjxxk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jiagoushi.top/Article/details/gtivdekzji.html

[U109] JS：数组分组
来源：http://dali.yonumen.top/Article/details/gtxuepwlia.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hywenlv.cn/Article/details/gtxobcnoij.html

[U110] JS：数组分块
来源：http://dali.shzxlz.cn/Article/details/gtinzglxwg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.pycfn.com/Article/details/gthzwhhrjf.html

[U111] JS：对象转 Map
来源：http://dali.yueranfly.top/Article/details/gtpmizalal.html

new Map(Object.entries(obj))
来源：http://dali.svipenyu.cn/Article/details/gtnfrokffv.html

[U112] JS：字符串补位
来源：http://dali.316326.xyz/Article/details/gtnndznzgg.html

"7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtdpumipkn.html

[U113] JS：正则替换全部
来源：http://dali.cashguo.top/Article/details/gtklyxakws.html

s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtynialjpn.html

[U114] JS：JSON 深比较
来源：http://dali.andypj.xyz/Article/details/gtonrdkelx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtxewiwaqp.html

[U115] JS：生成 UUID
来源：http://dali.ybcxt.top/Article/details/gtcwrvpnip.html

crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gttsqlzsmf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhongyouzk.top/Article/details/gtoscipzuv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxvtypqmb.html

[U117] JS：单元测试
来源：http://dali.dianchejie.cn/Article/details/gtvrkhdjrr.html

npm i -D vitest;  npx vitest
来源：http://dali.svipenyu.cn/Article/details/gtxyrqjcjt.html

[U118] JS：开发服务器
来源：http://dali.chenlongwang.top/Article/details/gtunbcbswv.html

npm i -D vite;  npx vite
来源：http://dali.yongpay.top/Article/details/gtsbjveljw.html

[U119] JS：生产构建
来源：http://dali.ivvv.top/Article/details/gtxdsfkglu.html

npx vite build
来源：http://dali.nanxuanxn.top/Article/details/gtdyyyybdc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shanyushiyangtech.top/Article/details/gthyapzkpr.html

import.meta.env.VITE_API_URL
来源：http://dali.cdnleiting.top/Article/details/gtnaoxnmtl.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtrxswyqtk.html

统计汇总
来源：http://dali.hnqzz.top/Article/details/gteayntwim.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtovywfkko.html

按语言统计（条）：
来源：http://dali.zhengqikj.top/Article/details/gtwheddsye.html

Python ......... 252
来源：http://dali.iojbl.cn/Article/details/gtkfyoyryt.html

PHP ............ 252
来源：http://dali.wangdashe.top/Article/details/gtumdgbshe.html

JavaScript ..... 252
来源：http://dali.c1oappe.top/Article/details/gtwtahtuhh.html

TypeScript ..... 212
来源：http://dali.yonumen.top/Article/details/gtlbzftwtk.html

Java ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqjuzgrm.html

Go ............. 212
来源：http://dali.xziqi.cn/Article/details/gtoyntpilu.html

Ruby ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gtjcwnzxvt.html

C# ............. 212
来源：http://dali.sysykeji.top/Article/details/gtctunlsrw.html

C .............. 30
来源：http://dali.tanke756.top/Article/details/gtsjnarmua.html

C++ ............ 30
来源：http://dali.andypj.xyz/Article/details/gttgohnsvv.html

SQL ............ 90
来源：http://dali.hammf.cn/Article/details/gtfgmczjbn.html

Bash ........... 80
来源：http://dali.shanyushiyangtech.top/Article/details/gttvxsvqsw.html

Kotlin ......... 15
来源：http://dali.pycfn.com/Article/details/gtnjuxznbn.html

Swift .......... 15
来源：http://dali.hnxiangtu.top/Article/details/gtvsbxriqx.html

Lua ............ 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxffkiucq.html

Perl ........... 10
来源：http://dali.cucudq.cn/Article/details/gtotszlmuc.html

Scala .......... 10
来源：http://dali.dianchejie.cn/Article/details/gtdoyvrzcr.html

------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtuhrdkmvl.html

合计 ........... 2106 条
来源：http://dali.yanxiufei.cn/Article/details/gtyvflmxxg.html

按章节统计：
来源：http://dali.guowangkeji.top/Article/details/gtibntkdel.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangtech.top/Article/details/gtcchdwtjn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gtqwtkmslb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gtnzkxsqub.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gaohongyu789.top/Article/details/gtqssutolp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yueranfly.top/Article/details/gtltonjpig.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.pengpengdd.cyou/Article/details/gtxkvoqlye.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gtnumbbvsy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.316326.xyz/Article/details/gtamvybpyn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtnxqqapsv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.chenlongwang.top/Article/details/gtblfstanu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gtmsuyfmwy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadqozzar.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtytqhxljm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhoulong.xyz/Article/details/gtseflkjim.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenzaomai.com/Article/details/gtgxassmsv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtlbbnwios.html

Q SQL 专题                              90
来源：http://dali.quarkkingdee.top/Article/details/gtaylkgrrn.html

R Bash 专题                             80
来源：http://dali.feifeiyinyue.top/Article/details/gtxhvkyugh.html

S C / C++ 专题                          60
来源：http://dali.gaohongyu789.top/Article/details/gtvmfizhjv.html

T 其他语言补充                          60
来源：http://dali.aizwys.cn/Article/details/gtmnrytbim.html

U 高频实用片段                         120
来源：http://dali.hongshengwenyu.top/Article/details/gtgpysdlpe.html

------------------------------------
来源：http://dali.yongpay.top/Article/details/gtwcutsnoi.html

合计                                  2106 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyprpmkrb.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gtzabjjxuv.html

使用提醒
来源：http://dali.yj202588.top/Article/details/gtkiztdeth.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtfaycxunc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yueranfly.top/Article/details/gtjnqieciu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zycfv.cn/Article/details/gtbhxwltif.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.vqdsnc.cn/Article/details/gtemhjgqsq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhongyouzk.top/Article/details/gtnggfpsst.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkeycodi.html

—— 文件结束 ——
来源：http://dali.sweek.top/Article/details/gtgfjwjsfw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtpdxcrroy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cucudq.cn/Article/details/gtokhmcord.html

Common Programming Examples Cheat Book
来源：http://dali.yangfankeji.com/Article/details/gtfqmkkpab.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtjimrtoxd.html

【收录内容】
来源：http://dali.quarkkingdee.top/Article/details/gtndegttnp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuktvyjm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shuidangran.top/Article/details/gtrcryxypp.html

SQL · Bash · C · C++
来源：http://dali.hnqzz.top/Article/details/gtepdjkpgi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenjidiqi.icu/Article/details/gtlxxcxnzw.html

【使用说明】
来源：http://dali.tanke756.top/Article/details/gtgagoorto.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.aizwys.cn/Article/details/gtckqeoead.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.svipenyu.cn/Article/details/gtcgbqofcm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.bjfxy.top/Article/details/gtngjyulye.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gaohongyu789.top/Article/details/gtkbjepkjv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.svipenyu.cn/Article/details/gtpzgmkaqz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.pengpengdd.cyou/Article/details/gtjawsqivj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yonumen.top/Article/details/gthyhwqrpw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tanke756.top/Article/details/gtfcxzinul.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.quarkkingdee.top/Article/details/gtiwtutdxg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tian-w.cn/Article/details/gtvohqbfxq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.iojbl.cn/Article/details/gtuldfjsft.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.kuanghao11.cn/Article/details/gtxoaizqjz.html

【文件统计】
来源：http://dali.xylfe.cn/Article/details/gtuufuqngy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjiauare.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtgtqsihxs.html

目  录
来源：http://dali.tianlin.xyz/Article/details/gtbmmhzrkk.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtciiapmuj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.daxiang520.top/Article/details/gtczihyvev.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.gaohongyu789.top/Article/details/gtezbepmzx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yonumen.top/Article/details/gthuuiulyx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xuetiantiany.cn/Article/details/gttpvqgyac.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shzxlz.cn/Article/details/gthgwyrznl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gtuinrtzuy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gtnxpmudho.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yj20258888.top/Article/details/gtleuepazx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gtjwarijmo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gzhubu.top/Article/details/gtlviyqmgo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gtwrlfnwuw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtmxxzddyl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtqjykakei.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ivvv.top/Article/details/gtafksuxoi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.mhx1999.top/Article/details/gtflvjajdd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlkormoz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jqgufenzy.top/Article/details/gtumzbzvyf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cucudq.cn/Article/details/gtvdnpifyj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.bjfxy.top/Article/details/gtgbfhyeve.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtxenohlpk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gtajlddwgo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gttgzdgufh.html

A. 基础语法与类型
来源：http://dali.zhongyouzk.top/Article/details/gtmskuvhzi.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtqduqdgku.html

[A01] Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtqsuzwxxp.html

Py:   print("Hello, World!")
来源：http://dali.jlsjyb.cn/Article/details/gtlccqmvck.html

PHP:  echo "Hello, World!";
来源：http://dali.chenzaomai.com/Article/details/gtxkenhjss.html

JS:   console.log("Hello, World!");
来源：http://dali.cheryme.top/Article/details/gtuwjnvtjn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.316326.xyz/Article/details/gteugaonqt.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrsxdynx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yueranfly.top/Article/details/gteghfzykx.html

Ruby: puts "Hello, World!"
来源：http://dali.chenlongwang.top/Article/details/gtlsahocun.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.0kj1m.cn/Article/details/gtjkamqqgq.html

[A02] 变量声明与赋值
来源：http://dali.kuanghao11.cn/Article/details/gtibztzfdv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhiwuduotai.top/Article/details/gtncpwgacu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinqigufen.top/Article/details/gtxxurrcnd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.vqdsnc.cn/Article/details/gtsuzfqotx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yangfankeji.com/Article/details/gtsnuavpgz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.tanke756.top/Article/details/gtsaamcbog.html

Go:   name := "Alex"; age := 20
来源：http://dali.guowangkeji.top/Article/details/gtveuoqgxv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hammf.cn/Article/details/gtweeqisam.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ydzc1.top/Article/details/gtapkdgxcv.html

[A03] 常量定义
来源：http://dali.yj202588.top/Article/details/gtpwjksjej.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.bjfxy.top/Article/details/gtkkjaghrh.html

PHP:  const PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtpwssxqst.html

JS:   const PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtekjitxqv.html

TS:   const PI: number = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtiagpfxdx.html

Java: static final double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtllrdgzgv.html

Go:   const PI = 3.14159
来源：http://dali.shangyingyoupin.top/Article/details/gtpzopbwxn.html

Ruby: PI = 3.14159
来源：http://dali.nanxuanxn.top/Article/details/gtibkpsulm.html

C#:   const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtvpyltcrv.html

[A04] 判断变量类型
来源：http://dali.chenzaomai.com/Article/details/gtaeevncjz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhoulong.xyz/Article/details/gttyamvcvb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nwbrower.top/Article/details/gtxoqaddcx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhixingplan.top/Article/details/gtsipoyjxf.html

TS:   typeof x; x instanceof Date
来源：http://dali.andypj.xyz/Article/details/gtfvuxrrpf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.aizwys.cn/Article/details/gtanmgkvdk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xinyue.icu/Article/details/gtkmfxkyzi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwsxivdp.html

C#:   x.GetType().Name; x is int
来源：http://dali.shzxlz.cn/Article/details/gtupqifoki.html

[A05] 整数除法与取模
来源：http://dali.yueranfly.top/Article/details/gtblozbjjf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ehwqpu.com/Article/details/gthwrhwvpx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gttdtyefdy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtlkpfkxwg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtmyovdplv.html

Java: 7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gtbdgypghb.html

Go:   7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtsrsmenfc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtukwoccju.html

C#:   7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gtemumvxwk.html

[A06] 字符串转数字
来源：http://dali.jlsjyb.cn/Article/details/gtwvjeibwb.html

Py:   int("42"); float("3.14")
来源：http://dali.yj20258.top/Article/details/gtlwrxozqf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yonumen.top/Article/details/gtfeinanxk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xylfe.cn/Article/details/gtdoqppzns.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.wangdashe.top/Article/details/gtwlghuqpg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.meibo888.top/Article/details/gtzgllcemr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gotoacloud.top/Article/details/gtjhmlbaey.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jlsjyb.cn/Article/details/gtcrlzhdxe.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.vqdsnc.cn/Article/details/gtkbkcvmkv.html

[A07] 数字转字符串
来源：http://dali.shuidangran.top/Article/details/gtaohybxhk.html

Py:   str(42)
来源：http://dali.fengsongda.top/Article/details/gtrrefcxjb.html

PHP:  (string) 42; strval(42)
来源：http://dali.jqgufenzy.top/Article/details/gtmzimritf.html

JS:   String(42); (42).toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gteyoxnbas.html

TS:   String(42)
来源：http://dali.c1oappe.top/Article/details/gtotupgwva.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gotoacloud.top/Article/details/gtywxsnuqe.html

Go:   strconv.Itoa(42)
来源：http://dali.zhengqikj.top/Article/details/gtxcfjkonx.html

Ruby: 42.to_s
来源：http://dali.jiagoushi.top/Article/details/gtxdyjaani.html

C#:   42.ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofzhswik.html

[A08] 取整与四舍五入
来源：http://dali.yangfankeji.com/Article/details/gteaadfivv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtkgwzgfeg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cdnleiting.top/Article/details/gtyhjmjoif.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gtahajqywr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.fengsongda.top/Article/details/gtgpqwpggw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gtyrlnahcv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gtwxzppsvw.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jlsjyb.cn/Article/details/gtymzopgxl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdupyolyb.html

[A09] 绝对值与最大最小值
来源：http://dali.guannengcc.top/Article/details/gtjmwdtswg.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtmdakeabt.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtecekkqem.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtarougtte.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtscjzcjeq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtegwwvkgk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jlsjyb.cn/Article/details/gtrfzohayb.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.c1oappe.top/Article/details/gtxcpnagsi.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtwnbtxept.html

[A10] 生成随机数
来源：http://dali.fzhhl.top/Article/details/gtxllaqdgv.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbskjrzlf.html

PHP:  random_int(1, 100);
来源：http://dali.yvedp.cn/Article/details/gtyzsrrkfr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.9152youxi.cn/Article/details/gtutzfijkg.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nanxinkj.top/Article/details/gtixireaww.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hysaishi.cn/Article/details/gtmazxqkdz.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xinyue.icu/Article/details/gtqkrngmfw.html

Ruby: rand(1..100)
来源：http://dali.xziqi.cn/Article/details/gttzkrxyfd.html

C#:   new Random().Next(1, 101)
来源：http://dali.sufxvd.cn/Article/details/gtyuiqlyly.html

[A11] 条件表达式（三元）
来源：http://dali.xziqi.cn/Article/details/gtqtwysite.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yonumen.top/Article/details/gtmflbzlcs.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gtujtuomak.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gtrupijppg.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gtxrhbsbzx.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtnrjopacv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xylfe.cn/Article/details/gtsxliheoo.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gtpvyylgni.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtpkchqpsx.html

[A12] 字符串插值 / 格式化
来源：http://dali.cucudq.cn/Article/details/gtatedpxrp.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvzjlzmu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.daria6918.cn/Article/details/gtevjvidsx.html

JS:   `Hello, ${name}!`
来源：http://dali.sweek.top/Article/details/gtmizspszg.html

TS:   `Hello, ${name}!`
来源：http://dali.zhiwuduotai.top/Article/details/gtmylpncyn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.bjfxy.top/Article/details/gtdkysqxqh.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.dianchejie.cn/Article/details/gtmwzmsvwg.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtzcpgdw.html

C#:   $"Hello, {name}!"
来源：http://dali.jinqigufen.top/Article/details/gtdtfwihvg.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jinqigufen.top/Article/details/gtoyotrzvm.html

Py:   "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gtudlkdwam.html

PHP:  "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gttixcbmvd.html

JS:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtkhuvyeag.html

TS:   "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gtrjrpbtia.html

Java: "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gtdzdkupnt.html

Go:   "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gtxxzimqro.html

Ruby: "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhzlzdzt.html

C#:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gtcgrhiaiy.html

[A14] 注释写法
来源：http://dali.hongshengwenyu.top/Article/details/gtnvhylpfc.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yueranfly.top/Article/details/gtdfrbdjba.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yangfankeji.com/Article/details/gtqgmjmmrx.html

JS:   // 单行；/* 多行 */
来源：http://dali.dianchejie.cn/Article/details/gtfajhiifa.html

TS:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtgzqdfbsv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gzhubu.top/Article/details/gtbnqonxvh.html

Go:   // 单行；/* 多行 */
来源：http://dali.hywenlv.cn/Article/details/gtvbkqkmgg.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.sufxvd.cn/Article/details/gtggicjceg.html

C#:   // 单行；/* 多行 */
来源：http://dali.ehwqpu.com/Article/details/gtdavrzdzm.html

[A15] 空值判断与默认值
来源：http://dali.316326.xyz/Article/details/gtmwdihhzc.html

Py:   value = data or "默认值"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqyqlkuw.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.pycfn.com/Article/details/gtktzncwyz.html

JS:   const value = data ?? "默认值";
来源：http://dali.yonumen.top/Article/details/gtqfbsdfdf.html

TS:   const value = data ?? "默认值";
来源：http://dali.guannengcc.top/Article/details/gtjeweqyzv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.316326.xyz/Article/details/gtejwpgyxc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ivvv.top/Article/details/gtunzampzq.html

Ruby: value = data || "默认值"
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxclzgjg.html

C#:   var value = data ?? "默认值";
来源：http://dali.cashguo.top/Article/details/gtakprymch.html

[A16] 真假值判断规则
来源：http://dali.cheryme.top/Article/details/gtpanrsvay.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.sxryk.cn/Article/details/gtyqhdmnqx.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.tanke756.top/Article/details/gtqvwrlxam.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cqqwz.cn/Article/details/gtrwdmrdnc.html

TS:   if (!x) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzfrvnce.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.tanke756.top/Article/details/gtjaradmue.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ppjwa.cn/Article/details/gtdewselkg.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.smart0.xyz/Article/details/gtuemnrejq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xziqi.cn/Article/details/gtsjvrszye.html

[A17] 位运算
来源：http://dali.nanxuanxn.top/Article/details/gtxgzdabmo.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtqtkqvvri.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.316326.xyz/Article/details/gtzkfwmcwh.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysbpjggu.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtkzmwecyt.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gtkcruwizi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gtbqytxplj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gtypggtzay.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtwfwlsszk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yvedp.cn/Article/details/gtcirzdlku.html

Py:   ord("A"); chr(65)
来源：http://dali.hysaishi.cn/Article/details/gtyloflgjn.html

PHP:  ord("A"); chr(65)
来源：http://dali.c1oappe.top/Article/details/gtchadtgsk.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nanxinkj.top/Article/details/gtaiomivdq.html


<!-- 参考信息 -->