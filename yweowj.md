代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkqczfc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvqzqbg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlqzxgx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdmqjfs.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfuqdtg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kindwqvr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2aowpvdrh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmdllva.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2idombtxj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgcsqtw.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uioxedil.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqvktaf.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvaonoy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2frcbipnh.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2cddizsam.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvrzpwz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zscsefpv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2cveycbpu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2eswuftgk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsdyggw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2srifiqko.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2idzxqxny.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuqtngr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2obgzisko.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvelslh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrwcvau.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiwvjsk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2alukfssb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfdwkni.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuomulr.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2iplrnhtt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rtptstiq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwqghsl.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2okfmpppv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkgtbep.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2beslmpdj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdbtxei.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdozklt.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eliqyqov.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhqmyew.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkvplbz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvxoeaz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpbeapd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ribtmgow.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2srggwapr.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhxbzjz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnhzfsr.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgexhbb.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwkjwbx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjradnp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2eujcmuif.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkxbzzz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlafjdvd.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2fprldmnd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqiktzzt.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwobdrg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbgaiis.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcyyfrv.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaoyxub.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmcjgou.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pluonoug.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhpeewq.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxrmnkk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsgxksy.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2aivqllwr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2koudsotu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyxwbcz.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ewljgwsm.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zphfvfpk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xnixbpah.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrpvyts.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcwgnom.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2isxqclva.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cagoyiyx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxglnfq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2kstwogju.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2aebeqfuo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zolhdamf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iiobaaek.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeuzkwr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2sydfuqqr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmolaku.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtsynsh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaedfcw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkxoons.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dypfpzfo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ydunvuby.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsuqdiv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsfdfmc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlxcpsl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2naxspchn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqwcpde.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2lahrpcga.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2rdytaiqg.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kbygltpb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2akopmwcx.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaafzik.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ireiooxh.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhpkzhj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhofznz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2asmigoga.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2twsntrzl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtfbtiy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2azknoptc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2sunuwlyk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ialufwmw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeqjnwm.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2svsnouqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbimumb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2qclxnbhl.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbjrtou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ezojvkmt.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmxchlv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2obzfnzih.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsenjph.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2geudvtkr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxhsius.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2fibwunzb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2zupfqlof.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2izuhuvwd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2qynkwdeb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjnlfcx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xkibfycf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2iprtvqlr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2rojwblyb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2clidkyqd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxkogag.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdvicuk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhznlhl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjlqlxa.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhjjjag.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzvihic.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vqozjjas.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2xeflwmag.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyhrlaw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2odomfrsj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmlcsyr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qszytozi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkllsbsr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bccvzmco.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjomfvpm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2psmywuaq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2syiifulo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2asyxgdwg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqytqwst.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrtlqmo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaghthg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2udtzixtd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lclmijim.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyxbqru.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mojcrwqh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqytziks.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2luncpmyn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkttmleh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsgrbwv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pogdjhbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhegvxqw.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvxzldg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtvwioe.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vffbomqf.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2kefrqurp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rallhrhw.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjqmoii.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzeulull.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdonnxju.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2syvxtaei.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbbjgxi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jktibplx.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyszogo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uepzchxj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zelczenh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzywvqh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gokodiri.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkojhae.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2irnxwacl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2sqidocjb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqitbup.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2smyxcxjx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2jikrlhch.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sulgptwy.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2teadhfuj.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdekuetp.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvdcmth.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2grjpfeda.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpmoqij.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hupmimbf.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmxkkdg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iammdzaa.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tswplgal.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqvjwob.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdlrscr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2leledrjm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwzyzuv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrvczgz.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhcxdxd.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2schgqlkk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2comvpjop.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pvayxlam.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmdcnsg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyjrtgd.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kfehzear.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dithtlls.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bssqfzhh.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2etxmhzxm.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjkokrj.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpudazfm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2shwvgssi.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkafgwr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lchnwpvt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2iizqdgyr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmacbwdn.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2sslyfqav.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhacppf.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwwsccc.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zalpnubt.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hraejspf.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnnzatw.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoygwdc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxtxanv.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkagqjas.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfyjfss.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2npomqtvv.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuwxmbb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2siqiilbo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtvglye.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyolzuw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjahqwi.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlokptmw.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzyogfp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2bfttromz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdqooqb.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbxttuk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rikmlzgg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwkundc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmsvtoq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2janavzet.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfysqums.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkgaazf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkojyqh.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmebwxe.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqububof.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgxwrkb.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjaprtb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbizxns.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eaodhtcw.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzrjdej.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2rbblsuci.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsolsnuo.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2gepvkkwu.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmykwgwc.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dshkpzmx.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rblblqyt.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmctkuoc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmovutd.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xenzfwbj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kprqoade.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2slircsgj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpbpxmw.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2siuhuycg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zapwbigr.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfgzvnp.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2gczyadtr.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2byvdbfjq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjiivwxc.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbhmyzx.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmlnyqh.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nskgttez.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwynicti.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpykjex.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2eakvubxg.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2btqrsaej.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpeybox.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2itppmjmo.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhidyyl.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2smtdwzxl.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwhnbca.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2kbstinaa.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2chjbcdee.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2fubwksoi.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyfewwv.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2gxotwjll.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnodqhm.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dyztukwq.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzajuig.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkpgzab.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nllpsvjr.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcflidww.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgwyzpa.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2vugwhkpc.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhuiain.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2peglizno.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2czbkzwkv.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwcoouk.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2frvvtgxk.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2eawlayxv.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gsblpueh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnybbzqb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ylurbshe.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxnkjme.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lytmwfnr.html


<!-- 参考信息 -->