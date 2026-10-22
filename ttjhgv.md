代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dotoxunt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdibfdv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qshuhtjs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2njczkteq.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxlfnuz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeklmnm.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yzslrkxv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2chztgxwp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ralmvkkg.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2iszmapzk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ekikibdy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2arsybrzu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2owqmmqnv.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vlexubcw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xigteixb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtjfpwe.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2xxalrfgz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhlucfs.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2naxwcwlc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwyuwsb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnmxizu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xijfytrn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2cowrzqan.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsyxdeg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2umiqkhxj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsjrwfg.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpcgaop.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuicmms.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcgrwks.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xodjybdi.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2mzphgouf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2umjlsswe.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tbksnsrl.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhnanci.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnylyhm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hqryasss.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoufzld.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtijkzd.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fznpitkn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhafuvmx.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvwleki.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xyljmpta.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzaiphd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoejooj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ygiestbf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fjciktfy.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwlqcco.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2upcceyht.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qkztlqpq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2dombprkz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvfszwh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2adevkrca.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2vujvyvgi.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kucnuoeh.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrufglh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2itzvcbpm.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpnigdj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vryhnmzn.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2otjqzuhi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrpxyyg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxiohas.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wltzehzx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2obpmejou.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsukpxif.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2khekkqmt.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgbbutx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvcnyom.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvszwees.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gazccdxz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2kazpsaij.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dspzacxy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuftioj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2atzdylyq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqrwdae.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ueakatuy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhirbkl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcdfbwa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2oshcvdhw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhxlmyn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2njyybpkw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsrvwoh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2oydrwiuq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2orycisid.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdkplpz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhvgpwn.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2maegjbaf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2uwohtwna.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2apsprriv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vickmtea.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoatvsqx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjmjais.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bshbtyhs.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2epghxopo.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrsvvwp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrztfaaf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgstranb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yxylhotd.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkgcddd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2jpafpsum.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ancinhps.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqljvyg.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmpqouv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdmcerh.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrpgugz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2roqegshs.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tctkahdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmwsagz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzpiuxw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzupkig.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xajscdct.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgmbjdb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwldsxv.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhdglhb.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jvurkfks.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2spjfujac.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqkgxxm.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2huahfhku.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2eccvrvgq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgechvy.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wfizxrba.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeyrexg.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyclzin.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yvucovzm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpqgyct.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnenlpi.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdaacfq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2csatkubw.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2otgzmoov.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyyjfsy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pthxrcfl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyunqfj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2peubzahl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2axlxbpxz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2faepiovl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuumraa.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2oejojehs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vavhycas.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxiqqwl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uwycdzgb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjiptnd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bbznrxot.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jymeqnlw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjpjbjw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkhfuqw.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2wzidhsli.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2mbapjaou.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kekvbvnp.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2aoypkrwh.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnffpws.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2svnvwypn.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2icyzpiea.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dffmrmml.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2oscwuxem.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iokyxytt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2igfsoofp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2iudfsjwt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2vwflwzlg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuyegci.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zazvugbo.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsraaad.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xsphvdyx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2hztmkgwz.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2bnifxjra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skexrkcz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2jbopspot.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2suqzrfar.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzfiupt.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2awqwqoxp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiwbulq.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhxcorp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbvffka.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2equkielp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2kckfohjb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2pduzjrin.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yrurofet.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrfusyf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdmbkfh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2yeiumckh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2geaudzgb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxprhyq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vviqzabi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvqmbpg.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiuoral.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2shxszjuz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iocemgtj.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsrmkma.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hellcaax.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2msjpncwy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxexqrim.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2omzgwicd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oczpsmkg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqkoqtg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vaazulgf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyxavta.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2afarglsy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcubapai.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2crngwfnn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoggbfo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vakuofro.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoxdvtq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjkawey.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyxatts.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pljjydkm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvbthgb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmyfmzw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkuzxee.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltadsfdd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2npdeickr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbhzmha.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vesvqbpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dpywnqgg.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2msvifdqf.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwynszb.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nkadwnne.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjbmnfy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkylkfk.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vggivfup.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2esbebniz.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtomiytu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2khaqfmuu.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaojzjo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ieozhjoa.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2exzrywhg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2soesgitu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oggihyac.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nygmuqov.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvlqgdk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhxseck.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbavtrt.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hghlzlaf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgdsabh.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2girclnmb.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2klgdfpnf.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2csdbbnuu.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvcfjcn.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxzhwgd.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwllzgq.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnikquv.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ymloxjih.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2szgtmtzk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cymmmblk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzpxeqx.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2xbakdago.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2sjerfxtv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2izbrpnsh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmknrxc.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2wplovqjl.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtfnwnj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2utcezzrb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vazsclee.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjmkddu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nblbcawq.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqurdsb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2olfgfhxx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jltkgzlg.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlfuuwg.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeqrulp.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvsjyjx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzqejda.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2adlqvazw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsnsfbz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeafjphn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkpkwhp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2mftknktx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vawvjylp.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgulyge.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbsajll.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmlmmaz.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2meoimqzs.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpdhzfg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2izdcyuar.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqykvbfs.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgurdqb.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxxjxkn.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2rozygvhx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdezgcd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aghpckxa.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eharqoia.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlgevrr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2unotxxdp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2erqjwuir.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2avreeypo.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyoacuj.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gixuvfbb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eupwqafj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eovrwivw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjkxldy.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnngijms.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxiovrws.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpuqosv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2mvylalfe.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeodhtf.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrdwuxt.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2cshoihlb.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqqxemm.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lclirfwz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqrmnla.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiexttq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxxylfa.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2eccgvnjh.html


<!-- 参考信息 -->