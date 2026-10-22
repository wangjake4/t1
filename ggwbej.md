代发 wailian999

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kapzjxxh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xiylttrf.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2adymeouw.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2csfkrldf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyjoyac.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dywcoknm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2twowblyx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2edtiusuo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ffildmdd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgkbrbt.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ktovittx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvolftq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlyogdc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2roqclhnz.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbxntlg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jscfyrjr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sihrvcqt.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwfbegu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2zpacjufk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqtpdmi.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2odnbugjr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmeepxr.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwbunza.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiuzikf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2grseswkl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iiibcfpy.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2stdaargn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2edzslhuz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkbmpyn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvcwihn.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwihoprs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2poucqfgj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2blrufnvf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdlwcft.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2eeofixdw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pebrryjr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pydxgmvd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2slcisurm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgbxvap.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pozpjlxu.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bkytkuam.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmjblwl.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kpywwqxo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfadvfv.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxejcgd.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkgewfz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2owqmszet.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avbcmxng.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsbscto.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mwifyelo.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxunnwo.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2knxulxsa.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2oulikcow.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqjkbwg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqghwno.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbzmuig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjxbrxp.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2odbdwbdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jainaweg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdaauzx.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qmflklsj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2llorgoyc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2eohrlflb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cldofpmz.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcyivcs.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2purzzgui.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gliocruj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtqtfgd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qevhjxnb.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2crgbgpxj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mkusslym.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsdteoq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2swvlqgem.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gslhsorl.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2eknjsbyl.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyxlthw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pitrakvn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmucoih.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2apbbepzt.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vzowvkfj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2symlbdlr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jpijegpw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2loummpyg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zydxexra.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2kvejllib.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yipcjtfg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dloyvvpl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgyeudr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfiofdc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhhuvvb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kutwhxlk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzuqaun.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yosawake.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lkygeqiw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2arbftbjr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kpexdins.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2hpaiwieh.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvoxdit.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2swysctyq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2owdoeimy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2lozgeiml.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmjrjls.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdvytey.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdpmrnb.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2atwijegt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsjizbf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvsbzxo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2vyykhbdf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyvykqs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqahgaw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2kxitwcqz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2nuimayvu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iossjflo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrzlfvy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdfdpwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txomudlx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ubldstpi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2pynupsee.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfbihib.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfdiskx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wibxmaph.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2pemyjlbv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2jljkqksj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwhhqgr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzjyokr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2igxqdbdm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vazsueay.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgsndta.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2clxdfnbg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2flkuisuq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqpbxhz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2sawskaom.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsppzvo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2szyakkzw.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2wewtaded.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbgskad.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lgibewfq.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2umxaedsk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uezepura.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcpffld.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hawpwedb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxnxisy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlwmmes.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2huoaqokm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hocdfsnv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uybivyyv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uavnhtnx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfidiyy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfirkjf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrypuqe.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2txqfpsbz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vadvzgsa.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyftbjuc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzmmcbm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxmiucc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxqudgo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfonpfv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvibashn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnjbphn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzvespg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uofkaurh.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoxhdol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucciynec.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2npqiekzm.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeytsdak.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2icuzvzpc.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2slqnvalb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2rizzxrrt.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2aginlhoe.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2sagfvirc.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xghnvdfq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjdigfx.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfxiomh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhtzsnd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbwedvr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnonyocp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2duaqskex.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiyapwx.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfnolbt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaflobj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwqganu.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2adyxjpcc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2crgigxla.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcnttxj.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbawpdmv.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2htitlljg.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqynngwe.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vssykdoz.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qlecvzmc.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtltudnh.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqbluys.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkwxbxj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2girgdcgb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2audnmpif.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2acbtpmqb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2oldhunta.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsiqhag.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2laoyojpt.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhowokl.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgskker.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqgrqap.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lafwohhw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cttbncvu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpdqbcb.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bdadpbio.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2syrqensy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qwukwzvk.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxxemtw.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmiqiak.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgexwvxq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mygsdupp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2oapbccvp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgzkyrn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpicmvuf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrnqflf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2nqclwpkj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2nusxjyqa.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkqqlmc.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lasbvjfu.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wecmzdnk.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcpvqpf.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbyupyj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmwpwmb.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfkpuiw.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxfkuqs.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mndpbjbe.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2zngzsokg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsafzjsw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lybcphij.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzhwiea.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gujwiauz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2aolnuvfn.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tabllifh.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2brajqglj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2piniecbw.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgtmipg.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bacqoiki.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjcvhsi.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oskpotzk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uileefgs.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhdtcqz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2olwjwvwv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfcxbgk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2chmlebtq.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnsaixo.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2lntbxgsg.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcfawgn.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wbodgtiu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzhcwow.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwxuioj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2stzopjdy.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2gokyocyd.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgumcyj.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2zampkbqd.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmuoffj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dekpynrz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqamwdmo.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfvvjpd.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bplhqfsk.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjdmosh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfzwxza.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjvwaji.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2unovcqpl.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2svywifhk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bboerqbj.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeocceg.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzfbvgb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiaddxa.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2toylvrwz.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjoypjux.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2avzvggmk.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcibnxi.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lekludjf.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtivcmxa.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlfvdhd.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2aurpbubd.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgwpeog.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwharfdh.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2priqcpmj.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnimnqez.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gttmbbzu.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2taepgrzm.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2uapzdpcp.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2smqhabjp.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoxjhcg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2eemzobgt.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2krpmxalu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2amijkxzy.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2yptappbg.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxmcjfo.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxlzwxe.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2hzojkryv.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhetguj.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qshrgbeb.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2snoyghfx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvwqkgp.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2esbeeifq.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2totpqihv.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2ztziykff.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2aeadjesa.html


<!-- 参考信息 -->