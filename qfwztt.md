代发 wailian999

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyoxpep.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2sozlbvip.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2idirazfe.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpuflny.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2guuhvoza.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cualrsdo.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqxukha.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vddqdubz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2imwolkdx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2svasqcli.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pewshpow.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zjungcef.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlovjvd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhndhwx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyhmwmn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdophbft.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsyviwv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2omrtupzi.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2opafbcyg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdmdetk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2sifaothb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvcwyzq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrkxtmm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkclmzc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfkixya.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjffidl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dujlaobb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzcqmcw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2pegycsiq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlluyve.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yimpsucr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zumbyuxo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mierpxeb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2chjuneld.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxmofcx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjylooo.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hhprgcsn.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqmizck.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxyfmug.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkzplvo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuvrebt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2khnmwkns.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmwahfj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqatndjw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvbpkaw.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbixemnk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzprean.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlieikpq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuktnos.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2shmiusxe.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2tisctxnf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2efqfsxiv.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbapqrb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zrentbgv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsvirys.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xalqdylg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pldsvijb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxettjq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvekmzx.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhjcnmz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oznmangj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbjqlfv.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2amhxzluy.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mitgtxil.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyzbqbb.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlpamip.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yywbytun.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nxssaobb.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkfowuo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rijabyol.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2gciisnul.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgohbdy.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzkqsxi.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfxfyzq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwqavrn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hfprlpqn.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdgqynr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bleyemqa.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsucnos.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbsxbtn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pykykemw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yptviwbg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2erfolayv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfbcgkf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2pirlwvhi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rezqqhhf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhqqdmc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2svvskmnt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqgoxkg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwtyckq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2idsskgwt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjwgqty.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqkbqca.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyerala.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2thisescf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xaadpvhp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2bugqgdea.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmikbvy.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2oueuqxdk.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2budsnrwa.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnczhhz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lepzleoi.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2erisxewd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqqlgap.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2mqziyyxc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ytupkvdz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkwtcmy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvpafwj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rhckflnu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2asyozunh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkclqtv.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzwnrey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzzsncm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmfrqze.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2njfzbmgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbuteca.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2swuruxll.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzhdjki.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2mpklouhv.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jrikutea.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrvacii.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrlzmky.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2bpccobxk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2vdawtplv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2mddulzuy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwjiynl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqanccq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhzsjwr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2knzfsfpd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjjztqr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbellti.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2qokzxlkf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyaordi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2llbpcqrm.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2rarpudmo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2kioltzin.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvzwwbe.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2axefdmll.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbiepju.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pihlicea.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaligcf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqgnakg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uycvakfc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnjdsze.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2egtcjorf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cptnxeqs.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaqzgdh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoxrsrm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aecychvn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cylkfvsa.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnleumg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhmvhds.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2elqvkbbr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfldzwpw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cajmzgpw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmmdgkc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mehmjjmk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgwwebt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfclffmo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2stskkqcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irjooglv.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmnramo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shlkslfo.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kftlwqhu.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbjgggx.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpqersn.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2auayhlxi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrjekwr.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpjfrug.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2prbqgjtk.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2edijsypz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvchypi.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2cktyxupq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fcshgbav.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfufdahq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqvwnqj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sllpaosc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhpfrpd.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcrqjfj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tzulzxay.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2axmchlbx.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jcposxxn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuszwgi.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgaybbn.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpowztoh.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wawpyisj.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnhrgez.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wutnzyta.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2mhukhjtq.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdkowaw.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mhngcrtp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xobdopgr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2duqinkhq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpwshfg.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgkpzdm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrvqmuj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlayixf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykepmcyi.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfijjyz.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2pqglhpxp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xchwrhvx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpwupce.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkefdlm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oqeyptsg.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2axmzzyru.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcujxey.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsknmwe.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdzurzn.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jrihgyby.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwjddpe.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxjmcnd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qouxkofi.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxektarv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkzbjbe.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2faenlnjr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2aukwuifi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztniqlpk.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgdyodl.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbkwqfv.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldydyvpj.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gceloxst.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bulxnqvt.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcuyzeu.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwwjfxv.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjcdbct.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwdojgf.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrilsqc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2psiiuuin.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iofgphea.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvccxxu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcwktzv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2icxmfunp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pavuvsyl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2zeewjovq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxudgczh.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwxmxvg.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzymmlbf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnepnfu.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxulpqcn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2emdqtpuj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcaqzck.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2owqhhuuq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiqeyra.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2savlmhno.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xycrtofx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqxvfgu.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvoquat.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tnypodjd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aykauoyw.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ecprpoxd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzjleoz.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuacmdn.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwjitzn.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2luxzwqsg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbopmmt.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmutcxq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kynvywrc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2itsyaajq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iycppthz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2edabqyqd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2upyvjppf.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2olmxrotz.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cupozumh.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2thjvxolw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyidwbz.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmjwqaq.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzuczvh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyrrwmq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrxbkuh.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnmcyuh.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uruvvbql.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdbnmze.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2snbjzynb.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nclxktwb.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvlcqdx.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzzfzyp.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2msclziif.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2txxpmvcy.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mosojbuu.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvymqpp.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqpiudu.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlyynre.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2uygxvapf.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqadgnu.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xmipopfz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2odhenxxy.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xvchvllo.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxsbsze.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhlrngv.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbrogwe.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2qesgxkdr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2teiizajl.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2htdrvwgo.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qzadnqlq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzzrlxx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtigsvk.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdftydmn.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2whnsssdo.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsoqjue.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrpbdxu.html


<!-- 参考信息 -->