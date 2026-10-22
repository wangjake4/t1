代发 wailian999

[U103] JS：定时器
来源：http://dali.yvedp.cn/Article/details/gtbdphjjjn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.9152youxi.cn/Article/details/gtwmlmpigs.html

[U104] JS：防抖
来源：http://dali.xinyue.icu/Article/details/gtrerysabb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtqydayaso.html

[U105] JS：节流
来源：http://dali.wangdashe.top/Article/details/gtwvfkaaiv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinqigufen.top/Article/details/gtjwdcnzxd.html

[U106] JS：日期格式化
来源：http://dali.yj202588.top/Article/details/gtosjbmseh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj20258.top/Article/details/gtquyrvujs.html

[U107] JS：数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gtwnaybssq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gthujacakl.html

[U108] JS：随机整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkjvhwcd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgufenzy.top/Article/details/gtryumiknd.html

[U109] JS：数组分组
来源：http://dali.jqgufenzy.top/Article/details/gteqvvjhng.html

Object.groupBy(arr, x => x.type)
来源：http://dali.pycfn.com/Article/details/gtltrdbfmz.html

[U110] JS：数组分块
来源：http://dali.kuanghao11.cn/Article/details/gtrcziuobu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zdqjudy.top/Article/details/gtbzpvbviw.html

[U111] JS：对象转 Map
来源：http://dali.aibaodan.cn/Article/details/gtrwhbfdzj.html

new Map(Object.entries(obj))
来源：http://dali.gzhubu.top/Article/details/gtvtejkpyt.html

[U112] JS：字符串补位
来源：http://dali.ivvv.top/Article/details/gtgmshnosb.html

"7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtjavpdvsm.html

[U113] JS：正则替换全部
来源：http://dali.yonumen.top/Article/details/gtwutrtjjt.html

s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtcknjgria.html

[U114] JS：JSON 深比较
来源：http://dali.guannengcc.top/Article/details/gtrrducymx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gtqfzrobbz.html

[U115] JS：生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtlqxyrnim.html

crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtiprnncpj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hfpthk.cn/Article/details/gtrymldgno.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pycfn.com/Article/details/gtczckusng.html

[U117] JS：单元测试
来源：http://dali.yangfankeji.com/Article/details/gtrkzhnenb.html

npm i -D vitest;  npx vitest
来源：http://dali.sysykeji.top/Article/details/gtfwlsthax.html

[U118] JS：开发服务器
来源：http://dali.snrcjt.cn/Article/details/gtamfnalta.html

npm i -D vite;  npx vite
来源：http://dali.guannengcc.top/Article/details/gtzbclsise.html

[U119] JS：生产构建
来源：http://dali.nwbrower.top/Article/details/gtznpirhdj.html

npx vite build
来源：http://dali.dianchejie.cn/Article/details/gtoxgadroh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xylfe.cn/Article/details/gtqgxdxwdm.html

import.meta.env.VITE_API_URL
来源：http://dali.aizwys.cn/Article/details/gtbdjeernn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtnrwlezqi.html

统计汇总
来源：http://dali.sufxvd.cn/Article/details/gtmriuhkfb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzjzvqsve.html

按语言统计（条）：
来源：http://dali.cucudq.cn/Article/details/gtudciasdx.html

Python ......... 252
来源：http://dali.dianchejie.cn/Article/details/gtxfpbssik.html

PHP ............ 252
来源：http://dali.dianchejie.cn/Article/details/gtyaobqzof.html

JavaScript ..... 252
来源：http://dali.zhoulong.xyz/Article/details/gtfdwzhwkm.html

TypeScript ..... 212
来源：http://dali.snrcjt.cn/Article/details/gtbzlvwjox.html

Java ........... 212
来源：http://dali.shzxlz.cn/Article/details/gtghawvook.html

Go ............. 212
来源：http://dali.svipenyu.cn/Article/details/gtbzassjgd.html

Ruby ........... 212
来源：http://dali.andypj.xyz/Article/details/gtuqminkzu.html

