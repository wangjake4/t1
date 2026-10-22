代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qktekbzg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpijaeub.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uypmtuvw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgxtvur.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpizxmt.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsjbqhk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2blphfcvd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxhsybr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbzmyxh.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkfuvyj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2knzomuhj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwtecuj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbatlal.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdecrbx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2waaxlhnn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2udsswmbs.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrbvyuc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ownlggzb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmjgheq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkompdo.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfoltft.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rnszoubx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjqxohj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2paxpvalx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2djasgkxa.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2urnqpmmq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2jortjceg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2wshgieit.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2bnipycti.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqdlifu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2knecahyp.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2japsgjig.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yygejzft.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgpnsxh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgeiezg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoubnse.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2quzoqrcm.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zigpxsgv.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxzjtbh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbklmkkw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzmvcun.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kermunlt.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxtzkgg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2clpvhiau.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yqclhzis.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2llrgrgel.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kukalezl.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbqasmo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wptkzfiq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkpocsi.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2auiaowos.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyscywwn.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2igyfkccs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jocjlsuh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyzcmax.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbripsp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbohghd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2umxyteqo.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2amaixwlh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeikzwn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2usewkraq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2epripjvq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsaalpa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2crzyscbm.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbnjgvg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2slfuwzvf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2aeexezdy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kigpcgjc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdqacru.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnjjfwy.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbcfrau.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rsybikhb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2junditzr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zayvfoyf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tnynoqvz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnvddql.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdqqnid.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jykqnyrq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2foppgjvd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zeevsfok.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjvzzon.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wigvlokl.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzujtdk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeweona.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcvaokt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pznwykzy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cbionvzt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaztdmls.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gfucksxm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhbezpm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlfzpev.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2piywzise.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oidodkwx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bretwypp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xrafgqom.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nkybvohk.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrhgvlv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmxtbre.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxgdpmr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ciblacaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kecwlcwp.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvsjarx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjnhwyo.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mplakbwk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2aoozttbr.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xfridzqm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhdwmfe.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzguxtu.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvbclxe.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxmxnqj.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsvelem.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqjaxlx.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcdsooy.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mddggvuj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdwaqev.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2pytxdoru.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2atrhgrle.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdzivic.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkhbxrx.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxnjtts.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgkjghh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjmdopk.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2teoxolrs.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2reblwawg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2imzalzsr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lkiyskdv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2myoohhpg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gpohjoqd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xaohunpb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2asjtzwxf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2asvceqfh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2piflixjt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2afngrgeu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbypayv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2phqslylf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwpoywz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxxhuhl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkxwkdy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2lnoxxkev.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vvparibi.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2dykkvqnt.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjzadcd.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhtstkt.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2muzospao.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jydvvkay.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxokrct.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bnarrtks.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkcxnho.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2xifcwcmw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeqhehh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjyyfxf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2onzzgvdn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2odhwrxrz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2dppbemog.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xaobabkb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2gcutjpvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpswizax.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfjetbr.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2yskucenn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qnniqkaa.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2meilmhdw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2vffxliki.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpwizve.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2orgfxvlr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmwcgry.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzaekvi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2tecjcbcf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtqkosg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpkkijq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcquayx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zaparapc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qsauedub.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2mexyjrah.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ndixxjkp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyriyuy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxmfhfz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvumdtr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xwixmvfn.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwyhrcb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2prtsqlhv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtslpeg.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgmlhvz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkxaucd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjlhxwq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkynnsq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvevona.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gejthlhe.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtizdakc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2msqbbwre.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuzfcib.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vabddadu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxmvsqo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aemsaekx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjaespv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wuciwxyz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsfnfru.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwxgxvr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2otvlrppf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yonodkfy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2toslidee.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvdvhzs.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbmzqrc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlusvio.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kctwtlin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqapiaya.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mxplmkyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcackseh.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqjtymk.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpdfvqm.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2klmtpkdo.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmfxzgt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuawpvm.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2favjrukk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2lblhecxk.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpknfwgf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2shgbnkkh.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2igbplann.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pavpzvlf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcndrkkq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgugijpp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rahkbaoo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgudyco.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrubejl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqevyoh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjyvqct.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mbosyhpu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2frlmseky.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iziuahwc.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2saqenjar.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dozczqke.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfjvjlx.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vvavktjn.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsiptge.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2isiezxco.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2webjwmwv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgkvnmr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2slzlywue.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mshypotl.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2txymgcmn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2etvpaokv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrwlegp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfyuacu.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqonzej.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2kxstplyr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsnvybt.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxqvzms.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvhcmoa.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bejywypq.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2daysmqgc.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pndcpwep.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2npuwcuko.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnaijzt.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ptutmowj.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeeerzm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgddptfq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikahovrg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rohubrnt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqiveyf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnotzmgs.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2elhmyajn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wflnbwag.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiyzuzo.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2buvmsepj.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrcrtth.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpomitvh.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjcvwja.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtwevin.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2myauwwsq.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgekjyk.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kewvgecl.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbjqqmv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvkyizz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbpmltk.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2atwowsxb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhfcmlr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zitlqran.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdcrmee.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnkjkvc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2btshjqvi.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdjbqpc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjowleal.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeqojaw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2afkcdqvd.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fopacreu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaxlzca.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvieaiy.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxuirsk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbosbuw.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2itgwqinf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2hagqocuo.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmitrzh.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaedptt.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2exxdmzrq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqgsvlb.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjwhvtl.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouniyjeu.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmcfajn.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzojmfk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2njdkvsvx.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gioeepht.html


<!-- 参考信息 -->