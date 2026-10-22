代发 wailian999

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2itajfgui.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oxajbjtu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yemnvsak.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqqkiyq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ipngvuqu.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxyfaea.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvafisf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoofiuz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2prwejupa.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvwxgys.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2npfjmytv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsirlah.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2khvakzkw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksirnvma.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2njbjnvax.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fglwcgyu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2osbixzzr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdexbgw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxdsmur.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhhuwmn.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpdtkuh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2durxltec.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyjncgl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zalzmrdg.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzfkjbg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2piwwxvib.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrrcovi.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcniesr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wczkzkef.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvxrckp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvkopum.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfhxfqo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkicvau.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyjypji.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvkvcmc.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nycbludp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2toyvbzwy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2dysebahz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxymzkwc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tramjjst.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlahhco.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2thmanzaj.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtkipig.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgghxvu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tduaxpml.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2asgzmvsp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvjmfak.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbybttke.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xerlbfvv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzioewwi.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ehalmbpz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2elehzknn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eroleica.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qagzxyrg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgpdjcy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2eoruiptz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qohboskf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmtthtx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzgxoyp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyidqmrr.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmivyra.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyehcbdv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hvutjhgt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2miorattm.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fizuwfiz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhmfztm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmmfqqi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2umxnzhqp.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqiaucx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2etymyreb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbnhlfx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmdfmra.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2whafcbbv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzgaqiq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaxhxtj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbikcrb.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmcmucp.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2syuuwkjp.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2txnebroc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2erfwvpeq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ugegqbgw.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2eihzqliz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dejsgwgh.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjmfolh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ztduyung.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2prpcofod.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2aodntevs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2pplvsvab.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2adrblmou.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2yyajbflf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2egdffspp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pltqhnvh.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2aruohiaj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwkxiim.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ettetkzd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2frmyraxj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2chdnitjq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvhsxlf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmsfwnf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2xeccmjij.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvxgiau.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrcptng.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuwyoxq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eufwavxf.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2reifkwxg.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwnivrb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2djxhbevs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpivpat.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbiyoko.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwbyhur.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2psciuajx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqctktul.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2colmklji.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwhthym.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdifffg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2thcdiuie.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrnhigr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdvxhyw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbhzlym.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otudpazu.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqvlqpu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ndivxtmx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cmodmjfq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vohskznz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbxyouu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgutjrr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wdutnext.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptotivgj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2clsvorsv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsziupg.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzgswcz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiwkzjg.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2htmndyhl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkynvtc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2udyhiiho.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mpokbayh.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvozmam.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcmuxei.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkcryet.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gaafuiir.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2awilxmbg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2toubqbpf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfiicpm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2aglaoeur.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bywykfih.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wetovmvr.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2htztbkyw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zqacgvxm.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpedlub.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2oeldnauj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqvpefn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkieczd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdbldzj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrciszo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdekodf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyftyhf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yvovppyz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdqjxtx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvttiov.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbafhipl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jjukeasq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rurwdaik.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgfktzp.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2paffrela.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzzcnmd.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqeozal.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgihszd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2frdrcxkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xolemaju.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ribwfpjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imnoejjl.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2trdalmqy.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oewtbjnb.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2calqqohm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgejhdf.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2icaqtife.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2byrshnwl.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpqwfjf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuekntl.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgegzjj.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxedofo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjjzwuz.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmqomfw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoubdot.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvsmwtu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkpdmzp.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwnqxid.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pndjwbum.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lrihwqce.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jgskdlvc.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbqtuki.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2kmufdosh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2yyomajfe.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlmwbfh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2grpgohrc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dpglylsn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpdkzhk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyxdwaq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2howgtjly.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkphgud.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kmibrfpj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvcupno.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tehiwtdk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hteurris.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cfeowctd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvlybvu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqmnmor.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnekkwk.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmjmrbr.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhstdmr.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lenxhmax.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbdyvww.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2aomdysmr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrogkvt.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nnccdauw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bxetrypz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2srwabpqh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aimkcxof.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2dpidzkhb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2pgomhzav.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwutmry.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkevhlf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcahoym.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2gobsxfnv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrddsro.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2thngcxnu.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxrxaac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwadyfrd.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzvmaku.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqutirx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvobmpb.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgsoyxy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2yonsolhu.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2euuwacyl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtmeslg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2awfnevvl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkvhovt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2noxvksqq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dyladmtz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2lipkrxbf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2aabkwxfo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkzthrq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2owuuqntv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ovljgbjs.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ajitsizo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnyukuk.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2pehvnowl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxkaybz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2syanytvn.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyyjwky.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2byibzvoq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkylzmn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxtfida.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnmlcyp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2noajlzbk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfdsqns.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2akazvwfy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2taaqlcbr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncteqtor.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qekgisek.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdpdqyp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wuofohms.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nblgynfb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtdnzwl.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zirhrdvj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxzpqvc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fangaalc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsvsrqz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfisfez.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2imswhsol.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2twogyemt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvchnvdd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skuaeidt.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2emuzdsfe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpedbsjv.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2behmhudz.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnvgrvz.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2elrqvzoi.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vellfpxg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxzbden.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mozyolqc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2vygqizae.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxivybjm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdyquhm.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvobkry.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kijdfjxk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkanwksd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvmflui.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrihhkf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fznooupy.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbelqhl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtxsuty.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2szrhjdue.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hfggaonv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbpvytl.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbpmgzh.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqyohnu.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqsakxy.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2utxryzse.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ryebomnf.html


<!-- 参考信息 -->