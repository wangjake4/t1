代发 wailian999

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zouxmcty.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqgmjkj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqhgqcb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjnswel.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2lilztanl.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2codsizum.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbwcaxs.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrwntca.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fthjcvhd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmvogxt.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpbosek.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlmpkad.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvosnqa.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2izgdgwxy.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfhcpim.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2xfntvbwh.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rorwwkcx.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mphxfoxz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzwabhr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wehozyyc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2fumzxuts.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2chmwjacj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2usstjzyg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2esknacao.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnxvazp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2vxktyulf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ampfygda.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vxivlegz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dalyxtql.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmfkorp.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuezdtt.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrefibsj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2klscnlgt.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqmqmow.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2skjvgwbw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2slxrbwxh.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ocewoxrx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2sqinatpg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgombtw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhefpeh.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2icfkfsdq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2sisuzusf.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbaovoxc.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmunpxqx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfiqpfn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmwjmrj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2janqwyap.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzuucpi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjwaskl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsrpaez.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2znyqknqa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwhevgf.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lrepwmqq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgjuieq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nerulnti.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjqtoju.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrlhewx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgdhufy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2aeslvxgf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjagyadn.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2bffymxva.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnnzbzu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2olqvbwzj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdwaghk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2frdrwpny.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2utjnfbgi.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2komrtaes.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxtxlkq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2enhuvcvw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ectpfcdq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwimysgc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpxtyrp.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzlwzfi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hexyexex.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xszrqkdn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvgcufa.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkdutln.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vywymtcf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxhomir.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbumgisu.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwvbgdp.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrzfuny.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2txtofczb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hocntwmj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqxolje.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2crycmfag.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvdyafk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecabxhez.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhsvvre.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hznznpgz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2akhfiorg.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxazleu.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2esowdxqu.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2iiilscge.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2jujqdalq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmqamie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxajfudd.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2opuptcpa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ascjubil.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfbvxoj.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wiulwcph.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cmaflpef.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2juvmpezk.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eipdfxfy.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ephwqmwo.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yglitnvp.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2afnlheoy.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nazimnrh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqodduo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cympkpuo.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2payesmdn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrrjssi.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pgktgyqd.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbqdemo.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfsbgrp.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dljkfnsk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jysbaidh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bkiyoiny.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2reokdftm.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjwavky.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gatcyvwi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fepgdwmx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2znqkcwiy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ojiqmtzc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkgtihd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmnpkub.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsjqvyy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuqgdex.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2znfuatgt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2klxyritv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ohezfuwf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmbysrx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qethgerb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2knspwxkj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzbdkpt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfwcgzf.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkunzsd.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ylemwfjv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2leuaqqjp.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2npcwvfru.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2pcidhony.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ipojjvke.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wuumtgfy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2szkxmgte.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkcvspf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbvbaeo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjecrqq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhdokdu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2naxfibtl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2pefjzkmz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2icieyprn.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsvzhee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azkdjoer.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsstnbhg.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtttwni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzublmhr.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2umycusxd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2mqejezev.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhrjhaq.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yznorykq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjrywwv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2iuywlpxt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvbdkpu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2icknxeip.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2cgptazwc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2jtodkcho.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rliawpny.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpchnbs.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzsiyjm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfvejiv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2befgnpyf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2wevwuhii.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nizxsgmd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2csbgmwyg.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2gdepqgmg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2awhxshtg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyvdukx.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrrgbta.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vskvuloq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iidmtjeh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmxevnn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvwsgao.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mevogtjk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2blprgjrw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sixzmiit.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbsgauo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2knczpjzb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqqrzwd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbzztwe.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsblfjr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hemdstex.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxuwywh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2krrsweym.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfitkcld.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2expnclkj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqptozx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvecjok.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdpzkrv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2iuusftsn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqntgffe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pasupdra.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpjolqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otcfgrdz.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2noxcovna.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvpbneh.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2umvtityd.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2czprnbgb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2szuofowm.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzvzwqv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnncaenk.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgbqhvu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cytrwovz.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2bintwzwm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnfrsqt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2heormyzg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2casdhdqz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyojjnr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfmrfju.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkddhlt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dusgbdlq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbercul.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjnipmb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2yothnvlm.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mollsoql.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdalkwg.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqyrmmp.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmnwxnv.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2itbhncop.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqwpcnn.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eexuctzx.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jxojnrgc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyijbyfa.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzffbeir.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfhbizy.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2roftmhyg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdedtqv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpdrxfg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjxsigb.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2wepjntlg.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbagruh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpfeenu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuyhbmn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2byattvxc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2imfbtuna.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbqtwoo.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrplkie.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2txweittq.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nsetqgal.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmnhfzt.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmzstdv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbcmrqy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyowxbs.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2olflvhcc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfutnth.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhcebjt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcwsgdr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2twelhbjr.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nlutwbbk.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgkpuwr.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzdcgbr.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pezyfleq.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2eetjqvrm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuxnuov.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtzubzp.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2kthekueo.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nivdcwuc.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2lunhjehf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hojtzijy.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yevltcop.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vreiydqp.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbrmplq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjpwyty.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xesalpwt.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgnytnu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2umzozpis.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2feoljver.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxvtviz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyanrlvp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oltptbcv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiocjat.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sijojrom.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2axrtarnu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnwxnqx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyezskto.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbarqsp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhettxl.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmwyrjs.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gfamajim.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmuxkcx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnhgkxz.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2shqrytpb.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqujkifp.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkvmsqg.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbrqdzk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqzuajo.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwwywih.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcpfvwq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2musblyhw.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyhwnvg.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rkusqssx.html


<!-- 参考信息 -->