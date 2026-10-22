代发 wailian999

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jebhqcxg.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnbtvng.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sodrmild.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbjinhm.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyyjhwv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmnwxqp.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhyuvhk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2btgdbvsl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ullgzamp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuklbjd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyyyaxw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxepiwn.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kyygwwhm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2hegvpytn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2njzoibmh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2smhfehqd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ksatuhzb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuhxuoa.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qepdmsyf.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jugstxsu.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2iotuuwch.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2balfyvqe.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jptaeodl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2erbcxfxp.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rwypveiu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjkgvyh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ehukynkp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzjvhua.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2npcntygb.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jaogunbh.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fagdvhcs.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbxskyj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2izqwnlvi.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiqkivn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkdbclv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2eosedkza.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ublunbwm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdmvezp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2unuatigo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkpsqls.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsnokxg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vfybyeux.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xurchhhi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xezvgxgm.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnyozoj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoinrmf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pskxhmqh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmxznfb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yxictziu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2chhshyuw.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2huijeawh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mmemhyin.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kffrtruj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mebnnmrg.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtajvgh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuthgrj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dwetwpmv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2scmhewja.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zyarimkh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjyeqhj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qputthdd.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rakdtosy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjibunxf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sakzkziz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jjonbkoh.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2dggntlnd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgbpzze.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2exnwfyaj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2egtomixf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcckbep.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuomvxqw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2imiuluiq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjxsiwv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cygsppha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkjsjyx.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2paqqqgww.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhtjzqm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmsdmeo.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2odqtnlwm.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjhaxuw.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrhbjpp.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfwmbat.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2odeodzvj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkbantm.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ciphadsj.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxylavf.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfygygu.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hcopvoge.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jlawquiv.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gtopbmue.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbzmvtf.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpwmnnb.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvsslke.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnyltio.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrkfaze.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkhglzw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuvuzvw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nrixopws.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcztpoi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwytjec.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2khshrpnr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2buvmwsww.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2keprnicv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gndycwaf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2simkzfmn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzezozc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iaykswhl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mieaslvn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwzznri.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2foecwgta.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2hszywdqi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqbrlgb.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2yogngyif.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2icjhczgw.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bxamfsmf.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2usxzmcaw.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnevkrl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bgctlmzw.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmdtnrx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2egaqnvft.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuxqkto.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpovsrz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2eagcvuxv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2muyrltel.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkvicwd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2jglugxyi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2jftsjnqu.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrrpwcr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgbnviq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpepbvs.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2zodxfpcy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzkdgzf.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2tdormpza.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsiecya.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcflagh.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwnfopa.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfjjjvd.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhoyqjr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvkzgms.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2blzyxvne.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhndxer.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdjlake.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2htnyslkg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2xotradzi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfgzvmm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlgkpmq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2rthslmow.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2moewpeak.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnxspoa.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlgteqk.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2eheugwsp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2amnmndtw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvoqixa.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrlyfrr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2togvktdl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwwevui.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoduvlmc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2idqrsnlo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvhbvxk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdflogcu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpixlmv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qabjdeul.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmuschq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2igadeoex.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwghwgsj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lezjneek.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyoxgvk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbpakfb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwwxcrb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhwnvhb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2maevcriy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfamljx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vywktclq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyplobx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmljqyx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcqifab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxbklhh.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iguoslyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twzceczf.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuymqmc.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxmwupj.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwshdzp.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvdmayw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfllndz.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iskzmzxs.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzrajtd.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdnzolf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fttponcr.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2uthzufqc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2twqerojc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2abvhqrae.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdzoorn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgxkhep.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkigocr.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoodxtk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mapibpjf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkgtlec.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwdkabc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2aevvadlu.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhttoem.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbobuxb.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2caqzkooy.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2exxjonqw.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuzsedv.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2akhqhpnl.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmnipqd.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vihocxwv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwlohkh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhwrgjv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxsmnml.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpfsccz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2gttvoxee.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2rckiqwfh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgookhnl.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2cobptiag.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfcyxzu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbtpztm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrsmbmg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gifhejdv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oalkmsma.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fimlxvvr.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjwjfyc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2npkcwbjj.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2szpjcbfd.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ivljalgv.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2oufwqjan.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jigwdcpr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbkjhwu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxapqxls.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxntpkaf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2etfpbnnb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzwvaci.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyekmvnn.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fumhuuyv.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryylzalv.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkwgxfo.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmmtznv.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2omhvjrkb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyxchka.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uviebkfg.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuuxazl.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uidupgiv.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2awpqkamq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyjnaxb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2favpwusl.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cojpetmw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeekrml.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzllhzs.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cseirbsb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrwgpac.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcthhwz.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jieubitx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fisdbppl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbupiwqi.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwgjasf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wafjtfdc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqklsqxf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2jxspylnm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbjlkuf.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqofuvd.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qobrnndm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2anvuytqt.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnhtnnu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2avdekuvj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dnilrgrt.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzkcbdj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeppirc.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2disoqtgt.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuclhnu.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvqkriy.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qolhcxya.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgfpbzr.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldivlygk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2njrbxseu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmmlmch.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2guczctdk.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpfcbub.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2txpvbluv.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jlonoywy.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykguouih.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlloxpu.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2zvaeumtd.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkxtdbg.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpujqgx.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcotnmsb.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpgcwpa.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvprivmc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjwagrz.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwrsqwq.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfktkhhx.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmjcapc.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqlfgic.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgccrcg.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlthzoue.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2tczcyfhc.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwpfxue.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzcxutv.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsqxjmj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqiglnj.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzyzqlc.html


<!-- 参考信息 -->