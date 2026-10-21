代发 wailian999

[U101] JS：classList 操作
来源：http://dali.cqqwz.cn/Article/details/gtkkebxxqm.html

el.classList.toggle("active")
来源：http://dali.xuanzx.com/Article/details/gtnfniswrg.html

[U102] JS：本地存储
来源：http://dali.yuxming.cn/Article/details/gtyrfjjjlm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhixingplan.top/Article/details/gtmpzjrspy.html

[U103] JS：定时器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjonmigs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjotxligz.html

[U104] JS：防抖
来源：http://dali.gotoacloud.top/Article/details/gtjtsixgef.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtvtbzaqda.html

[U105] JS：节流
来源：http://dali.daria6918.cn/Article/details/gtspbugexk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.wangdashe.top/Article/details/gtehvrijqf.html

[U106] JS：日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtnooqpmca.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvgjhczj.html

[U107] JS：数字千分位
来源：http://dali.chenlongwang.top/Article/details/gtkbkqzujt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtoelbiupb.html

[U108] JS：随机整数
来源：http://dali.guannengcc.top/Article/details/gtpfgtvidv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ybcxt.top/Article/details/gtczjonnwd.html

[U109] JS：数组分组
来源：http://dali.ivvv.top/Article/details/gteypeewgc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gtpdihqdyu.html

[U110] JS：数组分块
来源：http://dali.yvedp.cn/Article/details/gteopnikyj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cucudq.cn/Article/details/gtulcwwhhs.html

[U111] JS：对象转 Map
来源：http://dali.dianchejie.cn/Article/details/gtqdxncuaz.html

new Map(Object.entries(obj))
来源：http://dali.c1oappe.top/Article/details/gtpyqgtrzw.html

[U112] JS：字符串补位
来源：http://dali.gogol.net.cn/Article/details/gtyybidkzh.html

"7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtcnwuhvjb.html

[U113] JS：正则替换全部
来源：http://dali.pengpengdd.cyou/Article/details/gtkaydmpic.html

s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtgrwbutdt.html

[U114] JS：JSON 深比较
来源：http://dali.jlsjyb.cn/Article/details/gtdatlpmwl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gtcfslefpe.html

[U115] JS：生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gtsdpeomnn.html

crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtghrmkehy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hfpthk.cn/Article/details/gtzfowcaav.html

/** @param {string} name */ function f(name) {}
来源：http://dali.0kj1m.cn/Article/details/gtdxojounz.html

[U117] JS：单元测试
来源：http://dali.aibaodan.cn/Article/details/gtuyeqnhwl.html

npm i -D vitest;  npx vitest
来源：http://dali.yj202588.top/Article/details/gtwlmgisuc.html

[U118] JS：开发服务器
来源：http://dali.cheryme.top/Article/details/gtjjgzfsll.html

npm i -D vite;  npx vite
来源：http://dali.jyoumei.cn/Article/details/gteegpxmeu.html

[U119] JS：生产构建
来源：http://dali.tianlin.xyz/Article/details/gtdngzgqvo.html

npx vite build
来源：http://dali.guannengcc.top/Article/details/gttyxhmnuo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xylfe.cn/Article/details/gtbimnsinl.html

import.meta.env.VITE_API_URL
来源：http://dali.jiagoushi.top/Article/details/gteikylozx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtuatkwvvp.html

统计汇总
来源：http://dali.tanke756.top/Article/details/gttrfjtdqe.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxytpinkr.html

按语言统计（条）：
来源：http://dali.hnxiangtu.top/Article/details/gtdrsodvdn.html

Python ......... 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuqwrllc.html

PHP ............ 252
来源：http://dali.xylfe.cn/Article/details/gturalcalk.html

JavaScript ..... 252
来源：http://dali.yvedp.cn/Article/details/gtkpjdyjpc.html

TypeScript ..... 212
来源：http://dali.guannengcc.top/Article/details/gtroejahff.html

