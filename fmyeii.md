代发 wailian999

[U103] JS：定时器
来源：http://dali.sweek.top/Article/details/gthzvmtkmt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.316326.xyz/Article/details/gtlzpmjvfn.html

[U104] JS：防抖
来源：http://dali.svipenyu.cn/Article/details/gtgzgctyav.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtwlsmxzdn.html

[U105] JS：节流
来源：http://dali.nwbrower.top/Article/details/gtubdoprga.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.smart0.xyz/Article/details/gtyufuijkl.html

[U106] JS：日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtvqhfvhga.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gotoacloud.top/Article/details/gtekswxydv.html

[U107] JS：数字千分位
来源：http://dali.yuxming.cn/Article/details/gtvlaneawu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shuidangran.top/Article/details/gtcakgbosf.html

[U108] JS：随机整数
来源：http://dali.zdqjudy.top/Article/details/gtlfvzutjh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.snrcjt.cn/Article/details/gtlkmbbtsv.html

[U109] JS：数组分组
来源：http://dali.daxiang520.top/Article/details/gtxhlnsfgr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shuidangran.top/Article/details/gtfpwgkuwh.html

[U110] JS：数组分块
来源：http://dali.jqgfzy.top/Article/details/gtxqvyakoi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sweek.top/Article/details/gthvpaaytz.html

[U111] JS：对象转 Map
来源：http://dali.cqqwz.cn/Article/details/gtcwbcjhbu.html

new Map(Object.entries(obj))
来源：http://dali.aizwys.cn/Article/details/gtgxcslhbw.html

[U112] JS：字符串补位
来源：http://dali.wangshuangyany.cn/Article/details/gtohpuuhnu.html

"7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtpwehemag.html

[U113] JS：正则替换全部
来源：http://dali.yj202588.top/Article/details/gtocjartwa.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccutjyvm.html

[U114] JS：JSON 深比较
来源：http://dali.pengpengdd.cyou/Article/details/gtljpnonyo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gtncmkbrxg.html

[U115] JS：生成 UUID
来源：http://dali.316326.xyz/Article/details/gtpscttifi.html

crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtbdatmmlx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.feifeiyinyue.top/Article/details/gtpdfowisy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhongyouzk.top/Article/details/gtuvbhfaww.html

[U117] JS：单元测试
来源：http://dali.yvedp.cn/Article/details/gtyrbdhikb.html

npm i -D vitest;  npx vitest
来源：http://dali.aizwys.cn/Article/details/gtxirhmpcx.html

[U118] JS：开发服务器
来源：http://dali.wangdashe.top/Article/details/gtonlugrdp.html

npm i -D vite;  npx vite
来源：http://dali.vqdsnc.cn/Article/details/gtbnudtagq.html

[U119] JS：生产构建
来源：http://dali.smart0.xyz/Article/details/gtywtobufq.html

npx vite build
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtqnqiqs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ppjwa.cn/Article/details/gtsjzrletd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gtrenmoxzg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbfgarmar.html

统计汇总
来源：http://dali.jlsjyb.cn/Article/details/gtkkkmaper.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfhjvamo.html

按语言统计（条）：
来源：http://dali.jinqigufen.top/Article/details/gtgrhpbkgb.html

Python ......... 252
来源：http://dali.hammf.cn/Article/details/gtazudpopt.html

PHP ............ 252
来源：http://dali.bjfxy.top/Article/details/gtkytpremo.html

JavaScript ..... 252
来源：http://dali.zhixingplan.top/Article/details/gtwylxsdbc.html

TypeScript ..... 212
来源：http://dali.birdmap.top/Article/details/gtcsibfalf.html

Java ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gtjvcknxgl.html

Go ............. 212
来源：http://dali.yj20258888.top/Article/details/gtjqkdrsrz.html

Ruby ........... 212
来源：http://dali.nanxinkj.top/Article/details/gtlqwkczsf.html

C# ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gthmyesxlm.html

C .............. 30
来源：http://dali.meibo888.top/Article/details/gtbsajvrtz.html

C++ ............ 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddzyitum.html

SQL ............ 90
来源：http://dali.yuxming.cn/Article/details/gtroudpihm.html

Bash ........... 80
来源：http://dali.yj202588.top/Article/details/gtozhptiir.html

Kotlin ......... 15
来源：http://dali.dianchejie.cn/Article/details/gtmyctimau.html

Swift .......... 15
来源：http://dali.nwbrower.top/Article/details/gtwanofqrl.html

Lua ............ 10
来源：http://dali.hfpthk.cn/Article/details/gtrnbuvaim.html

Perl ........... 10
来源：http://dali.ybcxt.top/Article/details/gtbjbydfac.html

Scala .......... 10
来源：http://dali.xinyue.icu/Article/details/gtoojhxinv.html

------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtfujuscij.html

合计 ........... 2106 条
来源：http://dali.sweek.top/Article/details/gtqgtviwcl.html

按章节统计：
来源：http://dali.hammf.cn/Article/details/gtbjpufyqe.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gtonarinfl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gtuwsstoem.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gttryrrwvg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gthgllyims.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jyoumei.cn/Article/details/gteusjlkqs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gtehftcwmf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yongpay.top/Article/details/gtejollsya.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gtqieqkmic.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gtrxjbsgwb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gtokfqybmx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtpsckujnw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtoqxgmyvw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtgolfptlb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258888.top/Article/details/gtorphmqwf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenjidiqi.icu/Article/details/gtnbchlpsu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtcpndhdlv.html

Q SQL 专题                              90
来源：http://dali.shangyingyoupin.top/Article/details/gtmfdatfxx.html

R Bash 专题                             80
来源：http://dali.hongshengwenyu.top/Article/details/gtqamyotla.html

S C / C++ 专题                          60
来源：http://dali.hnxiangtu.top/Article/details/gtsfudyaho.html

T 其他语言补充                          60
来源：http://dali.xuetiantiany.cn/Article/details/gtidlrekiw.html

U 高频实用片段                         120
来源：http://dali.hfpthk.cn/Article/details/gtgiuzvkgt.html

------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtxvsxjvbe.html

合计                                  2106 条
来源：http://dali.yvedp.cn/Article/details/gtjiuedgvl.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowbmbnmm.html

使用提醒
来源：http://dali.shzxlz.cn/Article/details/gtweswlwdb.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtsjsyasik.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ivvv.top/Article/details/gtalixqtgr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yanxiufei.cn/Article/details/gtbrfvdobg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xziqi.cn/Article/details/gtdfhwbxrd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gogol.net.cn/Article/details/gtmvzvovxl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.wangdashe.top/Article/details/gtzqakikxg.html

—— 文件结束 ——
来源：http://dali.sweek.top/Article/details/gtiwrlvjfi.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtldubykvd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shzxlz.cn/Article/details/gtcetmrfjw.html

Common Programming Examples Cheat Book
来源：http://dali.cheryme.top/Article/details/gtlzlwdbvh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtyylrnedy.html

【收录内容】
来源：http://dali.daxiang520.top/Article/details/gtirrtsfqm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.daria6918.cn/Article/details/gtdthbcutf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenzaomai.com/Article/details/gtlzjkggew.html

SQL · Bash · C · C++
来源：http://dali.yangfankeji.com/Article/details/gtmfkgichu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sxryk.cn/Article/details/gtwpynmcvb.html

