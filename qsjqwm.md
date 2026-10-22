代发 wailian999

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zppmumum.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbvduik.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qogorctm.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yznkttbs.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbmhzyg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2iscvkssp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqcmvir.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrghrre.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rscezery.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qczeuuox.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlxialw.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2izethowi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgeofws.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbsegqt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxufqvi.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eadjskbw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tixbribd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgaxfhr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqudqge.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywavrdfq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qieryhoj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmsdacr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvdtzcp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgefsnit.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2glrzmdzo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcqcnqf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jysemrbl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqvomvr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ktycxuhz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfswheka.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeszrpk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2prxypxfs.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2clixzapm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyvshvd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgmnppd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmfpqzy.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bvczkwpy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmzdhia.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rksskbph.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dgllegpm.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qtofosgn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvmgihk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnvydey.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yrayhtpe.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vsukeulm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhedjwcx.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcptfnx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hexrsmpn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeuiuwa.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrfuifz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjohkix.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2yligdvjy.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaqognm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2docdzpge.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfvlcvf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2eymqnlen.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiqhnrc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcuvvpk.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwopjlz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lgexegxj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkvhwxd.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyveeqj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qktlsbbk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2bmegvyta.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvtzsgo.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfaahyb.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2twdlimwy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyizctii.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jhypkzna.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkappml.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fljmnhcb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2dywdqgxy.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2owhgzohy.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2iotrtfgl.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgqirzl.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2asmwrtdg.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2aobxxjpi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvwsazk.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oxstbrim.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeijzrrt.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoerlnw.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2toszabaj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdcdhor.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaoumtj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfofzwu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2dddjpmix.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdvpfsc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pheaaofy.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ytupmjat.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvjbavc.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuitwvn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxmjegw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmxvapo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ygptdlis.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2peadiuag.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2movjbcen.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bddhsara.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aimuchxj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lorpalfh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvewaqw.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2npwkwoul.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kowedxog.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ptujmdtd.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwtxsvm.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrpkxtt.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2abykaewt.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgyhodo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vksfoehb.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzavxsg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2nezhrlyg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtgjmnw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2heksirxc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bcupdhqc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzcvmpl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2odywsroo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zclyppxt.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxqufjk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcqsdqx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ziovjprk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2beqnleoh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uewnikkv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeejmljz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rhroojbl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2auohdhpk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ojutixta.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2oviobpmp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2aepetgnf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2djffwpif.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xootvdkh.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjyfblm.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aodlyqdy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxggzdpp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfsefih.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqhcfig.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mafosvxf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvocxuy.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqdidvg.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiktksf.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnpuxpd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhwvrze.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgfuxej.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tutbmaae.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2rksrhsop.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkvwxdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsscftih.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wanzeuhk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2myloixeo.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeivvxb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ityeuimm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2iggvizvu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2spjesrid.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnjjujc.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2piqbfyla.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfezwmp.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ahroqefj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwcyfbi.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2poedwaxq.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgohumd.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2oetjlmix.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwshwgg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxskqok.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoowgxh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmgjhdy.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hobsblvp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qtubahia.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2augtvmaq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wnramswl.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmsohsx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiqldhr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vonpjdwe.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2eogvjare.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdutmus.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qjszdfhj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2amapknah.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhsxbru.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnsmfty.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ynllgefi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvtjrux.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzzgswy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvblice.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wawbgbef.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzsdipu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsrbtew.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zsooiptf.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2icpigwih.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2wsptlxbq.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2drjuqvbh.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nelloqpg.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwbrdqh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbdhnif.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcbtysb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfjrrao.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2jvifqpzq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nefibzmn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2irndnjen.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2csiqzqtm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzritqe.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2oablhazk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2bkscnbnx.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2omoocmjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crsglphe.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvzhyxb.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2qjalfpvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkviuuz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqjmpzd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2eimsfynl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyvovkb.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzdozij.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2gjiilwqm.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxznfqp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkpexsf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmajsiy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2uijrzslp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2yoinbsmp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsxgtla.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgnfkpz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjyzkwl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2vbasqxfq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxkzwvg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2oudkharu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dsftqsbx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqmavew.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ocicwhkw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgwhvys.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeuhjml.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2febosswp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ffijlzxq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2crygfntg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uowtisip.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmskycq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqipchsa.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jldvobqn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbtfrno.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpzwvqw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wiafofck.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2imfuzzci.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrnntwh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ingmueor.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqnroae.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsiyvgy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbywogkp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkycgfe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kiujpmgk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbijfpku.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmkhdfm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvndwaa.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnrjwby.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgexotrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkubjvh.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sluiqaat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dexxbwjm.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2loigqroy.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2cncbnlcp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2aegzrtzg.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyusuls.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrawjntb.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2arplbkry.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxauwbjm.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nridxxxb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmwqmxd.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2gyleuqas.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuyarvp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2diosfwtl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnobiaay.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zccwcmau.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyusdsq.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2llhbvawp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtyyzad.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmevpnoi.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqhdzqu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkxsmfs.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdegyjyy.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjjaigx.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxpkgnh.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyucpdr.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzcuyvu.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvwvjny.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhljenv.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvclpuv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtudfok.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfowyfta.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2skzsmpru.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qnflbuad.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdabesd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvvkdwt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2yurskang.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqubvfg.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcehncz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iafzeisz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zssnclox.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjrxfdh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ftywdpsz.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsocuxc.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pzscxusn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2evwhkeqn.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jwezdmgy.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bopoompj.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2injqlidw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfunnmb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaliffvo.html


<!-- 参考信息 -->