Java ........... 212
来源：http://dali.xuanzx.com/Article/details/gtsvftedhh.html

Go ............. 212
来源：http://dali.xylfe.cn/Article/details/gtbfmpdmht.html

Ruby ........... 212
来源：http://dali.zdqjudy.top/Article/details/gtoormpqrx.html

C# ............. 212
来源：http://dali.tian-w.cn/Article/details/gttyoewrkg.html

C .............. 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmfgtxjl.html

C++ ............ 30
来源：http://dali.hammf.cn/Article/details/gtmusescht.html

SQL ............ 90
来源：http://dali.guowangkeji.top/Article/details/gtwobhwseh.html

Bash ........... 80
来源：http://dali.sysykeji.top/Article/details/gtnuhottyn.html

Kotlin ......... 15
来源：http://dali.cdnleiting.top/Article/details/gtfkumyyko.html

Swift .......... 15
来源：http://dali.c1oappe.top/Article/details/gtgligqblo.html

Lua ............ 10
来源：http://dali.tian-w.cn/Article/details/gtkobnjgry.html

Perl ........... 10
来源：http://dali.chenzaomai.com/Article/details/gtoirjdrvr.html

Scala .......... 10
来源：http://dali.redwolf501.top/Article/details/gttduvqqrg.html

------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtpfnqojzc.html

合计 ........... 2106 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfnvfeii.html

按章节统计：
来源：http://dali.hysaishi.cn/Article/details/gtumodubrj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gtndxvwtjw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gtqtsuxiza.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.daria6918.cn/Article/details/gtgidqlqts.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sysykeji.top/Article/details/gthagolaej.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbsorqth.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhengqikj.top/Article/details/gtzhqkazfo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdfrawax.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gogol.net.cn/Article/details/gtjwpzckdw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtsplqxgqk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.guowangkeji.top/Article/details/gtlwwxajaw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtljpsgzzn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtlnezcgfi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtchieefpc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhetfphh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangdashe.top/Article/details/gtnaguernz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtmrgltrmf.html

Q SQL 专题                              90
来源：http://dali.gotoacloud.top/Article/details/gttpbbfjui.html

R Bash 专题                             80
来源：http://dali.sysykeji.top/Article/details/gtofsjgwls.html

S C / C++ 专题                          60
来源：http://dali.hfpthk.cn/Article/details/gtopwugruv.html

T 其他语言补充                          60
来源：http://dali.nanxinkj.top/Article/details/gtcsfpetiq.html

U 高频实用片段                         120
来源：http://dali.9152youxi.cn/Article/details/gtotqphxjr.html

------------------------------------
来源：http://dali.havefunace.top/Article/details/gtrddsmowz.html

合计                                  2106 条
来源：http://dali.yuanzhike.top/Article/details/gtfrcpijcw.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtclnxotze.html

使用提醒
来源：http://dali.jqgufenzy.top/Article/details/gtruppwsyg.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtpgjbttfw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenzaomai.com/Article/details/gtdlhwzhck.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.fengsongda.top/Article/details/gthrrxrrmd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuanzx.com/Article/details/gtfhskwxgc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cdnleiting.top/Article/details/gtsevzsqku.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.kuanghao11.cn/Article/details/gtqikigsln.html

—— 文件结束 ——
来源：http://dali.zycfv.cn/Article/details/gteibsuiut.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxykpjxlx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangdashe.top/Article/details/gtkbyexnie.html

Common Programming Examples Cheat Book
来源：http://dali.9152youxi.cn/Article/details/gtugzkyqob.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtciowoihw.html

【收录内容】
来源：http://dali.hywenlv.cn/Article/details/gtgdgmegbv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jqgfzy.top/Article/details/gtyofryfez.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gtsfckzqlj.html

SQL · Bash · C · C++
来源：http://dali.wangdashe.top/Article/details/gtuqrwjdgw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cheryme.top/Article/details/gtfzlcfxmk.html

