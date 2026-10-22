代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnppsin.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbplxny.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfooyto.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2frfcjmqa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuczhux.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qccomfyt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2sgldrkag.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcldigma.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qywaavww.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2luzfcikd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyyrihj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eunwucsy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mubqpzyy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lymyqnax.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmfxxyk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2balszmud.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2adrjdrfg.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wqojgpeh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rffyutrk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egzoifkb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxeiknp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jhilvguy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrfxcma.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uemprrkg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyzoust.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukisgakr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyrwhhl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pukozrqz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkamkbz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzzwseg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2coqvxjez.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjalnlg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlhotro.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxwubwe.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrgoaaf.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2idozertf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcihgtf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2egvkhuad.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2djgumpcq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrnhtzs.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyzwnzb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpeemuqs.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkkdnqq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfeeruat.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvmjbrc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtscdqt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rctxidhx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrliiwp.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2clxbbtep.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsrfoif.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgphstl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2usajqdmn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vxychlyg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fevuwiuz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jasenelk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hejczryf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ueezghdj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vznrbjzy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oqechmdo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwrsscx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kavhrctq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkwbgiv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzrjsiq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkfxabn.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tewnnoep.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkwjoek.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkxkxiz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvcbxty.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sydtpjzf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2safjmxgj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrlvgrm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nomlffgn.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2evisxlpc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqmcobu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2enpvbbyb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtorvnj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2hotdoqcc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkmegil.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ikojhggl.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfqwres.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2isjtmorb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzqjgjy.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxmkgav.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuwaqlj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2oumlrdhz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcvktso.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2gkezybiy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhtvlrw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qimnfbec.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzeyluj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2oxotmeug.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxptykj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvhaamr.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkgknjh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzmwizf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ptletfcv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2geobwzew.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoloaphi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvizjxn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbskakw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoovovr.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaqdnad.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dclncnuk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuqfzbu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfqwwhq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zssfpyeo.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2spcdaoxt.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pquetjkq.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bwszqhyc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ovftykxo.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqawaieq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeouydf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhsqdsg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2squvhsxp.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsixowo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpepuzk.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dqksovya.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2esxqpdza.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmutduz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rggovjwp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqxmvax.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wkabmkaj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxvpmjt.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkgjzow.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aembkruc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhygcyhy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2gnslctzd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnxninx.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxlbrei.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvbbvps.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrlsynn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmyziqh.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2blocrmii.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2izkkauai.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaasyho.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqxawpw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnmghgq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkuixdm.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vumwepyw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2txvlbdhv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzqmhxd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2korpygca.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhgnifp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnegieh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2oabprtzz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgwqeyv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mixzsrds.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qelgwmqe.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pemhvaxa.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrdnuqj.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2htfvshbz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsahnpe.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wofezdwl.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjdbbnt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2oziqzrxn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhozkend.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvkcafx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgqxxye.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkzzcby.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcyxaru.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtwzkzn.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2upmpjubd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2kofsecrm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxksznv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yocznsrt.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2pqeujiaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aztbbsmz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2hhneapvz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjjedjl.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2khxzhtbh.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nsukoqks.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkxdhav.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlihsmn.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wuitrkbx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbxjayz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbzlqgg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfkiorb.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgmarms.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2agnhemch.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyasfqh.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvsrlsa.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ukginyqg.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhvegkn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uzurqkpl.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2clfnyzdl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rkksufsa.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgaivau.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgjrnsn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lwquvhva.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gabubnga.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pidxhgxb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgjljsj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2igoayccw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpebqna.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ftugetfh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhuaxyn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zeenpvro.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcookha.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dknovioi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bspggiff.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kybalvck.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xcooigrz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjmohea.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsxyoak.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtpdwol.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpitcax.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkrzxze.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpydwrx.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2oseehfut.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjlanfd.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2iokcvxww.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwabkun.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrvrxhm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqnuqrt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbtppac.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmhxhug.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoixuzq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ftotqkpv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xzunhtke.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyelskn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcnkcmo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2iychivmu.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2liecdgcl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rywqcagb.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2aimtyhdm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2yorervmd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2puezhatz.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2uadusfzz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhrbnge.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkxjbbd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjrqzzl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwfnyge.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2einsrsvz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxllllz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2losmhbot.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeunbni.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2alujbere.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdmcjuo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2gegsipha.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlfyoqc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbxjfrt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xqebngwu.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2aehsmxcz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2cebdgttr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xakmgrfh.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2simihwbd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xpityuko.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbibrjpz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jyttwfyr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpicxyeq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzthrol.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoiuavy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpvuzdm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcjjpkw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtvdriu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nukyotuj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aexyttvc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fctkzflw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwlhdbo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2civnwcoc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cynpketq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgpkvef.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jambwgqz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqnzqzc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdghehia.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zssorhuo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmspamqr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwhgvvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xomvppka.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcjsbhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egrflzbq.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2icwzjrql.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2skeusrvt.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaeqtrk.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxgqlnv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbzlfqq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxysokm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqzovyv.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeshyhz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jophbmym.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbtpwak.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bdikyjfh.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsonfqn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2prlqzxuo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcinwvd.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuxzvvo.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2woftifbf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dygwedkz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2urhiaekc.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2drymogwl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ledwsylc.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxxnnsr.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfsygna.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngawyulc.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2naahjbly.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqddgse.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyxgsvs.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfzxabc.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uugkccoi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgeovxl.html


<!-- 参考信息 -->