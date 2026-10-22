代发 wailian999

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ysarpfvh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtfnjii.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bttegvoy.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpszsfc.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpgixhg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2eoctujcr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2whmchtlb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jstzoyuu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wrehpsdz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaiwtpuz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2nekicoyx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gmehtzks.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmuuxec.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaethjg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwjfuwt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2iugynahb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2coqzyfku.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2yluzoetr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrwmxdo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2nboyksjs.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rflrwlyi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrpjaxt.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjawdxv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2sjspfyxq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcmftxu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdepkxf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgdsczt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrxnfxu.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fjelfkld.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sytiwvmy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sziecvyn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpgrzij.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrnyghb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzmptzu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2khotfmpq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2klsdbypq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxpaelo.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2uexwumbz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmfrvly.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2alhjgzfg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2atntmily.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2isaecgfc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaksgcs.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzebdsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzkmizy.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2adtxugkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxakrezb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kykncjhs.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2afczaquf.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtqgjdy.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgyguir.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qqspirqi.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iugagehy.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqrtmhr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tabxveye.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpljsoa.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyjnxsx.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuevpwj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxmnros.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hpixhedu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnjmasf.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyyyjyx.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgcoswa.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uemngxnu.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlgqrxz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpkqslo.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vybubnva.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnrhtfb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzhrhuc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ihacxdkz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2boatswxi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjvkynn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2quswdoxw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxmfphz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2drmomiis.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2cacphqgu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nqztirqg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzmyjqu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fhotcysw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnltmnj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ekstvxzt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fohoyjew.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2cczehsxe.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgbctoy.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzoxkje.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2fkppkzwi.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwflszz.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wfletmmx.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvkrigk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qeouirpw.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2awhumbie.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2diajvuxx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2sicajnwx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxmtjft.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqaehuz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2fqczmqrm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2anjnmeif.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fobjcloz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzojhuh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rommaiiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drqbtode.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbxzbrv.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vaynqvqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knatehao.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gktzybvb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxcbkhe.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2wltzdnmm.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2agcbedve.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwtzfrm.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2avwtvzke.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrrgkmr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyemyik.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyjggfz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzwjzjz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjfspig.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2okrfkcpa.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrilban.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ymowxfgg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xliddncy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2euvdxnea.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zudkafqh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlpjrdd.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2nmryfpku.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2vaovefxs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmryxhq.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2micihhjv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2orveiume.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsernprc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqnjpbh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hagupmep.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuwzfqd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2llqyjjlx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zeytfwjv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgxixzl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmyzdvc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2krfqnwby.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2olbgnbir.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkiaykf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxouzxrd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxedpdaf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpoorqq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbipkozi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffiswlpe.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqilptb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urrqmoxj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkojojcv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cckjekzv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2avnvedam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stbbzsbq.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrdsmxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdfasyd.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuljghd.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoirgbin.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ahiittdy.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqlhdvw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzalyazr.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuuyodi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsxgyvx.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kubvztnk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnjobfs.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2qppuwglv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnwxcvj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrykaoy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2auvjxtoc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zznlntvx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2evvesbcl.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2kixdlzuy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsmuuap.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoohvkro.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlpppuc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2dtalbdcu.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxfxvms.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkrzwwo.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oikazmql.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxowuplr.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxyygum.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmhtupk.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2abvjktir.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2feitrihs.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2blsjhzlr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjudxhbu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmkfdsq.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2domvnmyq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmebyse.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvucrko.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsvsqig.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2pjelidbs.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xoldzrlo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fatgdqxi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkqrdat.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iugszpcg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eebdqibp.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwabbhe.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhafbbj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqgjtvk.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jymzrpkw.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gvphkllt.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmmvwgz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtofcmdb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkzlywz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fumdmunt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2talcnwsx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcmwieq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuvhkog.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyzyoqc.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdcribt.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2waylbeoq.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2djhgakyc.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmqwctd.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxjvtml.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2byvejaca.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2axdvhfiy.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ackavyjp.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrwrmyi.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2dmezirmv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhovyft.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pktbuepc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2juatwtzw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkziqzkg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmupslko.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fclporil.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvdboxx.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmghnumm.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzcejbd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvbmdaf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcurtiit.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfylyppm.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhquyvzn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqnxnlj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2cthpkfwv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ffytylol.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxocvnai.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnacsciy.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjztawv.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2txtvhwzf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwwnxdu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqdpfmm.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zncrhvkm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2makceerq.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2uomtsfxz.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqwfmmn.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgspjejr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwgzawm.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijykywdl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnnezlh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqudvyq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2afzouatq.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhhbuwa.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlifien.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkurmgd.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrlubmr.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2foiostis.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgleqgff.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2bovtjzly.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkyhqau.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2egyramzn.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrysurf.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsquwqqo.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zspwlktl.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2moilkcgy.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxzkoll.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuismhm.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfstsxp.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmqvrin.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzgsezb.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcqrbbv.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ceioomyc.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdsimzj.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ekogcdgi.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjkcgas.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmgltaw.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxwkavm.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2otrgbhzw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrldhbn.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zsikgdju.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxigwli.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zasyhnef.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dxogbdaf.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2oktyyobm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ogonswct.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrzhybd.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2btelaios.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxgcajv.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2evtqgzew.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmjpbyb.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2klxrapze.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2uenoxxva.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuqlsgf.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2ineflefd.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wklnrcza.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ausxudje.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdohbzs.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqvudzf.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsiwbrw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tysxuokb.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2exgzbchj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rmslnslm.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcgdcvt.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqggihj.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hiylxcux.html


<!-- 参考信息 -->