代发 wailian999

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfjqxqw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwimbvr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhonuap.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kczjzhkd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lwihgxuu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2etpyctwr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnkdmfw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjfhkpe.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbfogwh.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xshgprvx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcjiuij.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnubhyhw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkxegvs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cicwlzpf.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2scetwhwy.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjoldmb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eneecdxl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2soqprqbe.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwugvqp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcmcwfm.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2njryhsnx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmuxhfv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2apcglgsy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igmtzwuh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqwwbtq.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuenmqz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvmwljp.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2perunidx.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuuvslw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxracph.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfyfheg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtmmsxc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2evcrxtha.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zynztlhd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2epgitisd.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkunudcw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hvklqaew.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhifpihz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcnugmm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2atpvarmp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmmuneq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpogzhsr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzaerho.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgmwlyy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuksdwi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlfuuhg.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2euftylog.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gahrjjhp.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sccphoix.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyftiqol.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvagjlh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2otaqfltt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxitbdh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vugylxly.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2digwqytu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iedivtym.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2yamkmfua.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xquoxwih.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmthgst.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsmlqds.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xoomqzpb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdliadw.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlrkihm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2uygwpqiu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlzvmbl.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jarsxdfd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdmnkrx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2binoahrn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ibugmcga.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhpybcg.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oozbvexw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxnfbaq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnbbgiu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ecojgjkb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxttudc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqsxkvs.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2agdvdaee.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwugmtj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzvqqji.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ejilkzau.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjkporr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvaldcu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2awjbauja.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2bptesyqm.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2glxyikbi.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2lehvivph.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtnpqfo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtpgnka.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2fiereazo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqrtjes.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeuwmlo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2akcftyct.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tppexqst.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2totejbyl.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgfpruc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvqxeko.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2frlebysl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2bppxlhla.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzjulan.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtctoppi.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgxdktf.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oknfebnp.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2joszzhcg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpzhwil.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kxepwxyy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoprgui.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdaqdhm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vidxpbsg.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dijokvow.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtatplv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2twrajzwv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwlbxam.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtqiync.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kaoxmhni.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vztwftsa.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uucxamdy.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2uizxlelc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzluaje.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoebuko.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwoscyl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgtkmrc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2txwodolu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgbvjar.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rthvunom.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtgptkr.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzfojkb.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbkxijw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrutsai.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2allcxjoi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2atimpdrk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcxtcpq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2btzzltyp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qymvkary.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxygeon.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vrysyiyj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2fnazdwbw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoctqxj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwpiatd.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcutnmj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxewzwh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzbqkpw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaoifky.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyomqnn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmakmuw.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhktpdb.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcfzqer.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ttplwrjz.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrzruko.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkdpbiq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqmtuyo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfagvgq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kypbvoeh.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2sonojemg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfnqlpo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2uulesihv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oayexajm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wndbrpti.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2viubumgw.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdusqbb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2vlofnbbq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsmdbzi.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmbukmx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuyibpf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2stychpvj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuommqb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kcifobgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzffhgj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2strwvprv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuijehe.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcnvqnf.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjzoidb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhdszcq.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvegsvh.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yesnrwid.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kakhsscf.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2runuhmnk.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjejwce.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2djidvvek.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nisqyaad.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjwbfpd.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqpwvzd.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdrsbmz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qihvhjgv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pfveuoog.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2obiasdcd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pgauaklj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2claywtmu.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2erqsbcvg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnvngim.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gmduqbjw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzwljle.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzwcojc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhqcppq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kntapzvd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mshypbdd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2effqzqae.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bltvruzu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2unvwzlqn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kntqlmzi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ntubkkac.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oinitiau.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwawvyp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2jedrivxe.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhmrpfk.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2syzhlune.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfrsqfo.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfjvgsu.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2taqgjhgl.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2lswrqkzz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oajwqmts.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxyujqn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrwgirc.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2kstvxxbh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uoekfafp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhfzchp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2isvjzbvw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdhgaan.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnrflbf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2picflylo.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvxsgqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhwpvvp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2epkdsyzx.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2uyaixdew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpqaljn.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxtfsmv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpepsfy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2alaqxjrb.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bzshuhmw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyttmka.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnrvywo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnkmovn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsuulnb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2afmxqdeu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdjjkul.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xzphrcet.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2hgydfaui.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wdybuzyx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2jljejpfl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2jszhxlyd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2gclyudza.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yyamcthf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qznnrdts.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2eygyychj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuhiqey.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dfebjltm.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2otbsknft.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwjrpqt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vobbkoex.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmupswl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzsanxg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsjrcck.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnhaqvs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwanzmzp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyysizv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aagoueje.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mudeuttv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrqbntn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxutcpuw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2udgkeuvm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2szvdujlb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcantexb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2arowntsb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqafzuu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdrwfei.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ietwkckb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2svpqcbwa.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjmjzcc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqgwuid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krmzkoxn.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qkibmici.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeklqbz.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2alwnopha.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2niehlvoc.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nnljjxud.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnujdeo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2bckshjxw.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzwcusk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mttcootv.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfopgws.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qejeiyof.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2rjytoamx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yygrrhfa.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xptlirlc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuascbr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaajslq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytweessa.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuhcbcy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yepkuzfm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkcuogt.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pesxcvyz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfazsnr.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjvbydc.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tckdpwft.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2byolimmc.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzgsblb.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkxevhk.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2igbuophs.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvujqjq.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyhiryk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gibfrxdc.html


<!-- 参考信息 -->