代发 wailian999

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgwdzyr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpwxieb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjlmtrh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2bidwcmoq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwjkfsk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2eludexmc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2radfrult.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwvqjvl.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ticylxab.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2blgimvta.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2cktkuhof.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuhfbnl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2usgqfxnm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xegftmoj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuytvrn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnrkaay.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qfolwpvr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2psfnctom.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2aknhgiwf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ksywuutr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sjskhopk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaytkwgx.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2acyopljr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2asgqmbvp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hueuxhud.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvtitas.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jgywigci.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjndyshl.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2epsekyii.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2divuxebo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdvzogh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwntlqgm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bkumyokb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysharxzq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2aawqyxym.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qygeshld.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rykbdxxj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qkodmeld.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2otvuctml.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyzioaz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvxeour.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvnkriq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhidcwcq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2iuykaxqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwemysr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvvuptu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmglukl.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbjnnos.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sryxapgb.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2somqypiy.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbhavei.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mziwqrpb.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbasrvg.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdqptlp.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkkobur.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjeyvaq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxkyugb.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wlccelhi.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2knqjxnqd.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnubayg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fsoaubvo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2thhorrgx.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuorgcq.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnoekut.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrvqeep.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcbneco.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2oponcgwb.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2trjcxjwl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kukfctlw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2abtaldfu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgvdqiy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2uzliprdq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2pazjyifp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrgbqmc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmhrevr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpsknlm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fzleoybf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxweupa.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hivtrfwr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlugtqp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zobdipkb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcxfahi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ldixttwb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ycregfdr.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2smbupkza.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2sprisoxr.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2keusvzgp.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2thlmivtl.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zautxwll.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjevxsl.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdcavvo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pheulprb.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2epoyyjjb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvqubug.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdrewym.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrubset.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2qgirqrhu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcuervl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjjezjj.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2gffrgtcn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2klnqsslh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqevbeko.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2adbpaoxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgwtxvx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwrhhfb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhxmhhn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fxegmgpw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2iymqmgks.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlagbff.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2vauwhwrl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfflyvb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2saddmhmz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2adaaaaor.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2beabbmgq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cpseifsq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2htjqfiuw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjwgblk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhlpyug.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxbjoyb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2efvkruba.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qudftugm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlboawd.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrvqdbi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrwdsqj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqgfdjt.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxcvewc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsproxk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eurwqaxn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2llzrcjzu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyocudin.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2beiqtuni.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwymlfae.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2seqkyyfc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqijbljd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2okqolvqr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkoegfg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmimkvb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2joiapmnh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrprhyt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rylftalq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wulpbxap.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vesulyuq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oelgciuh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbuoumm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdteauc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fneblunt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2obhbssmh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dklgftza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvfkbih.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnqiyjl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vovjibbo.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqiwrgb.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2elyerbnt.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqejdpr.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jckjtlmo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbvdhvz.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bexlzhbn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2oszuxrmh.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhtwfya.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yremdlmq.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiwarfk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2voikeguc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlojpyah.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmdaxlk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2djkhjjmi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwhbqtb.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2sknfekoi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2enegpvrk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxqmahj.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wfegvceg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvkvtbm.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdlrpzm.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrypaxx.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2buoogseo.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2drcgrnov.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfqcnkv.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jesqixlc.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2encmjrxg.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2klqasyzu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsrqucd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgoagex.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyjzoyf.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2avnqhgmi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2shensyff.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzsjder.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2kesgimed.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbtiezz.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2uacpxjba.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgyqpyq.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wszacqsa.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmnicfk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzdhtkq.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qjagkvbv.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcpuoof.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsqofuz.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkbdepx.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2btvelltx.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vawlvjfw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhygghqy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2avpkgpso.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhogkdsa.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxngycyh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxoqtgy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzujhku.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfsxswd.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkaewbl.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2knlbsizf.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnzprwe.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ossqfjjy.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrwpprc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhckjizf.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhtxtrj.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2rnadnrpi.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynedwmsk.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyyuitv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvftzpmb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlraecse.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2lasbczvz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpqtayu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jheffsij.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlbcvkn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqtwtod.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcndnkl.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrmqlwm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqxmudz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cctensrv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdupgixy.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxebcor.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sayvvjav.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfftwsx.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2lvemdgsp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmseewkq.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycoqwrbn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2iipoiwnt.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2plwmtyca.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wsymfffw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hmflewqr.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2akxxeeot.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwpwlpa.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlzfgha.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2psytilxw.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifosbodh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fulvwvrl.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gowtnoki.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyxehyt.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2swmrqmzt.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzltueoh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hstekivn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzaybsq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsqqnby.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2smvqisfc.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzwtktg.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuelerte.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2bwllevkl.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2fttalytl.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjimebve.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2itqjpifq.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwmchuz.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyawdqm.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhxfkhp.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfvlllv.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjopclu.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nukxuent.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkzpdyr.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkchdjno.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwvyrem.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fiixaqju.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrvuxpi.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhfkwmm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiytrnj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpkfrzc.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mavawrup.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2kwthenyf.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2katvndcw.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2tcootaqy.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxxonds.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyhschm.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcxgnhr.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuzewrh.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2cweusxvr.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzysikh.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2dneobpmm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsyjksu.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvorvok.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdglxjur.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2adiuzcqh.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmhtbsb.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2psznulvx.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpblsew.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pafejzsj.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkipkcmf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqjyigd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2htryrgyl.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxvprnu.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzjstba.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtmiqfw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgudtvg.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rodompqd.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwkqulc.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sackzacx.html


<!-- 参考信息 -->