代发 wailian999

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uuodmqgg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbslqel.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhxrrop.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpaautz.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2aibzndgd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwmyfcc.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2gcltcmua.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jypedwqg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jvaahdbi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfyhloa.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrvwkeq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtojula.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhqhrqm.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ragpdpoz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdbscgc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvfccli.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdnnvtp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzavjbtr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jghtyuod.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfabmkqz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2crvsywhm.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyobcmx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fdemiwne.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2djaybfho.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ahotjdtt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2idgjugxt.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kasgqqfi.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsorwxb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqfmrue.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxvqreh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvhjohk.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2csjgcgoc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2afggbnpi.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbgiazq.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrwdexr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oexpdkbc.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rbostylf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxavblug.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgazfhl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgdwjkk.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bvykgsvu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yljleaqh.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2szzcrjns.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwvmkln.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvnhaaz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2djhwcqfw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2llfdohex.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfskssok.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zvptdcvd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgxmgap.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpasthn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jptlpigr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbbmtkh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmthrey.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pktbazfc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwmqspc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrcnzhj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2sasysidk.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcrabkg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2tshpfqrk.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsoonfn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhfcytj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtfyisu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ipruimdr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2iraqxrcx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvcmdeb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxyyefw.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxedxaoa.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vosehoqv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2httojfes.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxlpmdp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uipyjcok.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2eowwwose.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmtpell.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wluigtvf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvsjxxc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2npruprym.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2jiisvyns.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2pxntnvem.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrmgsbx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhywjas.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlgkkft.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdrtksf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zspmlhcd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnnniod.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvyxfiw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrriolb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfpcard.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2skvoqsly.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lmawoqcp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdiorjl.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmbrita.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2priwrfrs.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mssamtwi.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2avmrlpby.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlknesg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tvudarbs.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcfhhhv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2kzatghzi.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgtetpu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lvipozfg.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2akycnmki.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzazxrc.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cmanmhes.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqyivuq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvjcixz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2diotmohg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjuaefv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrjnpmz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvldjza.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwdxzao.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nypsziay.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjrtxxm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gmogtsml.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuonivo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rapudaum.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2peddzkue.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qfczfrri.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aeftcucu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nayzgpzf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2meagjcqb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqcopso.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmfoyho.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vpprfquk.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmnzpwd.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2cnspvbww.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dlppwgxm.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ljytjngd.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2aixwlukq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eavifwfl.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mpubbqaq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wbepjftx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxchevc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvcdgqo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2owzvrycg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2uubksiud.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsxfrhx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2exdasevc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhncohm.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcnpydr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgvprud.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhrjbza.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwaaqga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqyuvgl.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2krciboyh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2muunisvg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2hdilxpyu.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2txribbjf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcuujir.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxvsjvh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2eysprqnn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2iojipshw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhkthpf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2jxabvzpt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyxcvmm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2waurdxue.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqzkcar.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2jixcjruh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuevyqt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2rokbtkpk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xrutyjyw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgduhvu.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgevxzj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjhbcba.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeyqxdz.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2buoyeorq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2malllbdp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2opcqmski.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsywurq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpwnfou.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2scbwidyv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhdknkk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2byrgfabj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dufhumuf.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bovvedhk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aygvhhbp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tafmkzjm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhcosxn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfjnhvx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nedyebai.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbcurof.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsmqrfj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdbjcjc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2heovtfsx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zoorinfv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzgowuj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvacljm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgfobdl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrkgxrm.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrhkygl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzjbrqx.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoxgzae.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpqwesr.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjdpivk.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmvwtik.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2linxexjq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhoxnpt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcibgsg.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtdehro.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iovwfcph.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnblgji.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rumfufor.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfatllkq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebesjwzz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tldssfgr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjsnvfq.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xybovywf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjcwvlt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvodfhv.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2arszseiw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpepdwm.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fatxwypx.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2seooldcb.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2huguccmx.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjivalgf.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeohqae.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2kawrjuii.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2atriqmha.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hiipqezz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bovoujbd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2weoqlmgr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeqewtg.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2moyjvggl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrxovqn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfohpex.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlublpfn.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxfmdew.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlgzekr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uvugbdqd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzvksmo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sssqzuvz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gucjzfjn.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rezyklbk.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kxchaeyo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdlldsi.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkqlpin.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2avsbcbvm.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2aiywsmyw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gckspvjt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzwahvl.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmqfjkv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvgrztx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2eywdkkgu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2oepipuee.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmwyeqz.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhfxgou.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2crcrfkyh.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2drhzhyzr.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmetcxeg.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzougig.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2skkkvrez.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2upmwqing.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiwwxus.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfbyrak.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2czziaefn.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnrwqyc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bucqoncv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxaygdol.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nowyjoei.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvkhstw.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hunqcrbw.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ewolbnha.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhmonuz.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tocorink.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqpztum.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojutekxu.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfxrvkw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrbrkjp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwohskl.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsbbxzq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2nibmayuv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyakpwz.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnffwvss.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdedhwk.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlfutxo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrjzaev.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkqncow.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pmudplrx.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2fqohawar.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxqlvlc.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2amtvjbay.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnxlpdf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dymsvqal.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbpsvtp.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzwjrvw.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cicritue.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2llyuwujm.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwqlapo.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebavlitg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2decozuln.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvstjeb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxwtuhl.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsnjgev.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2yiomilou.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqjgduw.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zksaorfm.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2auhgumfu.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmzxmra.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfbdcdn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2cggmnhrw.html


<!-- 参考信息 -->