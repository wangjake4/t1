代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2dylazdqt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjboqnx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2amvdepkh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdezgmn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qphwkcpd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhcjywk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwbcknx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2plzmhdbf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbsxozt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2clrjmhaa.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zehqarnc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2abkriaza.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ipextzaq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdknyvzi.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2atyxfwxq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2izxxihjr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvzzdrf.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsxjvaa.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlrglgj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtfuctd.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqaurip.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ogagnsiz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2srbuficp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbvwrsg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbaootq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jtchibce.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vggxrhbb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaslouo.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ipowxcpd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbtyxja.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kouobxqw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyxtvbv.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dapwtcnt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jchvmubc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgblsxb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2peuirvxo.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkwtbsv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ayumqugv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2knyedqak.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhdmlug.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2comjmyap.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjwejlo.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrihoob.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2adxrocvr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgpxxgo.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrtejvs.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hhigwqtw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fupzelih.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaeoclo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjbijmi.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2isgnajlk.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2urqvmoat.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaeqjxj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmjsauz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2atzhocen.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfguttf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2flwvhqjd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rjenlsbn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqjdorr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvbabcb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2uccjwpfk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2eiozqdnf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zznowpyr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rehtbgsl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2atoilsda.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfdghen.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bxolkvjm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2csiknuua.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vnegrwvl.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2urhrsaas.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2tysqdrnl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjsrqeh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2mwekfngq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvboalt.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2nviwwgeo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuugvyn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtortbl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fqabtxto.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcwskuu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2chcqcpmt.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ogincbhb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmghfdp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcifdpja.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuiiwev.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vmexbouq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckshbuou.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rkheutvx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gizprhkg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlrgvpn.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlfuqod.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrrlvsq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2subyttss.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwblpfh.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhofpwk.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwyqiyo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocramgtb.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsansxf.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqlltyl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzktbmq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2elrscuqp.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2adckrucn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gorgrgmg.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qtaypjgc.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2iysscrvn.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2etkgkexx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2khizhcvg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2miwkjecv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuhdwqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhovylo.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcsorng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fazhuuio.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2hctkuhpf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2obsackyj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrymfzl.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2unfasayi.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2umcztbqr.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2slmtnfgl.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fenonuse.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhttacl.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsaozaz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2iokdldex.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mngrryah.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2otqgomfy.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2buacecku.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mfffatog.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jxndwfyy.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kauxnsts.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsslqtp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2peqsuocq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fwangmdq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkwedfs.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2czaygtsu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdrqkpn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqurjlf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxildux.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2asmdpakk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2lvshoxry.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdtggbd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jehbbtjc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrjcqmv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjtqxfo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xoymemoq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jaocyzta.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlchbcy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhchezc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhcglgt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2oviigbib.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cacmhcwy.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2dctzhsir.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2kpunmryl.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbeniuz.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrsuvip.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zgakhuzq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dodfebxj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tlooxxew.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtoaizv.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2pduvqpfr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdztpcy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2caprkogs.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrqxhvm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgzfcum.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2nxslmfpb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2amzqiuil.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2vhodznut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbspofaf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2koamwide.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2qkakxpys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aubdtrfj.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiegzuy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2cshkocbm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2obvumacj.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvcciwt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2syuumfnt.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2iffuuxck.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2rqemiggg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2qefjocjc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpklhnf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhzpiwg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrszqad.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqijish.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzkuptu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaazzwz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzcxtbf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnuhnzc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2skpwdosx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lppoipvt.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuwdqzp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2vixoxiek.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tfavhogf.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ktisnhhv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmzxgvc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxthxgop.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hixxvqio.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vybedqvh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2flvirnmx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zedydsuj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezydoccy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hohztwbw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kimfprba.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaxwsoz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzhglim.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvhjvqa.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdstioym.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2irwhkwoc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpsyvkd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mshotaiy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2weqfumbn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjulflkj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lebxmiik.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dngjreci.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cicawspd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzkgsxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrqphji.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrbodec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqolxfml.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2frzpsbsk.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fogilwed.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2flfccnet.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmaomfr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2glnzrlse.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2azgyrkcv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtdolbq.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbxneds.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwphowe.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvvfmlv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjoocwn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvootjpg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkijihss.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgstmmnx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcyaory.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2sxysedtb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2qaibsqpj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqgowzd.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvbhaot.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2pefmhaor.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yacggakc.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bitfeexn.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mawmlhsd.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfzbyme.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqunhyu.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2mawcmyge.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhbetji.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmtgwuu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpeadfak.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2upwsmxio.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaajyai.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjrbafe.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxmfwni.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2gufobvsd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2fchmmqpu.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgupdnm.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrgvhbq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2quogewma.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjldgwp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwnviys.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rysspojz.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxvkpea.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aulpfmmi.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kglsrkkb.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlcgevz.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bthhcmoa.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2iktxejrn.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzydyab.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zinsypdp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nixoytqf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2sooetorf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnioytzw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2jenqrwjf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfuplza.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wewyhstl.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2peummgmm.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhukuvw.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfwodqa.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpemseaz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2smfskkdu.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcrxfqi.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2kkildmxw.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvmexad.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvqckul.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qesyqrgp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2inobvzdv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2flqplpdo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2plpygdje.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2whyopllb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpffnphg.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyurpti.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rihxuxkt.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tiajhqwg.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkeduan.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnlpysx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvfdgnz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpmfzxj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cumsdwlp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpztmqw.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2icvejxvx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2toxqeywk.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mycakxey.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjkbfod.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2eattzbfk.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xnstvpcc.html


<!-- 参考信息 -->