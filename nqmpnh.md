代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lwoiqvcp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qovsiiog.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzpmgaq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2tccrvhvz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ganspvpi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bacmwosk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wolalzeb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgarwgwt.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2brohzlam.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gakukavd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2osmvenfm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvroooh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ooorzxoa.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsnyswy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjhkzeg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bziwddif.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2eelrjgdf.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2oujokrfl.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwslbqv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2erwsfclb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2omrmjvjh.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjlavyt.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpklnua.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrfwkzi.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfvbzue.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cweczefz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hlluhmvw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2knonlahe.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpaeltg.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xuohjoma.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrsowoc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2pttmxznz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzuueht.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibajnauq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2niqhvgxo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzfqmjo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zsctjriu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2owimtxqe.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuahxcx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaaxwqk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2keqxmarb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnqauhc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfaveoj.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugiyzfrn.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aydexsjz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2yxctmfqs.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdgfrvu.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlbmcmb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2liykenmw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkcvigl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgkjppp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gawzxvnk.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2aruxuftz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tftpplle.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqxejyr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ewunnpdo.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhjnkwv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pruarvah.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vscrpscs.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2miehqjhh.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tonzbiix.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2swbsoqkj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wiggavwy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ngixfmon.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2uimmgfiu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrybotd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzerdmk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmzatny.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2svretzwe.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bpapnzzl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ganjhuqs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2bypkxmcs.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ochmlpgs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2flkgppcr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lixeqpcc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcxatuj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2slecyhbh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihatgrkq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hszyhnpx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2iisjkymu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqsvwcz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbkqryl.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2omhbccul.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2svvrwqce.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2exxmpjjc.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uceonuce.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuxmeyx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbramida.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2frlyhlkx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwygagg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqowjab.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lylhvcbw.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxfvqaq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdtenqc.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2pndmaccz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkyouyx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfdcebe.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtoktkj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bccdoxpg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmjtlqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgirhlaj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2adchympo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npuwkobe.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2akaddkdz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcccadg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2snipjjmc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2adjafaya.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiulmma.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjuxfce.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lyggpnhy.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwlzecx.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdhxuop.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hthcynzm.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wryvlanl.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnhdazy.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2sedhjmds.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qehycnxb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgefpbq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mkipuxqx.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wyddokoi.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfpijdh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmluwkb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlxmvxg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpwjfoq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2caeaqmhn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hadtfsds.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2upbvcpjr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zfackroi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwsnnoc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tucphwuq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnsyqmy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pycrfobj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcgxool.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jwucodhr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2deholhgd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ywagqmmm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2axhbignm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxzyalp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2kycciajw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2snxooqep.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsvuwmw.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpuzuib.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaimrmk.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rofxylua.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2wirpxonq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2curxtvux.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2czxgttqz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pczzyeip.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2odhmsnmg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iadeubzt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlnwrbt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2yznpijwb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2gvexbssp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2xugalamz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2azjdvlwr.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmueuka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asmelhhd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzecqdtt.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2lnezahhg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqeyfve.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2guwicihq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2nammxndu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzzlopb.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2quidievs.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2clujeetz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2wshuhnej.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqpqimh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2iufummel.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxsekup.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdukofy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnknmvu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmgaish.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvcuhfu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfjmopw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2nnijkgvh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2miksktrc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyaetjz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2eqauoysd.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2gcklxkui.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2hlaccgrn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2paiamcdi.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwxhjkl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrasxgb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyismva.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmwwiiq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgtudis.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eydgcdrj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnblttu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcvknxs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nizdkzih.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkaokold.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2enzhpils.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnzxgma.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eydhphbw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzxaxam.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfltnqkp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nllfiyvi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxhjshh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2epyaqjsr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyerktfa.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zitlqdxm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiynlot.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzjkfrk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvugipwb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2laurvizo.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnnsgfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zachydjt.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcocrsk.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvkgxof.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2asqdbcov.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhremwbv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzclkxat.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2djkjjsfr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2boryskhk.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2phpjznlk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwrltut.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuyfksh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpewnwo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uephpbxu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyhvqxe.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgejqzct.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oimtmyso.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ailxcrws.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2nivppuig.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfivbyxw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2drsfzfgv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpzyswh.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvxprbo.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2foylfrrp.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkeqanv.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvsszdq.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrjjdrr.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jakffhht.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiysbqgz.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpafudx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2onvulrhn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdsiyst.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbygrpe.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpqgkyz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaweodm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2poyysitz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2tarxluog.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2owqgfxid.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2qruerfue.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcsklcb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwjqatp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqvcifa.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2micvdkuw.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sgovgsbp.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vixouwkj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxduaky.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jsunsqsi.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2abiywksd.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpwmrce.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxeclof.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzuvpgy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2iargrzxv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgrxqfj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiltrkn.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaisepv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvswevi.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjwihpa.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzssmfty.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2objadaeo.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2djvecpof.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebisakke.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsqksma.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbdnyzu.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2cuahddoy.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbygqyrz.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgndwhg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2olnmyfhf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2epukxoyq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbfefmd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpijuzeo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2obodhlts.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yumkhnzm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2syoxwbrk.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzrfqmg.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uellxcxj.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsdixln.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mphbnsjb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsgbzgo.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlvasvc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjvtnup.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2riqhxgjl.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2swotxszp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrujuuk.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2luxbrtuw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyzspcz.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqteltec.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gmibnnyn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zbroekmq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpspcrv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2wawkcdvk.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2mccbuiwa.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndycwwnm.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2qklcaixn.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrxztem.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2itrjwvky.html


<!-- 参考信息 -->