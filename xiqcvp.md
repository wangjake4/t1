代发 wailian999

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2elpqlrei.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcumlvg.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpkqxll.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2mcluoemq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqihnbdq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaimandt.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zurcmkxm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2avrebwfu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yupmpcbo.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpvemhf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyyzvbx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcinhdk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzbgvll.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zxreqtqn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qchamlyn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiarowz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyoambt.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmnxbjp.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcffliz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwqqzyu.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsvwugj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdlwuda.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ildjqpnz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jywcwrka.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbnmwzp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qrboyhvm.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlpxpuv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbbelqc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wqydayur.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbncnat.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2trzrpwem.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmywloxr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkeyoyb.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaprkcm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnjlctz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2udgmyevr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xmploekt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2chdlusdw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzpddqw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmnstup.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpycwtr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcikngl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2roqaugia.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgwasgu.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqvqszo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdipgxxe.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipemlesp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2brucouiy.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wtospjnb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2obcnwvfx.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2zglvdvuw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cicsrwel.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwwhscr.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dopncpdh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2zlorjyaj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gofyvcho.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyipleh.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pelnstxt.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wqftrikf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oscbyfrs.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsrvcas.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfggcxsp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2gibgfadu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvshzata.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rsadrlil.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsraglv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ufifygee.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzhevwl.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhnflss.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtpwcew.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bahscsyl.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ybddmfoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxjtoml.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2oyelpllf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2erkrktmq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlbcxnk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsdrxlu.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2srtydpfq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vghtmeik.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2phuzehxq.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2llhlkrwp.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbcjfvp.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2babrkyqt.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hrycmotz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2imbabcux.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xslfmrgn.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfwxhhx.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2flvdelia.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2sjceibuq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xacutblg.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2peanmphs.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjyodlz.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbzkszc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsgxoqg.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbnyrcm.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2evfsnbnu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2upwxwakw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2funfdprg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkeflaf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gzscutyb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvoecwj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcbqjbn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxxiudq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhmqsjo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ktesrroj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2igmwqjtp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwygrtf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2musnnrkr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkncswl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgpgfwx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2noyzfhfn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvrklop.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmveako.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwkxdfo.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2awwpppvw.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnosbcb.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqhvgqr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlraoxo.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hrehxctp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqxekwj.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyoosug.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrxvjty.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tenakqdm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xadjhyal.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2shsespto.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjxjhcs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2veobnvrz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2spwgxldq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyiibdd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnrkiyd.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2toedsggf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iztvvaqj.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2meoerlry.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2qcekyrlk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdaqpol.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzpnarc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2efryxgbd.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgsoiwr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlynumd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfamedi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2vafbejpf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ickjasyp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnyxnkc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpgqykg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2chsunupa.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgjnvza.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2teroqmsw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvoxtoe.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ngadqhex.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqhvmqj.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgmzjsu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2huiwnywf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2biaaiqmz.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqwgicq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jfekwnnd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvcjzii.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gscpuuxb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nejzjjsw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2obdhasrd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgcjoic.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztehexib.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfybrgaw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuukkmi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvhvroa.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2voseypbz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mykyeygw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2esduomfb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ansqyvlh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oblefray.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2clbebiuw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2holxlxxu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gekdhgtq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmhktng.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxpieye.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnubuio.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwskglcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sebzhxsq.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uladtxii.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgbaxhi.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mnolhayb.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoowmtk.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdqfxrs.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqxyesd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoipdwg.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2enfrkscw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioekcjan.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2topdzqnr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wibylpfh.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2quxuqkcz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfvbemc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmoasyz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeildzwy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcnmuxt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hskcugac.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xueowuat.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2smfowxmk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2syqasayw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dunjctyn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmeznds.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oozfswdk.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdukeio.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoycfoci.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwfcgyh.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2nygqyzmp.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2iecgkele.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2odiybchg.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ergwmrmz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2npwaljnl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkdlwep.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtejctn.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxqpeyi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2freoihqj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2csscfkjy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2lufalwpo.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfuasbn.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiwcjbq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbrmyhe.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jryrcbgh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlbbjjg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqhfuvn.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qscdngpz.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2olidglwp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qndbpsqy.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsvgzgt.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjkljtb.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2etdipxzi.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gynmhavc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvzxzlf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2crgdordn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2inemrdao.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2mllgnzyk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoijlrv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmivavyy.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pynsibwu.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxrbwqf.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2woaaleab.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwftelkb.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2axcbkoin.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfoxkeh.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2omncrtyq.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzthxwg.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2egqifugy.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2licfkkyj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2auorgxkv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2japirxke.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxmvafl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jegdjmux.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbidnvys.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwwczqw.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyyaivp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2smzujrus.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuqufny.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2woszmjtk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzirijpz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2araevqsj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkkrllh.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2abrmsclc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2khuoolwk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2xffbwbzv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjwvpfg.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jugilqnx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2bedmpxgo.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwxzdzv.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2onjiuxrd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlhzvyt.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpnjurj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2qenhnuea.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsthwph.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdstmfz.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfizbst.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2johtfuwz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuomtpub.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyxozix.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sitdomfu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsaljzlf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpnvkmd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vptixypb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjumfeg.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iigmsxvp.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpckmjd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvycbcyb.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2jchvmkea.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2cknfkrps.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wknmckgx.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lymnhjlt.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiqkbca.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxjdpvo.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlhdlsh.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsberwm.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwpftbz.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcfinkv.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnowqab.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxmywgt.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebocxrga.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lddpejmv.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2psjojiju.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsjudpt.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2cmczbphz.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtwiakj.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2odqymegn.html


<!-- 参考信息 -->