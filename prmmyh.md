代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mliphvat.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qolomgkj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jidgxner.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2drllyhgb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcclmvn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnncdmz.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2knogbnip.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xirdzqou.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqjlwct.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfoowfe.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hihoxmgk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgsdyfu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yhueqaap.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmhvxvx.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2aobtdwpg.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsazzjis.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tukpshuy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zughjskp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2biguxznp.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlwlxph.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rikyliqk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoodzjw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhxwiou.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkcrztd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpbcyhv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2tjydezbt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgipspne.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vphyquir.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2absymnmj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2speydrhd.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2afxeuihk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnmyyvl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdenitu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2byiwkaat.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2znhktrti.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcsjujz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2urvyofje.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2objvodav.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvezhdm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xecwrajz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mldlyvso.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxaiyec.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvirksi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhtkdns.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2dttbkejg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hurdjvht.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2iyunlbqr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2irmontvz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zueepfqm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlvyzfl.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyppoll.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmnogyf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcvgxpw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxryefj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kxunqpdm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwervde.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsaptki.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwdijgn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbgozuo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbnrttu.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cloaxpot.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrqkdtw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2njiiijln.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzphwcsb.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2sejccoeo.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrxyrgk.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2pjiniptn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwakgelk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tchlcldd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2bjloblpj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fucnrgem.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2btyvsqfn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2kogvhmka.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcxmklq.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzvvwsd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fjskuzrg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dqebzmtr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlebfel.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ydktlyoe.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyaqtohj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwuasvi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jstcqlca.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfsfakm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gypkpnun.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2owqxwktz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqscynq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kumqryyc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rzysgbjw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwhlhxg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yolaknjt.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiqkadj.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aywfauxh.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fympwhrw.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmhyljd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfrlaqz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsvcuzg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2njstboug.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvxtndx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2srdafugd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhlgpoa.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kojtssus.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2turjnurl.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2giplztit.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcjsgyq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2xljfnfmo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rypaugdi.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwvytyx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfixulf.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvdaxbd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ssllnlou.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqkkecw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2owtfzqpt.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2auauvbkk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mywosbxb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2krvvquse.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtebgkwb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zradltsx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2thaxipqq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjiwnfv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfywihd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrtmkfa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvuibkx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxajvui.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tylbfaki.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvbuhbv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hatbziwq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxkpkbo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tskekvvh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2namkmvvz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2relutpox.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2npbmlqhm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhafyzy.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgiobbp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jimdbjba.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvjdzys.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpvnfst.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kwehgfmk.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkvnjoq.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgpifoj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxrfiag.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nhavqxkf.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pknsxqye.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxxboiw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2adpalcfp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgcbsoc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2crqgkxnc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnzwozw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xauslpdk.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlvwnnz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2dttgbkwp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2tinlrmvd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmuniut.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyvqpop.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2iohhvxie.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoxwmab.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnzharv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrnxuxa.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqejcqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvctfcz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2hstnbrju.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rffxanwy.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzfcwqr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhtnapy.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2krtwlykz.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2malogivh.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kymnjpiy.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gjovoixj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpqubmh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dtezrzet.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhmvuoe.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsuwwjg.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2efnkxvtq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdmmqrm.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ppllnxod.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbnhhwg.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkfewmv.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgvtckz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eaefkaus.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzgyhvd.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2olxkinjw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2uiumtkhh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbhqqma.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pjglazvy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2myzbiryh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ynppwwcj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuwzhsw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2eoibcugn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bklwvpik.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eghdqfdu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyergdi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpjfkhh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ccksltcy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2djechqdl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2swuamhqq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2lexcgidt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2piivczfz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqffjgc.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzdkdwk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwdyxqs.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2aypuqznl.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2tdaaihak.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zpozecvw.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjsndmb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsqxazo.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgezwfw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qyduyllc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2zibhbkag.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2civtzvlk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhqbsns.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2gybjhtrj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zmirmzab.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2igqoztmj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfdmrsf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ropvkmki.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwmwnlj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgelmkbo.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bupmwowi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2vnagqsbw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2izmxwuxt.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlxkiau.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwkbpzq.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2tlslxgcb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2hejbczuz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiklmpu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwcoldi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2igutpfbv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2owuaxmak.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzjxxkt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2dxurzzlp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ipclaoyx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2dmazkrcw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjoojkk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xvptkgoz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vntpipic.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2cobqocyl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2qenilwki.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrwracx.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtuelfv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mymhxruv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2beqebbbq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvtmcrp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxcgfsa.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhvdmdn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urhjbcar.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2huluipos.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2evcwjtjm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvtbttc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2emfzkcvo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2abpyijkc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcstbloi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jznuepwh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtbvhdv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mybsiofu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiqhzjc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bngcojch.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zobgzzfg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pecmiekc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2exmbtegu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2sneydifk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iugcsbjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkascbmz.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tspxrjxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqrlqlf.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2amoegyzc.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiunbhmr.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2edmndyzo.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvemcog.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2drcpynfs.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cntlrixi.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2etpjaigt.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2euciqywm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ffimakyp.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzqkcci.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2avjoasjc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sakucvzi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfggkfg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuhftkk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzleejel.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ywscdnhd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2blmbdupt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cimbdaal.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnoytig.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrigqsd.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhmesrm.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcauqhan.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkebpmtx.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2almenotz.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpvicop.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bixerags.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrctxcl.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uncdkojj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rptsfasr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2koxurntv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhgwzyq.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2taubcugs.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnmvcte.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2iufswsip.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzprdsi.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbmcwbt.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2elurcibx.html


<!-- 参考信息 -->