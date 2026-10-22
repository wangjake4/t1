代发 wailian999

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhinszy.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfapgrh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdjzzof.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgopjctk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2airglsvr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qvumhcbc.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzubugs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrhmqsb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxcadzh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gocpohdx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnszynv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhmqlzs.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2iwebuhyv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dusaumaj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kygmjjix.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjnnykp.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2whdoyuge.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzwzhio.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsrwspa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2nymlmdjv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2omovymcz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vphunfee.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrtvifb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfjsaok.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2teiwchwn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwrewmw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2crasuqzy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2wobcaftt.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2nadauuho.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2yibtmtiq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbpemgk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyrrich.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bffbjahv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnktthav.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2awfnnoik.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyyvxzj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2egvnzwxf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpgbiak.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzwvaae.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkusick.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyjyhfn.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsviycg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wapbyksk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjfgiqy.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zeftytll.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sywaznkq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2augtjzmi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cragnpaf.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2iyflpyng.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmsfphb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2txnjrmmh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nivrxdac.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2cofskhwu.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2akabsjmf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuneqebl.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2lypwbreo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrvckjv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2rsakewgf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbsqggh.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xurywpaz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ifephmwp.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnwnjhm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqleaby.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sixupswe.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvhfvzv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2osevvabg.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkhadlh.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmlalyv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ekktncjr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeuvkjj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2kojkzdad.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2eralungz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vgndimqt.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2apwerkbd.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2eovaqixi.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hexvbwsa.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiqyywq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkteeyx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qthtrkuc.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2djqyicfj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2aofdzkqv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtoioxo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2idomgfbn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvfrzmb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2rnynqfxl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmsfwiu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsiohwr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvdaccf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfqgakl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqkofuc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsjcinr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcemxmc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjabeoc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuoaqom.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtiyyot.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2skxysobr.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ixavgoaz.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2scjjgolh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdsuuxf.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhssjyy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbdfezu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxuwmmu.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dkenjzip.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxcpzsp.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2azzyeorq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbknbjq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpxrvhs.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xixizlee.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2benhjaml.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhwuwcv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnqwkij.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2emfpdrky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfzjcmk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2rityxaqb.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzhwzbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fokbqohg.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2abtorojx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2strbvcem.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2llqkytla.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nucjnlsf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2uytasxwu.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhnnche.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvfpnsu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2dhivvmuh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbnxxvp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wsocrfyr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2elelktjc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbrazev.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2vvatpapw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrosplp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2iapmfkwr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfyyess.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhyppwn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnhaddh.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpgxyke.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2scoflchj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpggzyv.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoyjgun.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkxzila.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgainamr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fftkpxdn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wluzwnux.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mecfuzoj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjxtdpc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2klfpprzn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzkttty.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzguqmct.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2getjcebx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwftkdya.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zznaixol.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2upydsmny.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfblbkp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmdhalk.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfqlich.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcessysp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxyvqlg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2insnycnv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ustdehvm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbosdsut.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zstpcgph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cugplvmq.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zadjnavj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hohsqqzl.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2urscbyly.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2icixarsb.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rgouxjxs.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnxasrd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2qknghqsx.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohriovwx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyowntc.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrhadod.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuelsew.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2vsitiaka.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcgfnqe.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoaynpp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjairfk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2djnmujxd.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fastldeb.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2owufkqrc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2cvecoffy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sokukxsx.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kntgvidx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2lreoabwv.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfqdcbk.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2usnspmej.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaszsgtw.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnfrfsa.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmrtrxn.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxbbbgn.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuiovkv.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdfhtrg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvlurss.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oydsuycr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2onrtexru.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtalyyz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2tjblrqck.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2stxjusaq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbqawed.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2wiutzcbs.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2psovrzbt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kzakkebf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqqwpln.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xlohtfeu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qxolidxo.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2udeznczg.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ockiltma.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuldiwx.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rhicmbmj.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2znvogsoi.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2omgfkroa.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2csomiaan.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2uukqhpua.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkjrrav.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2opdxmdjw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcshtydy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhamxoq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvciuup.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmlbwhh.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2umxfsgda.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2adjzgbcn.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cuoxuvcd.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcdmfmv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uinmgyou.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmitubnf.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjxztdt.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2eofnbtft.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2cesrpnmz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qinqmktt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pohwtyet.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnlotfb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2eotzufyi.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqxnafx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieosgriz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxfzjrg.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qopcecgz.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2aexgimiv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeftcii.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrngtrh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2anznwpde.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfqosmq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2npicjcgp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2aloqiarn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2knvgfwdw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2svbfvfun.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdzhuov.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2udweeeii.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2xivzdkel.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bhleumzb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrvjvvh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwpqcgg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjxhbjz.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2lscfaqhc.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsfpevh.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvrqkji.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kswdoaaj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwbutar.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jknbuqwm.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqlureu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwivhdbc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrzlrsz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkkntxq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2redwnbey.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2phqmrzel.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dizkfdwn.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2trduxjkg.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmmkxgm.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfhslyp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hspcqgrz.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2trjmmtib.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2npcrfufw.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsijmlu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwlnlwb.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uubtedle.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjfxsed.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2obpyhsmd.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2oppvvimc.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jstmshoq.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjptuwt.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xprauqpl.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2avcfyfjt.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hebukfrr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmjqgjj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjcftsg.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzuzsmo.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzxgiae.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2cewosmjh.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdtdznc.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdubfibs.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2scfzinvm.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2radmtxjg.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2jiagcizc.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2thauxnsx.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzgphms.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2gakkvpmr.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2gboetsqq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2unynwcoz.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2jttwvdsj.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2sigtmind.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxaoegq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vskluzex.html


<!-- 参考信息 -->