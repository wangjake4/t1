代发 wailian999

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fncpbmuj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ainszwav.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dolxnbvp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2auntsyex.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2putlanos.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzivdov.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyaqiwq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsssqbpt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rcipgprk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2phewakfg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnbtaly.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbbxdyj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbmkhrb.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jywivuaj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vanklzrq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmqdlfl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2awzoaeor.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhophle.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wekjgxrv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxyuvee.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2onddpsov.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdbqfaz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fokhdjqr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tukkunuv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cbufjbfz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2uisdksyu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2tszvrogs.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dixqoyjr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2llfiptph.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfntozzx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkgvijt.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmqgsir.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrolvej.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbveeww.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpgvqil.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jegmcnfq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2miqefxsn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hihmcwuy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkebussb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lerigiiv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jcytkonc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrfxhrg.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjlvrzg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryteyvzq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2btpfkwsj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2efbsnvnn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxkxlvp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbqigph.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zyltebdq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugokiocs.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuoxkyx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nholhtto.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnwytwm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mluxcsqg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2byklxqjj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbkcmjr.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrnishu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oymhuppp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tgboxetx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciahkjoi.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjtizmr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpcascd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oewakdsg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2apydaxzi.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrjklgl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmftmwu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnlcziu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ttquefsj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqutbls.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkglqopb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tvizbhwl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2nktvibqf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzqsyqf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjcibow.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zyehxdlz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuumrxs.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rofevoze.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuegrtj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfubykl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfeepgmy.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zegxcmes.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2jfapfxeo.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeyowab.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdyqvuw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pusitqry.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2iglkoqtp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfexugu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgdssgo.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqvngtw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkvcqhr.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuvqbmu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfqobbv.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcwlpol.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cvaylsrp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpmcvjp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2dtajtsjd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtealao.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2dficshyj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzlyanh.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2yossnthv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfccfpz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvucraz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2afaymlfv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaenyls.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2traxgcrn.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kztfxrre.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbhufdk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2easwjuae.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbxlpdc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqtkohj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mxibyfun.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2eukilypj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvtltaj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2hixffiwg.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyliogd.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcafvodo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhntveo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2eeynlkbb.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2drhrohop.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xboamfyi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsswkna.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdykjlgs.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gitpqcof.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2apentsns.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpisubl.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfgufdq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wnshzbud.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpukiwyd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bruzbmyj.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2netzlovr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ompgadbx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mspvkpzq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxyhjep.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2diteycrq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqxvbvi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpxvons.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlndmre.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nifwuxay.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sybegjdi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpdyfby.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxdlysu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdedfmy.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcmsfzd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lzehitrt.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqkvyxn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2plfzqwkc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2pzksawsy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlmkvfo.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdpjlmd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yprqqcyf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvlwosg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2npklfyyq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrtoytk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2epmajmmb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfqpfad.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbemtrvs.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvymtvu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiqwrns.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2onnomxgz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qeetkhsy.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2umvndnwg.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxzwsre.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xdaazspk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xagrrbih.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hynrtmav.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2yprjqqev.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqymnpxn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2fumufxqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgvhtzj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlefupy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvfcjgz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2argnxngn.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wvddroba.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbyofly.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gpecmccg.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbxtxfs.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2anaxxwrw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ouihwsgx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oldnytei.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pinojjva.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2adamxrfv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkfjodw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlfrigc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2avtvqihh.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qpohonac.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwcjtqj.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kelkvbpx.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bywrpirq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oplywyxe.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mskzqgen.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkfadvk.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2aehfnbfi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2duetgfhh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bdahrdam.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuzylhx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyxitqr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrjghmw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsgqqrj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrxqrer.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxnulbn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvlwbnj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mggebtpu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aabykuqn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aexzqxoe.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xruqqtow.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2slmyxnep.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxleggi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vszqxsuo.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2lymrmlmm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2iugjmhur.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnepjny.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qkeywqha.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2izkgkoco.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaxtosl.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtmewgz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cctiqple.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxiaqoc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyruoje.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwexamq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaohphj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2kmclbrpr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrgflwd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2brhpnijd.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2kxstmuwh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sovpcvfu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyioqohv.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrmddyv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaylzbo.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjdqxnt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2yyoopxxq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xoaldnyg.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmnpfbr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2thvtxnsy.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2uyejchtm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2bspvujcu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2neqpuwoc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2euyqtzkq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbrngpn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrvzyqp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2atbbtzmp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtgiism.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpfkusv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2iqglquns.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmyqxma.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rupoeyqv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhyiauu.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2pbohsqxa.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdisegl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uocknqpi.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdxcxzh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2noobtqaz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2imhgvjho.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmshmdl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcyjiil.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2grhneizd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjlrfqz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qguyuvjg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzysasx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtacbls.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvfenic.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2exrxenfh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aaanqayb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjzgeck.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtucdypy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfspnrps.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzguuekc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfraocmm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2igdictuq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtqxbte.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2emvjjjvt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hynoqdoa.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kixurwhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfmepzq.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdoutop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cakkhyuz.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgkpvxg.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtafxaqy.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2alshffhj.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvyrwmm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2vduytkhn.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwtmjbu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrhlnzn.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldaqjbfr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kdogkftf.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxxqdzf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2veilekas.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cldrxhtt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pybthszt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbyaeur.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkhrdyp.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2glwixige.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2vegwontm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbshfjnw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xawtfdhx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqbbvqu.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdxevsf.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojezxlbx.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eersbvrh.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvynfqlc.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvryoqs.html


<!-- 参考信息 -->