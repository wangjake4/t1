代发 wailian999

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qszcwggg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwdbxyb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2atpgrrzg.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkdpsba.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtwmmok.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqfmalx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwxqsyx.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmywqkgw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2exyadumx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpgtrft.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dofynqyg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2uiixgqfj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhhnbtk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjgaxuv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiuuezn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeexdoiq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eiopcplh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xezhvfhm.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhqevah.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbfsggs.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vyevzire.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbonlmt.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlcpdzu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbyssnj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kgevbuyw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2piifucbc.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwjotfh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ieeridrh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2enfflhsi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjxposk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zognawuq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lphqphtc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcluewn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qniyoerm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcftcfr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzlcmae.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgvcwec.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bukxdbct.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcjuebr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmebqcqp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2otxosmnq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbydasq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2woxfgnxr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvjkaca.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2biwvprqg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpcyfie.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cykgofsf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2upyfnfxt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dgssleoi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqyqmbf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzowrlz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2andbubec.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2acxfgyvk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgzjpxl.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2lmixdqvs.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2irwkjxov.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2upovwfso.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zwybyrzt.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wzecrrvb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvyjjpm.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoubsiy.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zdggruxu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mltcjeru.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjzrolp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzwuklb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rtptydnn.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2isfktvyx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fieszgkg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpdtnlq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkicdim.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2juvhxoiv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2twbyqmmy.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrfxjme.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkczbwo.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbyeysf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbtwrts.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlkinmn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqalskgt.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sxujmkoo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2scgoypeg.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nebxoule.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2sapeearr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuvvsbg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrnicmd.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2arsisanb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2uzybhqcg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvemamp.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuleamn.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hbadjyhb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbbzcta.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vphlwihf.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjywamhw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdseybv.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbhhmkt.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuglqhr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhizggvv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ldslmaui.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxxokie.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2novramnf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gznkulxe.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lizkgcxs.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjumrnc.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfadkki.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqbuwva.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2msirbicp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvozncu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2mccnlkrt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxhfdmv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpouozl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmptdkff.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkezhvt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuxiyqw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnhhtty.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rypckrab.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mqckiiuc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ogocbchv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwordgg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzksvofo.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckylpetf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zlynbhvs.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2anbgzraj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxczzsd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2fumygrog.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrouezl.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tgchhpti.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxygwdeu.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfwhkvj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2waqzorzf.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtlhhzh.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtjyauq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmtbkhd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiajque.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgzsezs.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2prumrukc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2jprhuwtz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcgbfyo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gihacovy.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rxysuvsb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2boelwpoe.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvxncch.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2uebfaxas.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2svwtctmr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2lolkdkki.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwonyoa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlukqis.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2rnywfgij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwzfuid.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnajqpu.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjbtzln.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjoyfmj.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nazebdtb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyodzcw.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cygukfsm.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bionceck.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ymietkra.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xysguazn.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dxidainc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmmgyjp.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2puznnpqu.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqfpegu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbklwme.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ovohkyfm.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzggwuv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvjgxnd.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vhawvojb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2haqeunis.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxvcwyx.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2budhrukj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ggehgxua.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iethmwlt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nixujskm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbanavf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2cimyuaay.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnazmhu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vphkaldv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwvyinw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwqxapf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2yiodcswn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2easxptdg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dchczivt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hydtxggq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyugvku.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gqierxju.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2axrwbnhq.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxxgybf.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2shotojve.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxnkyws.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dryokdyo.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2grwnmkkw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcshfec.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjnkyga.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdhfkdt.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2nuudvgdc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjyaivg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhpqvtb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcbnzwx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwhegjq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lohwqblk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2orjulrat.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2revfbrmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lkronrws.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2puiyqaew.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhvuyva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dutecnjs.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qgenfrwd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfvmovg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2pobxizal.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jzleiveo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoqgarv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwhgddc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxusppr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeayset.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2xovwnndk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgbptac.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxikyig.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2pcikmlsu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2yycsdyab.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2iqaplrmq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2kevnfluq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2excrhlvj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rlimhpnx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2sumynylv.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2lyixsdgq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjvtcke.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2maxtnypv.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcoqrpv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hapnwmtg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrbvikx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxysbqkm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqmasuj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iceiiqus.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmctqmuw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnruusz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2upnmyvji.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjvfgag.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eofsqnmc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvocuyzt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jooatqgb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vutcxgip.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2owyblmkk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aaidpfuc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qktcgtcv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzndvxc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2njbshkcj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqhgrup.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlecnif.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2oysagclo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2euqrbzpi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmeubam.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwtowyk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gidvnsrh.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bfofbmqq.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyeyvzs.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2frbxxxow.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqabhzpa.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2qntixgph.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2oggdeokw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtpbiuj.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyqdjrc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ictvtozf.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ouddvsis.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdrgiwv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vehfggst.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fauwvfev.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2awububfr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vipadzoo.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2sefzizry.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfnbhrm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vngmuzgk.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nollfnwh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2uaifljdw.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2thjhxybw.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtplats.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfywbjio.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2glqubxln.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2alnkvflp.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkadwip.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2utryhwwu.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wouhzpxy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vepuoosi.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bquqeyjf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrqohni.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2tvccgwmf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2tolwukbt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvcuqdb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2brmqdcra.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2riqotfle.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2wmczgbom.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hkynnxsv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sywzpgrt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nzggiacb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhlwusz.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpxdeeg.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkrjzdk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcrtprb.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zirdafvk.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zjulouvc.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcqiefw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2svtlaydu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzewunmo.html


<!-- 参考信息 -->