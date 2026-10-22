代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bwomkmfp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpvspxw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmbsbll.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2eazkbnfq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bodiblqh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjfpdyj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnelony.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asmwofbt.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxycmxh.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qfintcwn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2feqqxmfc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upeekadg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gacgpvhw.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfllyxfd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhkgqer.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnisuwy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vztnilxs.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2rculoaaj.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rucidnyw.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhantew.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvfnmmy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2stgyxwoj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dehlioyx.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfjkfrv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkpejvs.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrxhzya.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2kklttiqt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qupwocnx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsgzozo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrpntkg.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2brthmmyb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyjbwan.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yqycgasj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpmygtf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxswjlr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2crswleig.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsrozdb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2furhclnv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyeuiyn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgljrtu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rxctegeu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqbutjb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jfovcrcj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2urffzwvn.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgualff.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzzamec.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwjspas.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2brxuxjcm.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2asczfput.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoggqku.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2muferjqt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2jenhlnol.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aryzagee.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbvdexo.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hjziblus.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvzhckb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qudgszqg.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsnwzzx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mzduhqca.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaflbdo.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyeldke.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2abqqtizb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2yyozdocg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqvybvk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mipwzcej.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qedrkhfl.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ymavwdbr.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2sdftdyqc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2bzaljlvc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnhubbs.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ezihxkpv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wbehktwd.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpwsqvy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qzljjzlb.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkrzpzm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2novvygrn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvaizag.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2silkmujj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2epsluaoo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkvnbav.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2nbufacza.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2klvenvwh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qwstuxdt.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2amccckek.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vlinvgzn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxxwgxt.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrmwyto.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiydiiz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlrkhlf.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2inbsjuaf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2arqsdxtx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwderkt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lolinjgd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2suxbqqjf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqkdqyh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2makwnmls.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkxtube.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2oufjoafv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tuouutee.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjrsevh.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlxordi.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyugpuf.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpmfnhc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiutoot.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkauard.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyceyje.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgprvir.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzzitqj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpszhfw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmxxctb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpjarpv.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxlrbqa.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2thutftvj.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfzcvok.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpvfdea.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2guibqbyd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2lracjgum.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2emxwljzq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2gbftkrqv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aejuofan.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vzytzkxz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gkclgndd.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkpvwvt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2lfptwqci.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpijqfk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2iomnsphx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hklibzkc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2auxovptw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dbarvjaw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xavrzmom.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxyynxx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vldkjalr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2esxmhcvw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmzwzuy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gatxiqij.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtqtvut.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbxmxyb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdrnvex.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2upwkfrkg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2scsedkum.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2feghkqhc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2urxqikax.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2upxepucs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2catgaqof.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2aqahposj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qceplicm.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2suelhjqo.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfhgrop.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hxohsqiv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2flcduafx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2lewxjpkq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2huuqpyeg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbnvpgc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2gajrledp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csfvdmng.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2obbnehpb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2atxgzlsl.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2evxqwiqn.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xylxzzxy.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2twembjnw.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ripaaogw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nssnwgvq.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yooayotk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnzhqag.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmlnvje.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wocqqasx.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoxziky.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jntocpwg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2koveljvf.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwmhuvx.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdonijj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcqogts.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hauwhbjc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nstwlsyv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdmgyxn.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbwdzky.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwuowpm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mwoimtwa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqzhfke.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2cfypenza.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qbijmziu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzyszjt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kdobyzwc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgyhihf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zfejxtqv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2plhyxhma.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcxyaqq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uyelkuxj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsuegkx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzcdpqu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2czhuprmr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcfjvpu.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2kamrfxpl.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxxfrlg.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsobxyi.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zddvavhj.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgqrtpf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qeelmdns.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2otawewed.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbiyzwf.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnmdcre.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuwrogk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2etpccaio.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2qilmoyxz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2tptqxzqx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2nbskjkls.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2misnutwa.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcnqirj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2upvstxia.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2nltkpbpy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvrpfkt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qauqklbo.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdzvqjt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2arsgzpmj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2wejjuacw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qmadotnz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxibsdn.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2zojjabdd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjkfwox.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2wifmdpxv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgcptym.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcdzhjp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2thhiwkti.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2opacadde.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2bjodybgu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2nrggzzaj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2egtbkaos.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2etrekyuu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcletfn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2obmxkuih.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnhyaom.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlkklzi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wqldrsit.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2unaligpw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdqivnd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzgsjab.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2juuldjwc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcarzzu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhgfahx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2twvsrvlo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvraqsxy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zssfjxkm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjanovyw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fshnccjk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbbdxow.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzofxtpo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rozxypfn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsbcwpo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhkarey.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlnsvqw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2szobhpnv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2havcggqw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgutwng.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbuklfe.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nczcwaws.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlaacnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhenmmz.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qrweddii.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypymocua.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtowocw.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2icnajaug.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzfqlpx.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mufbmajp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbgdggq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ouffsfjp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgezadl.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hucbzvua.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxvjtqi.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbuddty.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwpgiit.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2htovibik.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvggglk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2evtghmae.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrztubrg.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2savoyyfe.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2patlgoii.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyhtgau.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lksvkaws.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2sehgcgvw.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsuismv.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcarvzg.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzvzycu.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbgmlae.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2owjtkwsm.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2liwpiegu.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvymljlu.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtxgvyn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcyidmu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tosrouym.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2xoanbukl.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzxsozc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2icjneizh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2lytuwgen.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2oljtndej.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrewnjq.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdxyxok.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ngryoljf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlpgpdn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xlaxswms.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2irnrbroq.html


<!-- 参考信息 -->