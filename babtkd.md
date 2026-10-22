代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvqmhzb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmazdjip.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmwwkrp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfnkupg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxrqtci.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2immifpok.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2omhtgjkb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqawgmm.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qchbceqe.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiebovh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jatrfjra.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vpensovm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tndeygym.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvmjcyy.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmqasfy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnnezjd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfjexez.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cikecwdj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmscjou.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sssfvndt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrfppjl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2slndjpqc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2shqjeutl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlrzsrj.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2weekdzjk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnjnhgx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuqjuau.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pelagzhg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2suttbbtm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgtccfp.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbpfgrm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2dwurqvvm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2repffpcq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwfkfkj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwjxruv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrzivfz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtxwqmd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2cboobajs.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqkegfl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuofpku.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fgawggbn.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2flmukknh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dqulpjjz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2illkgmbk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2cbamvbrb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2igoqxexu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dztxiipq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxwknlg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmmnoqz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fzezubof.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2futqanlp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbhhaqt.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsvoavr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmkxdzr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoemjuu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxwgxuc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2keifcafd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbaiwtj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwsnzjk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2alivxtvr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzxcmtn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvjpujz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwfgwgh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nabkicqi.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2olxujwic.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bezrtpvd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2asncoxwu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2byffulhk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcksvqo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvbchlp.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mcclvdwq.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzqnphc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgvjwtv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbploep.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhlnzwq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuayrhv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cizttpto.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2votzlpbj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2duclhoff.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbsuqby.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmreryd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoesysn.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrxbsgp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqtbwgx.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvnsjxr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sakysocq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaenjup.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdagduql.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnshycx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcysawcc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2aomrhuaq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdfiyyt.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwkwlrx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixevkxxn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zggrllnl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjsakks.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qawejpjb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eegtbeyh.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxeucql.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qksslpfy.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdydwil.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcgfzro.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnnszvm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2posavkek.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fmakuhbo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2taeobdjj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtvhlxn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hnecujef.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxuokpb.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2iluhfczu.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyzgcws.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2brdttycv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2feqryhxe.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kavxfnrq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2phjsleja.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdffaag.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2brmpxnga.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2txqeyivf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2oycmbebm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmvztzn.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oohkqadt.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmtgpph.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgxminq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2sizcruuq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlmgsmh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qiimxosz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2olfhafgt.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdxxufc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ccibusjz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmdusmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqrkybb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2glsbhhlx.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dklqyagg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2exlijltl.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wsatpswi.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pclkvidn.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zigcortu.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ladnhrdo.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzlfryo.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzotwyz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgmuzze.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvqqcci.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwsydqh.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ultxunqj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2unvhcetj.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2unjhyugy.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqazqar.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2irtxrmeo.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmsmpyq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyaekat.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsxuxqd.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnqptnl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2igmfbisb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2axirpixa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkhtfhn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2yihqdfvh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwzrxlr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2abqjkrur.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhtfnoc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qeasxszy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kvggefvn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2sggcenbr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2accackaf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gotfleya.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcgenet.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvqzwhn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2yzesfnxk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2neaywhdg.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdamlpo.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xudbpgnv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2uyemkmjq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mplvtznd.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvovyvo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2seaoqbem.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jendcfsk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2heqltcly.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2owozwnyj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rbprikni.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2nquxvzvv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2tyspkcxz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2gndhkhuu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lxiisfpq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2jhttvrmh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzgrtkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iucvljio.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmarbre.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2icvfgkhp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blbqeztu.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcmyvcy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgsxcdj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zkljyvyb.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrfivlg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2chdulbpd.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvdnulx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwxuqer.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwwksyr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2blvrctai.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2vawhoiov.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2icrbrjqb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gnomvabn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmbdnne.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2omhidexc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqsrtvx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ekucojbk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2tejtnife.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2djeyeudt.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbtnbng.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xsifudvn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dtszxuqb.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgadkxt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqfecny.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqovzaz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pramtegt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiohnlo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kahgeuco.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2obixltaw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2anyeidtn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdpvyjb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2caftrrtg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yssvchlh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eubwelpk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezputjbi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbjivly.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2haojenel.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsflweu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2berjqprg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2awddgiiu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2meljawns.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuzlgjy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpisogw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rafeyxkx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mckauvtu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zskedvsy.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxouzti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2doqmofdk.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fsthfspq.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxjipfi.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2aokztgcl.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tfndftns.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgmprqv.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcrggmp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhrkhqi.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2efzsgfxi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2varcqrkh.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbgxwsf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmonrip.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbccvca.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzfshim.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhxrarb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nilggqgr.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpswiud.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2nxoyaupb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrmlajp.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dfggznmd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjbfyll.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaahkrm.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pritmytg.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwpdaux.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyvlzyb.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwunhvs.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgyzrvc.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2leldswje.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsoweir.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyqpodb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyhbhhq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnfumxy.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ouaijhez.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2jfucntlf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyxbaln.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddflkber.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2juhmvnnz.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlraxlh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2owwstyrz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdmcghi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gjieknmr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2avfrbsfb.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaguluv.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wgawdzjn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yduhjxfn.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmsahha.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2esvvxdzb.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2afusmdpe.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzxqdhy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyxakmp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nudpjesc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlzhkyb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbtfyli.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiqrqsr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhiacqa.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2upscfxgn.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2avkqmfli.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtfaqld.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2udmvpgtm.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wziplhvq.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xscqwtau.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdupdjd.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2esvhqohm.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpkdidu.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2edsbvszj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuyrsri.html


<!-- 参考信息 -->