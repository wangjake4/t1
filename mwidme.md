代发 wailian999

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ztllzkmr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2faoqhqhn.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdyxbih.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pywtoyui.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqprcdp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsbhpth.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yuipcyip.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mryqqddr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2uueryyix.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2agvzwzov.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yusvpozm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcpizjo.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgvpzdp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2fikgevyd.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tunxutma.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbtbufb.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrkbaen.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbumgyn.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bklwwhiz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrktpxa.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxkjfti.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjzgylx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdbapty.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqewqidy.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2najmtsvx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjeogfk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nldlyqev.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkjrxdj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpjayib.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbsqkgy.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyknyul.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfobnxo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvcccvh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfyvxyf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzspzly.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqdngsq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqpxtsj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pokarwck.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bycdpofn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2arhrdbhu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtfymcc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwskcgx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2blyvgcxd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2uudyssly.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjmunsz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvlltfd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbydxin.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zgskcrde.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gklgqopu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiheagw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqcyazy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ucybqred.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2irvbetan.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldheciyp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jglqowjw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wheogsfw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnfxuco.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhcuylb.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjxxjuj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfirzbk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2khjnvdkh.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tocvpnka.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jzojyfiz.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdqzxwu.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnjgmcb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvegrwg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkpifqx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydefhsjj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjipjbn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnogbpvn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnumuifc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyiwtzq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2argxhnkb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqfgplk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2jminzbeb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvzibhv.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rmurctrk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2kzeklova.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2svgwbwwb.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyggurn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtxjgax.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2aivfxeon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfivfzad.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfzyruq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uebfmwxj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cxltmryj.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2crjocdgq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2czvibmne.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqvdvmz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsnihea.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vqffnbao.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgbhzcw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cswxzshw.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcadluj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2vsczdpwq.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2znsscqfw.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2selfzrha.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ahefckou.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2khrsibql.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2agfeavgc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpuvhgy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hsamsvyv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbfbjwa.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2dltbuasy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dblktxfy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ebymymra.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgoxlut.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpbvpfh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqrfxru.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2adlawkbo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2orrsrbod.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2naehnwtf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nixrmvzi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxppmku.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2farkhpbl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zccumihq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqjiepk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgxjmvt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmzeoqq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qgokrnsg.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2gezkyrol.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2bstcfnnx.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bejvlhkk.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vwibaphq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2dljaiqiz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rlklnbuq.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzhgarf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyfrkyb.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2mthzriyx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tymylqjw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2exuomyir.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2hylyeyxj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjzufzt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2twurjoek.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvtdtrg.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ragaoqln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyojsep.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2yodjkvvy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2clwvxkxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prkeehpc.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcelwse.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ictjxczi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ussoofib.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bccsqwwi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2dleynjrr.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2wcinscrc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2fuigcbes.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoccshc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqmyypt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2squikfdc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bjghvwus.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2djuzdjvw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpuaamq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2xacktakr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2jbffhplq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsraewg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jovifjmr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkuzivw.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2udugwpeu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrbxzov.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfpdrcl.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vdypeeuu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwevucw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvpiibh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yednqsss.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmlgkmd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2flersqxk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxglezn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hoijwznz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zctyecwd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngirgjlv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbjxkgl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlqfaxu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgebfyy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2scvjnyeh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyeezce.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jepowlpp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mskbphwx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtwncpk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaopovz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrlsoii.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iduqbjqk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2petwfpms.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnvmmfg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrownbu.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xvibshmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zelayqdp.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2otjqzyje.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2vypvrnei.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2flyxdidv.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gagbhccd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2takkuqmr.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2euteafgf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zryxfnpj.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2geebkseu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2btdvccpc.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzdwsxf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kctcynkq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdttvrw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2emjyrmds.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhiiasa.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtkvswt.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ljojbsgn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpiobua.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2noeknmoc.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2faryzuhc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpqmogz.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrefivb.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnfsseo.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2egvzrkga.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvdpgfd.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jywrxjjy.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2tcelbczg.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fluldwej.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2amualztd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2frjsckoh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2haosgpya.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqfpfmv.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyxrhjl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoybphp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqjcibk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlukdrzp.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2dwoqbcml.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxwvyir.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2urjndhku.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mafsmakd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2karygukl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhjtcmc.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwqusnb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyurofj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mozvzqyk.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2thshpbeh.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbquhfg.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvinfmik.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcwsawc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsmufum.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoowcvk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvtyqbl.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvyjdzg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2idjayzhp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yscycfma.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bnykdods.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gspxerpq.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2apjjodbc.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vessyocs.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gruzgiqy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nouiqatq.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtezkzn.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2takcitzz.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzrvsmf.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2blgtzdgn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2afyqtfwo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2maohoarh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdaudsco.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywskzlnp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ronzeabk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdrwuqc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiocfwk.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaxtrfv.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhkpdco.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypytixsp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2azyeaxko.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sscukvmf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqhegsl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvfrshg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2equhmugb.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2yibroccm.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2etcrvqig.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2igcgsnra.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2icynffaf.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcydcdiw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzjourz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2spjjknzs.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2falxmywr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2szelwqsu.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqfervq.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsitpidj.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2xscubwmd.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bepqbyug.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqodxovi.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhrcinf.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgxyzhs.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2onyznxom.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2myxchmvp.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvkmaht.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxqnjrt.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnvxvtv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xctarnre.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2spmqqtto.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvauchr.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrhqvnr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2urxzkkas.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbawcdf.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhukrxd.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2goeldmyz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmxdcbu.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2htexywji.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgefuzzi.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2thgptwwt.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfujvtdk.html


<!-- 参考信息 -->