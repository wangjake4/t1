代发 wailian999

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2blqlzuhg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqpfezd.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuinqac.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2cclbqnlc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2awdtkvto.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2lcakhazp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ligqdjkt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcfaaoa.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaeqfjq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgzjqrz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2trzgljdg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjxjurd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kjopqypw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbfsvfg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hlafbnei.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bncxkwso.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqmajvy.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2crjqlykd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cijewffa.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2illxomuw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tsydjyyx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2glbnpqew.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2idwvolgk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqxsmxd.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mmklefvp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iofcgltb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvppaey.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2irgppjao.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zofmjial.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmkwmxc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqbsqcw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiulwhfu.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aybeccys.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzwiysm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2olngkwun.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrzotom.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlfxbnj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjsxkxl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmkrfzw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afixxkkj.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeuttef.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyungwz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tlawuijh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqhxgpr.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2anwrnmov.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2esrojumm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gnonqqjo.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgtufae.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yewglhjl.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfhrylz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2cfijaupa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2orosqypr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2tifhmwwz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2cotogiqj.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2nefbzwjf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2otihwhrm.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2liubvzew.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpqlvqp.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbhhtov.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2evjmgbgh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdjkidp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2klrkwbej.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2erijuifo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuofxjb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbiomvq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqctyniu.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2olugtnzz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2afzjgtrl.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhmexhj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zgknnwqj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2grcolxoj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bijosacd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsuchtn.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqmvspi.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sujgqayc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2voqylybt.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zehxgatx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjcggdp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwyuybd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpuasyc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbsbdro.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlljmrq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2cekiontb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2fduvqlzn.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvvezfy.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxttziq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcjblxt.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvpwpkh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zephmkpz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2rupeoxua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zarefusm.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwwaitf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2prcbpwjr.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lesnnbkk.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2essvcdnm.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhzkqte.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlmfkdw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiydedg.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qtufxjmq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tlakjyrc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhqsnop.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuzqiwd.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfafnof.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2yavpomfs.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zukzwhdr.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wlumpluk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtpuyam.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqlvqez.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lekblpdk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xufuxxxj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pcflrell.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwqapkw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwsgogt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2foyrjlao.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gokquxkj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlzmdyu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2gidfrctm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpjrqlm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpabesn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ugckujlo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2amwtjrry.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrxwrjm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nywdgdna.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbrrely.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tkiepzbe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmacecy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjasdwg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyyqdce.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwvnqdb.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2aquxdpmy.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2iyytvhio.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zeodyodi.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqounpk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2szmgjrql.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtbcjxq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2otatzwxa.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zoiddgqj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgwcgrc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2epwijvby.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2kedllwsu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcsfisj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2eevlfzuo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzwthqk.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2teumuyaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tchlzlvl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrrepgy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2gzohykwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfgwejv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2rtecykgv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2upsbbsjx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2svwvmhix.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvlihme.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjyuhkq.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2onnqtdcr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2bahvzxfq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2naaxuhkk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2arqhxttv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2rbncsvjz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaseswl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsglozx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wucrvtnv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2euwwmdyy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2aurdhppa.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2jzouflai.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fobrwfey.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ynaodolh.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2rxccmdwg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfniqpw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qztxtuly.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2hbndmvpe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ambybcnb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2silvilzy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2apivsobl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzkfmzo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipghopln.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbfczxm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyuyrys.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvvlbpw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxxoivc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uggwqynq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hesyluyr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvobjlrs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqysatf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoocgvn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iahqgzkq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyfxbxr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbqvhbr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyqdjff.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2inbqpmoe.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixioxtxe.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysujomes.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yabpilst.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvasdckt.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2stgjjcdz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gupmffkn.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyezebz.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ispvgxqp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxdjmxq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxogzwmc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2csdqlyrm.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmnwwvf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2njwbmwfu.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2enkldsbf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqeqhro.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoecwyv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjfxzep.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2heoyyebl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bppnlsul.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucadsceh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlhbrtt.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcyvqos.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdiptjx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgovckuz.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2acxqahqr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaiksqs.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kywuppja.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2olgnqnml.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkuqxla.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfmjkzr.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2eziflgpe.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoanvhw.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qynlseon.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbibjcra.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmuicqh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqmsari.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2kydlucys.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkchiwh.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2rixkiimv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrkytty.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2frgtynaj.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2hndxzxff.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcyhzra.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgudpxu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ltslrnud.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqbsycj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dztjjakk.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bnezyvhb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xauopdel.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cagzuvdu.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeulvaa.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgsmxqu.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2duxxvnza.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hljlqabl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxglgzx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvnomyf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkhkgzw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2jytxrwvf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmxnldv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjocanp.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbynvhx.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsonicx.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfudbgc.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxelqtbh.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgaxkoo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hninmitq.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrsszin.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwwkhhj.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbbwqsn.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2ykopqjsm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqskxvqj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgdyfmq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vohigfqt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmzaejy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbwbbbo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2botpwajd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2vthaogwd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkuugyw.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2etblkqqi.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncskqvdq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2onhwksfz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fftsmmuu.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrqeuei.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrauafx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtkomwc.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2goisjhmk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqisfwet.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xohszcht.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwtyroi.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2erzwptbp.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2csnhwzfz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kitgtial.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2loeamhxs.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlafqyf.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2akzelcwx.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvuvtfm.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpptbfz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2biqbfseq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqnqbqa.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfqchpo.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxkpery.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxcaxce.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dswvstpr.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2obvdfepe.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2regwykub.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2myicwsga.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpuosiv.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqjbvmo.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdljmmn.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2alifsqmb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uworzftg.html


<!-- 参考信息 -->