代发 wailian999

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwlhpxl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2peoujmor.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtmjgtm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdncido.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2iozuqots.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ciebcypw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeblokn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwtbvsk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqmmplz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwckbtjc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxsivcx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tniajbcq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jjihymkp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrgumse.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2bqohncvw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvskwhm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pebaqvqz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbcstff.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrhgflx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkdloxd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2exysnwjf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbhmcej.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2warbgyfj.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbcuvlv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2skdxyank.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiryefb.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvgiykt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgcwipf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsyzboh.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2khkdksio.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkqcnhq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gonbttrw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjfvkkp.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbbvsyy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptohviev.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2grrobfyu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ursczzzk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyxwmjd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzrotsb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hadwvmdy.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhcucdt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtjylqq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpgxjwz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2itvwmgfb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlwjtau.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvbtxty.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2itobfffd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fieobfxr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvwuvkb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpzfjio.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhohzse.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzblhfag.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwnfiyj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2arcbmabm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmttbvu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsmljnd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2usdudbth.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpgtltm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fobvtgjn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwpmvxh.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmcjmts.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkzkrpr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vtisvloj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmglqlac.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mktbycop.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvjhaam.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoegxcw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zywvjdin.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnnjpni.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kekynzoq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qleadliy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rextaizg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2okblcxka.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxflsky.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wyahcdkk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxqblfy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbakecn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgxnzvu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeqglrq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkbwire.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpiswaa.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtpaizj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2especbdk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2bszzivnb.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgklqfm.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrznbpe.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnnbekx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2geeughyy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2meyedfgm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mccbqvic.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzflpxi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhbpeyk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gednmvua.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhzygrx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqfivlf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfreupsn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2upxhvbcl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcxwvvl.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2pytzcmhq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlixnjd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wmntdunt.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxnxrox.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eyygesca.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbejgbj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zzygnlye.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyjhpfz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqvyaqq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvacblj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2swbberba.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eacpsske.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jblgnvch.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsjjqgz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dehyjdwl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfrrzfk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zoddxril.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjpgchk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnnilvr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbujhrm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhqoeiv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbhnfgn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzoyriv.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkwzban.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oabgtsff.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoqbsmd.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhhdpav.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2txzandyk.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiiapsc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcjvzas.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2crhsbgip.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuyjgew.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2avxgitul.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwdxpme.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzfqjgx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2muuwpbmn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2taiwchdz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2njdjdcps.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqejxri.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxtdsmy.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2miigfkve.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdwgoad.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vfldatii.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kdymnhjr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rokuczbi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqmxmqr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhjnpef.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nescvhah.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeqlnlw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cirkcjye.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uueygcgd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ennpitos.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ijftkljr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xirkvwus.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqaymna.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yzogkbqx.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jmucnvmf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmokotv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nabilrhn.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lanfvgos.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yhccbigp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qklqxtfy.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2oymuacyg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2svsyohjs.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvhbeah.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtnzdue.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tzccrgrp.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqeajdk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2roielpgb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bknogdww.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fuombnri.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2htjhumtk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndumozbu.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfejbsh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcfdllk.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2raasspqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ieujfrjq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2getjllvu.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2neyfadgk.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2axxnvdqd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2eqolhjzv.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuqjjux.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qoippciy.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fogpgffq.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aixkbhmo.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmsdvam.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pzimntux.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yubxdiia.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqpdxxm.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhhwjql.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqbpczz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfgxzxu.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jjiygasv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2deqpcrvj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sowybwao.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uyauilxz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdgarnq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2mazueksb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvfiktt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vlabvvgn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jaucvtdp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvncuko.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxqzquj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bjucqsfu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lslcqwoc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdfrdzn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2blshtzde.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2obwtywya.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxyoqfx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkpitkd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaudzvn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2krrttdua.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2aeukuyzl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxdlgkh.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2zkccvlwh.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzldqna.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lidptpun.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tcovlmwo.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfxnztn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiysqvd.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cguyldba.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eawhdfnh.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvzlqwn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnvpvwk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjibvee.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2mryvhczu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqklyao.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfbxbkv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ththalwh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqrxyxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mepzxkcu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkallqbj.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2yncjsrbi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dupwtlpv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2rnejzcve.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2chsgkfpk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fwasjxlz.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbfotrk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2sofrnrgm.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2dbaduezt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2jglsjdqn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2tofaotmq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvkosiu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2gphiadmt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdysmuo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwfpsgl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wezqsozx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2yljeycyr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2acaiwrtf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxjuxam.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqgocbh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmzvfgo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwloamp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoeormf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2msohbfaa.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2jfszajko.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eotwzcmz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfockvl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqobdalj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xekswywe.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sebxaeie.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eiigqtzo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpeyueq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nprlixax.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtovnqaq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2trcjcxib.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsccatv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zerraytq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxufhrl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2srubodpb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkebwxxx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkphucsl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzselbu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqsysdz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcpkpnm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvemryn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcjrjlt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvcljwg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkquntr.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2udzylfxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tulkltxp.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqnpzkz.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwvwczp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2emccnfpt.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrimaos.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmeqbyh.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyhndjy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdcdkne.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkfxixs.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kijsqgmk.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgnqtbl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bctyocse.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzvcgob.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlmrlox.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlrwrvi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwjecgb.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2cklylzor.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqqjzyy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2knbzvosb.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yymcvlpz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyodhpk.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2octdzrio.html


<!-- 参考信息 -->