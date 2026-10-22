代发 wailian999

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kcybmfhi.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpkmokp.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2izlzhsjq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lopuzxru.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfspnul.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2odayqxaj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ajddkfbd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwegcwet.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2robotiyh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tymqlgmb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoopyga.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgxyowx.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrjqwwz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrkrkxu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oncuqnzi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2idwurxmw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvulqyv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwbmgyb.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2azsxinat.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdkxiic.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hghsiuqy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bixmubqh.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2otwsqzqp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sfayihdr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvjkokq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdoqams.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2timibopl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjxodyu.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2spfsmexa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqgmkfj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eftnuknd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrcoyco.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmldjij.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rphvclaw.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2skfilsic.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xpitimtc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzuulrv.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhedclo.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhyqrrd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvctcmv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyvxagi.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yefzjqvb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxbvrlm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2seieiarm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qssfwmls.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfuleya.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtwhhbu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfolejwx.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgjyiad.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2snmqklzv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbhlxef.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zozsjqxc.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdznlxq.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmhwova.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtiziga.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2doyzhsjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwclrhq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2rkweohuf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gexxadtr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kbssezac.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sflttlkq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cozyubpz.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2etrdkhos.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2najnjdim.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2duugnztl.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdlvslb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrijqyt.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsgayjv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2agruwuwc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrmbfix.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuktlqt.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwgwxkr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqejbpx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqllkbr.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdkhtsr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdmucxs.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bclexbdq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlsjosz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2foukyufg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwkkifo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gihugnrg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrksgid.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnbchzg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqgjyhj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2lljiozxj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbpavst.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tutswuye.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhumdrs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bckobhyc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2scmxcnfi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gsszqmlz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xoromovz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qsblkrbk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yvngvdnl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2nznwazuy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ehccvsvb.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmgfotm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsdtmtv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nlodzksx.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrypais.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2awagfgaj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mpstmswy.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsfutnv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yigikgun.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhcivcy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnqqtss.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2sptpjvay.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuutcpa.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ontvaflx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwpjnqm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2tpulxamw.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2knywhvej.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bigtbmgg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzsxfey.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2nlarkfng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlzxbnm.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjiadva.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmucjrh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fososiju.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxnycok.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqxuyzj.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgcthtb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ifibqtgz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2kzittfmh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2sbixzmfn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2savhtccj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2obidienf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfygbdb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hlezwcii.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlwrrqs.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2horlcdxu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzrndch.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jcodmmcf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2brjyqmsl.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2sknujkcg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxpcjum.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjxhvyu.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2etqtqshd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqzpqqm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvifhzqr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2skyrmjqc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2knffgorh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzvwwop.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yskwzguw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwxrrlb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnphawll.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvklgfvg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2igugzlcd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcimtbow.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nladrxne.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnrwajh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhjnqff.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpxiact.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uapmvwmt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmpnpdj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkhoaab.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2skzdgnif.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aelpdtvc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhbhuxh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpcmhkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oygudxqa.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uujzqvho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrikysh.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsqpfby.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxovjgrq.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yamkehgi.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ocktgrol.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjihncbf.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2osazvabh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2egjprxuk.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2juagniuq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nyosrhgk.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqlipik.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2aetacitt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxyunwp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbozneu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzbkoos.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2krnytwiv.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2inrtytjv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwuxpqj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhsache.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hftxwrvr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2saboqpgm.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtscdqfq.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2slfnbuiu.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mibpagvo.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxsibjh.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmuxoql.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbeurox.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fptvhuat.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rliddqus.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuadedin.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2veszvirg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bkoifmww.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ytiygikf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2zzydmnjj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2dehpkslk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2iurheuzh.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwcexfy.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqhiezl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xocjeffz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vmppjfcl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdzhnqt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjbujlb.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2znitfoot.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnqpjis.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2btunrtkp.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sapjefar.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjsvxlm.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfjqkgh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkdsfxo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhctnpiv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2brrccyfb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjldvrpe.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqslymwc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2dpakapuo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cudswsmu.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xjptoego.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnumafx.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcuxrnt.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpblpxv.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfslimf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqpwnlf.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbihisw.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2llbtuaie.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrxxcyd.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2csvbqzff.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfawnokm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdcwufu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2iukkwakn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cabwdorj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2okszyiff.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjpkdxd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgtsudl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2axnhgyvs.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2skeqiypd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovexylqg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qczkoiyd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2glxiikid.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2leuntovg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjeookf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuhawpw.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzzwtim.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gomeigiq.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlktdvll.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2txvsxfmu.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjiidqf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfgvxrx.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkqaugq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsvjjyt.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmgpgen.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhktfcfb.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbbtffe.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhwcpmt.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyyqzch.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2srpbyceq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxwdfgr.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjffzvym.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jghkbvat.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkvbqyn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tomrfwyr.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrddbzd.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpmgupt.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqdljbm.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2opgacmkc.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2bomfneee.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlugddr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dagkxzet.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkttwcr.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkttxwx.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2crgxafsc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2llmbyiqe.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxkupoo.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mywqpazr.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfdljcf.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhstsxql.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sddkbeno.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgbedvm.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2stsxtwnd.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvcsnch.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2esuwndrt.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2mucnsrrr.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2wheshzou.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2gitfdcgp.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbtwwog.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnmzkka.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2khkwxjci.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2flxgktro.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfqdmjg.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjzaedn.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxynpcl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2cbijzvon.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyphpju.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2evxcudhz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgolmsev.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfxpmfb.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2eaucxaxa.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqjhjhd.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2wpebasvg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2erlekyae.html


<!-- 参考信息 -->