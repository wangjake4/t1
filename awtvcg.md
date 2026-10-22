代发 wailian999

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqxlmao.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2uqouafmk.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qajmovqa.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2escazfxy.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2seqkjkgg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2keoffyww.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pulybrwf.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjvfjim.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qtccyrpp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2idfpfjez.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvjsaux.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2heqomfmy.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2afkqtlpz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsghypy.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ealdatkn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqtydly.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2laswmscl.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ytiqdjht.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlmqyri.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zduhwcew.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgwoave.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwazocj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xculfnsd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2abymbzor.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2renanloj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xorlsrov.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqsixrd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dygtjtjk.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2drjjdoeu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlxhvsx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbccsam.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyzzhdn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrgqbea.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvplqppu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2twqsdcrt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hogfqfnw.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2crpndopk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfkitma.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2flhqtegy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrrwpjd.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2megeppef.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkrpbux.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oxttihec.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2bwufozpo.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2thkapasi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2crcmvchq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2omkdzveu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiipitz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zeshmcfl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdudsqz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2crdefmiw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ychxlfdo.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rhycyltd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyddkkp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyaohol.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgldkzql.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmtqlbj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rskrwgvp.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjwflpb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uanpzjbv.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2oemqcysy.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2npgtzpxh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxkqlvz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2setjafmb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2eyexwhqe.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2taljzwlz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvbbgpd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhbepze.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2duiaweml.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyexqpj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpaftzn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpjnqwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwfldyp.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjlanku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaiazom.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsjehrw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jqszzrxc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2aynwfpfc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xauokwce.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fdagtgta.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uiennoar.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvcjbgj.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhwvygb.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2trntxrst.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2oygjrqtz.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mshfljkz.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2xchnyzgi.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tdikernz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2whblojkq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzihkbq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdqgplv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bccygmbz.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cighpues.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gypducfh.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkxyzqq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeikosi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqhfolr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zirupilk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2idsjyfeb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2abfshhff.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2hahedwws.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xsucjwyo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gehfsvlm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcgvbwy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvrbytw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2aznmvykk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwsnkaj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfkfqjj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkkvooq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vwafhqxi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2vsubmlqr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjycgji.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfiqcqy.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyfowmt.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2blkabsll.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhguksx.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2klpyfcgy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dcolqyzu.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmxxiqn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2folofyfi.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2sigmepgy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2thddkozv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjsvnqa.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjosqdf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2fnncxmxt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkkmwwg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2umtmbqke.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhmxbon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2albaeobm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtrnxba.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmklmxr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztglxzdv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2olvyzqbt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfzbdgb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxjazlu.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2extfwrjl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmdjpov.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjdzaki.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhlzwwg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfzuuug.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrwxaaz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvwbgkv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lppvzdno.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpgumat.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyhjwlp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2dldridbp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2djvkjoir.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyotufy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2suvfkjkw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmsdter.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2elkplyct.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgrhpuf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdzixfv.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ratuoubx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmhlnel.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2srtubteu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsmkvxx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjeermb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fybswvwx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dphfbxsp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhukddf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2intfnpfc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rykqorue.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvwxarq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2brjbrxem.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwbgviq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cimcfwoz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmrmrkr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyjvgud.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntoyuyma.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fejqwfkl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvqzpnv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlfspjg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrrjrrh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsyfbpb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfmqpwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlppxvtv.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pifueuwn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acxdvxow.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cyevyrdo.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2kppbacsn.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgeapjf.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjctawaj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2awdpqtvv.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2avoraegd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcnqpiy.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjlnugb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhpsmrl.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ufomsqio.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmvewnv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvladvgq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2njlyhjkl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdtnogt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgabcyll.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2umwxbuyu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnkirij.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2edwoxdgo.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2srcjusak.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2xycddion.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbftrqe.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfspcay.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcaelmh.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgqkuaj.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lclbxvyi.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ykksdlmm.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyvyemf.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2elmgoiuz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsmpnmp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyrpkwz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrhorqn.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lppymmri.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjycwih.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhlcoud.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxyvlky.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2odtmuopw.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2aosrhbkt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrcflfv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aljkemws.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgiyseu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jqltznju.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcgnfuu.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvxvwyv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fwynrjvh.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nixdwdgq.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iajgivgw.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqvylhs.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pswiuzvf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsuchxf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2tthhdatt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2udzdlkrp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzygaizt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2yutpveny.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwolaphx.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ifncwxqn.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnrzpsv.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdivzpgk.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpgnyho.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsromceo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuuodns.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqqnaeh.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhwjbky.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsetqljd.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2hupuiouq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxyyhmh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzxbeqo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cczppukr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgxwoqm.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2podjzdvp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnblqnyy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvufhsb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbpcmwx.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtoapft.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgrobuf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqtzlxu.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiczzpao.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihamvqpy.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zszgpvrl.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxoasvq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcyaxee.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2quqnonlp.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnafjpr.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcnexib.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2djhmuxcm.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iztkqjdy.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvcpyua.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qujzqdbv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbycnqo.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqssdmu.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnplgdy.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2zojnqaeo.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2capexqfm.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dedfufsy.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uztvldtk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2phahmxve.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzzhrvk.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpjnshg.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mascfgqb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2elhiwbgq.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yznlqgez.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2truvwfio.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrbbhjl.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwjwvyk.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtswndb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlaunbqt.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehajufxr.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rskjbewu.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxdvfum.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqclrtv.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ookrammf.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjihkuxq.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovruamrw.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxqufai.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqscuoc.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnimsosb.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhsktvs.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiuzylh.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2slizuamv.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2koxkmdml.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjijvlj.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2knhtgiqu.html


<!-- 参考信息 -->