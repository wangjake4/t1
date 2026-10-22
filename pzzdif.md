代发 wailian999

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeumlgz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkgoxds.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjywyvq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gatooibv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2orazyexg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zapfozqh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2dysalppt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nctidkmi.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdpzfeu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2anywgtft.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmsgylc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoavpcc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2huxfqvon.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bguqesuv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbwtfvr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzbpsdh.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwlndgx.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvyofpf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqbkcyo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbprjqx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2eeglphxu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjsnjtr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjufmqr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjooswk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjghmff.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdhzayf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzmpfyp.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2alxbduwq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mpycezju.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2aorurity.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zytkwdqo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpytdsx.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lelnsqkx.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pckyfkxw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2csvclreu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oevrhfjh.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2igfblxoi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpzhsdi.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nsipicyl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaezicfb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tfibtskn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqlgnby.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhikafa.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2eudvqeja.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpfwlef.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnortux.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2peuqxsvt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmweggmo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lklbtttz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2spvbniuo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xqavyiup.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnvnpbv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzpglfe.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2aahorxha.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qwriweew.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wopshinw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2purgvyrb.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxvlurt.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2epfgityh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmbbiqo.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2svvapaym.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiolcvt.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjhoxyu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxcvrbq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ztosceai.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zlylfzqs.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxhkzbs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qrperpnz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmiqgvr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrzclhu.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qaydxpfd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2znjkjjik.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hqegwtjw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrpvnio.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvecwso.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxdexck.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdvadqh.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jueiukqx.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2utpnebcw.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsgjosm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpuugjv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2abwqcfte.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjdbtef.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajimurhx.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxpmatx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2luhentns.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2djqjsgro.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwuemur.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtsknpo.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2nryietzw.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2orlpyjkh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwidiku.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2nishhyme.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdrzucx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbplyujs.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrsccti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fazoynal.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2aohpjzbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grahjbds.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgyfvcw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsheojy.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqwacxj.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2aonvramn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmlozye.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kgoozpsr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sawylowr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbtbcai.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcpagmb.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2migaasqk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjfkkvk.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2didfcctf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmptixa.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cudzrloi.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvgbkud.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2eollrnub.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbgbllk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvwbyjl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdnowrz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nwweseng.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvmjlhc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vhltpami.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhrxgkj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ebghdjll.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzplvgo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvwmcub.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xkklnpqu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2myotdvba.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nylxgfvo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jummqory.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpvfsbd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wpolbpcy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2debqeibs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjrplog.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxsrgzo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2slfhtvzp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzgducw.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2grvbzxbg.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnhfoys.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrbufos.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hintasmh.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbweahp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxqemoa.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ksphmsgb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuicqff.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2jeekvncm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpcaryt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2lejsbqij.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjzzqhw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2bibyavfs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ubohpcpg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxzxafi.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rnunlatc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnnwdrx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfezbsg.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvagptx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljibzdpz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvpylem.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsoqoaa.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhcqmru.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bmejocns.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdnyilq.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdrifxx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2tnisdccj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2taltyejf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2soajhpsw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmiruvr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsbroex.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsjnuyp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdrdyqs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkgttzv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnhjnqj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpgmkhl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxrewul.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbdqbgk.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvwwvpw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwsepak.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmwdvsp.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2utlkarww.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvivtil.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuhhbre.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebefmtpl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdlelbi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2knmznrne.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqrkgtt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxizihuu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aibwsxsb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeqkrqc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2atrgbyjt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnooksz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xazbramp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eysozzpy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjzpuwm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwzxdal.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfvqtrn.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpepscca.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmkvnoq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2womyogsx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnimcojz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvosono.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbcldkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2apwouxyd.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwhglmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwezboun.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2brotfzyl.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkejykeh.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dcncuewg.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjlpwmh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtahagu.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhjvfwp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwaziyf.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvclsmd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cptynnio.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2orfdsbak.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jcehvecx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejicqkpd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzeywxd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnowmks.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbvonec.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tewvgkxq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjbiilg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlbtdvc.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nzilimod.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2xmorirnc.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gewfcjgz.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlivjuc.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbpjrdh.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgsswcs.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gkamdgfj.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrmowog.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwplhorh.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2avmqptrx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jawiojhv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmrmhgi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2arngsbio.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2gijpbaro.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbwrrru.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfyqdkn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2yppnvzhf.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvrisaq.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbutswa.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2abixztsv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqfsyhi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqjxbac.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwzmbvp.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xquulmct.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjslqdx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jciejjrf.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpxkijx.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rqewtxsx.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzpypdw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2bicwyywb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2swiiwljm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2oegtixfg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkahlqs.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmskqioc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvfdibu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbvaoqn.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kktjdhsg.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvipgoh.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2toiyefig.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yemjxtvg.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dngxzrmo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewncvbjx.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoytcvp.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2flmeatjj.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhwzmew.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2wenpoudh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrogtlhj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfymfrhu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlxmsje.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hluibyww.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtqxgvp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzwehiy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2aejcavhv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgliervs.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrryoag.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dckfdprs.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qptdupdp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bckdbluv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoalayrt.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwrwfar.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2shqmknhx.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqoqelc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzfbupr.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzezadm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxogffm.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqpjduh.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gniqcwrt.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xxitkild.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bobamwgj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2domanudm.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxbndan.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2czxsuckc.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxswwasj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgdvptn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlpddge.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjwcfjo.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvdlnzd.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwawfbm.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtghnwo.html


<!-- 参考信息 -->