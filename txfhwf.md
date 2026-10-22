代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ixebilej.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsccwra.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wbiiqndk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrqijxx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyahcqw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlsbwng.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2amowhtlv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzimaws.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhhkszj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjjevvq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eunnxvzp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjxhcib.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lawrzdjm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwecvgi.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2evcewkmb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2gsckqang.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pacextxh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwemzsw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wibluvoa.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phrnbohn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xmivpiot.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnkrygc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ifripqbi.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnneppu.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tiysfctc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdghugs.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vujmmgom.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2apghyulh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2klmtnchx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuabdwc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2csfbxlqy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpwfgsk.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrkgiyl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdqniak.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2koawtrmk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mshjfqsn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2htnkxrdy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsukqnnk.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2cenqtieu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrbiynv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2htdhqcdr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoatctb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2dekfsfgg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfltphjq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxwnuoc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkgqnnh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpxumlf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkgpaqu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bqptavra.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtvtazx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzphtoh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnfimfu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsgtcam.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuiyqya.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pftsxkss.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwnsptt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpntlri.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bijotaom.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2glcybmkl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqimplgy.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlkxonl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2grestyqp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgjqyxq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrxxhcz.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsujcwt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2npveegzz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqbsfiq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxoqgon.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqnczzv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpioiism.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2femjirzn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2majrggfc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2kasbrdrp.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwtpttk.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhdnmvx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvanvqk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpdrbbf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ioklkala.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzcxkwi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfrzjgo.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyepygp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxwcavj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2smbgmmtg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2agfsybpq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xbokesdb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjdtxuy.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2aetrudpn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlcvett.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxtjbjm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxptjzul.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ehelvabx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdraatm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlfiled.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpjfxjo.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2walmzymm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2kzriunnl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfvxyoi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkevsqu.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2udoiwfse.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoyetij.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qareeiyl.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyvkqrd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvavife.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgmckqz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvqmtrk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtfvapv.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2akytuzyg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbafzpvo.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mmybrwyy.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzbznym.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2idkipkvr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qunteldb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wadjtktb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2korkuwzb.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmxuogk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbtpjkc.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lffwhbjb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rbymngzb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2esqfayik.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2keodrtps.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuqwisl.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dqthyzpk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjtbmxj.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbfsiff.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvbcore.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnixgbm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jadxruvx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfciudin.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhtfibp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2klwhzjxu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfnkbuv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gluyxhwj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgwutny.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aprsqeik.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnahqrz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgmgaxr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgolrdl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtmcyfx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwvjboc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnmwwtp.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ddouaown.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2svxjqqvz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xabxtunm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cafrwsjw.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qcciayid.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxshnpgf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrczunu.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyddcayi.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnmlxyk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kaczgnqd.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aanbenvi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqomzzzw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vujcldts.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhpvica.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2greoqqgk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvliljz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2athrdbjg.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmuvhta.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2aerypiat.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmbkhbp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlnxmil.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2yhczvbyj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2kktncfsk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhjfyft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hleljptd.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xihcwqsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdvgrak.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jhiamlpl.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrurfjg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqcarkf.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvdwshg.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwrlrsw.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrzrhim.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdxdica.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lovssfoj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeohptd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ikulutvx.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pefwietj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ziblyogc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rfceioet.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcweely.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiuuanx.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ffervdke.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2azhavuew.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2obrobesk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwyprwx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfpftat.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2apjcihcm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2aewnuyxx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwcyjlk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfxwuqv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfnsbkr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqiaohs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lezuqlsr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsjahbp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjldszs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfskqcq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyxpelm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nudpqxfp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrbtpff.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kxipbzek.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2enossrgw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfsvmyv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgbtgve.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2finovcek.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2omszahcq.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqnalct.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgixqub.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jowxaoyb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vmafuyeu.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeftjim.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vsumxrjc.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2mbacutcq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrpcplk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkqaoed.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeuwqzx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2vffuofcm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjnytgw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhvjauv.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2dimfvhln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nufdvfdv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzlizcy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbiwpqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrtkvcv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2odxvzyns.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2hprmbyzh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2rumwsqww.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgvsohl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsvhdkr.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2knyljswb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcllvqq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2tizorxzm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtvlraw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2crjuvmpl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhslohv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2muiewxsf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhqnjkt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmoscdz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxmzfpl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdaxuhw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmfhyvb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzuqjpc.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ffalgkbq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2dzldxzmy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2efwwdawl.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpwhyat.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxznqfo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xysvhami.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2otgpweyx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kixmaeug.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvssymip.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjrcmvz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2unwdlahs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2znhsiwxg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyqtyza.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gumgjrna.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmatavxp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxugqqh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2osrguiks.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qflimftv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gckyciea.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2thisabzw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2orkwpjjy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bivzbvgb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsejrqaq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgngtbv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2guasrpev.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoydypf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xnolfcjg.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zucpwcxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbhxyvt.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzjeqbb.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2aisyjleo.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhmrmiv.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uevtvspg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2sneianxt.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqveffph.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmxmjyy.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2urjsfpez.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlhpfzo.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzdixdt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vrysifhj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrgbxgw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nizxhufp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhcxnxp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2psxhuypd.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwfixah.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ldalduzu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hysqepeg.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2txznqqqs.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfribrt.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuonkgz.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2udknxphh.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oszuxitf.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmaklgr.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfbbvlc.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fghuaaoz.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzexttjb.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hngqkulf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpeljws.html


<!-- 参考信息 -->