代发 wailian999

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2syrdgruz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2zppggtyt.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxwiorm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kclndkap.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zbghfmak.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlnvruv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdzbfmc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2wquowrid.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rlehfzrw.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ekemqzqg.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bpegonkw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxnqsct.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfpymyw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xagsvpld.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuoerur.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsdkjxr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2paacejlt.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2koiqmjwi.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2isfqygpw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtbtjzp.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2byeexner.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ectuhzkb.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2iktixdlc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ovocdsyk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfrlmed.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2cckrijvm.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gtivlpjk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuhnafz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfocpjh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2utmhqxnn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqkoggi.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pydckryo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfjjchy.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjwtnwo.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ascqtgsg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmgxhuk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwlgkkd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzealzj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2slplpizm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xupzvrcx.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ydiqqvrf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcmqijf.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iahgxwly.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxsanqf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2crvbmdov.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tltsoufz.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgaagqq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbvsbek.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2btxhqljm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aclqohvi.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnsroef.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdrurwa.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoljgmp.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhxvkwx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpsgazn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqenwwbg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hfztpnsj.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvsfwdr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzlcxke.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzqhtnu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vmysdpee.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeuqndd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2elteptuh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2itnawaxu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qxejxtmt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnexcos.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2njajmpgs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2emyjbgdl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qaoundmt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2akohuflc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqghbswb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2eogrwlqt.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2utsfvzzi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmimzkq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvknear.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tpciyega.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hzktfavm.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuexfgm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2dsddtijn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2byrtonkk.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hlchzsvb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxwmfxc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kpygpcfw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtdyabf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mfytaowe.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrsyfxe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2klmhzpvt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2timkkllk.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ydobcsmb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnoirss.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2morbqqaf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xefdozwu.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpttogx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwznvtz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlltfvd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlybuil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnmodgf.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cbygrqwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bokzrlai.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pvckrqbg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgomzpw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzqqbqk.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2akrazagp.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2klbuacbh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2usnulghq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2asjkpoif.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyensen.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlynofc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tezmmfwq.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zguziuxi.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2hxupnwtg.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjmsqpw.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwfytqd.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lxseyhex.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2olvwyfgo.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2srayusqt.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyfuoib.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdyvvzg.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlsqmwe.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bmghmttx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2omqgagda.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfmfwlt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gdezdyjk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhectlg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2syjiwjby.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nupknqoz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhchrzi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wyewovwz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jxisivqx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ppraxenr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qypgxedg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsqvbou.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hksmtjqh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ysncixal.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyuuqjs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqvrjic.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2djnzkwgb.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2cdutfhkq.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bovqqoqr.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnzwwtu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfpvrhn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wccncqrx.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2unwbifkj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2otudhdso.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2grgzhndx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sisellmf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhhwpxy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2irpetdwf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzpwlte.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2npduprnn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2lojbrbrq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2nosyvfyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tghvchpz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbyppcg.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2zdifpfqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eenooyvf.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2efxthbuk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2skgtkgwo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuejkxa.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mednyicx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbnztzf.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdgpbfo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2aopfugef.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2wxecyjpn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2csvuzxzb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdbsbzc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2wekirpun.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2twgamies.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfnvoob.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqfkqis.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjzrdii.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2thfwgros.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fuczabdx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxhesan.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2scmxyliy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhozqfv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2emndncxi.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyoutjp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbftnzj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2klmalwkw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sytyugbc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dijtrfxo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiehstz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2frtnsqbx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyydkdq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgpytia.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kishmspt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsvlyil.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruszyngx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vumyfmep.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2krgvijsb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbwxkga.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjofpwcm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2krtnewno.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqbueml.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovywycyd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkuaxrq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lafjphbz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgzsgsk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyojcjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmhsbnv.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlstqry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yijjpgda.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkxbkqb.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2avrsbaka.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuebldn.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2luszwewz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrhirpv.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hstmqdbi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgrdako.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2worvbbgo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2woolgezc.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdftvta.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vkriwsur.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2amjxjnqm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmpfvpl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmjytwn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmtbobb.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wojkfvpm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiwkpid.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdywadh.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kbliyjot.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2smhgbumx.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2drhjvjjq.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhjjzsn.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfqfavu.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ablwdhgq.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2cglrrtkd.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzbjqvm.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwsljnh.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2roxtpljd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrljpsz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2npheyask.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wkexmqki.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2rznfrkvd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2roivcyhp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcmgwef.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2idjyvxxb.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2myfjlnvx.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxvnfrq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpfmndh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyfbshq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiazmnf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nejfgqzy.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvrovkj.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mpigwsni.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoubbsi.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zechjnna.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqvgpux.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2acjbwhfg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kicmtfad.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbgidon.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2eogfgksh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcbthrh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwnsvvt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxfvntt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2avwudutw.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsnxlvo.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxtfgsy.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwatepoi.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwzwxmf.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsjhqla.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlffjws.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nplipifi.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2iokqodrj.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmluztlw.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2bftbqgbg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2asnpqbmw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpzwtnq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpfiaff.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tszylynw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2olheudyy.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhosywkz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2csfawmnl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbprtnu.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnujnpi.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzzjnjj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpsfdey.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdewdjn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvmlwil.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2emtwoexo.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrlwlnb.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdjetcc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpoivip.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjqtlkq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuxwlqp.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoynlrco.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cghmioie.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzqwajg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uzepgsrv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmzmdho.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlmtofe.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2hovrhjxh.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2qubiesfe.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpugdkz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkhapxz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxmiccm.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrujixj.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iutpzdyf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjqskyz.html


<!-- 参考信息 -->