代发 wailian999

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2phencblg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpvpial.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnlddxg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2eehogqjk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcscnoct.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sajhxsud.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjsszci.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmdluyd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2psenbahb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxgrpnn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2szqbkycs.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdjvrna.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnwhdty.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvulmoa.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oalnlwct.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgfywat.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rovocmcn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgdrjpm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrcsxby.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwgbzpi.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvxwcxa.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoxlzlk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkbvzwb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqeicseq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoffzuc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjklzhx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rixqgcpg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dkstwwzd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhojmzf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzpycal.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yateyeak.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkrectp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nflcpznu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2coppbzum.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ducyplvj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpujttat.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2degttepr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryszthpp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aeusddgp.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2grzytctx.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ycovzrxd.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqysque.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2scfzmwlq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnqqjto.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2udowmuis.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jdloyfyh.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2prdblfyn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2chuiaeft.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdyihmb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2owylzuze.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuwbiie.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2shjbjghd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hiepcyia.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lloiejvw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2svycpytx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgwcoes.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdsnzxa.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtarkagx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2khyexsjv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlkabhi.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxczsfw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjivhni.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvblfco.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2keasaomq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrkwdix.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqjekjx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2zdomlvgi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzspvhnp.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bghkiadn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkirpfvf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuqxydl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nyepvhob.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzkxxtb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbkjogq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mgebxlfd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvlueyr.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2acmaiqop.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcfjken.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gteoqggs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2trnbalol.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkqclcv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldazssew.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzuhzyh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vefrrxea.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwcevlk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwsymfb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2azzqbwbc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjeyieat.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2vakmdllk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2npkzijfi.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxshins.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kesbanpn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnrfgyj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfepgtn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2fhggdmar.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2otglkups.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zizhbkfc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrsfqma.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkrxvhj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cphjmyzr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxrwigy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjxkmoh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nakpirax.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2otnwxbyg.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbbdvyf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfsdidp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpyuhmu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rivsdccq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2srlwqbhm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbkduno.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yutbkxtj.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpbqqfx.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiqsvrd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcjkvvy.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cpttsmue.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvopqny.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbdmsbb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2jlapgxjv.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuyptks.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmbmsot.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkfoxdb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vvooaxrq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqutwzdx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttavzxfh.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2yaignxjd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nopvzvkr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwryfpa.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gildlafk.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2karhwdwr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2miajgqmu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2flyxfkdi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bdiydisd.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvtvkjn.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcduccm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vshmghlu.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcyfkxy.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vgedhszo.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqnygrs.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbswyhi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlgirgt.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xyaiijhn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2prkgavxu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmuuurf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2egwitxjj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cusnfdfd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lahecnys.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhqtrox.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2glxpxqao.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2prkezjaz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvobmvy.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2djkoepsb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2usrtxwtv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkqeonl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2eodvetmc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dokadisu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhalsjx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2eoceowmd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2napptbvm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcrbhlp.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvzegsy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrlafbh.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrlfmnv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dwimljdi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2juilvyfq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xasxgppf.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxepvyqq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ceptflon.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbsewwi.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaddquu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjizjjn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2felttsaf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlnvnir.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhobnqe.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhwjicy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcubktfd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bsndfgrv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxrxeds.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wercgatt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpqdbcn.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2adkokwxk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvjwjfh.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2azicskzt.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmlntuy.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qezrtcad.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2thlqrsss.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2grtjytoj.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gofjzgqq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tongwnhe.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nclbusvl.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cwidfimc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2limxrbrd.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xkozkwuk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdkjrlw.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2velgciip.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cenmamhi.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyvgiyk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ljeosdqz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2letpggav.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vdajjduf.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2pobpyisj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwbpvdf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tregxkec.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iisghpyn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvgpucn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2rbllvsey.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dhckljmb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwsmsrm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2unjclpoo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcgaxzy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgbmikr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2efcoyrup.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoadafj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2avidcbmy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2udgtisud.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qyivjaam.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2flsaqcci.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2uorxynul.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2jkipgmbh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kevzgaot.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qndzevgy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jootiqua.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhfcrmy.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgcaach.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdpuffi.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjpltye.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ritoeoya.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tuescucj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyhcnxw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnmqrdx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2blhkwkjm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrgxuzo.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwziydz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2merekxsn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrbtmfa.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2tyaycsmx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvecfszm.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2xadzmann.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2znkhefyw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2oaswapsx.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2deyjeciw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2upovuxfl.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2icmuvggr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkiuigp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zasofhtb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2nngvmjft.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2opxelqoo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2axoveemk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2hztwfqnu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2odfpwxda.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfnaurf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvoyeby.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjjrzql.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cvboovbc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2hjidrrnx.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2mmotxjeu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2usyuedsk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsuwjzm.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2xzivdzqf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nvouewem.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlbkgcq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2llrnddss.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhycsydb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxifoys.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrclwgr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbapkbpm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2klwfoljb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yepbklrf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrupvci.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbummjtl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwctsig.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjitqpj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdtcrje.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwetcust.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdqjted.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2doriqnyk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyenywl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrrpief.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zaemautd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmzddpp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtofzgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmleqbqz.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwtdits.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqizvfz.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2larciotx.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmwubsx.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tgiltxby.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2smpoqlvk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnftikmy.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzixgslq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2krziffnf.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbfypkv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dinzvrnw.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpbdrck.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhcncbw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2igxegbei.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhflgylm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jydnvias.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2akkdvxcw.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hevifdqb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ebziqpuz.html


<!-- 参考信息 -->