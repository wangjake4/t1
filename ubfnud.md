代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtbgjff.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2vihxggor.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyxvojh.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2brxwmokb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvlqesr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwmvvzt.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdxeyok.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qttbaxwj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxmfpdl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2upuwzbls.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gvszbnpi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akmicwtt.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhgjgge.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2tespwluk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsldqzs.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnyogrw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dftiucck.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlblzwk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbezfnzc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2inkgtpfk.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2stjjvjay.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jceeseuv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tshsizlu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2aviumfpq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2apuxletj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvwulhb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjsvuds.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxqpcuv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxhpxod.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2stabxfdc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2higaomda.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjxgmof.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpafsoo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2okuvlxkc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbundkd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2voettwje.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2opwusmzq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjxxgws.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxxlvuo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rctqvvgu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2naosedvk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjnkcxq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnzfdah.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjywzmw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2iyclvrej.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wommiumi.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvejepw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pngrqhps.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzhwwhu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvirumoi.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tliqmnwj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfngatpi.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2koaccwli.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2empgenrz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2chktasiw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtsjasf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2absxlwat.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dijbimbm.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyqxoeh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mlamxstf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhnhzsq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcfrkjn.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqmezoi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgutluan.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2thmhaacu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ushbosri.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xppibbjc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2youacvwa.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnhwsyc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjkgyjt.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2icuzxurm.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ywctvwmi.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2kajomrdp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2wtthsufd.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rynthmdh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaihjki.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pllzukvi.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jdledlcn.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pysifvkp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwacmnek.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lioxtpcx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bozujair.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dquuasur.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkxsreh.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2cagwooqp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2btxojkiq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwtospb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2blxjwfja.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wnchoyxn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2dicanchb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xizjwklb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzyovwy.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bywdnpfg.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2raizktgb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2drshufri.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdtflca.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dginylzz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2dkytbftb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fagtkpls.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2apdjvzyt.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tukaozhe.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2mcenxsvi.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mweqxhmg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdepbdjm.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2nidynnml.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhtiznc.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbhdjug.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yogvdntd.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2frxkopzn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kontedar.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfruxlz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwgmmix.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ionxfnpb.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvodmxs.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2okgdjawr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpanlkwx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2njfbhylc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2omkkkpyf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhouutr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfrjhha.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gpotcqwc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2acmvtjjg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdetsox.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsxttzv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhmsgkg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2adfwfqlz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbshwqz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2itqeoqoq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhmrhho.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2btevmjfu.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvpssli.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuqmply.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ccugqebx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpoixqx.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dheylztv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbergjz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2apkypatc.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqvsazj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdiuruj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmxxkvb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcbeggb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lseugsat.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aieqcjeb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwgycoe.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ublwekfe.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqckaeao.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcbhhuf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoiqamo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2opzqschj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ofysnscg.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2umsecwoe.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ktralzmr.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyaowzj.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxmhgvl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmqrisk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2hbihxjnz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzbdxvq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxzlmjf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yueimdxq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xorudjkc.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtgvful.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpznthm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sytkveri.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmwikxg.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmgcudr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dazwsjyr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2btlgzrbx.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqbkanw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhgxtqz.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsiwfcq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2babygtcn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkugnfq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2givbtlkc.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mknsbfws.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjrleep.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2glvcgeck.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyiazsw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2novrtbis.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoodxzk.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hddxwzgx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbklzhd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzcclil.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yimfpjpa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zugxpili.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbxfstr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nygtfcov.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjvrpmb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2psmumhyx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2swrjbnll.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gntdwwuz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzqgjkq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjedhew.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bjavtvrz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpxrrcw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2fojirzeo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gfipuayk.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhvnjhe.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbgyjba.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwnmimt.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvznafk.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkzuzsf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2houhkxnk.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcnexti.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2voercber.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrbffoc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjpcagr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ddekxrpn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2caypyxkj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwmcuvs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbjrhrs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrdsjme.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2haackiij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhqquey.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2miwpwjha.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnrtygm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vilodqbi.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqplfif.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwpksgg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrgxybg.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ntncpdsj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2mygfgqwn.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsiijkn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2bbggvnzl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvrelvk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrnztse.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrdrtij.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hbemhjjb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2duflensf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxizrps.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2esejlzcp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfkoiam.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgnfjbk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2kamayenc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ssljcsya.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2zshgyspy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsmguld.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbxtsua.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2yduuyxce.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gaheldvd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmohdihz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sepsxemc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyfngyz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iicswuwb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsirtsfp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwseyreb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxlsvok.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbarkwzv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rafwfegf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2egnvsamp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdsrhhz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2geihozhr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2axrkoajr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bphmrxvh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sevhkppm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wslvtulq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nudrvopr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzaeufxc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhzmewq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2azgfmsan.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2knzystce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gptirxdl.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2khnfjibe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2duzjswlx.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkdwrnu.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqimpwf.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjmxktx.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ntinnhuq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjflboo.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tifnxwkv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvavkhtk.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2skntalvw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2agwxliqn.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2axhczbwq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cebopfkw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2meewkote.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfrudqa.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hclcwafj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvardif.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgaurrk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdochao.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbcrmmx.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2whhtdjwb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfgjzvn.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2launibpe.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vynvrhrq.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjewngbb.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhxmptn.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvyihjv.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmxwwnf.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2orfysbmv.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wikelmvm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkkzvzf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcpgvue.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lycstyeu.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdmndwe.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2sesfvjsv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzkdexr.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmkluds.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrnjjsj.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2unhmwgrm.html


<!-- 参考信息 -->