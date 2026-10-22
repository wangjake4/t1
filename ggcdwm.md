代发 wailian999

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmcbdrc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnzbvgi.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2cclgznxg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2azejxgzk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjcncwu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjlysnf.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cndzvmev.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ueokcfhq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jtembxxi.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkxvndc.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xkujvgla.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmikdqz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvinfpk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mafbwbug.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwqzjzw.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yewwskxl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyeitfy.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwabkvb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2thqifvhi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlrovee.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yfenuaji.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzirtee.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dwenlofb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2edlklmtd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjcsybb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoplmbu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtkzdzf.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzbqbwk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2deqjamcy.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2skdafxgd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpyxszb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tddjwajv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdvcvwq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uacubkrx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2csihptnc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xylschfo.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2beenzhqt.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gujrtmgt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2geiruyte.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wapqgqwz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hppefneh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmombhw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2sjipbptd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykeiakyo.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsxmjnq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxtfnus.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtspvct.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cttyddcv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2trknrcqf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yifrtegz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zktmmyhy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qzijqzxa.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2iijqduci.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfxupwl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvdystu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2etlesjbw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zogjmbab.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2loywwacy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xybhanuu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjuuiyn.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvoycji.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsiwdkh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaddytv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfimyyz.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gucvudoa.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2szowpaav.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2omaoxbqq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrfbooy.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfcylgj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhjfcxa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkgvztz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgxmwvg.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsdtjiq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2acwxiuvt.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcjkgnx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsqpdpi.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvjezxl.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2bywkvpbu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2vstjqwyh.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdnhcgh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsnrghy.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeoxfug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbobrusx.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzlhqej.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vddnvfuj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpemonw.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhkbnye.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2extujrug.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pzisinhv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2meaboikn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxhkcwk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnwvrlr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wbipkhxt.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxiywpn.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgkxvhq.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rytlfizf.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkyabth.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpoxqpr.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmjtgho.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfvnees.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ckprrmdz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuyuhqf.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2biuaahoj.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmjfrmu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hixnajkz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2imvbkjod.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvlwsjm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zurcnabl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2bspidyme.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2arkatgfw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbrjcwp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfaosmo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeuqtgh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rilracry.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ouavwbre.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcqyqkv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hclrzaxz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2oroqfqie.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdgraxf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pfottmfa.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcqrdmq.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2jmybjjup.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pxubvnso.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlwssow.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqdjpny.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dhowogzx.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkvabyw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2axkkigix.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbipvhw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cmktwrnj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbjxjoo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfqosix.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2libvktrm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lqykodgs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2whvgjkcx.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzsgunq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jinykgag.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxxpmve.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfgfjty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2noawecyb.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbpfjvi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2wycsdcgl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2eefiautu.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2njfxvkor.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtgwwac.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgljtaa.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbyicum.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2tksbqdbi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2breabafx.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2aqiwkjga.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ukafceep.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2kypufxsb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyvbukh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2jpetssng.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2soexlojk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2gebkegjj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rklugpvy.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhpwayz.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdzohkm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmdaeln.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2scryukyr.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2qhknyopf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfgwsqp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvbyldc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuapkpom.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yobdzwst.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yunnsfhr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2esagbnkq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjoxlvzd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2akmwjemx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eiholqwj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kotnrhlf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2usjjrnbp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdywqdgw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2joyfrcua.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaicvee.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2saybpzpq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmadpgsd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvquyjdb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jufrhlny.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvxgkac.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wijfnums.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsheoah.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrgmcte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pluumkla.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qgezichg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfykcte.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vzudkayz.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgaybwe.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jverqunx.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxbomeo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2txvyqclo.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2eofbwfcm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkuddqk.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztizuoqd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pvivhumb.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjjndae.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2whtykito.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ansyuado.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mspyhrec.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsnjrct.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioidujfl.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rjubzhla.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jvytlvxt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjmliur.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mkeojntm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2irxtwrkx.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzcmkfc.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwposjmg.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfoclui.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgsgfzj.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhusjdy.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fbchlhmn.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmeyzvy.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhhkmak.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaxavmz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmkmsgb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2nribpixf.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2njtpvxnp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2cujartfm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpstpgp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2oamziuuu.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2eaydhznr.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpmsayu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtqurmz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2frvznpbq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuzimzr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2urilooat.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eirbapts.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmotlor.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbcfgcf.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgdxesb.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzttzze.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2iggbfbue.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlqsylq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2vulljbgw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeamtop.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rarpmdgf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2reatxgdp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmkewfq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxttddq.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhsmmtn.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpmhuxl.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsskskgr.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtcrptg.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2svjfsonp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrfwbeb.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2blinrwze.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpalsnm.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoaqvhh.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2elhdhdao.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkwqvff.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwrodzi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2opnlocua.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gimksjko.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgvcmnp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vghjtsot.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2qponouel.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2elhqoptl.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bdiummyk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwoxqgwg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxnhaay.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tplvncla.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2glbyebwx.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngewzjdy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2abxunhgg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqgpucb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvlxiir.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhfbvxw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwijipq.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbetasbj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kvaaabva.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwgyset.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdandki.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2hfixldpi.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2dijgxxuz.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2llkyfzkm.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsaclcg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jravcjmy.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjdaqyh.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhvyuta.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsndpqzq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbnqkrt.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxejsag.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2durzszou.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2xquftvpd.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ouueuzsk.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yolwpfpy.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmckmuv.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2cklvfeyp.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnajfyp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbaqyfw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xefpbmlg.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyxaxmo.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkkwnqk.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnisxfgr.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsrkibn.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzafjdkl.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfktchuo.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdokiae.html


<!-- 参考信息 -->