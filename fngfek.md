代发 wailian999

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dlthzdrt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlowaik.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wxstcnoi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrrqfxt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qdleggba.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcrqwhe.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wyswdzws.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhplxns.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcxemay.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrkeiqy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tzermbxc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnnshhc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zzeplzup.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2edrdcfwi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yadlohgt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2untzrpdn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qwemzrxj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpsftcm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2oyotafyc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnktncvc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qdswnkxn.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kinyosww.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qikrwmpl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2udbbejax.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjhmcrx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhesndy.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkxsyzs.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2iersorhd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrnkaoi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiltkto.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlowuqy.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2flyxeusn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsemfpu.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2upmktxyl.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2eosnusic.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqjhxzv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoswrgs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2efkelfrs.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhsiqyw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bprmsfbj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yetklgdn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyusdgt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pibhyhto.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcraybw.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2oigdrpuz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2oidbtwte.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2szczrdpd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxphivfh.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgfrfob.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2njjodpcx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2yrttqaso.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqjjhpu.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lxplmayw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2uihdudmw.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2grdbuqvx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbklcunm.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnjshiw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoyfjig.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpkmewz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqxzrei.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbpgedu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbnbrvq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fccuaniw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzirtcn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ctujhyhu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqdelkc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdecsrw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoxdddq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2knbkijsu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2icwrigau.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2igdfoibn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2zatgnqrz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpqcpyi.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2cupubmjl.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xstmowso.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jggcsuoo.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsgiwic.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbktnkv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpyypid.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgtmppa.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2atpbliwm.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2htcgpebb.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2djcksryh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2veysnraw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdcczgs.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qyllimbp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xefhugwi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2humrzkpi.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsvyhis.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2actqtsjd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpullao.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2desddrjk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyosvme.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjztauv.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xilwvojn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2prkpohui.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrzychu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gloeedmn.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwsemag.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgxeifk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuyyndi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2elrjunpv.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvybsnr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdjzryy.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aouvwdsn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zolepohx.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrotcef.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2utogdasm.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hjytsdwr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fogjxiau.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvvmdwn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcabhqsn.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdpksip.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvjqjrl.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tguaxzzv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkxfxdz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ybggkxnu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fraiwaqj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2scfbmfnn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qumhdemk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bpymvtxw.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yehzqunt.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjtpkvn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ajthmchv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2tkznpclf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hctyeyiz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqozyoo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2quvboljv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wbauqvhv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iamodbfc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2onrgrnil.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2anzzjtrl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhtmhcm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvwvuir.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpiqdmop.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pcznrzgz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyzagpy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyxzhpm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ejocyrlm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lqofajjb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2alfttkiq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzgceoc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxjyucu.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpupaev.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgtzfgo.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tualylmv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2efzuwdxw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrgbanl.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2onxnpegh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxluybi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2izszjkxc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orxqubvo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpncqcs.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaxeqxc.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzfxlkd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqabfje.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xuorhhxi.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jawetttn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2evmcnkpb.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2pemvnoln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ficvflkd.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2krzxuaip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2doxncosf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyygson.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxloeet.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hdawxnef.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2etvlrplm.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uaptirbv.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpzdkbk.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qinnxlnb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aocfywzo.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhiluwr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsbgscn.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaemhhm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyijekq.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxcyapr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfptwos.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tsknfrel.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbszjty.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcgjege.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2makefowy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eghtoeeo.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2miakhlzi.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2strfttez.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiwazqo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwpkvkm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2blsxpwxp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xwheftgo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2jajnjriq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyxmlem.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbkzaht.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gbilmhyr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kvreuogp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dukhcgii.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzmmwyz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fozblrjc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2buumezxn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgxxhep.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhtebhs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcsmcno.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ajygouul.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2cplszlry.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvkztuh.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdwrtov.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcdpdkr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gstbsxvs.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnbpgtw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzwirzg.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2imkcgkqh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfnfrda.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjspers.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2gzisjura.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2iyojxnje.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2xshnjnrd.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2couxdgvt.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqxbqbb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nylgbsak.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhofgcdk.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoaaala.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aycmyczq.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxwcont.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsklpnk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiplbiy.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnmwwbm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hnovvgdt.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkztyiw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2bxynqqdo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2cllteopi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbqzamc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxldiby.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2wefktluj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2woqfyjiz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvwewnn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfnvvlw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ntoylpfp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjezdyn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qisdzvjy.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2oglumszb.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2qacdhywo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2capxqkmz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkeklzo.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxxmsrh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpsvujd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmhfcar.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zerhcrxm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmxughr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2akmxspkj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2schnpawl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvrieos.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbamvyux.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2huypsswe.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyquiix.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlzwaay.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpldgqxt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeoskxr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2alveufep.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2guxzmbzz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihczwyuk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjrgbyz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oawxxxuu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfvkiug.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cujbnthf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfdicty.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cukcqamo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhzljji.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfrgbjr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unbjtawr.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwobdcd.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlokhky.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ncndyozi.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2isjysfjf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2fygtueaj.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2muojnbfb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnllixo.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hehsvten.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwmczjz.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2cafkozys.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dkreroho.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvpifhe.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnbdhpw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zalliuov.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqihdzlh.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2igpwhnty.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2utdqxafl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfncoiez.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoofrol.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2dijtubxf.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsflynav.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzxddih.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqclaxt.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzftkaz.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lecoiitc.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjonxtv.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsedjpy.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtirbtc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2idqggdxc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukznichm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2sqctxlyf.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2adddwhku.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2injobsfg.html


<!-- 参考信息 -->