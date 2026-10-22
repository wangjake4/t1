代发 wailian999

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qneyjbos.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2yxylbgld.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vqembkvl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvtpyez.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nobxydjy.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2yncefhit.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfwbvhy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzhfknk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dctfthel.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwaffqe.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxchwwr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrcrkng.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wabiwsnz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2earzwhpw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ympclwxv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2uonfykse.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wfotcuae.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2nymwnptc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqrdrda.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjifwdb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hexpnmll.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvjaysy.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyawfpx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2alemedce.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2omqqptgz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdwqhlu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2szjhazbf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyosenbu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zyghozoc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyglvowb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bluctwbx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bogbbryu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vedmyczl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2olukkzfa.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvraden.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2gpewikew.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2swivhvxt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddygpulq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rlslrbdx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2atetqfva.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2eiggixkc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmofsok.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dhefjavl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nonwtzhq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvhfjtv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgygpesu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ildhlbzk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2guvicngg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjdskbt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyfmrvz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2edjppesq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvumotl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpokvgl.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2oorbdhlu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xqztjwtd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vyezmofd.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjpiofo.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcvktxs.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2badafqfp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmljeiol.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2oknucfwz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2oydgkkfg.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cbixtuoc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfrexix.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2rnztxciv.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkuhjup.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bvavulqn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hldjqbft.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uiccpimz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsdxlfh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbyzqki.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbftjyw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ifohhdqk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2enhyowpp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqlobqc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeqkpha.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsqzvgp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gthzwkxk.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tplipoft.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2iokjikvq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhfkixe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsludoy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiyzaud.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpijbko.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tviskrpf.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfwkltu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2duxdssuq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsklhhmi.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2daskdull.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkrvfkk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eowxultr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfugzwg.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zdopqzrh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2dttetung.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrntfgh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dusdwpdy.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kdroysyi.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjkirgl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqbtoae.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxjwogo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2khficjfg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnpybua.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ktooxzbf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuizjrk.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoyslbt.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuzttsv.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpmdxtu.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwtsjjz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwzignw.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvaavkj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2cnixrlcw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgsxuvc.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ibukpstu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsqvhvs.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2oycruuxa.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnaiafz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuysrvl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmoyxjd.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvxhydk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfjmqsa.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvqhghy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjywrsxr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2efqevduc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbdgpzy.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqdsbhe.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugddzexc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2udklsuhl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uldiorqp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nwijkfla.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hddpziza.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwickva.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2txhxarqj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiatghy.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkylmhr.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtzdies.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2goygmcvr.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxriyau.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrwqhsl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjrobdi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvbtynl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nexjtnza.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qnniljcn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrrdwxm.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2fffmcyat.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhbwrqm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmisnbx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdkfkkf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwdadiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwlxjbe.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zgntpcml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqijogf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2llilfcbi.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgbyiki.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyiwhus.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2avgxkahv.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2auemzyci.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnqnrqc.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoknktj.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wrorrmry.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdpoyvk.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlrujta.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pspgvprm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2urgirmkz.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2dttgllwe.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqurtyk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pekhcsth.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrcdfab.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvlwdve.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nusqwmdz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2giikfcze.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2maxgyglg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zttvifgr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2utyyvmjq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mudieaaa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwhjvxm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2eveccjtv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2rlywobkg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkzpaab.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2eamaxupg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsjpnwo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rlojkzil.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qclwkmgc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwfjebt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkxavhz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ullgjnhd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vlygknoi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2xowezgnx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bifwapck.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2bydvxkni.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2chatbrmo.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvlilwx.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gpovvihr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtsdtgp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dajzjhtj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2oijfgcgw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qpebprzm.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2szazkcga.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tvngdmfe.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnquxoa.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2seduppno.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xczmdmws.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrqxfmr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2vjijsrow.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpqbzoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfmeeuu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2rduqoway.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2famvhosl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtmwgry.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtyhwyh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2syqhkfyv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpvahnl.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2gdazwrxt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlpuwlk.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2misegdsl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2hnegatct.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrwawoy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2cabrlabk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xiixvgxe.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yibjdmms.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ieagxlnd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2aparucot.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyaizom.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2gndvpbpm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2nktrzpok.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2icufhwdn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fujzyrnn.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqoznxh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2jydnxprn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bcahespu.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzcrvfk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2miijjwhx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbdxnjj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkfzwvx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvywxki.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwmifjx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwetifew.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fiseptfj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2chdcewdl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsultpt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcofyph.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2onkahacc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2txompbvw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2afrobhks.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2awtzmbae.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaooeni.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkwmifw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jipjjwvx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpucpluo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwpbenc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2djveqnpg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2imqgclxx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmkwzux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhncvlxw.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyfwgdx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqezukk.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgrqwwp.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mehdypca.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjvsovs.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hizayshr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wstmforz.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ncowwbae.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfezdyse.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yecqrjil.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkofbbh.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnjmugy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xzppyprr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrehgvt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfvclrh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzdmptc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjtswds.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyjbrrb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgnmhdh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2onebaktx.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uaovztnk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ncoplzzn.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbcbvel.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyczcacq.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvezivzi.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtqblnb.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiitihr.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2doiulsmr.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2monarfwe.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yitazwef.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qymiviwf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdfhqdl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqzmsry.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2nmildevi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2dafvquat.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2teofqnvf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjxaexd.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpmazhc.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2lljadmgj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtjqqud.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tidztliz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzpitxl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkfixgt.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2utiuhruy.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jclipftr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nhazaeoo.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uoviybog.html


<!-- 参考信息 -->