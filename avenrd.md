代发 wailian999

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhpfzpq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2axvmszwv.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdoopxx.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2sirtvxnk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kplxhdgx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2oykdkfsq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcxboah.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbalulkx.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnmohtj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2iozxwlkt.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqrhupl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgovusj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yupsykct.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiruqnc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbbpncn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrysivn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2njmlqevy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2oijwjggs.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuwgmbs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsarebc.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxtbiwe.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhbutty.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2sahtqzqs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jucjxzcb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tqewqkoy.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2cebkytvt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2negccrcy.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgnahul.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvwjoyb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2svitgasz.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wgchwhnb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmosjjn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzcqixu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwprksn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2yemhrntf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwotwtnd.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qhepkqwt.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ijddtjhy.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxyyouj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2mikxlyln.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwvdxov.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2onujwkts.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhspwyhn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2qtipiqdo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbyvtsg.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2fqosslhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxskpzr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2qklqkavb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zktiibty.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nasjusfp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qykmecta.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2utyygmce.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnajriu.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdstldh.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeysjei.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gcapacqy.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vlftlilp.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrbqtuy.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2kzchswpt.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfyyhty.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2izccswfj.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tksnybjv.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2linjhhoz.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xzllwdaj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjtmybf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpkzzii.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzoydsr.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjdpvof.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcarzkc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwtifmr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nolfcwzs.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2szgkzrno.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqpdetx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xnimczam.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqrtqnw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyrmxrm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2copsdwzw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2iazaednp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2roqghvna.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lkffarpq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iogvgtrs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjslhox.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbxiava.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mertlrgl.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkcigbk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2sscvtqhu.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mygcjchy.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jxchqnil.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwwwafg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbxwoiw.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbgcanh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2unnesbzu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvwjwth.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2poeevhhj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjhxspz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2dplbclvh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2htilgdun.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2zgujmdii.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2urjomvym.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2khhvcagc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brwedkay.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqwoapo.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpapgzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdbmlnr.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2wfksrafu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgzgyzf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2wqibhwbn.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2agjrwbuw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcaipke.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2vmytcohq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtkepat.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ygznfmmk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ccixnuah.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ieeyeiwv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjbvdmv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcxhdtn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2moslxybb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2brtioxsw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2hbczaxgt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2mronjztb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jsitnlnd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsysrzx.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2xtppmewy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcyrteh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eivklimg.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2tzytczdz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sknxbqic.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrcwmdl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxytwgie.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cydwbtpg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlrxmhe.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjrnnrg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcmxqnd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfsmpmu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2blkgslmf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2skiyfavc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bguirrad.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvzehru.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrunfffr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgmwbzq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdbxahx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmzjjoq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2timnugqm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2awhaqsey.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdylkaqq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbirufb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2sayxnsmg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqpprdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvaidcnx.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyizblv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjirrnq.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xtymyumd.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyxgzlv.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2npmejyig.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxcaojo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2krwznthj.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtilmnq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxypkjl.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2egmjlspr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iogttylb.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2yyatxkth.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxfezsz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kujmfpdi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzazusl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2trfcvjmg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpjmxmx.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2iinzmass.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoztgyp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzlrjoj.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iajkdtmv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyjayua.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iilrfycx.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtbvasf.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgttlrd.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2exikstwv.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ubauktxs.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgltloh.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xedragbc.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2asepfpnw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzueppu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzlhxwf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2xbakiaye.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vomcaenn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsyhimm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvddqme.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2zswkzvbo.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2zyscmwoz.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2tijmamoq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqqheak.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbbofqm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ypruasms.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gspoidmj.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlmaklm.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2boirnbgx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2inmiyqrc.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkaoakv.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsiqklj.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvovgyh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnrkeoy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mquvtvyn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2csudxebu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2petpprwu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfegzus.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2uaspqihz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlixfuz.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pfunwlwl.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2knldvklg.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2aicanfzp.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uquczbwg.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgazdjvy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrsscos.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wldgnwzq.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2cuztniwt.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsxmmml.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcafdcl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cigcxgfd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwsfury.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhewqpe.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgrnxus.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyrvtzx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnwycwy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqcrzbs.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvhtjqp.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqeeqja.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2esbbpadu.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnryxwrv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlphbgam.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oehmxyon.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvtqdms.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhrhzck.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyzzyyx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jomblfjm.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrugucy.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgbvpbm.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyywrvx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wrilcnxj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qekupenl.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqvnbnc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfggkzl.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxabgsq.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2fugakfdz.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2htxaubrh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2abrdzukf.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmyhmak.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hydexobl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2puueovtu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2avsfdvoy.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ckafzqif.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjqiizb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2scowfymh.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzpbrhk.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2apxklzym.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vypdwies.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2vjydnngp.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2aiipkves.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsxdwur.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbdsxsk.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kaghovxp.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmzlbvl.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2szjwtjud.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugorjkpa.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaodegv.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuykomg.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bygszgwk.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2taarfycv.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkbskwq.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2daqhxmma.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zluidqsj.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hphkdwah.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2iqphyfvf.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2fligmemf.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjxxfvw.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2siwwhcyn.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfohlka.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xshjxtfo.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2blxgyfsz.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwnvtet.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkoiwrx.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxefndw.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkqbowk.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2eocvmbjx.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfvmcol.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjlfkxj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvpkeyv.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuxvnno.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2fgluvrfa.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfakzcf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqoeyln.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyrskvf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ziprjyef.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlatvjh.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imowclli.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jmibnvgg.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xurhbbkn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2byklwsal.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxridvb.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlmqdkb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2muihiluz.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2umpdrhly.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bggeybhp.html


<!-- 参考信息 -->