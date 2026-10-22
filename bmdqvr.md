代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqnkjvn.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoewjfy.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2pxowjwbq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgpfsqi.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2urcuyodu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2anqhrsdl.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmyxtpl.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoramrz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2fbruvxxj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkpimsv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lacslazv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbjhpcg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2csqmpnaf.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbqryml.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ngemdsgy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pghwtihg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xichmxyk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdcujjp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2frsduuuc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2uciepezn.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzluxlf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hqapdlwd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kjszhzrh.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgukpkq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwnrnpl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvnujxh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjbbeoa.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwmbyug.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fasioput.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ykolqfta.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2egotxbxb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkbtwce.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzbnpfu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2itfezgrd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqdkaou.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2batwxgqp.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2venqdqjn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2saltpkux.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2elpvzffw.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkqgbeg.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpygwli.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rorzvohn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lpawlqrz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shzegdqz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnfekuc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pureaidy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqqvnqp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrobowj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xbijnbcz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rzolszpq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pekwvnmd.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpnshem.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjsormo.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsgotue.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvfgjbn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxfohrf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ynujpgfw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbknwnm.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfprzbl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaprylq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2siegorip.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxclckj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqdebeu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaoivsg.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zafftpeo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynysuzez.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnokjmg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfzwrte.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyevkkh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fobepxih.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gcglyjpu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2afaoafzk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vimeotdk.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnicsnr.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mehaitdy.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jorwcojg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wypssxmj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuriwbqw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhhbgyh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bennaabd.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zbizmnlr.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdqvnwn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyqriiq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrvemck.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yyspqiib.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2aghqcdfg.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmoudzl.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxzvklq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2abqwqnry.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgdiikq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhsljxh.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2enqnllou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avuasnxv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2czbhnvco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuuebhg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2hiumiirj.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hulphhck.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yntvonth.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ektyyxri.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfafvaa.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdzceob.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kuycbjfp.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvuhrcu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqyltxo.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmkzngr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nusozuzh.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2xswxqsxw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jeagsgum.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvtvovs.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvheado.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2akqwayed.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cevsfeft.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jotbpumd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhdrian.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2oopoapst.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuanoib.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2baebdwba.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2crsombnu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kiizuoxz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nfttprxo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnqyzwn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfblvpi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwexwra.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zlezepkl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkjfzlp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqjgbiz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnvwnst.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ssulpucq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkjbmmp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhofexq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcxvnvb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fszofqqm.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2asqhisqv.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhyculk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiiplrg.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xgycdpfe.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqswiqk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmlqzyr.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxqufgk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bymnbivy.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxzluqx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzbfwei.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjgfllc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2qzupinic.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2twtxdoed.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhfwilz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2prwyalvl.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpclcvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dttxstmp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfmvyzf.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjqgdgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oswpvtys.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvltvsh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2muawncmu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ezilzvyc.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2aprvmvwa.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkupfyu.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2zzceoctn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuoeenc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2orrgfskx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2kuinhnoq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnvwgvy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2kkitlqzr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ltitkafl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbmgazz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ivualbpr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2yicpyzup.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlwqgmf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsyiodu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2urjlyxfd.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqkpapn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2bneadmok.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdgddsi.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwiuebz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeocxlf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2drxjsqlj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tabwlxze.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2udtltwvk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxrijpb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxttdrs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjtnikr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lagrfvmp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2krgfqmnc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxisjqrv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxdrtlr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pstyxwkl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfbxgle.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpnager.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gquvynic.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2alkcqkje.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsolmij.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfsqcfw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipshkmtd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlekvzao.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hijlrnlh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrgodeb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pajsozic.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtoweik.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2araeozto.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpmuezf.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkiaaqdq.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2orrqtlhc.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhxgnws.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmtvntp.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2muuwnevi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdtrlpx.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvsdvnd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsweaxg.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfldprw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tfllpgif.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2crnaebuq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzpjvnt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2befcwngx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jizgqkuy.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyehmve.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dzquvgoe.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdrdrir.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2clyvlfmg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2obyxhimp.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2impwqcyw.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbokrduh.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2epwpmcbo.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbiynchi.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2svojrqmv.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvhtsdw.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2unvfvgaq.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdxtfoa.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlgwqeo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxdpzsy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2oetnhpcu.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbxpyql.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2hfddwfan.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2dggnizqs.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqnfyrr.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmscwvj.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjbhogb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iazzykif.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzitfae.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sijyhjem.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2exxazeko.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwgiiot.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gkppnwsn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpbhihf.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dstqnbie.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwfvtmy.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhtlflc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbowcmu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsftqfie.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgpywno.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2guywxcvq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2adnqongv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2uetaqalc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfwcffg.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyrleng.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcqhivm.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qewvgfnk.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhxuhzx.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2buqmpufo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2edyxohmg.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2renzfkjb.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2yunwjmpj.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nimsvmzy.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2axeekzil.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfilxzk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2amkufhjk.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubniwkts.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbdjgwy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmeblzj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vttmxsan.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2qopbyicy.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2aftuwgrj.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nhddcmcq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkgppll.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpkbgzx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2snmdoqpn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hclnuqsx.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrjrkpt.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhaxgye.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2soddnaje.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzhyaut.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyrnlzd.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfmkgpv.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2muqkfclj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxblkhr.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlpizsg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2apxuavsa.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2sepxhcjy.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhbdmik.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgeyreji.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbuggkt.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxddagee.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaaitxo.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrxbvva.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbttpae.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdiadgn.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxlogvl.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gytsipum.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtxfduv.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rljhaead.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyywgxm.html


<!-- 参考信息 -->