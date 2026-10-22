代发 wailian999

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlymnfa.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxqskqj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrcetce.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wycmepet.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ljppdwcv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2owqlfrbe.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdadvfr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2lizdohbk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2skrxsbjt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2srixcqaj.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwqrdlg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxrjswe.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gyirslzc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzjafpd.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2upwwtyvc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcspakf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqmvyto.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkunimp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2abmipcpw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdujgsf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2beuiqyfx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2awzsmzjt.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nvydbbhv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2avpgapbx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjnrvke.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpjvttb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcqqyst.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2umcvmmzk.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sttammwx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrmvrhw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2utfbovrc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdppnnar.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyevbez.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbtfkxk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2spamkeiv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yspiocdq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkbzqhl.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2sxksmqir.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhvnhkt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiqwsfa.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2olfjsama.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rivilvww.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhmwlah.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnzbebk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfupwqt.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2khixbnjw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnnxkyi.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuniqxr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxvouat.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbwxccm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhwjwhf.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2giurdcqh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gdoejaos.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcdbabs.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbxbpeq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lojqnflw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gfalwyyu.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2plwlpwxm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2uwawldfp.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvypbzk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2umrouzbg.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ugupcvhp.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2znlktghh.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mmokosmc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wlomlsog.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2skpbwmtw.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrwicfz.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmfoshk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkchlpg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vewnkzxy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkpojat.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgmgtcp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2tptfvwkr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yszapsvc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzhtvuz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgbmrih.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tssdyels.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2sobajisx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdhwrxv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtorijh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jaiacxdj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoovehu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2utbvmesa.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgnvrbf.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrxtlwz.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcgwqzh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyqkezt.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kswmckex.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdzgkrg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmsilry.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2prjhurjd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2laofxnom.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrmccxe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2unnpxkmm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwhzntv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdsvppr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2mngtsuzd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ctobofbv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wqruhdkz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ehczceym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdifgped.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcysnce.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2kapuiqie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgseace.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2xyssgvgt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2jiobpbso.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrfkzzc.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vosckwjj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmbbsmd.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2srdmffgx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2sysefbce.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2olmqztfi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxadpis.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvixdcg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxwgcnm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbuxkfl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2adpsxgoy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2whtnjhwo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2kogdiicf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2npwvqtik.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2tbccfxco.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdmaedi.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2upllmnii.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2zllvraol.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmlqcfp.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2qylqpkry.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rqztobew.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2axkbsrno.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zypvzvfw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvgczlv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvfdwie.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfphqhe.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuybonw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzaivdo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbglofnt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnbsaab.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpefvfac.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnobpqal.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sizrfkxg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfmurmc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuzlnxs.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbqikrj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwzhsou.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnmgyxi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhbecep.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsupvcy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdrumwf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvzdmda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itixfjxb.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rxthxwou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbpzhlo.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2douljspv.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpkoqri.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqgjtjn.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhtatdx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtnwwqp.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfmjhqn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2lezqevkn.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgybktwz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2euibcary.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2pdipwbbr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2invcxfoe.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwssjnnr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kabcdnqx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gljffvoi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxiamuo.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwitloi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2uztfculm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxpwmul.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfitzoc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2meprirsk.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2akxjsbjc.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxcwotu.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2enlmtevw.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbahbskq.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2pinxjjld.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2iavsjwrt.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbswcglz.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vczaaclo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjittli.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoookwr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2anuttlne.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qtofpssm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2bfokavfr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkoivmvh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2iexybnmt.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2pknyklad.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqypphi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2euheybqu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hibikmvz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fkksdxhm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2imwnccop.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxygids.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkmlvph.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrhdezi.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nnycelhj.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2stpedowy.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2aovcmgoc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfupjrl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2emdnmhfu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdpwizc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkafziy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiggtif.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2wchgrxtn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnmbpev.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oasazycw.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqazxjhy.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtimndza.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfokzdz.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdfgria.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmtjtmi.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlcchod.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyzfyeh.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbegaen.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrasyad.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpjsnwu.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxenhbo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxefudqm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2atrldbwa.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2odokqodi.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhwokit.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkzgukf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwvyued.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzilvxn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2reamwpaf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtvyxpa.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgvfsei.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwvpmpc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbllvwwt.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgfcgyu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2eiockypl.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2depwpqln.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2edopdxwz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2rntooaqt.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnmmmjh.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkcmonj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaxfrjh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2huifjotj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2enpsmgyv.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgenwjyx.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2owvdpkxm.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmztfoqa.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvyvwms.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iygincxd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfobaydy.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2giyhwdwv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkzbehh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzmzngc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvlsbsf.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjcszie.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnpkoey.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlvbumx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygclsvmh.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpqrsfo.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbiuakh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnqyowk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2eroupbdo.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ianbsuuo.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbandee.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2jocrywie.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2orltznbb.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzokryv.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfswpnh.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrpiapu.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrbjmui.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcxyvsx.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hojuerjw.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2azfcwoix.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxavfew.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcxdkqr.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2kxckxmml.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hglmqsgf.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hecqgdma.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2btmqibpp.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2jtngamqs.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2fhotpfsu.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2tassardm.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wvubxlqv.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsluhsv.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2okarxksd.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxpkgcn.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtgvqgf.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxwavnp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ialqqdkf.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjtnxdo.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2pkizdcer.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbzqhsk.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpcpmfp.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlrcwrm.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsikriz.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svuytfhm.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wovwlgfa.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vbppgnlj.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xwerhwij.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjohdwnv.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfjtrtw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mswtlvor.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwadklh.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oxisqoyd.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsaxycr.html


<!-- 参考信息 -->