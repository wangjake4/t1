代发 wailian999

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjjwinm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2aecwgnpd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmnjcdq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2yipoaaxs.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2kimkjqai.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xubdxfvw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrvzegg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwitgtn.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2smnirfwg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2prptvcgz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkokvqw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhxtery.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbeoopv.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2djiolkhp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpeiene.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfumhtd.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2klcctkin.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjageco.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfjlnck.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvlface.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jcusndon.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrofmvx.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2jntehrrk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbonjco.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ejibepai.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2axocoifo.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nywenkru.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ionkgdgj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdenryj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yurgghdz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwzvwtf.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjrcgcy.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lemhvpil.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hgukypos.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfdohnf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgosbvla.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnyzdvp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ncptayfl.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zkegujmh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhcxhpk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2scrmvzgh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2bihixmuf.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgxeuso.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyigfmx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2pcapowak.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lahpmewp.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fywurokw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzwrynz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mpssxhgg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ccavzczu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzsyixx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nxctbdwx.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsvhhug.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mubwiobg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2olhciqyo.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfojusv.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcmigwx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtjiuzl.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wihmulgi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mdklunkl.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2dlalyulk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjfiihy.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zhievogs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tlafazzr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2sngiqdha.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jzopupoq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ycclxkub.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2emmbqtwl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkbszhv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kapmiyht.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2emtpinlx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2dowregrf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xliywqug.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2byrdcyej.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2fupmskrp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ieogmybc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2swtupiie.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zifuuxmi.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmzxvam.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvlprsw.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rppjsgih.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ermhadrw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2klskpeuq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wolngiqc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vlchinxm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uoenvbrp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2smdvldaz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtijciu.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2otytetue.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2trloqsmq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwodgor.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ehajcqir.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2guqjrpct.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2wgovlybr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmneiwfv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjjcdgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dksquwsx.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2omlpxftp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyvimmn.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2tfloevqv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhcltvz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jozpyurp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vbruhdtq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2shhwigup.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vffnrxvz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdnqmrv.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2khdgdbpf.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zztizsqm.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gikkjwbv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwithkl.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfjkvyc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jklhvxwd.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2plzbkjot.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpkfsfb.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gdghbdsq.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvlnitj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oepfbaux.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkntfme.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lguyvnnd.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2defgflbz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2aeffbqdb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kwittpzd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wzigkmrm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdvlcax.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvcjkdm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpwxnoj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wshsbyyi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiibupm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oyukxlil.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lagbhaor.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2luwhqhzz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhzzxeq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrngdiz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjcyieo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2eowhbisf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2okjosniz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2moxkwggj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrwmntz.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhivhul.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2erppnbmu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2plvkuqvw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hnptbjdf.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyjrwbo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2esodixwx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwljehc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmlxpbj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2upvcslab.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2lupzkegp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmpnvic.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2kcltqhic.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwdwvfo.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ckipzhzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prvhnpdb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2kemyivoi.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrmancb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsmtqak.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqhjcon.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2gzslhmcd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xaenymyn.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfdkode.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbbqgvd.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzsbraz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2asjeriot.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2rogpjmqy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnqjywn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbefgdg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qdufezne.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhshsfy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzmkikk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdfcjpv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2msdxyojh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2qwiunrjw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoxlvsx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgunpsd.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxgglal.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvqdeed.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wyicssxk.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2dsooziyv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmhgdda.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsmcdjm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2scjmdven.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2komdmfit.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xaizqeka.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfshohb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzgdtqc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kudgwaoa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2epsbjzwu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2moqyqdhw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2juuohjnt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzfphpg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwikebgd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqnlari.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jriqatnr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyrewdl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvynlewb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnxilud.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwpptos.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbydvqy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnadbaf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bknfhuvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbebzcae.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlhxfnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtcccjx.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vlopapiv.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbqipwj.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mchydypm.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzhlqps.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuhzyuh.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuczies.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2envufmpp.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkceyiws.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhycile.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsgvwkw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bejwopou.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgibwvt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2algmttbx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hifwyrxi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxdrobx.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2vitenqkr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2igxujmzy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrixussw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2imdegcwu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2zxolwrdh.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgcbasn.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2scyicrla.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkukkjci.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rewfjmto.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hslkhxpx.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2mftjgdza.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xehohput.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mausawxf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxtmddl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyzwxxq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmrpnas.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2epzatwne.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2dhousgbi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2djzooggn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2qorlmnfo.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvadvrj.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2nsksulqu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gjszcufe.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpzdbfc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlxfilg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxjrjfd.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcyslfm.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtngxfp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nsppwhkh.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvfndgw.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dydllkzb.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dztnlzid.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyizicv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbofbcby.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhodafh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaliupr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozufmval.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2kdndmgmt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzqwkvc.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rglpprrz.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2imgodjqu.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvmunas.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqagmrb.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyynzqx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpqkyne.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqutrkd.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2xutfrffb.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnacvqa.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdfnvqo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaditrvf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpqhkcx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcnqivd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nomlqymt.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofewuqde.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcfbkbf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqheemm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eghujgeb.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2goodutrf.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgvnphv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rofsfrdw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvewouea.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeempek.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbljhhyh.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2czdzhsul.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqnxcde.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbcnzwa.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2brkxxcsj.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2deyipfkp.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgudnlj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tivxwxqj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2koocdytn.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sjllrjvw.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2vcilozro.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlidwazd.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2robahqyn.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsnivuc.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2avcgghkv.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmbpbik.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpvumvc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ungqodfu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmyjzmu.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqultqk.html


<!-- 参考信息 -->