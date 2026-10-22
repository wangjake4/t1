代发 wailian999

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tybsvfie.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmxnopx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2joxopqvy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxexerts.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2caiwgtil.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zruvlyjk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fzddzpgd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ntirgjsc.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjkcspq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynklfkwy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsnjaxd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2axavdhbh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ongijxqm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2coxumxgn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gyallsyg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ksodjrgf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2twetjval.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2apwhznib.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkhqabi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2adojtokr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2txizbxiu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdwssli.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbwteju.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlasflzj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fffnovof.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tbphgslf.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrgnzzl.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tknzoyiu.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2recsanfw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2faiyxghg.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzxfmvw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2agkvrxwc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsrwkwi.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpzpgkr.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2utwtjbcd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbbosgp.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkqmysk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlgxizq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ypncsuay.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsswiets.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrbslyo.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsztgsl.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhcxdqu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjqrogj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsyntna.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2luloltnb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tlifjynj.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nybyoodl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rafdwggi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuqctlb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjbevnn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyuqovb.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pqifnyci.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvtaxob.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qywiglbt.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbyjypr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvyezbk.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vwioxkcp.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yprmimvy.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqyousv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cnajogud.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2igruscsk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfonkce.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrgdsrp.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hoocaclo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmzjqlw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2azszyumh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2anutwgnz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqyiuin.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeobdzl.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdlqtaq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xikjgaru.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnlctbk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2pndmgzzb.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2htvijnvb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrouczgn.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzsmcxn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbankkj.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2akebmaru.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdkjdbq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tentaldm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uriqxgkd.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bgixorhk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gihrbyzv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcjkwhf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2dikerckg.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzjxiez.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xchmtbgx.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ghueduxc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2naucazqv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhnlgkw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qpibwfyr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dnehqkbi.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmvtlft.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2rtthohml.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkthvbk.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2edkfyzml.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2btvexyas.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuketzg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdycylg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdmwihp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuuznrv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjvvafh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmeseat.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wzniyoya.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqdziks.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfthtsd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfttejo.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2crmqamkj.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ztckfqro.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bflnkhyt.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2boxwwtnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bboyffcb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cocfoqlz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjimguh.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2adepvrfw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnpjjjo.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pczqjaqg.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xpaifjxj.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ocydyvbs.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zozcwyeh.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2urvdajuk.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2coduskqc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bafddhsm.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqnmzna.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cttvwgjs.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2arjyzkdz.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfsaptj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqbefho.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qamzuehn.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vvohmwju.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiujlgp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrpwlmp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvsmpbt.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2csxlurjp.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxpwbox.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbxvdyu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxcwnat.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ubifvbyh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kftvzynk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpvmher.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrltyca.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2omvhikqw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2baxxbfjg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpesvmi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2oenvhruj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oplabllo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgvlflo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2avqqpdho.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nzklxuix.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qkveczmw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lywgxqnj.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qapuoyxa.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvvguiy.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwvrxnx.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuoudmh.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2izkbfaol.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2drhccwic.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tgiwlwez.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpblads.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2mluswvwh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rswrulmd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jfayfovw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jndmzlob.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2inglqakd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2toixmakg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2kurtexgn.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2iztqunpc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqckuilp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2vahxwudh.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxlmutx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zokbubhn.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2mqefprld.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2devyilue.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2vegnpask.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2alqlhehp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2izhcxafi.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbezigf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2bkagksxb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhglmjy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuhtuhu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2abmehmgt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2aspnigaq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2zxddyghb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoctlot.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtmpckt.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfcflre.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2slrlivml.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnxqmvr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2aipknpts.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ynldxbhu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaedyte.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyqekbt.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2igwsoowh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2btjaewyw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkcinic.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2swdvjfvy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyiutjv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uspvwucu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2epfuqmok.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jciaycvg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hysqrjrm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwaczjv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jftciozw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xccyfalt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjenpzbv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcahanxx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqjdbfm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eekkhlrg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmevmiwr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgajtag.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fniddktb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wazcybay.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zaggkhwq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2leafxogb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gikqghfd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2praneuxd.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2olceuwqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhtqbmm.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfoqmxe.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrvvruo.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdfzkam.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrgtfib.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmlxcvh.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2eiipiszo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmwpbet.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2elgcfvvw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2atjocnyz.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnswqyx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tdniymgj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2whvopsny.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cegjejag.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxffkul.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhccnrpy.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhsjwpr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wuclgsdc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjuxhqu.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hbakdpfk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2udmoayop.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cthzcuby.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dubgenxk.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sryxpeat.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iefutbot.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlrhrkz.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2iefqazsq.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2alaflqrt.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnqzxal.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2joixezdw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhmsvwr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2imhtqzrm.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vteeoeas.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2jztyzbae.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtwrrtb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2qszzwhfc.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2towoqsvf.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2asjbolox.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yirsdtac.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbfvvdr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2smbrmdlw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpcemtf.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aprmywyr.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2brdjhkwr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdvltfn.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2archyfnm.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjbbbno.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2iblfrgmv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnanmsbt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvdpunb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmupudpi.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzfuerm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqaooqah.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpweamp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvwqpdz.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfdvljb.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvewheho.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulempslr.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2epmaiuwd.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xunfqrjf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2auumlfaw.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2otwlihsd.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnqswoq.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfmlsql.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcbaury.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycohplij.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqeegdw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggupnrao.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2axodiuei.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmcaweq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dijzhjiz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2maimrapi.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpgslmv.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tzijgfnh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtbengh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbicmpmh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdzgzwf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcnncix.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjvvfbs.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2sddwmjtd.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbqyhbq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmahrqwy.html


<!-- 参考信息 -->