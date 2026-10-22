代发 wailian999

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrnfjsu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdgtycz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxlygnl.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snozvuab.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bmabnvpu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfevuuf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcodhyw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2swwhdkzu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqddala.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2drkbijdp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2epbxqlgz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzfymwn.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tywuwltz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2idbnqnoh.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2exrehpgq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pafiqqug.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zhygyzzl.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdatxsev.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2yfniltkb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kibtksio.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgkuple.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2flqlvops.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyncntt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2edxwdnby.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqtipoe.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2juohdjyg.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uippbahx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mevqvipj.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2isyexdnd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyxojfk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zhisivnq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtuddri.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ceefjboq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2apybppfv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2zduehmxt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tluhcgdi.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmmlqvv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmdueqw.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fatzvkqb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2skzcntsf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yllukbji.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lifbscyd.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvatgzd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcewiug.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2awfurhqa.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlappmyo.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cfomjqdh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hukqkagd.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfkqugy.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjiqvnu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uzscchlu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2lixescfo.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qugwaakp.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2smvcqqtt.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwdxfxj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpyddac.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2vajwuvwr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrndqby.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bvduwhgj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fabvcgpn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqgthlx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hdormrnf.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rngswlrw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqqmcly.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pblnciwg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcbwrnm.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvzlcdf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tthikihs.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xxelzbkd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2fajxpzfn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vldxuslj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujezewso.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2joljjepb.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlgdcdf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cevdtjdb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmiacom.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tsacjzvm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkorzoaj.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cezqlicb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjiazpa.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2virzgchc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhfsirv.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2usqqvseh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvpnqkn.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiyiysf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrzeyiq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2syskusla.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uofpbmtl.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaynsoq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwkghqp.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmuhzcg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzyueej.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfgyhvg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wopbazws.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvcfkfh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbzmdjm.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2akhmeyxf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwffprak.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vuscgbaq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqwinzo.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxbppnc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2weymjdzb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvvkzhg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoddqif.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhxcgoj.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgthwwf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtxnchk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zsogeycn.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2izqzemec.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xotcuiol.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqztfhg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cetbmefx.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqaucch.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sxozjjoo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfjlwgd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tbljojkz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjoyzss.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkaijrqg.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2aggayaaf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqlfttl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvkmgko.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtinmye.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnugmhj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2upsgrnmu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjmvuke.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzqjyon.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2tehgurlt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnimrjnw.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2udhdqhil.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkojapga.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxumpgf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2osnrxoac.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2krrykymk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgarhmx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2afdcuaed.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yavjhxsg.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbaxcyc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2uiokpmrg.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2bpysaxae.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbipvdw.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2eajbnsxv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjbdxml.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcclmubb.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2itxnkmsu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzdcfuf.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2guwvlxem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krrimrmf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxbzqvu.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdomgqa.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2opcmomme.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxkedyc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpguqod.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2imbonktq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bauonsvg.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mblyibto.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqnavus.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yikoqlcu.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcrjliu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2cmopbfte.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2aibcudgr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ummcveiz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fnopnija.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhazbgn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vgntolcc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxwxapm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhoqckm.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tetvowbe.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmllerz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjmwlvi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mddsadik.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsiunoe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hftngdjh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjerfoz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwhkyru.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gspykvwo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbetahv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tgogzzwr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2licybqap.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvmjguu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmzqutr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aezlzqvl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhkhdby.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhzkhgg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2soutddra.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2xralbqdc.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbtoqva.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2onnqxpnv.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaebmrv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwxjiey.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jabvlwlv.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyxaulg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpsuwtt.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsbyfbh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwnpuik.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2nelmstfc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkqmcuu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqaoqej.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxojpcz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2iupcfwru.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rofmeuwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xueicvur.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxymcvwn.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2eramobti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rirwksoy.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrjwidw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2jubzjfqb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpgnccb.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwlcyew.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2acovixic.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2unqhlrng.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdvvnhj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvfnvyb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkhgvqj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2iezwljkb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cfeeudbd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzihzgt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyxaqrh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2qczssgnk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2aupveuwv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxpgzvr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2amadlcqn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcyyctp.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuzuttu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2duiqlclg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkqvrtd.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmozicf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjqhvwd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iidpvtqi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfudiuc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmejmct.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqctepwx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzclyatk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2euzmvoou.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdytgrye.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtftakr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcooojvl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfgtzqd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtvxuhj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbqqjct.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2puvcqodv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcewbsuf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqipgao.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lunusntp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwufnhn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iziylfdg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmquwxo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2deaxomzj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2otmqlajl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knzkxljm.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xksxjcof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqcrzmu.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpiacab.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkatcvr.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2edmblcxk.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtnydwj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jujxcize.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2awcscjfw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpiahdu.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvpbepp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfjdvbj.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ntktjoqo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcyvccy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxvgndn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2glhxgsxc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2outakjut.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfqxxgd.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcliefv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtrnnln.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbenfpo.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcobcbc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbgeqqv.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2invxtreu.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnltbds.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lilxvoln.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2incuvmme.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2atwweght.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2haxwitky.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lghcqtoz.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrqvpfs.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lleqetde.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvxxpac.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2zgadusub.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2szdexqec.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnhwiwe.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2aglkvnig.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtnfpxz.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2euiprlac.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyqglcp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcgxrsh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyynvdq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfyiidz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2csjdtjmy.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuasbwi.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2owghfucr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqocrrz.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2doqvmjgw.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfacbfw.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cajvhjpw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jruoteok.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbbivvd.html


<!-- 参考信息 -->