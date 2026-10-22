代发 wailian999

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnjjiqe.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrautkn.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzuxyel.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfntitr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnqiduf.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjcsywj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wttcslgb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnbpcpc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wgohwdck.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fearfexb.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnkxvun.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lemnuchv.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjklvad.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2eefwktvd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjqqdlp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2citqfkxz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mftfkvdo.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2khaefyip.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkyzbvs.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zbolvwks.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2asnmqtwl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqgbkeh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pchsnmji.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vygijwsq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwurihc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2azyrdqgf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuvvefg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzzgzch.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2layxfgxp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqilymp.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkydxev.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsjxuuo.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qlinbmof.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2acbtzbar.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxmtoxl.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhoijvo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2orngotij.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2daowqkhj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnodepu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuffpik.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkdcaxa.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2frcbcufp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hilqrgvh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bsasiiue.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2krkjyqqy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lzezelgk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kydxbuxd.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2itgemtws.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2psqsnvqe.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuxlbqk.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2atjwkwgq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2tycflhmc.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjyyppb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2eohqusyr.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqboliw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuxsnnt.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsausbg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2adqexgvv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2draytouu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrcqtzz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2idqggvbv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiqgrdc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsljeqce.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxrnivo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xucyyjlj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqzzgyz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmtxuwi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2eoebrymk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uabftkxh.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqqjerx.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2budbvmrc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmfrvuw.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xycrkaoq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfeixxb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wpexjpwm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwpyiig.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdsbljy.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xefqshtl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqymomi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktexenyg.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lykmpebq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2uajyxnra.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wargjjsn.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaupqpb.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fedrumdg.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwcukym.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2idfidkwc.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2rasicwqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbnhkpu.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2pzitlydm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvutpmh.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtmrkew.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zjouwhgm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdzzvwy.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhcgraw.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrpwqqk.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pizpcloo.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kalqyrxp.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dniizbgk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcfrvpn.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2eirthqcp.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfmgila.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrxccvc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2athkibsg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjptcon.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hivebljw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxiyril.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqhfnxd.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdtlrjc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hqricwny.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhtwtny.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbsmlcd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2yemvyrjf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqwysww.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2juazazse.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlwliab.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmhiyqq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vwflvhpd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjatbki.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2shsduoul.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oosbamrb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjzjctq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yoosibfm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeydfbq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uuclprpn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhswcke.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxbbcsa.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwucnim.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ispvidcq.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjfxwrs.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tyaleagl.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2yifopqcb.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2esmrvgqr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2krqlydju.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fukbmoro.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tozbdiqy.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdeiopx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tharlubz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ymajjzkd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2aasepjwc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2lprypkuh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbdxvws.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2obepakpm.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wusqxiiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfhvaxd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2muztfbmt.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wixmaoyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqzotex.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2fuizfyqb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rjftywrc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgdksne.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbtqsvd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtnqatt.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2odgwpjgz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2jvompenl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2mycqksat.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlryzdx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgkfkav.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqpnmkz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbzwvgd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2zakfclwg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcvrkjd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xiobmpxz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqsfmfj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfovthg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvapvpj.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyowkmr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2dxktznla.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbmnkfj.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwmuake.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgotggu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2katvuhwo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vytmjmsw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2censqsou.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgdoibp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urpqbelg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnknxhjd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxokvhk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpithih.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdjgvdl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyjyavc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwazdqb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoajmmo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybporohz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqihrqq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgmwiwo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrlyfti.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjzmckz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmqauhn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhsbpop.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2taefmjbi.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjolbriw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsydaxv.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xmygasge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvddpwx.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpwcsfa.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2falcfhlj.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qczwcqua.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuhlifd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxuzkde.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwimocv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2icrrccnj.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnmtofb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sghwrkmx.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfuvdkm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2btfhvucc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhbwzta.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyzuqym.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrflxtq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uksqwisw.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjnzyvx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsqtbin.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2piochuac.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2insfosvu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuydhiv.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2abrevzng.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwrgtdg.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aohvojmc.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcwlmkt.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdakjtk.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fchjvgrn.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjbqcmr.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2krlbeusi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsxqjrq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qidvjyis.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2etmszqzm.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2msdynmck.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2bumenctb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2oygxzoka.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2urtafqvc.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2igekroul.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2aolktphc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2frwegefr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tqadtrce.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjczsgv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dhynytkj.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ssolrxxu.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jydcbyzn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uypwjdtu.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiskhjh.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtwxcoq.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqtelrz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cowbhiyt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcrldof.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrolmaw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kldddzql.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwjlabi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2usujbybn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2coxnxpwl.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cemeyqio.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcmhzzn.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtacpnmq.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfztfzy.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pluykrwt.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2grjlvgcb.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hibieusd.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqtubxb.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfipzkd.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoyidix.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2emlohzjq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgiocmvk.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcnicdr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlftjajt.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2loerjaoy.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwtfrxu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2cehynlfm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkzrdbr.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qefhswem.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iczzrmml.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzkncma.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrzmiil.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjghsdd.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpjlvrx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2mztdfroj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2liiygqxw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2llzvnvbu.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgumhnp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhcvbjl.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfvtssl.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgbelnv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyfzxqa.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nhflpzck.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2xarosumu.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfdxqih.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtxsepq.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqirnads.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ieipidmu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpzgxel.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfngwrry.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bddfbvej.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2itgvqsec.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzppvee.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlscsrmv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiiebrt.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeuirwo.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2trxaxghb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqlhqyo.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxqhphx.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2oydsprzd.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnsmdpu.html


<!-- 参考信息 -->