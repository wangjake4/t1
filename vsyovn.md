代发 wailian999

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuwmldz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdkofef.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvgmswj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehikqatn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tttubtaz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wijatony.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pwobnelu.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfgyzuf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmkhlyl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbydypts.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnnnmjq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dultysqv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwiytje.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdxlzbv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2asbyoojj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjslhjcj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxdcelc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qffkodsa.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfatohel.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dreibbyi.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmysrip.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkokeym.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vihoxzlh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zckmfymh.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiqmgbk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2golmtobc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlvqdjh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzruwovi.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeoezcz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrqymdr.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2voifkflg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjlypgp.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2syggesgn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldszymik.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmzniuv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2dchkntfn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqbtzsy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xawcexns.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxvcjyc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxhnrty.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2oephcvzl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vozlfhub.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsosqpw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2piqzgsii.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnjrvvi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2irvqlqkp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2autgyldw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2amnxnhzi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wynwptxb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2epqkczsl.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdoqzvr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2axnzzrmc.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rpiwfpps.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ustrclmm.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbbuccu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpidrvl.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ptndnxqr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpbqywa.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2viddaylm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2zirkhgrr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2slugjukc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gaisryup.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoqpvoa.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhyfwap.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gusytkdp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2srpktckz.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2funzamqr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgojyyc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tirkncjr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2laemokxu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ardlnsiy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aklmqdyb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2slhmhjce.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lidtxlzb.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdhibah.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsbwgyb.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qinpvtjn.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2vpytzjrk.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmbbzdu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2yziuhwdd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvhmcnw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2igennfny.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfpfxrz.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvofdafd.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqrjxpt.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwucaqs.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdrvpkb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jowsfies.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeprhvk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrrdrwf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2czhmqyof.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyfbcws.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aksixvbh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fjclbnzt.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyqwquh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qykyqnus.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvxmtwy.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nsocpejt.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvwmmfm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnknlqbq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbfrudz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhaiahy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqerfmb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qquzsonz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2vsekitwz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxhavly.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pldvjroa.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtbsazq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qczcskot.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxicskhd.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfdguzb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzyeodd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2btpivhpu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqjselr.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2alirbcbg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvqeoay.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lddrwbtr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2outbtckg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2igtbesjm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkcbghc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2netqzlqv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnkzulk.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxvycyo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qjomxzhr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ihobhylq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiokfict.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxidbdk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rpltvsky.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gumrylvb.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2envwkijs.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwjutob.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnizljo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2riiqdvjk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvbfkwm.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuxvfmu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlfceev.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsznjyk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rghmndzd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2adsvmgpz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znzlngrr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkhgzwf.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvpwdfi.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2osrhflbl.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfxuwaf.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrxdqvk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvxqcbx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mldchuyp.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnetlrj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtzzzdy.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kmquyyyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yitvgrzu.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmdvgmd.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qahugkjo.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ziockgon.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdkihnz.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2abyflqcc.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2siyojjvq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuvzrcg.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxgqnel.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqsajxl.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrdocaa.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxctjdi.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwwczdm.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmonquj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bhimvjoq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2prwvgoqf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsresik.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zsejdgdn.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbclfyk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzcyncs.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2knzmxzzq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2etkdnnao.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgdtcwz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ynalqofc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmucmoz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfourtf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2dfundpjx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrnhjfv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2apjkseau.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2tuskjnes.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2evkhjprm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwibzid.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bobkdaer.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdowlmv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yemviykl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qtubdtld.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwueofh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nwubfszz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdltdlp.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2schmsebv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zkowfzeo.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiugrzc.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2uycmtqfn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fiemutnv.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xefsaaok.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfntupq.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2baqkabmf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2etzamtiy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlalkrg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfabvqu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2aqicyyce.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2twnvxvuz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2pylwvgqh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2cddyxgdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cehpafek.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwhkiyk.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2qscvhmyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmlxiks.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2pigyjmkj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqdzlvg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfcckvm.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpgimbz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2utiilwlk.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2txoyebya.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnoznmo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjehcgu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2drrlspdz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2uskcmzaa.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdrkknj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtpnang.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkxnswg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjajsgu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsyvkrf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwbmdkz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2aplueixn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yitjacvs.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpcifdx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpiezyw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pioznbgb.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqqlxip.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2knmysvmk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mailwclb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2juaniggd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlrttfo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffegzkxx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzqjzvw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrexnura.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwhbirq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfxfrqa.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvocvnei.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rivfutim.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpozjzic.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmdbkqz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sccakujt.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnovtjd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbmpgtd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfjksdw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hocsisfu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kehzqeiv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvzcpmn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zswaurju.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfswhmrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrqmzlx.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdazjej.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmgmvnc.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwmgmxe.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvflftm.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjblvgd.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtttxkp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmncqws.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcnxcaf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2wysfwiue.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2aoukgqjj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ytawceao.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2woydurfo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wyavfhrd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcutycqz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekynstuz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2offwhmfk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmbehky.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2cbigkjfy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlkwpuq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2afaotjwo.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxcltht.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxpiodv.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pspqfpvg.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqomojq.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2twacdnyj.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaicfmup.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcnumxv.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrtvsnr.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvyqzws.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrqzpew.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqpspld.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlszhsa.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vhchyhrl.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzmkclr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2yozntbvj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfowvdvn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlyubho.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2mwocnvlw.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgcdelg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hnasjfaw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtvhyij.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlfeakl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2peujvqro.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkyyekt.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lvononcz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cussfdkz.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xazhvhyx.html


<!-- 参考信息 -->