【使用说明】
来源：http://dali.ydzc1.top/Article/details/gtvkgtelbx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sufxvd.cn/Article/details/gtbvuuletk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jqgufenzy.top/Article/details/gtdgkhzdji.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cucudq.cn/Article/details/gtyxnhxwzc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xinyue.icu/Article/details/gtkfguonhr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhiwuduotai.top/Article/details/gtyalxoczm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenlongwang.top/Article/details/gtkimztwch.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj202588.top/Article/details/gtjkojqene.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ppjwa.cn/Article/details/gtiejfenyk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gzhubu.top/Article/details/gtsdjtmzgk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.snrcjt.cn/Article/details/gtakwxnsev.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gotoacloud.top/Article/details/gtehaegvua.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jqgfzy.top/Article/details/gtozlftbyy.html

【文件统计】
来源：http://dali.sufxvd.cn/Article/details/gtxxguneie.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.quarkkingdee.top/Article/details/gtfvevjkpg.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtyboecywu.html

目  录
来源：http://dali.316326.xyz/Article/details/gtvnathnif.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtaoyndfns.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.daxiang520.top/Article/details/gtjkbuzhtx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gtcoomjcge.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yongpay.top/Article/details/gtdsbjobfw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.andypj.xyz/Article/details/gttukhreyk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gaohongyu789.top/Article/details/gtrpouxgyn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.meibo888.top/Article/details/gtmsarmksp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yonumen.top/Article/details/gtnjecazrn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ivvv.top/Article/details/gtjwocrvbu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtmrgzqqmw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.havefunace.top/Article/details/gttasbgxzp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtkdijsaml.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gtiztlfdmw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gtgcdtrjaw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.bjfxy.top/Article/details/gtdlhrmckd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sweek.top/Article/details/gtnsujfcfm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gturqruonu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gteaaknylu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.pycfn.com/Article/details/gtnucvxgku.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yonumen.top/Article/details/gtnqejjayp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtbwmtmcwh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.dianchejie.cn/Article/details/gthlrbsfau.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtffalhxjp.html

A. 基础语法与类型
来源：http://dali.meibo888.top/Article/details/gtlirazaio.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbeifqeeh.html

[A01] Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gttiwxvzoa.html

Py:   print("Hello, World!")
来源：http://dali.aibaodan.cn/Article/details/gtjhxfllkb.html

PHP:  echo "Hello, World!";
来源：http://dali.zhixingplan.top/Article/details/gtcksnphgb.html

