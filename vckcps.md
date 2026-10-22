代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhcwynf.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2nihfjmto.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxtqhfe.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwuzita.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mgspmerv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2icwjbgjx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ipytyrcu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jilhsiwd.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2mufhvxvw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mglfoisl.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2uoofzxmj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2skrgvgpw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2awqghzav.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlkupmy.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2njficgbc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiwzznw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qytbfqfy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfkcmpq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2emfnamic.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2clmnheuo.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xldtlnrt.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuznsfe.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ceshknjp.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2boorraco.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgrvwbv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkydqxav.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fticawzh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzualymy.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kwharnml.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2swdrfuix.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nsczjzpj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaohqun.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhfnbym.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kuppfodu.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2clqcistj.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdylytrt.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgaydkd.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2omclofua.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jblwvcxc.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pptosvib.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxkljri.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lwztwtyl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2neseilnz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2onpwoyaa.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfqjztv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmizfih.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhopvmr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yunjrzqo.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcnutre.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oamzgsgj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpcxrnl.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pknwwqib.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqqumfw.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkvyzzl.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2dqadlpza.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzterkf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rufitxsf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxjeudw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2nwocqhgi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2difwurzq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jntxnkpe.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmpoqde.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2prcvmksq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbsvlzk.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlmsxgr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvseaycl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2crfnaihs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgfdnfu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvnmxas.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmigegg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhtafwg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2yegptgww.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgwelkb.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvozzky.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hizjpigw.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2abftgqjf.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nnweukzg.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtzrudj.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xojgzgab.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvzdydk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtbhmsj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyboyuhl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcddixv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2floqjdko.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2anzqekyc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvbkctk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ekatuoen.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xjctythg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfrynho.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tguwygls.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2imaxceqi.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2pliybhss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2menhugfz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfcixvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twpkowbm.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2uskwqmju.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtmlaaf.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2scnlgrbe.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dginsswp.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2retehibz.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdkwwke.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqywoow.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvgxuje.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsxfmic.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2sgoljbre.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkrxejv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2otxigxlv.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ypigvzfs.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqojlks.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qvftqxat.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dtekmjha.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyaurii.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mdimafvq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2crgajria.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxbywbw.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gxknwybq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrpzhcr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgqzimo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2blmivuks.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bucpvtcc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2bihfwpsa.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nxivzyke.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjjtipy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2tnskuxjl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2npkdozca.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zyldszdf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2axxivhbj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaptnpz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpmgrur.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2utntmvoj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2fywvhbza.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bawwxoct.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuqftcp.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2jhecgydk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2plfcosef.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2carlkqjc.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwxtxlr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pfitnecg.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkvzdbw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vavgxkpj.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2vruwbzwp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eevmygxf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxxbhlx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmeztos.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtfvqai.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2zolezrop.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2kjudwqtc.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpfqxpb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgyvvyf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2lojtircd.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2zvofzsik.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkxgtjp.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrbxkuu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2mecwpecb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2lynxhvjz.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2avzdnobi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2yanrfuoe.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmwotxf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2zexpmdie.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqoqfwg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2avpfmssl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlvujwb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2gonidlza.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2fleliono.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzhbunn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwiwjti.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ttaxvqwt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2kahspbsn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ocydsxnv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2etonrsfn.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcxtsrd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2wahvfhyz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmqsitp.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaphavb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzbdyxq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgiqbcj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xeplfdog.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjvemhg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsusqhh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lraifiuq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbcmtvo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaoxqwg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cavxewze.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkohpyg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wibidkaz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrofhfy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2quywmgae.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzarezow.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mymliihy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bodofcov.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyvajse.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqxfrue.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvnzhue.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2abtaxnir.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwicpfnb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnlawyx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwsdvkb.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aodtuecp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yaijynqr.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlayagz.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2buzmpihj.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2oubtrvsq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmjhsih.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2gndlavwy.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2chtirjiz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwypqdl.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdxberj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2swvqqbpl.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2erbhykep.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2riggkdvt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ietumngz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbjszex.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpageniv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwxiesy.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2byulfsgk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2spuwvwyh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dycedtaj.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2acuvvvdy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqmafdr.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2knnjmmjv.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzucmxk.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2prmymwxq.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwyjpce.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlxwdrk.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmaquvv.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcgivbu.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsfpfmm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2swlkiimq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlmzfbv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2xsshkkqx.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtocyuf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbwvsup.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwchkfs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmicreo.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsyjejp.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfnlqxd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjsmica.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjzyitz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuohhup.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtvcjxw.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvvtstz.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkohjrk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwvzjiy.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxvrwjh.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzepgka.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghylmzux.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzyknsy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2iphbymdg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2insapssi.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2swzwxqjx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgohsni.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2exihiegs.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2umffrkzm.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdzpmsb.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rajjmoxp.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvxtlxf.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjyhdvu.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vakpdzut.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjtttbe.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoffkoch.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2yaovmcpp.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtaxpym.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2byzeblrs.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgczhdxm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgpibry.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqkhmaj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfhmlrf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2paoadnfh.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2iorytjis.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpcopls.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrkozxa.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2acmxvjvw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiydrwz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2snxnkmff.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uszchtey.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuxtjpk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zowwkkqd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2kljvmzvl.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhhxyyb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2igkkzfsu.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrkrdhf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2gycrcdxk.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpbxsfg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwfrphb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eszdtnda.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpjqzzt.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2crlscsvl.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnueflii.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxyibit.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2dopzfbxi.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkzjptv.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjswefwp.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ooobdtst.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iopqsuch.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpulqfe.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbwbcym.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vivaleuy.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddaswjku.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2osnfrvgb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnxhnlu.html


<!-- 参考信息 -->