代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qelslcuh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkovkhfj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuqujhm.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uelmgbel.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnqoyak.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnahczd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rtshkwgx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkovgnz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmqoerp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2odvjknsy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ikstjpbm.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqivtgl.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlfrjyr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2umbdlgyp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbitbdkk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjgihrl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wdctruar.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwmrnmx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2usehugue.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qoousnyz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpitzvu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wpperjfn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sabdfiks.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcbfxsz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhidltj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdlcnjg.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcvrmdr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wszqvoaf.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tnubladt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmzxbsy.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjujurn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxdydxw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2srpqmpzy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zktlcwdh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sivxvvla.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nrguxozq.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvxpldm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjccnvhx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhqhzrf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpasvoim.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfcifey.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhtyotx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmhfvhk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyesang.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcgjnip.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2znudfoiq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yqaxqdmv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cygmbusl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcrumlu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vusjangd.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxybbxu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaezwbl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ingtckcc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbrhccq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uohhlowx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvxrxpp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkrwqzz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuiwpahg.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbuinkq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdkpzce.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlisnlg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzqivid.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xieakgla.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvsomkc.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkawmyz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzkelfd.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrvybim.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdfbkze.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uyssuxue.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xftjunmx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgxhthx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kvulotxr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2npdgmsld.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2apgfnmbo.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2juqpxxda.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhmegev.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bxztmsyj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdtinea.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2btddgiya.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgsatez.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2oistukbz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjdohvt.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ytovjefi.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2kzeurchc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fizrogda.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2zifqbvpq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2stvgcegv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2otgzjssk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcmmyul.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrjqxzn.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjzzbua.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yayuwziy.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2coszjhlp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ueujccex.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhpbxyc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtyscys.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pwukpcbf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2rprhkvmt.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fizjshlr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvoeoit.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzezlrm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmbblhc.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcrfalp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rikbkwdi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2eifrvefh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrphjhhy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvkxzbe.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bopfukrh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2yaldrckx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gyomkywn.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ndenpwrt.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lspzmffh.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhuyxgk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2thrlczys.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxdpmfs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbavgqb.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xikdjxfp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmggeava.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmjqtcy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kixdhilp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwpdczh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2asmgvkhk.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpgmqjb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2yayqfpmb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzwnmbn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxkyiaq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlrujcz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2flnqkrjl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dldkfaqi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzffzbbn.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nexkstns.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rmymflwo.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2huwjhsji.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zttgdmyk.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbdhyiu.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzqgsqm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhatfpi.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeghtltz.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbbxeaa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwihboc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqwmebz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgfdiaq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2thumevzz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izzkippk.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2savponjp.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2loqvzptz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbdbxqq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lilfyloa.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvwvjsl.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2iercuzds.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmrxqxm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtboopr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxnvrwe.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxmbfcq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuqgqip.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2cavpcikj.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nouqaekn.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjtyebs.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dokclqgx.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fazxkbwu.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2poxuesyv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfenesq.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeefrml.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zscbbqxp.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbxbjip.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwetkru.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2agaocvug.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rzksywpy.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwnkfos.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnlrdzh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vkocjvnb.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fkltzbay.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vnayknxj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dclrjmaj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2drdvshdg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkwxfsn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzflmok.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2onazzwln.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcvcgnu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2sudnuihq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2idrojlto.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwsjrwp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2amrnkzkn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsfsxil.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhbbzcn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2njaumoko.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dtudlold.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xapirsro.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nalrbxpk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2igwhuuvy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhhdnii.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzeuwdi.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgkpfjv.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2qjimoliq.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvqsqqw.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2puahqiua.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2osnhguom.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dhthedzs.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nijaefzh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sykryzil.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwijxxy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2trrvotwq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tmddcusk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhluwco.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxdvnju.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2unkiddqo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2moryynyz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjxueji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnedoglr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixihuxfu.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2gvufgvnc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2keqvtbyp.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2avenaitf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2enoxkrnk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2oluudyqb.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ybudiqow.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsihcuj.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmiijzx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2kzboyjqm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmvfydo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dybjatid.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyjddbm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2novdulqx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjxzrnv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2bzialdxj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzizopz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2huseulqt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsfwmvb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzkhfix.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dwseuepx.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjxanvy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwxzxvs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuwxgth.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfznibm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2loxdmllx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvrmcqt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uichyhcc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfkqnag.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjudfqzt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuzrggl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sggihhys.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iztdknnd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2admtsiel.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksspdpge.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqreymke.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uiskysqs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ziufiaez.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2irukwkde.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bemenxgc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyackff.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmaxmxts.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlmqsdv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tinbxveq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfulqbgq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fheroqnw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjebvmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gfipxken.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpbvwfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcxrjge.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrlbmuo.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzxpzoh.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dylfnewt.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2flqqehcy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlhttuj.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2embblhuc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dogxxuxu.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhyecue.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pojocret.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ngahqece.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sesyqplu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2srrvzbmp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuynfmiw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbbvngw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuqpxfh.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xopsuwrq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gddvjere.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qklsifrn.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcouzjz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhsxzbq.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxyqyxl.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddntppin.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbiwilsg.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bumzkosh.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmklkvo.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2swkcjlbv.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tybmjfxg.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcgugev.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2swazmhhi.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsmnmyo.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lvawchau.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2htiriotj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnvmdnp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuiudvd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrotvat.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2znxtkzpj.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2arjlykaj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mniphgzn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pctsivlp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkpacvh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hohbdmnu.html


<!-- 参考信息 -->