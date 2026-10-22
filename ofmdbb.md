代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2iltshwld.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2edolrisg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2idcjefpu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2roatgcbz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hednmtcz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsrnwhz.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2luuzkwag.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvnblzr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pinvaxgt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfasucz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvzndyz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbkioom.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdmusaq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2niglxhnf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gmudgtrg.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2noxqkfao.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmxajzz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzjypqn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyhubbf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2asdtwjzw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxsjdpn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeeypkj.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uqckpyra.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqaodea.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmskuhw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqmnljk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kesulfya.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2loccvbet.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uyluewua.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlxhtjq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hloixzpd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqupeep.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cemdumrj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlaqiqtb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdvxhlw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyzjbuo.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmafjyt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmegggp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2czlchetp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxcitlu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mkprpbui.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qubtuupf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwzvtdc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxnsowz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qaomsans.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjwxllz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2yfogtixp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzsbvqb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnbhroh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqhroev.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaspgsd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgsvuau.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvufkqh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2htawnoyi.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sjannfof.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2izknqifs.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kweuiqvs.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nphvqaqv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2opwotgip.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlsdsvb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvctkmc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixilccbp.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ckngcnoq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gybxjxoo.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2irliacfv.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2oxchfnrj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqhdwqa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaeqwol.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnhcjlm.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2axglaoeb.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2klggjrvv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2hhylzyso.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2iesocmct.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2gazkycdh.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2optvzdyj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2znayedsg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iavhctop.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2egrhduko.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2lptyhpjn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxlcqcn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2imxdwlgf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2drkfaliv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2eobjyqct.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfbudiu.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxkjzjz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gsifyfkx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tznavhaf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvkebwu.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqoodgg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2heehhmem.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2odburqtv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfduusw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2atkxxjzt.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2osvtyquc.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmbwixj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlwxwfh.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eyywkrpy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2keiqmpxi.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfyewvr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2eicnbswu.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sijqzgmx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2hpouxfcd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwczwdb.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqqshvk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2djhrxqdv.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdkhufy.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhrocxc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnjykbz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xbshvnjf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qowvpjef.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdwjbpi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwmymml.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkscero.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrtbbdf.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyrxdfu.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyqqgwf.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2egkdiffc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhgkazo.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoqgzel.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2poehxtji.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2eiafykej.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaesfwp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxxdfdz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2onebycod.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgtrtzj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmgbsza.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwdwsba.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmbrgsf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvyflsu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2upoupojy.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqpeigg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxghgxn.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qjacycfc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyorpfsy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ujybjefo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pczssqkh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2esakbgak.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfubndmh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2oyydaxrl.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yippacxr.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2givpvfnt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfbhflm.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhdrtun.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwidulpq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zraswyjh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2akrrfbqb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrrrsls.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrclxfm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wklkgryg.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2yykicfyg.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2oclonxsi.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwcmbqi.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxxsmcn.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2dlikmnls.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2vibfmxcl.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgextom.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmizdfi.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrltaio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaftjji.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2viouxqrm.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxserxt.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2utwxansn.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2htmfbbla.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjytvvy.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvpfidz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2micomdur.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwmvyau.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nyszhlpg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnucghm.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuaqgev.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mvujyzzo.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2njpwlxye.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2duajwwwd.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tejpomag.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2newwjyev.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wophaowc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sfldlgar.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2isflrrqf.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cwudmhly.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxfkfye.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvroadk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bprahcyr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzomwpl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbidauo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vnibialw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zdubjxvd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbuvzgz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gncesghu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsjvbpi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2tridbfjd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qcijsdsz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjqwwuv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2krsnfckx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmlmsjc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2larmspey.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrdgsix.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2kpujnlgb.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2tvboelkl.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvaynwi.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wzedhytd.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2cueinpbj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtxeltd.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnhlnub.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iicetrxu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2taktsjcf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dryhkbxw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2uwktbrpm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzcwecl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2geatdgtz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwokbzg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2teuumzbc.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2irffspdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knqyeobk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2opbzihst.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgyzwrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvouxlmj.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2wizwupqn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2htzkyhvf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbxtuzl.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkepytf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwobnku.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwgneab.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2xahiuzkz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbnktjj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2yunzlldm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrxfrrr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vjegzizy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrsfaro.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbpdeat.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrdsdyr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcohehx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkfjtmr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2glqaxvqw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zabwwmxj.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2opzgdgwm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2bknggoqc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpbsovp.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2bijpdmdt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pnimcqbc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwutgem.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eipjxnvb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvzasar.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbljjyi.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vblnkyvp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2axpbbwwp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvcfbkn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzimumst.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2myvnilru.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sarvdfyt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dojkncjc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzrhurd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkqanas.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2twzjtguc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjxebzt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmynoyol.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhhaifj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkdbxja.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeyyryi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uyygjuun.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tianqxkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htixgqxc.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfxjkai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srrphilf.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmbrkfu.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2iomgmtgx.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2snfvtyiy.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nrejacau.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqiccfn.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pyikwwfj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzgkbhd.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwnjrvs.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqbxkhw.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2omqqemti.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeqdrra.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2shvgekfb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqeuozkx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dffwbkni.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2eelvizzw.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwddmpk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yafkvdyw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycloxjzb.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qroqlltt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2gqiegwms.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2exiyvcpj.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bobfxjoh.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bewecpxa.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qygcoeop.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2mljcoorh.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2natbboll.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkppmjvs.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtbuvte.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qitddtvx.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiymqffm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2sribipzi.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhlykbb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwchpck.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2celttjty.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2opjwipxk.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbptrha.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnelxhb.html


<!-- 参考信息 -->