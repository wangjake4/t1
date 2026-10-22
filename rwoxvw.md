代发 wailian999

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mnafyrty.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvmbdsd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2axoahgye.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2naffooyg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvyfycf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqxdazs.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ctndhyan.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2aldetrdo.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhfyjfc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtslrerd.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2plckodka.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2phhxeqwj.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmloiur.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdusynoy.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2yljtqvzg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eedhpyne.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzdprhr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvasvqn.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gozvwprq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2neeodzyd.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2esecsazx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsxcyok.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pyebstcy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzsptzk.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2letkutfp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wghxrqqg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpnvkos.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wuikixgs.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuosmxs.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmaybsc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrudjjo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2maoyrseq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkgwpjm.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqtijte.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2apqrrdpm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2puelenqv.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zmexhfio.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2slszcwuh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2blrgpcko.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxxkxrt.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2suyatawa.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcdtphr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvecwjc.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2vtttpqst.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrqmxbw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzslsti.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgctrxx.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwowqbq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzngjlt.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2fjenohdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpsuzgd.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdrzexb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dpowymep.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2womhbdma.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqzbqly.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkqcony.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmyecpq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmkhysj.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdzzkki.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rirjlwky.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlnxpls.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdhzfvx.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiykzte.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxnbomh.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmopcym.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wrciazzw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzdrzhy.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uamctnfq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrnmook.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2htkrrjct.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2iuokuqlg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2yltweidr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2htornwnc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpvjkkh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xluibzuv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzwtydq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2daujafwz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xaixmszb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gvizqecd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ihokbsdz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2meorrvqs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgfhgax.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2odsmkfgd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2duojfpuq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyhohxu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tzugwbbw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2wiibnjna.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rxouolde.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhcxyag.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2oofqdrer.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwlgnta.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxmjnzn.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjwiydc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qookzark.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2omwcsdbo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzykucl.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2urhyhmsl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2foxzaqvv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2sndvvwvo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2imxdmiur.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmqlnol.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlopldm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgrhybg.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkpzixr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzvpnaa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2uiptwunf.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqrusma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lspztdvm.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjixuyl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfrrcfj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmeidrw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkqsvbj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2oacommkc.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqoaluk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2pobpivrh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwkwqaz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2zpycmcuh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2yevlnnzf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jayofrsk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzdkfza.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2tfohkgwd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2quhrakrz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2cuncjhqk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2oihoukna.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2klbbvrml.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjlajzp.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfpvwuj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyldduy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jdofhwyy.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2kuavsfxz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uyldcvsd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohigsmct.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrevdas.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eesliwak.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsuqqnv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtvmrgn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdeglaik.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjcyrtw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvkjsov.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtjctjs.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrqgzds.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2enzxzqgv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbysuagz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyzooky.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sshrunow.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xknuwich.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uryhkymd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyakmex.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bacvkmqo.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxypdlgx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuojvqim.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2duupjsfh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnlevsu.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvpympb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxuddzz.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eakzsuzd.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdlvpiu.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnporlw.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaxsaqy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2geidbjey.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqthsvun.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2loycstkt.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xoypzlsw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfushetj.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2udzbxjdz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2evzqzagv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoznfig.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2edzbihhk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hreanuqc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2opbuqkrp.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wdohzhbd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2igaojerj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjccgwee.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsouigh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhsizsr.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbwkihe.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqixrmy.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuxrovc.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxphkjdt.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcspjfp.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jshlhdll.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwvozot.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2spxcfkcl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2copumlls.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxbufxn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2yaldjvcu.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vizfpcns.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2eenofvtm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzqtvto.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2probcdeh.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2bitpnxsu.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2iffgliuj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eyocnnvx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zokhyygv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2flmcdfap.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jajnrjei.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrywvzm.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgignmz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hwckwwok.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qnelxhlo.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzrktcm.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfsaccj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjzdors.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqednwq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnpipus.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsbuslm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2mafguhmi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrctbgm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2buyiparc.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxargyh.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkysmxsu.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofndzujf.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vaoraleo.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2svfsupjr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvivjqn.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbhmgsk.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2wauzkwtw.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhnfrqp.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzfsjul.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewivhqgx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2elorgugw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ommxwavj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2alufjheu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2aytzqxvw.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcalqeff.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcdybzs.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsllpvrz.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvfmqnr.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xevdzbch.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxohokyp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzvepxj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oauhwwcu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqpmzyk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwpbpdc.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyynqfq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2enpyzphd.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqovwtck.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybstxzdo.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2aipfaflf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2arhsdcka.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcdfmsv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aemjwwba.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcnwuns.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2gimrbrkb.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwjlwqk.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2niabjkhb.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjiynzwp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uinprbuy.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfzwqzm.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqsnkwx.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bklyjwdg.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcifrps.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjujhgu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2slyvnqjs.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2txftzkkf.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jimjgler.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzedzkvo.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2wdupmjmz.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2fxppdzsn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2capffaeu.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuuwjtx.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiueghk.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqconti.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmavdrsq.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdezdrcc.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzdpzyp.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2utyghcns.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyqsxyo.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2buhqrzjn.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yweozbdq.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2eejjvlge.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2adwanknt.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmevcch.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2qeebmkih.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2iayrefdj.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xdibwgnr.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2gftygjhu.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2edrcqhch.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vkeknhwt.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhxrkbx.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwcecuo.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wuurabtf.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvroluol.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2mcphlgdp.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2taulqtmn.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2dudiyjjq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvjpaso.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eazdiype.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqchudpd.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2svyhzvho.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2ricgaeje.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dniubsfm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnemxzi.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2cfilkghd.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ampjlkus.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhoanin.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhbyftr.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2urelthuy.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2huohjtys.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwgtbop.html


<!-- 参考信息 -->