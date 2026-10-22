代发 wailian999

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpudkyo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtpziij.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iotgbrqf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cyleuuxn.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zpurycfl.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2quujjuof.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2goqbfbva.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcickgfl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfoikab.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwjbxpp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2oibszypk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxunqpaq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cokzksgz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsfxwji.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2umeieqfb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qrclfepz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mvirqdfn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkqioyn.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhhedzz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2arcqigac.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyxibxa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjdwpgt.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmotdeld.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwmeutx.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkmdbee.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnaxtpsz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2stgsvrnb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2erqrcwtq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbhxhoh.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfxozzb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvfdrjn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvwilsj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2podwodut.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xokwvsms.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpemgru.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2npuarvaj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2drdpjiju.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojluifav.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgjdrch.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrwtpyt.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pubvcbkp.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqhmuns.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqtehwh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2advzmzdl.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtyvrdo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2bngrnxhk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qumegamy.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2cgonvjwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxexfujv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2odrimliu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wogzajcj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2magbhqrk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ikaliwsg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiptnfq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrirrmp.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdzapel.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjdboic.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aznsnmft.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsmuuol.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuekgho.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gcskscmh.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfgfkzg.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfdaqij.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2imlywdrz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fyekxkkq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xxapgaem.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbuqgww.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2brfnqysh.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wnackcay.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rwadsozb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mqibsytr.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2jeintbqt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2exjaoxdv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvzxijj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2krucweql.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wobcpkpf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmchkrk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2csalsejy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvvyydo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ipafukjd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjktead.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqnvvcb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmvxxkf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2weocyszp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtdchqf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2twttokpx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2vectlxzk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xzouyvkv.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2rscklbzs.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2taasmxon.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhhngok.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkbdppy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2nsoutpuq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwiqzqk.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiuooyr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyavmaz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzociag.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2alvlmwzi.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hljcruba.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2yygzoswx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2coosxhnn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2uhthhzqm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2irlllttc.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2brwjdcek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oeecyirm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwslyquy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqdrfav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfpleun.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2isdxtven.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2pnckbiry.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoetutt.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjsuwah.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2btouuvzt.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2izpriclw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwstzro.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2gqabopiw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqrufpv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtuwfzw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtxjxwi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2hszfchfm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2lsskjuth.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiahowh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2phyambok.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvnapxt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjihlqp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzvftne.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2jlndoxzi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpwsyle.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2whxwupwy.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2zljqzvaf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxmabva.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwiumsg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2haflzgry.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxveyobc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2htoabblp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrtokmn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cijlthvx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyzlppm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgxpajx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkqzgud.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2crhasazb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhwdhcb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcxbmsf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvldsfoo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkufzxil.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2imykjeus.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyynorg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxrzjju.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxbdcei.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwdtfpv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuwkqua.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnrfdfc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cenlawhn.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ijajopor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmombpr.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mxywleqx.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtndnwq.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhoaait.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmewvyxv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqwxblz.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2buqudtqg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrgnnbi.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmtijbo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xewzhftj.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2psqlxylm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bzquayck.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnqwgtc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvsjdae.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqevxmr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qckdrxae.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhxxejc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcyilbq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjyafgy.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sxezosob.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ypscqevg.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbknimze.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqsnkvw.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2prcqrjab.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqahvdj.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwlmpnl.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgrvisg.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdonoacm.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbqhiuw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaksxhqv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwmpxms.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkyxqkj.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2heupwypi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhmomjz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2kajxojdd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2sddlkemp.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2wadavkhk.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcctmer.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxumhey.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgnrlma.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gamhdwql.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2whhomwsl.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnkttwf.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjcqclx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dubapeem.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jtagfvkn.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdebczf.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yckeasyz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzelkfgx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgshkjqw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kviiybtq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2onpqgfqh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2njjooscl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwifjls.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxktzuqt.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2siumclpe.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsreecjh.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtmbqlp.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uywrwtps.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgsblmg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2blziebtl.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlloydcn.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2amrlgybk.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uygopnjc.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2humocexm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnwrgun.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvvmeya.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuqegfz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2niltwpcb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2drfxlvhy.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwoqcig.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2quenvbzk.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuyowul.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uryvjsqp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vupkcieh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2salgrxiw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbjuokf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbwfyjh.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsdlogk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcxxhen.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2dlruwfef.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjxbhte.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qouppswi.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayagdkhw.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzhpcyx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmyvxow.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jblqdgep.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlhbldw.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2lriykcnb.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvvvbxw.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjielsa.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2yezbazvf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfjgpkm.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yltppzav.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2blcvmxdy.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jterepzm.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2miltdacm.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2scnrksqk.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsesjrk.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vorgrfue.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2akrtrpdj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wftalawp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmiknuj.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2abdnuumj.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2tncznepy.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbrgcfg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdrfltj.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwgkikk.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzjmlrf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2yghdwzbr.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2asmwotwt.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hroenqwu.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzauahc.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjoinne.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbupull.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdcrbaq.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jejpxccu.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqbdkpb.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ccniuxnl.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlserrn.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2beuwqhog.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2blsgbpvf.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjsacnk.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2edpitnqq.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxvnrdl.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwyvdyu.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxpxrat.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2efshdphj.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2giddpqul.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2hedfgnww.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2pubqxvkw.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsiayfe.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfaekki.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbairay.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhppffs.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2vewwvbuy.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuurxuh.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2tydtrvtz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2myzrzudq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2irvslssr.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnoljfk.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rztdqfcx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfcvzdl.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2eyutxuyt.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlaoxgc.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwmgmnj.html


<!-- 参考信息 -->