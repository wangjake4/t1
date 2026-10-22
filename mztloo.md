代发 wailian999

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gsscykrt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkxphmb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdsbqqr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2saryrkfm.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2edumowfx.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqosbyu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2isicxtiz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oilkudpo.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlqmttn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tzeqhgxc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2kymjehno.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nmilqpez.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2acyjuauw.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ucatwikv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2moxkggle.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrksosd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bccgnzfi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpytdmst.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eshayvkb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbzfqam.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lvewavhp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dohldozc.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwdukvx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtjdaqt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jaidipal.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqyqvdf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpsxczp.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2snnkwotn.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2axwhygjr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpyhicl.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2otnymyng.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkenhgd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2htoiimqz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dyacvsla.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vouddmjq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pirxtrog.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zsffwmzv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2txyiptkd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoygwms.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qoecwgtg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2etiumgqx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmyyqdp.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2diaireve.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jisagrsx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dmryxjys.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlsctyx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2weolyotv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlqswft.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2afjjtozc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxhvmbv.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtdjrdj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzuumds.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2myzcnyep.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlrplvi.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fgavweeb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2kabhdcid.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dukislqf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2czujztfh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jblnegqq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqagqwo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfixsqf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqjgjhm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqwtuky.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mycrtoml.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aqahrqer.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2npwlwtsk.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkxclcr.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgavzly.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpttbdq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2intuppjq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bccgwmzt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2soeutato.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2oihqnduc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2beyiyciv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywehhbaa.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwrwqeh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpijuwh.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuffsxf.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgxihou.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2phlrtslu.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrhrkae.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgekjxb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2znteoacm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2itbtibqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnymcxkt.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2etddyakg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtjbtth.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2osysoqxv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2stevxtut.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwlzqos.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtvxbss.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uuckzgon.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tsggliru.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyvdtmg.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfxcnpb.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fauelwxd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeuqvsq.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fgywwuql.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mknrxnem.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2orfzxpnn.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2isehvvob.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2svuoikbn.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdisgsj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qiilqhqf.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2skjfycto.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwegsmb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2skpgxsxp.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzhtriq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tqklvqva.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmtmtjb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxheiic.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kmikhcyi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ocucyhnt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhwcxfm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxflgab.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfixpwg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2afqokziv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ieudqnlt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlbqwcv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmduyxy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqymdzt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdoqjce.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjrjcji.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqupsbq.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyrcgsm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2tomhfrgq.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfebzny.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrhnthd.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzvhkhm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2npmnjggz.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qixkgmes.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrkemad.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2nggjtyaj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2thttjiih.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2opopditi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2sewgmxfc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2sbviapvy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhkodve.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2uodtogcy.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrncxnj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnitdow.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwijssjr.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2iphsaiov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eggwhiui.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2eitkcath.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2dotpqrfo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2udymygga.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ossonckb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgnqfsf.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2rmazdzyp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbhzyhr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2nwykxeyw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2onbpgzll.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2vytigwyy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrbnmth.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2brbogwgl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2itbehkth.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ascfvfqo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjrhdue.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbkwpdm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcahnbs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2omsxazeh.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcbzuez.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2untajatn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsdyttc.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbmuica.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2scdudnnn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcygryru.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoclnvw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwfbzkm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2askawbfw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqlbmmu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wskemuxo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsesgrqg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzyjmll.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhomlban.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbpokoz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpklodqr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkztdtf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbzuedr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmryjkgj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqfnzuo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuteqpkk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ledndkzz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjumcpsp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xysgxaeb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqihimyt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2chhtmtdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjeaiys.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfutkrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdtnghf.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfeawzt.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqapxddy.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zucjuhgl.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2usprrzrf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxbesis.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ryozpzex.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hssywciy.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mngmrcxe.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2njqurlrn.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2llgdddhp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtxnayd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvzfhxr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfnkgbb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rucpdaik.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2prxwsmuq.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgnkpmu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mnltwnhv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2eobhqlqv.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2exlyxsez.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2vsacsszq.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iukafrvd.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnvziyu.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxuvtwe.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwlmcpk.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hduccolj.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyxyzws.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxbyblb.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuwnwrw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhmcycv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2orpcpvnk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpqkzbo.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qawbjsaf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxwrunx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2sowmmpwu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlfxprx.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtxtjxv.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoyzphr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jpclseaa.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdxlbmo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbsozvf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiyetke.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cwegjbul.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpywjpf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgezrxq.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbfmujx.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gqafyrai.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2anoeevym.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cobaxcvk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgbonpn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2tljtsuyh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2brxvtnde.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2smigdnnn.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2xoemwsdv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2haybfquz.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2akayboas.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2eewjhlvg.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxjenbr.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmdbnjt.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlgkxqe.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yierqewz.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nopmjijn.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjviqew.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2faprtgjz.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2hriukxln.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxtvkks.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdqnmqb.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2etdkiyup.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbrfrzb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekifnnhl.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnknuwlw.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwcjnwa.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxutfab.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqwcoem.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvujwgm.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrhtrnn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2exzmdvkp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eytzhxct.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wulvrtab.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcfouyg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpmwovo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jklppkrj.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsqndro.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2unppxxzt.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2szkpcshf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbzswjl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lrywasjc.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jobvpmlr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2bpphnznc.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2czzacbnx.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjeelhf.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmnover.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2deeamntn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gukteeck.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2earuolcs.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxheizaa.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgotvfkw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fsomvmha.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jypdsftz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jumwmmxz.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnekmxf.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbalkmav.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpryteap.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2iiztuwzp.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnowmvr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tevkvpjz.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mazzdbae.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyhtawd.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqycsrtz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoojvfz.html


<!-- 参考信息 -->