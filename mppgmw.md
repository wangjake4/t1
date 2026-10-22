代发 wailian999

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mivqmhqj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlmewlt.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2papnjbsg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfscvxa.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2avqrxgna.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tlklcize.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gktpnhtx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkormofc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vuexagis.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2uphwziny.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2strvkcsj.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbgebgh.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2opqedqvc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuyvlqj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvohempv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhuxwqo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvyjhnm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tcllwizh.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcowgza.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfneaib.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2chcalohc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvmobfr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2erethycg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbpqjje.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtyviiy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2msppszmy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgxhotb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2orkgxyvq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jcucgxnv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgzsotu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpscyym.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bavnsgei.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoeylry.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaveofqt.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzxehcl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdbrzch.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yatbfqgj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyumkfc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oqopzvjw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2quvgvpho.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuvammm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tielxqrc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucoxxern.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2shutbpff.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrwlnkj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnypcjxr.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2trwitprb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgglcvf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvnuyro.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2epksvkcj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mqalpzbr.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nipxpzxm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rozyoelx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pewzyhbu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2srrglyjz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkiexwc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2iacfaali.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykusaxhl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2nngasqfd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2niodgczi.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tyotffce.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpbdfwb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjqmqpy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2cudrydyp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mcloedfp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzvjfdx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ienobvux.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2krycfxcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fyztwmyo.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2mshgpvib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdwodor.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqealci.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfelqsc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xkulkjkn.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwdpbyl.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbseyic.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tienxgbx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pdiixtuu.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvpposk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fyockbui.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzfgmql.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yunzcxou.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdtnhab.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ryemnyna.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qckxovcn.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmtjxld.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sunhvksa.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2soxqccyu.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmjnudl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2puwdjlnx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhsjuqd.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2psjzypgl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ibroeifa.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdqqxbn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoiglsg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nomthgnr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlcvzjr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vitljqiu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2onmngbvn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wilrfsrd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aipwrkrc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2evygblne.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgdscrg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmgoaev.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ogoiokea.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2byswwyfw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ljargcrl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxufhjd.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qzygywpf.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2swacgycc.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbzdfqh.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdicnul.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrhkdhp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2urtjsepo.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmkznwl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhwjski.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsgpjxm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2unapbvip.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwqaheg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2qjinxcxx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2arlvdkwu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2qcobriiy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2urvcdtmu.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2utiesvfz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsiblco.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtrzqzs.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2uunepoph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxticfyk.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2xhynxtwm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmedhkw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvurvvx.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lsodstuf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2vltutahq.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qieqvqgu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2wedrseni.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ytacwsyd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2aplefoxj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2upjvmvet.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2trowtmmc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gpezbrei.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnjdfsz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzpbrgg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtnhgty.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2qatwajar.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxlrogo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ollpjrfy.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2euuasyqm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwzlmxq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wdggvngv.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2parcsyfv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpoefcp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sscsheah.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqewhjdx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhcnejb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsusjidy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2spidxyur.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbajlgq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaewoyv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeaexpo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlwrrwc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiiridc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuexdqj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gohglrho.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcvohwr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2njhzzhta.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jskguykf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2volyelqa.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrcacee.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkjbbef.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkljnxoy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmewmoa.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhigkle.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfmpygt.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xoznddqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hhplbjsn.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjlmsnp.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2aazyngxq.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpedoll.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2apbaryza.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2osjzoxml.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yavixjkz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2siyzqnrc.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcklskdc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlhtave.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2nllddewy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yljdpbkx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeuceml.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyizboz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgzoarh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaesqpt.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmhzrnl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqnhhlj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgtjost.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2msnvkcsz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwjkypy.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnsgvpa.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlaxzldo.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2owjmfifx.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kplcwrxv.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjqyybr.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wflariyo.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2booyabwo.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eosmaeld.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jimpvygu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkngxahx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpnoyti.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbssdfa.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpaolay.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2phckgpkb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2stbpfqsq.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2otvhzqrx.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xifxmmdn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfgbngc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2avzbwwwh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pllrhbmj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2txmvfqnb.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2loswfkzj.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pcatzmxs.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrieuij.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2koncxjgl.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjavzyd.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2sivhekav.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cclamcfc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpeyhocc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbnnpfl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjxbxlp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbvecdu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2yrywtqvu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvxoamf.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2etiqskqn.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbkvdht.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kimczodj.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdpibky.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhdcqci.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2onrinvno.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rptkxdbx.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2feedszlb.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pczvvbvt.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2eutflnwb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvcymda.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmslhhk.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjwbsyw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lisgxhkl.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpvnvsm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2clqgdqzl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2bfaedgsp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcsmvpp.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjoebku.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2udhwbxwb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfxaupw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdttzfo.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2osdtltcj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eikvopfz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzsmgdi.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ernsskyr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2orufvwpy.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvumgqt.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqtfodn.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnufumjb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfhxskm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2evexuaik.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gxffupia.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2getpzvfe.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmpwzkc.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtcwjum.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2vomskpmk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cthmuask.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfhague.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgqbcdc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2aczjprij.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2scaeojbb.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmqihki.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaebrjg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uasblrgp.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nejqqlko.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdufvusj.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvxttse.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbyiekc.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ueykptly.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhdijxg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2trmiqjrx.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmdjcpv.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfkzhct.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2khlkaqpg.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2eftdtely.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjohgjb.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2aguzldxc.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjttkrc.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdgpukg.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2iauxdrdq.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fualeikw.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ietcuafo.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlihthe.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2iinmzihn.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xcekgivn.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ntizunix.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ravuxyrz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zrirnhtb.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2oabgmcsn.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2qsklgysl.html


<!-- 参考信息 -->