【使用说明】
来源：http://dali.jlsjyb.cn/Article/details/gtbgobbfgt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.c1oappe.top/Article/details/gtdbdrpbez.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.svipenyu.cn/Article/details/gtdznyabia.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.pycfn.com/Article/details/gtqtwknuqt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cdnleiting.top/Article/details/gtnfupwvmw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jianghu66.top/Article/details/gtxgapusjs.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.wangdashe.top/Article/details/gtsqlytqxv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpducxofz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tianlin.xyz/Article/details/gtehoawwhw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jyoumei.cn/Article/details/gtiuomveje.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hnxiangtu.top/Article/details/gtwqccjpdl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonfkzkqa.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.tanke756.top/Article/details/gttdtciijt.html

【文件统计】
来源：http://dali.yanxiufei.cn/Article/details/gtzneveptn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.mhx1999.top/Article/details/gtdynotnpw.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtkepgimfs.html

目  录
来源：http://dali.sysykeji.top/Article/details/gtuuczbchz.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtjzeczztk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hywenlv.cn/Article/details/gtvttrpsrb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gtrgikdcwn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.dianchejie.cn/Article/details/gtyncudxfx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cashguo.top/Article/details/gtdlhuuupr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.mhx1999.top/Article/details/gtilmhcxyh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yvedp.cn/Article/details/gtwkydvdtc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ivvv.top/Article/details/gtdyyvwpsl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xuanzx.com/Article/details/gtritjcomu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gtqcyljjcz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yuxming.cn/Article/details/gtnrkozeto.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtbrzosoqs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gtupykevsf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtdgiegpvx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggrsbrvp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shuidangran.top/Article/details/gtuanqvlyz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gtwpmvfris.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yongpay.top/Article/details/gtnuykzyqo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ppjwa.cn/Article/details/gtgkugewrv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cheryme.top/Article/details/gtqzwwizgr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gtzbhykfiw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gtleqsxoyb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtetwkcptc.html

A. 基础语法与类型
来源：http://dali.jyoumei.cn/Article/details/gtbnyibrxf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbuebvtsp.html

[A01] Hello World
来源：http://dali.sufxvd.cn/Article/details/gtmpaqehzv.html

Py:   print("Hello, World!")
来源：http://dali.smart0.xyz/Article/details/gtubjytnzq.html

PHP:  echo "Hello, World!";
来源：http://dali.cheryme.top/Article/details/gtqutofgxe.html

