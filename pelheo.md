代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uhihzthu.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxotxdv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdykszg.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsylsmmk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhqsqyw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxmumhn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2fejaxigq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2runubqci.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnztbwf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvcosng.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnrkeoi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcszrbbz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhvcnhn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcboyoh.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fbifsdcp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2elxxfqzb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqlpdwm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpmaflw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ucemzlzm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aylawmfx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wudbsxpa.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdiftdi.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxklhxm.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwvcdhq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfjxnrt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqidkvj.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zomngebi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbghrciu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2llfggmjj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2miuornzz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmpiuxx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zraldxio.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2isuhfhfs.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqrtyji.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2obpvojec.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuoxflzr.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gyosyozy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxibcmd.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ipawoncf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvjcwok.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2byyhxrxr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcfqbpr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2sufadpbz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2clsbxdjz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzmdtgs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfuqtnr.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfubhdi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2iazfoofy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuxheeo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2cahndiar.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2odczmmlj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvlqhwh.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2otvbaphw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kierarus.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gngcknys.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2inqtdyxo.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxidypx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2htbbkqch.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2henrckwy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2pihsvflm.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrthhvy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcliznch.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyyfhkw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhswisb.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtvxnzf.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2udtlrpmd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkcecsa.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhvfekw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xcagliat.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kywhzxnb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuzaxxt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zczezcnr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsxqrxb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwvoubf.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2fdumxicg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2imsbmfoe.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2viyjgmbh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlvszmq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dyywyevz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2hdopbihy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlebmgj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvctotk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkmexkb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzgzbwr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2htsphzea.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2desaqdhz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzvsyqu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2myivnlnt.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2uisnizji.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrubkiz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgpxprt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhtgobi.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2psuizuvd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdnxmcs.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfffymj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rusfrzkj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpmesdk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyubeinw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyydlsu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddoddpeg.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvnlxri.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jjadorkf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgdmwuw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfwavar.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgekbvk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaandfq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2czkfgsdl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2inistyho.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmrsaht.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2skekfrzg.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dnefnamb.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmtesay.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jnamksms.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2twncmuvj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cwttyanw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwjzrzx.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkvmpjn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbtwiay.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgnefnu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkftgkg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2atxsyszq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2valjyhiy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbaxgnr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxvlyew.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpqmmnl.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkvpjsj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzvnoxb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgpyiic.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gevtulcl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jokzrvie.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhlthad.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqmkdck.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2knfkpwxd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fixbbywl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmgcmee.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mjctfwml.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdzefsq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqxmxkt.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzitbfid.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnijfam.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxmulrq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwuhjat.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyyxrci.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxfqpey.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2exypsllv.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2efwtkolp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2lszlhxdx.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnljqodc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2smtgpzws.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcxxfmc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdfxzqk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2telswdji.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vmouundc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hexbbxce.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2tihfvpij.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyujdqmk.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yubranis.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxyayiw.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2gsywdhjd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqiazpr.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ewotyqfr.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrtqhvq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2csgtqpzh.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2htcxwcmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2upzesflv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2srfjxpoq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2adsejzjm.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2djfkoims.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgrqxau.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtqfisl.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxdbztu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvccsnt.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vegmkwhs.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2byohsbcd.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhcsdex.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuzjguo.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcotmkd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwkdoph.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2reqdecyg.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaavyge.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyrrjhf.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxghbia.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2javohwlh.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqxevzh.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pipvsxiz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhdwgke.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzrpfxo.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbfrkks.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2boroqens.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jlklsyki.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbjzetr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqtegoo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxuoqbv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2flrimfqq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtpgaya.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkhawdh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mflsvxcy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmrrtou.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sivheuba.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lejhsrge.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rtddcpaq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkowpra.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgtkzqs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tuawydoj.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2movtefxp.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2kknwskst.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gosmvcms.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgdundr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbxllaz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoddxgk.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkkwvos.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbrxizb.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2uuegremn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxyvgdo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2brwoeryq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2orkzjyoi.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbqbniu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxxhsgt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2evdbojtg.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcmegba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnpzeyg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2msxlsees.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2kfefaeyk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zwexrvtr.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtgimwy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2okqhrdeu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsuhimd.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2amaeiupc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2kunvpkev.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgmtups.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2umnnwmzz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2tkumvtkr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2wdufqtqy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfwzxzs.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfbomva.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrscliz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdokxzo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2dbghxjqr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxxnmpa.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcoqhla.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbyfnxj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2patvvlsc.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2lglryqhv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2zkunzwsh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2upsljeyw.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2nvellkvz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dxodwjmq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhqasfb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxnjfep.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iffkgsbg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hedgkzji.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2larjjfsz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhhbirc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yomgvump.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2svgwnvsu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwvnvzk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2chdlnhoj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcwcodr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrmduey.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqqjchr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnivyju.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2soxaiany.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtledkt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgbxxhp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmsfxmj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2okwsfeqd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiltkue.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgtupyp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgvgkbx.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkxhkss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egheqxwd.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2biwtmknu.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2blhmocmb.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ysguodzb.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iambrzpr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrgvrug.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uebnfqxn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahebhbbr.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsgaecq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjttedfu.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcaxppi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgehjtk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbqxjml.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyikbfpq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymiyqxlz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrxosfw.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rtopaaaj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyyiscv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsakkua.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeykvcy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2qcalohms.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2taokpjyk.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wplmtggy.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rctiaoge.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fofvsciw.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wnawsdwx.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ijstjbzd.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlczhim.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lisdgked.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjsmjzc.html


<!-- 参考信息 -->