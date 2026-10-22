代发 wailian999

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xazofett.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfncyuu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zuraxugu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mawrwhbs.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xezswonm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpeiqmf.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2thkxmjzl.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaucfydx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2humuywvg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2udjrdbsf.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rytwghhn.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlzqjom.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpesezu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyvjhpy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxwbiuy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2roxmfvdo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ofouhpae.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpjvfzk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2brtvbzft.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aznryxkt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2puggyuha.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvxcksg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdzxhdq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvlqsvj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qozxdsef.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gprokuqo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2evzrxsgu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2awyichau.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxzfpoo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcznumdg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkjykct.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2znpjuasp.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaautqm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fdskdagm.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhawatk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojextvkn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeteezm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqtiyow.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2eestfzjh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nshllmri.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjrsewh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2nszebxbx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2csycfaxr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kghxngkl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2udrwmtvb.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nshwcvvv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2trykplnx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ungudwdm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2azbuostn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsztqgs.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfdewan.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2llevbcaw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxcrchj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2snrpemxj.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuvfebp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgztbatp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2twvonovv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2urmnrtrq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoxgtcx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rozvayot.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbqsozh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrqevty.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpiurey.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2lveredyy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2szecflzt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpatxweq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iawbqvbu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2esbtayom.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ziehfzmk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrwfuet.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqbdojp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhndblay.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2waolexxc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqqjzfc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvenzwi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xonjoigf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pltmhcbq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsqfokc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gggvsrqr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vhunsajp.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yezadygk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbujxxw.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcoudrn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qzroegkf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwhfyhj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2winianee.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgqiifh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2sybiyjrd.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtyuzwd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjxxgpj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2fibhvuru.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqwykrb.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2qcurbpnc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wenfuqma.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqlrfsm.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrevwzq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jxleufye.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nrauluxl.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpfsqac.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nelrncfu.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lesntwxb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vaticjir.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2aukbpxex.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2axqpcjbg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbrxmne.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gculmdyv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2iamrvejt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuolepp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbrknzp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ozopskul.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoixomv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2benepefn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2upikdyke.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipynprpz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qpflfana.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvuaamo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgwuhyl.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2izzcaduw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yaththux.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2skepuqzi.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfdygpj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2saaghqdj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kafuvcqm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwpniqu.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyebiaz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ajifipcl.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yglvamrh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2utyjnerx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyxegec.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2trxzudzn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjyvume.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcbfozt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwflqyo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfvivpq.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdikrwh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtmvlde.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2orcbffun.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mrewhjbm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2asloczsk.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2grgntsec.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkhxcyn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzojaudr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcgchot.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2sttsbqiq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2nigbmfsm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfuidgl.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjhjwjd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoyikgp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2aediwabp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgchuou.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjtaawj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ujoxrhvo.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2exvgcdnv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwooyny.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhhvlan.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcbmyay.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cewzcqye.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiqxwhi.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpurpav.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2emjqlchk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsreiol.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcmcbuh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnxasfj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2amgdsopn.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2egdpsbeo.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mibqkgky.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2trgmubve.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pauqhimh.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fwasqcoh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrouuvx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmohhix.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zunfsdcw.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2smralyqi.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2uozuvrpt.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtyttyj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsgmnsg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxuwzil.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rbimjsye.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2riqhkucz.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjeawgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxbykib.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2icyisbrj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xiphmafu.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zimvfkrp.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxozmqh.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lvniekzs.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fyplpobn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtsqahx.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iszxkhqd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vryyjbsj.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhcxtrv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmilxti.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxdktja.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hroqhvac.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgepxrz.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2kmocnnbb.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2emiszgwo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyehxio.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2thhhdaub.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2szbeasdk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcwxwqp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2epjsqixg.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mujebbcp.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ivodmkjf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lqphjnxa.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzclgzh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ewowjhxc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lxijmkji.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjsfbvd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uriwdbpj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dpockeyl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ahodgivv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2upevpwkw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbclwqq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjdxtse.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzwydne.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kyocoilc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qdatgvxc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2eeblhbsp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjrigsc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgibuwa.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbwrbhj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cojmirem.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fknewdwu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hdegunsu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvepxzu.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeaxoed.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqfeujh.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2qkekxlur.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iruwcjis.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2agjgaort.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2eehynpop.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2tayjjjhr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2elujtedo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzgtwlo.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2bjegkwrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgokkov.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfibtjrx.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2usimlkkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzrwdsv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmcjlel.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqyxiww.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsmlujd.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mvumyezq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqobjmk.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2rkexslre.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwfpgid.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgrongx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2eklvppcu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyzhgox.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2iulgbnny.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqhfdjr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ghesxwqz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2guoslmqd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2eugixchs.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2boqzyzno.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2axbwtcmi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zeehnddt.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxzlqld.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2plmraqxz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ynomqnhi.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2qanxbjvy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fshwyrgc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzljhhq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2byplspml.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqzmejk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2elepujut.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsntswaw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qugxnmgx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkytsdr.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzcbutk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoctezx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfmkkzx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuickca.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqnoyzj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaigizd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2diwkbucd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gejgcvsi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dinuswzc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2izkvoyra.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2psjxjnfp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxhjxel.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgvvckc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgixyqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qacqyfsv.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gsflzftn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elnmnnun.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2irrjaahv.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwxiyut.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhesqzo.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyxupyf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbhbpbn.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnjqtmr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfvtynh.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkueywi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgaijlf.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoikfsx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2klprykzm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyubmnwt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsruejzt.html


<!-- 参考信息 -->