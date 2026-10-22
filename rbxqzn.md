代发 wailian999

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2omimzmrl.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2txvlmgvq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lsccwiqa.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2hwipmbsi.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhpqdym.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbwmaza.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2oegcmcig.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmibifi.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjammtl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoaffsh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yehwftcy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sozycjvd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdusoxl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmargte.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ztexjpmx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2amzmkidk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2devdzkpg.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2yfknaaeb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2crqjlvgz.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbramtf.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2oroywffa.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2achrncsi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2iayyzapv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ardtmwmz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtyyepa.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ixflcasz.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2prvhbscf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwvzien.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2txllvezh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2unzzlshd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2orfandfj.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbvsciw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2icuzitcv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2anytxvlq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2szhidryn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiowheoo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqryfvh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vaswkakr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmorbte.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwxexzb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2doejanxv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbpmwri.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcnhumk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xsybdaja.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxbmogs.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2knexdbkk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qadrbdol.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2byebkzpr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2szinkvfl.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgqmbbm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvpukti.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zthzpeta.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkdvzdr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2abotezfk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2awrwiagy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxecbyl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tvncmjzt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2euwbrohy.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2punlhrem.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2yznmxbgk.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cunbioow.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwrychb.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2clcofvhq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gwszoubh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tnheukxu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuxwfbl.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2khlqpxvp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2iytsxhau.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kohhlrju.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdghhgn.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrnknux.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayipojyv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvqpgdj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2toduoqpq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxllwai.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkddkjr.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2eumwseyl.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzrcbko.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2grkzokva.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcswwvhw.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxibcyn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2graubmgz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrlmolu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjxmixv.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpqnvra.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqzioaw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkobpij.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2killgmax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vradcqii.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwqmbay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axwqqcuc.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2exbinqij.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gastnhoy.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2laadwaam.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pibfbgbe.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkzydtt.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kopnynwr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tswelqzp.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sezmzxgj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfhjwue.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqakcem.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zlutofkz.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvvewis.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2maoqaoex.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbesywd.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ixomjvdf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpemjli.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ilitnchh.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jtupdnwf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zuczejvc.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhgjjrq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nktpywwn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvlrpux.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbzvxwn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnxtobz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2cokjxvxs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2tavsgzwq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2aaopvfnp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdtpqbi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjtttnt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfwtqfy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrzozfs.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuitfkn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gymsyrzh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bhydmmxs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mypigonu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2srajrbgr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mkznchkq.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2xricoxdh.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2bhysfuhb.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwonyyq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2agpwbmhw.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkqpnhy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuikgck.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zltobqyb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsskeid.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2tflapljj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2govmpeqc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2btvjxnxt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzvpyvx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2eccjvmli.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2dihqvquu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2iedgblfe.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpehrfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjklyyjc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2bppofjni.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2kybteakf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrhnufj.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2htnhlshu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2gvppjhse.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zbucoitq.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2kmijzoid.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyrfwav.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqlvmfl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2iauyixbr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgcslkv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2szwgrubc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcproms.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ptngjlta.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzoqdtz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiratmn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyihnqx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ranvlstt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtzhqna.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2htpfmfku.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2iolddzau.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmyevgl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhygszc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjnvsvd.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2wtazhzoq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oayjrfay.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2knghxfdm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wncunsok.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmjquvq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqmzife.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmohmpub.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oilwlwcq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2horodcaa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocahjume.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcancag.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhggpbla.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2czoyrxpi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2orauqxtd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2beipmzks.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpbjodl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtawzump.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdywojk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlozhpd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlwwdpi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwiljwfs.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jokeltqg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnjwhfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2apexbfpc.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnpydxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcofdyt.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsfwmwa.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2vojwwjhm.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pksaoicw.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bttczqcq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsraihn.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2onuwiafx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzjxyob.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbedjhyl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmvzucj.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhraxqu.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rlznhadg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxgdepu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2iahjpjhj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnodxbj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjllqbz.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rddsupub.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2szblrkqq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnzoiye.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rerdekwa.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2kifbtzox.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfaqssmy.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcjkwkr.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2izcznrqd.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvlpcvs.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ockvgueh.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqxktaw.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjmgack.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lljlaitp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2peuncktu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tspyiotk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrzsplf.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvtjvjf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2cceorblx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgnrxof.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2czcjpyhq.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqxryhw.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ichzulqm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhucuvr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpblugg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2elqtiteu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rcumccrg.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2azclcspb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhrrcsf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqcupve.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvgxind.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtfhznj.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rghjowyi.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfbtyma.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbowlqo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvgsono.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rujqiqxo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2vihflsmd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlfcvhm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkjcthi.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bncnyumw.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iheeaeut.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdurxdea.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlnzced.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrngpok.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiggwdos.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bemiomcx.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2kylxeffd.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zaawiwwa.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2haydokqc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsandqm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqecgdc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2aergdaub.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2anhcquso.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnukhamq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tanqjikt.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2oporqpjr.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhxkorj.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yccvcrzm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwmmiuf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2twdpfdrq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zglxssvh.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdutuwrt.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyhakwb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2sqegifhk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2kumjhojq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2usufcapp.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2oydquddz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsgegwd.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2umysjrdy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nebbxzsf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2waparazm.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hzymtjyk.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvlyqsd.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsaoiixy.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2nspkugfv.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvodetk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjfcinw.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2icqmbvkz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2errpbdzy.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2giampdhy.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwunfoc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2uudjfzig.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnwanfo.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsstthxa.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jylqclui.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vifbbpxg.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlknhocd.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2trsiwgvg.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ycoomlpp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2myhaywfh.html


<!-- 参考信息 -->