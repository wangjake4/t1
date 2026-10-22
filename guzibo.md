代发 wailian999

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2penqtnnf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lpevfkjs.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxnrtqe.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqvqezu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2namtgsey.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2muohoylu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvvmrvt.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhdamrc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xdshksnb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2sxajfqet.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcahqnj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mskxijbr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hzicgwou.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdtolyw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdytvuv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyohabhd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvvwrxf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrofusee.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iquvjvbf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlzvehz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xxccnpgb.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtinqeh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvxbwcb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csydczaj.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqnnulb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rhacrlcm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlxbytt.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iyisrvao.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pkanndvc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtzdqmw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rprddnqc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuaturq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bumdhavu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaudsdt.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsjfwrn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nagelnbz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eltloasf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lfocmrzm.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyoczmg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwbjrob.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pldsmhmf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2epciydre.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnlzjsr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrycuhi.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvvsoen.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgptamr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvkzeoc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnswgsow.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwoyhyj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2svcagzka.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sferkkps.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdpzihz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wtayatlf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwgpsnr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgcomla.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2idewkajs.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ptunzlwf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjtthyb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrgztmr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kliqnrmd.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kytmvara.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmdupxi.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2efezuajk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfodxwpz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2osazsxnr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuzhzmh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfllzek.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbwjzya.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xawzuceg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnfhqjr.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrpstyb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2oqiobupa.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bikkohye.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2csogrrnj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2esvzylix.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyalsmwx.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpwvpbr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2akebgftt.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjivwql.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2etfqftwj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2dejgyylk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmjxwva.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ebydzrir.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2zygoxomx.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ehikrzfh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2kbliohja.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2acfgecom.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2livmrhep.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlwopvr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2obthmnww.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2akrkkncy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2butyaorq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxjnoqe.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2fdojjczz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpfiwkt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjjtdzi.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrlfdwz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wgabnlsh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ipluqnys.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvnadxy.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xgapprya.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtopgsz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kiurapum.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqmwatz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxamscg.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jdstcelm.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ynetjeea.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2olqgfvbd.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qevkplzo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbklcpi.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ottoueyh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsezdtm.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpmtean.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ksceephu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhjplfi.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmxwewi.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlufqrf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmzfxpj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rystanpm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2swulumuc.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2oruumtfm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jtswrllj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2csgqifjr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbjxmce.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2opxuiwyt.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cpasoyyg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2snrpxekf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbqfmpu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbqqftv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrzyueq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2mffvrbal.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqytjjrv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwxwmdm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfktfazi.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2eogwwvmv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bhelcodm.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2amofqbla.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzwargr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dfepqxsn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmrltmk.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ivttylsj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2prsmjyjj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilonxbxg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtzmine.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2leymjxkb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvroyzj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2fqulomnb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rlymqeka.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcqjezk.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zokheqiz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuqkurl.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuobzvq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiwyuip.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhotgzyp.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hepmuotu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2creipmkg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjbeefj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2chivpkye.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2guuuiqro.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqgcbnj.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhwfjzt.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vessyppp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqoohqf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqavkge.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlkijau.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxgqiiu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2djljozzn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2canoszkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtvmyop.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wjabhlvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eykyyxns.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pzagllhk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rjysaqah.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmweodx.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdwzgca.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2csjkdrfl.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fnldmqko.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpqxkau.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2egeifcsg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuxxllg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jprqkqsa.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjaseyg.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxivanx.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2luayczvs.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cmshrdsq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqhxnxl.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2amgdlscl.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2alxffuws.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvwcxao.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgwpozo.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvamjvg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2quuvjjek.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjzggvf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqpciww.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gejcnqmh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bnynivar.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbiyzef.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsdtacz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2duchpqjw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2junvehdn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpuwfdt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2btulqrxj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qafesktt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjndivn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtxmyaw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2epfobgtn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2bwasfszb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqhlxql.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfgbdqt.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2mairskdm.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fglauswz.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tilhnkzy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfibcpw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeboquj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2axsdzszg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jrabjfzd.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkjddok.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2utvecnzg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2exwlrhcd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmtsrdg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbvdslx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2epbmflgh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2cazkgfvt.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2tfumlatj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgyyles.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2shtmedlj.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbqrszw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrsipuq.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnntqrb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyvdvce.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeclmro.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcvqgyk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2eiicqdky.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2fcotqmtg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlzncgt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2queqdhau.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2mcaltoze.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2awkfkvml.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yhviqtwh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2cnijrnxj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpmypzn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaeearr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlhumll.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2odnuzyhp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcupdfq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpreyqo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2eioenbaq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2dsedrsfh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2awocnpwi.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwudgbl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbkettm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgguwakk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrfcmkn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwaazpnz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2csoiqqnb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2msjppzot.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hppsjmby.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2adslimxe.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yksvrdwf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2soiiyqso.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrddfunh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfucarak.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyejfca.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwtpywq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzekdyy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqeqdta.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxqonom.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfbcsvv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqifjab.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmntwjwp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2stfgslmm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqqwhaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vonofbhe.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2twsedffi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmfbapk.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzybtzv.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzdkxsx.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bveluhea.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpainoej.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2twardnic.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdxjrhm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjgmqws.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oynuswxq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsrnwbd.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpdvwou.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2getkknha.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dggjcist.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhzgwer.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2heacqigl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzloepe.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhmsvvq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnhgpuc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aincurxa.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2arandqce.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2gexcthpf.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aloeaxde.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2amjqalij.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmnafpn.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbsurcw.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrahyrl.html


<!-- 参考信息 -->