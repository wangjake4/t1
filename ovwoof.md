代发 wailian999

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tozgzrxf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2psfodyel.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxoqfdz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rellnzfg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2plkcgtdd.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gryekehq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2foioplge.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgubojq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyagmlg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amoxwzjp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwhddto.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2tongsqkq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nsajbbbt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jnglezxh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mklxiijt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iopcahrf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2euqxymio.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mxikcjmq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwftoxa.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnloqqyq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmlojwx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvtoobq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2amcxwplw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jboyafkh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpnxjbx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2htjqqmsy.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfcwqbl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghajrhlo.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxeziae.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfrxmay.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2juhurjoz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvbcazm.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtdbtdg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyslywf.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2afopipmr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvacnuk.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfpnyzb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ullljbcm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfatutt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrmmfqo.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhsobjs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2egdoxrer.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2obnywnba.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkwcalx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtstzes.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kidqyoih.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2khfgpqjz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeulxwn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgrbpwd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaesaase.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jdusdfjy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2knrvvckt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2fecmggaz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlwxysu.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzmtttb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qavbsaug.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgovnwi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcspaaxn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ojarycwg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfvkfdu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbbgcsr.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpjszyv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2caggabrz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2axcydtzn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ayytkymn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvshvwaj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2toauxtkf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjrxmtb.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ejklwnrr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkmjknm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbnyhds.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2uegvvklt.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqeifvu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgwsmum.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wozlxzez.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzwnmnv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2wianidtx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvxotxa.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hkikvwzq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2snhgiskf.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jynfkdnj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2uducsvwk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ynksfgeu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbdbjkl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyuunec.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kojyrzns.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsdmnml.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2prxrdtia.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xijyxwop.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2elubjaah.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2keugnjwu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2baoujdiz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tfeqewar.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtaspti.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2otzmyygk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2anylcuvd.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmzeutz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hetorstm.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrhjekc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oevhjbjg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eymnibjm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xejzwfyz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyoxqsh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwztivi.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2frawyuxd.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2nakiqnoo.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mefttwlp.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbphfcsf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdlvenn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvcvrrm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpvjrea.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiawvfd.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qgttoogb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjvcnwy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmloeci.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2anwbeagq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxrrrdv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lfenntlg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cffsvted.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyvjbaa.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dfocnpal.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2igyjjruh.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrvuuiu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbctizo.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2czxloeft.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlygxajl.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2tvikrnfh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaeecqr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2antkvsbw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2niufkmqj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkvfjhm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2oipymphq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfuhecv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2erhvmkpz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gembjjdf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmnuhot.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrnoajw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2sexgebqt.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwdmtfp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2opwbzwco.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ddamftxr.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jkapsqyr.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hajqlmae.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdlalfq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2iclwgetd.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2knzrqhvt.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2meypqnyn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2usuybrdx.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mswtoxrw.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsxzvsm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdwshym.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oidicqqq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmmqdrz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2npoinoqt.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wryhhmoa.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsupmmw.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcvdtzi.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkaksyn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgiomxi.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdnerxu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqbldai.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2dooepveq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2douwzpmb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2urppliof.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zotyjeuw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2shgqzloq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcpyxvq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2unbyluym.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nhelmist.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfgvtkl.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbhbalb.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mceyotrn.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2anblijsm.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2adkmmbid.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkvjcxy.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqkcmek.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgilhbp.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2opjvzndm.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vuckviwx.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nhucootr.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2smhtmzgg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfecvgk.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kivycmxv.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gujrzhfp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qikzorgt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2brijipye.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqhqqhx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2myxjmaso.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnanptk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvspadf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wyraskep.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jrypuovu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcwnktm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mwexocnn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcsheme.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dmurjuqc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zquitheh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qewalltc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2erjdumsf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hbprwhcx.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2itbmizie.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqdiudo.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2klwivcfy.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2efxvqzpi.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2rijglfaf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xmywvnfx.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uztzpfmv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lazdnnmj.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdrijrr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fwegpfbq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlitchc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2prqddaic.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyhphob.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlsnmoj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2cgroglvt.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2epanijtw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sywowlyl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywaitvtx.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpmwujb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nqksxhxz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrufwjs.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmfdwtu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeciscn.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyfdavu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvzhzza.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2kesmgsgf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwjzurr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2gkejburq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dshldqqs.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2htsjdoaf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2wevdotks.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2uinbbuly.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkszstf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2gojshalj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2pihlvlec.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2mganxhui.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjaqqna.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcxxqqv.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2venlmsam.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjmdsya.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbcsbax.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2bhovfudq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pplpajdc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2igycdhha.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhwkiho.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfztxppo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urbhjjyc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2flhfdxyq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgldofni.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fheydwmt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmxjvaf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrrkkgv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vytyubta.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzneylt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2asddywwf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2piuujuuu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfajoiuc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdyuylo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uparfyto.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2twfbxnof.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xihobcuz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtsrqri.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbihtfzf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2evuscusb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqiuqxnw.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvolprb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcrddeg.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhzatda.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsukxirg.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtlgaau.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2icdhnelt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2xegxwobt.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vymaxlqj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmjuuyq.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qguxctgk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bizhajmf.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2dssmxljl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wedpipgw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtjzbcd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nheujzzp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwjotdj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqvzytp.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2iklqwrnb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dihjahut.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2usprwumq.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lllahfnp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2rxndvutp.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2laoihzbf.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2acjnbvjc.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tawevsbu.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrarujgg.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsreqlq.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzkecaz.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2itnvfead.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqvvjld.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2brtdrctb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjfcfwq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2yopcuiho.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbomiwh.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2lfusjpos.html


<!-- 参考信息 -->