C# ............. 212
来源：http://dali.gogol.net.cn/Article/details/gtxulsdyeu.html

C .............. 30
来源：http://dali.9152youxi.cn/Article/details/gtajuuzqzc.html

C++ ............ 30
来源：http://dali.feifeiyinyue.top/Article/details/gtcuiodvxz.html

SQL ............ 90
来源：http://dali.ydzc1.top/Article/details/gtvljifbqj.html

Bash ........... 80
来源：http://dali.nanxinkj.top/Article/details/gtipsbxbyu.html

Kotlin ......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gttlrxkjno.html

Swift .......... 15
来源：http://dali.mhx1999.top/Article/details/gtqqcjiwyd.html

Lua ............ 10
来源：http://dali.yueranfly.top/Article/details/gtlhmbffiq.html

Perl ........... 10
来源：http://dali.c1oappe.top/Article/details/gttczyojrj.html

Scala .......... 10
来源：http://dali.nwbrower.top/Article/details/gtbeypvtht.html

------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtnjvthnvn.html

合计 ........... 2106 条
来源：http://dali.smart0.xyz/Article/details/gthajfsbsb.html

按章节统计：
来源：http://dali.meibo888.top/Article/details/gtvlvnfdbu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hnqzz.top/Article/details/gtmvvygmzl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtgaegxefs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtorffsidy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinqigufen.top/Article/details/gtaozbwvkz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nanxuanxn.top/Article/details/gtjrdogxxv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhongyouzk.top/Article/details/gtgesccqbe.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gtcjdxsikb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gtnbcfbtsx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtfuxwaqyj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.c1oappe.top/Article/details/gtcqucmyhn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtoawfabqq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtqwzliyow.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtazikimsk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvhpmhih.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ehwqpu.com/Article/details/gttbjyxghb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtieggmixr.html

Q SQL 专题                              90
来源：http://dali.cdnleiting.top/Article/details/gtqgnriyuh.html

R Bash 专题                             80
来源：http://dali.zhongyouzk.top/Article/details/gtgkmsvyxy.html

S C / C++ 专题                          60
来源：http://dali.9152youxi.cn/Article/details/gtdjsmbaul.html

T 其他语言补充                          60
来源：http://dali.cqqwz.cn/Article/details/gtqsiwcqvi.html

U 高频实用片段                         120
来源：http://dali.gaohongyu789.top/Article/details/gtwmjqcshf.html

------------------------------------
来源：http://dali.yj20258.top/Article/details/gthclqgdgp.html

合计                                  2106 条
来源：http://dali.gzhubu.top/Article/details/gtbzhbjkxs.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtdawbnfzc.html

使用提醒
来源：http://dali.guannengcc.top/Article/details/gtrcrjexuc.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtvjjcnwmr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhengqikj.top/Article/details/gtoptgeepx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cucudq.cn/Article/details/gtbhzbydpm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdidnmogm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xuetiantiany.cn/Article/details/gtcsvxsdvk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ydzc1.top/Article/details/gtjywrefys.html

—— 文件结束 ——
来源：http://dali.gzhubu.top/Article/details/gtcgnwczyf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtfizhdvab.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.fengsongda.top/Article/details/gtffqpvpsw.html

Common Programming Examples Cheat Book
来源：http://dali.jqgufenzy.top/Article/details/gtypwkjvms.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtvjoljoze.html

【收录内容】
来源：http://dali.cheryme.top/Article/details/gtylztcbiy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yueranfly.top/Article/details/gthuqrbtud.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.9152youxi.cn/Article/details/gtoeteixtr.html

SQL · Bash · C · C++
来源：http://dali.xylfe.cn/Article/details/gtyzoktywg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sweek.top/Article/details/gtsfqcizxj.html

