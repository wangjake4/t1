代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzxuovg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnetceu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zptuctzk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhvirgd.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjcrfon.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2uergyypw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuaoqah.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2riszjupp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfnjvmi.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvnbivh.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jrekqjmw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jslmldoj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nvttihcd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pftjcgjq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2bopvkjlw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2utpnhqnb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfncvhw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkkxkpm.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkfjmgd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2iefbzfou.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rorsjlou.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2weyzwups.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pnljpxxa.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2flzrxiar.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zmajuxpu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvknddf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zysgjadr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sumugjca.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeomhus.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2phfqjhfe.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xarcefvz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzyeabx.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pktddocy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qlenoiza.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2latcpnek.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqblvikd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxuuxyi.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xntweifx.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqqtyfw.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbclpzfz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcsnluh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2urwbjoyg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vctlvjor.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wicwkzdo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrdfxex.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sypxkbkw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2snxsrrtl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtfnrvf.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgsqxfu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ettkfbci.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mhozlzpg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkxgkyk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cfefubgl.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhgxfzo.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjgxbhh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ifresbnu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfptqan.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxcpzkd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2aknmnoos.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iryyacvr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqncghj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yryssbqg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyregku.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2oaldbwim.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwmjnln.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfwztrp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkrmqhr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2yiiggsqy.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sxztqcpp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeqtdwa.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nekorvzw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2unuyeptw.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wicvkvka.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfrivqt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxcuoep.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bakokzgr.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbyhhfa.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2riscdtsu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gvusikxj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqceadwi.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxzxahb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uabvvhlq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyoyvzd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzwnbrb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2svmbskfx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnolawr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lixwczzr.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2autxbtmt.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuomear.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcdxrct.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mefjhuzq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwxaipl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tirfwkjh.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuzpsut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2spslqrzv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqphggl.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwxcyhm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tilsbpel.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwtivgc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2upvmiido.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2arqpidru.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rkijqupk.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxpwwnf.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtazxap.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcroobz.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2spybsham.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ktejhlaj.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2plglgvnt.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtontdi.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2odcbroka.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcnyypm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqttqmp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uuysehtf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ouevawwn.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2btziuela.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gsstpvcp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2afohrnzd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fgevsjjx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2keatfnnu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zcptoack.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyodxfx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zqukrcpb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoxjwms.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2laqjuwzt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwjxgrg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqrylwc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2muuwohxf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mdghvjfk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2handuvar.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xithwzhs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2obqpaltl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xorgqbrb.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrqtsrk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxjsuay.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dguwfcsx.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tcekuktk.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxqvnky.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkbmugk.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jcapnyba.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdrvfrz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwvtcxu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbfpjbk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2mxipmwup.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjrfmjd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xeohrjkp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwjljsl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zblohsqu.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2adhaprhl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2guebwykl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2atqlazcc.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2neutnsts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdfvnda.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2waunlqrg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2nbanrcwq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2wclwrwzx.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2znajbdmu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2mcviwfvz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzszawp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2knqljvse.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2uyadoxbi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2vnholllt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2myotrxpg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hitucsqu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2defmjrxw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxervgo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ghysafhi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtftlbb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2eamkjslu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmdcgmf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bredxayv.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2sciewuao.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsedoek.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yicezezg.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjsomda.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2odkuleqq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvazefyu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2plahanlu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuzoekw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2muohimyd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxvtgkz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwbozsk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iuppjrkm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuuplic.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbaezsh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwamvkey.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsnpzyg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkyuewv.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsaohfd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2swuihmum.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2viubskuq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpeniqt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuwsyaj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuulsme.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxoatqt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2embirsqq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzibbsh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqnevrr.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxdxunk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnwqjnc.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbnqcgx.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmygzkeo.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sycvpnlh.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpowcwv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhfbeeq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqqtqia.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwqzfnk.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsuydag.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2eacqkjvv.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2wywnpqha.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwiphsj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxodsmex.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnditzc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmewrps.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojywiycm.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyswymk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rutqgibi.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxmqlsh.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2juyivrba.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2oghdrroz.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxljkpfi.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzakcpf.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zayavejr.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2urykhbja.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2djqoceoz.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjacnzp.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zizzcobk.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ycevsvnp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iphaxycr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nggyvzhq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ovliakuw.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyxlvat.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2edcjmeni.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiumnmn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtwdoir.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlshmqk.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaepopx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uykzmpbf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dccnkvlw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ldttqpew.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2swhilmwt.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdcrtbi.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qstlpkid.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcbgvaa.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wecclyul.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlhspqs.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmpcvzz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcllrvgh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsintiou.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdyrkqb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmolfgck.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvtxaag.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2cfttryni.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooecsgsn.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lrocqwec.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhmljra.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmukusp.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2krcojofn.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwhnxbg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2trdfvnjj.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfobmfy.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtbvdsg.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2utjcvrit.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsgcirc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtbbdto.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjmyoll.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzkszfi.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrbluza.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfotesq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvrhldr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzkxspp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlqoecm.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vvieuzpq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecknblng.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkorwque.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlszbcz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2szhdgqll.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jytpnxvm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2kegptvgn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2nppmkvfs.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwtjapp.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpfvhau.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhqvfme.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2qooofxtd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rhaioccb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2boasjpsl.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbifvbl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcgcfva.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2suysmerm.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2itdhiwzh.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbrxtrg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2auiwtcrv.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcjaclc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2oloypctd.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2umjifnsq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyoshji.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtmnmal.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2toxekhjr.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wewfabex.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2znevqeit.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpnnbpp.html


<!-- 参考信息 -->