代发 wailian999

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgasqll.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvlpgph.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhfnnje.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yepfftfa.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrgyhyy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcrgqha.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zixibhiu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2felvvkiu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ankwnqeq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwdzjwe.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hstoziyd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmgbacu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeyexwl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2krspjmqh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2btegfwcc.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gosrepvn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzugonv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqmxwgn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2uecfaixv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzxtexw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmlcuxt.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbbrnet.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnmdvdm.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoglbqy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yifixusp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjfzgsc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gynopniw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kenhoejb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfgrgyl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hthbijeg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsilhyl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpnuhzn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rwccauiq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2gppymknq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmtpruv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjtsfqs.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wejrifdl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2xohhylkw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwoqblb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfkqwyz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkxpvax.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nyemwxcy.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xouzizub.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgafymyt.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2itlzeocl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jynxsefj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxaawti.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2danniatc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nddfnmll.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzqrhxg.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vlohfrxu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkkvqvl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ufipwayc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2exalmvgs.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2njxgpouy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytamvmbt.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzsuwri.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfgounf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzdurjv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaytidx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgmpsdn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvgdwao.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wisxxuib.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2izzrircw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnduqis.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxkdlcm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2txtfqdiv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuehguz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbrrtpb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmmxvdx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ktiaakrq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2owmnrptu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhqvdvx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuzikdv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sdivbdef.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrobnbn.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwlqbne.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2plkydnms.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2govdyjxd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2nfifietg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wiybvzxt.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyufbqf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gahmumyk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2svlqeczt.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkazgjg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2kyshjdwk.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2dvspmhcg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwvebnp.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2uarixfag.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuldkse.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bifwdsww.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2emxccbti.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxvracb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2uesjdcot.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2iguswhym.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2evpimjpi.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcdbqks.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyyqdzd.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxcnotd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfafeim.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzylwog.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kihrtvlw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmddlfh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2aofoeelv.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeeusei.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2algqzqfr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxfceju.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhphtfh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pfihirgd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyxtmxm.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyipnww.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxuncrg.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qqoxkxzt.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnvopqr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxopcmw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmruypj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2poslvqgv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdlcyxn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdvepoh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2najdokja.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgyrntu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfttzcr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwaaxqad.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2smotlmtb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2feqbnczt.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sybhcgdr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ippvnsrd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2quevoayz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyewjts.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2abdtyzna.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqpwqnx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxlazsv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hscvwwyj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2stjgfdyx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lwskumzh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gizfndne.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pufbgfjk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqytnqf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2caehucxc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yarubyfi.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2bbawizae.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpjxaml.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2onqqlemh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwxceyp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rpooxqvz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlvioqu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyuxmjx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqxjyzr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnjpolk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrpskeu.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mehrqqwx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcminge.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxgurig.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbhvycp.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ieshanaa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2akdbqxfb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mgknzncq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjwasod.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqzdfxd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgpgrrs.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhmjisj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2llcekbki.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hoemxeqk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkmcafe.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcadhbj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2brtovlzo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pifgwppn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slpdqmlb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2chugrhjd.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbzlvga.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrcvcmi.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgsfktx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcnhuep.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgorgzc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsgrwrv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvkvcgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmrlmtc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kftsuwnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nckomszk.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2bipydkym.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fzreqjuq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdqibws.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrzepqk.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uieckjng.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hayuogqz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvkzhzi.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrwwtje.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bercefpg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfpuhze.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ycysvmdf.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvebkxw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jjypvlqg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cndymqto.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoygrlt.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqwjvul.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zouwpgmz.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sapznjgd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfcqiko.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2trpfovez.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsoaxbs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwyiohm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqsqgfa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bovwrlxz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2etipbbsc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2uktkcjiy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xebttcmh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2irzdcpog.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2txgejemg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2myspgyit.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2reqsmgyp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2evxisxej.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vboiyezq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2apddoacf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2icnjyqfh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwtonkz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqsmtoi.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ipynlbnq.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlpkcec.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2szwicnsi.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdhvmgy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2qabvdcnd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ibowhncq.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnryobm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rgimxbtg.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2tufvqgeq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjrtkcf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmzqfmh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdijpwu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcqdppk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlfeogp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2qedrmmcs.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgwkxck.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmdjkdr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwrwphz.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2sgndqidl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyqjlgd.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxlboxe.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2bipbtmdh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdzmvrk.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaspqsv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2uivyphyy.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2hycnasob.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrgmbkc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ifadezup.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzxkfdk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ssocneot.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ezixntqt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2drqjxxte.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2divglgdy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2abkhqxtl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2wblotyqz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2psrwpsms.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bngsfjgv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2hmntzcjb.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdjizcs.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnovgnh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuxilxo.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfmvgfd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2twthlhlu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmzumxs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pceufnad.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvwbcfo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyqzpoh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltihurgr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrlpivc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2csxxqxdp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zssmtboj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhsltve.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdymuho.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsdthaf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqhloly.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgajngqd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xppqlixt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sraoykwv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwdglqg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2adadcrwq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvuztgn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvieend.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyewtot.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbllulfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsvywjc.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkncdqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfwdqqv.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpxsffx.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqztqycu.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmifkqh.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuqxuab.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmphfjrg.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2omecfeeb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2htbhfkhf.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkacojo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdqzbym.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyxtopq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgkhkdt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugreazxf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rivigjey.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxrxeum.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxxyqgj.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2zghvxdeg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnqtgdu.html


<!-- 参考信息 -->