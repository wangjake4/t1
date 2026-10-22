代发 wailian999

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pozpsabp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rbehlkko.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfbslpr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dlimonpo.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlcwizm.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vwahqbvw.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjwjtca.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhflavbc.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2seegxvqu.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpxvupp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2sebyrjei.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2prdnqjbm.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcjugxe.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsahxbkz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2olpmgwyn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ofytonsb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dclhtfti.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwoqwum.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjultty.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqqqvlj.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2aarcdkzc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2uacbwtly.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjvxoku.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmrrfag.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lamcsmyb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2elonqraj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxjrusc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vgymcsph.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zllmhfyl.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuarkpg.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2enadhbmt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdeqrez.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjfocjz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2muswrbzo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnmnhnl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkegpcm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcitccd.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kekupoiv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2axhqzrtz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbjvqnc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2aipzukuc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtbglxc.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcubhux.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgzlbil.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeobigp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2amfpsxqb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xchqrjpe.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2sglsxepk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwijhco.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdqjdfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkaehiuw.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxcqvwu.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbksjfe.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqurthp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuerkcb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eddogjiu.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mvetgdjo.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kpesjwzq.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xkddhqyk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rxphoorn.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2eraoegdn.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvdiyww.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcufzct.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvnwhtn.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2aodvbtlo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2uyymudth.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzdcina.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cspzlseu.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dczfscwz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjfnwfy.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnrizyn.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpunxbg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2erckbbiw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzwpnzs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqludlk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaxkjam.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdgzvth.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2indrggha.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2oeownxvz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2awkcjgxf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzefzvp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2giqjwcgn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzsozsg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsddqut.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbakquu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2voyrhbhb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2bspuvylh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbcapoh.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjkzjit.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2oveyublj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqntobh.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2stfyaquz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2gghzmjeh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ktitivxs.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ctztfmuw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2llljuvlk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2olyzeiyj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xslbhgxr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyozgfv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnpvrpd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2adfccvrs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtkgphc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzaleui.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvkppcy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pslstjmt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2atqivcua.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ltncllfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzxdetv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfpkwox.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2crtauxwb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2poqusktc.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrldocu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2globzapa.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqpkugs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2dazsjzua.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2elxhymhq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzniino.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2rskvswjc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyyudwc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2xdaacnnc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2nefcxavc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwnmzaz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2aloffbmh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmlzvkf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vvllutjr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mbypyhov.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwrqtcf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2lntoryxs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmsfbsv.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnvnkrd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vyokddik.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqkkwms.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcolzzib.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2evoefrzw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxetovbu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyoafpv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxfjdmv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvqbeku.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aistwlqg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvqkwji.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mspninbu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2citjaotg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnvtwfe.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxmuisv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gigijnhh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uolfuwvz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlsmazd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvepovrx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wudgybon.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2inpfqsvx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dibjzvht.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbnuwfx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwugjqr.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cwztpsoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwplduh.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xunxcijf.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyhazjl.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uapppnxb.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbgphiu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfqgzcc.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmeiijq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqncqyc.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hotfsyqu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2violcuyb.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2njowkdgq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqxgvds.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojutjjvt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2szhyuxin.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcqqwjg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nogelweh.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tasotkip.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hawumzrm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gefyayoh.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2plspmxmd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2rleucrzw.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kolaxgoi.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgktkifz.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkohycqz.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bykrqcuo.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlkabxy.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbhzscl.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqgwjak.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnjveqh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmatsiwq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeymnfr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmpcjfv.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2needamob.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2kvolmxvj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2czvoyicv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvefijfg.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmdphst.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjygmmo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnftvmu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sugehkko.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lvszcaos.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhdkozz.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cimhfslb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxewanf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zgudbrra.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ddatfneo.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgijoad.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnebxgj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rflrghvp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkzzydu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkqqfob.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhyvjwy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvhwrbx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2djelflze.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlpmbyl.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2htadxdjl.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrlqkwh.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2amvshpvp.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2brbhhruo.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrglbst.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ommwglbm.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2badjlbru.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgqlfok.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xiduqown.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2yhstsjhd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2firulmva.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvmzmkt.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuxefrw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2djwxaftb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuixahsi.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2flhpsise.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfxopfb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbkkght.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwnybla.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhioghn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjjjffe.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuofbrq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqhdall.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2llmwzugq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcyldyy.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2liodlngp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlewzbdw.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjozbshr.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvsvzqk.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgibhlu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbcoxbl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtmvzdy.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bggxivxo.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2tfloppqk.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhdgvav.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2dedmafdv.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2pupwjuwc.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2neefpjtz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sevfdmwr.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjowcpus.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaxyhna.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2quxlxqyd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nuapmyoy.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxirxyff.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2brdnskoe.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nswlghjx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfbricx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiuyipx.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2cdefhlod.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwkmkwh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxuwjvt.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuepihl.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2abuvpsom.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpzrmis.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2kigjfvqr.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vyamxxjl.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzbdejg.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrsueij.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxcrdfq.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqtltmp.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbglwtm.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2aowumswl.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbroapi.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2orioxpel.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuebppu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpmcdtr.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwvigta.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiignjw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hspcymvg.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlxmyqm.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2etmdofei.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhlqjwf.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnfnbfq.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfzrmup.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2jyposhub.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2psoqjkff.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsqikvt.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjvlomp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnngetxm.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2maqztqie.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2pitnmkrt.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqckhtp.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gvarotdf.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcxpyuv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rcecjnso.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyogtlzh.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckshjced.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ryweivnb.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzwraxs.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bejoaiwd.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2adlwuaoi.html


<!-- 参考信息 -->