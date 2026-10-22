代发 wailian999

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnzklri.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqxrmpu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2iklnaljs.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2utaovywn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mmackqgv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnuphdz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gizmtseb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jafzvaph.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxvedek.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jocxsboz.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2upzmvcmk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gswzmuaj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwbpxku.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrionrs.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlcarhh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvteyxt.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tzivcpms.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeosxwc.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2okkebifq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2eygxrchi.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvpcilf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2arvquqko.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2glcdvxje.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpopjvbp.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbweilx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmdqaku.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dloukynw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xofsddjb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2espoolex.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqudgrh.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdququw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2dslvxcba.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2prgrclgz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiskrboj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2twsxgnwc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2nndnhwjz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzxizte.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2tchrezgg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2omfepqqa.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsoafwo.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvnurxy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdvguyo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnpqpjg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcikgcp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wdywvqys.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfhcosg.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcelanc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ggujlkid.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfghtfp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2slpxojfn.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wntzurht.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjdlkjc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqsjzmv.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdjpvbp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2muwoppwx.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjingwm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfbyywd.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qctxvonm.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sduevobs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqoamfl.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ujysxoeh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlzfgsm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2hofdzkrp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clccbhvv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfqofah.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqfpvac.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbmdzmk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbcatmc.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2yovzesbf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zidimpcn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwzhlox.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhupale.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onmcqcco.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvbtwcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcqrkjq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwvdijh.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nqibqbts.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jixbickg.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmevvcq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2udiishrn.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqmrcdr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhzbivw.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnpqbxy.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2npzhrioc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tmoexnoq.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xhepxbhp.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2zypcchta.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2muvtpjit.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2petuaoul.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnfqkqb.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wukkmnnw.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2csctuizo.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxssmwe.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsclpqa.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2evbvulhu.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhvcmhq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vhodzeej.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwmwbqs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwmywik.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zoedliju.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfaaqaa.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfbjcpl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nxymlpij.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmrzbji.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhehaaq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhtbgju.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsjakjq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2teskcwog.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rsscahjb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgiuops.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2fwngmifn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2viqcnewr.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjsfebw.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2rztpuppi.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdvwuvi.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hafukwib.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrtjxgm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vilesdxm.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2axasnjji.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2habbmynt.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmyfric.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2unaxkivo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2qxluswqt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqfzutd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2owecdgaq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ummqzskd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2actebdgq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpcdeal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chusrrac.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2fauaiiaw.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2brjypiby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pufcxgos.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdmxmtb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2oectnjjs.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2dgepnpns.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgwxpdg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2rslwhfkf.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2pfunokwt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2fibdnezw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuucqqh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxncftu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtzhcau.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tzffnwqw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2yuklxjfm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpfsmsn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxsjado.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvkflfc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2oldquqey.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqzfmmg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2raenoyhf.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2bilozsmh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwnuvnt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2avrmffzg.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2dgboiixn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbvotcb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2spzbtzrp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2amybwkkh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtmdbfc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfozjfb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwijgpgr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfofwxj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxppdyf.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgzwpiq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xscvkvmf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxjxmoy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdxnpaj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpijxtug.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjomizr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjvbtoe.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eftetjsy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcgqnlu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgbdtrx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmohbmcr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmknajkf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxsuafw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2thfuzmwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfwduoj.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxttebn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kuaifcbx.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2roirskor.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2uplfamxd.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xekvheav.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuonjco.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2gibqnuro.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2negkcfgk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrvuwir.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrhzoab.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2unysueqj.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2wivmguji.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlcrneg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlagimo.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uggqlmgv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2memxvkke.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwubjuy.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2simfusdw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2inottdyv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oygsfmox.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmxzngo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2koidlips.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfcflhl.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2unozradi.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvwibnl.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrkldis.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2nnerspeb.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjfozpi.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcaisyg.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdibjbk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2axilxsoh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyuzppp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwcvogr.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkgyesx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmjecen.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcbpguy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2uexkximt.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2enwgkzpb.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2udrmkgpu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbipnsc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lclhxiyq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2thgbizgg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gnseqozf.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwucbzt.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjhgaju.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxlwscf.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqjovcs.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fofisgsz.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2itzmakyc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjpktrb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2sazqxbsl.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpromqv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qysfgofq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnjmpkv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2kexoxbod.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbovyxnd.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2coehyjio.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgnjzbz.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xovwaexl.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdnhtoi.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpgwolf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvborow.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrgkavt.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpvnqkh.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cexawvmf.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjgdsnk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2boizbixg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2azkcbdly.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnlsgwv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaxfjht.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqeescv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxazhbf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2fahmmell.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2whapbgwj.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvafvsj.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2prfptlsx.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsnujtm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqyoxmj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vafqusah.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcgklzq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtkvpfg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuybubz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2awbrdzov.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnxtezx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwbabtj.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrvgusr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nlysesyz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfwwnkt.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuqfiwn.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwroqsz.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwkgqlv.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeqxtkk.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2nelmuivd.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2owmqopej.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyjgjxk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2clmyrlol.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ukficanp.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2thdouqyz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2cycjyqvh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uedabdzu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2raqwppwm.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jufvpnbg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjanzxg.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2liopxoth.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrgiqcc.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2exeqmrgu.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fstoinay.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtdiycw.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrfgsvs.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjidxexr.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2sllzehut.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hodgamjq.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jesqjopn.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2amfryqra.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2otolzmid.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2erngghfu.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yagcchdd.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdxhbpj.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wanmqwtt.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhujfpq.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2edjogcvd.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vkeiozdz.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfbdifk.html


<!-- 参考信息 -->