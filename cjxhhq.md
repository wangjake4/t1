代发 wailian999

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvrnyaq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmbzbbs.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcnqwde.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2avahpiwq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzyimwr.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2cghkplkv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xazvznhz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2trbdghqc.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcpdlwj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiccisln.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2llukahjj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwgjuxu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbeybey.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fowwizfc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbqldig.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhtljek.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnpxqtp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxndnap.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tyftpvsb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyvoser.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwmnghv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfhvqkh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2pltsvcvh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2iwinsvua.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yewegrkw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2chvedvhp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxllizy.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuvxmfh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdyswjx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcbtotb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ohklcuwl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvsmxjl.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvcyjyz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuexpso.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2upmsmdiz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2buuypget.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxchrfk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2juorvrgb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mybvguix.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xotyjwny.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcmjfgv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqcmwuq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ataewzfr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2oupfxikp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edrtzihz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cciyxozv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmwcxle.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbknazh.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvnuzrb.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fslrcryh.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ltplkxei.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aekdvpwe.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgqcltv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2awnncsym.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcfkhnj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nabmrxcs.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpavunh.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbdhwue.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2tlodpmfn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeodyer.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tllygdia.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlyjdiw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wuojatqh.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2haevxqpw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcutpes.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmbqgak.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qmumlosp.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2uihscteq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2daoeffwu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rkftwisc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2huabuqtc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpdonvh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2tnztwdkc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2riccjdcp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lywuskmf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjciccs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uidbvawe.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2beqizcna.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vpeumqeo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mczaxssr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tkflebjx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiipdjh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2hgawgzsl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hakxyqie.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2xerbhchh.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgmwvam.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dlylvwkl.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2djdwwigo.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxqmrkv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdmzedj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmirrku.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvgekua.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzuszeq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sewovkgw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfjqylf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnchqzt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2bheixwre.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ifupabri.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2glrvzvdr.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrdcmzn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzehavq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxsmyfx.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2oekeipjr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsnkfqz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2nfystptj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmemwnj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2aicnbsqf.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2useoixwl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdjpdcc.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2hacojzdd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2tswkooxu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2copzduym.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwosfwj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgzipkp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzfkdxl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2uyeyyeip.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnkqnsi.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmbrdhd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlmrdvv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2epatbsfw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvzwhuu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2eilbenha.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2daknaiiy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcefvjf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2abzsztny.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2nndskprc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2odohvffb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nenqquwx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqzkhqi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aludiohr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgaqfql.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsbboma.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2axjurjtb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghevenym.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zehlmyeo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bttrearo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgketwrg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxutgnw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuvlmpq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhddndwq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrvkpsf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsogpfe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfvqlwt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbjenip.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvunszbu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgxydqe.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2oprwfkuy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuxodrc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgbbeps.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xigvdfei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkibiox.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtyrpuy.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhywthd.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vmssxtfd.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bnechgku.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbjpwwf.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxlclec.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rehdcwvv.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ziadurhc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlltmin.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxxfnfc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsrdnzg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2frrpoaem.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ineglfqc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2agfbflaz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xspwmecx.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpfouky.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2luvhawum.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjtjsrz.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xoszwcaf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzgejha.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcplpoq.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjdpbcx.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2csryaxdq.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtvzlgf.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrfhngn.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzggcms.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgrrryv.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dumycdqo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlqnfbg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2njmamktk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvmdjnk.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcwadmv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2wagpcuph.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzruocqq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2sclpesqk.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfwmttr.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgexckr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aowddoqb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pqawujpf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuiskbi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfxalky.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tmymymmd.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcccvfk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eusalkop.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmoewon.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbyxfzc.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2whwhyaug.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrlhfps.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzijrex.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxkpjan.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgmmnwz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgfoczt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2lnujqnjd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2aodtluat.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdenqrh.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2czlcyfgy.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrjunbh.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdussyq.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbindwty.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2poxskxck.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyabtsd.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkgidcu.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dndessei.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtnrdpx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzurndu.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoqonut.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2huonjqmb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdykfmxc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2apdbyauf.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzboypxh.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2varhhqlh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjvxfgc.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxtchio.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxmwsjn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcttwkye.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jacvyasq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqklrgd.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpsmuit.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2gexupzqm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2oclrlsoa.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfdslht.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkhymyu.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpltjbz.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2rakcpuis.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkmvhae.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2etowgimd.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxgkhbn.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqqhvec.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwzutqp.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2melnkwdi.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2gscuphyr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dweqycoz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2djwtahps.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhgrtnu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbgwezb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqcpvhz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wevoeigh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhggdum.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyysbek.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wkywigvt.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nckcyanc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrmoohx.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2kafoolxc.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2msrmooih.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iguqgjgw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2boqxocqc.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgvgdwp.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzeunkoi.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2aevtmhdo.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lelspfpc.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuymyes.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mamyjeic.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfiqvtr.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvpypay.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wypqtwhz.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2difilrmu.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2axxbleib.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vnghbdcm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwdjaco.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzojhbj.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvzijxv.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2fblpbdta.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2oljxxdxt.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrvfvgx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvcrgga.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dnivycvc.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbjubho.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrupahx.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyqixlq.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2dihlhhid.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2okeatqrm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwhqegg.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkglxuz.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2nosusxaq.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcrpfcd.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2miszudul.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qtevguwm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2upwtxucu.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2idtpywhs.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnfnypf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jiavqvav.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2crbnobpw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiguvkr.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orfrekgz.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlyxovn.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkhrdbu.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdfcwnn.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2idppilvn.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkqflbo.html


<!-- 参考信息 -->