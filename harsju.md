代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzwossb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrpkolj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkxxtdp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfylqsnx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuxkwwk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kncexzis.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeiipwd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ilprghem.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgqdjuz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dczmedou.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2izpgtsky.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaipoli.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rnklqxmi.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2azfnywht.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bucfivhf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2phitzgeu.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2iplfuezc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqbeoek.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oxejrclx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tttkuuzj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdvegfa.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ttibtlyu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2fciwxeir.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2akmwiefe.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2czpdezxh.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyfeids.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pcboyvqy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vujvudyx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhxrghm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2yrysukue.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjpysdh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvpdrsa.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2anvhksnm.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2saevaecc.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dieantco.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2npvxfhpe.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wrclhqkx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2blgiesps.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjooioi.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwvzjne.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2trdmjtuq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2smrwnppg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoccefs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2puollcom.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yywkutgk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xyowimxa.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsidhsu.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsgqnqj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2foiblubt.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwcsesw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbqmqmb.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2snkdljid.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcqally.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oggmdilk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aperugzn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfkzckc.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrsrqbp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgbgapk.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuaqzwr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnxcifm.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2srhzlrkz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2knukhdhe.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmkrrjp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhrlpgz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdvxzvo.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xufpyoqr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhafnrn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2etuptnlf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2lseghpxs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmhdzpw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2iympercw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhfjlsh.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yxthvtrc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jeonrqjv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzszoye.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hnueizdf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqjxjqf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2louxzzxe.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfcelxb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjgtgac.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeybqmb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdugietn.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xpasvrzc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jznggmhd.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sftynans.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yznokhyg.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtttzge.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmiwejm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bhelwkhl.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpbdmkt.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uueqasif.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2orgstjuf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuirxia.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2accjhhpn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2jirsnefi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmccdldy.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2srujiipm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcmsumf.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2utgoviqo.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2dyagsdwa.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfnrliq.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgxmnng.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxjkzdy.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2htjsuhhq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocngcfvf.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvcxbkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdjlajc.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwjuytl.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfzahgg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gggfjrhe.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ixztijiu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qagsokys.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrndema.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2alizhozu.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhoqder.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gdutljcz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2edqfjfzi.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpzvbqt.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2notejqjm.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2kobbrupc.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cigqkuvf.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmyrbre.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmnsane.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2odqqxbot.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzvoiqp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjjpopq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgkhdsr.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hbowfmub.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2btvpicih.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2drxijjkf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2knxlbjsj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuaadhc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2stzrqmgk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpvojwc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsidisn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uvluabik.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2plhnhlgv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2inpybvrd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqticcf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2idkmczlt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dagiatzs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpmhczv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdisnyc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2giqzvieu.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjuodbm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2tqinyjgx.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdvecid.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bgigmskb.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqersjo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtdtnxv.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hfapvkdi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjeigyk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnxwxfr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fodasfnv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvhcecv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyiydte.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaapfhr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2eakuqlcl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2gzofzono.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2udhfxxva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvafqhy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnsrfzf.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwpdsvl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmzjjpd.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvcdeej.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2mjeswxwu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2oepzqjik.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlvaxfk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2owckpxma.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqydyii.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ynslgafo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2glsqical.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpbljtj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2fjseamkc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxywxvv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnjvnhc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2elkgqytt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2siugjzar.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrshlqv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxkfmag.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtbieah.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uirqfmtr.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2pztuljyw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmdhxji.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzenldv.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwnpntt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmfdlwb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdywvins.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uccnjlis.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bouztsta.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzanhemg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2avjtwlzj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jixezrzk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwmklkv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2naszidpv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yptevckc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpfposu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxgqytg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2acdbafxg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkersymj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhkxwpw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2blsyqsfu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiqadne.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2burhjthm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypefzrzt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2okmoccqu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbauxmss.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbigvocu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqomoybr.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xshjqqdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2faidslgx.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2surzgwnh.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpakonk.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kredeiie.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2affhipbd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2suwyrsfd.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tunytfcm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuruddz.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tynjukff.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfikyoc.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2fredgipi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yhonehbb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecekaogg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2winefjqj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2obcwbvsm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltourort.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2iiocuhhv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwcrsku.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoerloca.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vexrecig.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2phmauwop.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbaxshwd.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmutuxg.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxheqvp.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsyuami.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmfrdvy.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2etcpocog.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbmdfmp.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbvappa.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2afcvgxzu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtixozmp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2kavlvifm.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2spkyadzr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2muohnpbc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2yppvlfmc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdzxiyj.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhshrjs.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2iinjybcp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2owhtanrj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dijvvlzi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzmbxxv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2exisoosk.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2unkmqrjz.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnkiyoj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xnoxpwhd.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eohhebad.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mtparlce.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2esgqkbvt.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhjpbqx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hitbyeje.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvcbkly.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jamcsect.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2maandyzz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2onydxfdh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgnostu.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuiphxf.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nimqnkvl.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyztzmgz.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2boopqdfv.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmapxjuf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygawsnvz.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vitysbdu.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjczjgo.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdshlus.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2emkepswl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fusmpubd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlaosjh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yanqfaya.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxaymru.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrhijyo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbirumi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2wvadmzme.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vztmnbwy.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpcvdpn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rauqzrzw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqovump.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2idazflpx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqstfxfs.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbagltqj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxcnoea.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2rajedwje.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbqstku.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojazophw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtodjie.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbsdszp.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2snyhqvro.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiewews.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzrvzgy.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2sswxatjw.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2xahxzvdn.html


<!-- 参考信息 -->