【使用说明】
来源：http://dali.jlsjyb.cn/Article/details/gtdudbhzfs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.fengsongda.top/Article/details/gtgxzianri.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.smart0.xyz/Article/details/gtxmomfhhl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jiagoushi.top/Article/details/gtojiwazag.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.aizwys.cn/Article/details/gtdulwonqk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.pengpengdd.cyou/Article/details/gtshbjfjch.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj202588.top/Article/details/gtftfngtyz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.feifeiyinyue.top/Article/details/gtkbujzfkx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gzhubu.top/Article/details/gtnyxjncen.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ppjwa.cn/Article/details/gthhofpzlj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ybcxt.top/Article/details/gtesrzqevo.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhixingplan.top/Article/details/gtyphggbuc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jlsjyb.cn/Article/details/gtitdumzfn.html

【文件统计】
来源：http://dali.kuanghao11.cn/Article/details/gtsofqbjhi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jiagoushi.top/Article/details/gtmtzairuu.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtqaedngcb.html

目  录
来源：http://dali.hysaishi.cn/Article/details/gtfbfutddb.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtpvhnfubr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gzhubu.top/Article/details/gtwoldkame.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtnbhoaqyh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvamgjudz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.redwolf501.top/Article/details/gtsvfajohx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gogol.net.cn/Article/details/gtrquwwigz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpbwoioa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.wangdashe.top/Article/details/gtymekwrnb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hysaishi.cn/Article/details/gtlfuasvpb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtchlshuqd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.dianchejie.cn/Article/details/gttocoppoi.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gtuccbwnbh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtthpqgvjq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtguiegqxx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhixingplan.top/Article/details/gtwdplqcsh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yvedp.cn/Article/details/gtqrqchzuw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gthwpetqwg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.redwolf501.top/Article/details/gtoccrmqka.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtvrcvnjbi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.tian-w.cn/Article/details/gtcjotubnc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gtrrktofjp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shzxlz.cn/Article/details/gtjhcbmzhs.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtmjvgrsza.html

A. 基础语法与类型
来源：http://dali.jqgfzy.top/Article/details/gtyczcgthr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtalyscssr.html

[A01] Hello World
来源：http://dali.shzxlz.cn/Article/details/gthperxwdr.html

Py:   print("Hello, World!")
来源：http://dali.xuanzx.com/Article/details/gtmhltthkm.html

PHP:  echo "Hello, World!";
来源：http://dali.fzhhl.top/Article/details/gtiewpxndt.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gtlciwwqrp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.andypj.xyz/Article/details/gtmbqdkfiz.html

