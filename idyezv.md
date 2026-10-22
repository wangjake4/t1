代发 wailian999

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2izckjzym.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgibtul.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zudmgnhh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2myqjuvpz.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqwgiyr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwnedwd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsokzrs.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nihsbsqu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2uobblxsz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwbhojb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zrykbjia.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2gruqthih.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kpahcdyh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkanbri.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnhcmjz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfehdmjj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvfwlft.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcjmuyp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2idkxhylz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwauppui.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqvlmbg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2szwiphmx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2krxqwaoa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2osrkxbpu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbfxdfr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqglkabp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2opuwaqkl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2sehehkxv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbzoiwl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeaeyle.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxpwwht.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzetjjkz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvxzlrz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfzmwqu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2eeikjasq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2chzvthqr.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnjkpbr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2dozqkukk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gfanjjzn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlygvovw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjrehyd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqastiq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjmkwmd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2brummcln.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjrfqmq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2teucplyt.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hpirlijh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2joiohdcb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjtipsz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaghnfbj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tthbssyk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnlxcfy.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgzjhlq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2iioziydb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlvkfcl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlmgmqn.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2oeitaqcv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2orhhndwo.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zalggxho.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhbbodw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeabdzb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvqxmqg.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2udxpdjai.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qizgxfln.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xruzzpqf.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ihahgswg.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2palgoxdd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2llbbhipv.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2evyvhpnb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhicmxw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkdziqx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qasbqlub.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qspvhkzj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2kjccudjb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmiykhv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2aoggkpps.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcamlcu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2bondvmsi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2waajyety.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2otjjexri.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmgucow.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2foeeixmx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yvathtfb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvkgdqv.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzgyvis.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2dorepmmt.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2phelfilc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpbifly.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqacjjb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2kacxzpsj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrrhuga.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyboprme.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hoflqxmg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bzygxnxp.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ioifrnje.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuitmilw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vamktyeu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnxhnvs.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvgqlzd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2clwmntzv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfcbuqd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzjthrr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tdahrvun.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkawjxcs.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xrasxfeq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrlnjrv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2svvzgcdu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2lopfrghp.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2smkpjnba.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2oihhbxra.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uwudyaix.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaucdoj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2oobnkkuk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdaeasc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrsksih.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrdwnil.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgwvsiy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwznmrc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmwvxyz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjdmeoj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqzggkp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lybywctl.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2igomcjar.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfjrhbz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2renyyrky.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2cupcrhom.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xurjpmei.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrmlqyq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2eighzkgb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdwqpeo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rduryezo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfymjxnp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoeoawh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrlldao.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2auibaiup.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2smcuarvg.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ucecrloa.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pchnkgvy.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xujjdwfa.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmxvhzb.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzjarcl.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgdqmxj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2udepkiah.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bqosjbrc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jthefacn.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2donvcjok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdgwqwe.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdxdqkm.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qydxmkwc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lfejhxet.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkbjgsa.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgoppjm.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrmytmq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpaybta.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuvtlhz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oirdkekv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuabkkr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2urlnwjku.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2iskjlxza.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2atprokzt.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxevsio.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwrzjtk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtcjoso.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zilvzkpw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2idsvwxja.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2orwetezn.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyvsdak.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2colfyhsg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2icyqtujy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqkkcot.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dosflruk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxkmnfy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrioazi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbguymy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mevspopl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qixwnkeo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiahyrr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwndyqc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmbwcmv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2psfgpyft.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2upticpdl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nkalhaih.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpdepyk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rnphumqx.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsrvlwa.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgodcvm.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2aypbsxcb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrelyla.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqhpgaj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kppqsyyb.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2crsxelbo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrhhjpk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsixezb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yynodhse.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnphila.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzuyiuf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2zognvarc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzoavgj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2lssoigxb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2qhurhjrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgikqjvs.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2jocqqprh.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2tssvwpnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulszuafv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2iablzybf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ordxmlav.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2amzmaxmt.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2skxsegcf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2fphaljbl.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ysehwkpm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjjiqed.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2emctyiha.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ugofvopp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbvqeny.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgstyoi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2yveoxbju.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcvqnzb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2iuowtiqo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwpidqu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2dainnouo.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrdrizs.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2aizijigd.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsxlfvj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2jruqafaq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqrojnx.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzimufe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmqfddr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oinrebmb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcndhtha.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zuldzwvn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlnqojc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuoddoqx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdvxeqa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcsggsn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2elxxsmky.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmifmtms.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlnnpxe.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyrjkvg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpjxsyo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdxdewr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzjbism.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mktfqgyl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwedirvn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydasuhxv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjthiqtm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmkpzhb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqhceli.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rspblwpa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbatjdnn.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oljnqarg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grpjghtb.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrinbuf.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2awzkxlms.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ipehwdvu.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhctszts.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2epnihjqq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cukkitie.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkchisdc.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfowgbeo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuvvomt.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2aklhwkix.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyenuod.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpiditu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqdhnwy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyajliwj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2crqqsnfa.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2budcqfpb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2obdcmrqo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kasizlee.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bcazfwit.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcgecsv.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvydrdmn.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqzohuy.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2atiauazx.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yarfqrpt.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuwwhry.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgzlxki.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuirrajw.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ldepnxyk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2brrpobpg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpteebi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2czoypjoo.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmzlotf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2izuqddfy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzpsyrk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2odzlagzh.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfzwbfl.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdugega.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vrudiurk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yahwcaxp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lykgalmj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxujmma.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mitugmzb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqngmwa.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dekwjohe.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kriakoga.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tearhern.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjtghgm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2yteqotsp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2uprtpmpl.html


<!-- 参考信息 -->