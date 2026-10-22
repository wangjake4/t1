代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2geniwmfk.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ahizjgfw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhhfiee.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2svojjzvr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2czbhhwdd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2urdsnmmu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfkyytb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2moeqskqg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2cklnamlb.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzdnmfu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zydbhmny.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjiuylf.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbqymvc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjbzmzw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2mpncnvix.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhskgrn.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2khirwlhm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2opcgykvp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jebvpdxn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcnvmfh.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2obofcwgz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tanezivn.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2adjhdwoz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2wccpgixr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2otbmehoc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnrpyph.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lettlesg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvecszl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2chquyzxd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzneefo.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwahgjq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhjhsxc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cmocgxra.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdwwxow.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2eeewqlje.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nknpawdn.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2eammtifm.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ticrkazl.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lmseatmq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyevlyrh.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyuuepu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfzdahe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2awcjkend.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoahwuq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyarlid.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxkyvuk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqsimre.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgfueiy.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwzlffv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2twtqhfjs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgojnxtk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2qcieqsvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsuidxm.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2rpurdvbd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzplnjmo.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2oognvvsb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwajqks.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gorpueff.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtblnck.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhxivaw.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hlomvnat.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2weuoarmx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tyohhhjz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rafnkkoq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzmumkb.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzcggbj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbhtptd.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tybghlph.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2avgojzhs.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2osgukxyy.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwyaeym.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqwgknh.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwzdddp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuknwat.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlujedi.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvezjff.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaspprc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jbezuhig.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jbudgidl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zuigtbdg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2utqfitzs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjablbf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnipvcr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2imdflmvc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcqpgnm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgrjwrj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2prmkirks.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ovelsmkc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcjnksy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kitmfaek.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ynglvstx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gifkhovs.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2rylbiwyh.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2eynvpjoo.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2desvgocd.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2sypibbkz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxmueqz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2baqdkakl.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrauvrj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uaewximk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2cyijnqvr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrfuihf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrhtnys.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqrkzjn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ylplmurt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlkmwiz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2sixjtvgn.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgqmakv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vaefanzu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2towcsnxw.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2drqllnwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zazxusco.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2tjccttam.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2woljwwvt.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaihicg.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cpghxusb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmtlxpz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2kwudtxac.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgisiiu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2keweobtv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2fujsxryd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2pupnlspn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjbzykw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsbmblb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2opagivxk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2zojnrtlm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjfflua.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwnjxro.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pckiunxu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzcytlx.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqwytoo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2whfsrmti.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qoagfxza.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmaohsp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfadgbo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnieqcnz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzcphiz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2prjhcymt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgryvguo.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqgxuoz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufckowsj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2psdguwrg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfcwjhj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2diwuircp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2meuhbnxv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqlsdbi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lepuynla.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyxsnhe.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zykdxmyh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lktzygda.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xanvwtvr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxlscvw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcldeew.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dguwncuf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldscuutw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvocgwg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jidgoaxe.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtfpuwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtqbbxr.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2inyltzbx.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zccbhaqc.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqughwc.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2smfrathd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2nneosrbz.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2caixjpck.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2pscscvnr.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdwvbpg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvkxncr.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhhwtgd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dyezbigi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzvniqe.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2soikbuga.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkaubpg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhkbjtv.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmdledv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tchttvdb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzxqmlq.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wqugayix.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2mukvgtvp.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpvppej.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpnitty.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxwsmpe.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmbbwod.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkrnukh.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfsjhcf.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pihtngsy.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nndcisqt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqpeanu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2litebgmn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jnihjwcc.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2xprjqmpq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyaudbz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpfejpp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2aboijmen.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzjgyct.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ullsqasj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hotgjbun.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxewwlz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bajaaiqu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqeysbg.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdykgby.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ogblxbvt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqphanf.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtibfkn.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpkrelp.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqeszgm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkuplyc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgurgdbr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wemugexa.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvjzrqa.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcazraev.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqfddaw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnjplgd.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2chxzwliz.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2djcgdpan.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrjcygz.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcwgcfh.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2usesadgl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvkgvuc.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cierscfa.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2rksxquyy.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdilezs.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2scvwnypl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjkesxo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyrgsvv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyauffsf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnxrtze.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcymgyaw.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jowzkouq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2trffxsjv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2canhazam.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvlgqyr.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufugsmni.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vckdtdsf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfckena.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpgbhpq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lawtmxqm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqbcmxh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2akvtarzu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2imcyfssm.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmndaenj.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2fphwrabp.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxvcqej.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfsyizl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjxmpyt.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kteelxox.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2oehcvoeb.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2azyufcom.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyjkohj.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjcfaww.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2oljjhpnk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjxddqn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2llioqnhw.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiiqlrf.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2flzcvxgp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbcqmeq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmawkdq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnlpydl.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2maujmfio.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvcgjvz.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2eibsnfki.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgnmsdz.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2rebjyjlq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssibrmwr.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzpyibc.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgrsvrr.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmtzodz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmjfsxj.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgaksel.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mspnwant.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhneadvw.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcxtfjb.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvoycjh.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2istzxyvl.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntexnvib.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2abzxxstc.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuaasne.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2izdaugsn.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2qagkscwg.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxmexfj.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2idrjeydx.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2auloctxv.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrdafnu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2aymkfswu.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnrsotd.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2axwkwhjq.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2pznnltbr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2vtamogve.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2hlasppzs.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlklume.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2opfrygvv.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvdtcev.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqmskfa.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2waxofeiy.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2ypajntlw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmhbgum.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2yltcmdqb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rynrskow.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bafdszay.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuwyjdx.html


<!-- 参考信息 -->