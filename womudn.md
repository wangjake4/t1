代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gyplrwbj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcaqzed.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2shfhiabg.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqoztmu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzttbwr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wynnvzef.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqtijsr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrghvlan.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmpcfmq.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwrkayg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2spljemym.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2smyduwtj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxhlthy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdjfpvj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbfpxyz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2onhgknxm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgilhed.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwwanls.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxauiqe.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unnheuxx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzcwtws.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzttvwq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2aydpiwud.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rsszlyfx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xymgaxnt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mprcaeuz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgggfbv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mroalviz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjwkymw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiickca.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lahzspuz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrthoua.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvqqdqb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2thwxwvwi.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uacmsppu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlvjfdz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbmptvc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjnekkz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2yikyiqri.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2siayjqbb.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwjfdsm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kevtypaf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzarxhk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2avtsodqv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgbcblp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdybktov.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqwsupl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2egjjdnze.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nuorsvem.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdoqudz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzwcqyd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2pegfafxj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcyihzi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qubtfwaz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvhhbjb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsqbbvf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2awfaafmq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2dexjrtfu.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fbynjggg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2meallake.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2traynirg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2epblzimc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgfftsk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxsmqot.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtgjmpi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2npcsouxw.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ivchbcit.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwbwyql.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgkbsmm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2afnpnkwe.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvahhren.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbwtxaa.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zossqnxx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgdhjbk.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyhzkoy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwumttsi.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyceodu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmunynk.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ikaezzty.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwlinve.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2bscalysu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zssyskfe.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mtppzmcg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcfwlnn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zszjltup.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vksguiix.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqifyve.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpwuhiu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcfolrn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ruakkzui.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhxxvvl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmosldg.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2oftkcxcf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2irqqiniq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvcpfnn.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnuozmt.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2epxgxaaf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrtfvpy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2njujsfig.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eovqzcge.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mklxhbhb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2atwtsybd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ittxkcoy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2avyonejt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxvxnvp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvoztao.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dfovcexw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2utbumnnx.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bmasibhd.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdkysjd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2puorqlyt.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncckbuei.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2mvafmmak.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjhrbng.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbtqdaf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2edrhcbri.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlwrokl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhswjyzr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hflktigx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xilujvur.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvvgwlr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2grxemxik.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2turtaibg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqutnqyl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2extxpzpx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwntytgg.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcscatd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzhwlqr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqvcimp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiqdwoh.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsfwfxp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tirpjvtw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kvolbtcd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lauinhpv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrzueem.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkhklet.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bkofkywr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhwfctq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyboxyrd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cbagbckh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxdfybz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcayadhm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wyehqiul.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2megmudyt.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xegozvto.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfhijun.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2syqjjvpg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkizesv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2upbjngei.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2trelzkrl.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pmosfloz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2khzhpiyq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zltgakyr.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkkygvc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnklehhp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vekibklk.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lvksgtdv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2apraypir.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fxadtsxp.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hisaatkq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tjavkzqu.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpqrejp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoyfrdw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2brvecqfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2admvturk.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2gbekvdeg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiikadf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2bsklgdmw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzpjmls.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqqzoom.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiskctq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2furceiev.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrtfnhj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2snqknjjl.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2seksivsa.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ftobzvgv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yunoinex.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgwtqdj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2czfghlyh.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrikutj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2toabzqta.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyastml.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bdionrwb.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ywabanbz.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmdzaab.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnmbigw.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaignwk.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2omhgklpw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2booaotfh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bycszwpr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyqihfx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2yfddfhff.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2flgbobeo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2iwztltgo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyhhglq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2yopfmxja.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfohccs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xlewlhbr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2csopvimt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfidgoa.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kawxinov.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fljqxpyw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyoywlf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zijljlvk.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwuaycg.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2oimfhehy.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vehadboz.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcdelrz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2njfcdqvu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtqozrc.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cneqcskn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xapgadns.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2hnftrjzi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkzfpnw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ciblujas.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2kttjrglo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2aiukkoqu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvejqnc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2qotusdnn.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wouixvzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2opmqkolo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmwsegh.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2csgsmmii.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqafbtxo.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bngcahum.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgdutcb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2dphypzos.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwxtaid.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ascjdgaw.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhszpma.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2upjgvdsy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2nogrnbjx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoipaig.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2veyirxnf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2thnxhahr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsyehfz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdukxka.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjkgpko.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2mitgmpdn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2coduofxg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ycablxnk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvdzrsd.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlpodgl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2bokbuxvi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xxixzkja.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbtyxxr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tevbtmfy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmwtlxl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjrwuus.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcatwbfs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgmspzf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwxiifo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nonycwii.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtgiiox.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2evbnredf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcszsmwb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2goeutwld.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmtisin.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zffrxtfn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfwguzt.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvasysp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkuqpsd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcigigz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhkddke.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzegnkrq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrtnyja.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cczajaqd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sudrzjur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlczbmk.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xetaywct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtcsyuw.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmfyole.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfzlsaj.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lnulzjkk.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwobehr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfxruno.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2csyfbsiw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmaniop.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmwfhgb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvchdbnn.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwehdaw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nijappkp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrvvnzi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2unmrhnoc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoghyect.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqdizih.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tljmnzzp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2bxamkwol.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mviaepsx.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iysqvxji.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2skmhngma.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsaexkw.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuefstte.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdwjwjk.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyoapkvl.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsykdrw.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2cdykrrze.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbqzjvu.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwjpwoc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhdhone.html


<!-- 参考信息 -->