Java: System.out.println("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gtheyzsgae.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhengqikj.top/Article/details/gtayogdmke.html

Ruby: puts "Hello, World!"
来源：http://dali.ehwqpu.com/Article/details/gtsaudofxp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gtpuacqare.html

[A02] 变量声明与赋值
来源：http://dali.shuidangran.top/Article/details/gtsmtelsmk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.havefunace.top/Article/details/gtrjrpqrao.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtcxyhkjmk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtrpqcgpic.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.guowangkeji.top/Article/details/gtghdanzyb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ybcxt.top/Article/details/gtsvtrnzzo.html

Go:   name := "Alex"; age := 20
来源：http://dali.havefunace.top/Article/details/gtricfnjta.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hywenlv.cn/Article/details/gtwlvrzypl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.snrcjt.cn/Article/details/gtaxorgfpt.html

[A03] 常量定义
来源：http://dali.jlsjyb.cn/Article/details/gtlzawfmzf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhiwuduotai.top/Article/details/gtldjflzsw.html

PHP:  const PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvyhgnng.html

JS:   const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtigrqnkzl.html

TS:   const PI: number = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtuuarctlq.html

Java: static final double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gttxnyjvlt.html

Go:   const PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gtxewfsiyr.html

Ruby: PI = 3.14159
来源：http://dali.xuetiantiany.cn/Article/details/gtixolavjm.html

C#:   const double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtsseiwotw.html

[A04] 判断变量类型
来源：http://dali.meibo888.top/Article/details/gtqgodylax.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hywenlv.cn/Article/details/gtmvttehfj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cucudq.cn/Article/details/gtbmbkmqek.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinqigufen.top/Article/details/gtdjiwztar.html

TS:   typeof x; x instanceof Date
来源：http://dali.xuetiantiany.cn/Article/details/gtczuweegy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shanyushiyangtech.top/Article/details/gttkpapybq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhongyouzk.top/Article/details/gtgrudqdbk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.svipenyu.cn/Article/details/gttrjyseau.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhoulong.xyz/Article/details/gtphvcdexx.html

[A05] 整数除法与取模
来源：http://dali.mhx1999.top/Article/details/gteyhuimga.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sxryk.cn/Article/details/gtctsjddhy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhcqbmla.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtplljwgci.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.andypj.xyz/Article/details/gthdpkpszq.html

Java: 7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtaupfhlwy.html

Go:   7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gthdbitxtr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtxbzpyaxq.html

C#:   7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtcuzbeysm.html

[A06] 字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gtpibuglec.html

Py:   int("42"); float("3.14")
来源：http://dali.yueranfly.top/Article/details/gtacbfyuwz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.svipenyu.cn/Article/details/gtziecleub.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gtyogafhkw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shuidangran.top/Article/details/gtmpzbuurx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinqigufen.top/Article/details/gthmtjlqfx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxymjxqxu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yongpay.top/Article/details/gtwrcospcy.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenjidiqi.icu/Article/details/gtfxurnbvd.html

[A07] 数字转字符串
来源：http://dali.dianchejie.cn/Article/details/gtdtxmpzvy.html

Py:   str(42)
来源：http://dali.gzhubu.top/Article/details/gtslxtmnpk.html

PHP:  (string) 42; strval(42)
来源：http://dali.316326.xyz/Article/details/gttmyesyni.html

JS:   String(42); (42).toString()
来源：http://dali.sysykeji.top/Article/details/gtvwcvakit.html

TS:   String(42)
来源：http://dali.yj20258.top/Article/details/gtbxlhdqsa.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yvedp.cn/Article/details/gtwgcwdsai.html

Go:   strconv.Itoa(42)
来源：http://dali.pycfn.com/Article/details/gtgdeonahh.html

Ruby: 42.to_s
来源：http://dali.pycfn.com/Article/details/gtvdsdkzhk.html

C#:   42.ToString()
来源：http://dali.hammf.cn/Article/details/gtcbdtcwif.html

[A08] 取整与四舍五入
来源：http://dali.cucudq.cn/Article/details/gtvamyxtez.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gtebhxlutd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgzvoyyk.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gtvltnmlii.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.dashuyun.cn/Article/details/gtqxdwsnbu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsoiohixt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gtkepighda.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jyoumei.cn/Article/details/gtpuagcifk.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gtqjendmwq.html

[A09] 绝对值与最大最小值
来源：http://dali.sufxvd.cn/Article/details/gtlcqrnedd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteefwdeve.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtegrovkpe.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtkcucaiiw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtmfnrgpwp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtlkftriki.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.nanxinkj.top/Article/details/gtivztwmyg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.havefunace.top/Article/details/gtconamlpd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtazddrdju.html

[A10] 生成随机数
来源：http://dali.guannengcc.top/Article/details/gtiptlyuzj.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yj20258888.top/Article/details/gtilnwnuun.html

PHP:  random_int(1, 100);
来源：http://dali.feifeiyinyue.top/Article/details/gtkvbeinnt.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.bjfxy.top/Article/details/gtympadpvs.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zycfv.cn/Article/details/gtlfhmcedz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xinyue.icu/Article/details/gtdsvszpin.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.redwolf501.top/Article/details/gtbgtqjjvj.html

Ruby: rand(1..100)
来源：http://dali.jyoumei.cn/Article/details/gtljeozfua.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinqigufen.top/Article/details/gtszntodvw.html

[A11] 条件表达式（三元）
来源：http://dali.svipenyu.cn/Article/details/gtwnxydygb.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.nwbrower.top/Article/details/gtwpwmfoer.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gtbqmlaqtw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtkeobzkaa.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gtcugqfkus.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.cucudq.cn/Article/details/gtbdwjidnr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.gogol.net.cn/Article/details/gtmpphefuo.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gtcblagxaq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtokguihhm.html

[A12] 字符串插值 / 格式化
来源：http://dali.yuanzhike.top/Article/details/gttpsivgvw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cucudq.cn/Article/details/gtyuijdckk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.cdnleiting.top/Article/details/gtsbztnpma.html

JS:   `Hello, ${name}!`
来源：http://dali.cqqwz.cn/Article/details/gtepdvgvqv.html

TS:   `Hello, ${name}!`
来源：http://dali.chenlongwang.top/Article/details/gtqiumizub.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.fengsongda.top/Article/details/gtngsnutyi.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhixingplan.top/Article/details/gtgyjwpeto.html

Ruby: "Hello, #{name}!"
来源：http://dali.hammf.cn/Article/details/gtxcujaqzn.html

C#:   $"Hello, {name}!"
来源：http://dali.redwolf501.top/Article/details/gtaayqbpxr.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ybcxt.top/Article/details/gtuqsjhanw.html

Py:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtosqjdlce.html

PHP:  "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtvzwheagv.html

JS:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtzceyogid.html

TS:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gthaseghjn.html

Java: "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gttxtetvom.html

Go:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtkmgeuyby.html

Ruby: "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gtddycfqhg.html

C#:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gtjvkfvpqo.html

[A14] 注释写法
来源：http://dali.yuxming.cn/Article/details/gteuvrcgzu.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.chenjidiqi.icu/Article/details/gtcacctwfz.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.redwolf501.top/Article/details/gteohnseou.html

JS:   // 单行；/* 多行 */
来源：http://dali.snrcjt.cn/Article/details/gtzatjcgwd.html

TS:   // 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gtizbldvmw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jinqigufen.top/Article/details/gtvaiyhhrq.html

Go:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtrzkprxax.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.9152youxi.cn/Article/details/gtiilmjyno.html

C#:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gtmjhmhlgf.html

[A15] 空值判断与默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxtmskqg.html

Py:   value = data or "默认值"
来源：http://dali.smart0.xyz/Article/details/gtshbkpubo.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ivvv.top/Article/details/gtdxfjmpgg.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhengqikj.top/Article/details/gtbxlvvbuf.html

TS:   const value = data ?? "默认值";
来源：http://dali.fzhhl.top/Article/details/gtzxtdwcmt.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj202588.top/Article/details/gtczzdsfyx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hnxiangtu.top/Article/details/gtunktpncd.html

Ruby: value = data || "默认值"
来源：http://dali.yj20258888.top/Article/details/gtclzjjsec.html

C#:   var value = data ?? "默认值";
来源：http://dali.redwolf501.top/Article/details/gtmishrpcp.html

[A16] 真假值判断规则
来源：http://dali.shanyushiyangtech.top/Article/details/gtccgeakgk.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xuanzx.com/Article/details/gtbxjfqgfy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturgnwsql.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sxryk.cn/Article/details/gtrubxvayw.html

TS:   if (!x) {}
来源：http://dali.hnxiangtu.top/Article/details/gtxzgcnaqn.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hammf.cn/Article/details/gtzcrocegy.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.fzhhl.top/Article/details/gtdboebdjg.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hnqzz.top/Article/details/gtkbewhxbv.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.nwbrower.top/Article/details/gtnlpzvbjz.html

[A17] 位运算
来源：http://dali.wangdashe.top/Article/details/gtczmcctwm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gtzxoxwdmm.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gtjdkkstqx.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtidqjrenf.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwxosacd.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtivglvaoz.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtaticlsol.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtlwckynze.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtqtcqkdve.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwokmiij.html

Py:   ord("A"); chr(65)
来源：http://dali.sweek.top/Article/details/gtxndccrre.html

PHP:  ord("A"); chr(65)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsvdemxc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtontoxylc.html


<!-- 参考信息 -->