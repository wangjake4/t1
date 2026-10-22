代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkqkrmh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbceiou.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhpqlub.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iblivugq.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cetinmdj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwcrdqn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjxuksg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeimicr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmbwoxq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dbalkkgh.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oowbqxcb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdnaijc.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dqugiliu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2copfhmbk.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvmkjmk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzwojmm.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlqsuyb.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ovajfqgg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhqatbb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqetnbn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnjvbwm.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2zixhfrmf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmpxcdr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2uezwspvw.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2imnptost.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoaoxolq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2quqygatn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wahqiiqt.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuzseyw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnmhqrg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zarlykhi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkrtfza.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiubynf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjiaojs.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehncwfoe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lswnsqcq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxvgdse.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fggkpmtw.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2lcejzoan.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2keknyavt.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gkadcixz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2padxnfrg.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjfvxgn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzaopbi.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qruqaagp.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2btiehwib.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwftuas.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmcmbbi.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2isqmltbh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyoottj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnwcrgm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usrwkjgf.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hheujxey.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvcrmqp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkqafph.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qcelcnwe.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgwpvwy.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoqqxte.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwweeprj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2akjmqoiu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbliyeif.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnjzonh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhveceps.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2bilgjyyc.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyljoxb.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzieown.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhuqwzw.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gugyqvsm.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvfiwag.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rzeqqltz.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvqseng.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2grwvdsav.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vupfuwku.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2igjzrowu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2fedjtffb.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsjdsyi.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tidnjfpu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tljcwajw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxjwxzn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfplmbx.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vhorsvxn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wimibxot.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tvitbppt.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkmetas.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2oydxgogx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjcrnwx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrdojrc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qfopewtj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2teyqifky.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwtngvo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kywosrcw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pswjhmpd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hmshhkhd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2stkypzlc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvczgrl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtqqrfh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsiuloj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pliljzuu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2cfslxgct.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2stbhqyaz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jsllyzgt.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2rjunfzzc.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdjexop.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwfmibe.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqlxlpe.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vvklizvr.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2woqqrrju.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlohasb.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2mibnotsu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vurylwod.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2piluubtn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2oszyrwnh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2waradsro.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhgpyls.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjueyez.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2nxabaouk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wipspawn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzonxosx.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2strrgtzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otlaqvia.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbxmfae.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2jwptmimx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zttumxbn.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaqxkjf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvwchyz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2xsejykgc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2hiruixsa.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2tomojvgl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2btzrjubs.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfjbewd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yohzskfh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbgjnea.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnjhxxf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2rckffpui.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ewygfges.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqvahqn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yrypnzia.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsaxssu.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ourtwmkf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2bebaoxlk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cududsvb.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2przilypw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuolrgk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfthrphe.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlonkxm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlihrfh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2isljbold.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wakxjobn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqvqfmh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkrydke.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2flqwcogj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbhhvzh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjdglac.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcthgpl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwkqrzq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrbzjdj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzahqtd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpithpzs.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvbipyq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjfuwqi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2akcsaysk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxqwjkx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ianjdwjp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zllgsmtp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrlwpyi.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gghaedrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxhvltg.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yluojwvv.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuqztru.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2evqpfdlb.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2baxpewxn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvrcdlf.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsskzvev.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhkiloo.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzbukmv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2crptpcla.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2kazucmxt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vabcvcni.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jihgxuwf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrhrnxp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bghrbvvj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgytkucf.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2swutbgri.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yupijsqe.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uupysybi.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iyogaamp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwmiqxg.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnewnez.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqacmrna.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuzckrj.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zceiyspi.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmxgkuo.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxnafuj.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaninpxd.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhtppma.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsscvks.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwenkjwm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkzvzjw.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmkxhkf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhbtpnc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2vifqqnas.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkvxqlz.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjkxvgi.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2vvynddpu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbrtbpk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uylvjzdz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcmboti.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgmylyk.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ekspgbyl.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tvymvjgx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tvknnhqy.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2okwgpqzm.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbrnxyw.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhudkiy.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zumriejt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcsykyu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2oarxwpfc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrsvolr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxddrvz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2brlcnovw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwogijqj.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2izuagast.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsruaapl.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvscgqc.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeoutsz.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvxjsvf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qerjvoin.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpdedvf.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2luglhtdz.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhjlprr.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkftrta.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcttrvvc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxunkwd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2anarysqn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtevvbq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyzzkxp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoaryyc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2lridtvbr.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfpudxj.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2khlufmjw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaguteg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hizmeinq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuiehdd.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmhhlnh.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2szeknpuf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2texnomwo.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2bczcasgb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2odtvedgs.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvwhpuz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2engorodm.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2sigzcrhg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkedqny.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnttswk.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ututchxq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2mojwjvqd.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcfiysx.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2grnzegwp.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsujgiz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoidjhj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcudsdwe.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2djoqxdbu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyvcknb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiscymd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2baokdqyr.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtetjdls.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2oaszasgv.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrguvsd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2owddjrrr.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvmivkz.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2cfskerdl.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2eutfutmq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cepnwduo.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhsnidk.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnpqbpy.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gaskqnic.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbmrgdj.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmbucte.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtlwbcq.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzhabdy.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uaetamkx.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2euoioxyk.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nknjhflz.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2oegrybko.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdxzfhd.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2imeavyhe.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2fkglwllp.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2kexrltho.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqztmou.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dtklkcxu.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2myxfxizj.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwstarl.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2uzatmxvk.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuxsnhl.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrewjaf.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2uoccyurp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2vacgupuy.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2okzlpohj.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2nztrdnwj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqhoziw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2heyxddfa.html


<!-- 参考信息 -->