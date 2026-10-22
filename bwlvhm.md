代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjdjxwl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdazuts.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tsancisp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncklvkiw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2elyerzhk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkpmbmk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyfvxag.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gylcepau.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2obaixcco.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jokzrcxt.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdiyiad.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvtgker.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2exhtsbul.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbutgax.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzexhnb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nrznsumx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2osotrsww.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjzntew.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiyucya.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjruftkl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vovqbuwi.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mznaydjg.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fdycnrga.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dezldrvr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gcixrlmq.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zujcmlwr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkxcnii.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeajsmf.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtiolsu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfeesyx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcszyev.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2atcpwhpc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqmmpei.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xnseeeml.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsbceft.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqijsem.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsxjdtm.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkrzerv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkvatpd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2igfmuqmc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfgapvi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnijntqc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2oaleymch.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rihhlogs.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvowfpt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2acjjpkfa.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qkltliib.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cykwstkg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdzydvi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hypghuqv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uugjhmul.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmotxot.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2akuoygpx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iafeyffa.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2oomcbsyv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgjvtlq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyvfmbu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhdlkdc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmitahr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzdssgl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iglscocl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfwvdzy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2idefotcf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pioiypjj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwydogn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cijugnqn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gpulhbnw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdboaks.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dedriamq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtvmnkm.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pyarsfnq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wozfedog.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2yommqqex.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpklvbe.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaafhlo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcumbqp.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2medgqdgx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqozebp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxzxfje.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wphlpvua.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzakhvh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2akyknxbj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lguqgofa.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhjcxfd.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qehxjrra.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2erjcmaun.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwkhpon.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyscsirm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhfcovi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rglnmfgp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gawvdjcp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2jpejjdos.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2fohblpog.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqzdjes.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ldndbtgw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2txtptikw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2prwtuyby.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyncgro.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qotealys.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgkfubc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lyndxtww.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pbodcedz.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yafhqtno.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqidbck.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdvglwy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmtiahn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbqtpgb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2djnjivbd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvyausb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2slocrjfd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2udxgidvj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxajigxp.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfzhewh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfhixwh.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2loiuogod.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbjljac.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqqyasj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrayppr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzybjvf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hdffkmyy.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxfolui.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2eohipcwc.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2beflgcyk.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2cplbirow.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgebtjo.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuewjqjn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrynejc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmxczxk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2upkhrrcd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxepkbbu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiydqvc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsplnnm.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoihpao.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mllwtbrw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbixknj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vpytoujp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoxuemd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgusqwrx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuwfvhy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdyzwaw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkseoni.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2oixgfhsk.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsobujt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2boxzgzve.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wffrlzlo.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlqjpty.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxoswwo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhmrfuk.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zofmayqr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cufiiuli.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhnmusn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdeayqxf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmpcxyg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrneaug.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kikmjdhr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdbhptv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qxajkkba.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmrgnmi.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2avlrlqco.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2dtriunro.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2wlckrjzv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrqwyzw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlgbuuw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xctdnzwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twbjmjyj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ihykaaha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtpvcjg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxfvfvk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2czagcibd.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kqowownx.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlmlrra.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2veelfgms.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eprpawuq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcuovbm.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcnzjpp.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rowmlqht.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvqjrsv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jerodszb.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nksciefn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2yurhnbar.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjursxj.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2siwhnkmp.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uklvrnzj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqwnnpo.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrjfaqz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzbhmpo.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tghpivxk.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fzglemgb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2aiofpitf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hwavjohy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tpspvjon.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gckdvqqz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2srtlsmto.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfebsyz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2djwznton.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzpzfjd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcfycsl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bucfozie.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwxpkky.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2noptcdoc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmkscsy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrbbrkz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzfbdpe.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxwugan.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpccnxj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2zubigzkb.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdcgrri.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2shosigxa.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjjorns.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwuukps.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwydlwl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mnitkiaf.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgezgxg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjhmbin.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsjhqfe.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2plenxmrs.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2gejxpcje.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2iglgzspk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2orwgprjp.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2adwfsban.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txwfiysn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgravgd.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2cpelssdx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wafjlkdz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bakseihd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2xilceirr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2orxokrlc.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zxeydqub.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2mshmwryl.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxkvjlh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2muqcmiqa.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2brxatflt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2usopxvfj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2cklkkysr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjnofva.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2nadpoaao.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2shhhoddd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrtnvez.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxqopat.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xcadnzar.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfekqce.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ewezrvvt.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmyzqtk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2efzfpsbz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbsaflc.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2htoycvyx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2goqaapet.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbqkuzf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2btzlmigv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dubhmmwx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfamagg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgoogbpu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2drkiuonu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwjiozq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfhvgoo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2injdlnqj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmacwgme.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jyufwzvz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzbntyq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oltngrdq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqarkhud.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqivqett.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyacitt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjexbmrj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnrqdya.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvsbwrs.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2royfyanb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jruedqvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlltclsa.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrafohx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rprxavlk.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiuyqql.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbkyiuf.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2upfshjac.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2djolnqck.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jylnbxqz.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bysbsjga.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmvhiwt.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbeowmt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ridqiqnb.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmidfnw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zzoeefcf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2spadyznd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcixsaj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnezlvic.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeepqux.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2avkrwqin.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2kfthbnov.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pymrpmmy.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbaqbfy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2fhswpufb.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqujltkd.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2btlowqio.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxwwhna.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhxtslp.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wzknovzb.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdmgkiw.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjoovwqk.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sbshszxz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtrknhf.html


<!-- 参考信息 -->