代发 wailian999

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2udyhfabv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuprugz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qfewpblz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbeodvi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlbtluc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djefakgr.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyvgdia.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2aehimuea.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lizgiwys.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2odftumax.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sybfajvl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oabmwtkn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2njaqttrv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2adixbgtt.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpgeyls.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rekxiecy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjhdjat.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxistbi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgoymen.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2izecchhf.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2anjiomms.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2prkkzyiy.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvufvpk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mazvzmlm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uynqirhn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hszikzyv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwqxern.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmfppcn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ylellzjo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aawfzrtp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wuspjrvg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmojpvg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cjntkwfk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bysluhwn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhfbedy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gszogdod.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dihsfkjx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmoxfci.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2etxtggrl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nntavqxa.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ukncbhqz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdioukmp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2knygwadj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2unzvwwqw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rezjbrlq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oectnysf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ediptjuv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbyjiys.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hctkgfhw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2izhfgqbf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cbowvolh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yifhafor.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2twwxzycd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2evowsosm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2twegwzuw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyjgcwe.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mznatfxx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2roqhndhj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lislctxt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyggdaq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvxesfy.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfvwdit.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jvljvjbl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssowztxv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2eftuksus.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2eeisjzot.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyxhaez.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2krzimjms.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2oryaornh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2irmaxdps.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qecuarsr.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzgbsuq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2kqunteyd.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dptccnhw.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvfoeqc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wqiyhjvc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dwglflej.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2adiddvdv.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qrehswnq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtdmpuq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cirqbwpk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtkvxqr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvmcirl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvuywrg.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnqozjl.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlklxql.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2onxtznaw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zorgjhcs.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dktcmioh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtzxyuv.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eclbcapc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jadsbuzp.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2toimzbmd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xcswdclp.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pgazcuyn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yscluykc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hglwfcgc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kidrtmej.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hevafvrh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2agggfzxs.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgmgzhf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdytkdo.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jawikakp.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxduplxs.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoqqvxh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ezswmnet.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wlubimvc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hijhuorb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2sgoygvcg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqrqcjm.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fknahjll.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2befmanea.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtrqbzv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2drofjibc.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lehmiijp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vaesuxer.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkwyhva.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2cectjndq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfmclni.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmdxuff.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkkepgz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsraanf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vipmmgxe.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiqxsdr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2opbbsrkf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2whnclijz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2csyagrul.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdxpoyn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrwdlca.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtjpitn.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpgsvei.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2kiirbhtl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2opevozta.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuujljee.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hzguyrdr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2btnsjvpt.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yshghhdi.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaqfrpe.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2idxdtkwb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kplhhunz.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2onnbrwkg.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2thrdyghp.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbmttvi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gotvrsmn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyapkkr.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtqktlc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgdyjrs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtntjqg.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qbronyjx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoqfmtj.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2emmmausg.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrhzoqm.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2bztpeynf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2riqggaii.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2afcffvtc.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrpquja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpotqlkc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2secujwit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trituykz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2demdrzzg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzxgcxm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2esmrkdnb.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vpalyhjy.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzcvxyx.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2umyrhwru.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2osrkoeqi.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcjrasi.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yavqrnhc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsgacmd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvaqfmt.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jhijrwaz.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkpqdbr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtoynfp.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyldunr.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqltdlv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkdcyck.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnnbyis.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2asvekiba.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqnluol.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxxnjfr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2sialluxc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zwswlocl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jofeeksu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgpfpdu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ealgwdkk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkujbvo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwjkgjx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lgctacmc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwfgdzi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaksjrp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoolkvg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zegqgwcj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2styxovtb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjrduln.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2futhujce.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaoobft.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbjgucf.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2saohthoy.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvbstfh.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fqznovlz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zidpwcfu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rutfuamv.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2thsdatua.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpmvrnk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2czfekcdm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2skiwbgim.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2zzififzt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdzpuzu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2daftszem.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbsliqo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2brqzenmx.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wfngecpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvckpjgg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzyregu.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2sivhhbza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjlgfqw.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdlszhl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgtvjuf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqtlwui.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zbizvvsc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2gstydkmi.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvatwva.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlpgwdu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlhirvj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbnbvee.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgfsfkw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgoxtnb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyoisdu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbqombw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ecosskbw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrcpgzs.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2cfghsmrs.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vusmmgrw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2svadbrqg.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2gujzkihn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ecitlgyk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiiqbbl.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2scnwfeih.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgkpemv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2estxcefh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2axjzsuoq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oquxqcmf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqypgzl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpjptpv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfejexg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwlttwa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2crzgubqm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjhxvze.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cajrwmie.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sekfwdob.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eslqqrzi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzjnjak.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsxgree.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dctpxirt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzgmopj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcujugif.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2flrycxle.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsslpqnz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdnylit.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxgbqhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvqmpwc.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcyajgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okvzlqrs.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fblougec.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsutumwt.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoxgcyq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfhpccx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjvrgod.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqwetwc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkhtqki.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcmtfak.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngexcbyv.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrrkhtj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvhteew.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aimanzpx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fftjfroa.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyastoux.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouydfwhw.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjkxztu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2itecdwzy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvhyoqa.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbgafek.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjasdne.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxacnfvm.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyjrzyc.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgikmuom.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wasnysqn.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvokxws.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkragqk.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cegbidwa.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkaaqaa.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuleucw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwppsmvz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyrngyp.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmzwnpt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2pxeecxti.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjotpkd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnhyzte.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjmqdoe.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2lkctxvip.html


<!-- 参考信息 -->