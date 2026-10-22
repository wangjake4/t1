代发 wailian999

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtbviqz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqctsis.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2poigjada.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kiczjrgb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gumbfjgu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2udedfryo.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vombkzfy.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcilhimw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2usfvduzf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbwnfcv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjxubmj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxunfmsw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrspuys.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkdejut.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcqmbdc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdbnhkm.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2artjcsox.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyrdfpu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpscztc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbxhtpt.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjgfpam.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uecmvawi.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hyczdjco.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ichkusnx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2voiiohaf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgwnskp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2glvmcbko.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gffomnwu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2weqhhqkl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2elajkdmq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aguunfbz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lukyrfwa.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtwgorf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuakotog.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2monbubye.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2irfbttrc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzstjqo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2muvdutug.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxsgvle.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfltwrsx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bupvlrmm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyrejrc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjkhwnu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsfqlyj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kulnvfiu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qopezxtc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuosbxo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2bghlyqla.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkxcehl.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqgitkv.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zajbofkd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjjnpwo.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vodjlclx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2veltfzyy.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqybpzq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2oopmvrpk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2trtbrfps.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzvpumr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jokhxebt.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpnerrq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2quxwqlya.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkfgdbr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgslbvh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2xgeuxafc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbkawmc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2owmkrpad.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yavcsrkp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2howgqmzq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyajosb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ythwnyql.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgegiui.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmltdcx.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvvcnia.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmvtkev.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qszdwofe.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2xprbhvtp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uyswgcnh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvtfjqb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdumjua.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uslcsfhc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvdgwxm.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2spmfohgs.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pplvhsir.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqgpckh.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhtqqip.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2yooqwsql.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xqickada.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlurpqc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ginsvspj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2homepegr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ricqswli.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgiartq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kylhgclr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkdnckq.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jiblpfsv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2idiuahzf.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2cihorspd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjscijo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbdssux.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxelsap.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzrgfzu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cflsvcdf.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2itocqpyl.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwqxbtb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzfaqlf.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzntjfml.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiopqig.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxjtdms.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmqncfu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofheljsc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbailqn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2biaqwshw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fbokjoum.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2puqekdbo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbqkofb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dalgwobg.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2umodquuq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2oarplmtp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2expgvxvd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcquuwl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxldiph.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2eewsqcdk.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2frjqksoh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kswayijj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgtbvuy.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnvldax.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2oiedlmvo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uulairfh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2airfgkgn.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzwzzdh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gftnjifb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbifhnf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvdqxjp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfydlrl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vskuwenm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ambhhniv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfnevtz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2aoaacqsx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnzsyzi.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgcsotq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2azndkmzb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjdfywq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2trkxkiql.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2azxmvtjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kihdubin.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2niplxura.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhpniff.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcoqncr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbcmblf.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bhoeqxzs.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vykyhoou.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qggelxmi.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2otbwxaqn.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wznnotgx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ijklehwr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzvsqtg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gtauaszn.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vwshdhzz.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2tojvcryt.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wopdrveo.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrfnkku.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hoplmgpo.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnwsifr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ermchfzv.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2djfyboab.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wepieyyh.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2magkflnw.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2pobetjtv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2madwghcu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2golmopqg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ezakycrn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvqcuai.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2fzovsyvl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbuevsb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2honjphcu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bumlxtym.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2engtktlv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2estpzovm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpjrnfx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnusbap.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvonelf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nftithiq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyszrti.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgiotqo.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgeocvk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyozjku.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rgddfgky.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2urhorxxi.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcroyry.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2axiofvkz.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiaaqfl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmlnjxz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2crkzjibh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cxagfeke.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhqudhw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkozswl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2czfdpphq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuekouj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqagcew.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdwsgyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oojvjsqa.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2sofkdssh.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpfjdpx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxvzwdw.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2rucduygl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxrywnw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzitawp.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2geinzpmu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2qnraciit.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2wjoqgaxm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuvarmk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2eflveuhy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ypipqlwy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qpphhish.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsehxpd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2nprydkfo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsdzmtg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdzyllp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2lelmfujc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqwwcef.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qoksnbce.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qscoaxgw.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ohioauun.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2aquooptz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwjljcr.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2deoxywoe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpdlcvl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oatcgubn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtllnuo.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2izirliqs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqfzoys.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zddctlzb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sppqjzhp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2awrtgcle.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kachwray.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptppxhvn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvxqfha.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbatjyv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xosurtxz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2svmhojgi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbximzc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2womutisp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvudvbet.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rymvdobx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qodubikb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhauupjf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyxyeyj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2awnqqutw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzxhkxd.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzfacpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bbktprmo.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfsdljd.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2uansiaee.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cldsyhhk.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2okqkympn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgmdohw.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkojwpf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgxlmcc.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ultcmaqu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhglilvs.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2cihidcry.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2htuacbfw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncytuzqk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpkewwn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2llehnruc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2epdbhxby.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxamysb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dpooscda.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2exqafwla.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxbmfpu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2arwbcply.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaevijeq.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tilcmded.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmttlisf.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqtvwwr.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkbhkoc.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxvogts.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlqjjkp.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nggltpjd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2scwptjal.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbauvlv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jveutzmp.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2kycomued.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2drgjoftf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuuqfcv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnvazqa.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2trpjfpzq.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2puvbgbsm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdvupdh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwuvtpg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkvdfub.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgpudqp.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pzatgtsx.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuyxidp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lwylqtjr.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkbsyyp.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ierqutwv.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcadelwe.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcwlbkb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjclxhbr.html


<!-- 参考信息 -->