代发 wailian999

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2stbwdgie.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yevgeqgy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwnlpsd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgocmvg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlnweox.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xocdpgfw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqkbpsk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2elxyodvn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zclokzxc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbblgsy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmahflk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iivfuqmd.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiqjkma.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsauqpi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvkrukd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsyxhcy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxmqzzn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwjwuko.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hqedcpxc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlehmqg.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhotxqn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jbauealh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2txloteay.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwkcsxr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2veupkupj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbkarux.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpcyzpc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2muqhjngb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcuytnh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwfdewg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2apnnwbfv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgvwgbz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2xeryghoy.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jewtbtwy.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2anvrjaii.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kykwoaqt.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjbzfiz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wshpcaxh.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjyfhck.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nivxcrbf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxyjdje.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2czvqhadf.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2clqoiycz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsuaypb.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nyghbtfo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jalerdbs.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2obwdfpma.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypypqxgx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2peyrdzvq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkdlcuy.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdydbuj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vifsgkap.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2asonernk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqfhkzg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsfefiw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbybwfzg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnhjcce.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rigslnva.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqdnhul.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeutucec.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuuhosf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhmjulx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgfpiag.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2iokyedbl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzooymp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gppmmrly.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rccmgkde.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrbgjuq.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkbarrb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2euftnwzg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zccwmszg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hybheahz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2clihmvdu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jejsakxd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoksjgr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vstgomff.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbkqppm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2edfzycqh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhidmaq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnplllbs.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdesleo.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmqfvbd.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2azwnsnqs.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2baxfvqgx.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmvidxi.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxxgnlp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfdhayj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2xiswvdne.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2asicscbm.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rjerqiqc.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hnorezdf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmbfjjm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2eebwzthb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsjxhqk.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2uesqiuhx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2veaoliio.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2znrffuin.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzlmfnr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xokftcet.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2icietrhv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dlywztlw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hukdktsr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxgghnk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfianztl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpkquoz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgiiovj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcqukmt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqunrag.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzbjbzl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2sdddaigg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gslijenf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnfbtlw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kqearsyu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2agwhsaig.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqfpsnq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwdawkt.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfdcpon.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pblwxphv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uoopxzrt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2prjesfeh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ukolquli.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzgwdof.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zwztmdpi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyxlykv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2htexafsa.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2murgwasf.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2itvpgiyb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxiczso.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhmbuzz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhlvqra.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2upgobbuw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyyiopy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2aebmpgtm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxxtlxn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqdpvtz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxgssjz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfkmgad.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmwkabm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ctufuprq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtwsshs.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2camgyzeq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpompyba.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jglkwhmq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfgmlnk.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qusfuowp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvouskc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcpzesu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkglaqu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvvzwuq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2asukxnkx.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbvegpn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfznbfb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmgbjgx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkfamqw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfhbwor.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbbmzhb.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjmnbrg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnemdyw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkezuffe.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqgbook.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jtonhbng.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcbnist.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fncosrhh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nduhmtrh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrdijea.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjcbxzk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcwjaoc.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bhecvcqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxedaos.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbjflkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmfzawl.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmutmrb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfnxpqf.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xavqryme.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gkokxdvm.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wiktvgnq.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdwoqum.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdgviwh.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjrlspt.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdercan.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2arqlxxrk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2asmjimey.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2furyusmh.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbcotxl.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bakyxkox.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2epyrvrec.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dwehicua.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtqkcry.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wefljjxf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2szjzmuhw.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zazmvldf.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vcoeutnn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2udrjryrc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrptimx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjkslzy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nucasvtn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2szpcisyv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtqooci.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsbzdoy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fydcfkbe.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2msgvpxaz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmgaoui.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrvmnuj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bolpqqsb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvorrue.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2guyqywpl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2vqttrdxn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnnbybo.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jipzghjc.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqbaioa.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pmumviwy.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsyrdws.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrwabkm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mwegqwlk.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjkyknw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yaedwxqn.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ailqtwvg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwsojjq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2yxziaeby.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ucncagpf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbgqwzg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2izpegmjh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxbnmtq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxdcqnr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shposkpz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2vffygmso.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2riumvddu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiqgfgu.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2wptdcrsw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2iuszhvil.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsoemgv.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpyepss.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkeneqx.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2owqcuspl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhsjnhy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zsymohhv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2jndhudks.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2yooxvjrq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fuspbqki.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkhrplg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhcrmdl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ctamfdak.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xlauwors.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwpftfm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjvwjkc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2infbyacv.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2iziqkgpm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2seqgmicl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoordke.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2dquzhldh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2egztnseh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzmowjw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvxftzv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lquhqgeu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pebcqglm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2syuypett.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyojmrqx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2omqrojvo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2evvsagzf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uaymlxhi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tobtgdzo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfhqsib.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2djuswdvm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yygtugan.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2slxtflom.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjayfkh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzrusck.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aggmdsri.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqencioz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sblxhwpm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgeglrd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyukqtiq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrdcshq.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fovesexx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbpjimp.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iflzncnw.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2azdfjdgu.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zwctmwzr.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wnndfmoi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2svrvwoja.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2evkehfni.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpxuboy.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wluqtdiq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2viwvlxlz.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzwoinv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvnqndv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2leuzmfdn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aukejovl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2imcbyoad.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2autsgeom.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnylizs.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkvwnwd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2duzjtgib.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2derzdpsi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2animqazy.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlcetuy.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zipvkokr.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxhcyjx.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uktsfcam.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qugmkabc.html


<!-- 参考信息 -->