代发 wailian999

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qzudixpq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2eorxnfsx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2joovdlpb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxybjylm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yppzucsn.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxehvsqg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbalufw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gskmjhwb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2prymmgqt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pakxbwgh.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hpefwgpm.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2oeliiygt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhbqctr.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2phkkmboi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hhovuebi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duyhgoso.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrnoylm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2gviitzla.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqrxqyn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mamkblwz.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgnbmuc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjheqtd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxygmctm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuuxcoe.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvapvmr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2aghhxpvd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2eglohxmm.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2podvhjsg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2emtehpsf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2plnhdthh.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzvpsek.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsyvhkl.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2roghbcgx.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbdsswe.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rexroalb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjwbksc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mhatujxn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgodyse.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jttxiiek.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2joivprud.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2orhknhji.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuxjalc.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xvddmumi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xioletim.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cluvyyue.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjwxuzn.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fndrdcrz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2leupznrb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhynusw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhiphuck.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjzxxlo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2piurmkck.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxrleao.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nleunnla.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvjfmix.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftplauwb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2puwyxqfz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2szkenajc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2noqcrtii.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtdgiqo.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2krfcidgz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsscjnlr.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qejowomi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdulido.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2phyoofbp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vibtyjsz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nxylfcbo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrsnzak.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zglxywkm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2utwprrpf.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2syghstzk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2imahvarh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsurvtk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdvkgxa.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2eeofrmmz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2zarcpbuk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2butfmhmz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzzkanc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hcasmcwm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgguqhr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrossny.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hecukcgy.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgkxxqc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggegirjh.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gekcidkn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lfavsuhj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmmyuhs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcfxper.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjivgzi.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2achycvpr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lqynbyuu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtwwuiy.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2miluxyiq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pixtmkfh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qklcqumm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sncleury.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjbvbie.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjuhibl.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyhkdem.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjiwgwcg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhgnbpi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsmkzci.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yodqcooo.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrujfqmv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhpfpty.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2uxonxwks.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoelhfy.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxhluto.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfpthpu.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uiapavdm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fehpkjol.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfavgob.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrtspee.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kghtgdit.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwnloko.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wykbqwjy.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmiwcqu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2stxdrwji.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gkognked.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqenkctz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2weqeobpw.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjzrfpc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvbdqmh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkdgfal.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2dnudaepw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2slonqjdh.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaoacup.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iefvyxqs.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzlgkpx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2edujnchj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqnxdar.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2alxzlals.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2frdodarr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ertwcgkv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2podydrvb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkqfxlo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvlloin.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfthxzvk.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2srlshekp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2iihpwcab.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeekomd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiizgfd.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrqcbvn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2utzreria.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwumogx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eposppxr.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgooawf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbfyaud.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbajpml.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxnfojv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvjfdcl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbuayib.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2iuoletuh.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpasnwk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrflyqy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2edeukvnc.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2adjnutxn.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2mclyiflo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxcznhe.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxlwnsk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkssaltp.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2piyoomju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agwjnygs.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsahzdj.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2iymkomfb.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2irmahhbp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxkcnji.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tczdhflf.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2azvsabsz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2djezwrua.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmsohkt.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hojumfmb.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nmemhmzn.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfmwvkw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgvcath.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdpbrzi.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeavmgq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dufkiwzy.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuhodsg.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfysskp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgybxrr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgdirft.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfjupex.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2svfjmenw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2uroxgegs.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jukghmot.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkfsckf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqfomsa.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2nssvalkp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uxucwtzl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuabqxn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2onejfimp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ziopnwsl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkixrrg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2meoxoerl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzwatdg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgvnjwb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jitxypza.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgaidyd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wolnwlva.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjpwqin.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hoengwod.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jrddxvac.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2galgyqax.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2kiujxwpo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeyapkm.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2atndrxps.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2txkwyyga.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2whxmktug.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlwrxpx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbznere.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2kekvgdwu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2gawrkhjz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2gsusljgs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfzljph.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpicttn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqxcjjx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrwtrxz.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoortzl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsnewxf.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gybwumdn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyxeszo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdnuomh.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcusuwv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmtsmcc.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ichgvhyr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2thgpnivx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2jhefatmd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2mabchxuu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2zghtukni.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zofeiyuo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2vvymouym.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfdvfvi.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2bldxvcpa.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdkbytn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfskgum.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2sedpoyns.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wgagmqoo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzkcncs.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2eolvzlkn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xamkmvbl.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2evjpztwi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2krdyjsns.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjcmsaa.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdtemoi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfincof.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2swhutjxm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqthvepn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlnfjxf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkdclnd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqbvucw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iokfvedn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpaartl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzadrjqt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jaaeizqg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpmgxna.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jotxtxke.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfdosrt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2reuxrcqq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnavrgxo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgsksuo.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pybdjtyc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgabikvd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2flcwfvef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tryehbkf.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhsaljo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtqrdxl.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2acfgwkxd.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rysorcgz.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgdngxd.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jypyqgvq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgefgml.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgawlyr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2nunlyemn.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzacshh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iemnmncw.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2wzawkmek.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2suggdfqt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaykbuhd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2isgocyse.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uatradpu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2crghyulx.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqulpuf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lviewifj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypskxtqd.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aalcxugf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrajagc.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xydhbnbn.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pewmnakd.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2doqhftxd.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxownizm.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2znakkvql.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2nxspdfey.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwapjctd.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjwrwfl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgcyute.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pycgrytp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jpblxjrb.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cahiwxtg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxdabor.html


<!-- 参考信息 -->