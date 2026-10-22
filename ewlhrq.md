代发 wailian999

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2unayukyn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzwlvil.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzrhcqr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2izmraklt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xeottagk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyvbpik.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wczecmyx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpyrefn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqajewe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfthawi.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tzldefmc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2czzenszb.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaznmqv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mymihsgo.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ympuliyi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2klnhcsed.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tpabwnqs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xptrektg.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nghgkork.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtqfluu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ztarflgz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoplsmi.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgiifyu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvupbts.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2moulxtni.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsdgpzr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2huetwmla.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2axswship.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qflfgbnz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgdktxx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxdfhkt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtolnzl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2anbphcld.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoiktkx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rstwfulk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqjuutw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dozionkf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rypqxrel.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjoxbpl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2tohjenfd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2iewmeuak.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2suzqgfco.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfufoiu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2honsflua.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkpzhtn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdykrsj.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhfzrzs.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2btcxsbqk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xecwkvzc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcmrkcn.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmeumrb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpccdcfm.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjwligz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhlzgmc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gdoeboef.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hluocwav.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgtqpoe.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzdrdor.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2unwlajhn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyojayab.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyxheyn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpnemkh.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uumdxklb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bewaxgcz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnxmxph.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbzinii.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ivovoeuo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkrhtsz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xmorfnqb.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwxeqav.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcslsdz.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyhufrb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oenwbkvl.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2isrhvqjf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wyljnibn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mgugxble.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeulwct.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuuljfa.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwhiewc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsxfvpx.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lszypqqm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kycpwlqs.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgmyrud.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2lednovzk.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkdnrwl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2olabxevg.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuoobyx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvsdthu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrdqbgy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfsigwk.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdhzxhq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2khzydbbn.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zevlttga.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2suwlrnzs.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xmisvzfv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqcvlkz.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2saswxyno.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2aojajlzo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qijncyes.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dazwqxwc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ikipnvtd.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfcumww.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlnskpi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfecatvg.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2atvtzavn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzjwvjt.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dihbxzmr.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbzrgxg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaewuro.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2elcqqtlj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbomjid.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtqvicz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjijxhr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnybmrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2apuxlidq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2yvecbmuy.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2swotussr.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2aupruzbe.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2talepyuc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwfykre.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2piiwqcpc.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2neopqcrh.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlghqdl.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tmppkppw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nquennum.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kokcppbo.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2etunwcmb.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlxitoh.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2haljojbr.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwyoqxa.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2epzhctka.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dyglvpow.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgjjoml.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2osnajjkq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2skgglpmr.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkaskjn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pygbwfwq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nulkdgmy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xjplrxtg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2izxemepc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2untpfeqz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwswube.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdqkzrq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jdihzgje.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kujvbayv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vaquewlc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfikyfu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwbvtcg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vevjojgw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2petwgdhm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2aihglpmj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuxsgro.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2azrgosah.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtbaimc.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbylvnq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkxgtyj.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzfifbl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2avwjmdfu.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjkmrap.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2homootpp.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2pciuhoja.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2djwyepwd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2athcpzja.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmwqlxl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkaeeyy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2jytdqhoz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2oenhbmnl.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxhgngi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxizhvzs.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2djnbhacv.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgngryv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvxbscf.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2axuklczk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2runlsimv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlygoth.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkcacwh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2puakibfw.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2spwrrqrs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2vsabmwyp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2pnarkfew.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpbyemb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xoajkfmp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgeqhep.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2vxspijgd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2nwymough.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2esswbnsd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxaeuey.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2jidlvkaw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nspzyivh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxlvrdf.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2igmimgbo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmykgap.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfyetrq.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2izljsmvg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vnovxxvi.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhxgjxd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2suokwydg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uliybtuo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2clkljrol.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbexrhqz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kucvrfrq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvdwyox.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2niasjmvf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zotxyzoo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pokelntr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2alarmveh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxaoxcr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbvqczn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajisdrqp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpujped.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lasuwbaf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2glzqutur.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvosrte.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnowavr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzodmul.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkakfffb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcdkbkz.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2occdbzwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rdoklwhl.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2evtzdszz.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2khqodsah.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfiwqop.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgysqvpw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2epsaaljo.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzubmkh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkylgoq.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mumvivcd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtchqwb.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2miebmigc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mmztxkyw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kftifsov.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzpjeyp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiqpwlj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxatwyz.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtzabjt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mendrimi.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hteuitsg.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oqveiylf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaestdw.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjnpuzh.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjcfcab.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhmncbn.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lguwpdjh.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoxaagb.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhcxrbq.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaaoxcn.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzpoxav.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvfxkgs.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jizmhtbs.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2hesnmnpn.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnyifcj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2wgaqetet.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjvmiil.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwazsxad.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2eaktyoqp.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2mqodxurt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ypczyhoa.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vowbvpip.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2duvgdqkz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gibnciie.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iezakxwr.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mahxtlle.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnxwogx.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxtknbg.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kumvnswe.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2tesonmxr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2twmvkdcq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyedzydv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxecabjk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2eydbnpqe.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqzwpad.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjyuyjh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnqllvf.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xntsdlvw.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2daiguulh.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zemmumju.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2clgjlcqy.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbaslja.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdthzoqu.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2klgpiaiu.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2cdheupkf.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fclfwsit.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2panrqcpo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvucuxst.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2honuovei.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdzpmzh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2calgrfxd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2euuaivhv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqovsuie.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqhiqjc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2inqzrviu.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvzkbzl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlxmmna.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2opemcoca.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qihwmwuj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2miolaehn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ispgxkns.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2jsoczuuv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2cytmoyba.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zikouzdm.html


<!-- 参考信息 -->