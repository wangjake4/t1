代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqnutjh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2urhltnaw.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yedrfxbc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qareowbj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yubbeprz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdaimls.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ppluvszp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzfxbwi.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdwivuh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbieiqsx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwmmdih.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2uprldsmm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlapqlk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uutwpaob.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ejspqszh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2sieubblv.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mangfkrt.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2kodwyhrt.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2txhoizaa.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wratfukq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqyoyjq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpgkvid.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xdeljran.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ydizjsks.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfzbjyb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbyckjv.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfhsxht.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2puwdehln.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2eieaduhn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hxypgnty.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpaehrt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nghbqvhf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyoyspp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2exuybpxl.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdtghlu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjzgbuf.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rylfjnrq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2btibjwmk.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2marylgue.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzchklns.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yckhbaej.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjtdteq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wyykjrso.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrfmmvl.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbbwnvj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rguaaefb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdkxhpl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjqxhuo.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2moubivix.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpcegli.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbxcfqk.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaesyfy.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvulara.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwgrstn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkxazbh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rombrexx.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwlcxvy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyezseu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqaljuh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwtqeeg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ugegzjlh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wsszhtkg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2plaiytap.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2dydczwyz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuhawsk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2cppgduqx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkkrsml.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjeotanh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2daipvhyg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jloccsqk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnzktll.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkzunmp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhssvns.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbjhmmg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jhurtvhn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2repfvlqr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyefdrv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmdtzyb.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzqggjt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaqzjwk.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pflnyphi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nusigsoc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrzdhtq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nepihwtr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjxvjar.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wphniess.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyvomrd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjinqijz.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hamkfeys.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmrqbur.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbgfylw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2banscomt.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gxioquhk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vaujksvt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnhdnws.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntigepdf.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxmshbb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pldnivgc.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjhjqim.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kbiskyfy.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2crucjfhm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2pnusyidk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xesiecnt.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiollxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcsvdgz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2nmanxbvp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oafpnuye.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2dywbevse.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qysqniaq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bosuugsm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvpfbdd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xezeuyst.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjjlbyd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2guvybwkl.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dotkguus.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2onsxdpxy.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bicnnedw.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nupmzsir.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgsjkih.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmexhsg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2syqxuxku.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2atiistpm.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qexyswcp.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dylpefow.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oytxfgin.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzecuzu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2opdkgrdv.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhlvsfx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2juwbvcem.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2trnsnwin.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlkdmjw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsyiekk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2pusuwwol.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2byerctxb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2swedlqvj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbvquyc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wxakzhyp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgjnooh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2syjkanvx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhvjtms.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2etiunrrt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kmugdzbw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2sohvzvol.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2opvgrxlq.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaimmbs.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfqlila.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcmsasj.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zljczvij.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeimaav.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2szshekam.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ffumfbkg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqtimuz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvbeffw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2idbzpceb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2demokgzo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2vzicvsej.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2oifvnoxp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqstudv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbkisxz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2llncjwbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kszpfkhg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruofcnxw.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2maoffyfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvqfsog.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2idfkbmlv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2aywemyzb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoblehx.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2aqygvpdb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2cyayilnv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qokhcdxg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmnliog.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zisffyok.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrnvgfw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2hswkxkvi.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwkbeow.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2vellitzb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2gudonuhm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2jybdsdwy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqtnzul.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwesrql.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwclwtt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wzemakos.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2scxivoou.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmnjewm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zapklakt.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2smxqfpwl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cstacqrw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qocodmhu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2erzogcdu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zykeoqkj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmvwiph.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lworakdl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpuobjx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyekhlu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uitmbeqi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvgggip.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcumgej.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzckwlnh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nptmjtkc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcenbaa.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbnehln.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2smkwnwjy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoawpnj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vheowpwj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2glrhgtra.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjqiuay.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgasjtfn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlolowvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvexvpr.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qkupbrqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yebfaims.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhbzmik.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2bornliyn.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjbcohq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2abglgxlb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyfjdtl.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2aacffjth.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpcgpll.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnapgog.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2stqevzaw.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ddogljvj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2axedhkcm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzprcpf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2izlxnvru.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaspybr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqlxpak.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlqulom.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhcbmwf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfceyjs.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oapnfqir.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpnbsvz.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtkjbsl.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaxzoua.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcrvyoo.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2atjlagny.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2dbodcuhk.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqjwzsq.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuzgopi.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hqupsdgp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzeuukh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zshbcbrx.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwkhgpb.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrrveba.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2zevylwgo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbblfsnb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2agiqxqkn.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyrlxlr.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2etuaylnb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxwgknc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxioudk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbazlmy.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2etzweizp.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fkffztiq.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ddolrpsv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2acaxhnzs.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mccdyfsv.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhfpteh.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsapygl.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzeflns.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbayazzv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaaqaid.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2txyujgle.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2objefdgl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdllhxo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrigvxr.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjbugct.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2azhlyuhk.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfltzymc.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvekubr.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrvchdl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkzzvfb.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxjzrwi.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqearpt.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkkmhrh.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmhnwsr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfewpzta.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtsycmr.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbmkwbg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlowuew.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuqqgef.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnkmjph.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2viqxntnw.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzellae.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2toghxdtn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoncrxk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2drmfnlle.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqzgtdm.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2srpugtma.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmalsmtf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2suvgswgr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2jlckdjch.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtyothu.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgezffgu.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2whajojus.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfflpigu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvbdjee.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jzefhjym.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ivomwuwv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgzqnrc.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoyuirl.html


<!-- 参考信息 -->