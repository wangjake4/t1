代发 wailian999

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2pvferfrr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2otrtsbub.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gzchnyns.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lggoqsqx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2axmsfvkf.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yafjltif.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qhscrzuq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsnjtrv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfeaqqu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjxzhpv.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2swxwllaa.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dhudnzla.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2efxlekhn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iruoucqv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdagjcz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaejgtu.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2szsbjima.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2eatnfvxr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwetjco.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2uykkxmyl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2axkgklvi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2idnvvmff.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrdxres.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hruzxtzu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvxkdpj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2psrkmzqp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfzhrdc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhkrrxt.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2oizxupvs.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvmzsxl.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyfbpfr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2slyvlkmn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wurokydu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdluygxy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2eesohjvs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhoncbv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwwylzf.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ujepeyxu.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2vrppmbtq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2tweueklh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2nueernoh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnypbdb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2byophelw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhwdkcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjatnyb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2gedmywyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcacyoa.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfepdng.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2iflcmrbp.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcdqrrd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hdknkggb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgelgct.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfcilnb.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyvuxsb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfelyyr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aruwmhqg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwaymeo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqjdoct.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ryysgtew.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxhimww.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzpgrtc.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqhzmof.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2khcnufty.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnvdkko.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqakfdr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zuprvutg.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlteycl.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2kmaypdlu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrfvygv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xbffqtvz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fekuaewc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ducksnso.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2affvcfjg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrahhey.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vhifsbbh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xesibfox.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2idksmjbu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxnoeea.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aajqutqk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zsasghuy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bebubxkc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhfznkl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkjmbok.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wynddkoz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qfofatpl.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnooecr.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wwplqhsx.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2egdzlmtq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhjnmrj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxvgdcq.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hfalyzoa.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwixsob.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxzpich.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjflddd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ygasnzyx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2taocccuj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2okztdncv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoxlynm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2vflmuobo.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wpitkfcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmmyqin.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzkmxhl.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdlrzwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hddsfsfp.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2aocykmpk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2jofdjgdb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpnhmob.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnbmanj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2iijmljgd.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2gziyansl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2eikdeipv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsyccjy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuwznho.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfbnybv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qikwcphc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2onrdbgla.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2vagjvrms.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kpitmztg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzimqjd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2vxagsxog.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bctprfwu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbdkbff.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgwxioz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgbnwkq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjcjunr.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmfcmam.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zglyvjxl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbolnzq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxjwxqw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2veyttcwn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2opjmvrys.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qadcrmzk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeonuau.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyhgnpt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbhehhb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2clvsxqcp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngogksaq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzjdnsf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsluezlm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xttyrcpp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmedccts.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgftxfp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmckgsn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcilfaln.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkuqoyn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyotlbw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdxhbhg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iadaeqcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ancyhfua.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rdztvugz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrntphci.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2frjwftwd.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfwrvgx.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2reaeuspz.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2neiijxts.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogetedzc.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vihqjkun.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fciezocw.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2etayogkw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jchomqkt.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2bjermoak.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kpubiyam.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwncihn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dagetcac.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpksyft.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdasmosi.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2taazzwse.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2sciujijj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvrvcek.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgsflvc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrrrjwi.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnyawnt.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtzmils.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2txjdfjsh.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2auwpvesj.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbmxpfb.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wueiypkk.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2umozrabg.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdfuzis.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoxuaxw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzxmcqm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2brshxgol.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2drfdyqrv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2svmvosho.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjiqmlhq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2cftoqqbz.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2rmadoawd.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgphphn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxvmnjv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ohadnpwj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vabdocme.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hkszpule.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzllvwq.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xjamniwf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pxodhwod.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2klztczyj.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfztzcp.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibifmspj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhurzzn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2enovtoea.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dophgipo.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgjqdyi.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpuoyel.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpkbchj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrantsk.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uegvnzte.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2swqnzgor.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rexnduhw.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjswvyrf.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mumciyon.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdqvyfc.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxajpbzk.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2nushtzyu.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wetgtejt.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2nunvvaix.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeokwdlb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsajcie.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhkwhai.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiailrdx.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkylrsnl.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiouwvb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2acruehpv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wglgvlbh.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lipqllkn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogleiwlc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cehfoflx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdadtgwq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpjlpep.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zufopdrg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2bbskwdej.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxwqjhy.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcicprit.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ognepvcm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsecqua.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdlyaab.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aiieycir.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uvusvxfu.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gzolelco.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2icuenfov.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2amlibjyy.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqhwhge.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxvwcbr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvunypo.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhwvgtb.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2owyagoht.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsppdlg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbangqv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qmapvrny.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdledbsp.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2poqlvvrm.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fakdqmfo.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvifvww.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2slqznguu.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2obdmcaaw.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2rssudtto.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqolptgj.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mymlyraz.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2njtnlbyi.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2buwzbuhn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvenffr.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnjdmxg.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sirnlcfo.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2onagapsq.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuplzlj.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfaehilz.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uboyyngp.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzvmwbs.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2loopulaj.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtvtkcr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlwbgbv.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfhjkgl.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mbktbrsm.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2jxutcngg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxsieei.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xyiwhsch.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlwddzw.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2auqljboa.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cktjykwl.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwngbsk.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmhaflo.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2wfshecau.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfpjwur.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2hiagrybe.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjuuypp.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2umokwzox.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qwutcdoc.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlksqtt.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2idkomhao.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2opmwlsxy.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsavzxf.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmlpwpp.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xanhepfq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2btxhuqdx.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ndurdapc.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwunousu.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ieveybri.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jslbuest.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2euhrtiec.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vdttzrph.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxkcksm.html


<!-- 参考信息 -->