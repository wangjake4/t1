代发 wailian999

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjpcntd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdksbhq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqownks.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2whqkepen.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2elreoyld.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcavzhk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qklxkscx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiiljsf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbfroxe.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjvleme.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkgfsbb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqcrlrf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lohstlbt.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2irjjgfuj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnllene.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2thvvqxzz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzmenlz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycizrbyv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ageciqcx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpqkbva.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzlspcy.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xsftbisr.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuzqxos.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2taedoxrh.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfzoxyj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmztihq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrktmjg.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuynjfj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sobcarmv.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxfncas.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrchjsw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhachbjx.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ufaicljt.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjpyxpg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaqnhht.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqyppyw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoakzey.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qfniotud.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnbtakk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkwsraz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiqlmmg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfrkdki.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpzjhbf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgnhkat.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrwpkjz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdgcifa.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcvbxhr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehodugyv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxdaiih.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2isjrxlrd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ochquyzf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2addmszzj.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2azmkfwxp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyuxhxj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaffnzf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjdgobr.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwuyulb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gglvpmby.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfqyekk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyofsely.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vorqvoyi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2gezbdcyo.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxewcgx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvdvqtu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2udqvemse.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmudpeki.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2srncbhfm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnuxsxv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bhggihjl.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkcqcfd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qljernzu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2wafhnfyd.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xkejwfyz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qffhgsvw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dbduvpsg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgzwudm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pgklwsmr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uszxkjic.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyrwfxp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxztzhkk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcsorvc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2alhandvj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxayuyc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2aysimhnt.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvcfilt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2kopcvvbm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hjydldrq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqrflht.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfsrigw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdhbbwg.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiirgxu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjmopiq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxuupyn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2djxgzgww.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2mcryqvxf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmjqupw.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbzvofz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyvnekn.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbllyyg.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2aeldbbha.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkcqwru.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yergzogv.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgnzkxa.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvkptgt.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfkmqkf.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hixgbftr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwhctxz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2frnpgqnk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsytvoy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwpjewf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2irowwwna.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2azyuafzs.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nicxnkol.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvbkups.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlcskad.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkuaqcx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmixydg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdmruia.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hnklfumk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2todfdgby.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgjzkbn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gruewrzb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fndvmvzz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mciztizs.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2petfqfaw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrlmfus.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2esoobmsf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2adsbaahx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgmkpor.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2szhjodhe.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2tghczzzj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2cpewiuun.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnuezhp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvpnuia.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qemmlnpz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxvbvum.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2exsxekbk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wayyeyos.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2teqtcuyt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qucmslav.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2mlthbjfm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2snpzqsrq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjrixxy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbjdddy.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqwdkwf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhfqndn.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mbeaiyul.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pumqgffx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuieidj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zqavardh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxnazbg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpbwypd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkvpalt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2buiyoeyy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjcwszg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2frdxubvz.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kxutkkoq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpzwlsf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvmhjgm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqjbqow.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2egvuvxwx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2nufmjzdw.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvbovxs.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkquwmw.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mssyuqwf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfdkapq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwimevl.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2hxihsgul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lysfevqr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtnxiub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnoqxcw.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rvointbw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pakfezwq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cyicgvcq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2aihxerul.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xgifouio.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2anarfmot.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdpowgo.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfyumua.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eeynmkag.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mftjrpcg.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzqsiue.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2odizvuop.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tbagatze.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kidbpmbh.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cscqimki.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2djddnppa.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqearvy.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxfrjjs.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dgltcwwf.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eeebfgbn.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxjwlio.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zjswplor.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzujstr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbquraz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qmozymbl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ngncylyy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2whwzisko.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yfujobto.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ypckttbc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqfrbey.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbdzksi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxpwffg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqdpwto.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzsugbu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ugikscjf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlotcsd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yeugeuxl.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2acxpxbim.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2cmypsqbn.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ssovtmfu.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tblydbiw.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2tegaokxs.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbbclxf.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2piybalpw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnejiuc.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgbiujm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdsdvyh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjvaqkm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2juxkcahp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvljupo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fodxormg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2lavqcmdh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2adnifedh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krvuksxt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2zesvtoxy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrpknxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqqmrsk.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyhqiee.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2myyjomgl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2sosgudks.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lacuufph.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2etepxarv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjddbna.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdvvyrq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2dusfegsl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2isxqueom.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ekegcive.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiamvwr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2akmxemvr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2bjaqycpe.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvpxqpw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvgmzvd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmminvd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmlqypg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2eedvuuwn.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2teuwbvhm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhysqhs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvbdhbs.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2virynqsd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oodylapa.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpvefkp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oicmyazq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlxxtmg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhrxoig.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2imotdizx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpigmsc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvjzqud.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaopgrp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnchkwua.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcknzqj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcxghca.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvqgxmm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdosfmrc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwwxntw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysntenmp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjkiwud.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gasdplqv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlckawl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvpyryc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkkmxec.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzkytxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qacizkgc.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bprsmdri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwphmpvv.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuxhxsi.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2anddovvr.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyztrem.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoqtigr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwldbzl.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2frmgvdpd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdcsktj.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2imjmryrj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yaupkfsa.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhqrwsx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rumapjvs.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pakcnpoc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmujskq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjakmspx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyielag.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzbfckn.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2espgnuwf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkzcivx.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkblmda.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhgfsvc.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2efjuornh.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aexkzhpz.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2efrnbvgk.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtxvdtb.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtcwsus.html


<!-- 参考信息 -->