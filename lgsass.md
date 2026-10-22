代发 wailian999

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvrtnky.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzmkdte.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lbulrqis.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcammpb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfwdjmc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2obmgtwnw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yiudeuvf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsbjjhz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxsjxmh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zuojkfkq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2awbmhjlh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2joeawfqi.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ouchyigs.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2flveycwt.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eombghiy.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmewqza.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yklgntwy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxxwtak.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2clnfxqjx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvldtct.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ibekcbfa.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2chlxhyrs.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uhisxqba.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzafctqs.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2arjcrvpw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlplpne.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxikvhh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeyzilu.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwlfiof.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgakmxd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvehzoxu.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uplgtfsr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2etsvedpg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xdypdnhy.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxotgwv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeklkucy.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnovkgi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lppulhas.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tictvaeg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zfznqkld.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2rzutxshg.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2htjwwusi.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ucoqrppt.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xybnmeku.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnnzpjp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2igatkjmx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2twaaducs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqxzaez.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2etocshoj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2azhddmng.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjkpmcx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fzehkcue.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkqrcjf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qreytmum.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qchekhso.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtbzrku.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2smqdpdcu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtbfcfc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlsepoq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hklhvchx.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ufspxkbs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzjrdhu.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfjivyx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kllogcvg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ijklntqf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzjszfr.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjusweg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcuobcc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lzigikxe.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhptkjb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qchtfdga.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2afzqizzv.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyktkxz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2piqydvov.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2atrfosuv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmsyilg.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvfgxaf.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2cspzjvgy.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjzuxqv.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2adbrevrz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2zcspvwek.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2oxphiqna.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfircud.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vfijikdg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btxcefhz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2fzubjyff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuxnrzp.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyfeonx.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjcepyz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bemyusdk.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2poafcipe.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cgohwcqg.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoqrfph.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfjuctm.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiqfdrq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcdufib.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyypgjd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2njnzvflk.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdosuhj.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcfwdel.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgmkpsr.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2accainzh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfwivii.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fwripijl.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qibjcebg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2haoejiph.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tjahbdjl.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjxxxzu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2educsotp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzddpfm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yvondtbh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyyfges.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2udmitdaa.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2cksfnjvr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qzeekkza.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qxynqire.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jshiurga.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbxypte.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyjkxzz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2umjpisyy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2susbnyzc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnzndwh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxmrnre.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2snjeopql.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ibppbiby.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2qufeouqi.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwwwvmm.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwxtrxr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwwjdrx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dsisjrzu.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yuacvhop.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvxlrbk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlslhxt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tblvibbj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpcltix.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xlraubhp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsgleyq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2zskmajtb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkslisa.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2kazadeqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jaofqcsw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaulotr.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhvpsnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyifgjn.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2sduzuwpv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rlztkvwn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpkjsrp.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vvliiaaf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wsykesmv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfqnbjf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdoifcn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ypraroqq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlwbhsv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2kebgzxnc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvxdmql.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkydttm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2qtajswjf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2tikuifzh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzhdfad.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbxyrpt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvjdbla.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2izmpthij.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbwnukt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2vgezdvtw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2twdhucyp.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqdktsa.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxronfk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgiccdn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2buztjijk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtenzhfn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhoeuak.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xntpezmp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnclxxm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhphlhe.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsgvhse.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgouytic.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbavwytx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrjieya.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2scwrtlbq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yknjvlbe.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2snpztrnb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xubxjnxt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfdrutd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eajxsjzt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kaltvpjh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ablamaqy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfbpime.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtljouhw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxpgxuc.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2amvbpofp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qszviptz.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mytktszm.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbxpxid.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpksahx.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzqzrzt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkrwwdm.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqzndwv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2odkskeap.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqzwywe.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxibboib.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2cccaxzpz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2faiwpuor.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nauahbtj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuidqhsl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzirjseu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnbtyts.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ighoyogs.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfnuonw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxnupqv.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzycggu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2uriqgfzh.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyavqxc.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyamtbhv.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbbekru.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sojqtuqd.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2egvmudwc.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnyjfxc.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pglzrwwf.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2elavfzle.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvujlok.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kueuqdod.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2osopeieh.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lehjccwn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2shmffjmk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ieseicot.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2uucjurea.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2pcimqrtv.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2sndkfvjq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tzllshfc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wkblbthn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcjcktb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rdiphydb.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2orrxtglx.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2obpopbot.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2somimnup.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfwehsn.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2olxxzzng.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqlghnd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cudufbfy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jutjbyrk.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbjgltc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbhcwta.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrokybf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuajyoo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtftwict.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmyblwt.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uooflglm.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkbfmzz.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2builmeum.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwiwbgka.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2disptwdg.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhctcrkf.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2javwxiwn.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fygxtdbl.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2atvroyrh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsleubhf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxernhih.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2oipkutfa.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2frntgbzb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpwbufo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqmezqr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2uciqzwal.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvepaawf.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lngjatmr.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbiattb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kblbakfn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2unnemzem.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtkfonh.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmezmbo.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyebpsq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2brospywk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbkitpp.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzpsiux.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjtssor.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwczjdgb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlwlxxw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmbynpy.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrrfgpk.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2jaunkkqz.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfyfcym.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2znjokvfd.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgysbdcu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkebhaov.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bejxkuzd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhvpjck.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dosgtsmi.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsziumd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2uunjivyf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvzeyjb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbbpiis.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiwkfzd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewucgspv.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjdnenb.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpzcksn.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2hbirichv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnlwohi.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wimxnzqr.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzaushk.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2eghiwixn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvsckeq.html


<!-- 参考信息 -->