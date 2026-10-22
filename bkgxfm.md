代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbkxhcr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsxzwdk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhpovmp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnfmstm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oemxemql.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnxhubd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aamxdjgu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrbegac.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uziqtdgj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcbywoc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhbzwaq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crltkqod.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdljgdp.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmejufya.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nknxwdxr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2idghexyw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2avhdnzyu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdnzwma.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvcashx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2puglnaac.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mchnzalp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfkhgze.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkarwzfq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uinncjmh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nijwxmuh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgelmwkz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2oawnzqna.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bifrhcpx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjzisoq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uemmigci.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2orhejhct.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqtglko.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wghsbvys.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcdivuh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vtctekgw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zednibgd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cuctxalh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcluznx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzyzzxd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwzqekc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2bmeznhot.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyahmrtu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuxretg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbhoeor.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qlovlwhu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wowmpsxu.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2woxarjoq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2djcpgcti.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyrpbfu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2daoncqaf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nglnetyo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwcswqg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeedllz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhbetem.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gumhghvq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jqepqths.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cezkenun.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbtphdi.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uwszzncz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjwrdze.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fvojmryd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2tofauwdv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2vuflequa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2konulhyu.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgdvnnb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wssyyfdy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2khialnlj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2erwolnem.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwzmyvo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pnoujpdb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzqxbqt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrhsdke.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2niqklpyg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2birabdfn.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvqmnot.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2elphauhk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxlroan.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnwltbq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2uypalnjb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2sepmrvvd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwzhyto.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2clryquao.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2taqchzyt.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnbdeve.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtyneko.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hybwclyd.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvmmwyh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbllimx.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxohnme.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hflrhajb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpxmwsj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrzdsnp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2coiiqsnj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2igvmhjrj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyjmhuw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fridwekb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuibmod.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2gppeqthk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcpjluc.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfczojre.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtjpmbi.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2abmrskqn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhndsxg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2txsccvui.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bprfhwii.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzfydfl.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2piocldql.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ltymiogz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgdgbjf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqorzyb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rrucccal.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wenpsdok.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhbpsjq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxahqdz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2prfhaxcp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2tdztjtsw.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2agvsmgrc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkmrjsc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbteprb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nijmzriy.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjycfsi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vodxncqf.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cygrvtpm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeutncj.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2nsparqcw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoejbvc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfntnswm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsmuvpz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuvtpri.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hntsujgm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ivejdxeo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjhlqdz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tubpznku.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlxmdrx.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jpaxjzbd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpmfcnq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2scsedzbs.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2teictevu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyratvb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkmofcq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgvxqsw.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpmxyil.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbotqkh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blwgtufw.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlvydda.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2utzvzdel.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2srrsljvw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmccpbl.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2vvufykce.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqmsfdr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hujjrhba.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2oganxkjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoipshs.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cojyltyw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmoobno.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2chbzpesg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ezesoycp.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rufprvyt.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2exybhiji.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hxeptabr.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxsnsuh.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xejwvtra.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2izjvucmv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2naqblzhv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdohaem.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2szwwvows.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaukbrx.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsczovg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxkgwxl.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuhivpf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wqysjbwg.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pptqykki.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rivncqsd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqnipiq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fuunxmur.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnxqbck.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiwphrj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zayzaovm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yaovqqyb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmncpeu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2djorfphg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2voeixcym.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuxxhmb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2djdraoff.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhcfycj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpuwxjv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tapymljw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdlpelt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zaitaekd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dvppeirr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2utviwilx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvlqopa.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2opkinvgj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwvckkc.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wztpqqma.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jhydugxy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnvyoov.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oxziueof.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2srzinxei.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfpoxdw.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2azpfqtlf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqjboec.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaegbtw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2afkyfyxj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuyraqj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcilyuc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2utcmmbjq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2asekmmpi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlrirfj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2tolirxlk.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhrbnet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elcfpree.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bcksxfwv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsensvm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpvnfaz.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwffhkj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrplkks.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdqhpfm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2kutprfhb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2sxckhrnt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2okplocej.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xhohigus.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2abfrgmec.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjcluhd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxclyjw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgprddj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2hnosttql.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkmowiv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrultdq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2evymjddk.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdbloca.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjbdpre.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpiogss.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvsrubh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2syqdbkfg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjffzyv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvclkva.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zopfgruv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzmwkib.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrxvoky.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gruloqlq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrdrfyk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrzkpvk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjqrisk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyholptw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzvqcbs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfcyhab.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvklwvs.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqxwwre.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfedvrwh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfvyoih.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgjjuzq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bljacqzr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2psiygpkz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vymtfwoh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlyqyuw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oscfrrje.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqddctj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2schhhqbc.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbzgwxr.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyfbkrl.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqrtpvu.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvymato.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhxtyfj.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jypvjlhk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzxpgbc.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnofmtw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ziesbcuj.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfyrzuw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kdevvrtk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuouijtt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlcsvbe.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgyibdf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuxflee.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2trhnfxqs.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rabhujfn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyuwszo.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2utnbthvt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2aotyxlcq.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ditogqwu.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhwcpfc.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xurqoeht.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvpznvb.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jtaojsit.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2zniggged.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2klwvbnfn.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdupjdo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpereenf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyqgysv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cbslncgk.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qljhlpst.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkeqols.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2thiwonml.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbkyzlf.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ffreydxz.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzjsvnq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bllppnwn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fplkrasd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgkeihf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkxnukt.html


<!-- 参考信息 -->