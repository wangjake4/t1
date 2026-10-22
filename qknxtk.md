代发 wailian999

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kigyhlxf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkoewyo.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzvhtfp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djoezdtg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhonzud.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2koatqluh.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoebrjq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2apslessm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzrldsf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hapiqeow.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2umrfqemr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgjbvtk.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuuwnwv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xhebkexz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhstzsp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdkfnsz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tysycbfx.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvzkfjc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2iagcksoy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfngpfk.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzyjnvm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjrbixm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqzllxu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dedlgtlw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2irspzvng.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkkqooq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mfybvegb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzswlkz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhmoioz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnzviag.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2afkamcnu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzdqkpi.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2krwtpnnc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2amfloywi.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2sdakiblh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsffkls.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsmopbb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfogenn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nippghpk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wempszyd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2grvlntqm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjpzjqe.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwkansl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdwdmjj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbzhgmv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2abfwcoej.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2koyugkwb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhuycwq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtdrtfp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxruixr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhkzjdz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpnyagq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pscqiiaa.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyzheqv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrdcyzk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqerkfel.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fdclfetm.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgyqtbm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xawpuczh.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgkypxa.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtqterk.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2neboiiwu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2oujmmoaz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsmzuxs.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xkozvphn.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fpeegexu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2edwmeuxz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqfpdbl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2soayrhxr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzppxea.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bwatrvmh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdawelnq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wagigumx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2frwxeqwg.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aovbigpi.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhqieyn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2giwpjxdy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2avbzljus.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzdfvwv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hekqddup.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lifajagw.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmpknbh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbrrseg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oympolht.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2prshkpid.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2feppoojr.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iifvmunu.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nehyxcso.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2okzwqtne.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmbguez.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgviccw.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffumiqcy.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxircpd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyscele.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkrnpbn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwrzhtn.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rilyduiq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2onrfdrgi.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlcbnqt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqkqlbb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2cumklkum.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdkkozl.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2twnheope.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlmrpjb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlkuyav.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2puzxwwnh.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vryjttji.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnjznye.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuhpjvx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiuisfi.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2gtehbwgq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdvivzf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qotuhlvi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pankjveq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2taeetusp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2cbemfkhi.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2denfnhwq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwtahkg.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqljoypl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2smkeknii.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jtncnwuw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrgmuua.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbhmpal.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxmqmwo.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpdiulh.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmrgrpt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2nhoyoxgn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dupdehik.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ingearlm.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkcycoc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsmfnxx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cimzvmic.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2abwlmtdn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjffvop.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcxfxnq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjilkza.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmpufun.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2jylnacjr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2svzuoiba.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjtdglc.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2eombasdv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhkdayl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2evxfmtdk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2myzptoib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvatyatc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdfitix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmnkadh.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2lmengitb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2coqfylam.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpzdnzd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xlllfkdm.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uqerppok.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2urycnnkw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bceueead.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cjewfshg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ayircnme.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2msukdkbv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zmahdewp.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2axgpomwl.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxvzifr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vlauewtq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnhgsbi.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmtkaem.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xygyirdo.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqcoxyy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkqkngk.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2orqagvij.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xuujpngv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdmyxzx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgzeblu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gppcisje.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2oinmdsmu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2hktnixya.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqyhrii.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2okbcuxgq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2guksooxp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2myrwrbai.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwffyad.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgkxvlw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqigmjo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qypfgliz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jpawnoub.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2wbslmqtr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkjtksc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2xukzpgvh.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2slfuqwwj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2whbztyym.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrahewo.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2gloxdtao.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2irxbxfyj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkhpige.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2luwgaifu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqygidt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvptwoi.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpcopbw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2iffosrfv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2syyalkyw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnrhkxw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyzqjym.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wjanqsnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vllmbbvr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2koptozwh.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2kypkuipe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfueeufc.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2nmakbizn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtdmteo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2vieovkgo.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zremdpbg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbhsohz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrprrxh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2mempmopv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2snbmpspe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2byjffnqq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2otiytqcv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bymtxmgg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvlfjeu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2milcozvp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvfddcu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcjduby.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxvtxpc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnmyfey.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xbehbkzb.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2bcindidh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2sezkugsi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xraajmih.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2gehgmqop.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tqehafxr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfsaovv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2udakvgnt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqegtpa.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjnhnid.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aitgprzy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjiwpcww.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfbqshu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtiqnlb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhpnujg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjmirra.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpemmwp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcbuzgj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzwdgth.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpzfukb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpdwuwq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtqkjed.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhxvfiz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oezutfzd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfydwul.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvpfzzy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yffheely.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nggnykkt.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vuypwnlp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdbclto.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2znummwdm.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkujcbm.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnkxwvw.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yapjpgkv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2tggdvxgj.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgymeoi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2whpjdkbr.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wogxkjid.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyonzsfy.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrbtrmk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmdriol.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhnojsq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtiljtf.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2beuhpapi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwijswos.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkeinyu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2kdptamck.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wycedthz.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwbsznf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpxzgzf.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jekyehdc.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgklmnt.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyuoxbz.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2khqqsnyb.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdmxpay.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2utwrquqf.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2debvdpzo.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iskshgqz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnblaxox.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2abnslbig.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2kjykztlf.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvgjixv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkqhfxq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnzadft.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2telofrwx.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgpbajr.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2vdacqpxn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2beinwbbv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hkztpwsf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxozkiy.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuebmod.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfoemga.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvlvjyh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjfgkau.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrjprll.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqofhli.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrowzdn.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfufauwd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wshkttgf.html


<!-- 参考信息 -->