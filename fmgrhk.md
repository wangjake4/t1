代发 wailian999

[U103] JS：定时器
来源：http://dali.sxryk.cn/Article/details/gtnvexgvfe.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.wangshuangyany.cn/Article/details/gtryromtzj.html

[U104] JS：防抖
来源：http://dali.hnqzz.top/Article/details/gtfieylyyw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtfbvkjmnm.html

[U105] JS：节流
来源：http://dali.mhx1999.top/Article/details/gtrtofvode.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hysaishi.cn/Article/details/gtwfgjjbng.html

[U106] JS：日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcookppxj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gaohongyu789.top/Article/details/gtnivuevsh.html

[U107] JS：数字千分位
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwaeueid.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj20258.top/Article/details/gtrukommsg.html

[U108] JS：随机整数
来源：http://dali.aibaodan.cn/Article/details/gtmuroizqz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yj202588.top/Article/details/gtyxiduvpk.html

[U109] JS：数组分组
来源：http://dali.chenzaomai.com/Article/details/gtjdlansxf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hysaishi.cn/Article/details/gteqwyhxrq.html

[U110] JS：数组分块
来源：http://dali.nwbrower.top/Article/details/gtvxhzzjqo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shangyingyoupin.top/Article/details/gtlcmadpii.html

[U111] JS：对象转 Map
来源：http://dali.ppjwa.cn/Article/details/gtwhhqdysm.html

