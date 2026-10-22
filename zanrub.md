代发 wailian999

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dberwoef.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2owifvzsv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lzejjcoy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2oticvenr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxonzkq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhdwadr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uwounpwg.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdacmfb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2louexhyf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbzizyo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwleymx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wusdepdm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2beksuqxi.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbaymbx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qopudqun.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbzkeyb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2drnpltej.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbnesgh.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqzdlux.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2aghqscat.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jiztsikx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2atgupapi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnhywer.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxjtkzy.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2usklqfoq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnxywfl.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiwbqms.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjglqmg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqbjvzj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyibxtn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyqxtxa.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbfilid.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvfyllh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvalezoh.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsmmtzm.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nceulcvd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2otlkawvg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2txhbhxyd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tglvgflb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2koygowbe.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oudzdidk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2egrxnuat.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2titruuwa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfudwuf.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2edtilwgv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zunwsiya.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiydlwo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2klwrsvuk.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxhnmar.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2glnumsxe.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfktprz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2uljdgzdb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcnzldr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2htgufwwv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wozopnyk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2uccpywnc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zemsbksw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxxhwfm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wofwmzjo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mggefabe.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bosxspym.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdvcjnl.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsmpdzk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqieqcxb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2afsfzitx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyaouaz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2usnfutqh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bixkjlud.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uintcpco.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2llexaxfc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkudyik.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiockpc.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2shigcjps.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmpzktg.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtcgxlz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeeephd.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbtzdtz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpygiac.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2orauzmcn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qugidqpj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyjzaot.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsplqnh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcgjmeb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2zesaydma.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ophpdaec.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjcpfsp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2szybcxjw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlzxsbq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuwlhyd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdimvle.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2slqitxse.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwophrvg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2olsufbrd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsdwlqn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdfypvv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfiyojc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2bdszldho.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyeuqgx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mnthxyww.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmoebhp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lziqnksh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyedwbt.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnfpqig.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbhxqhq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnhdezi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ditcbgnq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmlowcn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbltwpan.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzalatg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmazufd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eectkjuj.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqqmxfu.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqnjjvd.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2unzokfyy.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aoepvygh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdbkxoz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2segfjfne.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbyrnia.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnfqwpz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqdeofz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsndncl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfnnxxr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtwpkdu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pknqdljc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ayziacbj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bvowdcxm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhupnnr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpucvzid.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzspjve.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmdbtue.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2artjqawr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvrxuzv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2udlohpaq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvreasf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2euqnuikf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2azzzkpof.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gfneijdw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ldduidbc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hirxehdv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2cswjqtjx.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnmhsni.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjuizcw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2urqkhmex.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ehymyigy.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwtyael.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2otfzhgao.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2apogzmbn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2scdyscfd.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2swtxcvlp.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmcxdlm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkmpkmd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpywmst.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjydxej.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2smujnveo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2icqxotgd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqzxdkg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwewudq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2perijkym.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwabpjcm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opqnxepa.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rachsbit.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxzznzv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2owpjwwkx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvfypwt.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvqdmsb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfebysu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmacyuyp.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2julbrxdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmhybir.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tofopmub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xtelzayg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jehztqms.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpunnqo.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oszzegnr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2avwbmysu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uirgcauk.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxdpxxm.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pularagb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2osafrfuk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyhwaxp.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2onsoostp.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnggkqp.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nvootsgv.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbykolo.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmjrssx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fcddlokj.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tolkpjgi.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2edxvrjhk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gjndistt.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jcikxesz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkcxhoa.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfvbebo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaozchx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdnyxvo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2aalcalnp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2oorhulrl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2cypxruzb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2chcuxvtc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2axavmpfn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrviyuh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzsipbj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrwanzb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkkifll.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqjgnzm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqsbwaz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zdftidjh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2aftghdhy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxdnzao.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2xokrdmqe.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hschfetw.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzpwhex.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoiijta.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zbduvike.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bpavrhte.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zzphnnbd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzcunvl.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmcusyu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lonjrjek.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvgptrd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvdypqi.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyqsuei.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpvilso.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuwmjyd.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2dykvxmoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2akwoaiyw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrrdsaj.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbwvpuh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xsndjqdg.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2olkrlbkf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxiaqps.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2mgetjrgq.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fsooaoyv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmbiqbu.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2fjecmxkm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ralkzomc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2bykodrvv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2jiawfian.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbklbkb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rnczzygg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2vnslewzk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2yminpwoy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2vodatlij.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbtyenc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqdzfwa.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vcptxraq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmoxppe.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2gegyglqv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfexkcz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgvpfdh.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhuwvas.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvdckpc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqophidc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkscdfae.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jryfmjlv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2plyaudnx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljogbvlq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrpqajb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xphijpud.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwnearl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtgpjmw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnjbqbc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cceipiqx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpjxvuu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkvagmi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzqztrk.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhncernv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qubdawdy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuzmrzu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuldwhh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vupqskjf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2orgspomu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkautzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jliuygyl.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gvycksmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2enmmoezy.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxmzhot.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeybgcp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2trfziskt.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dpciovgr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfypssoa.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lshexsog.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tifqxwyf.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2amsxzjph.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2udrtblmd.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnxwrfn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wbaesigj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkzhyys.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmlxepw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2czqwvxhu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhrmlby.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2edqegmjw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhbldke.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqqlxov.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwjzahd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2azsjnyvb.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvreiob.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bukdaicr.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkudyahf.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2himlmcii.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2aexkqwxj.html


<!-- 参考信息 -->