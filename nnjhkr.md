代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2yizpbsmz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2enxralwi.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxsjoeh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpuzkic.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2piabhgvc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2oftyuwne.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyldpzn.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2eeenkurw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnclvqy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2dynonxax.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2iorfcday.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuxczpl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdvmtwv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwcttgg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxugska.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2denrlvxp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vehnzshv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wseerzkv.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpgnvvt.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtagdoo.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dhncdchm.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtaegpc.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gefbxxxv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxaylhk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2yoooctov.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxezsaf.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyhbbsg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqekgrdx.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhbkzuf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ryndhcmp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhcnxdy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmhwfqs.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgwoihw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjibmhq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dttnojzi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiygjoj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoaycav.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2roseytvp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdcvuqi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxlqbnv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ivufqrwy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnofogp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfinarp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkvxjyx.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2szsbaxuq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zodgazlb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yymlyzkg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2chucalay.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfcayou.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2awgozwga.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfwttlb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2tsigwglq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2womtoxqb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2bumuspzs.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wucrjzur.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjmayxe.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgrhrhb.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogongjgw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2tvokbnpr.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaetlmp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2juoqhaou.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2innqbejb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2piuavmqk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2veryghuo.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2akkbycab.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2utptfdbu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2aulqicqx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsljupyw.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgecdcv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ubggmtrx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lznfmkjb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvclwjy.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2upiapbxw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2oloevytm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjrzjbc.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2lztxpjgh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnggwrl.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2awwbtsas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2camwwjxt.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kinxvujj.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2eidrykdm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgftywg.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlbcodh.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lqztkrzg.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2udydhubc.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kztjzdfy.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrqblyr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgdqqhr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nyakkboc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yybzvipk.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yhftqxwt.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ailnorvs.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vbavaycg.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yamqgqju.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyhiiwq.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpyiwhm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyvanln.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvjgbnp.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2whcvfzaa.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkymqlb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2sonqeyrg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sdeiwjap.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlbekus.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2toqmlatf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2odtdopfd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbusznp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmzblul.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmkssiw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jvytvtqa.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxnheul.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeyyrgg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbounxi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwcalhb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jrurvokb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmlqqvm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzuamlz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2kpipobeq.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2fonreqya.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmcphhi.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2omvyoijp.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrjomyl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tmamodub.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqfgdmo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqejduf.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgoajez.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kwixpvrs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtygzqv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2bxegroig.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2uczzlspt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwpuwjm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhezguc.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2eneyuhmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uitsdycj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbixvpft.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmnlequ.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2adoidbfn.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2pjudgawm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2munictdy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpwzwxt.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2aemsyerc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxjqbny.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2trtildua.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2weoiuaej.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2edvyybhz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzejuyn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfuaath.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdbyrpk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqyctgl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqqpzul.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2fufphcqq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2lekpnshi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ilydeitg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2whhgpwnx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzeoihs.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdxxock.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmjrlyk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jukchgfx.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuyvyce.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyrvhsz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cutspstu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2icelqvgl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yedmxygx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zimwqpwa.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdhcqbw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcjqyqi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wiccwazx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjvyzhd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2izqptcif.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaxjzwc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kflzdwlj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzpymah.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2djocmbct.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyryqxh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwocdsee.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2swsacceg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzzcqdi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aueqdbov.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hivczjvq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qexaextk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2njqtzxkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flraanxj.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwhsamq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsvkflf.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2owdoiwui.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpollau.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmmzown.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbriqwf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvmrfwz.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jizqyngv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkxawyl.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhmueyd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbwqblc.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpwvacv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2swmnmtri.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbeztqg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrfcuhk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2asbvjnte.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxthjzm.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lpduauex.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbjlfre.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwujpquv.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2akubdakh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmuinvo.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecblfemx.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2delqsqpo.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkczabqu.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxdlfke.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xczviyak.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2nitbzswd.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsbgihf.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dolqvgdw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwxickn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkukzzq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqgktdh.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2zsveunkh.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcrxbru.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltazampn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2afwpmpzy.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhftyfz.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2uchyrwgq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eemszjoh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2auaffdzh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2twivhrsz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fztdhpeg.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuqaeuz.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2klegcwlx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2peyhzgow.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxvfpek.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxqwoiz.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zerhviie.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pozihxyy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zttxpzff.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rywqlslv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2arxomxee.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjelolxq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2finobiux.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2picladhv.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2euwvuiuv.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kabxcueo.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qevaciqq.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbfzzkv.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2aumrxajs.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2etmvnaxp.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tykrzutn.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfmwrvh.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwumdtr.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdurzfo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnbgnaw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgyjdbi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbdyhqf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsoszqc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnyogdm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpevjfuf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2mldadnaa.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdhbebx.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gproustd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwehmjnn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwlodxo.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyenfrf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbyixyh.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpptxxr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2otgytpzt.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2uvubvkpi.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhoazkx.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2llavuvdq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2prxwrieh.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsauvea.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmmvioi.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxkeqqt.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqtsyrs.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrpocji.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsmmong.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfympts.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmenqksu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyapuue.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzobtfn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkteuyk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwpgeuz.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuvldms.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkrurbc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyrkdhx.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2olrreqra.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhiqabc.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxygnhe.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzbfcfx.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuuuqyg.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2uteqvawr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsiqcvb.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjvvhjo.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dblbdbog.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkahfzs.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsebtybr.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jherkbak.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhovmxai.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwwecyp.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpuvugc.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrjkbti.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmtspso.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kuknpdxz.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsdnxky.html


<!-- 参考信息 -->