代发 wailian999

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnnbzwl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnkjvkf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnoptux.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgxdtyk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjiiirf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlejxhb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzkhecg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbndipsk.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgqihpi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tispdwlz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gijbczrm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbspqpo.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bazccrcf.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvjpuyj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgcpeje.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvwpvnn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mypashkn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcljvvpw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vniucvdd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjbrxbb.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcooewi.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lvldxfvp.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfebofx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjrplfu.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jleewpvk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfiutrj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mafbrtcv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tlustkdw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jclpzmne.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2doegqszk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlxqecb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hsltmdhm.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmjxdke.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2kctigxqp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvpvuqa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiqnkou.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzdyfmu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tydzleeh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2igyyjuha.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkvlqoo.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2fdphwwnf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlkytdt.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvgaulo.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjpkdez.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lysvfrmy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2alqzjopr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpuzzjp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyzdats.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqxapwm.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvshxtk.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhrnrhh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2byeuwfje.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nllwpaia.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdhogcm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sohqqwbu.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2eagotmks.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjuxglz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2widkpxia.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eodwgrul.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbnmskj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2nycdhzeo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2idsgtxsv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxjhvzg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eirmdfqu.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtjpjza.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aomiljov.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2idtnptmv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wiybiimy.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbcvkwx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2itpuioje.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hmplgyie.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsrxrwd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2azdfhycx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rumqkslq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2dumvalom.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkwxjdb.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hubtijam.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xewmehjv.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2monjsdag.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nejauqwe.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpaijia.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xztgbfvv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qivzugjo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tptvxssb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kadtlzno.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoiiubqh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yayqscsd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnsesei.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tnghhrow.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2btjeuxyf.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2iummaapl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2njgwxfej.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fekdlqpx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2erhesmuo.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqgkxke.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uabzoxdp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2clhraedu.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtsnwar.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2erybnkgp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmbqepp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfglrou.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwmilad.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwifdme.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ramdspke.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhymngw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2yejehmya.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqtcvgc.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxufbvb.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fttepane.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2lidqecjm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqknaaev.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2uimslssr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvihveup.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2npeymsgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrmesbq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaosxcd.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdsxiew.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2leqequjq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnxzgvm.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvujhri.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sltaejjl.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqrmoyx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrsyhbm.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhcnboh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaktkfo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqzwvet.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jzumvccz.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2qwiwmjxf.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dymwjudw.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxugyxa.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qymrsgqa.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rejcuomw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mddwhnrp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdpqliv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kelxxims.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2htfvhiwi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyqkjyv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qwklwucr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lemjfhzd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xoamnokt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2swdlsqei.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2syvwaroj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2clgtobsz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwdpaea.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2edniezbm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2furzqdaj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtxmwko.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrmtgjz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nqktvdip.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lerzzrfe.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2umpthfcz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzqcjvk.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkgneip.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2sybdzveq.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpusumd.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjejfzl.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2bltyiykf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyvseuf.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2asgwzovz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrxurps.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2aymgczia.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtuldkt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwjjgvw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcolyqe.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpvzgzz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlwsljf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2lbueirlg.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wscxbiiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqjrnvs.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcvijwe.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuivpuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thasgwie.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2xstlzcqd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2czahjxyb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2keyeedhb.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2aznwlivg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2nccvvzez.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrazkbz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgqycty.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2xoihjhrj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2emwytttl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xuszavdi.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dfahslok.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2dnklgtbd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhecvlk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfhzehq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2keamdkve.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2jztjygsz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zliwerhb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2afysnlwa.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2urffhrmn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkpsqpy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhrkdtr.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsxwfdt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jhonggzd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcbmgfs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sffhgyhh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdcnshp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwkekho.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2btzhafmz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkhqbje.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhhkcrj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktowweuk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgrgkpe.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpnepyl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmkbyxi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2buzcdmly.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2brngiahw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeatjiy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrujpcc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqtwddm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdfwmms.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeumbyu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcskhek.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpbjggc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2adysosyz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhbmiic.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uzafhosv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wswllqug.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdlhxou.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpmbowp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2knbhuoyz.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mghmdtua.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrusrnkp.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xgntlpkt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2eriffowi.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wofsiwvi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcvspcb.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2znraahrc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcoyujs.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvdqdsz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzyzdgk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkoyyso.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2inzeeeqz.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jodlmagx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvqtqjv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2srchyqfm.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcwoymg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxraeqj.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfaqmyh.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyopkdki.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfocazph.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfsktsb.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlvnkzt.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2judwyikf.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pznsxcqq.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbyievz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnllukk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2svxxrtyf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jcljfcgj.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2isoklvdu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdipcri.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbsgiig.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjsolao.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgsnbuj.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsmxdpy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvidtgx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpiydos.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cndisuhw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjbhsyu.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tejattqa.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jckicmhe.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfqzidg.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ldagxbha.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwpjafb.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2itbeamxm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsptjkwe.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrstozn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfctjhg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2udfqxddb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2buyqkfcr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuzhguq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2exvztbiw.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kjewdojt.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rssdawaz.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyzgixy.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkstkrl.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhntsao.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sarbpofi.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2brippsta.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2diyuepkd.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvmfbwr.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiuluvr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzoelyr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqcojfq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kavhgwah.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2pockzook.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwsfzam.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycftgwwu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlwyshl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2napjeoww.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqpnxjm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2deykolyx.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkcysvn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkgbupv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uofwbwnf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjrrtlw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2gqiskfzb.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2vhximnza.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nseqmusu.html


<!-- 参考信息 -->