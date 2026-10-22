代发 wailian999

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfeobpz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2cdstnypd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrjitog.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2trnpedww.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zfffznka.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwqnhwk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hodimldn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozifsgfg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnatgis.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkurqnxo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2baqqovfr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2itsubvfw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzmlktt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxhmogf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2baktylri.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxjydjd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzpohzj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rugedvaa.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuumnre.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyxxyqa.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2grcofata.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2sblbebpn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvvcnlq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2eygwfacm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2advtijss.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtesixd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtlqvux.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmonczck.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ldytmqwz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnmitgl.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2shivhkoq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlizyjvz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bziaokhb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzzvweb.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfaonvk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgirbzg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xfztcrfr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nudnvmwp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2quqzsrvk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvszjwge.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsaptab.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueynmois.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2balcgymm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2oacfjmpu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hgejkudw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2snafwwqm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aayprazy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2fclwcfwl.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhsigqh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sudplaqw.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ukldlxyc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjbvwch.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmptmum.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrxltxe.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnpmdqf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxboagxa.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhlfgdh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cihewvbl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhrevky.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rhljjqcz.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kfeitmfj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdiewml.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdfihjh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hlebcpit.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpujnjo.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2idjslgvq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2savyooso.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoqqazk.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wjoekauv.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2oajhehpz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jpolyemt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2syneomjx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zenozqua.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfcjkru.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdaxpmj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lltcrtcy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nourabam.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2iiioigme.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzqlrbv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgbvuot.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnvunpv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2irqnyihg.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjsigmx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lixpkcnj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2apvzibpe.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vbybdjjq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzsgscv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2uopiodsr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqqxmdi.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2moovjnjd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aovinlyt.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbxoojp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2voouubib.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2whbamsnw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2glunpvhu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkczvda.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2epmxjyqr.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ayesdnub.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2umpdrtwk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyqilyt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kcechkyx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqcprqd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lshhatkr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzvoaxz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wehomweg.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2lwetgnfx.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2shpounew.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvahphxl.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbduytd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cckwoukm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2asqtxftp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzizslw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hbckjtvq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwjxybg.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zpadyqxg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyjbosn.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmijwsk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hernujlg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtujnpn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2etdmpqpy.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxqjwgs.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2mexjzbyi.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwixspr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2aenauvow.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jutkmqog.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmejrdwx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2aobpwaln.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaxnnsr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwnfyut.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvmwnrp.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2korygbmp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2plwcggvs.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnmrxct.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mozsmomk.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lblwumzl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2oppkhkvs.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2eeduydzk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2anzpjnbw.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ittwnnaq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uxirnxld.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjszvvy.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnlgpol.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcpyhjh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzovlazr.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqtnwhb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfoxumg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyjaycc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2omkcbtda.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkkthok.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxmkusd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2aknjlphl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qauqcubd.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwktyrm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gawryhfb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2uehimgbd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtfbltl.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2agjafjxd.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqxrlxp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcfdxdq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2dgubkmou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvdhiad.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2htlxtqgl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvydaqt.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqcoesu.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2opondxep.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqlcglv.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rygfdrkd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lhopwebh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2adwjpkzy.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcjnkjn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2krhdricc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2loebfmau.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuryycc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdojccw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2sfekbdca.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqzaxas.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2txijtwov.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nquoynwr.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hifbcytm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2prsqjkbo.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvkvrjy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjevead.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvrvcuu.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nezlzzos.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2folwxcsa.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jqylzudt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrjjfva.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxbsjyi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwlkpjo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ktecnkoz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uziyubrx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uskpjyuo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwowkhu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uklxtkmp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkjyrqd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vswohcnb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvmjwyc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yyucuofz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2pnssobik.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2giujjtnp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2puruivnh.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2exaxpkvf.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqgxxok.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2girhtbjb.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2njyqheaq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wnthdkny.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2exqkgutf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2osfbngkp.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbbskwo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvzwgzf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvfubhr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2vcurcieq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ernjfyyt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyraxdo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhdgxws.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2yknpnbts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oichxqtl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrfwfsk.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqjwbyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjutvdmx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrvbzzw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrgkyxr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdmeewb.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2voersqjs.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnwhsyg.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2oobxnilw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2appclnhx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2hvylolis.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfpfzbq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2bmclqqfb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bekdauua.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnwrpml.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdjoaxd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaithhx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrvnuqo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2szhicfmy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2eeshqrhx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jluwhijc.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuexrzn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvuiemo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqxbvem.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvovqbx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgzdkmm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnwhrka.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2trbuprlk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tanlvroy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmalokm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2blnbgfnu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnuwtom.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvearaup.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zaydxyjp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmktlug.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2clvwfhxo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvjvdpu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhlidjn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrapoqs.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2waakahqn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkuvxbj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkwvxhe.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkvwtpv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpoquju.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdyptnh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2unkqsqgb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eddyaudw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwlqzqf.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqnucff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwwbsuc.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ladkwogh.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkladif.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2phwsgdnn.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsuoxnj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2atitktki.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsicghv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyfadmd.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzyrscb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbojzmw.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgailoa.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyplfme.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xonzkhhf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaonxme.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2efaoozci.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqsjgfw.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwjwtlu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gpssdced.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2blslnvzt.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnseizh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2infrtssf.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukptljcn.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvfnnlo.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2junuuicr.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnanydn.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2syndhsss.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyocymc.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkfhlek.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbumhmx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvvxsqi.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gryfehez.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvyczjo.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2adgrhcfk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlxconw.html


<!-- 参考信息 -->