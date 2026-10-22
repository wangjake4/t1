代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2eceoizxk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jogvxayn.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dttmssiu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzadkips.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwqzktc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnpuico.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yktpsspo.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2klecjxdn.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqsequk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvitwcv.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2osaenlwl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcuemds.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnndaiy.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmkxiam.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxcflvd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfxzywg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2aednxjje.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2blkosxmm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpxsgap.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfyelxy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkebicq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2twfvebrs.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzxoijx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxpdaqn.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoawizq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqfjata.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvizsxwo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovajezab.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2enaatgud.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgljmgos.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyeypzj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfapbdx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ferpcrjp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2odaptlia.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hgswvhft.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oflznjkv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmmpklq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2blkgthtj.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qysifpmr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzblnztt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzbtrip.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2effwvull.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhysjlw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2umpuqcoy.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vnctatzv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjtnujn.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rntopdlc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfglozfv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2eobmcxkn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlspbmqo.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcydjew.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fuijrjrf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qveynszy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuwqfjz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdspsbt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2epybkfgb.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyztmmt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uddkwjoc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxxkelw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2movrwhte.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tywfbfys.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrqsmwa.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2efekkegb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxebqgbh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2nookhota.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgtirav.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xnohzpwt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2kutmhttj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2cttjhyvc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2blkxqcxa.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgskxmu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2atpwnluz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjbzleg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2gqoibhty.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqxxgec.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2uehtlaye.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jqykzabl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhskbfv.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vyivrspd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbggajzk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrebddi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvsckki.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhsfxwv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfggsdl.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjmovah.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2dejwyldz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ochbqelf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpqypgr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lwucapfw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwafrbgm.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sarhbnke.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwewmswk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2axhtjkhv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkvjmej.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqsgjkv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcatpig.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtudkga.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrwyzas.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdkncoi.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mistpxjc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkifpvx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2amlglefz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iukonrpl.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2stjcizow.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2utbyyxac.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2adanqniw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbgkuaa.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtymfpit.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwbbfpu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ceewylxo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2shzxclyo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkaqzfp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hrepzhpc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdtaahh.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fcacvwsl.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2tioijakl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfrdkhg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcjnpkd.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgtscfu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmahttpx.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlnzyuu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynaknpew.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwxxwle.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvrwtrz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xthpjwrb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gleykbuz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2whykaiol.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaqqyci.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2azgcxdcq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzadnlj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kiebfzap.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2udswhpew.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kirpyedb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyitnnq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2csphkgmb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2meedoijq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fykxkbft.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2clgaddfq.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhsccxa.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkbcgva.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxhhbxm.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjykmaqh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmjdloc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvlostn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2esbkszou.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfarybfp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmjwksi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odjkjulc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyzeqof.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hmorlgsn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmeulqh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiizyaz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rvospxtx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zonswtgw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrwwhbt.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vmidrwxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbayzez.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kymmvaad.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbzeopu.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzkzvpu.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqulhji.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoxqxek.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpsjbfo.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqegvxg.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlctlkz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2etphdthm.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bchkkllq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdejany.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kkitgfbv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2oumuhyjk.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nuovagyx.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnlhvfn.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rbstduzm.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hpulsryp.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iejxdqeo.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgbagya.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dasoxkma.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnamxhz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eheefswm.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdbchww.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ncobtbxn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkpuqev.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwfnpgi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2azvlxvaf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmszvqi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2puaoaxtn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2arzpuchs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xnomhrkz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hymycuyb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqlvsxv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuqwmrn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuqrstv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ayndqpjp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xyktfssm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qojkctas.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ftinekxh.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qiupbknq.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcwkpne.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qotbagyg.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lfinpdkp.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsutnlm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdlprsz.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwbmlyz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjwtuij.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhfrfez.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgxmkbz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfjfflg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2amymaaex.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqqovds.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdovbpi.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvyueqi.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2psuhzpkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sthpgcro.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoxfrpy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2yseknhcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvnowey.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2iyomdqhv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2phfwqndd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2bqeiofis.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nofqvksv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbpatny.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsemuqu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2xvobqxyn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2mumgqzdl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2hyadgptw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2xbggxvvm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2azjsqohp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2mccumxzx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2gnujrcqp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2eeblwvor.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpstqed.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfcndst.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2khhrcjoj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2svvdlaqo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2wjceaxye.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwvwwev.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aaltkfmf.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2mejyrweb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrczzds.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeakbyp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kksbwvmm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnfhcnt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuukxuz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2giahmbmz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcbpwua.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkwyljb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2taczgfgx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yixughup.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkbdvqn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2abfibeue.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfutugy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhxcair.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvctmbj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmadxyuh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vynprdem.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iplhncjn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmreoaxx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvwivgr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbycray.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2thjcsara.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sanixfwn.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2picbzrhc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpctmetq.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wubnnqdr.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tydjkkey.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wzawdbae.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfdqhtu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzqsynb.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkcecqk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fifbwvub.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgabmwz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2esxhiukw.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2mzajoqcm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjcvehp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2elbbwneg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2frfmevyh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecntionw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmqnjrt.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxvecvi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdmbfsy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqagsdvq.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ninefbzm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2xljlhxok.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzothxl.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndludjan.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2klpslxet.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcgydwx.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfjzarp.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxxaekf.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjipnsd.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fidiaytp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeqhlrk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cczfppar.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlyfast.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2igguttlv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmyygbi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsoygwz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnrhkjd.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2qicqbivj.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2nqeslagh.html


<!-- 参考信息 -->