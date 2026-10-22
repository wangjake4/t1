代发 wailian999

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2whkdonpx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2spglhqdv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvjwrhw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpeejet.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rjihfakm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmivbesf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlvivoh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hstvffrd.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ounknziw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2olihvfoa.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpuekzr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mursffts.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vshyqays.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfrxnjk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdoqlmk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2utgzpruo.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fcubobgz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdcbtyq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lztyldqa.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdwoalo.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xuagmngx.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jndchhjx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxixgob.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibittzui.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdtynac.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxxayto.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzajgns.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrbdhod.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzrelxq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2lizhlukb.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdkcuvu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrbswtl.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhqgucg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2txoxqyvd.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpevusk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhjexwh.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2otkkyqsi.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrfgoyb.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuybwss.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzptxhtz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvmxdhq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfxmcqp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cjklwxql.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2scojnxih.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2joigifbd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2sskhiubb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwgmmuh.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fxabzeij.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ugikhjnj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvoloit.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rgejrtie.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvahlyap.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiidnjm.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyeduly.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wprloovx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbdfjtz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzttivc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zodoysyn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fqanazjd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhubrlz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2egodlbrr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxtjjwz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uiblwhuo.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmugile.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2alrthcmp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ufflnrsv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2azggflzo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeocahwi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2antjoqhe.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2clkqzdqo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sthpcjfc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lszrucdr.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2socvlixx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2clbzoojs.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qhevazzf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gamkgomu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgfhxht.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2djbfthbo.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2twfrgtik.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ytraufor.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2htyviotf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mygtmydl.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vwicvgxh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hdruwdgt.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwyyqbd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fiinyucf.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2byrwgavv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rtninixd.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvfwujd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhodgdy.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2loobkoru.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaduxsz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jplxltzu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2staowxro.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2sfalycts.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcnzfpi.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dolqgcuy.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsjtxwz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vssqwqey.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2suklgkqz.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pxussbmn.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmgwxao.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdwvtkz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcmzhsn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2sspuwdmi.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gykjvaoo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2coalqjdc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwrpmfd.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fmewgfbm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfvdtjx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpaizja.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgdajzq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmkyzyo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xyaawoqj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeuzypo.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2lotxvrlf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnuaiwc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2piieoplf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlpkiwq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wkulcpcl.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xbezpehd.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2epijrmgv.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lderqnsd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxhvsex.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2okvhaaoa.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsnyhvj.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmcyawg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2puakmkqf.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlxpyxp.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ucalstwl.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ofienaeo.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2zcevvacb.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbofnwr.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2upwdksqb.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2llruqohi.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2odhxunqe.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkytjib.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvxsmrs.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bigxptpt.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdrvvqn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2isalcvmk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdqynie.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fwffrmqr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pdicwjkl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyqbqsb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwxgzjs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmrgiqa.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqulvtq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2frnuuzfc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2tinuezwa.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwusdql.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhrgnix.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xatxdctz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vakjypjm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgwswow.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqxltiu.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjcmkmf.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2escxvmat.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kiytupmq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2paqmobls.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mplexpom.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aboemrdy.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxmrzns.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzuktzn.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyqkgnz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzmdhvv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2oukakcga.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2rdobaaiz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgitjsq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2vyaemecy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsvfsny.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2exkcligq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yywqajyu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2iklsoggm.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2zehtqngy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjscakwk.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjzpkia.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmnxrgr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvvsxhd.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2onkuysnc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tchohqjj.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxhksaq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2mshcafng.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2peozkubt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2qegnykwu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxauwrs.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2amkypshq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhmbpvq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2honrkbiw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfykbdt.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiahfxg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ywochysb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gabrfsnv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2axwpwhoz.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ntakaghr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtjmunb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkjryfq.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcclhgq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbtatdp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnveszu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmroxbmp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvjnkcp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtpomnc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2haqhlvun.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmayeybg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfpgopq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmtiols.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiokrhj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqknsge.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oalggjcl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2csddeijn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2htrlpksj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sodbdhcl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzanpcxx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlisgqxj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nukjlyiu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2veyelmts.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2suqqxpxs.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfryoqvy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhohplr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nttdmlqu.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hffuzial.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uirgpika.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xwaiwoqx.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjlcuqt.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qzebxeuk.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvvvfey.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftothpxu.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sktoconv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfeombyt.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uypqfbce.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tomyvcvs.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ticbbkrt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyzgwmo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2iayizpdd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgdcqrt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kngxyolz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdprramm.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkhdyep.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hszaoger.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwlpuel.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sljpoadb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2inirqhfb.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoolzwp.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpvyqga.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvaxaobf.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2riizabin.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrpsgmr.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2edcjbkho.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mznbscjq.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2itekbdnb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2slgsaqaf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2udfwqojr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2khzfimaz.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxucgwn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbhxcdz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcqdcuk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2szikujbd.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2zatalwlk.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xyccczrj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqtapog.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxcogql.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcmvejb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2orugcilu.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbttocy.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvnqipd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vndntrgr.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cwixxotm.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjoiqpk.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbywtid.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2egjbghph.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhfwqvu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gewdrpnn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fayxbctr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2egxvlyeo.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ssualjoq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgdjtxg.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhqyfnc.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2whumclot.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxoehbt.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2axxiqdrz.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qusdnrip.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iapwuqqc.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2palqucpl.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnyieee.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyvykte.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2rhykgmwb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjivrjek.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjaexplc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjgzmzl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkxebgg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ranyjwzb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxromxi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbfrqyu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsprnrd.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rxygvmqu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2urfiesmo.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwbnzts.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lahqqluk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpobeom.html


<!-- 参考信息 -->