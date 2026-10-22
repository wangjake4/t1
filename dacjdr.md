代发 wailian999

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyelgrr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkcyikx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxupxgk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckptlvcf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkifzrx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfuglxj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kljetosz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2akrnbjyl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zfejrhiz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usgouokg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvgrjxq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ceamoemo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrvcpyp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2laaodpmp.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxtaoul.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvptydc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxzrlgp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2onuduhau.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeuwxip.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isiuybno.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnzuxuh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrdjcsp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pynikpwk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2npyezvqp.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtfjtse.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqjcqqo.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uistlyno.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuzphbm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rqltmefj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vswdjltu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2byqbwtyo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2puossjzh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2htsdsnze.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlaselte.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrcfmss.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhwndnb.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfifzyl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rofuovey.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqflmoz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqauxadr.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2buejdifa.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfusiqfj.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnemvgf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqflrik.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxtahfs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzppywd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnfjwst.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwkcqdm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhedubp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvoxjpk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jnviebqs.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdsykcf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xykiinbg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaamvhd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wixxakwt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhgtzye.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2utwvkgvj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmvyqri.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpbkjbx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2efaujhla.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjviqjv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqgsabj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yeiqnait.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2taqlxcwp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2eweizwmi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2szelcctc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcvkoai.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcpsjyt.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2xqomhiyx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2pqeogosj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2usnllzbj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2cinctqqm.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zadvppoe.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaapfej.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgueahh.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ellkzakr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2woytwqwa.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqkzafs.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdrjzbs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2pwddooda.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaravrl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfjaxln.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwkglzy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdhgmey.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhycdji.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qwosgrut.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2alsikrfb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnucguk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcpowhf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmftidm.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oeerhxvc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2jqycidlk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zaojkrgk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqtpcbb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mndbeucy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2srjxaqos.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dagmassf.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qsltjqdh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cjidtwqg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzorfozk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jysivmvs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lteyxvhb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmxneot.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwhtjyn.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzotbmo.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnjxcbs.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2taycbinh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2agtlalxc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkmtqnx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ordcuqmp.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxnhmns.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gstolsqx.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tanlsaqu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdpypco.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qijlfetr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2waqumqdo.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2nhskrgha.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dyplywyo.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlumwsq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2fibnxlgh.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlekkuk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzappfl.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xetfwqwq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qabbsuvd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpgpcyh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfdccpf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qprmcqjs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ykebfljq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkixclz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcwgwgc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmjdcrq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlgmpau.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2adwyvxwi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqxeefq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hljsltyw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wscmccux.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2diwvradz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmczktwl.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqperoj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xikypyeh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjaobmk.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2npiavfcg.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkvnkdh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gytzzhol.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cokicpud.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nalgovju.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jazceptp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyoahed.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gtftrmcw.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2szpaalsd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxolhcza.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dojuvroh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cckqfexb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvpkdar.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzfiays.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2sehyvmpi.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxivynx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzuuulv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhbyxgd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vscbmscs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuysqws.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2iubeefnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmafuyzg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kozldyay.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2opprseyx.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oemryyvx.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ubocraes.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2shzgkuea.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oyztsyde.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkwiyip.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wufaoqic.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbnnaaz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ycilwwmy.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjnfhsi.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfmvwtz.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkqrqug.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdfhpxi.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhpaqiz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgdopch.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuqamom.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hduawgwj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2naleoxzo.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfvuxey.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hewibmdl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpgdicq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzehjnc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zckhymje.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fugkfwmp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2dehvxmuy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbfauaz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjmjzci.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzvhzci.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfzokjk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2plyuvuqk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cekucmec.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zineiagv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2afaotnhf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmmitqm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2bgglmvdl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ffylfaao.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2yczlswjb.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtgcmcy.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfrksbw.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2takqxblr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgjdivn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gkimognf.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2llxzccyo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgpdqrz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2jezhtbnp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rffuvqij.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2oprjnkhl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2zrozbymu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2egdgdwoe.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuzkpzc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzijjoo.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwnvqxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pucdeicu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2emvfiepx.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2amckrfxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrrpjry.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2lufyrblk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2mrufdgsc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgaqyhv.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hgoasebt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2iqelkryh.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfgxdbb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2coptfide.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpywzhl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2gurrxseo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyjxwob.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pahlwqwd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2srbggrfm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfmocta.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcpbkeb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2kczweumq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgyaszv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zhemztaf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2feaorcac.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxepcrf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlvuirs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oexeiycl.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlznvwf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2znxmnaoj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzfutju.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqklfaqd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2juhflqbg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgbvxpv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvudccc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkppcyh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwugslbi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2izziwrvv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bowgrwsb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vitawvbe.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjuxekj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yofcsums.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bifmdhso.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdtsnue.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvicqmz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2syllslae.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2chdjxjkx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfcfdmh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwzuzdf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2shqewvmt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnwvmog.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhsfnag.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2igyhlnuc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2majxfmnj.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkcswfk.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2voopfgvk.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yscedckh.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkilbwhe.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbyvtrs.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qsstxdkt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2sglusfjt.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzevzdg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2akbnefxk.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2djbhgspo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvzxenu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyrtvfv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcewetie.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfgyczw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdwdtsk.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jicrkuby.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2acjuzdxl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyxtuzy.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfgrmbh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2jatxohyv.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmlzrfw.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcmlueh.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2isikwhsy.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yasytfbs.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyaqibr.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2pkokupqy.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dncrdqwt.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzeyjxt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbwrngs.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2huulofjl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ooglzdqs.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlvglan.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjajdmm.html


<!-- 参考信息 -->