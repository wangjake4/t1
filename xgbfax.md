代发 wailian999

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbsyjee.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdlxjad.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqjocvw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cywhfsih.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fpojlwjl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjedefk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2naivauax.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2confqjtt.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2isntfepb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjxhuny.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2utymldlu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2shpmgoqb.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfcxbvn.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2owqweqmr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwrnvkh.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrueazp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eitpbcvd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2czvyaydp.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcucsxc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgocsxrq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeqhkyh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yogufhks.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mkygyltf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoxwoms.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2umlxyhdu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfhbkdr.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lksekwkw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lutgcvjw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjuvhmv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2aptiobkk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxobcqy.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyuwkdv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcrdiwg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsvcbyv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oytgcvqf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnpozfy.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjuiyhx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2djsvqcqf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xkatoehc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lkiqkcby.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mzizipao.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeymduq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2brvbenhg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2dscgybem.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdkcgtn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwjnjlx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzettop.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2htszsfxz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2nddbqikm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtgyqhk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaihrnk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkivciq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkuqqyr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hpukvyer.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2znswijeq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zuaygybp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2azukgivz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jebprrxw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpfchjg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyasejo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhvvofj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfmrvof.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2oucwpjxk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkiynhw.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2opabkenz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhkoygm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2bosakugf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2npyjqczn.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xocnmsfh.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzjrcfj.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkmaije.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tngguvhf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoifjxl.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkopthcj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzzmxgm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndznbenv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2alezplsu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bxblceba.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2zhulicbk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2thgrviad.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrtqbkv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdifgdb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hohmuonj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwwuhfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjwmkbl.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2oioaklke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2huaieydg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2tehlweds.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwwjmey.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnssvbm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qadowypn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnjgxun.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcaueak.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fzixrevf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbpyafn.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxmdtlu.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fbemolmq.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2chlpusbw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmrwgvt.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbrlstq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqkoydo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fmholojg.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rracbddn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2etxhkoeh.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xauhubrc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpfyxpx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtavamv.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gslplhie.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wehgipsn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhnyshm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkdgbfj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2uegivhgo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2paitrhhi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqtktfn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsqaivs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pbggslzr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2euxnmyve.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjtafxp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjeknln.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2keygirvp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yoipepwg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrtfawr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcsdvyb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdiqdjc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfrvnvl.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmkpytj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2obojxndd.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjlplwc.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ausbmowb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqwxajb.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmsaibr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wkehonss.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2jnefgmmb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hybyweek.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsuufew.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2eliqvzbp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhhhbci.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsophrf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2qljyqufg.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpnutab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxdjjsa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfejgxu.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfiujmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsilpuu.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2uuozxqvx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbevhzc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2shgrdabz.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtpvnup.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wywmzcxg.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuyujqh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2xovvpqxh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2tvszlnqb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlmcqep.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2encxufzc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2railcokk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmbfwvd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqsekth.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhvvhht.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcqywky.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxveuke.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnujdco.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2sowpfmvk.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2memljvsh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfjoadd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2deztupkj.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vztaaehq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbhkvdn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2slnxvtww.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhvobyq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oykvvymk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rubpxvdy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2msxisszm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjlkelk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnyflsj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2arrlqdrq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkofjhor.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2giyronud.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yituqxtz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxryrpxa.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2csjctupp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmldpgnh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2szoqbjxg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2trbqiaby.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwnoxqr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pboynnus.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtvkflf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nefyhjhm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuozucb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crfiivfi.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yblmdsmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhriidj.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhraugv.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrzrdii.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2oiybrnbw.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2supvalfu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnezmye.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2viuvfhnp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckijsnqj.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbolfngy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbndhox.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ppneywaf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2osbynjgj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzifujor.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfjxhdv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tailqjgy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2emigcnwg.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmxrvyo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvdnugs.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjjmwdc.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ovudiaof.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2lafwbkbz.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxottrwr.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cldbvnwc.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rphgbdrh.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfrhnvx.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lpspmyja.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfluymz.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yadsmxbu.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlpstwi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fijpafxc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjvueze.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2nvssbele.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdbkvha.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwrymdp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdssutz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2cusazfot.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwihhha.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeyutsz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cczqdtbo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkcxdcc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjvqbie.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoydtgp.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrteprg.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kohbbgmx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmuoxvu.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwppgtg.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsnngki.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdohyhn.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2siygxqod.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2iceuwcgs.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kypznvrp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2eegjinhf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcyreyv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvdhvan.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mejqnwye.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2buivquxy.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsivriko.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjumgvlv.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoxcush.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyezznu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqalbxv.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbpwadb.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpwbytm.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynotqawh.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2gorctoyc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvobcuq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrlykco.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxabdwl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqrcrxt.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qilovtnq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfkquui.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoadqky.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahizmdcl.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rplrlknz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsnnjqb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjsamwq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mudkvjtu.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecosfqje.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmshcnwb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2eukzthah.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxahiyo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfzpufe.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2telaigus.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ushkxqmi.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcrfdrz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmafvjr.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hgttsrma.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vherysdr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2leqapteg.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2serdnhrc.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgepafc.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2povksyak.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkteqjhn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2akbhykeq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sowvypvq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqhwznd.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cggzyngt.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxfvnnc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rneyztfh.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlprqnd.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmdqbba.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lymvcprh.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcckedi.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmzwlcd.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmdwxxy.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsokrpt.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hctklvrj.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkfdgxo.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvowclzd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlzlthl.html


<!-- 参考信息 -->