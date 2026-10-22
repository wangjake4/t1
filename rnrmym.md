代发 wailian999

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2aftfqhtm.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ygainyvt.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pitnnvyg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzhusoj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2glgwcvjq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuczvrb.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gcaanjbo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zllyuycw.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2puqiqzxt.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2htzwkenp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rcldbjqi.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzdiioi.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ascgsgeb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qczylwva.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmxjbii.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nblibobr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmiraya.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnnxojq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2izihqllv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkceosm.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhcfztj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mozhuapl.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dboypxgt.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pawccgrt.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgfjqcy.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpwezmi.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfjbopq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdpunwc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbkwava.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kvylbugu.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiqochy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bngpahdf.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gipodvkz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zffygvjk.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hobeifar.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ufidchfq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzabxgl.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sbohouus.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmsjlsk.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2luykpbek.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wxudepey.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjmefwg.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfqjmzk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2eopuljeo.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2tszuxiln.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2krgjetrh.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2idvdpjcq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxrpgee.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nbedzkff.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lxscldin.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qtizdioh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsavwoh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvojtvb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2idyhnqmi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsykggdq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qufohpea.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2srcmmpff.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tphxsnsy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbwcfca.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwxaisk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vapesbsj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrsvxgz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbkvbbo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mawesqoz.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2umiiygog.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2azpxopul.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jalcreol.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhkmqll.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zzimrxbn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpkpojt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrolwtlh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbesnoi.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yftruxsy.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2buoaywan.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2bveanisd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzdbxxx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tyigqyno.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqsofcf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyncxvn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2rcevvndm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jekwvfwe.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ljotnxgh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cshevpnv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgwmabm.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaovkhg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dbaxpnsn.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2omqcqwfd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oothyyxc.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2raitytng.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmjmpwu.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqmpord.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxldfhz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pikgcwhp.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvshlrs.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrlniaq.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2cudqlovl.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nggqxnbc.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgyffhv.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcztbwn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbzvjvg.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2coluaxql.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfffmai.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pafphgrb.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxqapff.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfjncsn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnhrtyx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbxctry.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lcicbppd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2djgrswld.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2decsmmhz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vaywfrpg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2llmortjp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yajmxoyu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mjefxuzg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rilchgri.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2asuxsdws.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2enhvybhs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2guqvprmn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2orhttdym.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2itdffrvv.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsxhpjz.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xancynlq.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtzadak.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzjujez.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2nikklyoo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xlblpxbm.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2orgusqqy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvisejd.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2axsujrfs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvuslpx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcsslui.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jttiknrm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2cgarqnou.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2bddstjcv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2hojmkyew.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2hqklbotc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbesqodm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2azrfuyph.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2qppvconc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txedoded.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2jyllzzol.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2egbplrlf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmuegqs.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2wvehekub.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwhhbso.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdgkweo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrwbksf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ofovdidp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2mukkvonw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2aejucggb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxgiswp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jjguyvtj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2tlezfxbt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhrhhlk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2roabpgvx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2meyunyoz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2iyogifyb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xstbhvpy.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqeldzg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2esoowmhd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxzwtuk.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmtrtix.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vulsplgm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsvprer.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfozqel.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsgkdxm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjsjdzd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pispirrz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxkoohg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgwliyk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2haiyxtwe.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tafslmbv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlasntix.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiwyuhm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xurossei.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjehufvy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aokfqsfp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlejwpea.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlowmcs.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iytjugul.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsaxhkx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsqowuc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uotpspjm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdbgflz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2isunwiyh.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2afyjknsk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2orjguvum.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vcenxizb.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeerjly.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfpkhwp.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xokqeual.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwururgb.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2egfkriwu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpymfckz.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jelgeqxi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcphjpk.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkabrfk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgokjgj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2udsopghw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiojmzg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxxbyvb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjryorgg.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnivoyw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mrphqtkr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2seuyhyxl.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kzalljes.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2vsflvdei.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hojlxqpu.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqvxvie.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2goufapdo.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xblvlwhr.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhmzmxd.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2nazoqfxw.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrdeyqc.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvgpqxn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrulunb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aygxqaem.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cabsjsyf.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mubgkuqs.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbmxsqb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvfatab.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbocnpbv.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2hpaivitm.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwejujs.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbyntjs.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlojnmv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ohljvcrd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkrxgqj.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hycnwxqr.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hfurvthl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xovgyghy.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2igeudvav.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2oicqeoki.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2irswfxyz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2iidoymuy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wufojpzq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2unyztpng.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dutpyinh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2owmxkaas.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcqryrb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dficvydu.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wywfqgtr.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlaawhe.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxtroyr.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2avfjkzxh.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2unshkyxt.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzbmqya.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2alvjecki.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2blubtcdu.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdvpgnc.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2dppbnjxf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2goixjozv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtbnvnc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztysoayd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2iowxkoun.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcagifr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2piqdczhh.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgjgxnh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2reioxwem.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvawelh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2udvdqgze.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2grcluwqy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtjdktv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrldijg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgsnzqf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyryrge.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfgqnmb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcobkra.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wngmwtnh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqwmife.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzctitmw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tivtozaq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvyuayn.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sznclkyd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2yjivrrfy.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2unveignw.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhxxvyj.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsyfwdl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2koiewbbj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnuddwl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnrrqbl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkrbtbe.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpdhkha.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2oywwpcnc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2acvfihso.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwiinqwm.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrtfnfj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsyvqno.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gicoyhiq.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2oapojwpy.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2icgsqzih.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvzjrrg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsairizq.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtljvkfh.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtowhrb.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrjwonw.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlktdjk.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfkdubb.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pivlxopa.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsknixj.html


<!-- 参考信息 -->