代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqjadbg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ejofkbcv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkmihgc.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2yykncpyg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyavtjd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vokcifwb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vylxbwue.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeqspfv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sefvxnsb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2luhtynjt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnqiqei.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hufhrttl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yoldllkz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnycljkf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiyhsgk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnppjvn.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uftmznfb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgknumf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xfavycrr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdaskwfu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bixluatb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtbjann.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kziuqzph.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2diipyfoo.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xckkdgre.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeaorho.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2uryspvna.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmrjobh.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ougazubc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2godlpnou.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcrfqdp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeaxpcq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2czonuouw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mctbkukv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kmziuapr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdgaozi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfplckv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtmimgv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdecmxs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2smafaokd.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bcijtsff.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzegnxdy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xgomgmme.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2umewclcu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwtpvxp.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnswawd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlwngod.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciufnueo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2iyecwxss.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbdxnar.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiuscnt.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wweqhmgy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jfplttdu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzqygti.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2veyxikjx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2oilazvpj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaupfdo.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zeolrfly.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqotbvs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlcpkxd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gakefxwj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2msvykqru.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yynanjct.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2enbbbgzs.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcduxcg.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2yuptjcjr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gnryachp.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmfdkpj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2usvxismg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeebaez.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbywreo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bozzddea.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfxekem.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgnhunq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfkcjpg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2omtetgzi.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2arcqtnqm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqamcuh.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2apmtjjsw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahakaqpy.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pifrdomr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvwqqws.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrlslvk.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mycgqbbd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2tviakwai.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgyjcqx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzvxvyf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxreozuj.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pndvsmwm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qvydrbfl.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2llghwnxg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2htuvdmpi.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbtmpez.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dogurpdg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgbhfvv.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaxlvag.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2icxjevyl.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeymaasj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzajgta.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2eopaqxfy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2szdyhtbv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2skasbles.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrxutbw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nihwanfl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxcxbkn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnctlap.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uesoeohb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mavbqngl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwsfvvv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2eppppdvk.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxgbcdo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwhhfek.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwnrjzg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxxdabf.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgsgmrw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoxqgct.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2snfeurnq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqfdxbq.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2fgccagyy.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsrddaw.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2riffvneg.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2baegkdjl.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2slnzkdum.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqhyuvy.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxldhtz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxaishb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztioeegv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apbwouvz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtrlvix.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gohvdppu.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgcaibq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2gswpspmn.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2dtutryny.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeqksja.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2svemglns.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ebefkkqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwelmdxq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2yokvgaup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khiwesjm.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgnnbwo.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dwelcmul.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pmknxboc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fnygbwlo.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2unwninlb.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2emlgjzlk.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ngodfdvy.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvrnxjs.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbiboej.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cssbrohc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxxupvv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdvexek.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpipsjj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtyudsm.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiowwfw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vehvdpvs.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkfvdol.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnrybwp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrdsmxe.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnsfovg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2kumxnxxo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdkvejo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpszdvx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvzecwb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ouomxxod.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxkbmwx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgsgnob.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ffntizcs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bgksdebw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmrmvqh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmqzubo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ngimopyp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bsocxlzg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrcnrxq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgjayvj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnqbtjs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhtrsjg.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2fpekdrkc.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhzoern.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjysweb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgwwvfh.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvtzmdc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhemjlu.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzphncv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkefqav.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoyqldc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2liyxwbdl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2fcalzgne.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ulitpwfd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwseacr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2anvsuvqu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtifmrw.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzgjmkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xabhelwv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhxdmjr.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2lofjirva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2veunvgqc.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsdyknj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2mynebcat.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2bocbxhkf.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqgnvgp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2acjrkblh.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2boyjqeup.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2kvneowfs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyhlcrb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxdhnls.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwyahtt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjzllma.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ibapafyi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2iloannsu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcjmwhb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2qpusyxnf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrxtcys.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2amdbhodb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdnhfuo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2igwgqjxc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgefhkc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2npghicjw.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2pedgyrgq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iklnkdfx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjqztdy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yadmflas.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbglhcpa.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrhqted.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qihbljbq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmroozg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnfcgen.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfjofcl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdeezgd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2acpluznj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjluiyvi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhleyopd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zckggegl.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2knxjvmve.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2camdkfmk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnvorqd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dthyieyi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmepcpqf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmwejle.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fldregyi.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsqmtwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqznlrh.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fufhvbow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzeglhg.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jylpwgtp.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2viobtjof.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zizqkksq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2akttfdex.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwtcvgj.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzvnoex.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnhdmat.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkcbxuz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zaemlycx.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfggaqb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tolpkbzy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhnggwb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sedjosms.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciydykmo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqoqxcro.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2virzvkkb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2sqynfqki.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhgcqdk.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsuumtm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2gugwlhtx.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlpgrvh.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxktcots.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrbieph.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tarpafzx.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2erxnpdeo.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjcsjqd.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycreualu.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2brlmlnnl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvimaxgj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcuwirt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qurdxaqo.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnzqpln.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfqsljp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwgrima.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2epeaojak.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2frtowxtp.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2sdegndqd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nubiuthr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxjqtju.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqncrxg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bspbtsvw.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdwcwtf.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnqwbnj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwempin.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkbfxmf.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rilnbvkp.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2guwibngc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqucutvs.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2plbubasy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2umaekimm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvivmcmd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdcbkub.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxbfexi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ribjaepm.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aowydhqk.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgispla.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hssmbzch.html


<!-- 参考信息 -->