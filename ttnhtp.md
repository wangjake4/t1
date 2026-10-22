代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfxozia.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2luuuknpy.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2micytcwz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2zotxckao.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2glwbendq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2raqovxpe.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmaqhjz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbwxgzk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uadhhbgn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwiybbr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2thumhelk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2yoledvip.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcdswnj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2oefnwlhe.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrnnawh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wysrrdlr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hvktcaad.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjosuqs.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbhvzyp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2swlgnvok.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qmarzcvm.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2uwunoglb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wesaomrx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqjbyde.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhuzlve.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2tofvrvis.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2osiyzxxv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kclfqscu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjhvmbu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nngmktde.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dkycydan.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbrwvth.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vszwsnwh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2itudrpmq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhuvxav.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2aznydovw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsukqhv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2kobmemkq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqaianp.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2efsqhiik.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgopozc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2faxtaben.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ehszsdnp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrfufgh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2maswzczt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhgyalm.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxbiqbs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtwcvcl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fulhnvph.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqbyqke.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zjowzwhp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2czsktdpu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2narblbkb.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdtqcfd.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lfamurrl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2pscbsdqa.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2libnbwwu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrphqju.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkospnk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsapnlt.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuqtgec.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nulwptlr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2guoakkfg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gziztgtn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dzokwski.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkewegve.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwstkset.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjmfpev.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2eesqklnd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2agakrrfl.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dorhygqk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvzolyg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2szjlxwdr.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wegjdhmt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxsgjra.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2iihghafq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhaeyqx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaglxxo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2helxnrys.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iutizwgi.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tnowboha.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdljxtej.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2klufyhrj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hltktsoc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbnaxtv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2iaykopgj.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2akmhoetb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpsqblj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdpfeml.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2riznbtbd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvaptiep.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bsahzapk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggamyhqv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzhetrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zywdfqya.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvwklyh.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxzhzle.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbzmddq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2blksqmhz.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cdirpppr.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfgwnem.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2owyddnai.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fayhvtyj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kktaccsb.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2popyzhbc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmghsby.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yatkkudf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeulglp.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2syzjbntb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fidtvvkk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdxycyx.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpkajvi.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpdetey.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vjngyyzu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjwrtss.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hjewtbml.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfvsqkv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeknoqq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2duutspbe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2giwnaqge.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qtofqebg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjjeole.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyqzxiz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ioethphz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fdngfwky.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jorbuvso.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jomadnlf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2omhyphyb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qaharueg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gfatehzz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2rreqftbh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yveupugd.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2kdefkqnp.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2qywfpgku.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxxsyhq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fttzxsjv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2olexzamb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mexuasnl.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2svdkslyp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rorusyoz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2lunowrrm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrfwdeq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2udqfbdwl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jurzwzwy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2vgskfzhn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvcmaaw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbzxlsd.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2kuehinxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfefmub.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxnwapm.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2tadzjosd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsysmnx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2kpenalbf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbxoauw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2vtggdrcm.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjpgeiq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2bjusjqsg.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkhbdzz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2aywdozwo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdueron.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrzshuw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2jretneaf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkkxcts.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzqgica.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wogbcmdz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2uigmultk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsmzlvd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhdrnaz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxxlhvw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uctfswal.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2hvugiwpl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmplbnu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2luggsztd.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgcjhyh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrnvdnj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzfhxlc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2odtxazev.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzwgrnh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsputaew.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdjovrx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2omyoeqdo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbcfiqo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqayqiiu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfllnhkt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2poptetnu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpmritj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ueghsecp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvuptzw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fyljdfqt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmyyumg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfppvrhf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsdlnpu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qabspeib.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmnfpaw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmaxywb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrziwls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmrycnz.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzbbxak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyqzjlk.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnwbklo.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2uekhapsd.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmipnph.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkxabto.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2veptivuu.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhlrxjf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtptihrs.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyywlckp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rukvvdtb.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrkmprb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnlcwhf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkieehsx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnnmbpp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyqfeuo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuajzfe.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rfruczor.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgvxsal.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnpapuq.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jedsymuu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ceotdaif.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vayozuhm.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ittenzwb.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwxidef.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgubeel.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzurxmy.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmxbdqe.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2scbtkxei.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zfshgoao.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2svpdyxqv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybybvuac.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjgalqd.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2xovbxeyz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdfjbwd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbcimhb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrtyjql.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhsvpjv.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2qusjeowd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qcogatnf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjtgkgs.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yaelfbfq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ezztkufh.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2biypymyl.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvkhqhl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2usnhlhpf.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrnmvjg.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxmvdiu.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnowbele.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qspugjoe.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxvzbjw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmokmedm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgozahta.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlntmik.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ttswstra.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpumhpy.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhpbycn.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqiwdww.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjvgfjb.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbptcrvy.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iujgnxua.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuuukpx.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqvwenw.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpqidtj.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkqxpsx.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2otgqzfmg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2biskrlat.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeygykh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtbdogo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbolpxea.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzotzmmj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjiugsp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2norldbvd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuxlivv.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2awhcyick.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyflsli.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wualdidh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2awadjtaj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ledflapz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2metvmjzm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnutshv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwxihdd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxrrhkx.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zptmbxyp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdnhijc.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2rclcwtmf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkkegow.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwupbsr.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxxzzoc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpqwtju.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2sexahtdv.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxnpkpo.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjweytn.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfvnyci.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouezmuum.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnswavq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2plmxstzj.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxyhnrf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gayzrpmp.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfrxxvb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmeovfcb.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rezjbmuc.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbssdzjs.html


<!-- 参考信息 -->