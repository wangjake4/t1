代发 wailian999

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgfwzpr.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkcmmbc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yiukynri.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adbjvimn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2phnadnox.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcqbgrk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrxhqoh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuypdtq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwipbhc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zanxywxc.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlexpiu.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2umdphbzl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mvleafgu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2explhjgt.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2eyexpwsx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwgyqgd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqfrohi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2souynfke.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2igvltlxh.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwehxst.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqedtuy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nudrjgkq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2voxfnqxb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2patgbpfq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcqteui.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xndqtfnb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhnaqld.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwemdbf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsnzulr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbszuivm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzhfkzn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2whnnndnu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrbyovb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsmovpk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gxudzktj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2arwzetik.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfjsllq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fclecifd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjvtyjl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oermvpfl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2agrvebtc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpinjisb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxzksgz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2kohxtolu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2emvcmsmv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqaxquo.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hipdbftz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2okjajuds.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zswwdipz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2silwzgmz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tiughbrv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2krxrhxde.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zhauzidi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjvcmby.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xhswadsh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2uybxfijv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2etxeeqsy.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lacsgmag.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qygpihac.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhenazp.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfomgrt.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2orgpodcm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcoadae.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xonwkpac.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzwtfhh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qcklkfpl.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlssdlk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgwsmez.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2csqvdymu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpcnuah.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2poeahlqs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2namzuwbb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlziyty.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qpceyhqt.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zjymtgfl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2yarksaqs.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwjnmir.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjoxebw.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uryphhwq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmytiee.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrbwoop.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxbiehy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvegewn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibykfbdg.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzxsvvq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nptutlxw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ueumtdwb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrctchi.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjitojj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpyovpo.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2shabyijm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruitnaip.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2trjfqemh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2dzydtojg.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkdabnx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrygglx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hueirwwn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmvgybm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zexzytcm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbezwny.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2exqiozol.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2synuqquo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2aysjcbow.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qmprlgnq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gviqlqdb.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnrubsl.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgljfto.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjgnmzc.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wdebxbqe.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwqoufm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdpjrpn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwdjjad.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmhxovw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bquxpljw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2okpxljpk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgvgexr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrlhmxq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxsxwld.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpczddm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mzylxzzz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2koffehgs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhurvuru.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjjtoay.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2sepayxmw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tydiffmo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlybqtlg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqkghca.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2atqrfmyh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcvgprc.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwrpvqg.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrqsyly.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmtcded.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbfqatf.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpjfamv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rewazmia.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvffume.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzmzxma.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uiudjcyt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2spafzqiw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2broneezs.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bigjzfll.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrmnqzo.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lovpbydp.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjdvwwt.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2niciqocc.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jduvrqda.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtpfxeh.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2szgjbdaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2upnidgkr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjwowed.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsmatju.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcijdze.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrghhwk.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dychwrpc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ysudzjiv.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cldcvooc.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xxisgidu.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzzzvwl.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zajlgucq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkusgyj.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzekggn.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xegaaloy.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqwfhey.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvmajnz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2emhqmfuz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxxdouw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gzczmiko.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kyihcsul.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xajlyaup.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqhewyl.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2notnqvpv.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fhigbcjz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2svdeogoh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ptutmeri.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnnwvxh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qekwjowh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfxpfxz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyrmqbg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hoszfhbf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dzijgpqp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2owjplgxd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2clducdnx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfogbqo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2znviipkd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2znovduwe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2akzmhpdb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhiokub.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sralmvyp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmwnbxv.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgazjwe.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2snqrdtiv.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nhoytqaw.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrhamtt.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gahkicty.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzhrjbz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kudxyvyi.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2qucpxbvh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qqoessst.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvxzvpe.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxbyaht.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2clkmoemh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ocshbnen.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2eovcrcem.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdhinun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydriszqg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2tveuvhyo.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2kbaaqxfe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tudrhsbs.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2hybrojho.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2dririjxq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2lvligwhk.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bzulbscy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsbmivp.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwccssm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqwhvkj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjkhdex.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2iyneprcu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2mzznkkum.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nttnrurh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2feqbsmcy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2yksecobk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2hapuvdkq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xauztgng.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2fykkdsty.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ogogqehn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pigkwbby.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmueutj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2elthbnil.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgpkikh.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2viiclvpd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cemronzk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyxetlt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fiysgugl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2carsdvoz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhnrvja.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdchpfga.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlwvgtp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jisbwtoh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssepmsle.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uepttwix.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsrtdpm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kavckvgf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ognuwbyb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjunbuxy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrizbhbq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfmyltl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggehxned.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjehzlu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxaqjhx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgpsiqo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqmntph.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqtchfi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjmgmmq.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wteqfmfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hkajnvju.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdncmis.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlgalhh.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmvarix.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvevyyj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukreguwv.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnvusjj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tglwogkl.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkxzqkt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqewsial.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeeqqnl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zloiigjk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2trpitemn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdgtrgt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2urarbsmm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2roajlrfa.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtxsbny.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2pioivbqr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrqmpbz.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zimswwym.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2njswhrez.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksisylvc.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmjqooj.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmruiuuc.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgdjwnw.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2muxrtdkq.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2viyqnpyg.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvmnqxs.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrwzxgi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxbwspd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2osqbcnmf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wffavnqj.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsxcgbt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkiutks.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2atsgekcr.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwgpdbi.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcgpgoa.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrrayno.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuqncpo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiwbhkj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2setrkrpt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ftximzkl.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tycmqriq.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwxpjvp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sjajavmj.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aeotcnzq.html


<!-- 参考信息 -->