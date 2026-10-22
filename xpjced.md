代发 wailian999

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bisnnehn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2suooxqsq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2litqmern.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoenpqw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2udakovkb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2horkrbab.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ltscgjhh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtiacnwh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2umfnbzdx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbpsfql.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2irnezkrt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwqplzx.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2tksvreha.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbuqnwu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeougut.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnukylqb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqkfmww.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2twvfestd.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2sexkfsbk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2omylbugp.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeaabvb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkhpjmo.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcrcvbb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gopauojt.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2itdhhskv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kivbvmph.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pouioleu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxkejoz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cdclarux.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsfotst.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eivcpykn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pnepqoki.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lowlghkj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgshxoyq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2soruyzlj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zifkhptb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlfcnit.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2axoeryec.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeongwy.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfekejcg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rogvgbiu.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdxbgcq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhcbshw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksttvqej.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cddovjia.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsbescz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2eumqfzvq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etaaaqrn.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvseshh.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2eulwtose.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2vefetjxy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjllikh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2todrlult.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoszgmc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2axyssftz.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzahjbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfjeugh.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2woaaxipt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeceuyg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwuxpvw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbaurzn.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrlmwnu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbvaifr.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwllkxz.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzecsdf.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rewaqxyc.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjyilxp.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2huhsnnhw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vrssabki.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxydqhv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxlgrmc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ddasaufo.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2myjejiqe.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bymunhoh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtuvhce.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbbthcj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2smbeeujk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhzqhus.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jcquyjsi.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkaylll.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rljzxwqw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuvzzhu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvndkng.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoevdtq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcuqqst.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vgefnndv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtogtzb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2udvukusa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eflbmvwz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2umbfmbol.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpoyicb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpniwtk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaancwx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtiixoc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2okhdezli.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2exiutvfb.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2xabxqgfj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqmrutl.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyfcpjq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqlnnzj.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2kflkshdl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vhempznn.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvmboks.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aqydkfyb.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2eudvrkye.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoidqxf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ziemmszn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2avixefyn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsbkhta.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwfidcx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2kujiwzlz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvtxbqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqtbyce.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpdvflt.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlkvgfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2natybwkx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtxztud.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2yqafiaan.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2suvgnmae.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpohrrh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsqsgqv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2hiegjddp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2evjywfwn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2swrlzbay.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2evmxqwqr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvoomjf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lzauneah.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvbmvrn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2adfhbtfg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2klhudgvu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2wviyypot.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuvtvfq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2clftsehx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2urmggtjn.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjrhcsr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoiuwox.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qlthlvih.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2xijiyuvw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwdlhmc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpauzjh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqgmypc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfwznrf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kayhlkss.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwjotix.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybersopq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wernsgph.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmokkhoq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpuilvt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvptyshm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yletibui.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2anjpxzwy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2seuewcvx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lilpzixg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdgweof.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pztczbjg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2osvrgdkh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpitcxy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aivfqzzk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeixoqc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2utnoizco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ceysjwwo.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsgspnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqesvnhk.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2isautqyw.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2scehhoaa.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpczmqi.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsowhxn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtozlyog.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxncyilp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoyzvbx.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqlrfia.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2neiesolf.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2jzejrfsj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkoifvd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrunvkpo.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnykyyd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2buqdkume.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtphsqne.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2upakekgy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcjtzuk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cevqpfcb.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mknnnbrd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2keysuqxy.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvocpbi.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuexefo.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpblkew.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyrzuyx.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2phgsvadk.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjanzms.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2axsjueoi.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ripbsmya.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxgtnlz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2giqsjuej.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2zigmafxx.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2tlodekcu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2jogmyruq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdblvyut.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqvrhuw.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsouwgw.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbvsnhr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmntlyv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbngosn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvctcug.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2muhvgywg.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dgatxdkx.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2esdktmjh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dreuvdct.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rwagzajl.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2alujqvkf.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlrpxgu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxtbivj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zckywmlb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbktsnmg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2avvkfflm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbhiggk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnwdsbq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnflboi.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gremvxrf.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmybsta.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uatayvhr.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfokgyt.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvlhgdf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsuajew.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2owmphsts.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2jgducnby.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtiscop.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2blhythev.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2znchzsrc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2axgmtdse.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnliomc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhkerdv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcwyyto.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlbvjss.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzdiqmi.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhxjgvu.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvhlreq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mebkjecj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2axpfeicr.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dchpiyyh.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2slrcwlqg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dawleotu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2qllscxkq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2szyoxthg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvplxwn.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2whxpqlpn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmoftoj.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkugwxan.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcslryp.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxjlkuf.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxxflmm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2dqephovb.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgxmryq.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrttjzn.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjqojby.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpksqjhu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2aurhsgik.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwuikit.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxatzbb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtliouhx.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nmaxoojp.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmltagc.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhodlnu.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyxtkzp.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyfgefk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oelqitrg.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjuaree.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2lfibfthv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2enrljkfn.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgvsfmr.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yoovieim.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hslpunei.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbrcpmt.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzygljv.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaatrue.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2immryzqu.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyayvue.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2oeshajch.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkdrtby.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcsdzue.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpclyle.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdhlgpw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2niyjopvd.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqwvzue.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hxogzpmd.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcbunbs.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgcpmbs.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2oziiqnva.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2peplsuop.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2obviados.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mysfbdlq.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuqemoj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2lztcfuyi.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcjuezc.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnwhoyx.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpgqxdi.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2alhjmlub.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwccgoka.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxrtnhk.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfftggp.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fhftquah.html


<!-- 参考信息 -->