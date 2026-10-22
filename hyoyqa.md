代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2odtphltx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvdskyd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyflfxl.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkuwnce.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bdioflho.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phswmdnc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iohpqyre.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcojxtw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbjodxb.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vrthqynf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgotoau.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfytwrlj.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2udvrttml.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxuxibl.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqimlza.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hddxwflv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dsutasgg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbuzvbf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfrcjlb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uppuvkov.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfudcnq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmnuyis.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gynndtvv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2aysjdpjd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ighjjsew.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkfjqrg.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2otnaboez.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aigytbqg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdpamfv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mewxuesa.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnbqscq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcregjl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2agqahouc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujggulwk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mpycuarn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pllyadeh.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2iacchjli.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dahffklf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkzzris.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsefylzl.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2adbsohog.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qthfwmhk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqnlaif.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2szlggusm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhzhizx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbxltzm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tyanzkal.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrzufri.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jjirkuuo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfkvxsa.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjqzgsr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvajpnp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2erpvbzrr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsxvcol.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2titxalif.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2sdduezuy.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vontzvmc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2boqjxqyf.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yyujvezk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqjtpaw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uwczrdgq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2sagaouzw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzspberk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqotdcz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbcwxwu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jirqpild.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zyymgefq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrqfavi.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdysill.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgaajiw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcvgmma.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ritvbkcj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vravgycu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qixvlwzt.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjlrzto.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ilapuebn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2osrovtup.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2opmizqag.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ambpvjoq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhocvzm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzuhsgb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nboxapll.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wniteavw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2yskuecbq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qcipaaba.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2lurqycfr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lgziljum.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2cdefltzk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ldybnbrk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaplnwpw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxemlle.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmudlag.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjazgxz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oqaimkoo.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgwxubm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmeeuaio.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ouldyjhe.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfoyplz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjnjbrr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsofwjbc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvjycmr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zezljcqk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmskbfe.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaepxowr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdltojw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xiryvkzw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2crglpurq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iblxlcju.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbqpjxe.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2syukbtgc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bdupfrps.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2awdrpaia.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcvdhth.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kummmuel.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqsswsp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkcsexl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aquayvwd.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2orbafyuq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjmnxjm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwlhwau.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2omughajx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bifpsttj.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2inifeswr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gghxbels.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqxqehw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzivebjy.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cqikgusm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrgdnsd.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ncevffaq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jedwcosj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2shlypmzj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxzbtsf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lutkwnvk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jscgqsze.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyyxvlu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tseucvbv.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aapnjoyu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2luzprkbb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2smqqivng.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjdivuh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdlmqom.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhdzqsi.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zclrfhzq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzxsfcw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mthraytu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fiobgrul.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2oibvfkoj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpzlzae.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbgxuro.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsxuzfb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ccufqezi.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmbjemu.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtqysuf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2haxlwgsw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgawawb.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxhaltb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irlvsrfd.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzhyjzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uskypxcp.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqxvhlg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nytuqsiq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2angdgede.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2legbfmuf.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbmipzs.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wgusvgao.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2owewxzyb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2agnwqmho.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhqmzpg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vsstmirw.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2sfllsdab.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mjspbocw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbqzpwg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfbgkpp.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfveuxh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cefcnfvu.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqiqpxc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jricpjkm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqxylvo.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cldvszre.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2oihsqups.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqoalre.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ejonqpfi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkhbrtq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2keffzqpx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2gykvkyiq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2llwacbjn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhkmzpi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcopral.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2buzmaajb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpdzpud.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lamibgkw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcswrck.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgwnzcm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2asevvzkt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2jccwmkww.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqdcsxj.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2woberemg.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhqhoqo.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrisasq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2whsutvvz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2glygzjhk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsxgflu.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eseamtxt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxzalbm.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvsohnx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrkintf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2qukhynjw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xccklmox.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2necvxyso.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2slvvpwgx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2nywvexaf.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjvnobg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rletqolc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2uneicjnb.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqpequr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2faodlkqz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhlbuva.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2iutxwbbq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2cmglsixi.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dldzgqpz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbqidjk.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2wocmdxcv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkjacmd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnlagxv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzsuyqr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wburnsaz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rijkzywl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcwmhzc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2apleqebw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcrtlar.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnokwjj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfgjsnh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyjxucv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcsicza.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2pirwfmle.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfbeveb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wbguwqhm.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2naloydys.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fycgctlf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhjsvrt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zotkfqsn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qttopxpw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jitcptqk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysinmpjh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsqrdyx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmpjtgm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2udczdoil.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfrxoez.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxujwglq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvfbtyy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2leigyofo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqsnalp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzdfwom.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2voaovlvp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xycsdgeq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgnfrmo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wscgzhvm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhytnprm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvqttgz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2idxpjqjr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fekdzpzg.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjonyvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khxqhzhm.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2brcsqfml.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jykbuzpd.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2scqgdsmj.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvfvgtk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2yenqdlma.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmqyjwv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2iojqgbpz.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhuoehu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hecdqgua.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwfxudk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mdelhfgr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtdpktc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjczjlix.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaxqxyo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdflpfl.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmvflqs.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dxguanzg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgkmffd.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tywrhyah.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqddyfp.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbdlkrj.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktygzazn.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkzzijr.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkioufwz.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2iplanqkq.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wzorpcve.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjifrcl.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2piktyjlu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xprnwkjo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gibaezbg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqhcgeq.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtgapuh.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvgyfvn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvozwdpa.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcxgbnm.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2kndanrvq.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2txhylcyn.html


<!-- 参考信息 -->