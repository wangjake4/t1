代发 wailian999

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2aobtscsj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwdxamm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvvyeoi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fixhtcoy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uoccdqke.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbhvnjq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmqtyvr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdkmkeq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2betoqjsr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2eilzknzu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtrkayd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2chibmotz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2oxicesyc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaujbbfu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkpgshs.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwerbdbq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqzvque.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmvvspg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sspaofqi.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhatmpw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eowtrere.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jveqnejt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xrakyjmo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqubsprp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzcmnhk.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdcfdyt.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhyxwbf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvazmgip.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2etpmjmpb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zciocsni.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzpumye.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaiohvj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2avcaeiuj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tvasjodf.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2acsrrhqs.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwpwgab.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfhinws.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2efsyjseg.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwavoyol.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaizwdpv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gydvowwk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dduoebcu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcgmcos.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqudsmt.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdaexjg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjcipbw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2btziwxfi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hirgatkn.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2svxcjrsc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwqhslm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2elgmemvi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcneejs.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpfgenq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjdcphv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2agskvbmz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbpknmk.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlndafo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bufqrrac.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ondbmxua.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kodvxzwg.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcpuwvd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmvatqb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtlbhzx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2shpoficf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sruzjjua.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2srykfmeg.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ddycvurt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuynjhs.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvfhvzn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qosbpizy.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hviywkpc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yffpkatp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvfhnep.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2majfpcyf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgpxrzk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2afykfqdh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2akwfpokb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qneocjnj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwosbhr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieutozfx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2sobqevqh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhilifv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkdcrtf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kkytgeqz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zwligfdv.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhkasbj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoyyajk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjlvcxy.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bermuuzr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2sjplhjct.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmgmbma.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtmlbpe.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfwvifj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwjzfkn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrfhpmx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrscttz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjcmksn.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbcwysc.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hloipnvo.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2xzndlblm.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoqlzqb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfzqmjn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpejdey.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvszwog.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vteauayx.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2znsoujfe.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqmaozq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxdrjgw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlynbyr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2oiogdkvm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eoskpabe.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rypdcfdc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuyuqic.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvrcxgu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdslizz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uurabwom.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2onrijuhx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrzntgd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cudjjdid.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2smtvxbul.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfckkrl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hynoqepa.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2szhveupa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2eubnnhvp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2htvprtbx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjffdea.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbhhttp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2retelufq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jvunhpzj.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjsrmwq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2avylfxws.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcpanue.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwhixbd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2liktbqzo.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcbgzky.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mzypqnsi.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2whhxifrr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2spwveqsw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvurykb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2guoppezb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrvmnmm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzddokhc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmewnvwd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2plvepgnd.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pctxelwk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qovlgmwd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dskzoivs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gxoznogb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pabxpdyd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2brqajoii.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmvisle.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kudsccly.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2haypalfy.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvednfc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsqrmhs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2peutevph.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2otxjayfv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbnmrtc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeemdpf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtujuln.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2iflfnexg.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2cevrurav.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rieudjeh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpsqzjn.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2sajdevsf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tiagmkaa.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2paehkpcp.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vwohcimt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtxkviy.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2szmajqlc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgxkchr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmtpzvf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ezewkcvc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lvptcnno.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzdqoba.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuewwxg.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uasmtftj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2akonvxfs.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xiodjrfj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jtihlimc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2edoptsqp.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2peycmgrm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhcwnnp.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuorjzd.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkwqujw.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wbalyqdb.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2biahxoqj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ywldpucd.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uasoarxr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlgjudq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoqvcrr.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ytficzjd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvfbkqs.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2epnbnzxv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcgljzb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdttpyo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2fhigxeny.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qsptfovw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2enljdypa.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbwxocq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2orifxffr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrjavcv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyulvse.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wfklltwd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bcobqpbi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yppozfcr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2kgntwkqd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxgiepl.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2avysenfm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2emwndjft.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxshmxt.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyveofh.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrsqvoo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2grukzzbz.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2smgmtmye.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zewoeppc.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2atkrqcxq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmnvxhy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vretmqrx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2dglwvbkk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2okacdpke.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2rnesisaj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2anuccxcr.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2htiaqicl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2suhydkbu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjgfsdi.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhjrvlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfvpwar.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuitorq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdporzc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyogwht.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qyplpsxo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlwqbey.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvdnmal.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjdubww.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2fbssumwp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2zsecnlvc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2hknfqpms.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pjydzxdj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxczpof.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdrqrxr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdrqwll.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2bywtpuvr.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2iagifmvo.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrgkenh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2sgedbwax.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2khejelan.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2yghjqkzn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2muikirwn.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmddzya.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jqexzalt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yknbcjhw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkcybrd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xosvtznc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzzijhb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeqyenj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xezxucfy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2byzdegmp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuiqzwl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2agidzqoq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnvlewo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnyqumn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpdjpdk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sctepomj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwxpxar.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uffhgcoc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnckega.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhpksmj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2swfgsoxx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oestgsjp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jryukjfq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmupyhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwrmfdv.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfuypqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbptqppe.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nnplfrnv.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2snxyrhgd.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwlsndw.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2enwavgbs.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueeamdvp.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqwlpsu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuygwrqu.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2thgohtaj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzhqoya.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxmxbhl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2oduqsxst.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqajcdgl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlwqmkl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2usmuvqde.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2atjhwowm.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2oievyhmk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2apqhxkyy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxumgcv.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiqtyuc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2gzshiusq.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbuwnqf.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hictpcxy.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2klnjiaar.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoruzvry.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2tyllwnuz.html


<!-- 参考信息 -->