JS:   console.log("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gtlewgsmbl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.0kj1m.cn/Article/details/gtxtutwckl.html

Java: System.out.println("Hello, World!");
来源：http://dali.snrcjt.cn/Article/details/gtmwmgdpgg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.haohaochexian.top/Article/details/gtqdlxrndw.html

Ruby: puts "Hello, World!"
来源：http://dali.gzhubu.top/Article/details/gtyucpjqdi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbhfltjv.html

[A02] 变量声明与赋值
来源：http://dali.zhongyouzk.top/Article/details/gtknorkvhm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tanke756.top/Article/details/gtdewldnsz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtqkikektc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.aizwys.cn/Article/details/gtoflloxhj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gtszixeqok.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gtdplvpjmn.html

Go:   name := "Alex"; age := 20
来源：http://dali.yangfankeji.com/Article/details/gtfgnbyefd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.havefunace.top/Article/details/gtzkipmjvn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gogol.net.cn/Article/details/gtdbszwxqr.html

[A03] 常量定义
来源：http://dali.sufxvd.cn/Article/details/gtwbqkjoru.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.redwolf501.top/Article/details/gtvsnvzyoz.html

PHP:  const PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsukvlbuv.html

JS:   const PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtxrhtzlka.html

TS:   const PI: number = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtvkjacowa.html

Java: static final double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtotwjkhvl.html

Go:   const PI = 3.14159
来源：http://dali.snrcjt.cn/Article/details/gtpnxsxzzs.html

Ruby: PI = 3.14159
来源：http://dali.hnxiangtu.top/Article/details/gtbaznpfnu.html

C#:   const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtycsobdig.html

[A04] 判断变量类型
来源：http://dali.wangdashe.top/Article/details/gtmofwzavw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gaohongyu789.top/Article/details/gtuftcbzzm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinqigufen.top/Article/details/gtrbaiptru.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sufxvd.cn/Article/details/gthevdtfkx.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj20258.top/Article/details/gtuibrlfdb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cqqwz.cn/Article/details/gtdyrksimh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zycfv.cn/Article/details/gtrofymwmw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.c1oappe.top/Article/details/gtmgoiuqgf.html

C#:   x.GetType().Name; x is int
来源：http://dali.chenlongwang.top/Article/details/gtdkmwecxb.html

[A05] 整数除法与取模
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqbufqnd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.nanxinkj.top/Article/details/gtnlnljfxl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtdlhrsosu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtmthujmku.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvlzlkaw.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtynmwdmoj.html

Go:   7 / 2; 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtpwznkjxw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtdswoybfk.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtaskamsgj.html

[A06] 字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtpyflhrny.html

Py:   int("42"); float("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gtayvbtuss.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.redwolf501.top/Article/details/gtrdacrrqz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xuetiantiany.cn/Article/details/gtvxqjbnlv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.tanke756.top/Article/details/gtxepzzios.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.aizwys.cn/Article/details/gtaptczluq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hywenlv.cn/Article/details/gtliiyswph.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhpzepdx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jqgufenzy.top/Article/details/gttrrkzwwm.html

[A07] 数字转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtqworizki.html

Py:   str(42)
来源：http://dali.pycfn.com/Article/details/gtvjieshlm.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhoulong.xyz/Article/details/gtqkpjgkfr.html

JS:   String(42); (42).toString()
来源：http://dali.chenlongwang.top/Article/details/gthqosljyh.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gtawlgtndd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zycfv.cn/Article/details/gtjbviaesl.html

Go:   strconv.Itoa(42)
来源：http://dali.xuanzx.com/Article/details/gtskxrvhvd.html

Ruby: 42.to_s
来源：http://dali.xuanzx.com/Article/details/gtmnngbtmz.html

C#:   42.ToString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdugutlqp.html

[A08] 取整与四舍五入
来源：http://dali.meibo888.top/Article/details/gthglwyidr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gtzmptvpmp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xuanzx.com/Article/details/gtxpsltsgl.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yonumen.top/Article/details/gtjapjcoct.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xylfe.cn/Article/details/gtlphqdcgw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gtijlcpged.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gtvqnogrqw.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenzaomai.com/Article/details/gtlmyxiyuq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtlvajqawt.html

[A09] 绝对值与最大最小值
来源：http://dali.0kj1m.cn/Article/details/gtyjfskyyf.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtubsmlail.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtlsrokxse.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtbjlcfmge.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yongpay.top/Article/details/gtecgvkvlw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtjgxvtivt.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.birdmap.top/Article/details/gtysvwvbmr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ivvv.top/Article/details/gtssskdhwh.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtnukbtrwh.html

[A10] 生成随机数
来源：http://dali.yuxming.cn/Article/details/gtdrktjrno.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jianghu66.top/Article/details/gtgezlohth.html

PHP:  random_int(1, 100);
来源：http://dali.sysykeji.top/Article/details/gtysanwyon.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cqqwz.cn/Article/details/gtyyonsuvw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nwbrower.top/Article/details/gthcpkdruz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj20258.top/Article/details/gtsewwkvqk.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.andypj.xyz/Article/details/gtqnkmgyvq.html

Ruby: rand(1..100)
来源：http://dali.jlsjyb.cn/Article/details/gtbgxexbkj.html

C#:   new Random().Next(1, 101)
来源：http://dali.ehwqpu.com/Article/details/gtpxxdmuxx.html

[A11] 条件表达式（三元）
来源：http://dali.zhongyouzk.top/Article/details/gtbioeestp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ehwqpu.com/Article/details/gtljfgjecs.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gtncadfnbu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gtdnfjnnkb.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtqdrkzyfr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gtvkubxjjg.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zycfv.cn/Article/details/gtssyfdcgz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.dashuyun.cn/Article/details/gtrdmwgjrb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gtbqzmgrvl.html

[A12] 字符串插值 / 格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxsrslzl.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.fzhhl.top/Article/details/gtiadztwzq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.svipenyu.cn/Article/details/gtczehwetu.html

JS:   `Hello, ${name}!`
来源：http://dali.cheryme.top/Article/details/gtxfmfsrxq.html

TS:   `Hello, ${name}!`
来源：http://dali.jyoumei.cn/Article/details/gtrkbksprx.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgrjedgz.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.shzxlz.cn/Article/details/gtaftvlldy.html

Ruby: "Hello, #{name}!"
来源：http://dali.yj20258.top/Article/details/gtqbxbxefe.html

C#:   $"Hello, {name}!"
来源：http://dali.guannengcc.top/Article/details/gtupffbtzl.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ybcxt.top/Article/details/gtzwjdniak.html

Py:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtjtriewdc.html

PHP:  "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtaezugyiu.html

JS:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtazjsnkve.html

TS:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gtioinwtce.html

Java: "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtexixivwe.html

Go:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtfliunmls.html

Ruby: "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtbyzicufd.html

C#:   "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtxlvtizkv.html

[A14] 注释写法
来源：http://dali.ehwqpu.com/Article/details/gtpqsqpauo.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.cashguo.top/Article/details/gtpkcbmxzi.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gtclbptguq.html

JS:   // 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gthcjojuae.html

TS:   // 单行；/* 多行 */
来源：http://dali.fzhhl.top/Article/details/gtxddevlbm.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.pycfn.com/Article/details/gtxcleqpcj.html

Go:   // 单行；/* 多行 */
来源：http://dali.chenlongwang.top/Article/details/gthbaqbokg.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hnqzz.top/Article/details/gtfufadaaw.html

C#:   // 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gtxiynztpg.html

[A15] 空值判断与默认值
来源：http://dali.yongpay.top/Article/details/gtasuuylgi.html

Py:   value = data or "默认值"
来源：http://dali.ehwqpu.com/Article/details/gtpphixiun.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gteqhhngcc.html

JS:   const value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gtnbjmaikd.html

TS:   const value = data ?? "默认值";
来源：http://dali.sysykeji.top/Article/details/gtxsmysutf.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yanxiufei.cn/Article/details/gtptsueqbt.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hywenlv.cn/Article/details/gtdlntfuqo.html

Ruby: value = data || "默认值"
来源：http://dali.aizwys.cn/Article/details/gtudwvslgs.html

C#:   var value = data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gtmvuhbgsj.html

[A16] 真假值判断规则
来源：http://dali.wangshuangyany.cn/Article/details/gtnfwxqwab.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.pengpengdd.cyou/Article/details/gtgtlrjodl.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.tianlin.xyz/Article/details/gtrmozxrwl.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.ybcxt.top/Article/details/gtdkwuqrwr.html

TS:   if (!x) {}
来源：http://dali.yangfankeji.com/Article/details/gtykkrndym.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtflszqdlb.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yvedp.cn/Article/details/gtpekintzj.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.0kj1m.cn/Article/details/gtzzraukle.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.haohaochexian.top/Article/details/gtzrpvvnkh.html

[A17] 位运算
来源：http://dali.zhoulong.xyz/Article/details/gtgyvbtuxc.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gtlmquxagf.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.sxryk.cn/Article/details/gtaiwcdcyh.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtscosuqog.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtqiqtvytq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtithsfvqm.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtqsnufrpz.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtzrjyeuhg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtcxncymmo.html

[A18] 字符与 ASCII 码互转
来源：http://dali.havefunace.top/Article/details/gtapvjumhq.html

Py:   ord("A"); chr(65)
来源：http://dali.xuetiantiany.cn/Article/details/gtqgbcgltw.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gtjzbprutk.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shangyingyoupin.top/Article/details/gtkfunhlsa.html


<!-- 参考信息 -->