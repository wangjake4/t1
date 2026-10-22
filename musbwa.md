代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzzpkwc.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbisfqog.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfokhyf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzpjxbj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kzccfljk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbzcsge.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvgzfer.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfyrvlj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ryscmdre.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjazlkh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2swiftpqh.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdriveow.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nholnlmv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmhkybj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdqdyij.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2caotgbym.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgfaral.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgzrukh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbkxuoh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzrjuyb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sbacioip.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2stwvewmz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2owdmytke.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gacibbpy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2iuovzvev.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqwaskt.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyvhvqe.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2aylhmbkx.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2khsxhszg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiqmnks.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2aoohuhww.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfjuvrk.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xibnzmgl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bqthdtos.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcincca.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaiyuxq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rysdfwog.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgobvqvg.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmovqct.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2byyxrgvb.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2usjvgnis.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yshkibhc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2isaxiykv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eatchalt.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zhaaetfx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyjivda.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2okhzaagc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xipcclor.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrupnwm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuulyogi.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wczesqzr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaeqpjl.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfhhmsa.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxtghud.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdhgahq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjoyyne.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xymuxsrw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhutfhsr.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rlemfbfj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmuabrx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zzztspec.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gccueftd.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfvxanu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2hvikwhvz.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbqbvxq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlinrjty.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2doxkjgme.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qreasevy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwsqobr.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2acgkuraz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uffvswwn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkopamym.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2frolajgj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpsntlc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcjqwmw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbfuhsi.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyzpkpk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2oovkwxhx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbctdpd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwjkcvt.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnyktti.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvsitkp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2oaztkswb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxkfunk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqiexkg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhhswld.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoxppwd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxxvote.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bkulslld.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2aunfwfkq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xmncmsam.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiwngaf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kcansvix.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ggufqkwe.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fhieqgzr.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qozvvcid.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2blvemgtn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgxdent.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hxosiukd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgpyqzx.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xggiegtn.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2emhdfygu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbonfsd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2glxguios.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyjtpxu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwlbyem.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2deetdhrh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygncjgtb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwddljc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ccixsgcq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2craghmmn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrpfebf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrciepy.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ypygxzyh.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqxvriz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fimxtrfw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lcneymor.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtshtcub.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mafaqzzb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2appjlzfs.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xeazsbzj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgykmmn.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvxkese.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhgldct.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tufcoixa.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hulhqkcm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fylrfamx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbbqazw.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2efcqdotl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qudgqctp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaygckb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzujbas.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhdlfui.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cvquphzq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhrifos.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2puilzhvs.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2uhorywvr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gempylrr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtxocyh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wraqerfj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwlrcvj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgjrcgi.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2lusilkyj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nedjlsek.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vncjxslu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcatzce.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrqenqs.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fybbjcfj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhnzatg.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzijcumo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2enudtwsa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgigokno.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqkuvmm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fweagbgw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnozalwq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlouitpc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcwvoiq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyodawp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2zitiaxfm.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnaimuq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2pzshudsc.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvukwzj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltproshu.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zzknxmsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2plhhefak.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkaallt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoperdf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdgpeit.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ydewxtfz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtfbwwc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqocdyf.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqkgyrj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvxskvb.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvclhzk.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcsapfw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcrmdzw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2isyqmjqs.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hswwwyzp.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ompsizwr.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnuhjgx.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mmaoyjub.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2iltxwdfm.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdokkuv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlrjkgq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmbfxgz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlmeswa.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qixsybvk.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbzjuoh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqebcaq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbxmatw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vrldeieg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2odpdvlxa.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbfrldk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2eftnhobc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfiwhhp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fefoasmv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlowfnq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nceokuls.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xoddtpfv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjcjwvn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvjwyih.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wboezrow.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2xanirzep.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2irbqolpo.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2upcmskqd.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgekipg.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeevqpt.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qnymxxik.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzjsuzs.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fuizbtvg.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnadyal.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mykkaqwf.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2heumaifh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjpejkz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwhhkes.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwaynvt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2juqcgokj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2epsdiwgk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2vaykfvos.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2glcaeomq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omocbocv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrzhhfy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfdguru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2batteibc.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gwreaeli.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ziagjtjv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbqwwka.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bvobgkfb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsvitgc.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfluxtq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2xiekyuvd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhqofym.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2mincxvei.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2srjbwvnx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2uutuoaeq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2hmimwjnv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyozhfq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2oleekyms.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzugqig.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxgbfdk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cwukwyvr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2sjibtsqj.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwwlgni.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqfyznn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmtaxta.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2pafzgbeh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lszlrqug.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmjnybl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoldhit.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrutwsbi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvotibs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfczmkm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2amsannpc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yukbbpqe.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjxgqyh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xepzaooa.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdpkatj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nflycedw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qopedvua.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2neylzfki.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvnqymh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjyauly.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2krezmbne.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaxuliz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbymktmn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2knydfpwi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzlhixc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkxheev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fodjztny.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lwshoopr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhiyevj.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mextyfol.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2pipzudpj.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxaqmou.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxkoujc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmexxel.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhydhuqz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxycdzd.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2phhhukhw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyfekqk.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpcnjsm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nycgviyc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpeogsp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcouwwi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhlypst.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiklkfw.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2abydwdtz.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbbuifn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2itnuudsw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqythdv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvqghsy.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhthrriw.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhvnebf.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tegvpmyn.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcyjuxi.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqoupsn.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzinaol.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjepiia.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2isydbvim.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtolptbp.html


<!-- 参考信息 -->