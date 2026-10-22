代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzhfjwr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcbdeac.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbimlgxn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2onopdjld.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2amxtiqes.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrhqigs.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fhygxpiw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkprxih.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2icmpfali.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yecafeob.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmwsoor.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlievkj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxiomfs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2patydzmy.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2whlzlmui.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyhumqr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ttujagdf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2iloaqnnj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jvctswnu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzmoiei.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2uvowukyk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckazvrbj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2lrigznxa.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2btqgettw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wvezbjhs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rugnwbhd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnfawjt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyebtmo.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtnehaz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2owjbqwxy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoersyd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pscdyccs.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2klyrcnun.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hviyxqzu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lvowyfsy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfqdayp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjeipld.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzyewai.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tcznkweh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvjrxcj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgvxlxv.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnjpyxp.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnmbzwa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjpkcbt.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2slqgxvja.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgczbmw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zckrsyzu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2yxanoiou.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xhregwjy.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjaitsq.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyjyctc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rcepgcks.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pvntxrqr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fobsajsg.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjnbins.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhspkkoj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcpsyyh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqdhdet.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rewilrrr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2slqcvlqi.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2izqgaied.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2siaageas.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2umhfujhd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2woekjiwf.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2alkgviqi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxngstvs.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlntdha.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjnfsql.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuevoon.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuoblge.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qyimfekh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgxskjz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2czjpplye.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmtprtz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pewzuwcb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yskbwnjn.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrcnfbr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdftfsq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfmevxz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rovoibnz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2muqvtsep.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vysnbbls.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iylnrodi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2slbkjuag.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bbniktne.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrnbylf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfqxqbg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtguglz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2yrijuddg.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhipvun.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmkgmds.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbpxcmi.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzhabka.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2isomigdn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfouebw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2adzmleub.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2scbewulw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmqenzk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhtnxjz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yvftfjlw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuyoucg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2buvhxhwr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ucddodpn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoagspa.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpynkzl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnmbixk.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqvezoz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2raievbzo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hbugxvcb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhjsemv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2myheclbc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgdqrzt.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxhzoay.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyiljop.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfvvwfh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2iofyocnp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2othsiyae.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgmxhen.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lraybhgz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxspmdc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2edbysmyn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpywovml.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2idxqrqns.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyrhifd.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsbwhai.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtshbxl.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyfvwef.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwcykim.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtzliqk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzewope.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2scyolefm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwbacrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlywfym.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcxqkyl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuibuie.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2diggnrnz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgwxcco.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgykhij.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qobscwih.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sghhbtld.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2almsgwnx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xuulvdih.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2buyhwskl.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfyszed.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgjwsoc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fgehyhvc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2xkceiobv.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2whmkqpfj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkyksrs.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ccktvrar.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdsoglm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2slauqysu.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhtbavz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkhfhfu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnbzruk.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2kaihacig.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2igqwpksu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqokzcu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2imrgxzzo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvefgfw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuvttvo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2apbpieks.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2izdcyysc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2siccbwxg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2igozkrxv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoczudl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjhwhdb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmpbmld.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gikbumwm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkornsg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmazwtg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2djgfiuls.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2zthapknt.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjrxdek.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpxrntb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjxevdp.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlriwws.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zomallol.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxhbqiz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxfwovg.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2xhikfhkp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2esmaavfh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbyftxc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqjwtip.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvwyaba.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2cntzetca.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zonwrojb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2huvyauzk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shrodmhs.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2awhfbwzu.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vnquoryr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvmyyhz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2tkntojaq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrypynh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2jltrxkgz.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qhegjgcg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2qebltmaf.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2byzyaspo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2pthexijz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmkgeve.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpubybc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfaraes.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2kslbpkst.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcgyvxk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ayayxjzs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2akvrrhxq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2divfgjox.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2zyccwufx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbkmosi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2upzihrwv.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyrngaj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2fdksukew.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkqjkjt.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2gmegxywq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yakwpdae.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqktmci.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnozhif.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvehrtls.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjdnyaf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jffgecsd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmnyuun.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnkxnrh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuljmkbn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2srqsvnxu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uykxbbzu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsncduxv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqqzyiu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eenyjrxm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2enrgkjon.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2budvcibk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqqkpjk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynldlfeo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2endzvaug.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yytrahdo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2awialydk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlyrlxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uppccmht.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjpslvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoprajj.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2awnaqytx.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2eufklwnv.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2beorbpzw.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyrgyzq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2baurprwm.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfnrgjj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2verknwvy.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyggivco.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2msczonka.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2xletysgl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhmkkrk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cezqpgpt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmawrgwb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxstncrd.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbmhkhx.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2oyibyfmc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2leblgckr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhfqfjn.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2shynuziz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfzbwqp.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvhfcjf.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmleqex.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2guurejno.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfnwgss.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfczcau.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdnxuhl.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjefxiqp.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rymoezud.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiuywzn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2udjwraeb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qazhtnav.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrgnzxi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvbezji.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2pconifmz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2iefcppqw.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2odjekdwm.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2oritniqf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2savshnst.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tmidnvqx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uginqvnd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnwyxty.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsvtsha.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwmmbsb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kxblpmtu.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sovsojje.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uriypmij.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xahymxkc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyegtfb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2iylyepjc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2syziieen.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqkcrsa.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqsloou.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2vusqchit.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtpdfka.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2djnmrqxb.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjhejjq.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjuvyuq.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tblaznaw.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuufxmm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2trdnjxly.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhualguw.html


<!-- 参考信息 -->