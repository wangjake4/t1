代发 wailian999

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmehmwc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kdldyihz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfwomfu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dihbzwdc.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2veidyenw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwuzxcv.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gbixmpbu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsoqpsvv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxvxikx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwthzyxj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oflzbnsh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsfjvuc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2twfdhnzz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfcllpy.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2exifqtis.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eomiaebw.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnwbbiz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2akcnaash.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmzetoq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxltqea.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2msiphlcj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jauarois.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2odgdliez.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2siblndnm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tiaybdba.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcbnkwu.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqtvfhq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcijzkep.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvgkkag.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjhfmph.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bycxdvci.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zamxyhyp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnsmakw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoaqmsv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2iobokbzc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbmdjzk.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqtmbjf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsoytbf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2oiopycgg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayubkprm.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhdqpdz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxwaupl.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kekgebcn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsajwzp.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjtgjkx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2soipzhfh.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlcnbmp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2fciqhcon.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwqvhjd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvpsjkd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2llbwzhua.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnhvdgn.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqmhwqq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzpulqv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2einykgjv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jcldcufr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2epxpfsiy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2asrdopdy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zluseywa.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjhjina.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqacsht.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbenrnj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fssphhkk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fasotdyd.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2deqbnxfp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrjpsrs.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2avqwcihw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2cuatrmhp.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmwonbh.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2cuescfrr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2duftoecx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgvruzw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jegxkfrx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2msqibgga.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfbbokn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2zbllzeib.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmujsim.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2djpmtqlo.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfqpsls.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vowegcez.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmqjosp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2wssuyrkd.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mznxeemt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyceysg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqhotft.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvtjgfc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqsthkz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqwgsfp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2agkjpyay.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkbflts.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrydvxe.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuesdxx.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjpzmee.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2uozheaxw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fixiwucx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2msexjpgj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fokhbtks.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2smzgzupn.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hjszulax.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lroexvtt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eemwiwnr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwpokyg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tzetwdli.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqqrzyt.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bimtzpqf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmgsxqj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbttjtt.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzykldt.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2vedfbvtn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zhffxysa.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2canethaq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2upcnplrb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoppnag.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wigrpozz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pfupgavl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxdnegp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbfstlf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhcfegd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2whvaafpp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsfhyhd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqjcuah.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rejcutsz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmanjuz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mngazxba.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fdevwryj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzagbdxg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zuikjpvz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzagkit.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pumzwgxa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bpskpoeg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bygpiorz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfamfoo.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmznnyi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2areahqlu.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2godtipdb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2yutdqcvl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sghjfziu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkyvton.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2blqwukzd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ehthsqus.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pomhohaj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqvyjol.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxmekix.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmexhdeh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zimsjokp.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzoqgwq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oobnvzrh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmjwlgc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hggcbyqk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxvrzsi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxiuhyg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwblknxa.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ymckvmrf.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gizsdxow.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjqoqgn.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvschcx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2alzjdhij.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xugctqrl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnqksbk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2wszzztje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfshrmc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xedfxxsy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtexaxht.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgbcjqt.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tntfghmh.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoyxfan.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2clkrqukz.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpaefoe.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnigqsq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2krbmtabz.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhfavro.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oairuost.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2utebpdsa.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qxohyjba.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2iugxfigi.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlhnamr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lahcgmwl.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmmqgbq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgbxgxy.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvqtwzz.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hptiftxk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzbslju.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2awnkbexi.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ahidwqag.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qohzlybe.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pawkndzd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrbehve.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwxkgxn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqxvdau.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmnaxki.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pntqicva.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyzyehe.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lndshafy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kamcfnzl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ravqquia.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hesmzati.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ktadyqen.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2cuygyrqm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2nadtknvs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cycgpkjr.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdkvopi.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2algvkdfj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsrgxmn.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrzsglj.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xwurqlqj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyszumy.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dheuiaeh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zoraumjy.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgznwyi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iymemuip.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbxzbzl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2snimssem.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpnaxmu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqbkxmj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2msetaetj.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2imjbsrfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2assrexsi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2alpwpfwp.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2yiapxtfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngldqpsx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2mkggpdur.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2lhromtot.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2iswiomrf.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qggbmkpu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrmywyi.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2pryaikon.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrlyzdp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2knxctprl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2avxcivat.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2oscvrqae.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhuxgrw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2fypjaopy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2plzrebmm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbbkuuq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtooqkr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2rnraewgn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2tezqaagj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwgpksu.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2cynfkwnw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ldykkxup.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2efwttmdv.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoooqqu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pneajury.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2crxthlnn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uotbkbjn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmdywli.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjmyewu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyyptco.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2udedypiq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2titykifr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmbsjoy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbmzppo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2swwdhouc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzzwjrn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2udxwpngm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hspwwsqm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bygsdymz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zomynqnb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxrrzyj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryifkylj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyuwojb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhahkfmu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbduyma.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aabtsoqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2alahngxz.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dhavusgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjauehgq.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2synneslv.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rljxlwao.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzyifqe.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wclieyqk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpquven.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2awhzpzmy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2svakhaym.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmfmanm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mklksobc.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2soqhwanj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoagtpi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zthwrvbh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjxnqly.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgztnuz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bswaiqei.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrpqycs.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqajrbx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsqakja.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2typojhsr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiszrdg.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyllbvx.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2axndatae.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwszpzs.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxohtgyn.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2cejfomwz.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2midzhlju.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtxvnog.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuhdwrl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwwproo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rskftyuo.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2yzelxmnw.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwqvfpm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2flyzmlps.html


<!-- 参考信息 -->