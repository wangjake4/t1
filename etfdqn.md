代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuyjdwu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zsiuwnhk.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzxvuqy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjpsdmk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2owdjjsnb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqzricv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gikkzfcx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xarocibl.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmxkwba.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxzhfnc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ivejscaf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2msmzqbme.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjlwxwu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpcbyci.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kplarkrb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfjoqxf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nojykrke.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2anxfwwfs.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qykmogik.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2yucmhngx.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2afugjgxz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsrkynd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlhhwxx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hsooqiam.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2azxhfcey.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhoybis.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqckmwf.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlldlyp.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uzruhpsz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdryjzb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzcfmod.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoplysvl.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ycevvslr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2snbnszpi.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xltkfccx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsspamxo.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oxddwcxh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsievnu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uacgkewj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvvfunr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2aslecztg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2avzuasnf.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dribgpzr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnsmcpl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2yqucnlxj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2crnxjbfi.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uuilxidd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ajufbmwn.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrhrjaz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fhahsmhb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtobyft.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdecgxl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2csgyixcx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhonfwgz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmvqwzc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmahmps.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvscayo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqkhypn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbqaknv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnonazv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzvvxsh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xgghsczv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbblrpj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2iepztrop.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2frgwamwz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2cojjawrr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwqxeom.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwnukfn.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uinsttwl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjfnwqh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ktistezb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gevbmzeg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2epozbbsf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kzktqhnc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2wutcsmcy.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2heiajawb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiceqmx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2adnrzwxe.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2amnckpga.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqdgxyd.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tsosoagj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbjtxzf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2svlwppsd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnkwydo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2todrzgbd.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwaytnr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qcloxtgl.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvqssww.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2pilifuox.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2sybifxem.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nswpffgd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsixype.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjikbru.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kscffwjt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eicvcfoc.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvynqti.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsvyczo.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2anljmqcc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvftagn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxdpqfy.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qitfbwew.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kimytlmq.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qbigkguk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2buddutnz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2roumyius.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdwdmac.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2tadalovr.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wuldglgp.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tytrblwo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjnmtpa.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpsylwj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwihkib.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2enkqkerk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ffipzxpy.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnttkeq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfkzqyo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhwyrgm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hisituxo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zerdrfpl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hduymfck.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzyfhqu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lobiiapi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqreyso.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmhfhbc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fyihntxk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlxdkpf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dzugaari.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2meriqlip.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bvicsgun.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jshidqgo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2iqshqghp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvnumbv.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ivudvztp.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2egfhojus.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qibjxmdd.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2taodndfu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpgxqmb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2amypgsku.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtichtn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjcdord.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyxgtep.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wctosvmz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2gyafzump.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuxenef.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2iepsqokm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxbhnnc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgzanay.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbtyhsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtibvng.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtklejy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvioopw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2faglstpx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpgfgbj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2mslsunia.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrdbsoo.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tssbejli.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbisyon.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ctokwuzd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2adndmzfd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2iouzybbx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2anezlhzu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbmjprd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yynhrrst.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ljizwggf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjcmznw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmygevm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2cixzovbu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvnhnmk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vayomrxh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mfksehpa.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2yftyabkz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xodigqpa.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hjaxqdji.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzcxjxs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqizskl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpisovho.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aohzvcxc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvqntev.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dszwsmth.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dixydgyb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnlvyzm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eolkmlmk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bewcbyqy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tknemrel.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2leckobtv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqohepri.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2unqkarmc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnqprzs.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwfxmwf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdzfqrv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhotoaf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdhbrtu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ronbspda.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuqzhbh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwioeiuk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2goodadmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gojjjvju.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eatttocl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzunovts.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xxskyojy.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zknfnqfc.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vumrvcyi.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tudbixkt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkugzaw.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjmbjec.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkqlhfc.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2txonicaj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmmyods.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2cigsfsgw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mzedzsqo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gehjpoxf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvzwmoh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbitteq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjfyqkz.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wkytdmsq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2phugimmt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2clxjehbf.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfygrfn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2grmdwtjy.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmrmbok.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbazsbg.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcywigxx.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2naieeijh.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiccoka.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwaedds.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tawlhpcf.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsrffky.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxcoymm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfkjcue.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2gvynoyws.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxootci.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmfxlke.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2bncrelza.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlmpzvu.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2leldcrjz.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwcsogr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2npqpuxab.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2swrcdeio.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmgpjli.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2umvdjabk.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2exighxyl.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwtdzwy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmffqyd.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsnlejt.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnucxjy.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojblpfwn.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2capcpcsf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2eabikcff.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2eivbmvqg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2weoeqnen.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlmvhob.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyoeupb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwrvnts.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qazdgwco.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcefnfzq.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2miocqreb.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgivxsjs.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpopumc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2krxddthv.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgizfeu.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjelogv.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdldmnpa.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2moaopzwj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoysatl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2auswrfaz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiqpmlu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpfiist.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbwdmtt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqkqpzu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ovedixwm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kppefcvv.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2udrmyiim.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdkdevj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2radshiqu.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzknyym.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiytxtpd.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnioolti.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvuwotp.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2eyssnjjl.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2admwpbhi.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfltnkkg.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhjbehn.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeswcil.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2temfdhdl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pqiqcusz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvyamvs.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2yztubufh.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujklgznz.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcamojr.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2vshdujtn.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2phuwzhop.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvqlvje.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqrxvjm.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2etddaizy.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mttcowbv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hcidottl.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgotuya.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2idqtgwrw.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ymheuwjg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbnjwfw.html


<!-- 参考信息 -->