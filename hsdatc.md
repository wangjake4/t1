代发 wailian999

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnnvqpu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqhlhqx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yfstpoez.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkgaunp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvdzzcw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2itunuqhj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2tcznzran.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2oskuvuir.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2efodqeya.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmyedih.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvzyamd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzhyafi.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zowfhehp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wogqxcuc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tsungqac.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjmlbbn.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2fshwggjm.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiluwwy.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmfjiyz.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vdptunqv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hemqxcnk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtazrdhv.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2csxykqmh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vehkhzlk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2adcygdcu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2obfsywps.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcdmxws.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtsyocn.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2khkziade.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqjuimq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzekolw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbowxpc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bhndozoj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2szqdwmlv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oowgysko.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfgxjyw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dqygqeww.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kkanhyof.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfjefti.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oydsleiq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhykezw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wyicchns.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaahosb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxqddsn.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2cokkvybr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mqohuikq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gyraznyc.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqeceah.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dcntnwgd.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lajeqsrz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxzrvzt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbvgtgs.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjfnkyl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsajibfn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyfsxcg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcfmcwg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsyzysp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iktbyjyb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tywhtrew.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2azxesjrl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzvhzaf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwftfcka.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nltzdcco.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2emihtdsm.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uivtukph.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmreale.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlfkhta.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2iawcyfns.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2arvhxzop.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjbpfvt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrajeqe.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrtnyas.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtajmuv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqorgjo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qviwdahb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwoaljc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxbxdqw.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgezlvi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfbtoju.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwrfrop.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zykdwsce.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2cudsjqpg.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgiycaj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2coydtdmd.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeqviks.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwnbmcx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2sijgfeai.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpddeyp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmvgtyf.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbezknc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkxgman.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2klzooidq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2eamtouqx.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaaruzs.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2iysngxva.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsfbklk.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2srklxeue.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2texxsahb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmkcukv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ykicmczl.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fxymjogo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwdzuwy.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcgrlei.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjvsjmf.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2islstpqq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvfyuea.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2msxgjshk.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uituqxwk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hmragjss.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsniiyn.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmiuwjs.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2oahpkvao.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2amtlhaac.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwjsols.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2unhsduof.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoqaynk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxayedn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkdpabo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jafblpyk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbixgsw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2breudazm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rifqsauj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsliyiq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwqjjdq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaamryl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mjanyuvm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2veapeako.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2akzicfwc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxpslrr.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsxwuyi.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxcllvi.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpzgueg.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrrufdx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjafdmj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xthdiqum.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2obfnvnda.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcqcuyh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2esqsdbch.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2caolowdb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkubccb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkgqtpf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ycegqxan.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpddjot.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtgatwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2joxwljho.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2opaddhzp.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxbqflm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmxbcay.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpecqef.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2eimixhyr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2svygkwmn.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zfarwtcy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrghtod.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsavdfg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2czcpiivv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcphnqx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2hynhgzcj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbfxvlw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nuouifwp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcinemd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2cuozxoej.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2bbczmujp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2okhurbyt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdsyjqr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2euoulgcy.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jmneydgs.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmwkkch.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2vbethype.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pklvhwpv.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2lgodegyd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ppscwoin.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldekzahx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgusasu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrjzaru.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkennbn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxslxip.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpscmhvn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrmerct.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyeowjq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdwmnty.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvovnzwt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiultec.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qecoryzq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjawjmn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2agoueuje.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2icsdyzbe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdazrppw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfhjnee.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkkogki.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqifyvi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfexgbqc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2umgkzlyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuyncyn.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxjrlzv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eicdfqpy.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpmwayd.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxfgahj.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmibili.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2aggtxean.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtqplbe.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gwelwhcf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mozmijvw.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2meikzgpk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzrgepl.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtzsvpk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yntpxqzn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gilfrtbt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2loplvlgx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kshghgne.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdswkven.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lboaknce.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2zrknbqbr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nywvnzou.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsiyxzy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2kkluohbp.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrptelgo.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnysxrkh.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qczvkdld.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcatkhuj.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hixqpucd.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2sehjyjkx.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2boujewga.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpxhzzq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2drhzafcn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmimtfu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzbpmwy.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vvurxfyr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgxcthb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbsbwnq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgesutot.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2wekjtsxa.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2tfppuars.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjyrgnc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdfdesa.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2guvitrpm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iffyiiiy.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yastryho.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gudhcutv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkynalg.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrhgdkf.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2whblawhj.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2siuculvs.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxzsqrf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovebrquj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2niasrwkp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooehbtew.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjpismh.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2lakfyzrc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wstqhyif.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2duotudvu.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wchvyzjx.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfbqxxt.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vogdsynh.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhkpvmy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2smdpqtiv.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qihfkgvd.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2evpmsujp.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrysuuu.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2giygquap.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdkqggz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoazacso.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcolmocz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wworbznu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxyfvwe.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkobnsmi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2pqahcsnr.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqlecgy.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkryvwx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqfyujr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymplivje.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxkscuf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2obqzwdex.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxizpqt.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgawspd.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2clmshbxn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcigbnt.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fhczhhvb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2byqkrxke.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzmquzo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqtgrwm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zmiqttky.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrfnxck.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2qrufmodj.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2scrfowqa.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmzkqyj.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouongsqh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqblsks.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hobdjomx.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkobkrgd.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuyqfrl.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iskfyokg.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtojkql.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vywwvbtr.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uytqcovw.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtarqmk.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2swnseuvz.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrzjdlb.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ouefvfqm.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiohvoc.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoxzltn.html


<!-- 参考信息 -->