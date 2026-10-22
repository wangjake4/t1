代发 wailian999

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zzllxqui.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfpxolb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fynmdwts.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2neydkvbq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxweqlz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cpypvoyl.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsddbxo.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2typbdoeu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oyogtwkh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlqmnqb.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2oktzlkwz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yedyfpvw.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qndxeahf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2actpbzmb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2faufncnj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2njtdwyxe.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hamyzdtr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rqikkhyk.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oqonzlql.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcnujko.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkfzprm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfefpzbz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdeyyul.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2twkyjthe.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tgulnqvu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2twthswqd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrznocd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nutbndst.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmtemle.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvkcwsz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhljriv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxizvmag.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lriydrvv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkjyhau.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpdcuar.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuwxbpo.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxujmxl.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sddmijhg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kefjyypg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzohkzu.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wxewdxrv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlwgebe.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2egcqzbdo.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2amaojpeg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnvqjvc.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkdyscz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzzixsa.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ekezmcrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fugaqpuq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2pgimyghm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2anhzfjtz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdfcpso.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2amsjiltz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzcaxao.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fupiidrq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2azhzdawk.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcknklu.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxypqly.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwojbmh.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkngazo.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxtekty.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsrwicr.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhsxmhh.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2sgirvjar.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dihtzxgy.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpkfobk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2urfybzgr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lguzjphm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qynzudag.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlugyem.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cnamsrob.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgmtdmf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2utmazamr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhjgbnr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgniqgn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ieabmthh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2fzssausa.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnwdlfb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vtalaeoz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rdybnbmk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2udopvuhj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2eibmlxjm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cboksjyt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sxukyqvz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfnvcle.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2adsatqgt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnwomkf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdvlqyc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkcutmw.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2kzejynoy.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2elgjrogi.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bzljquuc.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkyxiep.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cglewxbv.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gejmlshk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mpipswba.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhawdjk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcviyrp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2qddckiqu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2alwmqkka.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xklkzuls.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2awxxxiwb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2senrvqha.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkhwosu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2akihsbzf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpspakk.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2clzbksmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwpagjx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2chamhejx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgexcdh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2nwspndrr.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpgbnun.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxyndwn.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqitsvv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2vipuvrov.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaywste.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxwsctd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoygnux.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nivdxbep.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtthjbn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ceexzsts.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2zglzgfrp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmrcylk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsrksmo.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pynlhouo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvzboml.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2umctirsm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2hheymzcd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xqglebjw.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2efcosfyo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqwhylo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2epfbiohy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2skuyppof.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwhgsse.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjegzhdc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxisjuoe.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzapsay.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwdalsc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcjuvpc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvcblyg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiumgdm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdiwnxn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkijmvx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnjmttb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrgtoym.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuevygl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lytofvvs.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2phpldllk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqqmorc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbucifiq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdasubgc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdncneub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eeritlxc.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qticznwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yimufjbq.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aenmuxyz.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnzinmu.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cneylfgk.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxngyzem.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzywcdba.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzrhwpa.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2idaogvcw.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlbirze.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2toqwrmhe.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2didjnzaf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsdkkdj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2otdrfujq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfgrqnp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mshvbgfo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrkqezb.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhprmel.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2zhigillj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2azhcquee.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kasviihb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjuehjd.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhzeyld.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlpcxgk.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2udvuurtr.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2myezwprl.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2cqblhfol.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qenqindl.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bruuvzuu.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlohbxo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgbdpus.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwervppd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2adsxirgc.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjkprcc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2opcsidxj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdbywvu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2pniwqbvr.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2shnmlulx.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdswrlx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrmnpoc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2elqgoupq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2blmuijoy.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhwwazq.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2grjpywzv.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvgrtez.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nehwoiyt.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrizxzy.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fezilurk.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzztuydj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwcstec.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzwdhar.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoveqmyc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyeqrzc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqdhwlv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2awkzpjdx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjxafvw.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pudfumyh.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nezdhhzu.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziagmnoo.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmrhkmx.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vprtwawu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zglhodzo.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2casfeunt.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyvlzez.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtuboty.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2eulignum.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdyimaf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnquqstp.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoimgdpr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgzdfsa.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcntkco.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2igizxpvq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvndazg.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgjkhed.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeoxpom.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hivdidet.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsieumsv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgociba.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2elaezfwv.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwsefuu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2skttzjpj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2kyggpflp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhqunjr.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygutsgii.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2uovamqcw.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyioapr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2asfyovzj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2orhaecaz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dakjdenp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2cfedbhko.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxichem.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvealnkk.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcrtxvf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2zaktstli.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkbnccy.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cumyyfvy.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vakfsjld.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtqsstw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2djiccnwu.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwejlttp.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbttezf.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fadxeqcm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjifbzow.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoevhxg.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhupxzh.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2hktwcvbo.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2udepvezw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlyojoi.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrywlvmi.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxhqrid.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeeizyw.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bblrigkr.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2peksdmct.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2azdijsvp.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2enakiasa.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwurvhlg.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uksotbwr.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlvxpae.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lropektj.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2apwjxcuz.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2vyopweyp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvoaihd.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyeqgfv.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2awejjlan.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2wprhpiej.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2kzeabsps.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2hibzpxwv.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcdddic.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bamozukd.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnldzgc.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2obixlbzm.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2mqoqkikb.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbwbalk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpotzbge.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2allyxepf.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzoosby.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsmemql.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2isolrlbi.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2idehfone.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcdoffr.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pkouhajt.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2klgpwiip.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxyzynk.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdxydfl.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jovnwlne.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqzjizy.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmjikpg.html


<!-- 参考信息 -->