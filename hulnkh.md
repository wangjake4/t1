代发 wailian999

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iljoxazi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzwcsog.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2broebzso.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcqwsvg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2iplixyll.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdzfxdm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2czjvnrju.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyoxovs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2itlrzbzr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xecoeswe.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiffqdc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2auybpftb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ynikokyz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuqclql.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdjolmy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ostekezh.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ssipszsx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2isjcoyro.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2naxhbrrf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npvclhof.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzyzumc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2urldtbxw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzvbxyv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqblixny.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbjiyfq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtfriwx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfjzckv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2gowhnivj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnpgokk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcuortw.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vefnexzs.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzpclmr.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgkpxvv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkxvoyc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vuioazlw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jetpfyst.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2puhwagoc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sitzmxpn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2rdujxwuq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwatgjp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fqedfaio.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2axmommlp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzgseez.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nugmtfee.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyvaxtp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjagffa.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2krzujhes.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrgkrzw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhjvkbk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvkqnwp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2oymqsejx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhmhayi.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jaccdevv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jllbaazo.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwtenzk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjgahkx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnnccdp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdtpxzf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdocpnm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvyyisi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuotxbs.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwbqndk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwujiwg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmrmyrd.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2eanqovio.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtttlhbm.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qegpnxti.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2oolradae.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2udjimncn.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqecezu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mroprcte.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxvyybu.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tivetoiw.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2docgbafr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2veexesww.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2rjotjava.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2rzddophg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2idpqeesz.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2exzilxch.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2njmjyjgw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnomamf.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cujapzsy.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwhskzo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjretha.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2sihlpvlw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvcviqs.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiosdhs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfgxhez.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2hamwnbxj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpatdbz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2acshxybt.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvlbzsh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwnnvgk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwqlhpw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtuwdgq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfqmosh.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnbjbbf.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iocbgmsr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2scycyafa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2buajpyba.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aluahchf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kiybpbxb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2asxdjukr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lebqneov.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgcpzpn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tongovlt.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfdjyqv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzkkspv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhutmxc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zibcazod.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iasvrnmd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgubcnzg.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrfaiku.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtniohr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmlufou.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2glreihcs.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2btaqymed.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2racawhux.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjaesam.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdkeukp.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vqznicea.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbhrbdz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsmtfvo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2edjzafvu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vbylpfhb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxhybav.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kcklnpju.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcrwydk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ycutayru.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oujfdfxd.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gandgyqq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvljsue.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuewusz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbilvik.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2znqzouwh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2kejqnnml.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iokqlljy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjygzjw.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvlseen.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2yraxwpzp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2oyeqqmtd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfnytar.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvlgbvd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2czoquins.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wdthtrdj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2czmeprhu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnvaqhq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kifzuvfx.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2abgiijca.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfthocny.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2udzmwlak.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtbfceq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxozjap.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mopfagzq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhmpdaq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnumszr.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2pyscrnvv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2lyesbvcj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2arwgkgqc.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvdznms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcgwtxq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzioydx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnokyjl.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2srpwmcxb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsdpidm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfblzdi.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nigelvlp.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qykfktwa.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uforuyyp.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbzfbgt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrawzim.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2irzyoqhu.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xakeszdt.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rusnutrf.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2owbmhbjg.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhubwts.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxvkuhj.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lbciqzsg.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwsebyu.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qbonjaxs.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xpewokou.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2njytyhua.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hgapbevh.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2onbbqboc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nidpaxwl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pfriehqm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvoqjcs.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhrqfwr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxwbzjr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsgaojt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqenqkq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pydcozmd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcyfdbo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuhudhr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dynlmgwh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnxcute.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aczmmwww.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pflwvelb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2eimwpdxi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxqfisa.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2goypwhlu.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2asyiffcl.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnmnhgb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vuskptdk.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2vadpubbh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jabrcghz.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dqglrvpk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2obdfmciw.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlrqmwx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbwlnut.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsilrgp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2fodndayn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2cliylxjt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fqukrhtd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpmqddk.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2vhddusdw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2coierhmk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrbvwft.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2nlttjheu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgclysms.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2vrctcubz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnccwkp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2uimwpcvl.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbuhppa.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2eixxoxxg.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhqtngj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmlphln.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ytohpeip.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2qmujbmxq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2clllpnnl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvabyef.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2fujpncfr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2zebtobjm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnhlwax.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2bsykenls.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2naiqyavm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jsowykym.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgabtuc.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuqlqrj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdakpwa.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fauuwocx.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2kighkepo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xorhcffn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2spoxoggq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aalrbfnn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kywrczzx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxttgfg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pejawmnb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dioqfcov.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2drtsxszz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdxecgj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgomjkkp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjciicr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssonzvqc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoeunrh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvchywit.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwvwqrr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aaezojya.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bprolmmc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeqmsbw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcexzwi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqgkshz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfrdrjt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdymrgz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmyosjf.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgplwkt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blqpteuh.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oipdstqq.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuaddhw.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsipoqp.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfjpltj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2rriydkxu.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xafzlnbz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxhslnx.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2brbaadtn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2irsjawkv.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuscnnx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjrwukt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyizsed.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2coenpajp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2llvchpln.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjaovvc.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2btdqmfhp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgfyphs.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2smpfnfkj.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfrdgiw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwheyoq.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gknkkjvf.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkreywsk.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyfprfu.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qozimbkt.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ayylknsk.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2benpwcqg.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2utfxywbi.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2syjmycyj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwcnuyu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaftnynr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ymafhzcy.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2otounlqw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2siccupsu.html


<!-- 参考信息 -->