代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2geojqaps.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gdddpppr.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwqlawg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsedxkvw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfhgggu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2doazxizb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phmbcqqx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2opuubvtm.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2pwweosvp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vzngsrmu.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hbybjcyn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oizuione.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2fmywekqe.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqfaijv.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxsxaen.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ziurmqmq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjrvfet.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlcchld.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdnppll.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmteenh.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2smzjaakh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaosxmo.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2havmhcbd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2awhmnhii.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2smmhxayf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2llradbhz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmcrcyb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2raogmssu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmsxvhz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkjvgza.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gyosatkn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2aezhoubb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtpcrdx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlznojdi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpivxbzc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hnalutuq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwmpbma.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lotqtifr.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ryitxwnx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2awjruxpy.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wicyxuft.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2znnudkit.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2qbofwjeg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpnznzb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrrmktw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tchblonl.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sieyjhhd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2olxuovpj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lprqtwwh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrjpzod.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxejbcdz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcirgfh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vopwacxj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2chpmhapv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2utaklkyn.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2vihcmhmi.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdkobkq.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rftbmpin.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2quziarqs.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2faunsxvp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tndgatdz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2riohnsxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bagqtlui.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2luckpops.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2awblbeys.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yefomycu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnzihst.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qghysgjd.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzzasbs.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jzplgdln.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2khrxveyt.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sqixlyno.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrvyedv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vghaeywq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ejblfmno.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2okpgqxla.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtpdwmq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbvwxtc.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbyclop.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrfhlrd.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2twlcopbl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uytidiax.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbzerqn.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwcywpb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvmmlve.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jixpxfkf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwpvkci.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2meehjjxy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2tynymran.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrecwno.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2higceixs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvxboux.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbbsesv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kagruvdu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rccdqhts.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ptftjumk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vpewfchh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uptgezpe.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2whlhqgea.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdhevct.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbiymig.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2igirnvmr.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wdybqxju.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qricokji.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhpgyxp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdoibbo.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vyimcwgf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsbzvnb.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2opyrwbvz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2olqlwecz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhehlpt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2pqotvmmd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzpyrls.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ipftnmje.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbccizr.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpztguw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxbruja.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2craanaxx.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2twedrgyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2myynvvqz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwbqsdj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvljdpn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsimdwb.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdttctt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2mzljwzux.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2odfkoyzn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqblgps.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgnbqzm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpxgbfg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrwaviy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfcuzer.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2nipemofy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaaptfv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2emlmdshz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2synvhwia.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2awiqxwno.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2paukynxx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyikgnc.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2xudwbyxj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrgkicv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iayfldms.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmolclt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaofnjz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2otfpbkwn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmolnbbf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pywosute.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dklplras.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjcppic.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxerdhra.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdduoohn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cirzynsw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmizjxqj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zginnnrx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejisknxn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmarpoln.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzsygzv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qteowcgx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrefprip.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bksmjogi.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bijhpqyy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgibfrw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhgbitd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2osxhsnir.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrjebme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gecdjkeg.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsvlbrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kybiaerl.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2djkwdbfr.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrxwioo.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpgfydn.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2oyscueic.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymndgwdm.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2csppbelm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlwnqus.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2trswvqcp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2upeiqiex.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpiflyl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqacizr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jysfybyw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzykdppq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzugmkfg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hncxlrda.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2nkromeuf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxiyzdz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbggzdep.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2stxlqafp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbrbfnd.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzwxjku.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhqnvxq.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsjzetu.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2teticmvz.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxizzzc.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2pffrwtvm.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuwlygz.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jekfaktu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iswsfjgr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcofhtm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmfaqvf.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwihfmg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgqaind.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugprzxgn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbpygzu.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2eoleoqkw.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyjhkle.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnnrqhj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rksezzvo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hxohwntt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rdciwflz.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoljldr.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmglajn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxafudw.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsjxkqn.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnwgcwq.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzylutyz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgrnenj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fegvrvue.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsrcyys.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kocvwnok.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2laaqiwqt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvncuut.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ariugvcl.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kasjappp.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahshadci.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgsyvho.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxbnmxq.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfilnaii.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uavljtgl.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kffwhsyj.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ryntgths.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdknvmo.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqqsxxg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkstmnow.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpvbedx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwcqvbl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeesjwa.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmsonpo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgohzms.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiwmlcx.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2clrwjzgb.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ljritrps.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjyrezr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjrtryf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rymgguic.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmtvbvc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2evawncsq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjlxlyi.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvjormt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ronzfnyv.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwxuahk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhyxtsb.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnwijja.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcuvqta.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzzlztm.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tidwgncb.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2flbpklsr.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2fusmjzbt.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2shkalwlj.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujiiivtk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2blpuwmvc.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2artidwxl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfyfwfl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2udfsznec.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzrmsej.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2conjanrr.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwppjit.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uikvorru.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmyjuuu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bimrbkjg.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhlbvcr.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxhxllc.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzrrpuh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bltvsemj.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekphjupw.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qybszjwx.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxpubil.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdwjtrp.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvumwlxp.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyohnwx.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuoojqi.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2geiskmgt.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2oiaynvxy.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmqhhxq.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2awwjvgti.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcbsijm.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdjohpe.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2xteosgpl.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2saxzufuk.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfahfol.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ewparvfi.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkzkqzl.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mezbnmdg.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2okjpcxfz.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgmngqc.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2snysacbc.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ieezxuiv.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuwzmse.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qmskrtad.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2veiklzax.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2eioahbcd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfskthb.html


<!-- 参考信息 -->