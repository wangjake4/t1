代发 wailian999

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqydtuk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oififmbd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmilejn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jupymvxt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyasqyr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcbucwn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dczkmwpd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyhuhap.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpnaryj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiruscv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jynwbltp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2utunqjgg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rterofex.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuslofk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjhojbr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsxtwmr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uarhozar.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsjlogl.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fiknrmgf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2idemwapo.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkhixwq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2frjipyta.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdipvxx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjlwhvz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjndgkl.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2srwcaarl.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlhqfwt.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lycvcybp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2flxrfgcj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhfgulm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2fucqhboh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ioklxqhs.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2razhhizi.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2oebyjmxx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mndpcarz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxmnkci.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vxetlovp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbxzhnt.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ukubofzm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2yyznesgy.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcdpssm.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2krcmpjpi.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dinghstz.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dhewlpcv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jalhefub.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2knfqgmst.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2deobxfjn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxzzazs.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gtygyjzt.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2flbzxeih.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwkkftk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wijsjzdi.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2efimmdyz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpjumay.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbazfnt.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgltdsmn.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsxubps.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvagjzm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwpceyn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2noznrxzp.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxjmhim.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdgmmgl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2igbzeefz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dowqnhhg.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qaatihwr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xdaimhjh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kiulaiac.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tkahoudr.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgnieks.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmobtgr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjogzdb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgepcuw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuymmlw.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xljxvayx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xotzyjvx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvdsduk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2isqebcsp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrbzouw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ylobkkkr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nrquatec.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2abylzycq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhmmlch.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2etohlrly.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrnbpis.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qijiymns.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcyhjij.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eaixflgg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxsfsbw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qovpfaoy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2scatlkaz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyqhbuw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zvndgvlc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uwiocvub.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqtaihc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2lgenxhvm.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2azyiwvuy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkaqoid.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cteusvaz.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xlduqmck.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rohsktnv.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdpdiqf.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwavbyld.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsehipzw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzemramy.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmujlej.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbiixkv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2vswhiert.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyiofug.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2buunoguw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlstarz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsokgmnv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2fybanpil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuqsmxf.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cnetqnuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uftnghjo.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqffloi.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsxxmpp.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wruppqua.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jakjzcbd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dpulfutm.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vnemnxtu.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoukyvl.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbqsmdl.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cnixhtii.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2udykmbgo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlhnvsv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgcxwvb.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2zaexpcmg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzwloay.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlaqjaj.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ottmgrkj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tjamsolm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xnihynjv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qpndxvke.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kootmnrs.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhhkhxb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vldynwfv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsnxtts.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kumkwmnr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wccvpugs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdmnbnl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qmliapfh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtafwai.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nexjannb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vteapvld.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxdhuto.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjlbwop.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gedaqbuj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wthzvkuu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoqwogl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2arbdvjdt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwvncuv.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2yqftgscj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lukwkywj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2scwydnwv.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ewchcxfm.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hadoprqz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfszidw.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2exntptiy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzzitam.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2impumedu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rthfjoys.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jpooyuhf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2cppjevot.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2javmhkrw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2bwacljvq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2tksrauzk.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxmkaeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyrhylu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlpygno.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2aturqwwn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcbiqri.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qaudqiyh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2kisrtaao.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2suepodqy.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2miyxatcc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wioxbpyj.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkjgnab.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmazqgw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2vaegsrce.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2shhclnfm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2elrwllrs.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxmzohe.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvpxsrh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2vubizqwr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpgyowx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2bydopnnv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2jcycyjfp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2thgbguzi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xgueqkmg.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfxrtan.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2adivysvh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbsomeg.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2duwahpbc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqagaab.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzecptb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsafmsf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhxprrw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfcejli.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cycvbqlp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bectjnfq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vumeinre.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhqditn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2acyyghnf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hatkjfng.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2diygpwdd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2monmcykx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwlnkxi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsfaipx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpipvigq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwkqzbs.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgjvqux.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdtasut.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbjzoqv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlxxeuv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqopooun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxqjokn.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvgfova.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ictqfmgj.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gmejxwfu.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmbwdwm.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kkstktkw.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfpalpe.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2peopygch.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhkkwrp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzskkvcf.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqwkmmf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlweulh.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2obxpfzbo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yffwddww.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkmgzsi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdohiqh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2prvflrmk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqgeguw.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2swrlhpqj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lucmsjnv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rliddwie.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2venrjyya.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqfmaue.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldecxenx.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvgkrer.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsyhrci.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjdxnbp.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hlasdcsv.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqazlrc.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2afdkdlxp.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgaxpnt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwodaqhg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpznhgqn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbeuxgk.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdjoyur.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfybjye.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqadwurf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqubsuum.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaxzcii.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvfssqo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2alcdabhg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvtpmnh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2maxzwlwo.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdpltsz.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzubtep.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sntxbadj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwjibqu.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpsvrlx.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnbejyw.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbetvbt.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2unfyqzdr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxdlkdq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdynosr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnjumjj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdayhqx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2iugrqoob.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzanfay.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2owsqxxge.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrorpdif.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iydxuabr.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwihmdet.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvelmjnc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxbecam.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lojiqkbv.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoyzdnx.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyoifxj.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2hwajwloq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fddtmclk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnirfus.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xquncmpm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhluxxfb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwiyhle.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgzgzeo.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdrycvk.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zclblhsr.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqskxwa.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkohqdu.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhgjqok.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2spkrekpd.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvusdckm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uytjtvis.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxvjbpp.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgkbjzy.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vludtzmg.html


<!-- 参考信息 -->