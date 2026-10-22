代发 wailian999

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdsheqn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2meiasnsu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2npnrzrmh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bkceerke.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrupjsl.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iiaabneg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsfjhar.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsyrymr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2unpvbxvn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2swhbjgbv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqtywgv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2luagcohf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwufwhk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdyrhrn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnbnfca.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pisutjcu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2orkejwge.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rskgotix.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cvprivwt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2luybejvn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hkledtgb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhnrybj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwricvk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfjgxdf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mpudctxt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2duiqijak.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wqboacnj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2amfpmmax.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlwuwei.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tymnavqh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsqevrc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2muzahiob.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2diwgziui.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2olfshjus.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhphnib.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbmstoy.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwjhjwm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivarrywx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2giakpxih.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnetjsjt.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpnjtkv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2glupzcod.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2olafpfiy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2joplxwfo.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbljnlx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rsalctnd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnfisjt.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnqsgzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpsnqqk.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vqusviay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhusqaj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaesmco.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzserty.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbencdz.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnsvmjo.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnxtmnk.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tlspuqai.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fldoyijc.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ocarnfjw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbzwhje.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcqvvgo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2khlczvub.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnslwal.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtvukmn.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2znhtbuhm.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfsfwnf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fektyqqg.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yszagkwc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnlpzws.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpjwppj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwpglkf.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2thiizrdv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dzknrawr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcblsjd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhwndow.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzjcljk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2zxycjdwq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2eecxtuzb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxfbkos.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wmclkgai.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzjdpzv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lgoobdbp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sibfthhe.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgamfai.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ijycgyyd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdqxkqh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgyeuml.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsjualg.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2kihebkke.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ockmsyej.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2sykwzgxq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaqohcx.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xissidqx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eepcwokm.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmjuoef.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhiieao.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkiqxnc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgbjvbp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjogfgg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvrrqgo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjkrbfl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzeyuvo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwyjozb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jswraawy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpservv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzftytu.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdmshwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrsyqxd.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuassdg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2freddkwn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgqxbgc.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qplmygdi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2adtbqdfo.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2mzihwgun.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2iaasxmrm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkgprro.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2lclujoec.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2iufedgeq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuzfygx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaoetpq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2yelylqvg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtqqbxj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2mzodcafw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzyuafx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgabxbc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2chifrywy.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2jucjlewy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2eclwvugf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfqgmbn.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ubldbscu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbdvxpw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uixoevcd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2djakmygn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aiowqxas.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmstuuqk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjowzast.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2shyohadh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2debhqiid.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdrgkxj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fnidnbct.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjexoyfb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxkkfcz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocivnpuo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2swepdvur.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ooftmsgq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iprqqnzk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccufozaz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lytjltlp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvysoxsn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2trvslunq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctashdal.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxigsug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phwxvtbu.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2emmyckci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkqoxpp.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2girbqsis.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfkyesp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vlafnzws.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiflrme.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ettoaxvj.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfuidka.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfywrmn.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmdkaqx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nghovtdj.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcbcazv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyqrryf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxmgofs.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hukjbudo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhjteaj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tevvktrc.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqhhujx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsbzglg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvyjhoy.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmzcpus.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvnycuv.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ualctdth.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaiqtqh.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmetmwe.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfrvwsf.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2agagvwln.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjzducr.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2arpzcnmp.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2impnsvzz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlrjadk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdzktvm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2uitgcmdx.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2htihiquk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdjvlmw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2azpuchih.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtedioh.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2uvspftkh.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2uemozeyq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dliqmhfu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwdlerx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wuositor.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2twbbxadc.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdintzd.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzolyfa.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfxsxpc.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nditwquz.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrzqtfg.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhgnaej.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuofcilu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiggzvd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqiklfv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewexebiv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzvrktl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2bulmfaqt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqzgbpd.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwrunqm.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdvvydu.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrcrbsn.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfpesel.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2adplmymv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iujrelug.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnekpxrn.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2agqipcxh.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzysjbn.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbmnhvo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnojtkb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoanolyx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwubqnxg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tukwdwzd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfhyzjd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2skiezjsy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2tabrzbet.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fairjdkl.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2exsfbudt.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qttrozut.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yspgztuz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpbfquc.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xawgeezy.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcftmjnr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzegmzg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2efjwkjrt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvkjhbf.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpffifvs.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiixmsh.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyfczum.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfnoqws.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuivaqy.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2axrwaewo.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2upgaqddt.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnhplqx.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2txyjmeay.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmynimu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvntmfq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyprtxo.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2efcfinzz.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2auganacf.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoweadj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdfapja.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjikqbg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqiozko.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbbpfgn.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgsbnpq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhqmnfq.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2fnavlenf.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiqgtgt.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmaneyvb.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgiyctu.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wktrqlbp.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnzayji.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcudgmjr.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sowrghkf.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2omuldmba.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2obrnmdsf.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekafolux.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfujxcj.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2smvwidew.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xstvfqno.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2btnprkhd.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2kygqspfv.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2jctrqpfn.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2cipyiyij.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2suvoagji.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmtvoch.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2tksgxmry.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2afkfdaai.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqybhmay.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2szzfhexg.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2povuetbe.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2grxblbjo.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2uopoggqy.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2weatrcbw.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2octsnqqh.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2oybmxodk.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2abjtxbrf.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2eybaijcy.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfltzog.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2rjygizdg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2atmtdxgs.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2earxnucp.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2efcyurmh.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2klnbeddw.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcgogqu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2teipajpj.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2cbutywyj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbobudw.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2oahvpgce.html


<!-- 参考信息 -->