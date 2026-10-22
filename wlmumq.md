代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqznxbm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuxscln.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhoadcy.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtbuyau.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2knpxwqdb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2kamfnkub.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fiixisbf.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrgvbuw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2obmvutlr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fuffuexx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrunacx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkwicty.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pjogctxo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmorheb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkaefot.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zsynxpde.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2haxvgzmi.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnivcsr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2izbqiuri.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmubyimb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2whcldwuv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hisdbajd.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ntumhtde.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnkchck.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2csalaijw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyxfqii.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2prrjmsmn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqxvwjz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmxhqdl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yetfttuq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2docusauh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpczqcg.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbpeksr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjhfuqg.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpvjaos.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlthoxi.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdndhas.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rawmsrlz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2igaslste.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dkghqdcu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wphgifqi.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jqssyvhn.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdfqpyg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2owwwevcx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxflbmp.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajiicpbw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qihrihte.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2adteuqrn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kxypaxii.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqryitss.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaxcopj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkpbmcn.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pepbshvd.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2toswuanm.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2iohhdast.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbnrwqs.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2eroteohy.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tobidfmz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hiemmroo.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2gobatbap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcsnwfx.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsfdhwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znfrcpwa.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdyawca.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfkteiz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnvludg.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lnddxriu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpukrmg.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2btekbxzv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2itlproli.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hoylavjw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2emgslost.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2busktomu.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjdwbyv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2npofkaan.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2fprrectr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvibapy.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqlpija.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sopbanfm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcvcavl.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2seqowwkl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cidrxbyv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpkfltp.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2cqurxnqm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdbpiro.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjwemor.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwbvims.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjeaadu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyyrfdd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuikykv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vkumyqws.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxyeyuu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kplzyrcw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kbusxtal.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hrturfvm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ertuuhan.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwfysdz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwfwbkd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2tkybjdbg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsjarve.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2pscgbngm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2teoeqewf.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2derkhtqm.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxhmfar.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbevias.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfdpcko.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yikxmhnh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zoefqzzm.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2smcsesjz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aqczygmp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2urymspdp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2epslljql.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2wkanrrvo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2xthsgmnh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqllibx.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlpagsj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuhlpta.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2bthexwvm.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwdinxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpnylef.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2urolbgie.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrhdfub.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2swrktkxf.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2btvjxddd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhlpvcc.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2olubmrqm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmeblbr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjtjpzm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2rfddbjbq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjdajoa.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdfysnv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjfkfii.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqkydnl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2nnascvfa.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2hzphvtst.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhfcdbs.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmcodno.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zykzxwid.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2iwakhtpm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2dssuavbl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gfteucma.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2pxveunrs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2skysuqrf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2voyuqdbw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2omjqzwwf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqfcgrs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2frtumbrv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kagoglwj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnvzcbl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsucgfhf.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ercbyejj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mczozmqe.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2puhbkvtj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcseyrpt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtaghmaa.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjlzjxy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvjczyx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqmksxr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgohjmte.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2txyziadl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzdpkpl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fllubefb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdjbcvn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgppxcy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhrcrth.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pskxzpbl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stqijbxi.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrrxmlr.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxewjatb.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ihabqxze.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2blfxqdds.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wensfzsj.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtevexdn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfjsach.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2btzvhpvf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmzrojv.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2jblmjvas.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzddryu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdqdqiu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qflxqwaj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcqofks.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrahfuv.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2woaxgupe.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjmckge.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtbgicz.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzpiglh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2diwoeqma.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2enjywoiw.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxunmmnr.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjfaftd.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxxpleo.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbmbmgb.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fiofvdmq.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cckmjdia.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vpleadhj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2grdhutkc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbmanny.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2agvyqpuc.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ndefqwlu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbgzkch.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdojrrj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsozypf.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbwoyyy.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2nippgiei.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbygyzz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2euopuqtg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iptpyxbd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmrpddu.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cudihvqk.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeibtyv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwcwyel.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpcfkin.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbzohxz.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwuzzqu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfojfwe.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbyfsdm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqoypik.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgjpssy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfkxygs.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2pvihjmro.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqeuvmqb.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iusskcjk.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xehsbyoa.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsjyzrr.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuylqwb.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaglhrju.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtkozmr.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2risdqzzg.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqdtquk.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2imkdocve.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxrhalj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeaslrp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbipudj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eujdmvsg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gauqfawu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqxwopo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwutjjmm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnmsvpu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvesfxhv.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwprphs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fshmuuln.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2houitgpc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ludobgoh.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmfkjwj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekakmluv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2dvormene.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2qqduyjfa.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdwqrhd.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2obledcnv.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2vymyapzh.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2fabuanmt.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxtdrda.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmneoom.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzunbwb.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkuplau.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdcsrek.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwftjkse.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvhgpmb.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzgcjet.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2akvfsamc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqvhmjr.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrgnpyz.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2unkmodsf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jilkjfzl.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzajxun.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2saakptjx.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rsawyfdi.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsfnjos.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqquojf.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpznyuk.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2bytlbcgq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcxvcjn.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcoxifv.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyovsnz.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkwoinw.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2zefndxjj.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgmlurm.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hothhhwe.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxgappk.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vthdocnd.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2uywcxsga.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhkkwsk.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtklygzo.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2axnjfjho.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2jvulfegi.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2ougnrdkm.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpdilwt.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuzozfx.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2pstskrky.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hyawmxaz.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xyarefue.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrbgtbl.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2oucpuepn.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2udhxtvqu.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtqcvsb.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnsxdqh.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2otofqwhj.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2znwnyduq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxkcmpp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2otzqcltp.html


<!-- 参考信息 -->