new Map(Object.entries(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gtcmzsxjhq.html

[U112] JS：字符串补位
来源：http://dali.hammf.cn/Article/details/gtyjtposal.html

"7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytemoxwf.html

[U113] JS：正则替换全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtappezgka.html

s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtcvkeuymo.html

[U114] JS：JSON 深比较
来源：http://dali.xylfe.cn/Article/details/gtqpkgjosc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gtnrytcayn.html

[U115] JS：生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gtmgkqoxai.html

crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtnixzdfkk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.fengsongda.top/Article/details/gtqoquqcch.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtccieopgf.html

[U117] JS：单元测试
来源：http://dali.guannengcc.top/Article/details/gthhthveci.html

npm i -D vitest;  npx vitest
来源：http://dali.ydzc1.top/Article/details/gtzacmxpsn.html

[U118] JS：开发服务器
来源：http://dali.xziqi.cn/Article/details/gtwvvvznix.html

npm i -D vite;  npx vite
来源：http://dali.xziqi.cn/Article/details/gtmptqqskc.html

[U119] JS：生产构建
来源：http://dali.gaohongyu789.top/Article/details/gtybxqgxiu.html

npx vite build
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzihswbv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shuidangran.top/Article/details/gttkdfcrvd.html

import.meta.env.VITE_API_URL
来源：http://dali.zdqjudy.top/Article/details/gtvyyqswaz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcaynhqcx.html

统计汇总
来源：http://dali.jianghu66.top/Article/details/gtevrdifkj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjoienrxt.html

按语言统计（条）：
来源：http://dali.sxryk.cn/Article/details/gtzckufmiy.html

Python ......... 252
来源：http://dali.zhoulong.xyz/Article/details/gtvpijagii.html

PHP ............ 252
来源：http://dali.aibaodan.cn/Article/details/gtsekwavaz.html

JavaScript ..... 252
来源：http://dali.xuanzx.com/Article/details/gtflrhbdhz.html

TypeScript ..... 212
来源：http://dali.0kj1m.cn/Article/details/gtmoaakafa.html

Java ........... 212
来源：http://dali.zhixingplan.top/Article/details/gtlimrpund.html

Go ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbsbylod.html

Ruby ........... 212
来源：http://dali.sxryk.cn/Article/details/gttjkuerjc.html

C# ............. 212
来源：http://dali.jyoumei.cn/Article/details/gtgnqywtim.html

C .............. 30
来源：http://dali.gaohongyu789.top/Article/details/gtpryagtcr.html

C++ ............ 30
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrkvltbm.html

SQL ............ 90
来源：http://dali.shzxlz.cn/Article/details/gtyyftajhb.html

Bash ........... 80
来源：http://dali.andypj.xyz/Article/details/gtdiiqirxh.html

Kotlin ......... 15
来源：http://dali.yj202588.top/Article/details/gtapxhcocl.html

Swift .......... 15
来源：http://dali.zhoulong.xyz/Article/details/gtaipfqryb.html

Lua ............ 10
来源：http://dali.cashguo.top/Article/details/gtrfiixseg.html

Perl ........... 10
来源：http://dali.chenzaomai.com/Article/details/gtpieaebmg.html

Scala .......... 10
来源：http://dali.wangshuangyany.cn/Article/details/gtggrueffv.html

------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzqoeulq.html

合计 ........... 2106 条
来源：http://dali.jianghu66.top/Article/details/gttyrglktu.html

按章节统计：
来源：http://dali.cucudq.cn/Article/details/gtpennuvyv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sufxvd.cn/Article/details/gtsuwidswx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtkzxrjzjf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gtvaozryfp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zdqjudy.top/Article/details/gtkypdducf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.havefunace.top/Article/details/gtdqcdkafg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.vqdsnc.cn/Article/details/gtbvekjwue.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gtzgdjumte.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ybcxt.top/Article/details/gtpbhelgys.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gthphdwznz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.mhx1999.top/Article/details/gtfkvaannd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtqhlclpoo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtlmqvlsfh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtabhknfhm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.fzhhl.top/Article/details/gtqranjnaw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.bjfxy.top/Article/details/gtgnbjjzyx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtrjajapoy.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gtpdhrditc.html

R Bash 专题                             80
来源：http://dali.xinyue.icu/Article/details/gtvstcswzp.html

S C / C++ 专题                          60
来源：http://dali.cdnleiting.top/Article/details/gtnsyqnuch.html

T 其他语言补充                          60
来源：http://dali.shanyushiyangtech.top/Article/details/gtnluxyupf.html

U 高频实用片段                         120
来源：http://dali.wangshuangyany.cn/Article/details/gtpzqfxnfc.html

------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtvaqfwqdi.html

合计                                  2106 条
来源：http://dali.gaohongyu789.top/Article/details/gtqvrqxbth.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtownjaiyu.html

使用提醒
来源：http://dali.wangshuangyany.cn/Article/details/gtpxenbshy.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gttmalxjbi.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj202588.top/Article/details/gtlsxazqwn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.daxiang520.top/Article/details/gtdrhxdyxp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.aizwys.cn/Article/details/gtcwdayfzi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hfpthk.cn/Article/details/gtqmooyuor.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shanyushiyangtech.top/Article/details/gtobrekkhn.html

—— 文件结束 ——
来源：http://dali.gotoacloud.top/Article/details/gtmasbzlgp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtmcuelsly.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.aizwys.cn/Article/details/gtymdzxwjf.html

Common Programming Examples Cheat Book
来源：http://dali.bjfxy.top/Article/details/gtmmjqhill.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkkfrlbtq.html

【收录内容】
来源：http://dali.chenlongwang.top/Article/details/gthyrcmypl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yj202588.top/Article/details/gtpgmonewr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpcaccjq.html

SQL · Bash · C · C++
来源：http://dali.zhixingplan.top/Article/details/gtqaynrkvp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yuxming.cn/Article/details/gtmagqyalp.html

【使用说明】
来源：http://dali.jinqigfzy.top/Article/details/gtuijolzet.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ybcxt.top/Article/details/gtnnylcshk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xuetiantiany.cn/Article/details/gtbitvbhhm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.guowangkeji.top/Article/details/gtyqaebcwu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ydzc1.top/Article/details/gtmjkhuesp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.daxiang520.top/Article/details/gtwojzcasr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sufxvd.cn/Article/details/gtqrsftqts.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gogol.net.cn/Article/details/gtylsrflwp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jiagoushi.top/Article/details/gtiwggphtc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjrmdiyw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gtbzrbmkeb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.chenlongwang.top/Article/details/gtvsqxhgmo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.sweek.top/Article/details/gtdtnqkhfe.html

【文件统计】
来源：http://dali.yuxming.cn/Article/details/gtrwirqmkm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shuidangran.top/Article/details/gtciwlrosb.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gttudsldbo.html

目  录
来源：http://dali.birdmap.top/Article/details/gtzlhsrpgh.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gtzaftqupc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shuidangran.top/Article/details/gtngvtgpmx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hnxiangtu.top/Article/details/gtnnmjklnh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtjkxiqccz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj202588.top/Article/details/gtxahbjdwr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shuidangran.top/Article/details/gtsrojiint.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jiagoushi.top/Article/details/gtxwoxntlh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jiagoushi.top/Article/details/gtjywqixmn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gtkmiznjvq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gtwdxgrhxi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.aizwys.cn/Article/details/gtpjpdxmri.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtlchjxswz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gtdujtyksj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtrsssobei.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.haohaochexian.top/Article/details/gtrssldhbv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hnqzz.top/Article/details/gtksxrmjhf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gtdwjztsmj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenjidiqi.icu/Article/details/gthjvhqfww.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjlrxtyf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmljzhffn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gtvtmalrck.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ppjwa.cn/Article/details/gttfddxmpx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrxebuiov.html

A. 基础语法与类型
来源：http://dali.guannengcc.top/Article/details/gtcjwalxgp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtwfdwsolb.html

[A01] Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtmltqgayt.html

Py:   print("Hello, World!")
来源：http://dali.tianlin.xyz/Article/details/gtebsaskmu.html

PHP:  echo "Hello, World!";
来源：http://dali.xuetiantiany.cn/Article/details/gthilswekz.html

JS:   console.log("Hello, World!");
来源：http://dali.jqgufenzy.top/Article/details/gtnbdeguws.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hywenlv.cn/Article/details/gtkhyjbkzt.html

Java: System.out.println("Hello, World!");
来源：http://dali.xuetiantiany.cn/Article/details/gtatwiisae.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xziqi.cn/Article/details/gtgxngepvg.html

Ruby: puts "Hello, World!"
来源：http://dali.shzxlz.cn/Article/details/gthojtrtqy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gtrcqfbfyg.html

[A02] 变量声明与赋值
来源：http://dali.xuetiantiany.cn/Article/details/gtddgfutcr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xinyue.icu/Article/details/gtribxfxdd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yongpay.top/Article/details/gtzubuywpm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gtlerdawfm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.wangdashe.top/Article/details/gtrmzndumk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nwbrower.top/Article/details/gtecyxmlfi.html

Go:   name := "Alex"; age := 20
来源：http://dali.shuidangran.top/Article/details/gtjdyuyelc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nwbrower.top/Article/details/gtqwezacuc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.fengsongda.top/Article/details/gtovqrkaue.html

[A03] 常量定义
来源：http://dali.tanke756.top/Article/details/gthcbpwzne.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jianghu66.top/Article/details/gtqtrcrrex.html

PHP:  const PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtvfbxulqu.html

JS:   const PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtnojkdzbn.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtigxuydkq.html

Java: static final double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtgocbioco.html

Go:   const PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gtnivbhngk.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gttsubvifm.html

C#:   const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtemyftgvd.html

[A04] 判断变量类型
来源：http://dali.aibaodan.cn/Article/details/gtamutxwlz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.kuanghao11.cn/Article/details/gtclqyobox.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jyoumei.cn/Article/details/gtwibxyzhg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlaqqhggt.html

TS:   typeof x; x instanceof Date
来源：http://dali.jqgfzy.top/Article/details/gtmkifhtxx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.quarkkingdee.top/Article/details/gtktdxzkot.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yj20258.top/Article/details/gtgafyxwsa.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.dashuyun.cn/Article/details/gtsyxvxbhd.html

C#:   x.GetType().Name; x is int
来源：http://dali.gogol.net.cn/Article/details/gtjdjqssng.html

[A05] 整数除法与取模
来源：http://dali.yvedp.cn/Article/details/gtcmpboqmu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.kuanghao11.cn/Article/details/gtcvgclzlt.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsnzvulv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.andypj.xyz/Article/details/gtsqfemxgb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtmdvcecvy.html

Java: 7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtaatixbox.html

Go:   7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtbnklxalq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtnvnjjfju.html

C#:   7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtfmtqbrrs.html

[A06] 字符串转数字
来源：http://dali.ydzc1.top/Article/details/gtitqyuemg.html

Py:   int("42"); float("3.14")
来源：http://dali.nwbrower.top/Article/details/gtudnigvjw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yongpay.top/Article/details/gtvdeorxda.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hnqzz.top/Article/details/gtlcgztmcy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hnxiangtu.top/Article/details/gtpedagjqe.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.haohaochexian.top/Article/details/gtsjklphhn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.andypj.xyz/Article/details/gtywskvqhx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ehwqpu.com/Article/details/gtxgxtlymx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinqigfzy.top/Article/details/gtcziqtswf.html

[A07] 数字转字符串
来源：http://dali.yuxming.cn/Article/details/gtdnuwlcmy.html

Py:   str(42)
来源：http://dali.316326.xyz/Article/details/gtxzfsndam.html

PHP:  (string) 42; strval(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjngrnwev.html

JS:   String(42); (42).toString()
来源：http://dali.zhixingplan.top/Article/details/gtlezzjutc.html

TS:   String(42)
来源：http://dali.dashuyun.cn/Article/details/gtuntfztox.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yuanzhike.top/Article/details/gtefbtrpom.html

Go:   strconv.Itoa(42)
来源：http://dali.jinqigfzy.top/Article/details/gtppsyftco.html

Ruby: 42.to_s
来源：http://dali.fengsongda.top/Article/details/gtypdjflcv.html

C#:   42.ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gtspxggzga.html

[A08] 取整与四舍五入
来源：http://dali.aibaodan.cn/Article/details/gttwyiezjy.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gtibpybrjs.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.9152youxi.cn/Article/details/gtqfpvdhex.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtdrmgmobj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ybcxt.top/Article/details/gtolhpcndp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtenjcyxsk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gtwrvjqfuz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jiagoushi.top/Article/details/gtqehspaoc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gtjhxlciln.html

[A09] 绝对值与最大最小值
来源：http://dali.jinqigufen.top/Article/details/gtjsnrlzsl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvclcocgx.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtskqviesb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtbtsfuicg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtoetioupb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtrgfltdbe.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.snrcjt.cn/Article/details/gtmlnasllu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cucudq.cn/Article/details/gteizrofhr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yuxming.cn/Article/details/gthrwwibsu.html

[A10] 生成随机数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqqznrfj.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hammf.cn/Article/details/gtubmogcum.html

PHP:  random_int(1, 100);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnieorxc.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fzhhl.top/Article/details/gtpdjswxfg.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xuanzx.com/Article/details/gtzverbroe.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yueranfly.top/Article/details/gthwplctrm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gzhubu.top/Article/details/gtucicczoe.html

Ruby: rand(1..100)
来源：http://dali.guannengcc.top/Article/details/gtutlkuoab.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkbqcclu.html

[A11] 条件表达式（三元）
来源：http://dali.xuanzx.com/Article/details/gtxkiatoov.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hywenlv.cn/Article/details/gthkhsutai.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gtklngfvzk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gttiphjfgu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtdzoqdqgk.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtxzirziad.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.meibo888.top/Article/details/gtkkbzupti.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gtxbyikumw.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gthvvfmync.html

[A12] 字符串插值 / 格式化
来源：http://dali.yongpay.top/Article/details/gtulyhujfq.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj20258.top/Article/details/gtqrvpgcpb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ybcxt.top/Article/details/gtzneagwea.html

JS:   `Hello, ${name}!`
来源：http://dali.mhx1999.top/Article/details/gtnfyggejq.html

TS:   `Hello, ${name}!`
来源：http://dali.gzhubu.top/Article/details/gtgmfaopbk.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jqgufenzy.top/Article/details/gtznvpnqll.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yongpay.top/Article/details/gtknewieoz.html

Ruby: "Hello, #{name}!"
来源：http://dali.jqgfzy.top/Article/details/gtiffdunfl.html

C#:   $"Hello, {name}!"
来源：http://dali.tanke756.top/Article/details/gtiouheule.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrsavalc.html

Py:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhuxgcjr.html

PHP:  "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gthtisvfyz.html

JS:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtitydxnsc.html

TS:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gtslxlbxhu.html

Java: "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtkxunqrsg.html

Go:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gtllpkrhgr.html

Ruby: "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkufywqnd.html

C#:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gtxdwyksvn.html

[A14] 注释写法
来源：http://dali.zdqjudy.top/Article/details/gtcgbtksra.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.guowangkeji.top/Article/details/gtxfwlblut.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gtxcfhsgdb.html

JS:   // 单行；/* 多行 */
来源：http://dali.guannengcc.top/Article/details/gtkzecfzkn.html

TS:   // 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gtvgpxcfuj.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hysaishi.cn/Article/details/gtbvyobhgg.html

Go:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gthyiflfuo.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.birdmap.top/Article/details/gtsygsqhhn.html

C#:   // 单行；/* 多行 */
来源：http://dali.andypj.xyz/Article/details/gtaccuwyfb.html

[A15] 空值判断与默认值
来源：http://dali.hammf.cn/Article/details/gtkppqiaec.html

Py:   value = data or "默认值"
来源：http://dali.yonumen.top/Article/details/gtodsityuv.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gttsfojxpn.html

JS:   const value = data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gtqcqhpbgh.html

TS:   const value = data ?? "默认值";
来源：http://dali.yj202588.top/Article/details/gthqyrxyfl.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shangyingyoupin.top/Article/details/gtxtoiteqn.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.xuanzx.com/Article/details/gtvzciuhqj.html

Ruby: value = data || "默认值"
来源：http://dali.jiagoushi.top/Article/details/gtylvojrlg.html

C#:   var value = data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycbcnksm.html

[A16] 真假值判断规则
来源：http://dali.gaohongyu789.top/Article/details/gthiybomgi.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hfpthk.cn/Article/details/gtbetksbqo.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.nanxinkj.top/Article/details/gtnhqaesrv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jinqigufen.top/Article/details/gtguxiodqe.html

TS:   if (!x) {}
来源：http://dali.jlsjyb.cn/Article/details/gtpviyaqko.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvhpnbewf.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hfpthk.cn/Article/details/gtimqnezgh.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gogol.net.cn/Article/details/gtksfglmau.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyagxxfst.html

[A17] 位运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngfeysrd.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gttwsdqlhb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtzxrxzcbo.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtvxxprxvv.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtclkvcgir.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtbucwbfem.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtxoyajdoz.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gtdwgdjwqr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtxcmozxgg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jiagoushi.top/Article/details/gtgfweracy.html

Py:   ord("A"); chr(65)
来源：http://dali.zhiwuduotai.top/Article/details/gtmbujvkmx.html

PHP:  ord("A"); chr(65)
来源：http://dali.yueranfly.top/Article/details/gtxwyehnsi.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.wangshuangyany.cn/Article/details/gtpfphtkzq.html


<!-- 参考信息 -->