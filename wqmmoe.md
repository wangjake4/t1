代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lelqtlil.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnfchge.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2syrewxlo.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oydkbwcu.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tasbcxdl.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsjyryw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ommldziu.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwcusru.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2xeoccijf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2frznvduo.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyfsrxx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvbnags.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ertnpiuc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2clsbeqga.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2diznwhyt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxrzrhg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwwsevy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfbugpd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rwikppkx.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcsobir.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mgatxqmy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwisseky.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnmrupp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrknhcns.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2czhqryem.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2erxzizqf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuceaeo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaylgyl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlymupg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbibiyt.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ibilxxzd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hugfhteb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2uigngsun.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdtvpfb.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkfwoaq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2schnnldp.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxrizcu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwabgqsy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dfylpoom.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnhlsov.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhytnsl.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrlzijg.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2wepkxcuo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2avxaojot.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzsrxav.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lryhtltu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tiupoapr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2axoxfnos.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2eaiwxglx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtymmqst.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2prfpcrrt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkimorh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ezydkbwh.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2yokdidnz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2nsateczo.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2iihuoijw.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kstvtnjc.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvljmcw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjhiast.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2pywysins.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sycrivko.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wresjgkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdhbxmm.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeijmkp.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxzzdkf.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mlewmghu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvgwghh.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqlcxcz.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2snyckcrx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxaqgip.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoetiyz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyzujon.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2evsjfbio.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtcjjaf.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfxcdrm.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcgzind.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yibrxpdf.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2twwqzihq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2auodsxez.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtgqcsa.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhsgkzt.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbewhxo.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjninqn.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdnxstg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2huyawktb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vkigotal.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rldpdzve.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rcedykue.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2akpqvmby.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kmllghek.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2orfxrvla.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgaybnz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcbakqg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gypgapuk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lushpovi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bthpkosh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbquunh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmudtaj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrscror.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbhkbvc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvrfimz.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyxqadw.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fnchtyze.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkyglbv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfkhvzs.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wtivijkk.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxtqunp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxmzltk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfgriae.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhomizh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpjpsnr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2qxynllon.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsdinir.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsmfjah.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnubyif.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2hzywutao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzrbyto.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyfjojm.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2tpffwies.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsieuxh.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoynuji.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2tklamgsn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2tasbovsf.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfcrwxp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlfnfkn.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2cxstsivw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcvgzrt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqtmkgo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2eruzerqn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wthtmopq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cextwwcp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2baicydqw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhaugmp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2xktxdsff.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2allgxuyu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfenmnq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yubutpqq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ranmqbtb.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2asonlkia.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyqitsi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fzenttwr.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2whpprwea.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kuydamnt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdodtjv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkjxtud.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2grsmmqws.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcezbxww.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtctkdeb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjscfabe.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ealtvppo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qohajkrj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2omquidxw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozphgifj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxenzdrb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bybmnqyb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2melgtbzp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2igsurupo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqpooop.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpoyweu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2poknytwj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jordjikh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoxjwpl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dthbfkve.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgsqwwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgoklprh.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwftpgn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kecpuiax.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzryrny.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrrtirh.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zsipgkub.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dijmurmd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvazjrxh.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsepolz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zctxbuwj.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkastrts.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmekxlcp.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2iffddvfn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gpijccth.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wptriyqt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2czkmcbat.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2eygztmqx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fisaqviu.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfohiwq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeuhxdb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyquvaz.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzrvnmd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzfinhb.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqulmkr.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kirlkxde.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvjuanr.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uubfzzwt.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmvoyei.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmztudw.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aheiihea.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2drmalvqn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqheqvy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmnydqw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwngiyc.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtunxla.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2okngvxhx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2czqbdsqs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkitujyd.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2epocedgd.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2avkudwgx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yuosxcjr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wowzovpe.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2odsfkpil.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhqmigg.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zmynccvs.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cysxdyxl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkexjdj.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gxokirqa.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmfjacq.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfnwaly.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjaabim.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xejmttbg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjwllzm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpkyxba.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoriczj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2frnkrudo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gahlzyvi.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2smududyp.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhldsuhk.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqnoxiz.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhepvrun.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxfqcud.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gahsbuyg.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqhgetx.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2mdavldge.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iuoytcqi.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlntrnf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhppjcnk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvulmvh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dczmjsfc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyamipk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2clxcpkbf.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwiulnd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvqnvlt.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsiesda.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxrsnal.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuhogxa.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uurjofso.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxniyjn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2znfkkifv.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pufhjocp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqskbdm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpitlny.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2srpibstd.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vneyrnrn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2haychxfc.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuuvaec.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iutuoxmk.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dimzdhjg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpryrhp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2aztxenhu.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeihdape.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqtfyje.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2phmhjzbq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2adcxblfc.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lguhcfsd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iystxrcd.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yducgjbt.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjskpgt.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdcalib.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2srrwaxmo.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yahazmqj.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2szhylcqh.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2emsgaqnt.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pngogqda.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzgfwur.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpqppba.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuraxfxg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcplgxgg.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjkcoow.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmcizfy.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcemxedn.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfhbfpg.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqagaxmy.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kibtrhln.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqhechv.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvnsxwn.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbshyvmy.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdxhfkr.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqaaarx.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xodgfsao.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2izdoogli.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2rhggrvrp.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyojpyj.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjydmou.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2smkqnwkj.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzkgdwi.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkfdsqb.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2tgduqbiy.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxfpxzx.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppplbmwf.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2humfkgvb.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqbrajm.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiopqtg.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2gthwvxqh.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzhavou.html


<!-- 参考信息 -->