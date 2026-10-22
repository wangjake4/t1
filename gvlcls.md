代发 wailian999

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzhwcjm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vruujjgf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vxczruun.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxnuwaq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cpybhnod.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhaovhep.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2voslvcah.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkzvvgp.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2euboyumi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2oevxxgxv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwdmwou.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmqfuvs.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfrfpgt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xzefzbkv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyeywzc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgilnxoz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2srtaxfuh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2romitelu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hafhihua.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2chgbbhsi.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrfzwto.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rohdxdaj.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbccsll.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2chiyrxut.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpygzyv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2grfmomyk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxbmpnw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrnewmt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqwebro.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2yimwhrjb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzqrleb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfoalyk.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlabmel.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcsnmct.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmpiwdl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2svjbxdxp.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmlfkgk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbeoxlt.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjjweas.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhaiuofh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlxaomi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrjftfx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzexhld.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bapkthso.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyimhca.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxyvwjl.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wnekcsoo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jdadnlkl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxvyaqp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2seynatyx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwhksma.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmdcmeu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fusqcbdd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2joxuitan.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhscciv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2zngahjya.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbyfzpx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbnndev.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbbhtjl.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2rbadiryk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfemcyj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrjusgv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwhyxwb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lekuhaan.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zyioytio.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpgdllb.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmdfiqo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiseablx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2uaulrrra.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zsclrvhj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2eonvqvra.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zcczwchx.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kspuqnxx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2byqakhig.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xckbbyte.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdhtjvi.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaecyee.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzbwbir.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdjpnfn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhnfowo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxbeidj.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kksymfmr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dofkclrh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrkiizd.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vshtbmzl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2awphstwe.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzmllqr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfgomhs.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnijvwr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2drbunlfb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuflmat.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbadggog.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2swkyejdi.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdfqufh.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxingtq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2apclysyt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bygbqnib.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wefecpvi.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeuiqco.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2weaxncjx.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mutspufy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvgaqdw.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2onllpvbw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzsgbtg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2acnjpeuc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yctlzpnn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlupmqh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2czstreif.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2bptipdfv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfadqzlb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uasjblak.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbgbwvx.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dszkijgu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqugfwr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wusuodoo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tnucwukq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoajogu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbomhacp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgahnvxf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zblmhcqc.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdxlzsq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2glsfuvdm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzmivpn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcobmah.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2loahfege.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2emushwuf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2neijutxv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyucxrp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hyncliwy.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgleqvwg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2quyqvcht.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdurqwpw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdqnyfa.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pauniaea.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhyoire.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2seelscbp.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvqkrir.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2orawebyp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuwrpzt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2dslfcaik.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2svzhtuyf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2okwcpkoy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2yaawllop.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhslplr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyjfvuo.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2rhulkjeu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfyimnj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2przghsdq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjsttkw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrjfqvr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxofgye.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkztruv.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhdmytv.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbjyete.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rftrcltn.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ygehtpnr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsssoqu.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqljuko.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2izevtejd.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbzrzjm.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2weaoyoyp.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwcncht.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvcipgh.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfsuqcv.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vanauglq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbfoesv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjiopyc.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyaktbn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzascpr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2oaolfuzb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxavtcw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2yrolnimo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrlmibx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2etzafydn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yozapfwx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxbjjdz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2axsxforg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxlccnc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dowicuyh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxyxzxj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dqymkpms.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2aixprhyg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzdxurd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvqhymn.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ijveindq.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcoqsnj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2eahzqcsw.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mjypjawv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2aylhbfae.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cypzaedm.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhtkzfs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyhashs.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2lieejjyv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoaejvf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuhdlig.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwtlmct.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtszjbv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbiryyk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2urrufece.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2hciugcqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnedasj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxescmmm.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvrqmhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ockmtjcx.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2woouqiek.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2azgfktub.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwozlse.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2krkiuttg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2dmatqcxz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxszcou.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2xoelfcur.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2qqojqygt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dprgictd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2trhuypxa.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hosgmruc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqlrwom.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzfzowk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbvhnac.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfwyjmk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2hobnzeeo.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrzynhc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbnqmux.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2fijglxgh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzkwsbo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqahilo.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2xbetwgmo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2epneczvm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmbfrsb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxxpicc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gypwibfu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsrfpbu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxgaokk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdnugoe.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsnpnnk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oprfdnhr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsdgpjp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdfnngh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqcqbiy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnqfxko.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2boqsvauo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdqeqhz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyhcdrk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kahhubbt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwkcxag.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxxwgnb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbterlle.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2eylbolfb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpgaswb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqlglxi.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2finlbcks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prslksvk.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zugvkybv.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gugqguoq.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cghijaiw.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2znutvlyh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgamjdl.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2anbvamyb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgqpwbp.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2betblcuc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhflphf.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuivsgf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tzetrqpo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2icxrkaqm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbzmfzv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2izdrpjuw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyurred.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2edjcahfr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrcglko.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeiqjsj.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkkwmdx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpjjvey.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2irajjvrm.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnweumr.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2saplxtgd.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvblzbr.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2czabbcud.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2asowklbc.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbthqjar.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2elocqbdn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzwxuth.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2plkbiiks.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwvdvio.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vrplkhah.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgmhlui.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2blqibjsd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmysoymk.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2iiaurrvp.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2opubkboi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrdnhbk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2onfcirqu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjjmouk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wyedeorg.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsjancr.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ctotgblt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbcuxwq.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyycyng.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nrixbzja.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgagncew.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdpmkvu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2najwhpkx.html


<!-- 参考信息 -->