代发 wailian999

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtpdmli.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2uslkbrth.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhqcmtr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2utkaxqbt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlgmeot.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpwntmm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eejcnntd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pvygpbbu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiidlvq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mikbddzh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2swxlslfp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dplqrbre.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2insrisob.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2haygdcug.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqjvejz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqslssf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vonmsndb.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuzqkxa.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kimlixeu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwprhnb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbbuuiz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmwyivl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvexpse.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrvvyix.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqgptly.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jirixqnj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcdhvfy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdkfzzr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdtdcyk.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqemjdr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsvqqkr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dobzcbzm.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdxwrnl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2liebxwzh.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smurkoav.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkvmgmg.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhwolyq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpbnalj.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmmxaxp.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tspcsydg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfiooux.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ourciwug.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gltipygr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ducbvqyj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ickrhfmk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaegohr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2uayabgad.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2thllwvlu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwkwsqk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fautzxrb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2auyjieqy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsjdraa.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mknyjleb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgqjban.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2textcswc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2naeqlclw.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbrlozn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkmxrin.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaypxwx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2slciotiz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rkydfiaf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhulgugd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kmipgmtb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnduxieg.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2nfprhiog.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvofikuj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vitplknq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2djnrhxfb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrmfbkj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rysxnyyx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iygsspoq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpgihyd.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2atfpfmjd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaafoddv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfmdnxz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbwpyal.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2iiaakbne.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrmmbqb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2awksdirf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhiupvnb.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2udswlqeb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtrpkzm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xymexfbc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxfnhix.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjudohr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsmbfsj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2egvmtxjd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xheefiob.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hgedsdwd.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dppjgcwb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsixmmc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zsccgrvv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tscsrqcc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqqxgdc.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hwczxafa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdlymkr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgwasxq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xqthikhz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjvffpa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsbiwvi.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlonike.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2inqzrpqz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvkeeym.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2euvdjizx.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vxspabiw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2turpvgdl.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoaiazm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pemmexlu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmekvsa.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2myhlemaf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2covwiajr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cltkphbu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sfllvnrj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2didybdpb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdzxqsy.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxomskez.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcgydrq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzwvenh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2enmeggbc.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdfibxy.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcwqocs.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuzsubn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgaavwu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oixwcphh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2oerhbuiw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ignsnips.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsjdbsq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgerodf.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgxxmpn.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iyumycqa.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2htsxlwke.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlsseqr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vnovogbn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnnkbji.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vnufeuyx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfnpldb.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wvulujbs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhcocsm.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2igailvmp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrmsyiu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bbckqvhl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2glctbfcp.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2omewdtgx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvsylsa.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjaauvj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqosgtw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2azkckbkj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2duomppgc.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeykyii.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcvszyh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xdftjgxo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqzdoje.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvhywlf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dugdeyvz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbacmtu.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeocktqi.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kiivcdtd.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2aytqydyc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nisixpkl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2waqhbivp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhyybze.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcngzpmv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2onyjnkus.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuydcpk.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wjklhmbc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2tngvyowp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ozztifdt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2frmzevzx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnmghor.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2bkugvqqj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzgxzrd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjgczow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjendhkl.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2qkibxceu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jsewtxng.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2reouuzjz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gspksbww.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pusbmbiw.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ehburscb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqvjpdi.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zfadcfqw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyleper.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gopamzno.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2adpmcfrk.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qfotfocw.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbdnfya.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvxghnn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2opbjbkeu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rtasjajx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2alztaytm.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2twuiqdgy.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yosnbbpi.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkbpplw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fdakpoae.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpprscq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2feoaudow.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvemeef.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmuddqw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmkwwbp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmgqugy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2eisgafra.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2teimsiqp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2suftlcwr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjwmknv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2idjoeazf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uyikzeih.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2saqedroj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2veoanyws.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqzoaqy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zixgshaa.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaystta.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eapfphen.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2empvbwtw.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdppuvu.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mirmdyqj.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wqiwyhgu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2cqewxijf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2woxdjuxi.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fautsgkc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2afobtohm.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2beqbrhvl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hgojdfrl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2faefibqb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbgqvpw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkjjucg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2oqupeput.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlnetxt.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2nriskocd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvrdigi.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhtkfsv.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2dqiiavcm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmedaaor.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjbabij.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjyjaff.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwvbtkc.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2gxurrlbv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmxzmnh.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2zyykqqpi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwxmyhl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2imlpbpoo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhvhxzz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2prvfuoae.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vodcqljk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2dwejlvho.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wvstjhgc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kskwvxhk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfyyyei.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzsbdgi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zpngmaba.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjinslo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzttyej.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrsuhcq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnqulrr.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjpdqff.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kpovaucp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwvjwih.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpepftm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yklgxnko.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoupedc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbxfffa.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zourpijb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oodalfsv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2smkdmrhb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oucvvaaf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnkvmzd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wddzvuxx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmmkpzv.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfskkone.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbvroid.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2btnmjklp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnaykph.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2siyhdyrt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dovhxyco.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsforqm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahisarbg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwsdzap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vudrkdqm.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2smztgoiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iuriiucs.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmzijcf.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxtecqv.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hivnulmp.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuunzlg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2vskyygiw.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrklylw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbyaqxu.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2puajiajh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrsfonc.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnbmtzv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kybzeifi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwyupwn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uorrykmd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2twokjlow.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbubvaqy.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2smorgbta.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnohygu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqthcgb.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxhhdsj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2igfxlpon.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ginwlidb.html


<!-- 参考信息 -->