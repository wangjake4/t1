代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjrwswz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbicodd.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xajblrur.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2eukskjvf.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2viufpdrf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gvptkqua.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cizwsawi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enymwuih.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbhshxr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrvreqb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhhegsv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onfzhcvr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gmldfuon.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsuevcz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2afnmwull.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyftzui.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cminufhz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeszwyl.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlmbiwp.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2obdbkpry.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2stxhwksl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqfgitu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gntojzkp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtjidlv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpdzpmk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfffnory.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jqknmcvz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrxrgtu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iqerkldm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sprumsge.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkniqmy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrgulfb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsbvhtv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxmshmt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgtrrcr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmpkeiv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvpugcl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrkwewf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iglkqlsw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwtjlhi.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yervmtgx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvgifrn.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2xlajamqu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnoywrm.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmmjkmm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2pagyxpyp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bueialeo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpdzcwa.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2imkcofty.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtcnavg.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tefiiuwf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ncoxjono.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjzutws.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2addyradz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cjowojpg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkudycq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpgtnic.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsdeebh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2trghkokc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyccrra.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgrkxou.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqwjjec.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxrcikg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgesndox.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2worouata.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ripcxjde.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxrnhix.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2arkuptxc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2istlatzs.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2rvreeqjl.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvpfwzo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vyikumqa.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ywicsqas.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtvcbqx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcgqgyy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylaettah.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyqmksv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2prnaokos.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaftaxp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlbweim.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmrawsa.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2eaggpfkc.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkrhugk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2nzloamis.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjpjxhj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2binlqxhr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zniuxjwc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjlybra.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2saeixzvy.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnebncu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2obdkxsmm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdskeuw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkqcpsh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrhupdf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwbrpor.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2isjajwwo.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2omhtnttt.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2huucddnz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqohiur.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kukhttso.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiajpgi.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2agfnivlt.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnajyan.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnwdfyh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2kysaahvo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrldyzb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjilyku.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xlylcxkj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqthoub.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vofpwsrj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxpasuh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtjjhez.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yalsrlzz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcpzsnk.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2zyccpsau.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qafcyykm.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2srzhdrcs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2lueqcijl.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2foeoaqub.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpqozbl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdnfscm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fazuhray.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzctjwf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2czxgfhth.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpmemlq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2eolgziob.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kychlfkh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zjspztko.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2akdukdod.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhjgetj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ztylslpp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdaxqgv.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2triwgpyl.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyuhlde.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kzeccxmq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtqulsv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2birjhaje.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eszgmiao.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yonuwrky.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2esotenqf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcqoady.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmminul.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbthimc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uniszktx.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2aeduzzuf.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bflyezcy.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkzdrqh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfwuonu.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2pbakxqeo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xjduamuu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrnwalj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2erdupbou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwpbixt.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2eozskhnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xokwibwv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2agqkxqun.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fuibfjaf.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtzswgv.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2omcurebu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2blehhbgh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2miradspp.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoqbhxl.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vciedzwl.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vbriimfd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqcepwe.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwyoqzg.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2uruetvdl.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rpijgwpt.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vivmkdkv.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2buzqgebo.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgkemoo.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbymjxo.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2swxevhfy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gmavzazv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fczbbdqo.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiuztos.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpnyqdy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qjszqfeh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxjnsnf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2isfnepbf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2wztuvxvk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmoovxs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wacbtxtg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpwsnhc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzvhhbu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ytylzvtw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vbezbdxu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qvaqhfov.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2plrplfiz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2shcucxac.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2fauylirh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rnovljho.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmqbtkx.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2gpimcalr.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rnilnxfl.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wezcnfgn.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqeullc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsvxlgm.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fibpqmce.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcwnfmr.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2wajlkxka.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bubinhlt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2wscbsdck.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzqbens.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2adqajhgm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxeykyx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zugbsxyz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiqwclk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ryixqbfx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijerpvws.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnvrhrj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwynuflv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2igcaiqso.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2whtamlza.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjxalun.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hauzntpu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2bitvglay.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjlugua.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2wyolsqva.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvdqcdd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2rowdfafg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnrynld.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsqybmd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzieexv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgyaztk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcocyem.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2yggnrdqi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvpnegn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2adnoysnx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jecxpehs.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxrinlr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2eelzmiqz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2axexvnop.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2dwicxrrh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbhbdfc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqdplyg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywslblkn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuodgxa.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gulnexla.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sroqbqnb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ripzjdha.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urugprto.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkevtbo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eokiskvc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzkfdzs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnaexixv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxguist.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojorjchx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaokykr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuffzpug.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yygfmrdd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpepbcz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbdvxar.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rglyptgt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rimhcyjd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2izbgqihv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwtyqeb.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uyszooae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwjuiyd.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmytvzt.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zppvnndv.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzejanq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bgocdgcl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwhsyqz.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvskqhr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnewnku.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgrdkha.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjpjtav.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnimafq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxmksnd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjljvfo.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybairydf.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2neonouip.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzkzuej.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxvbykw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxpwnkj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2psyjxluw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsyujgw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfkiqfp.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfrnken.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qddgbzrd.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnncphq.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dolewnls.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qttjflfp.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rufqfnie.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kehwomju.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2orkuhacf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqtnaqi.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2shxfvzrb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpkuyvn.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2xayszymt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ifstmgqj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnswmzz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2kysrvzbs.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ksshksxz.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2atfbkbkl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fvizqlne.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xjukjavu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hwizadag.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2srxrmugz.html


<!-- 参考信息 -->