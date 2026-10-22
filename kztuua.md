代发 wailian999

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmvtlgu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2krlcocgv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jendbexa.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twitadmj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzireee.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceorbtwo.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsmkuzc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kypdusde.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2hyempjgh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2otktsqmt.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cduupujc.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbacrcju.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2chllpqaw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2svikhops.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzznghoc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhokoxb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ednkdjbi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aywljvuh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hcapecmy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmynhdjl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjuoswu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2msyvzqle.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2chdfaezf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbfpxkt.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2adqamwel.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrqonce.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2onuyvyze.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjcwojh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jhksrkif.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeomghzr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxoyvti.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmicisk.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vuapptvw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlzoeaq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2enmwafst.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaauhpq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2accpogjm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcdrjyl.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfufbxs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yialugza.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2olwumkkk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhswawm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pirmthnd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2dctxrkxx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aprwutwt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhtsxka.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzsiyrz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzlqhjq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2frvhjyqw.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2djgbfnrv.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ceiyocwt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysldepis.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2iriiyhcj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2cdivtzrk.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnluydo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdcgilx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rateusyc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2yffmzlub.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ctytigoy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqtuyaq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2omuwuvmm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2spckyaru.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2opdztqqt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvuymcb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nnypcamt.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyszacs.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2suefdnpz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wccdcytu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtyqwjo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxavvtg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qjckqkda.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhxmjlf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tthmipnd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bdphlfdh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2swpgibzs.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxdyozq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwhbmir.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsoftua.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfcujqk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2frtekrpe.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwopoci.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpqqprw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rugpamjs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2coidcpjg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtrvbcs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cwofpqxg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hewebnga.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppizhkjq.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nstwepoz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jaclqbgj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaioypv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2akggpurv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2qlogpyvk.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2orubtpyr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdzenlu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrdrnhw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tlikgtyn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tirrjajx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fdynvvqu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qeizkphp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuhcwwz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nwitwaix.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxyvvmf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjluqxn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcxqfds.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzesetid.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2feyyzeqm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vusyobnm.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2izlszwhy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmbcxhi.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2trabqccu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfgeozv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tdonmyjh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nkffqsti.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eeobwbdx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrpkops.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbthnyi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlitdcbu.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2upgdumwy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jnquintp.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwypruk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqsqocf.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xrknlotb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2unsbjtxz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrmzpne.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2urkzlwyt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdojyzv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnvzuhj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfygkei.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjpfmub.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2niggfolm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2evmmaiix.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2txxkpjvj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2duhhgoev.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuupgqil.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsiokut.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jywofokh.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvvlzbp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2vdiizbxe.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2vtugniox.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hyerbcno.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tbufxfqm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxznruh.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuepiyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2adfsxndn.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2posyoksp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqowpth.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkbrvtt.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhnuaeq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ktizmiww.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pielcizt.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2alzunckm.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfcujln.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2thugkzlk.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqxvqij.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qotwqkly.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmuojow.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pbupzvyr.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2txtdmwxq.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsqgyhu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fekhbrei.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fgefocsr.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvwcdtu.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2haseewcl.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcwmpxp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jsojhisy.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2frjjwtpb.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwkakjo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2whhkmkjc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jondjadn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2whenmckw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kxewovef.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2leaavajh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2azscmycj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2meomrswh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2swohzgrf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2azlosadb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbkxvpb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdnwlxe.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2orvlaxjp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvjmmut.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tczowcog.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwsjguv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yyphjdht.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2genoottk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqcnimj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ostproda.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpzgyym.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnnrstl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bbosgnaq.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyoddpk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rplqiakq.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtzesly.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyjsfhc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hirqvfcb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2dyejdxrg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2exckubin.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkwfhny.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2oaucezlr.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiamtbq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sscnftby.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayypglbw.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbfmspt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlrqyri.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2someomhn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwakhvz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkirusi.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbzhckh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2iyebcjjy.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2nykewnak.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsgjkps.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2nikqudwj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2jfryuhqo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwfkbob.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2idnzjilr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2zxldynyn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2byhhgutx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzjnggi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxlheei.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaxnrfr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxpvnca.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bprjokkq.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2cuthozol.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjbamjk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qohbgmkd.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfjoirx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oggvajlp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxucczv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpmtlzg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtgtnuf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mybziqvz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdwcoms.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzynhoc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2itqfjxsp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kffidkac.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwzhbok.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfyihpd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2orhtunlq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfpjqxc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjpdidh.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hascvtvt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgckedzh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkazuod.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjcwcdm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eknbiyfj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aipmlqlj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgyjbap.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dghhtjot.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lymhzase.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxxufxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wseavlpg.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhvnntr.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiilzte.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjgwcnf.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2juxibnoj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrlflil.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvvnllq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfnelku.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdahfsfn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzewgpbg.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjvajmh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uzanikgt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrniofv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nisedwfp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqsedtt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oerpytwg.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xiltnixg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvbwdnx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2viejnipg.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ipflmxfq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2iooocprb.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeskrna.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpkjpfv.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcctuqiq.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpvxowf.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaakzyb.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2tqroxrlo.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2beltaavu.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aojtaiyc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpovyjyx.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2spiywmcq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtiosup.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jhatfwrs.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2cayysxug.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2aumhryme.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrazabnw.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2goazsisp.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ceslwfur.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lgokvhiu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yaonaeak.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfwxqcs.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqhncwh.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2izsqyuxh.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2stcbelel.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bgosuiny.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2llyhnohc.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwthqgg.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpousoat.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fahfckex.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxnqest.html


<!-- 参考信息 -->