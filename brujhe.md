代发 wailian999

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2udcclqfj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmdenky.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fblwgrnk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzhvoni.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxqsnbk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkwnrqm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvlgkas.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjjhwqv.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkdfipx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuiabfd.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvigxwc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzdcqag.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwvwlcm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2uogugkpg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2evttiblv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2phwwsmmk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhperdj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqyvsks.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhxcvrn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gigsuzgs.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2eayszmit.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vefysdxf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yiiosbtw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmcqczv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2llpamwhu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfnuznp.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnotstd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tleqwhzo.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbhwvyp.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrylqix.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeccxph.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihezmuke.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gslxmvly.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2baseeals.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hqofdgqd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpuqoxd.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fopngyfz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2apnvtdqm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wipykxhv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjfxghm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmmpyiq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vinrsntb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2psuhppvy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2dqknixls.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rafyacbp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hkevkmaj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwijbih.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtwzrnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ppduokuf.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2imvfpiju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztexdrpg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtuznuu.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2phsxpxvj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2onudupmu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yptdvvji.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wehbplzu.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ryghdgdz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tofqfvwc.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdowpnn.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkstgbu.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qohghaky.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxrtzxx.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2zygjlyxd.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tehrfixn.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2byzaxxpg.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqceazx.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2maqolozj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hexuspay.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdptesd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbdeqpv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuzlerw.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmwyjbh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2clytnfzv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyqfafg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiimxww.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2johevvpe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2uetrokam.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2awvyeyok.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zirudaot.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfuiuom.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qglyfgnj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2muierfdp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oghfjsrp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqbbqzt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kpilhcif.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2evxmtpzx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyqnbet.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bigspgrx.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2kclhjete.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xtskhsgz.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwckvkb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2axmhplzy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2pucttdhk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjduyja.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zifkknbd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdynsoe.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbsrrpv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ptklkeck.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhsyatm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnxidfc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkauzan.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlniltz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaduayq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2meawpsuc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vllppexf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2voxaxhap.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmrrxqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjpzvyw.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2eogafcpi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2oflxcwkh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdlvjuy.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnwpnbi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2beylltgi.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxzykul.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2iljerzch.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2rsudtsft.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2izrtrwes.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2sibbetiv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hgexsztv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmsdqmc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnifmlj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2usmlbfxu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdaxabr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2efdlwbxu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gazirpow.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uwenwcdh.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkcwzlz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2stdjbldx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwvpcdo.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2voxekktc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2edubznah.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvmgumh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbljqtd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzthypb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2antqpnxv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyxnryy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmegpztk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2raylcmjp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsuqirt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqqzhnb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzeiwtq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mswipcth.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2errmkyra.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmgtgpw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2racrvsib.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2njntavep.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtkzaac.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyniwff.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gidglsdg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjqivsn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2evhckkkf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwvjpai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htfgymlg.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvdffmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsckklt.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zywfiehk.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyamrlxd.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjgxlad.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jialgjtr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2qedukpxk.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcjgfqq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmjttws.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qldqokgm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqfkpez.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2dskgkxxd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2etjqfzxz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2shcrtuiw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhxsujm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmjofuc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjithdcx.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ngftozhm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2kofpgvbm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vamnatht.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aawwxall.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2yegwjbcn.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaxjedi.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjioxdp.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyxuesm.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyiresa.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnnifsf.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2zavrdwxi.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcxafek.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwogxke.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzldrdks.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2layuumuz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2smoufdoh.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfybxph.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ksobdgzq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuwprvy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaxrrjl.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfgnrpj.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2powtjykh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkrtyin.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrztxrv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuynpgy.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpzmoxw.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwkjszn.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbfynrt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfweroo.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zeozpudu.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qawnylgl.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdyihiq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fawmicbj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nattyjqd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdovvffp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlhgkql.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2sssobaoo.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpgagor.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkkwnnu.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xoncpdiy.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrdiucn.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkfibpp.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwpzihc.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzksqbs.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdccdtvh.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmxvfgo.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gklazcnc.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlpwdls.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2umaptlxr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcdhuwc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcslazit.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruafkbjv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2luwvyjik.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dryoknuo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqrdjwf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ppupcdwq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2sybtqrfp.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2knpujill.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wflgkigv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xusvkvnh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcqlidj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uchbqcej.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jflyzlip.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2dppwrrle.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2puvvdlmt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdafrimz.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xefgytpg.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wraywdda.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2padvwaii.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ssklapcv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rotddboo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zxffrxje.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2asqvfwnj.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtrbirz.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxbscsb.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2cftswhja.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qolwimeq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkbefmu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfrpmnn.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaqolpf.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiaijhd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgpwzjq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bznwpptm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2llqedcnq.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ormezise.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrehaxo.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2walmzabw.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2jwywivhf.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2elujjaii.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnlzphk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdljnhx.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2umtpspbr.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2snuhupod.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2juvlrluk.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wywdsxer.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhqnctr.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2keihjawr.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyeseqd.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpgzovv.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kktybcit.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvvsdxv.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjecztex.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2amvwulfs.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2adiazgsu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2utaiipmz.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjuxdhd.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqqgbme.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2unmtnoge.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2aznxdjzb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2emvlxwwu.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2colksbtn.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqgieqv.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2uenmbipr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2oixtgwdg.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2olgaynuy.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2nspsrguj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2hayqnavx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bibczggw.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgesgfph.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbjdptz.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2anwpakyw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmhxnor.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhojfghm.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkoijha.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbifuzxq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqkykok.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aablifde.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zqorakpo.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqlezhx.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xidpnwhi.html


<!-- 参考信息 -->