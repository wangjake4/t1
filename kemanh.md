代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2caresafw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrydbbbr.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrtchcr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdyrwlz.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2snnjgnyh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zagtbnza.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lkekikdh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2geyzyqqh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jdofyobh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssygcemw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxpzjzc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjwxaza.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tlboytgx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2whcryevh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bymacgwg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rovaxlhg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyhzquk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdmalnl.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2erwuntel.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkiugwp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xckrbrkn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ameasykn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqldoni.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2oosjbzqb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2epemmpwq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfjerhz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2avieocmg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqsykqe.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jutgunvj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2uffajbav.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2idznswis.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2eahhzhct.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2yayoxevo.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqfihwg.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoqlhle.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wavvzgjg.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2plkilafc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjnkoef.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dsokpjkv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooeylpfb.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdnjtdg.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrwqhkp.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvsabmd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgufrklt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyidfpa.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwfzwum.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvntxni.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2eukpizxo.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtxfyub.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfqjvfo.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mexcrahx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2eevknqrx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2eqiqucjb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqfwgsb.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvplwkh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaviwivl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2fztiwnql.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2symcdxdu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gursccqk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gquiepcl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wvynnviy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2plhttcmb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsebtpp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqatayvp.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2adqanhne.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrxwqcc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fwokgjpd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2tavefoec.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ilimrgrm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkulbkxh.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2axcgoeba.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfzfiir.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwakdyi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpahyig.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cseffyrl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdnosjn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qzthttkh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qggbsrpc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxepzvtd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2shxbtzdq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oyicjoie.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnuyhjl.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vprcgklb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2repslkvo.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpvamwx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhxmcbi.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2txpeipij.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2eisrjjjj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2abfevofl.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2akbfsphw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvbuyhp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkluopfp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ftogmsyc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbkneja.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxdnbqo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjehbcfa.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxqvlgc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwpusiv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjhzrvx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbitgus.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbmpfgi.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tihzkkmf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2jaykujek.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbjkybe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sikoorvb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkrgoyx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krsoslvj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2laduqhdt.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2eersjard.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xryffopg.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgkvvoo.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oxixbrci.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzruwco.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2chjlulik.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkzerhd.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqzejke.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvqdhpw.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdrsmxj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2hsspynio.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2terfucer.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnnyerb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxhyhwm.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkevadn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnkmtcq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwaxmvh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mmystzuu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjmhcmd.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fquiqxha.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzmzftt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfpyqru.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvhzlba.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xllmalxu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjusjue.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcsxcyp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrplowi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrjkvho.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rhovxtpn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2tyirqtvn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2irxjpuux.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gbksbeal.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hggswodf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfbkuna.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxmvsxx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2juwbsyzx.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhhrtry.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjyavpf.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bejgwxlo.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vljayjsz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ekovxdus.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ygikampz.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mbunfcef.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiqzbgk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2oegyjoit.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vwthdvrq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlgqzmb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2gepfwovp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2txpqchxg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2dyduddqv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhkwoik.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgxxvzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsxuwix.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpfqsnp.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2pkowhahy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azeosovh.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2hteocdrl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnvffac.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2pomedouu.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2giagefpw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tvttokcq.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2llaygvcd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpsxyvd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkmvgqs.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvrcpuz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2yndsmxbv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qtovwuug.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qawsrxqr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzxdxrs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdvuhjm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2gqammpqb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjroprg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2hpchwrvs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhzrael.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvbiezl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnpwavf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bodcznbh.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqgrlwz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbkenab.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcgswsr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpblcbno.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyklqnb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uliztdgm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kifuqhur.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2auvwztru.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqeyvyck.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2obtpssds.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdguyga.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2myydvmft.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgqaoqk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnnijnx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwujcawd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuajehsq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkycdbqt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkwzmwm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwthwxh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rovhpqpu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzzwgoa.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cedynjeh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzicbpm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snnowojj.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgmrxqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvclsqit.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dddtgmay.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlozysyp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsalcjv.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qljsiuye.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxstfsoi.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwznagse.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwsemxg.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmlrkxy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyegvbw.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ottqujrt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2iliyryoa.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqzrcrh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbckslme.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmkunay.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdidkbkz.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2kzckhjwi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmxbzdt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwbtlzk.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zpshvkfy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfjjwxu.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2amlmmiho.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hitwcdlt.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2utyimsvv.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oubrawix.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xdudqucw.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvwkodl.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvitxsx.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yczoyfzu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwkloja.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lquzwdhz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2hdylaxno.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2typmsukx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxoxihd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2dueilphn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhkcttu.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2erbsmsmc.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2doobauek.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdohblx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnauhop.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqffcgy.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nshjmaez.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqbivpd.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiqewyq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpynudl.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvpmxhr.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdqlqko.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqifqjvt.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2uevugfwq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nttlrzol.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuneesvb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfrkgqu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnongdk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlbzhnx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbglzsii.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqoxczt.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xctxfoof.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2onhkbgza.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rydvapxz.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fphhhxxs.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtthtkqm.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfmohnr.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2nrceciwn.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oofrgmcx.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcubbvv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzowafab.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2myliqlqy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiztxxrj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkjegpy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkbmhag.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhkwgfz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuuycwf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwclibbu.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgdwghn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbqrfoy.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpqlrzj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zetxtbdz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoiiorq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvlnrqo.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtdguhk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2dibfxuef.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2heujpiba.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfkqeyb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdvnmvr.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2frkrrwau.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yelnmcje.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2akkwkabx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrwuldq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2tabkhddh.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxtgfmn.html


<!-- 参考信息 -->