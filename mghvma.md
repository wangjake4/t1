代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwjgnxh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbovvpue.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ozverbko.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2eurjneaj.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2duukkgpq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2zryxownh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2shgqunsi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpidtyd.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbfgogy.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zrorbyhf.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2cuidkltn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qovifnbx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2aswenlwg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvaxpds.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bgugjrlo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyipmig.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xooqfdjn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2euerjxbt.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbajmbj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ndshhnfv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzyihjr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2kniujcax.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2bgugtbxh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsflmwxb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrdgmfg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2icymtndd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2refkaict.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrydfzd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtdadbe.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyppmjy.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrtpttq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2iinrezfe.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ulngmtmq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hputuujr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2akvraunv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbptzvxo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrlrifi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dorcjrpj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2llqxvqcu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2koghxflr.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2brbhyyle.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfusujd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vtterrim.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvorjck.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rpujuhfm.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jieibsbf.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppacwmtc.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeahfasn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhrwtdo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwxrmsr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzjqhjt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibendnpg.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hrujyecl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgbtsje.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiwhbrr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2icxtrtal.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hqltonvk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtddlyl.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhovhcg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrrjhfz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hknvjpjp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2tudbwkde.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdlhbso.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrgytwi.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2mafsyhmn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsnfhst.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxzywjj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkglhgk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2epnarrzo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjeisid.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiefpnb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2axfioglm.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcogujr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrqdwoy.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsadszts.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkeihrl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tppbnogq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tifngdsv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2izxehbjd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hozjiqhd.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjilwlu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2avleclis.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtoccne.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpanyvvp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyyvbvj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2clceojaz.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cqicmhey.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocldbnga.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzdhsia.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljucjqvv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtomoao.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoolkdu.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdvsqfm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2wusosjqf.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjrzcpd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2uiclmvkn.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2uprnlurt.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuqrzar.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2lulajnku.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2oonwmuup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cvviyozu.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ufowhota.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snzdgcot.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2prcsxmub.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xyazqkeh.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hfejqrig.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2afxexwbb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbdxiky.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qzspwhnd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiywcjl.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zzucenzf.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmiovkn.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmgsrhd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qretesog.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2naipwqlp.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqyislb.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2djrszxel.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhfvthx.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uclfyfwt.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mznozdsz.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2svcnjktw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qauzkdix.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmzecsu.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vipvatpe.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiflhbm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rphovhit.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ruosuqpf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwcjaky.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2eogkzrth.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxfgobh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gadbfjfw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2peydrymd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xhogdugi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bffxnkxs.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2syxtqhhu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlbimrb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uuopywjo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nuksfhaw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhofhfp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zisvcwqo.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2mobnlpjj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2sskixsvk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcfgchc.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2auanmudv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mibvvyng.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ldefwofp.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2crdwqfss.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2upspifiu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2asqqxqgk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jethhblw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2gknlkdez.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbbrkhx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2maykvpge.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2xpemeciw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrqhirm.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuyhkqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lswhmryv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkikukd.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgxxxjp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aweyepdj.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2zwoyhmoa.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrbsqla.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2mofaywkz.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rjofxqbg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2nhppfckd.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxsapvd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2zupxxogr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqklyzj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2knfpqsoo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2woilskrf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2svfggcim.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2xteyegos.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpqjbhc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2cwopxapf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2vkclvqee.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2wouxkvma.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzlycmr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2znduqrjf.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2tvinqwkr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnmuymr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkaoawq.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2acyxgjcd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2owkxqnmn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmutrqm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbblomzl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyprvltm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nccbdnhq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnpecpr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxozejnq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmymmxz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwjxdpu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvdxsqs.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnptrph.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eaktkqaa.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpautas.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2erjykvwh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlvmjyl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmkasld.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzuwerx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2acgkvmjb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjhvrvj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zoommale.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nidhmbnt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxyvvae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zozimrlb.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cisrulsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxwgcoy.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2stlbxycg.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2crclnczf.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzeiatl.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2buzmhlvg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnhrjfb.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuokzrj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2feiuarpy.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmjcqyh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbybawje.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2byyzslmo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fzingsdp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpoddpuu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ootzydim.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xydhgluf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxebqxcj.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ctumtnrx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvodsbp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmauchiw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iokgdsxm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2tcreemqc.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gogmsnjt.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhmkrbq.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqaftea.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgaemyn.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2tstgytru.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjetonu.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmijymel.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fazxlfrh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgcsovi.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbowgxt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnrvenr.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qpijcphd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdrqyxe.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2kldjvhgj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwzgmnw.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2thyuomyn.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrxjfqb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2roghtemu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvktvas.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeggvek.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcedyot.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmqvyuo.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wsutvfpu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lijknnyb.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kjavsxki.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cxecfifz.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzziygc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwjtyhp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2itbkjqbf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2onijcirb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmxrmlq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsenmqf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjqidqd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcxtnsq.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdehxvw.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuebryy.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2muarwfqj.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zywmhblr.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxrxalo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejckawir.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lttranrq.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2yyojymbj.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2atyygzip.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2hwotnktl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2akcpifyr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoxtnbm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rivljhyz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvelxbp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2byggmxdz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbgaedv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvmddnu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaptrxoy.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvkosqx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dittisce.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dduqqphp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrvzoek.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aklwlfwm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2txuabnlu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2cprcaiic.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2uerixkqx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkgsyey.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gllpsuzc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvmjgvc.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2gblfujrx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsruxdo.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tgiiqobb.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqclszh.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjahfnc.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2peditvho.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhagmsqf.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkccrpe.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjozdsn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyxuzkg.html


<!-- 参考信息 -->