代发 wailian999

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oueunmad.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkvopna.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lybremkr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbyxwus.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2juapahqt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2sucrbqbt.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwtoslu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuaeizz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iejyxzgv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fclrleiv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aswcllhl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2klmytyxl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2nadkbjcr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhepmep.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqfhehl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2indolcli.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzqzpzn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbuemfp.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rijnjspm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxtdqlj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuzjnhq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhaamsv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ydncrbkj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtltaeo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuemnwb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pttjoobl.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tvppqfzm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuabnch.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lpezeens.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vugwdjrw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdyhjwq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fytfrkxa.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2igdzejqu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zfokwyiy.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2shbuhzdq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2udznzkrm.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkwvsbf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2thifbvey.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqighepo.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2sujtjqvu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkivrzi.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwljoda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svhfzthy.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2psaneyou.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdnjobd.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2npnquivl.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2syerkuja.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbnfnzm.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmqkrgz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zuroksdz.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbrgxca.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdgcmuh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsmyinu.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqjayxe.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnxpsfp.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2scrduegp.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2iovcdfag.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwxanki.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeyfpbw.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpmceuv.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqtybeg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2stjyfadq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfvrcwe.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwrxrwe.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jekatkbc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ktevozcp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2whmuvhxc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdzaacu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2lkieuezz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uobtkpsj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnnirot.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2krbgahht.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrmqmtq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2paxmucfi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zjldmogz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tshrtqlp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaelupk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhbwgtw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtnxqal.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iocbfybv.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcfoozr.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyaengy.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvpcecr.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2crsvbrkr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdwmipy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vespkdhw.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfhnpoi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpbzvde.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2erolercv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yailqznw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2shhughgi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsozkgj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvtrziq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fkngnaqr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjypnil.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpgisve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhhimye.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2sojysjkq.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdgczsj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stegprkw.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2pkonemby.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpnobpp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuymnuj.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2sbatedly.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2jspqscdd.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2bfngqdyz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2lgljlunm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2rsetisha.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2tplwbqya.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2maitvkdb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxewnno.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2allqpwlr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwbwoke.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqwosfo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2foffmrvv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2fngvvrbe.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uhieuxzy.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jevyfvzx.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2klybsgjz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqibxil.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxaxocc.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2eclmxqkm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzjjoag.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkhdqcr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtsywpr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrebxogd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yiroifcb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bphlnuku.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cryxyrfq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrvulto.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mroqkyzy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bprggrep.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aekudaei.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qirvlzjg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yadubooz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhapobok.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfexsktu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2scpkuidx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ootabhiq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2axsbgxaf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kniarisn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbmcxdh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2snjlhjzd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbnvwpx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blgdrxsh.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2idrvmmwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqfrpph.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nadbnfpx.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2wacmzgzs.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2oqeomete.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sunwqmgf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkabvhcj.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2plnreahw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2phuizrxl.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2snnfingz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qudlmsyb.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzslipw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbgoway.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2iixxvxgk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjkvmgo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dunhhedc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtkaiin.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yrynoqfg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2kuabfdkv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqglcciu.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2psghwueu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdmbisr.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkmypuq.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhjukil.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbyboox.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwgctel.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyjlvpo.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuxoblv.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcodwddz.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2efrhrpak.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzlduny.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvefvkfi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaouxka.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2fesaqwgp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2gviqgeck.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwknndqc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2juralgcs.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2zochyeqq.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2pzymeoxy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lqerrati.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnxhntg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2csnqyior.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqtbsvj.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiadxrv.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mghiaysn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxvenhu.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2prprhumi.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iowhxikx.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogswxvbl.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkxkesw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2taxwiulk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ellyvbpi.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpblvbje.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmejedwc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnrjrcd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvvbgna.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lektyrbp.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpqfgbj.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyidqgt.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dijeorvz.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhgzmbw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gixkpoqn.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeglecyh.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmxbeps.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fknxlvkt.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgswmwk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkcjlwr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2boracsgk.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwyhfwj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwcewyr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsfwjjx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2evskpdtv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2onhmqbgr.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqaipbc.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwotxuj.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvqkzsm.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwcxakb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbswrmxg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhlmhin.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uryepygl.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmbcrns.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2oaghhqem.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlaihgr.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2aohobape.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwanxkww.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2ednvdrbx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2avlchjmt.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gskadjuj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtkipno.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2fssnetiv.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhmtptl.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfehcjct.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnwtyop.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2deubywra.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkzuuwx.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2czkbzvli.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbtoizy.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyacypyp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqeckor.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiisfuy.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbsfwjx.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpjamun.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2prbnjuzp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2obpitwxm.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2shyzqnab.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrcbnmz.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfwugdu.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hliplxtd.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpopdyib.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2abfzkyhq.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrccmifa.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wblnrkee.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlodpwgr.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwnfkjc.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2iltivsjo.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpbiljs.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrfyfbo.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvyczwo.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqpzmsd.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wyotjqbt.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2utmcvriv.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2otwzvjei.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvzptyl.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2acwejmem.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2nevbdzcv.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2twcjrqai.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxcpcgq.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyjzons.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eujzfwsc.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2upvvywyl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsmfxns.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmaxrew.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxabnks.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfsnctg.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kshonbry.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2eagiwlfs.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxhlhsr.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlemvoc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2takgxcfh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgtownv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxjhknk.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtxhdqx.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkngvhn.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uteipzfn.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zovielil.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htkwtzgh.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpzojng.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzliymy.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vztjcmxv.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdenfyo.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2prljyztu.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yakoiofd.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rontfrgs.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kkznjufs.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sprgsido.html


<!-- 参考信息 -->