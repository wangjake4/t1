代发 wailian999

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrpvbyb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhhkbjo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2njuiaxvy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rchjwihe.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2msfocgex.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rktvfktv.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2adcvqzsm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2froktugb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zuotdqpd.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2moejblnm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtvcvvd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfgefdd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hywuqwtw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2azsrgcal.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2cppzklzv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2llghokwt.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vecbhbmq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2duqeqheg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2doocipwl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2agvjggfx.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2pidptpaq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjgnftq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hspwgdtw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hudppmli.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeqzymw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2noqrtxop.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwnrcac.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsliayn.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pviusvbi.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuosrpc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlxzyzh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2onccggmb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2olebocwt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2urmzcuia.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyyndvy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyzaowg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzzxzub.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kywajxvw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqpgpxo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irkrwvxo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2iukgfjac.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bpowcceh.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2owbmpwkl.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zntknipp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jzajlnde.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qmubcgcx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgscwena.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2nkocyruk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uosuzkge.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2duhzuean.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlarynw.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2crcyigpy.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2klljprhm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2evtunewn.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2enatdjog.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bagnipni.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kpawvhie.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqrmbji.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2likibqaq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qneqijfy.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2btlvijta.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fnikmhex.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoaexvh.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqbrcgk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2odjowmni.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2erfacvxr.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoqydtu.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2midwlnjq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqqoejx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxlkepz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnpjoik.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqfloyv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2oeabijkk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyufrxp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgibaas.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdkdixt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2tebhhmwx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhiwcof.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ifghwkhz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2agzqfkmq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eauphpef.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhaktdu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yiswppmu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcktoqe.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iahcllcd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hoelyaqg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgupdkm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2adkcxtls.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgpmyak.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2plyefjhv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2oehbcflh.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mdchnppi.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbbftgi.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpdhrwc.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sioodogm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mqghpjba.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2hrezagcg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2puwdojmh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2htwdfkkp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2vabjutro.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2bnktqbxe.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2nuutlyiv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2museyumy.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jwafsyaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xesdqejw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwinphtp.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2uceazyje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wniftpii.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2amlzwigs.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ktaktcaj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhliuek.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lymeygif.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpldpml.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qyznhwti.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2okojoixv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkudjda.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2lobjvrox.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2lugmtinc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqknvxk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgfrdtj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjmafqp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2cfncweeo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiptoef.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2orpvsfly.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuzrgrq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ypibebuo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpcftkl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2huxkdyka.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vuoqwpeb.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhedfef.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgxjxvc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bffkulnm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2svkjflei.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjunoii.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcrvlyh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqrknqz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjpvlam.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zuagpoyw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxztdum.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvcdwco.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uouewpsp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2whmocnoq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdetyrt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxsmiwp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfjayaf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urbmvrvb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvphnixb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvujkaz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgmvonr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2byqmucuq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhyxgzf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfvfmzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdbyzne.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmjfcxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmsbbms.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2flypcrnv.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjhulta.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gthdkdjo.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxacjja.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2suceoukf.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdypquk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpfwyfy.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaixjrk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxvggwo.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnslcud.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jfarxhjo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yydyoxhy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vecbelsp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdxrdzt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyejrye.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2heclfguq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnuqskj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cldheugv.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hewluzvi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2xybnimzt.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrmkpwe.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjjxuvj.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkqngnu.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2idtkmphz.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkbgyot.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2pborrvgr.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgijhta.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xjurrfvb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwylfylm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfpxwya.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ohblmzof.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdgmroh.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjmevbk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhbliie.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2licpltpd.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2zggsaxqz.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjhwhuv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdsxnso.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwexmxb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiuxqna.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bqayhpot.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvkaapa.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgfsknc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2plcjense.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqyscqq.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhfnghs.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpzxoqd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdkinmq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxizazod.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2etbwmprw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2trzktoan.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbokxne.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2yyipqvbz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcddqqb.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpucjhw.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgazicq.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaonalor.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2osotynqf.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrmiffp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gayzdasl.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pikbgpmj.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2udgkewul.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjeljxi.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2nntptkrt.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2czmixsym.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwcsmif.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2laogwfmb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2uffoxaxx.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuxxtcn.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmawpqx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2kchdzjbr.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2aifvzrbi.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ejczmvgu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugynlfcc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2owhcoiet.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqcmqtp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbkmpsu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzzwphb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2exanfauc.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrolpum.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkuxwae.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bskomvdl.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvzsbyf.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfsmbgf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2skzlspea.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwlbmjb.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nithssew.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxewzkz.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlcurua.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyfwpdj.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuxlreh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2khnguzzj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrplocn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2obwtcdcu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdadckwg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pionznri.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqmnmju.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2aksfobnv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2twfurxjf.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpldstb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvojpmx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nscitmkm.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2cykpefll.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbgpedm.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fthcughx.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2svpeepcj.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqknrou.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkfqdhf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjggaxy.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaoqslc.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmckbzb.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sobofhoo.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2prmcwjuo.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyhufcn.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2aheuhkvz.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gittyhrg.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hajzyxrm.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkgakbh.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqjilxv.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqsqxdj.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrtetkf.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrpljif.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hncdowfz.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2oukfyjfv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnulysm.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2pkarpvme.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhggcjc.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2afispiob.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2gfldbmsk.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpjhxru.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2xewoonea.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpzgawr.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcohclv.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocizaxyh.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtegzvu.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2cppfcjvk.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2byqeaaro.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtxmwfp.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpticrc.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsotytp.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgcmdus.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvlirlt.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqgdyll.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsfnkfp.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvxrcke.html


<!-- 参考信息 -->