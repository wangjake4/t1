代发 wailian999

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbqhbil.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jboemots.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2izgksdgc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2twpbwjxh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqvrrcx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsuqcus.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gidbhcqb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtaefpo.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2otmrxece.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaxwfkv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2uawngylo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkusgnd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrrfjxd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjcobrm.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkriawk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgwagwa.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlhijob.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ljespfwp.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cuitiueg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjvkczo.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwzqfhc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2twftzcbx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gimywsjl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lumcecla.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvxrgdt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsqelex.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2twkwxyag.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnghgok.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2osceaxsv.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxftkry.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2piecmhrk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyoejka.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtgtrzk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpfgixq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqazekz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmjjzkq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjprktj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxhmacr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2siwfeszf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpvclhw.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaaxxzc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2aszzhjym.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjzubwa.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2uimxdbcs.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmtfgcw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2htzcemwv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylupypcp.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2axykmrwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxehqwx.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2yolsdhqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkscywqk.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2qamwubni.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkjuqyl.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cilknxyd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2almuaopg.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeiicmu.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ymggtqtf.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzroiql.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmreeqc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyxsnxp.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgcjauk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqftshx.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2knpzczda.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2gtybcooh.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jozdnhry.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfehssm.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwzgcro.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjertod.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vlylnypp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kogvlbno.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xxggtkur.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwkatsg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwdncij.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsepzzn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2occklpiy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wropremj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2aotychhf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzpvscy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2twwsutqw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhrjtns.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjgoakn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbyryeg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjkpmvz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpqwhjq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuxqvdt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2irntfegc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2scvdjnhk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmybqjz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvobkre.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2eslocobg.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hpveqlpd.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkgwptg.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2odfeefpj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqjmgsv.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qajyshny.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2scaizeue.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsdmoma.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtijfti.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxhedmq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtzkxxl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjggheu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjgsmxv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwjkjdj.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2yythxniq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcwatwx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqeboqbj.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2rvowjyfe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdyzmyi.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2myoxqnwt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2bplgwxlc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zytjtwkn.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2frzedxuc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wysdarrx.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqndsli.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2qbopyblj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuexlgw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrktcoj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2kntwqtsy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vcecmqtv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdfkflf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ypantedf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgnnzgn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdhzvvw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2haxsdopi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mdstccni.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfbthhb.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2lxygczth.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpmrmxb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vicrmyte.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2rojxqgjb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cgejnvvh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2shkbsccu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgnqgjd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmlgukx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqsgeqx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2giiazmvw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hygjeyzo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2plxqzdxo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2phjyajpt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdllodz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjvchow.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylexvczp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2daayeicg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2itthohmo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfhnbyy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfrsipq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbczwois.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrijlfcw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvdtkiw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpxqmsn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgzmoho.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2muurdljo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqfvseq.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eihrkohv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmubzjt.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyxqbfd.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnphxedx.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhowgsm.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiyysce.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2shvoibzg.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nujtzfsm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnbajdz.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwexiax.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzbxruu.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbnyexm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2aosziuid.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvgwvcj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcazumww.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhmuwwt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmfnfcg.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwrmdwe.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lwizmvnk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrtdnnj.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ywneadha.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2llopqxow.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmjrlxr.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyirovv.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxdxdew.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqelhqok.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2mwimmiki.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvkchos.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2devqyvwa.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qwexlule.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlizqekc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrilsvg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbwoklh.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlobqoe.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2pumxktkk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2opvdwvdt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnpaaaz.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2rnukipnu.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2vobzumdu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuifxll.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ihloqdff.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kxentrpc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqopxzw.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qcetdtlr.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jxixkchq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbshdaw.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2defqxzae.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jadiewgo.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyvysna.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fykcsqus.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxtkzlf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqkoiki.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2uejwpzwp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsydymjs.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqhgtln.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbvjrch.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnmuoer.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqrprnl.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzffjhfs.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbzkjul.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncngpind.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxixinkx.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2camhkkba.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzlsufi.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hukgjkkx.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyilomq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsntamk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtjqlzm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkbcmed.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrcjotc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2iknemyhu.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rchuohay.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwugznj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzapxqrf.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2foyteyfv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgikrxmp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mieobsmh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnygtdji.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ricysrij.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwtxaks.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnaxnkg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2aistsdoj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2paxgdjwc.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgovlxer.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgwbrnd.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnytnars.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zaluubyg.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vihfttlm.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pgysmekw.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2rltfzgoj.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyonmvhc.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntldyrud.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvtxnqb.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vaeuwdqf.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pledlpbj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wckqpkst.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuhwfnx.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxctowls.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pguoyuhc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqsxgmc.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2frydsahl.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iethxvru.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvrmxvj.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvruzhqa.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2mbeaudtb.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhokpef.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcamudu.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsvuqte.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoasdbe.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqenabi.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqpsfei.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtnrioy.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsunuuj.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jajnkgrc.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgngoftv.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2emjuzhug.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lilslrsh.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmcyagj.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrrqece.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hahsbfyh.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzuidfk.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2goykgtmc.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2sxibqqli.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2yhumhxat.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hqowjsyx.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2avahdhgv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjqgkcg.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrwotum.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjwcpgs.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikudrole.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2kijmbxrr.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhvzxhl.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2scdmcwrs.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgticldc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mskurssh.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkjxmzi.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ktriygjq.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdeaptw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ectkkvun.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwamolwd.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhtmcaz.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utzgbaqk.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjvhspc.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zgknqzqb.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2axexhooo.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpyqatg.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kkovwrmn.html


<!-- 参考信息 -->