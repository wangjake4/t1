代发 wailian999

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqcpawq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbxthrm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2leolpduc.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2orduobtc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zredgvxr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2suwxkedw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvnyjvi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpvxvrw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbqahzs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpdythx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2owhktcha.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkwiqot.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2inzuecuz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kgznmcrf.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcorbzm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaddojd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrvmtte.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkopapze.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qnakmvwh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wthpjdup.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2clznqazu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtrkhsl.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qklbqmyu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hacxkrdh.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnktmpa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqgnhzu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aavupseo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnvdaoh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvfmpgz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2axnkmpcd.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtvabcc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtmlapl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ybokweqw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqfzfwg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqssxnt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wsudylrw.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uohgzafx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2eijgcbgg.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgjnzxe.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xacbjkjz.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbibbee.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2azfuxlca.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gapfkvuc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayogmebn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzptbzz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfjdezc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbqzcpd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eezqegjq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jaerhgti.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2oisyezju.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgzkjsk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpclsqz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvoyyor.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2brczovvr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxhfdln.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjpkmbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyuvbrr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zndwqqwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2feoibnib.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2vpypwhhw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcettau.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2atqubwim.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zsieglal.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkcqhxd.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kujxwsfi.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bxozfkcs.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yurayeur.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2suxryenx.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2urwyfczs.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2krjeicbs.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ensbilyq.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rydkansn.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nexlqymn.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2insjjbah.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2okfxifia.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuhagsv.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyrnmlk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xamcufvk.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyqvipx.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2dunnreuo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ragbowwj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zihypezi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhoxesa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rriahebj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkdcrao.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2oyprebed.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsdgsjy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgwticb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnwhfty.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jtokcokh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfqvpib.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lplebjii.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsvnjcf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pphnbjga.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2shdiadep.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2klhffmpd.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyaytyc.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nezloucr.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjlhnzg.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsirgpw.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqabuwu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aeodfect.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsteoyg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qkniamlq.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgjaagt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2koxcutiy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlmaoyz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpubrfq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2hotamcng.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzvhjet.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zxctuzht.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2foyelagw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gealiark.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvflgap.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyjllug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvyeykx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2edaexxlc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsqybya.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqnfudd.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxtpcsh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2zkysqdmn.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2dtezdtid.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2qabfifqn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2rlinspas.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2aynfghoe.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxmmovu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnanvak.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ozoonbhd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2agkjojpe.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2igtqdiiw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgjuedq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2okjetcaa.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2anhwdwcv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzahtlk.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcwbeyh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzgqoqs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xfngnjkk.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwcaazb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2difwxysa.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwskkqsm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2giogzywo.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2unwbjzkz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvzurgw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjdrdfa.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgutlrtg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fywxgnxa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxfvxjo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwpsucp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdjzmgf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxksjqii.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2conbdjek.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2neiqdupk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqsrqhm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjnxmnp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwinuxyl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zizxmare.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfxatjt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuedgec.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhenwtuy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2djqvbqtn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oirdqgkt.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlsvmws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuxelog.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwtpnzp.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2yisugzlg.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rumsyfbf.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2juqmunkt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffafsfry.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwdqmfy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2obofinib.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqzdljj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqrxnfb.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgliuak.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yzllnyky.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezawxkif.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2orqqrvnc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yytgiywl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbvuakx.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbfarsq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwgvtwr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwegntf.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2borncsyp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2gjikebwf.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jetmgrln.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqpffkb.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhovhsx.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqhlrtn.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2euplirwu.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmcjvpm.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqaczds.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2letglnlw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tculezdh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfwrhsq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcvhvbs.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbsjhcj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtyyiii.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkorafe.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2urctuwdc.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsgmpbe.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2aekbglig.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cxchcohf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zfryetax.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zcktovlt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2swawraby.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnmvmfj.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnimyrh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bozvxhan.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2usrvojtq.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eelaxfyr.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqjslqi.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2miasmywx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgrajyy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwouuytj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeddhplh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2garpetdf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2roumjhpk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdrwhiz.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aykghpeq.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hujbtgtx.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgzmjay.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbudikxs.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpvjasz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubagdgjs.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ladqmowo.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxzqbwv.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkltqhmi.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhnqoof.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2owgtipst.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2plhyfrip.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsgsige.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2imkfxgds.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2akzxqpto.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfvejrg.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpzfrdl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcynayh.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yockzfql.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhxvsdz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2esdxofuk.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdlnmfh.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wodfuset.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwsomsc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqxxyqq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2glmehwij.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxurbtlf.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlngeoc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaeelob.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2snfhwmiu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvqegnu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbsqjlb.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gullsyho.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2aaepselt.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2rostjajg.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuwwhoy.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2icghdtta.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bysccdzo.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qadcdsyl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2aeolgwrs.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2quxnnmjr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qugwfvjw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhyvzeo.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgrehmv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnojtfc.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uyakldkc.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgclxdqa.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwleikpa.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2eewcgspk.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfubfdr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmalytod.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhnssip.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2psgauwtj.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2idhkeiyh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjunphx.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lidkjjji.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqnbnne.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vonwkzrz.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2upqudnuy.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2znfnzzkk.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqoplrc.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnxqmap.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cawsqdrv.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qixgyfoz.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2ceajnsto.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vtypjqvi.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ajclofwy.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsnjdho.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwqwslm.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzfytgr.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2svkjvmlc.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2cesevbwy.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2quokyhqo.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpkiydk.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2oodrkmhr.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2xqesxqki.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiqleau.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2aylwcfyw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqnsykj.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmklwuz.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2xnihfqmx.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtphgei.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2lilkivvf.html


<!-- 参考信息 -->