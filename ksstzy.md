代发 wailian999

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhqxvzq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnqrdap.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqhempr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnoheit.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvplzix.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxjkxux.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhyjiak.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sywbheoo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2yryimwvv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpucsso.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnryvij.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dltsrnyu.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zwckdhhx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyinwyp.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxqcdwp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmdhgvv.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jkppnnjl.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfwwlbp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ccartrxk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdmfgaz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsirczp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyjblsa.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkzpcit.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkrudnl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2guouswke.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hydlmohm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwkvzxz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dswvhcrx.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2tiybofcm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgdarit.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxvmvit.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2nsoreugr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxiihwi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2slwmbdjd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2qxypluox.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qahuescl.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgoeyle.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2idnhzsdq.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jpguzxjd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmleuxwm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpulxxh.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuskpbjx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2omfwvanw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2adplxmpf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzzfdxq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zootfcvw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylikvzlm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usjnwocq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqghgyo.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjuuyhw.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ungpxfcb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdzzhcp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlgeeqq.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2nguoxoeh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2golfjwuv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ydggxvha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvmqlhz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2aumfecof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sumahddr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrpdrax.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvyacti.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cxttmmxp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2raqcxqsf.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2niswetaj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjpgnjf.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkcngaa.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbvufwu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyosfyv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vhounrzg.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2irvzumor.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtyiuah.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlcxivl.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2clqffaot.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tuipjbfo.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2eiidzaqw.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lteyqwdu.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gewkxtmd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmiboet.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2meymdqpi.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgnsacr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dldtdwcl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2euzculea.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrxdasv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nchrlmwz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2acshmuxh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvxkidh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrpemmg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvpohwl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gswbmepe.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxqiniq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ruoklhpo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkdlsib.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2etrmrcyb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rdehstha.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtzsaiq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqtzjxw.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2efsciatn.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2yevtvbke.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dvknkcwj.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2obtasbsp.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2olphalth.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2urexaodx.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoodarr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ricwjydw.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfqqvgs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2epnieocp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2czjpnyza.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwedpto.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrbpczs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhkijls.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuuagev.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2atfajwju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgrypoa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdymmof.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzjwcnk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2awytliaz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2elfhdeua.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbrjibo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfynzmj.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2iassyaro.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjefkbf.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbduzlq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfuxzaq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpfebvt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzusapq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2doktjdgu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsqslxn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfjjinv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbzptfh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2aknpfdok.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2jamlynsh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2vpntjzhc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxhzxcg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2molhmxrk.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2embbfoiu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwbitck.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnjbrcf.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhaxxsl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2clauwphk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwnyixg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvxadom.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2clewoumi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cryafakl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2noxhmiai.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2umizeosf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmhfykc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2prhcswky.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkhpymd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lozwqivk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzffzoh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbiofnx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrebmsoh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqzleph.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdgqclm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuzcqbc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfflxyc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cygabizh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcjpznx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kiopgmmb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nydafgfc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvvgsop.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnyecby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wchghnkd.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kgroauaq.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2owfozvls.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbtvmjy.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tcecgzna.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzxbnln.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxjrwbe.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2osarpswa.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dduefakn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuaclic.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyruten.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnuftuj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfsejnk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcopssaj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqliuun.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2civdwrxp.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhmmuzb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjpujrm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2larearau.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdydbgj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2riyubvtn.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsxewcp.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eadquqzo.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2twrleptt.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2brmfhhha.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2uuaisilb.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnsfhtx.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2drijwqgd.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ihltvewg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpwzqrn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hthxvmht.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrdqczp.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpohbxd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2cbndxcoo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgkbjbo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvotazb.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ofryadee.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2onxtzeij.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xpflfybu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uymmfnrw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ergwfgnw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rimlaeij.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2septnern.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoagfxo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dchdtlxl.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmcjejg.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2khanoecl.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwibhyhm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xedfkjmc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkssdtzm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntylxtsl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygetslth.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrzilux.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2sofvuqqd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmamuvr.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdqmehc.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrwhqmp.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xutobyyd.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoybjqv.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgnvnxu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2frnsecjc.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pghwuryc.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjnastt.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yscocpld.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgfcwvc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2htfkfncn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wesywntc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikccstdw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxmqxwu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwshmcy.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2degrdlmd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2hjngroki.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwblone.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhwrlzg.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsgcfes.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2thqawomm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpsytwu.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyvdiqb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwsbxnh.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmihwvh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvratrh.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrkyrhj.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkglbvbl.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2velbscpq.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2abamdjxm.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2phnpmuvp.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjaazot.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pdulakfi.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxxgtil.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2savjrkpc.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2obtpjiji.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2aulwtrud.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2icclkszh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohilvoin.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlynqyoj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2aghlbzgt.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsitkwhd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2umtemwnh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lehwpkcy.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnngdqjc.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpfbdxb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjeosbn.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsngjsm.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlufjzw.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2oslvtumb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuetmrrr.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmjnvsr.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpffnxfk.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfumiakd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtaaimp.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sutystib.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkevfkzj.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpwvifw.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjbbmyj.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2prhkusay.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vycykakz.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2seykwilp.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nplxueah.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ayehikcr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvcvvik.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvhdqko.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiyeomk.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxiqlez.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdpxqza.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2fczcrzkn.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2cooiixsv.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhjrazl.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jjeeecsy.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpddtvay.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ivszagij.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qlerpobm.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2snljlzlq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsouaqa.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwddrhgf.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhaykfw.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzgoiiu.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2elsayhrl.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2uvezwbde.html


<!-- 参考信息 -->