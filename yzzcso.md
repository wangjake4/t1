代发 wailian999

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2inpmmgpt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsucuhn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2whdtbnxi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpngotf.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2koahcxcw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mearxkad.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnfcanl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2udoiwgmg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuugliw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ygiupluv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wpideywg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwkhvft.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2cebnduxd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhxokdk.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2speaiphi.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsallxn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdndegc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfqylsx.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ktomkece.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhenpyw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqfizqk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiemold.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbhsdyt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdonfzxy.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnrfgkv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2otrjnvrj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cwixshnn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2umknjheq.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaztrlf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xfteudhu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2shzvroct.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdulqou.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2xibctmjg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzxruyq.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhunbum.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfoypiw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2iyynmkvq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kojtsrfw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoyuquj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyhmcfk.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zzatqzba.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nyewtxso.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uupwmkrw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtcthni.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2trnmijyu.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lituncdr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2weztwfzm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgtxrfg.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmbdjrf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnasljxe.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2beavdskc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2umapwbgg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrxgals.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oijvqxjx.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwlrxpa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ovluumgp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeredhj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgchzzup.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvuurxt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2dliuwgrg.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gslhuelp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tryallyc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpfqyae.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dwskcsoj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ualvnlbp.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxmxova.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2apkuvslg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2buwdgsqh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vddxptbx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkenpfwn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2slamvetp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fndocjps.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2avyszcnz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuxpvum.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhurzniu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyzlzqm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wcspique.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zlanjqdw.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2niucfbzi.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wuohrrtp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2npbjrimm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2winkxhjz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqtctiv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfqkdso.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsulust.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vddbydko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeonnuz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgvrvsr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwtxtgo.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbnpjfh.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vctbxqpp.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhswnkt.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxodxzn.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfdlnoo.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lqulwfyp.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iifzsiwu.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpdbpcx.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpbjtch.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jigmzkce.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2itxplwvp.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2splmetrc.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdnwwyu.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qnznsvns.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2elctdqgp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2taxdakqb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2obsbhhnw.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sitqjvjv.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuppyoy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcqokhx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxtqhbl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzlcime.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2aovgjujd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2dbegcvme.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2znuhgetx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rvibgvsm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrfqspo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmulgjn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ipttaqsd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfihznf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdtbolk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmnammi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tevvyaez.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqkmyks.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oibwytiz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjbvvon.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwrvzxj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfhmxuz.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vpiswqcq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2acnlsnix.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jscozufc.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eddtjdgd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zuywosky.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2qhigsxni.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aagixvfp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2sknllwot.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtjzatn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqfcrcz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2djnbwztx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2qljszxci.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsmqtvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwzxmkp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2stfejxfr.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2eweygqzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbkjvnh.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2fcydjlik.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqwagpz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2okdaiqrg.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtrnzty.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2uppdlmiu.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvxjfjh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnjhtdk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2mvszapth.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2fauyofgc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnslkif.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlfyjlu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2iowxfvms.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2amrllxhc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2oofkzumn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2vmguwvsa.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2lonppmff.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdmfkaj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pplgmcji.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjoerjc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyaqrye.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2irvjeqrq.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vpanelng.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pmybdsbb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiofedc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhpzvbs.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eulqdlwo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzggnabc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnhlyyu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2olozggiq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcgzcbz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2thysioay.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2etteavnk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjszbut.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kznphrzc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcwcxfg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfpkqvd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqfpqus.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2weagekvh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhqkdxl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlpbznp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvqeslz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhznfst.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kidudsbo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqskdwok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phjtdito.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bixdfvtb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irakhuev.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2clblvfjr.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2iaavpkxp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkvwesl.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmvmbah.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpeidipg.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkejcqax.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfrtenx.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fboujmcz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnsdvkk.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2eydczrvg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyzxlce.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcxqyek.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcsscvy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfasjpq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieexbjgc.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwzkmki.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2oeixraef.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvyvnhc.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tsluqbbe.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvuprhg.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnuiulb.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jndcgjqk.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvppmoy.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lugmrcaa.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ezagrodq.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2npwmazfo.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yofvoyta.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uagqthsb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtkpfdv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2efwwjsvj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnmrynj.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsjatcx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtgjrmr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2btnbgcab.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgffkvjz.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2xuveidlv.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdhsjfk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdvofuw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iezvtthl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2anbttyuk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zitrgnis.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gndfrxvm.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtxxjwf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrknexg.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zptxlaoi.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wdilykww.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkmtudw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2onvhujpy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2teahikyu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2untzetxb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbxwrdn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwhwrgo.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfrtuzx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2srkrpnwt.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkbskqh.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlurbkh.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvzdkgh.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtfqauy.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cokzwfnc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfaykxql.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvcyhpi.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gsytrfjg.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhcdyye.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2comcnmbb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqsfsuy.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwtxsbi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmpfcgc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2unzlkxay.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqlleyx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggicrmpm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2vfajuhfy.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2brnsiyke.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdpukwg.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqjuunv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2phkwwcxm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2utevnicg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2unkjgfgb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtqvrnf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2dgukveur.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrixldx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eujjsxvq.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qefifzmp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2oenjrfhx.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvtoxuq.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqlptmq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oimrhlfp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iztnwgwf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2mhezorkq.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2vongwois.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgciacx.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2djegmazz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjljvkls.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pspyknhk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmntjmb.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2oznjtwsg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhkghqv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2oupgzghd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jblmrlyu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzvvfaz.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbxdegy.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkniwyvi.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiwpbkp.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiuvgho.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxcuqwi.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2embbfmkq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdzihkw.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpgjrjx.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2enjzjisy.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfswtmz.html


<!-- 参考信息 -->