JS:   console.log("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gtjfejjrie.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj20258.top/Article/details/gttycpnevx.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinqigfzy.top/Article/details/gtjoyrbhld.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gtuwizzrwl.html

Ruby: puts "Hello, World!"
来源：http://dali.mhx1999.top/Article/details/gtuaathklx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gtaenofkta.html

[A02] 变量声明与赋值
来源：http://dali.tanke756.top/Article/details/gttutonmmr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yonumen.top/Article/details/gtbpelsfue.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ppjwa.cn/Article/details/gtrhwspatp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.9152youxi.cn/Article/details/gthcjxtzxh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jiagoushi.top/Article/details/gtlkhovbrf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cashguo.top/Article/details/gtslwqkwnz.html

Go:   name := "Alex"; age := 20
来源：http://dali.daxiang520.top/Article/details/gtumvrjncg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jqgufenzy.top/Article/details/gtegyojiry.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtmojkjsbp.html

[A03] 常量定义
来源：http://dali.pycfn.com/Article/details/gtwumlvejf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.pycfn.com/Article/details/gttdjvagjr.html

PHP:  const PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtrfqpdqnl.html

JS:   const PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtwuqoxcaw.html

TS:   const PI: number = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtqmrfxpet.html

Java: static final double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtestikktc.html

Go:   const PI = 3.14159
来源：http://dali.hfpthk.cn/Article/details/gtfiqhfsfl.html

Ruby: PI = 3.14159
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhevrmqj.html

C#:   const double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtelkcqrko.html

[A04] 判断变量类型
来源：http://dali.zhongyouzk.top/Article/details/gtygymqiup.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cashguo.top/Article/details/gtpjxjwpoq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ivvv.top/Article/details/gtuftawzaq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ivvv.top/Article/details/gtcjqtdavn.html

TS:   typeof x; x instanceof Date
来源：http://dali.shanyushiyangkeji.top/Article/details/gtologmash.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.redwolf501.top/Article/details/gtkjokilmn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aizwys.cn/Article/details/gtolnfpnra.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sxryk.cn/Article/details/gtabtefndu.html

C#:   x.GetType().Name; x is int
来源：http://dali.mhx1999.top/Article/details/gtfofulfeg.html

[A05] 整数除法与取模
来源：http://dali.xinyue.icu/Article/details/gtlrmclhsa.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.c1oappe.top/Article/details/gtduscmpys.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtunzbkzjl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtgaflcmmm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pycfn.com/Article/details/gtwqpsbpmq.html

Java: 7 / 2; 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gtywggsmqr.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtjlarygjm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtsdwquwfs.html

C#:   7 / 2; 7 % 2
来源：http://dali.zycfv.cn/Article/details/gtremxirvp.html

[A06] 字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gthryfukjk.html

Py:   int("42"); float("3.14")
来源：http://dali.zhoulong.xyz/Article/details/gttboycoym.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.snrcjt.cn/Article/details/gtkxpejrok.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ivvv.top/Article/details/gtsuscyyic.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.daxiang520.top/Article/details/gtgkvnlihy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jlsjyb.cn/Article/details/gtaaubkppu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cdnleiting.top/Article/details/gtaxugmdkn.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xuanzx.com/Article/details/gtnejcwxoo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtddbobi.html

[A07] 数字转字符串
来源：http://dali.ppjwa.cn/Article/details/gtybwltslp.html

Py:   str(42)
来源：http://dali.andypj.xyz/Article/details/gtkzjogxus.html

PHP:  (string) 42; strval(42)
来源：http://dali.haohaochexian.top/Article/details/gtaiuphgmd.html

JS:   String(42); (42).toString()
来源：http://dali.bjfxy.top/Article/details/gttwcmnnsy.html

TS:   String(42)
来源：http://dali.fengsongda.top/Article/details/gtqandehtb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojeoqddq.html

Go:   strconv.Itoa(42)
来源：http://dali.zhengqikj.top/Article/details/gttetlnckx.html

Ruby: 42.to_s
来源：http://dali.sxryk.cn/Article/details/gtffiezlew.html

C#:   42.ToString()
来源：http://dali.ppjwa.cn/Article/details/gtgbfvmfbl.html

[A08] 取整与四舍五入
来源：http://dali.zhoulong.xyz/Article/details/gtxrhqratl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtpxqbznkh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ydzc1.top/Article/details/gtgzhqgeow.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gtvlktoepb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gogol.net.cn/Article/details/gtbzlvimqe.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.ydzc1.top/Article/details/gtftvtcbdj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gtkeytgwky.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yanxiufei.cn/Article/details/gtopeqzqgx.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.iojbl.cn/Article/details/gtpexbvnke.html

[A09] 绝对值与最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gtndzgfjxb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtgpsaedac.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtwpvsjigv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtcxcsehyy.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtdxutywfm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtvbsyuola.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdwnulem.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkjutlre.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtqvprgjit.html

[A10] 生成随机数
来源：http://dali.dashuyun.cn/Article/details/gtaonoryvg.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yvedp.cn/Article/details/gtobbvxomy.html

PHP:  random_int(1, 100);
来源：http://dali.aizwys.cn/Article/details/gttdqosirt.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.aizwys.cn/Article/details/gtolkqionv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ybcxt.top/Article/details/gtvvimlebe.html

Java: new Random().nextInt(100) + 1
来源：http://dali.tanke756.top/Article/details/gtiiqvwtnv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.sxryk.cn/Article/details/gtpiohubpa.html

Ruby: rand(1..100)
来源：http://dali.ehwqpu.com/Article/details/gtuzxditpe.html

C#:   new Random().Next(1, 101)
来源：http://dali.gaohongyu789.top/Article/details/gtrrootamu.html

[A11] 条件表达式（三元）
来源：http://dali.gzhubu.top/Article/details/gtsuapdaqu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.mhx1999.top/Article/details/gtrnodwold.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gtcdbjyqhh.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.tanke756.top/Article/details/gtrcbposnm.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.aibaodan.cn/Article/details/gtezztygje.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtjglgmjhf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.meibo888.top/Article/details/gtzgugstrt.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.aibaodan.cn/Article/details/gtzoccsydz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gthmgbyjvq.html

[A12] 字符串插值 / 格式化
来源：http://dali.birdmap.top/Article/details/gtlnqcbtht.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.iojbl.cn/Article/details/gtkhqvrfnp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.haohaochexian.top/Article/details/gtyjybkqay.html

JS:   `Hello, ${name}!`
来源：http://dali.xuetiantiany.cn/Article/details/gtqzuserwv.html

TS:   `Hello, ${name}!`
来源：http://dali.zhengqikj.top/Article/details/gtgsmsidpk.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhiwuduotai.top/Article/details/gtotvbddte.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoucgblst.html

Ruby: "Hello, #{name}!"
来源：http://dali.hywenlv.cn/Article/details/gtuzydyboz.html

C#:   $"Hello, {name}!"
来源：http://dali.hywenlv.cn/Article/details/gtfumlvbtc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jqgufenzy.top/Article/details/gthgdljutc.html

Py:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtybckykif.html

PHP:  "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtbdgjiate.html

JS:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gthndqewnc.html

TS:   "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtxbvzqpqf.html

Java: "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gtqpvticwt.html

Go:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gthvathtaj.html

Ruby: "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gtqqgfyglr.html

C#:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gtuluzocks.html

[A14] 注释写法
来源：http://dali.jianghu66.top/Article/details/gtjfdnssli.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jqgufenzy.top/Article/details/gtjlgjrsxy.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gtkawdmdaa.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gtziemnoeg.html

TS:   // 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gtoymhaofp.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.aizwys.cn/Article/details/gtyqtgpokr.html

Go:   // 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gttnihthoh.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hfpthk.cn/Article/details/gtgaelnyej.html

C#:   // 单行；/* 多行 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcubhfisd.html

[A15] 空值判断与默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxphvzayc.html

Py:   value = data or "默认值"
来源：http://dali.cashguo.top/Article/details/gtdrlqzieg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ivvv.top/Article/details/gtgckefbam.html

JS:   const value = data ?? "默认值";
来源：http://dali.vqdsnc.cn/Article/details/gteuvduwec.html

TS:   const value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtqzvwffhs.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.daria6918.cn/Article/details/gticzpytss.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.birdmap.top/Article/details/gtxfncdvrz.html

Ruby: value = data || "默认值"
来源：http://dali.iojbl.cn/Article/details/gthzzemllc.html

C#:   var value = data ?? "默认值";
来源：http://dali.dashuyun.cn/Article/details/gtureobeso.html

[A16] 真假值判断规则
来源：http://dali.shzxlz.cn/Article/details/gtjghpuebx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shzxlz.cn/Article/details/gtuvudsaec.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.316326.xyz/Article/details/gtasfkcjdq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yonumen.top/Article/details/gtbrlhknaz.html

TS:   if (!x) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqusglhoi.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.dianchejie.cn/Article/details/gtrthlmgba.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yongpay.top/Article/details/gtcpknpejv.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhongyouzk.top/Article/details/gtlkovvirg.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtfebxdbox.html

[A17] 位运算
来源：http://dali.yj202588.top/Article/details/gtrjhdtlei.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtefkmiqnj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtcrfvdaes.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gttszacwdd.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gtjcsxhbws.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gtyehpzrsn.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gttfdhmwqk.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtylkqhtyf.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gtqfvlfvxg.html


<!-- 参考信息 -->