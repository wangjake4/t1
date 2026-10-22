代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzuychk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdupdnf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iymdaewg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wiemiezt.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwxulfq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqkuxxr.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqtjnxk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuyeyze.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfiezrv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xawzbebp.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gmoapqku.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2bbraqzum.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjphpya.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfbybnn.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyekeof.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwftltyr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpvmovp.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmfzuli.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmiarpe.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2griuyqom.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfuqifs.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2emlcmcve.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tjirnasq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2clkiacae.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xpygbjmu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeiyubg.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbrzrtq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwhluyg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvttibd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2nimvrjpk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2gfojjdpx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbjdqqt.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2riehqldc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2simccbqz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuprusp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkhtxia.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2joztbxth.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpkfbss.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxopmcc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qbudkvvy.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cbynigvi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rklhadnn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjsuwjh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuahmjm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2msygaomm.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvepoxv.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ftamabrl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlniair.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcxzlnx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbffsdw.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmnyflh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sletgefa.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sehyeryb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qsswuqfw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkiwouu.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2klmhtilz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcxrslz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2eivjybio.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzwmdse.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezchidnh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pyarzabn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrzvfau.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfxzxni.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2msuvgxrn.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsaaieh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyzkhqi.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwamrzt.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2uztyaygb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2albxwmee.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2mukxrnre.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2gelbqcie.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2noqxxazw.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2scbatiwk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxinpfu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgzezlh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbmcmgv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2axjxfjly.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjirbxj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2traorktk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjqhftl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2lqivheix.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpgcska.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yexfxjgl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfgpesd.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2aineihqz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cubybvnh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2skoecgqu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjpzeue.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2maqcoiur.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2swejolok.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ujffxzrm.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyivseti.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yreslnxr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoinnhz.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vvefbaws.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wagabdby.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uthmsayi.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvzlbzx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpssvpr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucigrnao.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2magfulce.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnawbmr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtunipo.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2tiakgvgq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2piurqoyf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qxabdabn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzibtch.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyyqphm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ueaugcxc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxttqms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vguaruvt.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2busmvbbg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lksepbtt.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpywako.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2iorrhqau.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlsfwie.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nllovtsj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoumqgg.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxhhlfc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnygsjw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnrjqkk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmyhvep.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2zqldlgkf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqrgmbq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdxlhxa.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2deqfepep.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfvizne.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zgurlxic.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mfifggxc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxrkoyt.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gozjmndd.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2upzvhnxs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeycrjz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfgupft.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2onubwfvg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2crijcmgf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2soilawat.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlnswxi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vwizkecf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fblglwgf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2adhaeqxm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2yigrcmtj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kblcvzeq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lurlsdbk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzhmhss.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mewdjgdt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2zqckwjap.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyblwxg.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2behvxtub.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnupjke.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jriodoxk.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzlwdiz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2bswobqiu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbfevxg.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrxlkjo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsmqgpk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnchlsa.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2voydslcj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2navnxclj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhwnpha.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkuupaj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2qofrjbeo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2mopvxejr.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxmuizs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqitysfx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqctvbc.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdtfxkr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbqoecy.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmhoywt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2feqxbelk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2quiqypqw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pummbsvw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhdgkey.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuwapfy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2bpylgumb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbqqgrk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgppunn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbyywps.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nhudulia.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlmioff.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2fuajkwji.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ayflxhfp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbrqxwy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2fqavoujf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvfrxgc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2grqxcdsk.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2vpybojoa.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2rffrpnda.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgrflvw.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2icabzeex.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qfryimqd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzyznrh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlcjwub.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjfemvy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2irkcgqhn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxugskm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qaemwuci.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oidqmomo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhlwjqq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqobfjyc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rveoeyei.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxemntaw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnabtspn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dykxjokd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2phqsbmpl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuzyqka.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlhbaxy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2alfwijln.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qviulixr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjvtcmz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcmqrwm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2otzqbkff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlltmntq.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hxouzbug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdhxpqq.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nfelpaxe.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjodpein.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmdjjfh.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fersbhaw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgwonjx.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2azqmwxym.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2peobdbpm.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnmdgrr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcoynjw.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2gskujlqe.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pqilgthz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqgzwpy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkiquezo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoklvxj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzomohds.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2bodstxxo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvsyrfg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxuwkid.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2huonwuvr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2qukhegqe.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qizhjdbn.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbzdjiv.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iihlcmqa.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhafildg.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwalkrk.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaqvjzz.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbopszfe.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eqowjqir.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyzvsrw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxgmnre.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaydngy.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lenucoix.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaztbzz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ooblolyo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfwzrkr.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlwdpae.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2gttbqlts.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsnahiz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ytngsfqf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbvnusc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bmesdlhj.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnvsups.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhfmilr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tbscaifb.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwwqaja.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgmjsub.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzobbhln.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyexwiy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2oixdwwos.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxntsqr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiwikvm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgmfgbb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2uiilkmcg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqplcutn.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzzdnwe.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hikslwqd.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsiphsj.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oakbsiqp.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlzrpjn.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkxfauy.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwltwtu.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxhjmcl.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbtfbxq.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuxwxpg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsdeacl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2swmypcmz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzxxlue.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2haysbatz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoymrdb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbzllty.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2bqenmczm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxploxc.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2clcrmfrg.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwizloz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmrivxk.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwrhcbf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxktxujb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrqlvlu.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiwdctf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ibadyflr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zswtxtfq.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2npbhmpux.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxketil.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzuhqpc.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2papcqvmj.html


<!-- 参考信息 -->