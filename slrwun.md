代发 wailian999

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2evdxgerg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnkytfi.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyensyr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbxolzf.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxtzfnc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2aanarvcx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qavfqylq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyhyxuc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2trkrhlhw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjehbss.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxwuhwn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2dihvpbrl.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjjcqie.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkksmdq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhovygk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvaryuj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoibfbe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsgwayq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsypwao.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbckehtl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkjqcxl.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdmixhx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pczgpqde.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuqwbre.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbjvtyt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjbpyqr.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlysrsf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lthbysqy.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2andukgwc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlvjkaz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iydptamt.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ennuokbj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdomgxg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpwclnx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2echcmnre.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2khbyiwuo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhlxfel.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aylatyub.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2smsvdeox.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vqphhjks.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsskkbw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oetgcoza.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfimntf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vivkugys.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2keldryvq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2weaiuzrb.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2dcceaqkl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzwdhly.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2epqxatof.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkjtiim.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2stsxmkhq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2scnzlihj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2chkqnqgo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uifrpwbv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lufkqoif.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ippoldwy.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jonfvhcv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qltftqki.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzrvhfo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2puizcwwq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2aquvlakh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jucoolql.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mkulmgpm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2aychhfnw.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jxryxtuh.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2svfbiqru.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2aefrxwru.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2anvcbojw.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyiqcgb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zolntjda.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jrscvjiw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2foplqhac.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gkffnamr.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2akuhbzli.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdfqkrs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfwvqei.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxlnuwv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmgffhu.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xpubmtgg.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2awyikmaa.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhcwwyy.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2cprrxqhs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbpkxfr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsicqtz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srhhzqrb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgifqag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zetponuj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxzumte.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfhfnzz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2brospndu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wviwdmcd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgwaota.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tkabnxsx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwtylwk.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ubigptio.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbqtnmk.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhwwicu.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtwkbrt.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkzgoqb.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2liybmwkl.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwnuwbs.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrihsue.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2knfvxosj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vdoqnbzr.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmjuixk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrddzob.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eswbpjvs.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhqfqwm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjyqzvj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vturlnco.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2omlirtoa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrppozh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuztdmq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ossxwywv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2skfcqkge.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2stjsbcgm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmgrfvm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2alvhndjy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qrubisaq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpvmatr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgdejcy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2sucwcdqs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2sbroaryz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qirqfgfl.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmhojgu.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2kakqblrj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2sezzuafh.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcoxzuj.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2gjanampi.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dqczevoh.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpgiaph.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fznteybe.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2gurqpoux.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlodzts.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2obdpyfvs.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2zityyowt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwfnqxi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbghiaz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwesouz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpufzlv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewizrdfi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzwvwgl.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vvicwxvp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iujkxsrg.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2inwqmpfp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2uyafvcrx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2itejtpjy.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvwintr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2qidhuqvr.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzuqpun.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcwtkzb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjmhsvr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvabclt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xejwzeca.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2gtngjqkq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2oyejbrjs.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrpkmsh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmqpdxg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2pqstuvcx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2quxhstwg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2balxkxnh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uneakqsc.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2kanjenhj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2drdrkmhe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zvugccgl.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2pthlqmxn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tdugwflj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvucgxr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjanfclv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfaivpy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhsnjzt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhplmnww.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwihkezv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqdaiyg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtizbjqw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnumehbz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwktkykz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2juvdlffa.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmnawci.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgwspse.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzrfyxw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2odplkybq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2splsatpc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jswxggqf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvjjgid.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjsimgl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgdrcer.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qccpnift.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eywfiozs.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ydamgwno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eweangst.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsvrilp.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlglnlj.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2msftlpua.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsulsur.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2dotnbsdp.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiknaes.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2aravhgks.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uihhwxje.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcviiwvt.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbbyzjk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qmumyuri.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qacibapx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmohruoi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwzbwvb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dogcfrnj.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2obwwzepf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtqjemg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kulupfgl.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgdibcs.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2uplrysxh.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbatynir.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlyowhh.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtjntoq.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2isastnyn.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2inhgtfrj.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2tvoafkgu.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiviuck.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjpdter.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbepmgk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnlrgvn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2uencrqmx.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzpqrdk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2dwecvhgw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2swxhqvcy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxfdrtk.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2sfajapwc.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmzetxn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvkbixo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqfadfu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfuwlkj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxkfnhv.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iiscfkje.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ffugegoi.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zxovbddt.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuajgpt.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxdtzny.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtljrvww.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiwnkcp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2quttldoy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2foquzphv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvqxcus.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcukqfew.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwiofkl.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2eodvjjxd.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuxmccq.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwbmcam.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2csfkwcpx.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsaajnv.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnckpqo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uihyppwa.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2szdfzrwg.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmpvlcf.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iskuooer.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2haymbovb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpasinj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nddgwyae.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmckkxsr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljulsdoi.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2klqrgots.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjitbmh.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2fhboephd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtnpngt.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qwszegtk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyqlzwh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2opxvznoa.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ussremno.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wovtymzi.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vufyqdhx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2cehofoqp.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbnmpaq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjedcbzw.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzppcmno.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuydhjkq.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyszvft.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdkhobp.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxisggu.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2znjvsnvb.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkbozim.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2yebduhmw.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2reurwgaa.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzviwrx.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbznlrrt.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxgsksq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqebffl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxusppra.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2klugqsht.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2deplswxx.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqkkzop.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlwfzcp.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fnndoeut.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdykxbu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2shfatwrn.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcxrsbx.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2msfsuxrj.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yguvqwsp.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ditjtgzi.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfacwyg.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocputlbp.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2zouqngem.html


<!-- 参考信息 -->