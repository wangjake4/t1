代发 wailian999

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aohtnqzk.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkzvnyj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcokotwb.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocatddgg.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2rpovzctg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhnoudx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2opdxeght.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkhqltn.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlttadz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnzlibw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dlolcsrk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lsoxjaqt.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xguzygqx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlujnsy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyeuxik.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgglonwl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2muztalab.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2iimvpcmx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwscfpk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xktdbctl.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgjqssf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2okzvuwai.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqkmcsu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhoyksq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpaqhro.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ffidusdw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2howkmdvm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkusaat.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xilsevqx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2dquiboed.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eryybnce.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcaeutr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlknqtc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2oguswddd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2bruapmgs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfymtyr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2oymimoqw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2rosqbmcc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuglovy.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxpuqea.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dosuocys.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzawkze.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlrucky.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwkdjcg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwhconq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcorory.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkgnoic.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmuukix.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2prwbslpq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2phaljkxb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2csbqggpd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2fzoxsehp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmdhmgx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtoihqx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjddgqoo.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvwiwlo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcwmpvp.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuktiqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnwrvdi.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdnyseo.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qduugohw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cwanpodr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zatqjmuz.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbneida.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxhdeqr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2flzxnwgi.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2irxtgzbf.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2llbsbget.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbdfyug.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2eitucnrv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2laaglacw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2uilifnwq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqxkhxc.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqnhzvj.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2exavwxfb.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2glmurycw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xenkwjcw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uamdqzgy.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xglaxpad.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbrlaog.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jycwkfge.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fgobymht.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qapvwadm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlmbqed.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2aigxqkrg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzpfosv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpdoidk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2turaalfd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kavbcivr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2moqcywtq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xtypghlg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwoyipu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmuanco.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lysezedq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2lundgjjn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrazdfi.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2iesgfcvx.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2sboverfe.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqhwdhq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2txgtlxtz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2dboimifn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qlifhfsu.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fflgccqp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2awklborz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2mskydpyz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qshbhujt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vypfljbb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2fezypztc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxvsujm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2rghkjwas.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2kjflxfli.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2msuqojnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eprgjyfx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdxejhf.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmljaei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eolhhzqe.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2whflbxly.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2qauxtbwr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbsbgxc.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cdceairv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2fksegcao.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzmiwtg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2wakxznvz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ubametxd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvnxrah.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2jtduhenw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2byfyndjr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyeuthl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnpoccd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2pfusdysd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzdcgew.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ttohwtgl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2adncnjdi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wuecqaem.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2abbmjlre.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdronbw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqfaixt.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2szmwgdib.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2riwunzce.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzelgkh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxijnio.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcenzyys.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoaaxvs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dphtmuha.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2futfoovn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lssbaewi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgstiyit.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2likrgpld.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2omuyjcbg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqfpvrl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kraqvqaf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2opxunpsh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxpmswo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrxboof.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqtyciy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiaypyb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wydewuxd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqllmaj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifruzjvq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdrhgif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsvxpwm.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpujmjf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tywwaglo.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2miruxrub.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkoquiv.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2karauhwc.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2drewpbcl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfcazur.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2msiqknev.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsvggnb.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtvstvh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2efnhgzha.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2gntweogs.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jkptwclp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdportip.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlvudnj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxeslft.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaxgmoy.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xelnqinq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2nytguqmo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2htijafqy.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2owutijni.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2leksutnn.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mamcqfld.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzmkclk.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhlhndj.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghybmryg.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxpzriz.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2aonffeop.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjeulbf.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ximzvuve.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdokjdvk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2htxwvgzb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2usydlmsa.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vitwptpw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2whzhoduy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxecakq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooygqgiy.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbbkmzh.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbwyyxo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdvanuq.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xljplwms.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2diogbyyz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwccoca.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwttmyg.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2soxvcvrc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjcstvv.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqhqwmy.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2htokkggq.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yccfskub.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nffrwrkw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwggkzwq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2yckqxntc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmbuhbf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2aanvoknw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2myvpxcug.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxuujhb.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmuszxc.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsksiwq.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyvsboc.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aogudwuo.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqqgbze.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyiepix.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdckgstj.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2hialpbwm.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2holtlxtu.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2zuskxtkm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2czwqqnrr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zznqcoxm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hounmsdw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2utiqangd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyeyvzj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvjlwys.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2bnamkljm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yihuxuqj.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbnftkx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xylbzcgg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2abskvqjl.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zusxndge.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgyfidq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2luwphobz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2twcjhnfm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2hpreysrd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkazwhw.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrbjmvi.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2aojvpisq.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2iegcvwkx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrunlgw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yushxerz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfpqmus.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ictqkkyw.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdajirr.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiovkyzh.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtskevyp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbcemys.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvhwjub.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdairrz.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjufhno.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2aiywzuzr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hqakmpto.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoqoygu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxoxaxd.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzgqvqk.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ourtwwag.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyocivw.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsvnwxn.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2njmnlxiz.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmidfmu.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxobzdsc.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyeucif.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqicbdh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2svprgwaf.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkixmgc.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2tatxcpbe.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyugewft.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvawvfet.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2eetpzfeo.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyetmgs.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsgookp.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxncdob.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2icjoroel.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjjaxku.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmkxisg.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ywakeqjx.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rysydhwa.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwuonfi.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2apgpcjav.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2mpowuhcw.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ngafokww.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrafhns.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoodtey.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2jwajvnci.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmsdvud.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkgeadw.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuvyovl.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhgrtal.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2otyoiifm.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnfovmr.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2egggistb.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nlexvldz.html


<!-- 参考信息 -->