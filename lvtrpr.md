代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmwkkwo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjhpmuo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbhxqxx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2poonmhmz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfzhnjq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoxesrd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaqoknv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thttxuho.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfvrlvv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrcjcia.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2itnuzdlb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yewbdmzv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjgxcso.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfuabis.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eijoouzs.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2opxdioch.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2dopuwkax.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhqnpxb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2eupvallw.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsxwekx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xslwirqx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyoflbv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aeijuhdm.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xenutveg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfbbeuy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvuswrx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wznvxiwy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ektoaael.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kpszpolf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsjsevf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hdambjgc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2olosmpri.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyoliie.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvljrlx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuakolx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bsoyfysh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xavyxwvm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2piuondfz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2byaeogdt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrlmisv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tupzrzuj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkmmudm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ltypwvss.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bctgfhqk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wngbrlaz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2weanytos.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qicbzbes.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpslnekl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpgdhmo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iklipeyb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rnclobzl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2btywcfhw.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhtnhbz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyvdlvo.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzbxrim.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2karlulaw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cjucuxwx.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2odqctkyq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyfefqu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdiztuus.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2bufeyqix.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ikailgpl.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmudfjy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkrqbmi.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2hihvedin.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfkqifp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkmisjl.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfeguwf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2omjwuivw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwounac.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxeiumq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2tcefjjwh.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjbvxdp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwzvryh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsyxupg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpheznyz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqwzzfb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnogqbi.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyesacw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mlojhjmd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ehstbzzr.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcjynjm.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2emiwqzgl.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qawxjwps.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eirdlpai.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcuoqpz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrylwrd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2anqfbmoc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvcqurk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2sjszfmda.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gspkjdef.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fydldkuj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xjogoror.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqeunwn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zkegxmym.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwftyht.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xxijgght.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2batdzjxq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqzlagw.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaeerev.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2delhieac.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlwyahs.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrcjfyu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaicjhz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbpssdm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwziyzvr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzuzbii.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtosmts.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxvqraj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2duzqujja.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iqngbgfj.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wymikozr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aelkipwx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxlnsux.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2zflgqohy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjtpqpl.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zcygohzr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2chfganjg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2cpneaqle.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbwowqu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoubgcb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgdvwhm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dxelaeic.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgelrkx.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2egwszosj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcbrega.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uysbcnck.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xfydrijm.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtokupk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2flmaxszz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vwechewy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xpokqdzg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkiaksb.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpgjfww.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfpijan.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbgmxqy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmwvhso.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfeopirk.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvcfqmu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqefdqa.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ilixkzyt.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpzzctv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2cykmnvuv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpmngdv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmnaxlj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2axdmyslq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcocmyc.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqlgkyy.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwouari.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ozoadcph.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuvuppq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2icrffbcn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpiuguw.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmbmxjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mquqbpxi.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvmiiry.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wbregppf.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfbgzxz.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kuupceht.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsezrlo.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cohtsdaq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2potvaxgl.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2baxdgmig.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2imsriyzs.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gneiynei.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyyahyh.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bckyfdcy.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqnmese.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvnbexd.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bznnqgip.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2obquswuc.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pcomvuie.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lazngotv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eajywsgv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jcblkovj.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2uurmuviq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwfkqpd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qaznwvlj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhpxjim.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnhsisj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xalqntwt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnaengc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nahalisp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2njtdpepu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pembwqmy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dumpqfzi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2whvmxztt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jqthtwbx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2guikzkud.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiuikie.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpipdwu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ehacdcjf.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2tihqmsqc.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2brdnfqmm.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrhdeoy.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfouckk.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwqxbxx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2daqwdpfe.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2llhgoxwg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpcyigl.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ropewhtk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2irykyhri.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlrsilw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jfstmqwe.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrwekdq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2sifeznmf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2atnvajow.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwgjdwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zltlbzsz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwdczdu.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2smzymrsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsxsgpu.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmvparw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2uivekrpi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2lmorzteb.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yjepwbms.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hobzayrt.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyapkpk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2onvuqjis.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2pjojebos.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2wdezevvu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2glqesrlr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ucywegxv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnnhmow.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2cizvgxqg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrqfllt.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2otlupuyj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnzicjx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nqleuwth.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkcyeol.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgkywjo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsyfdwc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uwaliuqs.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxxoafh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxcioyb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2okrkccli.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqlxzmb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnurvhzd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2leacmaig.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkayjanp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmpgzhn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oplpjtyt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuggvts.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqxltjg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgxmsvh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wncrpxlo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uecsyoab.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvldaaco.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmyhzns.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfkfwqh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmjztoz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2btcefnrp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2khpukjnq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjshcbfl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qeixybcg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwmacyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhroegqj.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mypdshvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2awipjdxu.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uavdylow.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhnmycm.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tuazymzq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrmtoph.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuleugl.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yruqoeea.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuncren.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyogueaa.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtxzxux.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2yheucabn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2aorftrfu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtisbue.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tywncidk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2iihvfhii.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcmcroc.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvkskvl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpflxua.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kecvmelw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbqddqj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2znagtlgj.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2svvlgips.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfponmu.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayifvlpw.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjcycik.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmdtirx.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2trmozfmw.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzowcygp.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2drfiqsuu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzihwncj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcztpro.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pwenqpqk.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2shchxdsl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgptgvw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjoeayxa.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2kosgixsp.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrxwsxm.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2utftvyww.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2isuozidr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tjthpkdp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzyelcu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oaggeoed.html


<!-- 参考信息 -->