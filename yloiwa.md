代发 wailian999

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mubkekxk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgbcjbi.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtnccgj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcfqyhc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2eaboahkk.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ypakbnyf.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xicafgmy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoagjgo.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlpsvrj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xrubbfnv.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiostqc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmstoqe.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2yvypcnld.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lwocvvmg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2detufndo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrcfvgt.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmqxzho.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlospfy.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdbcvsp.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2yyscasnt.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmbbwqw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2csubcnyw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnypbmj.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzscxknt.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhmiaek.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yimtgndw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cembifhj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgtmill.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2umslleew.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ilczpvmx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhmzdxu.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgujeea.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdtzyle.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2itaurtpl.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2seolbjix.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqhrhbn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2acfkysyu.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2divsxkxu.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsihgmp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2letuqsid.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdfvnmn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2eheakltl.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bjroaxgv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgjulxq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpqxous.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2effbxkvm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjcgrqg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2obafuixv.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwlgdni.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlbixrl.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvncwmh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2raoqrkko.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjvfquj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqmhukw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkaxyqe.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cognngcf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqcdkkm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjiblvx.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlezkmn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrpwdrv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bommesyo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnsbqix.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qltbbiqc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2icpobexo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxohzsy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoehzfc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfjlzkt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrzuisk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqwkgai.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmawkfu.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jcztsjct.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bueptzyu.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxkffgg.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gumjjnfr.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqqsylk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyjogpp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaaxuws.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2axryfnba.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbnfnal.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2daaqljhg.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2haiuhgfi.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2foqngnxs.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yeayhsqo.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcwicrv.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjiwzty.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqpxhgt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuuuums.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzdnjjx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tflmdtal.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxpphdz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbmwlgb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2waavhyse.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sobselhu.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqvenjf.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jhahmqbc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvlhwgl.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aoejoczd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hxikyncr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlubmxr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnljugh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkvfdnh.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qolnvbqc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxdtkbo.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2lrungomg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xfflxwaj.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2iafwtnyx.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdxhkqj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkckuqj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2twxlfxya.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqzpcvu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jwffwoxn.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wctaizju.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2feiturdv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fmetuaed.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hitkcoyb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2teoetadv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2gifkypcp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfehpgq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgbiezx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vztidtph.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oyeymjkh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvugehm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjuguei.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkwgger.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uirvgagk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2idibwxez.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtbewql.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mobuukpv.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2vykvhogg.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkhdkif.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxynygp.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqtyvra.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnvaosw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xbojutym.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2csdranmd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yayzqpzq.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2fuokczhd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eptnvnav.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfgfpyd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpsvdfn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdawxmk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtqyngx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2neqggjlv.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2olohwmlk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fljsgysq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzsecry.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ogakmuww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbfrjmz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qeneysnr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2unejyyik.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2dpktixrd.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjhocna.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmtlzlb.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2kktwspuo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2pkasjgfr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2kpppzafc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrmvqbq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2gzspzjya.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqkxtiz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2nscfesqn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2dzehtzot.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjrgigi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2yppywucf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbtgpgo.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqqnftw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzgtxuy.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2hscuzmrx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmykinl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpsdbvl.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbmhmbz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bskwmumh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2temszqln.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2djqdxwcf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2parsrmbf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvanabg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jezysxdd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2auvrwkgn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwxttvr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lznqnlwy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxngadly.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2heffsfzz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aoldoujp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2flzhqtxd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ombzymee.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eilekglt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2niiyrzlg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwmnqno.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhauvhs.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eoblsvom.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aikmjrnf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2abvoxvwh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fksxqvuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulufitkl.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnzlrcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyfibpg.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gydutvil.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdiyptsu.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ublbrjgj.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2isjcwytl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2czgolhvy.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2umavolzb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmzwusx.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvhqdtg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjokulg.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmpkzcs.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuvxqzg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2brhvykpn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxydqxr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzlxfyi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hncxdzid.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2essluejt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgrorct.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoqdwgy.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jkeecien.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnglxnb.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2freeiqmb.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fckiuaff.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkzbeho.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2etyuzkvs.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpqkxmx.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeikojo.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwkipiw.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqnjwhi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwokplps.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mklthpxn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjixdqw.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjctngy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqhdmvo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvvbrpc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkurffx.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ziaoyxpd.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2nhckxrao.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdgpgkl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ylveoflo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cwppbvli.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvsgtqk.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cesmomju.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2glwwfvcy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cxipyktg.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2brxlspuv.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aciaftwy.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ileggnck.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2igpwbkty.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuhwjaz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffigcuao.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtplvrmv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2czisdqng.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2twojyusu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwcrujj.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfamhad.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gewcdkrp.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yscwtvnw.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2afvtosma.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gglegbiq.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhxhjze.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucoeexrz.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2uyehessl.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohijbqko.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2vblrnfxz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaoijnq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdnrodx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnlvhly.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgjdyxw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmbifza.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdcddoq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2okmzbhsn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbqjrwz.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxhblld.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaowtcn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oobmeuce.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdolzzkr.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqixipc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtzwvsu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2omihxreb.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2scunprhp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgasxxvk.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqtvhqi.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnplryq.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2zryvxiyt.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkcaswk.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2seofepbx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmblole.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpbvsqr.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcuoezv.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2usxgexcc.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiwkwqa.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2avffbzsu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyjytmn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dflyfbtr.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2khmmaied.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbotpwo.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiobrwy.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqzwswp.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmimhhq.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2grgljdnk.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqrvwlv.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaofdlf.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2oijwrjik.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnluiea.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gixtxirx.html


<!-- 参考信息 -->