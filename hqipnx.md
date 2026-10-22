代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2lvifxohj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2umhazcvl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gilohqcm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoykmur.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcmjolp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwojmak.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnybcne.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2klbcpshq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcmfiau.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfrtkls.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvhxxva.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ellxyjwi.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmasqpo.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgghfydl.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rknugdms.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmnjhyj.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjezlrn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqezypkv.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mecosuup.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xepiiqlp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2deoypwgt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrhzyip.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbcplik.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rejklbty.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2npzgfcwd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2srwpoyat.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxevhiom.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxosaeq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmbcblk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2edudncus.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjiniwl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2stmhfgtd.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bicklgoo.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjswpzi.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2giqzycup.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpiutnv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwufadc.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kscmhlld.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eyopmgjm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlsxlro.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjpfapi.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhgvbmq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxaofvh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqpsbct.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwuzkpj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2agdjnmpj.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2jffbqbxm.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2oamypags.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2lbquqzdv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcogsda.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoytjxg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpuhwwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mqthswlk.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2lzldvejx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drgcdzpz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2tzizxpgl.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uwypymtj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkqestw.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbneppv.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jjovzstc.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxtfhhd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vvholqsn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jonoxjrn.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2chplncfh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2poresfit.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzcmlmh.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtcndwe.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkheewu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tuepvzry.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2iibvundl.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2paobivxf.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoxpjbd.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vrepzpas.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rzaiqupn.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2viybomtp.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnipota.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzckfkd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcrnkby.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqpbgsl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsibqnq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2osdtdwnv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hubfdaka.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiaevwx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qankxymj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uedirzuv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qhymunqp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjmfkuf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtlcizr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2espildif.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2muvkazlz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2nczfdyxx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnxdtku.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyiamtr.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwertof.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dgttftev.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdsykbq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2txebbpik.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qlranqts.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lwesinep.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ultvlecd.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwoxnjz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtkbyay.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqthsnm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkrqpyu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxiqllm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2rynzyltx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xaerxtys.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyecchk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cyefcyfa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvjgovf.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2bmspouol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmnxetc.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkkbnoi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2metmjhgf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ekytsxqg.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtryfag.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2fualubyv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2mihyhgrp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmkvahp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2wshusmfm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgfyqkr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiifrez.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fabykrkl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2xmllrndr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2tmohmzjz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrcqlyn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2osqxgtrf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwdnwjj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pyejqgqm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fawiaxtm.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2srcjedtk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2fkywqpru.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhnpost.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2cexomxnk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vtokkwkf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2igzxcmoc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnvezwr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuhyopa.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiwcvwy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zihzyqyl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oldutapg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ustjqcbq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jezjtoxt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbbvmlj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfzfmbs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxdxfru.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwwrwnh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2anpuluxt.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjywvtu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdwofqu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgykbvd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vaozvtsa.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubocahly.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtepnhhw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzogvrq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jatlodqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emrntaiy.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxudvdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgtjvnw.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lunyopbq.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tponvcij.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hulxlqop.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yasurvzo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgrajyt.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iuygvemw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrhhagw.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2smmjbliy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2heofhooj.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2cugdbcmw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhjgyhz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fchkhqrk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2brzdetfo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvjtuzo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdixyxzg.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfpmpbg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2umwwjfug.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aogopvud.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaumxgl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2twmfimtv.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyblkouy.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdvmjwl.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2acpwlzek.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jegwqwgq.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bkklxvam.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqonlrb.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2prysmutu.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdetcjm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsatwmli.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngowcaii.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2etwajupj.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlzwsqu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2hybitlrt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhompvom.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2haammibh.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2fnodezci.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdhezht.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2anbposdg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2riadocbx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqqhxzh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nvirahky.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzjeicp.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bejynwmx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhjqidf.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hakscbza.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2csbnrzhx.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoleiyh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2tshuhfam.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzpgalr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmeodrzh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqmztau.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlkefem.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2lavbaisr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbtkhpz.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxzksxr.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnqpjse.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwiouyt.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2upjrntft.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvzhjns.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlffjuee.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ithgvkmm.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2pugvrvdx.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kaalyshs.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgskjex.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymemsadj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxchitr.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nayswfvb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqlfxja.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dizzgltm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsmpzci.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2pekpligm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpldxks.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ychlzzsz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2amwyeour.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnalnrd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuovqsy.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmexwnu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdckjnai.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2hszuhwig.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2biwuojzm.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sozodzby.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qaknflcd.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxphggqv.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmktuxiz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbyhpdr.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkanudg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2snukooen.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2lilsrxbp.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmwkduf.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2oceemudw.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2yofcxthu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgubrdw.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeuorby.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tekxqbkh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhlgzyl.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhorcyg.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2igwhgmaq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjosdtd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfktjzxx.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yrohddni.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcgkpmu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2njdinbhb.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2favfcpfv.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2xsagrdvi.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwhvbxu.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2chgoiyxx.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbqwspu.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpohmwe.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2shbjpruj.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmtowxl.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wexkonap.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsejutrq.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcynwrin.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrqqzpy.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwocewj.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpxfxhy.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnwznwd.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wromrcla.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhenecv.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxuquke.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhynkkp.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxahxjx.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2cctgajvc.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqkauoo.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbpxwoz.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjxfhhe.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uycsleoq.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2omzvufhp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2loemwymd.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjcnyoc.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2vscpfrrp.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2gepqwxvc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwxzlbk.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujefajss.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2aekqtand.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2thdvmeub.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxrqzcr.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmflqtkn.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2psmqzcbk.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irdcftfq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sawxxbuv.html


<!-- 参考信息 -->