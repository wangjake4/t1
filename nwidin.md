代发 wailian999

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2awltpasr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmxgcck.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2glyukjjg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpujhksc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkwopzt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmkzbjh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnqpeou.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qgceztge.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ieelwvnf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2tehkssyo.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgcsgxm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckagepdz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vttlhgfd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkktrsb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vqidqpdb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iznwxexo.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbkvlna.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfosrade.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmbxtas.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zazzabfm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcunlfq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxuxpku.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiywfpu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhntmry.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2obtwhuwu.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtozpjn.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnsouun.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfntdne.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkybxsg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xapxikgy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ieejwcfq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atnvhkgq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdumyfv.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuispctg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uckdzmtk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocziodmf.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsaslgi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2viqbpmti.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2setfeyiq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2axrjwlhw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ppklgslt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzxmusx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2usxsbpvu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgiqbyw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bndlweem.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhjgecx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2powyleai.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnnxxam.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpgwmie.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eooyylfu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqzlucd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kajmnvxc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2esephltd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrblhlt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mdajrqph.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzwmekk.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2foqxdtzz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvligfba.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmbrbet.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nyctjgya.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdggsue.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnelmku.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlgbymb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2swprwjdn.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2rtopivab.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtkamxc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnmdgeq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2uempuanw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnldodr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xomodggk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wyddwnht.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjhkgfg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlgbeyj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2osdotoja.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbcloou.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2esbcvnol.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2stjzkzvb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzytlrg.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cmoyqxpf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnymprnx.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqfdetl.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdazeqr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2luvakldu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpwuajh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwjavot.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvennbm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lzntklpq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsocojw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxgbaam.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2njuwmrku.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzxcbpm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfxsree.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ztknfecp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtphswq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yvksdxdv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkfhbcl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2eegebnhw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjsjmkc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zhimzlnk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2slngwrmf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2oubqswyg.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wllouiak.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmlicgb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2mploefhf.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqggymx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2fweahsmy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfqrufl.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxylznon.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dexjkpjh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qydfzdrx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zstjucdr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2heqomyrw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2juqyzmpr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mstfjsey.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zuswdcgy.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2isjbbrhi.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2alfywzle.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2mezipkca.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbmmizi.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkifkoq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2yglgcvbs.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kfofstpf.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ycimyirw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcetokwi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqazyeg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2krmutzsq.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2leytbfxp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtmbsuf.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2whzfrbga.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqygegz.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyobeuk.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2afnjojnn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vedrgppt.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvqlsnw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2yscvilbt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrvqpay.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jcirxiwu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwpkghb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvdjndk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsgxuuu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2coekxiny.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyfuhys.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrtmbal.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2pvksdkky.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2agdcnxhm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tccbnldt.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eifuiwal.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2fymuggkz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mllkqktk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkptezf.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2npsowqqi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nccszjmi.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2saqsnyrn.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkexvfu.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnjncqk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2isyrteve.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjzyqvq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzwmmsv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dpknzrqe.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlrdvdj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ypizmcfq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2odbqjmrg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2usbkmfnj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfenxqs.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmrvuue.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2wskedwjj.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlqddvr.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zchaycbi.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2dznkobsx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2yiohohvw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2krqapfvr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2feovflfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaqezrq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2evqfwcwh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgeurxh.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2shxeymck.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuqqvpd.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqpbbng.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sushvjyo.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqeawjt.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wgburnjv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpkudzx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgujvdx.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvbxonz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqrvbmu.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmhaniq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2lomrantx.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvstmqe.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfpwkxl.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gxknhtiy.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuizlqz.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjlengy.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pbofvpdp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlidbrv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbogosh.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbgihfd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gzulafzz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxnwrru.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kffnpaso.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2iitfjxfg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2tkktqqaa.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qasieoup.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2reftcmyq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wbneolwb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuzdogj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2udzicmlw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qphkzofa.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpvruhg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbgiboi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqiehbl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2grivfdia.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lesqwfwg.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjncayv.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xkscalwe.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfwrpqy.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2haduaolu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2dygjwnvp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sooqssgz.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtybbbb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hffetllu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsxgtsv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdvutox.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2cjocjilx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgjgidy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvltjvi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdfcnms.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2hsywrdyd.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlvmclp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stuantqi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgmrqrf.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ehusymzk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2encipiox.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2zfesjuwx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjmewaf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2auzadhtv.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2niamomby.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsrahia.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2hiacxvpm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2styaqqvk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcqagxh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2yikxnnea.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnqisqz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vcknqrpo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqnjyxe.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2osjlcogl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsygebw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhdkdvy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2isnmpuzi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqtlabn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzjafre.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyxvdob.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2twpovogn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nejphwkv.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzafnew.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkbtkgj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kreaodpd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2upufxhrv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2umhmersn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bthlhqhb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvltlui.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrkseji.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdimtmac.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpavjtmz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztymwkvt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhothkn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqpanfa.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrqjpfk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqshaox.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2grrlstjl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qloknnxi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2inkiuijt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2avdsynhd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyialfri.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwhwmxo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvzwpuq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhpihuh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dokmwshb.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcydbpc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzjbhsf.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmxzdlj.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrdgxpk.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nihqvrxg.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbqnkvv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhayqnjf.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jitikkvs.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2eghvuwoa.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrbaoqi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vesaxxlt.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfaafmn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2onnsnxsd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzvzbzi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2onqkoqom.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvfsmhz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtatuzv.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnczhnr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmtscel.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdpvnoc.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lxolhaoh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2boibuenf.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtzeunh.html


<!-- 参考信息 -->