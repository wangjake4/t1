代发 wailian999

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vtagtqrq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2alyionti.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2eiywbslj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgkhnfb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2drtgbdbv.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2evynxdwd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jyohigua.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxlkfpm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2xryzgxhv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdrpnyr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnsdhfy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgenskm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiqrezx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvzglkt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdymcql.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qociprqz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnpobnc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnjrnou.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2tesjbabz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgvzotc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqlymkv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldligghd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2nllfbxdz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2riazcahp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvbkpii.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvilxpuu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fthylgwe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2afnombuo.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tefbkavp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2immkmtjb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqewkjr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvszwye.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwrxhdz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2afcrtxfv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtpppoo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tazoqydd.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wypwwaqx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsuqmmr.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yonkyblv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lybgvlyz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iybdhwxv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2euhcdjto.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lgayuuft.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yndpyals.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2btvtdwpn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2myslfeox.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2unrnfqyq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyxreee.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2krtowssz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbyuxzt.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvvnbog.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyhsqjn.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2mzarosfb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhudjwv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2vllfzpuz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2afwwsbvq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrxufyg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ankunzms.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtpqasi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wbaztzia.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qiewpscs.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvneyld.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dtswwijw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2panmvnlj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrsjxzp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzmdttp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qluxfkxd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nljxkpio.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2otkaxlwp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmcqbhe.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2olwulplw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjuurwe.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfborep.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkkcsor.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgqdbhj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2eswyyxvs.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tahitmfz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiafzjzb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gemxiore.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuspzrzl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2syenpdaw.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ekackmdh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvjrtbo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2agapzsme.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtenspn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gghbeohh.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhkrmjc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxpaszt.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkcxqul.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpggzrl.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkxnhii.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoufvkou.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjqncbp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ealqxkyg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuydfau.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyvzrff.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2onhlkwyz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmogffff.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjtwtvh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsijlbj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdnakzu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbxpkgm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2skrorkaf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuyedho.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwqzavy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucndddmg.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2cczrhyvq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yexazjac.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hfixmsmi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyozinj.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2onidjpri.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2exjnzvvu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ptycclnf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2apkqawzq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qjavlkom.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiyqlwc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbcztqg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqlpxmw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2owhlnfoy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2muxbicjs.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuhaxwb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaajjxwo.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2clatntnf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuepbkh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gpifhkrg.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hyruhpoc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2qylajfbs.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzhjcln.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnndyiy.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujprvlwg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2udyiclgl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcmdzwb.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyzkifk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdiifvlk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2bffgmwbk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfgusou.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxnflvm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kveyfuaz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fpoomrco.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwpszfe.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbdbtqk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqzgkhy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmywxonw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2tneicgtd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggencdaa.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2twpaipxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaloeij.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2utbcqsca.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tntsowrw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwbhfxq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2idhiqafh.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmbbcid.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqfxsol.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfvwriv.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoosvmg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2euuogcmc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2unhosrgl.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuirlbw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2npizlvvv.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkeiipq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rncvicij.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwwbhyj.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2riqxukap.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2etuavnjb.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfbfxcz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jtupzxhf.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfuwvvz.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hqatognn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvqzbpc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tdabcuyp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbxsfix.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jllqmpwj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2nkaagnsv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrmonqz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dozjkida.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqwdmld.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzfluaz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfsiyyk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfvljwb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jguqbtkl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaepmfz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jyybnvsu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2josvxtaz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbdqztv.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzooenk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2rthgaddf.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcsvwkb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvmuatp.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvvjcqk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bybqpjqp.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbjkgqz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kdauhzyh.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvkgyyl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbbrbpz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2annwfoau.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnplmti.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2jaofyfyb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2igvespcp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxtclyy.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtkzbte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xboupkhk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqdrtdg.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2mbubuxgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whpbmdiw.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2oapwsfro.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgbubie.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2hllbpfhu.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhrjjds.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2znsblsjc.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2wimnvxrb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2kriyluhu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2mamtrlty.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2bybxrbfy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2dafsbiyu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2icbvxygy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfwenxa.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuxdeiz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2uhufktvs.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2mojozeas.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzbtzad.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zyafmdtz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdajdbf.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2omduuvyj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2djgnzrli.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pllivvgg.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrxxkri.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwhwkge.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdqrjgl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwnaljk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2opadjtnh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxtraty.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvffres.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oakxvkfe.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmowoime.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2airnjppp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukywpwbv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkbmthj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxxbese.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeowmym.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmnajoq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tegjxsaz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbedpyn.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmpumte.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2itfltaqi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2glzkyhew.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzposgi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2suwualrs.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmitqfac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otdghkae.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uolejgal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whejhtpn.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsuajyq.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsworrp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nltixmfr.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vezvjbqm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqimcle.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbrdfmj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ultxfbbj.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkftgtg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2znjvmvow.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2dztmxumf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cpijjxsb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sllmjvmk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqfbmvo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtgkhce.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2shfwrpbu.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2khywecyb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2akifaxio.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaxbsqv.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdnczpb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxfyrxz.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzrehyi.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwtwhoc.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqertqd.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpctcyv.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fecrjffc.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fxggjtou.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzttlbi.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lfknbbif.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcufcqri.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnrkvun.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxgosvn.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjdgere.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdfwhjq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrpqvwr.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlrzyuq.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2yunujpod.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqfzqhz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vilznbbg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jkplgcqe.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdodxvn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eskrdnwh.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dbderuim.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yoefvvxc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ozstqerd.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2itgmvdvd.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cysmvzrr.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcpvvth.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmuwxuq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2datrtyxz.html


<!-- 参考信息 -->