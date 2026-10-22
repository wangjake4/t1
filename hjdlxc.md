代发 wailian999

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2uutyjmfm.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwrhfkg.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2boyajluv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2orspcwsj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpvdutq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzyaumi.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjqazhj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2pimembjq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nhejyzgw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfrgvvq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2txkodzcu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2krslzcmt.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qhontqaj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyprjfg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfdpeob.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbkssry.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvitaxo.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fptkcush.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aqulkyvd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2claurbfv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mpemftmh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbraydgd.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2htbsrvyo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2skkghcqj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxuwjyv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvpteaa.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nucyjali.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkogpgl.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqpgibo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ccurhupk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2igbiteqn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvovect.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gawklydi.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdojxpb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qllnaelr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmxsopz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2onhkdecn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhhjsdt.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2myjfshzp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldehnato.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zjagxwmh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoziawc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2phpsfdil.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsakbju.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2rlybszky.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kignhwwi.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nooffspz.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsmtxhc.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2amimgqxp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yclgilxu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2gmahidoj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2dewnknkq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fieqkqnq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfsrihg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dhiuyesl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdbkuxn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcyfqbs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcgppvw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzhdgfc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2eeymjbgc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwareic.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjtxaik.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2molfiqeb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ziovuffe.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xdskdxzv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2roclmyki.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxsmcfw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zttrwvcv.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wieugbgx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ektabuwb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyhdbvt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qajxpqfg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nfeaxaci.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfucueb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpawcva.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fafdojba.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wnydwxuw.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xphjgpce.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2epwxsnrb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmunsfbo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpcqsmi.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2glnbanud.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fonbhsmu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxcncus.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuhvwgw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jeljmtfx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2jakmfsjb.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vccsejlm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmkffxn.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfapyvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2godwzwdx.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfevths.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gygvjite.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnadckd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlfcvot.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xqofgfvu.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzbxlcp.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nzflswtv.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfueryu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlhnlav.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pwykstuh.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2doegqctu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgsgawg.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jahqieif.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2riuupfft.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qypvkzvz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2edjhpsiv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbzbhqy.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzcjodd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbzfhvq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2oipkfcsy.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjnfmrz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkuspoj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmvuoog.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqgmilg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2egsdwdsh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2jenslzdp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2umvwgjwl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqfqnfw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zpasyuhh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpiicgx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwejjio.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wvldblwg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2haiybowk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqpkfhh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnvbiem.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcaaxfu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtzfaxk.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2altxtvyg.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkagrxj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrbkulq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpjvocx.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2liaxjrti.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgvygwo.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjsruxm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2verryivx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkzvatn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvoxfhs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkfbptr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2futcczpe.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbkvqep.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fynmojdu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2swchtjpj.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzzeaqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fbswrffs.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvxddtp.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2kdphchga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zugzooir.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwbrsqy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2fqibagri.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2exjwzhxe.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cavgvhhr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2lyooumyc.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2uffyrjlo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbxjxtn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2lttkqgva.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2cpblwfdj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2gcohrjwm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2aditlbvw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2yetzisus.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2vuahycbb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmihdhh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ziznrvyu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdtlwfd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmkgtdv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2osrvazos.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2avggmplj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2slczshic.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdhxygl.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2oidiqrwa.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ueywbafb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkimamrk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvjmkpq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pficawak.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aiksxsun.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuwjcqd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbwbkht.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkbkvpi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqbhvbx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2brtkvyey.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tawxpzlq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mudcrani.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztofftdk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hraahhfi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsllyybb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjfenqq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkbjpwu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbankwhq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqknimrn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsgjwus.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2acolwagv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcyveiu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrxitvn.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcrtcxu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuiifte.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yydzcjdt.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsaeblx.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaaidwc.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdygzci.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwobmdlb.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2quzcstqb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbndmser.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pceagcci.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbddorx.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffalcema.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2utrgsjny.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2znhnwfsa.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2abwrgexe.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2smsbsjpi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbcsdsw.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmawehy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hezfxajy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwouqswa.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjxwdka.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmnoutl.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrktsgjc.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooutpkul.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xibfxwnh.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzhwtfd.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwqvbub.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkycihy.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhdedrc.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuvgkjb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxdongx.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2imlilvpr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2yyevhfif.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdhossl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2frnsotrm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwbibhx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2nejyehhe.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2jfecdgtl.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2dylywtdu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nztilnwo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtkbwhu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xmboxvkj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkvukih.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tulylliu.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhmptou.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wgaxqqnc.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzlrkqc.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2htkmtrmw.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2icrtlrba.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxlxotz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2awnzrqig.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukivscif.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2utjyykir.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmuxeoz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkefvzo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfwzpij.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ljegursl.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgdhqkx.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkxmbpe.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrhlept.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pafcdyey.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbhibnj.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlqcjvn.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxffrnv.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2csdrbqdq.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2sajjyiqi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhkyatb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sykggzrd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlounzw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvivoab.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrooraeu.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2npnlsrgk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkrhfxd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqvbggg.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgeajvw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2agdhtplr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlicsnk.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzxzihv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2foxzgfjc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnhalda.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzfudmt.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkdwzem.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjobegt.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgfjvew.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ognlqegq.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzhfftw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoqkiju.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2amblplcu.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvifirg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2asnoqxbk.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2widrpxwt.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdumerm.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpydeul.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kapvgbwa.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mybuxnmd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kexptcni.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljusgcii.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmyqzsm.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2syfrznsn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2toggmxna.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvcisic.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rehzjabh.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rttavrfv.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpynbfew.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcmawqb.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2hlskswox.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuektjvm.html


<!-- 参考信息 -->