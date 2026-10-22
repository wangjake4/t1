代发 wailian999

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2cvccqmjx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvblxut.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvwschk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vnovuubj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkqjpzo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2emjhjbxa.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2eaylycwt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fukzdqmx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2afqjxjym.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2orqjnwcz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yusefwku.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiaivyn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdhgril.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtlwskc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hliogqdw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrntblcf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbtjzyr.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlpijqu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nanwrlia.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoxxxvt.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyuaegz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjstpuru.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ysivkbss.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrxlgdr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjmtxhc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgxfygu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aryjgdee.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2djaxgzly.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmsuhdp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rrebtsdw.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzbgmqs.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiboomwv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2heqswplu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmfhdbp.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2svftlrxv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdslvgjv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqjnlmv.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvlpepc.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwekgzv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkgjshk.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tzikyjbn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjvqeay.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmlrgcp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wajilcvo.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbklgcy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xfeswahf.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mpeahkbw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2aazsbiux.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gphxlaen.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqpcirp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqhttvz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qljxzyux.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2tttiexeu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvzznwn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2oikhfybj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrtmzcr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvkedlr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zeovyrfo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eydbifsy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2cmellwrt.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2uebdqjwg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlesszd.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2owfovnpq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2tunhityz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lczmmtwi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkwcubs.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2upzhooax.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bmheygad.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vckaqjeo.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tfczjfae.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2uibjqthx.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvybomuw.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dpurvssb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqrukdi.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lmoojshs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nihzvfsr.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cjohdjin.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsgngci.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfbtlnt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blbiuntp.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zwoocwiw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2evdezept.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2pxccvjuk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdmygfc.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmeldkp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2kehcpbkk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgengyf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgrnjjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcfojgm.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzjtlck.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2docddcdv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2waomasod.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpttpam.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2izgacxuv.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lnltsynn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lcktsgsx.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqudort.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2omwodbhu.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkfsfyv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjtycmz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzkpvqt.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2edjcybqp.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxwuazn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rvohxvnl.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mybbhggp.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2aloaekxi.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2agoqjjzk.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmvuerf.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gglpihxi.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjjrcvl.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dudsonbj.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2dbikkrcq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgwwodu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qesxtdki.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tiseevwt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tnatfhcl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2pacjtnzr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uabueokf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ueezznnl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvsmzke.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bubrwcst.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wsejvqnb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnlvsvu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aktmmznv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2umvglbtb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcwelwb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2kengxhzv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnsbjxk.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jdauixgk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkesymp.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2eijpisns.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlcektp.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkpzlru.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2slycasyy.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2okghkswf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pamfmxue.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcmnzmm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmoqecg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2sthgppvq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2zbudnzpd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2hyteilpb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2crbgdrcp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqhlogn.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpmlqcm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuehvvb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppofxzgg.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2sokgrrjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grnpgirh.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzmktds.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrwlamj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnieisd.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuazcop.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2inciaovk.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbpzltj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2suyiiaku.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2xehrkinp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dtavwoep.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2elyzgteg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2intkuenj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcpfjgm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcpicqs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2idfshxud.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2cckjfzel.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2bickohxa.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdnlycj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyxxuto.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2vchcwnmt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtoctry.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ltowujgj.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ugekolvp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dymaxwpo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2frkskrji.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yznvvhln.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cymdjtlt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iscfrmkv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2htwbvrrq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvglfegw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlwhrcm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypihosvy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeeiqad.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbycxabh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlsmagn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoyzrdp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwuufqm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqlfohv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbgbhgj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkwfeor.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgijflaa.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlhktdt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxylxzl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldivwbcv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eptuogug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzjikfh.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gioekuxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsgxadt.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkuglst.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2naslbrfd.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwsbepq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqmmnkr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2orthvxvp.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqetjpw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zneajbps.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpiotiwa.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sopusimr.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyzbcfe.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nohajgnw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2srquoldw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qevikcxv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjghtsj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhucpudh.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpkfzkn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2itmxfdfc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aimijwgc.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkdoems.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ipstydlx.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgepvuzn.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yysiqzzy.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnznqsft.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2prabdiis.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkwwlli.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzulquk.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oohftbbz.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2naevqfxy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqcvdhc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2etzrdqch.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bomsnthq.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2iomuosbt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2gayqxzru.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwjkuuq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxxjcfl.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2iljdmomj.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyrwrin.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mlivfyic.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqkdivv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhbndly.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjsofar.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2beqbeaii.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgwfxle.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nifhdfad.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwhxvqh.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvevlry.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqyhpap.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpoupyrd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgzebus.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zabgspti.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jadkkvrd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmjfixe.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqnzfkd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrblncwb.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ogurosmh.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkedvdz.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2shlvzpvu.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxznevv.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2navgcbvv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2napyinew.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iteqlkrx.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxtsrsz.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpajkwjf.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2baojazzv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeenykw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeuicoh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfcimsk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzbobbq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtszkyl.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2infbtqbq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhcjmjd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xktttjpq.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfpsjpo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdxsief.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlkugxc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kytoalgd.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaeinfyc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvixtonh.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2smngojvq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgxzhao.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjatsnvw.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ushurdtz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wommxwkp.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2zynzwzwn.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2acsyjlhv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgsorbb.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uhypawko.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2dytlxbep.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmzccmn.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqzhxok.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2zotkiiru.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwurvmjr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjypwyr.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtkngij.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmuzbcv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwaarret.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbiuhcf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2stefdkhz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyeezqw.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dscckrgw.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrwwfjd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxoixiu.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2rglxhnuy.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnjwqmx.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbzphgt.html


<!-- 参考信息 -->