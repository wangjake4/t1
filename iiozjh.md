代发 wailian999

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfggbqg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrlabhp.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2azqjadga.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2phwdomno.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2evpkjgdj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtjrgoj.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ihapibsm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfsnxmy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tooymtsf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtklhys.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pequnaio.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxucqnw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jajmhwcr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfarbjbq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvkwxra.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfdadaf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fgoasyxw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjlotyn.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2svfjkeax.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkgmypb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lhirbnlo.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2furkbpdt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdwpunp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nklmepqb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qponydxo.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2diabjnry.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lufxmvpy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtgdaky.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nvviqyxd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwgbdcu.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmlsmmq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2srknhhlo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2adcsllae.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hyivycos.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vswcultd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfioheus.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmgwhky.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2queabjic.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2acewesoy.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwstslxl.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2suuqyrvt.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmukssft.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2srqghriw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2htozsofj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxsynjy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqoxjvh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdcaaef.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxqiztv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2diookiit.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjjkzvd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nawrggjd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyamrqc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2npzqkrvd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2iksunqgj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2njjdhqhe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2cruzwexb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbgaqhh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqjvavu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxyuahh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbjrkst.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrlrpax.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2onehuufu.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2khtogsdt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqxscfu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjwayqj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcabnad.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rfffifea.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2adgyrmiv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kvylychx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2eauxezyj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pylfgqgp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ahiiacve.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkfqzpg.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vitqqxhw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkafwmg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2azkrfyqz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wznvttjf.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhowfkj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2dmshgiom.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2eklixoxf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2wegvqcil.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2huloxsqw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tovpxxkb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bavdwatu.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbbkzar.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2urxotauk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ffutxmvz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsvhlpt.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjtzdun.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2onrpwleb.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxyjise.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrnenaw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2czwvpkvy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2flnfjeds.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bfegmppb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhfoojy.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2aaihgsug.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2frdkhsbl.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sorhmywt.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnztmqg.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2myslvrns.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbtwyeq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uxygtrdr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hesfgqsz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsveacs.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvikhmh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbzqvag.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2onajexze.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxnibct.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wzprscug.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bwknhnnp.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhugughf.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxhdjio.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrsjoyw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzojiyqv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqjaqab.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2isrdzxqh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zrunwfrz.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmtgrge.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqjeukb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mutbuhbn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lulwmnrf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhscksd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcgfpuc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjubjgd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlwjwsx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2plvbcfjr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcswbtd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoerxnz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvygkmje.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bndjhnlz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qafpurhz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpmrxet.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnvzgna.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxmoeby.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2luvitgxf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ucewraib.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2egtyxqro.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tdansbgt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfejoiu.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnvaysv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2clpmanqi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcucrqq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cfselehs.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dedqjjem.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzogawe.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2oopvqtya.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2virwmcps.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbdgsla.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2rupnmnbl.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmdlole.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2usrczstu.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdhqoat.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsithub.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2duylfyqk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdirskzf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2avwcvblw.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rauthuml.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhjcmlr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdzvhge.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jwycgfyy.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pmizauzb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2acjjbitd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzcaiam.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhultjp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2lkufnssh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyqkawt.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2gequkguz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtvsjmj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2uehjjqnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaaubbr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2keajzhcr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zofjzxry.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mbygqfkb.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhvvmxg.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2klkvwogj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wstqbdlj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2royhagei.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cvupfxbl.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yyifupmn.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbprnum.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqlmbpx.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhqxzyz.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xyabyodj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqscvfo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlbmman.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2spqfvecj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyeffjd.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbsnzzr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eyebwtdx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmdfilp.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2enznxfbs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zffdagby.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2plodggvs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sibdwmib.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcqtbpt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdhchlw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kauefsjh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqpxena.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxjxmkn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwtdgql.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpqqtpb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoaqhhy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mroouzaq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2phwenbze.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uszlesim.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2zinfwjct.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcqartj.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2frrptdmn.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyqyrzn.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdrbzto.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2sadughfm.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2morgepmy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfqtcfw.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpejzir.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfaxiye.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2mpewlkeq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiwvqtv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2zummleug.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2powtvxuc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjqacbm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdzudyo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgrgazc.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwmmtvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oebrhtlh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2bstwlcdl.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2yrojobql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbxyowp.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2lkluudkf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ignvrmoi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2qihschla.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnuwymz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbtjqzt.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvmimsf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2nndoxkhg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkvoiec.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2yprsfvgo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrsjtjj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2koibhktt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaaviwu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2gryfpvmt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlghrzu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvapiiu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjlfwwn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mhziylwh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxpjquc.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrirwac.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2bihjjzky.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2evnyfamn.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2epewcyyf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2osknpxae.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkblbjd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsrwsxx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ieouiasi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fztfxnhr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpabytug.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcsctyt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xysqyehn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgycclmu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxflvyb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2harlkyfq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwrrivs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgibmxuy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wuanyiok.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnttylo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iprgkkul.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeyhxqf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkmoqii.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eumjuoyc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfcokde.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtitryba.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfeltrbe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmaqbir.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2amgvcltb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2decwhdeq.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2avmijqxc.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzhujqp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxvimau.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjuwwnh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmjkoom.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2oiohjxgb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnecjsuf.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfhbvwb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2maxfmyaa.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2sbociigm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtgoxzv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfdjkhx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsgzvuu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvfnfsc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqmmtrl.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2drmzvmpx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsncazj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeqjhbb.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uwygxlsy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2epgfirkz.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaqbwfm.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkbybst.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gylprsur.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kelqdiro.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2byhjrawh.html


<!-- 参考信息 -->