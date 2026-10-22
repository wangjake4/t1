代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2owiqndjj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsomhyiq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2paitusph.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pludexlh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbayplb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnglfau.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjdzrru.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uijuvhhl.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuvuohm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtcrxjs.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cffzpekr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2waewsoen.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ahblfbqm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2woktcvyw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gilexwkq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ankzjvyr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjlmjst.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhcnarw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvekcvk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtyxwcl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zlunnvza.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2npotzdab.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2tugkajkw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpulmqp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgdnftj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2iradopcg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbibzxs.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuvzcyf.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdfpewr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmnpszg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmbtttt.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2utqdagbr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhfcicp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2arzuinqy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtykkuue.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmllevnr.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ghujnquj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2welhfsdk.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jvleeaqr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ateqvpuv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2syjchjpl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxaehle.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2dnckujlo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2txeykiyz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxnmbju.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2olekqopy.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjjlyel.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyijnjs.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2evsfxqwx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwegyftf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuqbwdk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hegzujou.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2higpzpqa.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2isitrcrb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbmhior.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecylcquf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvhgjwm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkpklmh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yiptpzse.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzabkagb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxazbrz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpfpprn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2olobvybv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkxpbtp.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyejvoe.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvvcicy.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuhoddk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqtqzqr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pylheuey.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxncsdvs.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bcradctk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2evotnhxz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2spsqydor.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgxoifr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsikqjb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hllfjpab.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsjakvj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2vydeugwr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcufbjh.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qthwmfyo.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjieahz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgmlkcd.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvhipyj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2scughrze.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2anqvfdba.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfojxrk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2zabeuhys.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkarhffu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqbfuam.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lbajkikr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2jiikgpvj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2vynkvhdx.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2geqixnbn.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxesmol.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sogoqewf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwrxfjc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2brcoxyxy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmraccm.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jaziyczq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sinkpkvp.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbtfiyd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsrqhzk.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqqsdzf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfqtlss.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cmegnfjv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcgqtqx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iuylxhgn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuflsdg.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgfsulp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jdacydek.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmiawrd.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2atwuatsv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2enwygepx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gznjinnz.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmtyokl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvfoowc.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2okglbymo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdcifrp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lhetptyn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ndaeeeek.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsjrfao.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2atfifbro.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtwirhg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhxigoe.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkpntie.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqipxlfz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpwnuam.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2oedxluop.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2atlakoxd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hslfczqd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgyldas.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2grqkkzhe.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxqfpnt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsewrvn.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhrjkme.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkrezwi.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpxhhae.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjixykau.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpngdmhl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2etbqnwxh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2merzfmzv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqfcfss.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcrpszv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2yegtmoxe.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmgxhim.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxlvlaq.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pqotiavk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkhsqfh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxulkgt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oppvpjin.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyhlikf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiujwcps.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rtycwlzs.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxygnst.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlnaxnl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2baoihssk.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyadqib.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2civwtyop.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpmbcvg.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2yvandyov.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrrhfql.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rubtxoqf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkhvwxf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzdibuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khulqekj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vrisgsxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2raawvwwt.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbjwlsf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tdaiarch.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mayxrdyw.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwqnfdy.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmwxmtt.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2abmeefcp.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtvkpkr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2apgahcnb.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyjhqkv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjltzws.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcjkftz.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2avlvlenf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdajydz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxdnapq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jxynvrqa.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrhwhmz.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xouaerxx.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hgatphhg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyemycu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2btqbdokb.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2sngjheqv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2veorzyko.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzarxaw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjhxoqe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2elpyfnpt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkkpalx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2exslcrgp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tspikeyo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnambcz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfcvxtb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ryytfrvc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfjerhv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hswrargw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fidnqkir.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2niuhslba.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2quqmeesm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvqhlhe.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpcaudu.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2pebeijso.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2yepwcaou.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdolhxb.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjwuygl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmuxttx.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2clpgnucd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2epyadfix.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2smriwfvm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iycehciw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxtdzwk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxxelom.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2datgymka.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2huootxbp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2yakcpaav.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rubrcbur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2teavvlpa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrynywja.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2yuncmymx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnifgqzj.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2zqybsfam.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtdrgxn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2yaikzouu.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnwumkw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2abzvoquv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2uykxzzhl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2gvoybycr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2htglwabq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2zocwssdc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqwylua.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yukecogr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbxnnrc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wecenmjq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoemnix.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2foenlkpw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoasljt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2chcaxysi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2figrwrhl.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjwoljg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzrkyap.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2blpalfjc.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwihqxb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxklcpp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrxyzya.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmhkxjx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuondyh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kusrsfka.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjkxiok.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmeosyr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2razvxpsp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oatbbpbk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2shcmlplu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgjbwsl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfjdwnx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjwmkke.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlahdqi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwkvkql.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vunvgzyk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdeepqgi.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpzfbqa.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrjjziq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2njbwjuxh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrurdlcr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjapotos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpcnuhs.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ketqgzmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdxtccy.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fzipwbjh.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2uezrbxsk.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2soipalmz.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dthkqjnm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfamoopf.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzhdxwe.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhckass.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yemylrhg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgrhwat.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2erxgspgr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2muqnhdvi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2clknpclu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpyyfuu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2avxjomlo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2icceuzvp.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjzgbkj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2iafytecl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2akpfrrxo.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2evxmkhcz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2odaouyjm.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hymqyagw.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxysqews.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjriuss.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjbxipz.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vblqlibm.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtqpwzn.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kovdlwwk.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyicozw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjnxjyp.html


<!-- 参考信息 -->