代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mljosigr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvymsefy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgougba.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgrfsdc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2trysrvfi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmatdpy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvdajwa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtxsjwi.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2crknmctc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2akwvzrwq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2posrnwnq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2evhetoqb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiiyxvq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbjwaid.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qijkbhvy.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2glgyocpt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyjhhgh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2btthmhsn.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dperckxh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyldpucy.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hnucpsqy.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mfitkhkb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2aekafmvo.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuryohp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdwrzvo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2betwpfnk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlsdrqf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkyoqbm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qcebxdzl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvdcrea.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyjowrk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2aafralva.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sumfxxtd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvcujhx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vauvlmsi.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjmgeel.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eyygqycs.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2akpkivyq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkrgrtc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zirstyrq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxyhhht.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfpymfr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2olfnydfa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuwickf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zulpmmca.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhweluuq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxmhtyz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyyhgmm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qiruvmlt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2axbdkuol.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fyllmdoc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2flgkxmfg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hmehctzr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gybtvuqk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jyitdfpo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcnyffb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xvezdfwa.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxixfcjo.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zshqbqoy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnfcbka.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2enaxbqxj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sadyodgr.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhosuxn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xesdircu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tapvejjl.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bovxuhpv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dtszwwkw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2udjtlnsn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqspufp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvftyyk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qipshpzb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jinzvwof.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2daytjjjg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2iyiuuyvq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2gaazsfxl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlhhprq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwztfpd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2szdmjwng.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjlplod.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoywaqa.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2mghbjkub.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2eubvcsth.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vbysbtti.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqxvskp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpyqkfe.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqcofkh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcvvaah.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnloptc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgxuqzr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2brdbjlqk.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxxwenl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrgfphk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbbqfkn.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2awmxclwt.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vivseqav.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqmzwea.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2escysvcg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2maaejcrm.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvdlkwo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjwhvoc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ienicvpo.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mryrjrwj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oqstffdr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkddyzoq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2menpshxu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkdkdup.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpdzvpi.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdouoku.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2grqytucx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zlboksca.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttculisf.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilajlhfy.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2plixpwxn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kxliwirw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvexvra.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxeeieh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeknazr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdumbiv.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lwggbeue.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2osidhgua.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2esjioixp.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kiapupaz.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtriimm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaxplyd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kilfbejz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpkwjfb.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bdencovj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmqvqiw.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ullghatj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2oymufrcj.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ppeyaxyy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwwtoio.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2npdufein.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbewyah.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqttzgy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsofxgk.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdksemo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2puzkpzex.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhhsuyg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2oevgcwwn.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kpblyvgl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2galxycbw.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wuarpned.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnfksmz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhrwzdw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgomvyor.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcevpgh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxcdkgn.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgjzhqv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbytyaco.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpuprvh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pftzptww.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuvylzz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmddhepq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pflatgkl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hprcvftr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mexqgdcz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqrztko.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2znsbocts.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwrskls.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2krhweqsc.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2iseqwsuo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfslnhp.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2pompbder.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbdedza.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyhocjx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwliyce.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gutpfabb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xungvxxr.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xztwccyi.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pehyemlq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2runuwxsd.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhdtcct.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhpvhdp.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mypwfgkh.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrudqpd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlfwdob.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxotqjm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2tcspbvux.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rocrvxkl.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2izyibahr.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzeijsk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlbdqut.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ptykjhee.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2aleaeoxd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtxsxxs.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tlubsvna.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ttykpwei.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyewhqm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuiiarm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxzlopu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkistjm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzvvstq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tlewvrjq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2segrffep.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uybzzzbk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kclggmlw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vxutzmmm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2egpmqyxx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2grzzaffi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2faksyfhk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xemcpbdl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2sycjhxix.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yheshkwp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2aakfillb.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2arxnnhil.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfrsssu.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyvbuwv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hquruvrb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkxdrdf.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xwntorsp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiwpfbo.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2moldoime.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmmeitx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ijizmpal.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzocrto.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpofnri.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjklyin.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xghapext.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2sothrjsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbylilkm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnlufjt.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyibdwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfknodn.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmcqtgn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjxoxty.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2sbehxwpl.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqjxdkv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2jlogrwvx.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2uafezans.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2pzutegqc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbgybzt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtyzkvb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xztmcfiw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2crcgkeqp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpviead.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2exnyvncl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2mozovbka.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2elxagfur.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnnwhzg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfowrhi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgkcmni.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdvedti.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2josqzlfj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2megyukxy.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwjvant.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbbzhcd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjlkfka.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgboasy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2etzzminj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfpyusn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dznmemrf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbbidbh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdjuvms.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpghqdzl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxyhpno.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wajkgopz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihklhpdk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zutiitox.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxxaozx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhnjktd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wevmieuw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrulmwij.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbniyfay.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eimvytia.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2evzeuwee.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2srffryop.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwmvyjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njoghgdd.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jngreqbl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdyyimk.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxdqbul.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzjquza.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2emckilmq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2htfbzicf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2edqpzdjz.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2avcqcwdv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qocjgojy.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwpxoig.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2quiapuky.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkskxah.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2viumtkdj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmhnhgx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzntcrdy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2flvwdlyq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwholsgb.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsjfimt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wgukreyp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdguuprb.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbwmxmq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2gpckpuoe.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2betefyjz.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrizgtfv.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvyqvup.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2unfyolbw.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2cclhphll.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdiolas.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gztkkwfu.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmejuba.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqlxmuo.html


<!-- 参考信息 -->