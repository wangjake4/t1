代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vippybkn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuqnpkp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtkftew.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tltkiemo.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaclvdb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbqnmdt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2runejgtb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cixzcejk.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdrfkjf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqhvuik.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2eqafabgt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aegqprtp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcpttcf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzjbctp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pltmbgtg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjzufgv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiulxfa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2glojpcyg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2acgjuges.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rlysdcxq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyplffz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkimddu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfcymwi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eutygsjq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkcqpjw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wopaohch.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bgluolbr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwacdzh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2owejdvoo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zobdaimn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdktpij.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpiwjrm.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yaubrkyo.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bejjgxns.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2causpsqi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvuixrn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2eukvqjux.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dezgjjpk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2myvxfvvu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdirsypc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tssyldcl.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdyhcxt.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpducgj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsiwjlo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2arwtevyv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyoenic.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2glnvxvmp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jzohlhdv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2syqwyebc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2drbznnfb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrrqrgf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2btbqeexl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rknxqshl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpkpmpr.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaiybrn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjfiutq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2awkjrkfc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bsonxvwd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcsgfps.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2fndmavrn.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2uvciisqp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkkuxur.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsujpoz.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrbxjnr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2djwbnpwh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgicsidq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqfhbnh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmccqgl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxanbwi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vglgfect.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tplzbevl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2guucqfmp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlkhpwp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdnizmi.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yenpvioc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxzjhdw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxusnah.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ezngslbm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ervbeedh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnsvdbv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzerpke.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mlonsgfg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2noipowwh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqysbfpn.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2htbobcna.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xgamwrvh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2izspwxiy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oksumquh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2upeypjop.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpmbhtd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcjnapc.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2acufxalc.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpznoqo.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxohcuv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqlftrs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fddlnsci.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2tdybvbth.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hybvdoad.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2acleqrmg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wohjijod.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgnsflg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2epciysod.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cthacoxv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxtxlfb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrkzblz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcfxaky.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkfjyhi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrpirxf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2crxfqodh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydstoznf.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2sibsstna.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gqetgekz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xkygtbjd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxzthbr.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxbbjoq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2elqdxlqb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2accczahw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2unmidfes.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2udsbpgax.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2affxzgtl.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2afjykllz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qouhqxcs.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtrbxqt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgndsekw.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2knncrllq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2onshgpku.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ifggyjnx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nrscaviq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2izojmakw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkusvnq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2aadplrfa.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzthatc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xupsjucj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuwpgxu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxbafyl.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtokayx.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ugprfqbs.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vjieygkd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mspynvgd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hoszcprv.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2elmtiwrz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjhceax.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xzipncfz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdkzwat.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgylmoy.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2afibciaa.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpihjxq.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mxiasioq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpoveoz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zwoyhxax.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpgxmtd.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2feaupgyv.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgvupbv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hokakgxw.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnzgnae.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2unjsozfc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdjseto.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hwphygan.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbtpwtb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfwkbeh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2awenfhzq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjuhqck.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2azdryuli.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2unbicauq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qilquvpr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdgctcw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xvudklhw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzsogjm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vimnygxb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hiipygpi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2zurrkzli.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnxslrf.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2klkwsdos.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhalvab.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhcakhc.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gyewgptf.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlyfslp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqzhspw.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwnthfa.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlxvdsf.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwafneo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rbstrltm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhulkop.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2sepwxmvf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rahcojzo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzxpdiy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2oyommbtk.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrsouhs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwofohj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmaohkb.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhpavmq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sictjvll.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkczlyf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2xopecxut.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxhznrn.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yxanyrqu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgvpkra.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhicvzf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2uirikidu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2kxotxfyq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2sozueiam.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqydhiz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpcsdyo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiokdit.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2bptessal.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhfggrs.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuyowlw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2otttsnyb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmajaia.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbiuyah.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2bzebfiat.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjvkkhr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dmglgtbv.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2dzowocmr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zspkvagw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsziytf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bekufndf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqnqisb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwintwkx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjgsikc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmxsotp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzgxybw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnknjjqd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbhqabn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcabryb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zebmkeof.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlctvvne.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbefzve.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxwddrf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsulrmh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxphblf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjsowwg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyjtssr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyunpodf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2efvslzpv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhyuvsf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbeqczm.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2orjytdlf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpnsdmm.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pjadjvlv.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrvqrfn.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fluvmotb.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnvurux.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtilwivc.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzohejrc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2buoeqtyy.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2abufrslq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoqoyzl.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2wcflputd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpafqjw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzoggtj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbllhbpv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpdkais.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2akpdrrrj.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hmegogcm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrbneel.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuwfrya.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmrzjrp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2rnychozn.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuccfnua.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2szgjtfvq.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hydsxdng.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjticdt.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpuhmsv.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qmznxjya.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vykpwset.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vljqexka.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfumtjvc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2euxanhai.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfcqjjv.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiiunwf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjxfyap.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2zycanzpc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2hltdygbp.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2izhycudk.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2nsodinpb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uesxcsgw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmjsytv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmpygsz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkdxsxx.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ezarwimb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzsvirt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuowkzc.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqoeqlg.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yvelqxxm.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2crbvuhjz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtdwfih.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwoobqe.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2phstwtve.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdjfuul.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2sybyixaq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvyxdkr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fubsyznl.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuddqox.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgrpydj.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvjweex.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uccwqafj.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2esnucedu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2udbaatoy.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nykjeiqi.html


<!-- 参考信息 -->