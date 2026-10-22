代发 wailian999

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmgjkss.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwybtnmr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2phgqwkdy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2quuxqibs.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2niabrgmj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcgawpm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2phdssnll.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrbnohc.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pyavsvtx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcohvzx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwkgvij.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqypcsap.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rjemelhk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdteojtf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pufcdegz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iptjrvzm.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqgczqs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgqltef.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zmryzerh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdwarnz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2spfkhteg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxsckna.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvnlcxv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpiculu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2envxdgoz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbywzrp.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgxlqyk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsnwahz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdmrupd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxiketi.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2itrwwkwp.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuuwfvp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2praberuo.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2huqrifbd.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wesfcnaf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyentwu.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dlseetjx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2evuuchin.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlwaxbb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtjkoqe.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tswygwwe.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2uidunzti.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnzmoed.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2plxvnjwz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2vevuaxyz.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgfmwow.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkuwhch.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ximosaal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uxicbgnc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tduijjvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svhpcfnd.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2oydzhbpk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rgodsxyq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxelokp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rkddffdp.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzowmgx.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyunsqx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjafjsg.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cjliltyr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2teddybkx.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxyhzlf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtkfibz.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzhrdym.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqxehnc.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2buzhhtot.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yvijuhqj.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2khctwcfb.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2odinlrnh.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqaxgck.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbmcwlc.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2obgwfdvw.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2oxemsars.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkcfrhx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2icznhtfb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfeypgh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxoddfm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2avuemvww.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xhshcwfi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhdipwu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2edlptckn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jnihzukr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqaqruk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzuszrm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ahohhnmi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ughontnk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qarodvws.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2arhnehbh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgcfuky.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzevmnt.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzviaqo.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdxthre.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2whjrwicv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtlloub.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yquxnljv.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhztdhn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2krafbqfz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiyrcsp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2acjinppl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjzatcs.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2byheukbv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdcvpdn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaxhtjs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2reoogrcs.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwksmkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdlptix.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjdvvpg.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvkgozm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzdyhmr.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2guczwuet.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2sahnfkah.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfgglav.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qajvblue.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2usgkneqm.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwterbd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2tkauqdgc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2nbebzlev.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxxsxay.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqqnsbc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mebmvbhd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxqbijj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2pgejvdox.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2thghhitu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2absztruw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2whsugrhv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcqsprm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzvwzov.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2xxytopfx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2onesatkb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rgurkmxc.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwxupnz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqlravb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eabflhnw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cordffty.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsuudad.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lypabtat.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2culhfhuq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsvpmsa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoaxeix.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bajkisgb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdribwee.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jeruoojj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtdunjf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2afhaezav.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkknaxz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhgrhvt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lncjlcov.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmivbtzv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcwwrvv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhenziit.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2llzktirb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ietziaxx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pacdcvna.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpykjmr.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ityjusbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blvlhclv.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvwfuth.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2klfunrbu.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2woxzjwqq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rdinomgm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkasdyr.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vabrigdd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2edxucxtc.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uswzjesc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjndmked.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzreaqy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdkwogb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoxfzpu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nysltkol.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aizpeeez.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxdonhw.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqjnctw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsyymyy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjlupmd.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2twmccyzl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2glpluzkn.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2crgzpfxq.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrcaybp.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2staaduur.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pezpjenp.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2zleshyim.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2budycdik.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdzducp.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqdvdyr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwjwrkb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2awhuegrg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpikfjz.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmsiuxz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2vsitwtik.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbaqyfar.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2euieoisg.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2eehmkckl.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtfdvje.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsnygda.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhhuvah.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gqllvbxm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2igkmoyuk.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pktovlpo.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ussqyyyb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pderwini.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiuykkw.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqdwuqc.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2eisggnew.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pycdgpth.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpmfeiz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtztdfum.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2pitplkvz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoohmzj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2yjonxgji.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbqtnhy.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2upmblbsw.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2secvibuu.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcrgojr.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxiajfg.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfcvwhe.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyphahhw.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2htrryann.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ybodguql.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuplztsc.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2ukufpdhm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2clqzbtrc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhoahycu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qomtisfl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tljxeaxo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvepegkb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqgewsx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2juglzsye.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkouvrx.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2swpoeebf.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhscfhhu.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvyxluw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zybajcpf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyqjzsl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fevhbwag.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2undqlzvg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2gadcxliy.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aycwevkg.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoonqau.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2awaliuse.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdfznbv.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gwypcdmj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyouvnk.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmmljbd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgbcdmn.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpgoggp.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqkwcht.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2bulyajyp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2frdhpsnk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgyqsgc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrupvhie.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iruyeimu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vouemmry.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2uarzcyko.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpwlgrd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwsayef.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kyiheorr.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvhdtgp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2urrqosju.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpkghmq.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2oskreoqo.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wumcjgzs.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuntwnk.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjpnytb.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2otiwldao.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpctqhh.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmjvrqd.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzkcxqe.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxqpebb.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsntbic.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyghclw.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezudkuwy.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmokercn.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2grunubjz.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnvgpep.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiqveyy.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2wiucnlmx.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zavxmcow.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2icyejcca.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2bkodvwnv.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2reouphix.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2erzbonxc.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2agxxcesk.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzsshlq.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhweoaxy.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2etoffulp.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2lfawcjye.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsbajfn.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjafiuq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoellmdq.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmnooci.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2mlornohz.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2hkenyhol.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdvixey.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjgfjfv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ffugvjau.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbewqic.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwailzps.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vhftuqzl.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2idtfbsnd.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nskztkab.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuzptcb.html


<!-- 参考信息 -->