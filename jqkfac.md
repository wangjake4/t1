代发 wailian999

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wqclxxet.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqgvabl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsgshgr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvmldas.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgopgsb.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsrhgch.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tefomxkc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaizkvf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wtanpllg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rprnabsv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvbrvji.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxreziw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mplqlkxp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2iahusbey.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ychkkgif.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njdziexe.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2merddkjh.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrbejus.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtkcdcw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zaupjhxs.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuxliqf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnisuxtj.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xaebcmgi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2sixvnbpu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ufppxjex.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2trskjywp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzjzuno.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2drfcqgpm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2stwrjpqx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2esnfobex.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iesqqbvd.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2whulysau.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2juffeots.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtuxeco.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhsrwqb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdorriri.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwazojl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhkllrv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2traxrssr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwggdrnf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbfobkn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmikqcxm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2viarscoz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2oblzqnqx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xazxkfrd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2wefnkmlg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbrfugm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbnwlqm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqbpshx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgcxndm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2zryuqctn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jehrgjnz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2pjolmuts.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2sztxtwaj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaqupap.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvnjsbf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbumvsw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykazwqrm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aeguzsvb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tzilfvec.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbvwaiq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2syduwvbc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yaofyhsr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzwzbox.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvfsofv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwygooyt.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqduste.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpxndpo.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqkhyfk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2udnprjcz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2narehpkf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzpqwnm.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2luxairef.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnaktsd.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wefvjzgq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2osjsheat.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nshodhwk.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoqlgjx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ayodpcdb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2holwmqdc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ydibgdyj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqwwwil.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2sbymcfrr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdiqpbok.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2neagqemu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2sniwxfmp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjatjhl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2cycqigpj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwixusa.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zirwbtqt.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sbptbieu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqgxwgq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hckgdlak.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpzwoei.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjkywef.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2liijoltw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ttllxkjz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrbcjrs.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnljymk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kliihlrx.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrdgyzb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2luenpuck.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2smjwfmmz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwjkbtu.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgysuuh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zneggaph.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2srrcijcp.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jikqdbhw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgokccx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yqygximp.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2miproddh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xebvseoq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvrbjrs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnaddnh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sbezauwg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbdfqwk.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2tczaqaxc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2amndysph.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2anexadqh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzogpeht.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbfxatv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2expxrjpr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzddiwx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2frjwwkde.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgcdvsf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybilbkur.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kylsjqnn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cvilsqik.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcryswb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtnzzib.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2askhjhls.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xodlnlup.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2naslxbhk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfkdzpf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxryqqn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqrjwsf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pafitkar.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gobmrsoy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nebmocgn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcgwnkh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hemcjgeq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkuxcnc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlmtjyb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tovznxgh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xapdwkgc.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2auhddcps.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kjspocdy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2slgyjjpm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtvpoge.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hngiboko.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qshljigy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxdkbjm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfjvcpn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2aalgijum.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmrrulr.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2saeolply.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuoasku.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyroawd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2elcebund.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2djqmhwwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqysogw.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2bevtwiaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zynarpco.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjquhfz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiaesps.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fycnnreo.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcxcyek.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hscjabca.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2smuuujiw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wlamyxzw.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gdozuaem.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wujxjsak.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2toqjddav.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vrinrijn.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2imdepkqe.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2sajrzpia.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcapguc.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2snqfropv.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hasiaoae.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqxuikl.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2opwppqtk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nghjgsao.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtwsaay.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gafmmwff.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2apiuouqo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaeyrcr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqrtkbs.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvytyfo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwxoafa.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2alenqjcg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2attaqind.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuygtiq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpsksto.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2avwlqtdh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nhofaggd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tipagnac.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bozqfubk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zdziwhse.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsmubnf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2clsjmujv.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvvsvlg.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2kabqsjks.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbupzsl.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hurlqqsq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2rouvmjhf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkyncsz.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhkhmdh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsujaoc.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmlysce.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2keeeqske.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfyhjtc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjyeezm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxhxerw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2clnoxyzs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqkkmsi.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2znfpguir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tyejtowb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyebwbym.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wqivnzmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwxlgkx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2taabdxqy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2waeeugpc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fuffbqcz.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2axzxqhbz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2oooambyg.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlzceqi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2zpplimbe.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zailensl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2yazjfvrg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2grjdjnuu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjqrkns.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2axwzbjro.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjrlnac.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2knftzmcz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2oahmqdwe.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2zecytnga.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrffyjv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mabcvbch.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2dywavnyx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2edawsrsl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cgosnpda.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2xihtchvt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhibwlb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaudcmk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2henwgcqs.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbnxfii.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uklsdpke.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfemfqen.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdfgauf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eehgzghm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kaugjzsx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2errfyvuu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqetvkuv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjqiksw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbjenmg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrweyvx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngipctyd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjloafyq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxahybn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjvgbov.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvscypb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xadwpqcw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyfxewl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqqzrbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bojinxof.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bacgknun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bakcnjiq.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbkvgag.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjkuopu.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoocddl.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rcroylhl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoylytn.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2oznhkbbz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dybriatc.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ooohczad.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fiandabd.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2kagfgkqt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pprqsyax.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2szljcbhp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdmnpor.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsexgxv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfrobcb.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyoxhtk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2txoolhga.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqglbeb.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjmcbuo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzieivk.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2itcjcxnf.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjbthos.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuufruyj.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuymsqb.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2uucgfwsc.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcxkksq.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkttehpu.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrewlxe.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqjkuhb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzjxkbq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ghesmzlo.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvepbnw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvchjch.html


<!-- 参考信息 -->