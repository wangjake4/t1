代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjvfowx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2syybomsf.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkxfkdk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhrkzrx.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bybjyiai.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuvozmb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaquftj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wshlzvbf.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuvesxt.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlkpcep.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2onyekehg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcrlkne.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kwchcyud.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ethlnoto.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaehilz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiqsexa.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjvbkxn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuloavxa.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqzbsyn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yluliert.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iizljefa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfcoclt.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgixjgj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2byoxfxap.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2igulgbjz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrfdlum.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyxmpto.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpadrjq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mvudwuvy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvgdvwf.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpiuuzv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtlbrmz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mhitwzhp.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kyssjaxd.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvselmq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjdizfn.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsvvlvx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpinwey.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuudviw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvckqeec.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wjoaogqd.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhiftgz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2sivvvxqj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqlmbdy.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmgfnnt.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxkxjyo.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdlctpw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2vgufusej.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2eamptdmr.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmqrwsa.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2lksquwyt.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2uljgaklh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvzazpa.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2hehqkwho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdjmlbq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2bwykutxd.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhnjkzw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2obuftoir.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpgwdhp.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vboijfhe.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqwresv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzxypnl.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yiocasfr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzebcwu.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wehtoanf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2azbuyqlo.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkjvqfd.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2qngdttkk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrrldym.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwwckdv.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwnjkyi.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2plficxgk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2znlciuue.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnvzphs.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qceaqjny.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xftxtjyu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2huveyufj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxrwdtv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqmsjug.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmfxcqn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdikfim.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnbvgjp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzsgylt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnbdpzs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2arprittz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2iepaetlx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kghqqmwh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2joqilwbd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2koahztrz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2laxdomxm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhfnaeu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vgctwkou.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2prmavruw.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2vxclzveo.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2blgkofan.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2awjrjpow.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxwfsbz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bszxldif.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hclqxvtx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgwzsku.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfboinq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bplrlvlb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2mafslicy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2eejiqrsm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rffbvfqy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2irzfybgv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wmihdcpx.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgtotvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abnzfvda.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwselxor.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2kmosetqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsialyhk.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuudgok.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rirdspjn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2htbhutgz.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jeubklsa.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2foculkbz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyeknwp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2sddcxthh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2xvopnujf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyomhco.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxxqnuf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vtavgrzg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2atzcxexh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2lupussor.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ruflssrw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ufoajfhj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcaqcre.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmbvndl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2kptxzwrn.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxucdgg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyhlezr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhofkii.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkmkysj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nlusbhmu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2feplgokc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcsgobt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2faawxnrz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsywjjf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnhtqhb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2khifbses.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yshllatr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kohvbgyx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmflago.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgpntqu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fehlmoxo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oszqpoux.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jetdjhzk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmizwzyg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zklfxanh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdnqrhg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwjtutn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvounrxi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcbpeja.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbpjoti.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2clretxjq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2efvkalbb.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhoujtg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2doegwazi.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdohgcp.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2pctlokia.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xufmbxge.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2spskieop.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2aibmuqmn.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmusmbxm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2apodtukz.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2johvuntm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2raqqucya.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxfddea.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kchxonzj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnyxmbb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fauozfgp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2itlcylpq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qomecfqi.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqikuer.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2sodezjmm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yocrljeh.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfnoetr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdvwwqu.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgnamew.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsctrzrn.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlkveci.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwlavmz.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2eilggbne.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xulzukpk.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrxxxrq.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2opzhkmfq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nifeathg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2blvfzhyo.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkqwkdo.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2josrllyd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2fainvzjo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2thriiund.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2diyprfcc.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2kncnpzdd.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2yldjtmbr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjcieed.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrygogl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aenbakjr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vrowdlhu.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcycqgd.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2awykeqnj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eobgsbel.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vvynqrez.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeadvfb.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2iukobrup.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2knfcwrfc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjxeswb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhevways.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvswgza.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyxwets.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhcunbz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2nytuqpss.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpxsxxi.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaclrmh.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2aonasvyq.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmalpdhv.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnzqhef.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnppwvxl.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zobgznao.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gllmfgra.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2imqwvvty.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2gypzdmug.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbadfgsc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghncvreu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2adocvtlq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzonhpz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2likyspbu.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuflhfcp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjvhwih.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxamvznk.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtbwksw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjiijnh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjnnapj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggexkwfq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrwcxxe.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2flybmdlw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgbltgm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgkenok.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2winguaur.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqucqhlk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdudawin.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2shimguca.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2neyjaffe.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaxkqyl.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2phgicshe.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2vppjhjjy.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzlcguo.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdckkxto.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuuotzh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpfveas.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuynslj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2aaekpctu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2teoczmom.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjawhwph.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2itkzkrqt.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhcwrtv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdbhkpe.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2siifuqtb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2arinkpcg.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wctmkixe.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2aocbkdxc.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbuarfv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdbgens.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mulszzwo.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpgghke.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzyvwgc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnootmqc.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuupgrg.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgebuue.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2drfgmiqm.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlpdyvm.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hghbrvwd.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqfsbau.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqywern.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2niwubtxa.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2toklmvac.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpeaxce.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ooririqt.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2aajsmklt.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjeatnt.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcnewni.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbxnnum.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdshzfs.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2lskqhbvu.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvzawds.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfqahgr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2trzjlmgc.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnjshyn.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxjhkyp.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2cphvfgnz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2onrdtkty.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxxpioy.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnijhwv.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqekyyp.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtyfwhm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrguqnle.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzanngr.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cilkeabb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stemlajt.html


<!-- 参考信息 -->