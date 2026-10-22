代发 wailian999

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cffooshp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nscojylh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zdouhjxr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvjoppw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrcycko.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2drriuuwd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwgtbry.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2deuzfuso.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2xtefyfpm.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2exrkgebe.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxuktgh.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfcvyvg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqqbyiz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2krlkcppr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaetduf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjusxze.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeeksxw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxbcklx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2sraxpflw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcpjcxt.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyenfct.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzchmql.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvxvkfj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2uspaxyqy.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcskxxk.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmszdcf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlzjwta.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsjbili.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjhwaou.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyygnno.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbigbzp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjpjdwl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmpjtgi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsseluj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvicspf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oavyofpi.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzpfuxq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoiklsv.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2evntkggl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjnrwmi.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2twbmhgpc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdnespp.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqfiwuh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsbnqmn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2sngjauof.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lizqauff.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgsuyxz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbfqbgm.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2drdojijj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiwrepa.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeaspeq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaxkxgp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbmvqnv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbxazix.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuneatm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qczwpytn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbqzurr.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbtychs.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrswvet.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2etpiiaef.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hurfqtkn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbvjvzd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcqgirm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2goophzxo.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2crelisyh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2szelkrxs.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdihthe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgiomlb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmwutnp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxltfffr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpmvuik.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2tcceowky.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuvrdkq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwjbbfh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rkaownin.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxtlkue.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sazgjjhq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvdxmjz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgigrev.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2aggcpjsi.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyntiat.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkesskmr.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kxezteoj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaamisj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2sesjblpg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2eihzslpf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzboaesb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akgyujsk.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tncultub.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2panpgqdu.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2scquoxkp.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bboftuhx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2vegezwcm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fldgmcqm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhbhznw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdymdda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyifxiw.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvtbowf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfafvtli.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwljuin.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ciudxfot.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlvsevi.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nwposcna.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yydhcmva.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqwjyah.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlhjhbr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hnazizxi.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hoptiuzh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2masaojjv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2byvksxuq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2gabomvho.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfclxrl.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxgplnq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvkblxr.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2amfasjck.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmwcdad.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfhnkwr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dxepnncd.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xancsvta.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpitsrs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qbypygjz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vncmpthz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2aidgbpwr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvlrmfn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjgpzcl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbhzxox.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2skjehjsn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dozucgjy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cygjdecj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2owwmxtfo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsemphw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2khjdctee.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjlwwsw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2trmpyrhp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2omelhcoc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2grxssbnk.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2iwovgfbr.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2oympwbok.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hfozhiyw.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qqoklfos.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrezblm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2byosvhis.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbrafzu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2llswzlcz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2howiljav.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ywscphav.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsvyogi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2fwysulwv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2frxgpcvi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2xmokhifn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2hrufpsfm.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrepajh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvqzacy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2csnxgpje.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqfqsoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kyahnuzb.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoquwib.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2kysehara.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2djgwvlcv.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2szyxjlmp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tctkecsp.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlaekrs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuudrji.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zqclhvqv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2aodievul.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkfcedp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdwsfcv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqwsbwj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxklrxh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjysmos.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnwfdqv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxhwnzn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uozxglje.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uqifsztt.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyqwzxn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2eupqnvim.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyiojum.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2zofiszgu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmfjrtc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhflqfsx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2idxpibdf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkikmor.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2elvrjujv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbejdmzn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfcmzaq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2itmbzimr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbgnhau.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyczyxv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsykrdcu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pemlghep.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzjukel.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwnfpir.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvifuji.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmoazie.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzubbxa.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeelbtn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrlrfib.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzzfjnu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2klabtuxo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuzzryx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jybmdakz.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwozhccn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pficoarg.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2icjhriiz.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwfyqtg.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2voqnhduo.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pukojxdz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqyktim.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrntgve.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2alerruyd.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvzopgf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpkouay.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ovokwedd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvotyul.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrqfpqf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnebleda.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlfddgl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2puummunk.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2osvfhkjh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjzkawl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmsdznm.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2evkuwhyp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2iknljocf.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eruzdvfd.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2enqaccrb.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2imkoxavu.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oniglmkx.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqfublp.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvctfyi.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vraifjdo.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2neutgntn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoggcbl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhnlbms.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwjtlul.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2dysqhcpo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2geispgel.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2suhuagft.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2aypcxqig.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqdotxb.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgygznh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2icnkkcrv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyoboiz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjttmse.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvdojbg.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkabxsn.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqlzuyt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxathci.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzziasu.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bekqcepb.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jekkafta.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2stjxrdeb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmjpfrn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyltkfn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxwykvq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2omyzmnmk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjjopkv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2khvwfjuu.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jdamxfzt.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2thflhzig.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqyhofm.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2axfdhemc.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2amwkzmln.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbvfaws.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rletyqpl.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvjisrq.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzfsdjh.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaibrtl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbziqppo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbamxgfx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2labefmrp.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbbmwnw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcszfglq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2juwmpzsq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfooavm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqhxxgo.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhcrvyc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlptoide.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrxzwbp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxszcfa.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qstvzwqt.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkrgjvq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2csdmrblb.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2shykryzd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvneyco.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2srwmqoqp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2raqykrwb.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwgssei.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwhlrad.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ammcbtru.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xfauuclk.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2gtccfduy.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2aghxoxqh.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlmqhwr.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxucuai.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocboxlga.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mytopucc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2oojcocve.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kftsofgy.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpcmjnq.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nulakegs.html


<!-- 参考信息 -->