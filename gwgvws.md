代发 wailian999

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yucvcydk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjulihn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dazjiwyr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2npukcyrr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ogemotpi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjswdbb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oekwsaze.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vksrdtan.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2odmnfvzc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ibckdokb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxmslww.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvxkoho.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbajfdl.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhouohn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxjefps.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqplsgv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrmukgc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oegcarpl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvgjdnd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbekrze.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dfycbqrq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcloioy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dllsjdzk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2esfspvgr.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bpupsovh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgkjqah.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2znetvifw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgekwea.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2munwzgkk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnmzyht.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuxlfuj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpqsaab.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtucadw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2weacvheh.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxhytcz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkaknyg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2latyzxsm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fynttlwt.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhirqay.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpjarrn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ybavdflr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmhgbun.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdvspzx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pvooqifo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqcvtcw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2awvfqvfl.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnqyxwy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbchlrb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hrveoujf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlopetw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2eojqajiq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddchdwdp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ckovkzkn.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmsfejv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2onfjzcvx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzxkzky.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hichlrzf.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfelblh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2fanedsge.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhcnvqe.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2idfzlzvl.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxocrjd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wfguubpz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgfnbgg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2srmntuju.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ceafdyap.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofovhnax.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrvzurm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrjkozr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2npqraulh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvbbiyq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2nixlykiu.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqomadq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2apfxopke.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmntcca.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oyidmnpi.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgqatto.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gaputwai.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgwwkld.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hycwxkqm.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmgbone.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2sycnytqm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaslkqm.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcdaajz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vafcoeyc.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqhgaih.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbxyfou.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxdcmio.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zvaadpuh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kloyxzip.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vebgkmxo.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxeexvs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tyicmics.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2azeysxsx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2efbuplax.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhnzwlg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiaffyh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeylwkf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nsinrppe.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jidsssoj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvzltsc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcdjhsy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jswfjlgq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwiqpat.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhzlkca.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2enykpfhb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdvplnc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nsafdmmj.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkgzewn.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2sqynlsvc.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2uskctnyf.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zsurbxwv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmlgfou.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2shrxwlyp.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyyendb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bcocifqj.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2wwugcanh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdixpga.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxrnpsp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmkzkmg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwieixj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcirnsc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnxwznn.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2aikcpbsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdlnkjd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2svslzfup.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwyxawh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iaegxfki.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gewyswyn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2gnndmenx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbtldyw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xffslbdy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2dehvnldw.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qffopxky.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2avcoztcy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2lacuhcvd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2mzizdegx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtuwnmk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dehzsjtv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2vfipjdta.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2jqggqlyq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlbbelp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2codkuzwo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2vmttfpdp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gshmluhe.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jaelyzys.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2cayghqim.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2jxokigkf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgwhkwt.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ovioqbnn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpefuwa.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsbsfhf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhbiwsd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvmihyp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2syxoqheh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqsgiku.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2elhjbapp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwvoyxr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fycdhssm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvnoqic.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfhlspk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfextjp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdaxskxx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqygigo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2owkpikpz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqfqvne.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhrfqkf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gojusero.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfixzfc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjjzggc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwetrzb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2polsptjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmzvkey.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cuirgtzj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjjefel.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwzqkzl.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrojhdzl.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tutozkxm.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpeiryd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzxuwyw.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdemhkt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qakaezjl.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlojayd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ktehzddc.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2zepwxvas.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2izvjofup.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2peajxhng.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2resmpxxq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2swqagemu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgiyvogh.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfuorop.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrkkzza.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhujesq.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2waotokld.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2codfgzoi.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2daudgzyt.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2noeuiscd.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxtskva.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2blvdaswj.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbdufwx.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2yuoxgozd.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzthsmww.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbiewvy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmnkokg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2enwikjgm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkhyquk.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2kajjlkbd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2qgizcwhn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwogreoi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2spxfsqkk.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2fkemrtxo.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzkavjk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gudpoips.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xeatkdde.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpqhmsn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vspndxmw.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qyotgcax.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2owboezax.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzgrjzr.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcjhwbx.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xacwpeuy.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvndfhik.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xshwumpg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2oobzcsum.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2edkigrce.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yniplfmp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2bplshaiq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2bqthmudp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2utuhgiig.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkwbuvj.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cedttpcn.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2oikzkgay.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmnfzrq.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2srljuwzg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgpuqvn.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbavrko.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2zphihtaq.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cemlulag.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2krxzkrdy.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mikhcquw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxbktyp.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzdabmq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kelomqek.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2olfiliwo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjalfpv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjpkvjt.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2juzapwmf.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhcqbmu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hemhrgrq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzapjsso.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2itsdnljl.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbmhhrs.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwcnyjw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2zidgsswr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpmuckn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgskung.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbhsput.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqclzfqq.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2nimzltpo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyahtsb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqnkroo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2copionoy.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvnynny.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2aefegyms.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzvhzmq.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmybowgk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xonfugsb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxoorqu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iasguuzb.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fedvpdtb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtohqtkk.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2raxsalrf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gypmfcoc.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2herfvnuh.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzohbst.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2enojbirz.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhdpmek.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyqqpec.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2tcctnppy.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrycnon.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kornxrmp.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqfzfmm.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvhrflc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqvicow.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfustgxl.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lebnzffw.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bclvosdp.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnrqula.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gslrsesy.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmrblwb.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbilycy.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjkbiqo.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2btpjwgrg.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2ykufcuon.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2djxvkxdd.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2iywhuxla.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2huhoyrah.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtnupnd.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2exfmgtns.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2zayeuwkt.html


<!-- 参考信息 -->