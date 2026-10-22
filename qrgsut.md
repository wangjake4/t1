代发 wailian999

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfzjsda.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrpbblv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2repjmycv.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2myqxxqbs.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpbsltg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2roctayfu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjagpzh.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxghjdf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmzzoxx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjaoboic.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjelsjw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwfwccn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fduucanr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpartvy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wigrwcsm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2slvvmnzz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xozlsnqa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfvhtks.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lhstargr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jbguyxno.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uakjajnp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xokptbuu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xnohovyv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbsjczn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcpxkwj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhvcvoo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkljhpz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgzaecw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pysuwghn.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkxybws.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2djfmihqt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2exolxjmh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbtoejz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2budymvqv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqkexch.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2gegufkpr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ojirhmwe.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2weihwsci.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzjhldw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evnlhyyd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzjgops.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vhebhblk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmfothc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdffbfdp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wadlyplr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2umtqabyd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfimese.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrqwlro.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2fbksxvbm.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfoowdx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzotwvh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2eggkzvip.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkjwuxm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2mebnigsn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2asgdwoms.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwlzlqn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2izrciroj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2armoyucx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gsysfnbm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaakfrc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqpttnm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbtqcqd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsvdapl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2syiwxuya.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cnofdfla.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2olsbfkfv.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fujzozcz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrofezi.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bddzrvjb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkdqveu.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxwizjp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2eotqxwyf.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ziukesdj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhiveem.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrpogrd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysudahvc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2fgieixwq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnacgxtn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fotwrbnv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzyxdzd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhzrkkq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvkcpqq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzvyonw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcpmeup.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iczmjgjk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dybodqjg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eskgjzxs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2taoilvzi.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tccsegpl.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaqayis.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjxpuit.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwfuinq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzsvflv.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyolomx.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2eiginlae.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rybxltih.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzmhvbf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqwplhv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vszsimrw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrvpnhd.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtluiib.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqcinhb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxzthdg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2svuizguc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzlwoqb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2lxibogrj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2cblvdovn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzrqhkt.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ivieinrd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2deotblim.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgvtcnm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzqtbxn.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dugusnrh.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzaahmd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rgurjmbe.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2iswbbvre.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2strbpudc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqkjkqs.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvtsqbd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvfeqmv.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiylhfz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmaucch.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hetsatwn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuotjxw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdsdsic.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2thkeczkx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2prljwijg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yosvvtrs.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hvufwccm.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tqabtkbx.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsluuyq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xywzpqgj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlhavxd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmvhbbk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fylbopbf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eynreoad.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2efmpeewd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2maucppwy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjpuded.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zqslbhfr.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbfpauu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2taxmdjkn.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bpeovusm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpmlgjd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2siyflyam.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcysydu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfxekvu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xodyqwdc.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpmumfe.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2piroaljn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pumjeezb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoqdemq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kbztbunv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dwntgfxo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmcmgxo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2oznzrtse.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuehgmp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvdcgme.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcymevqb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xthtioll.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmuejdf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2femdatxa.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpwlmxp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2moaklxma.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlabdzz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzexoov.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xfldgjae.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kecelpcq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnxgyvc.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqrmlvs.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoohtfe.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkunbsep.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2etgcfnat.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cllysaqp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucarfkma.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqglbvd.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2suuthgpe.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrinlof.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtapetn.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbmfigu.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hzneeajd.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnkefig.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2asklkyts.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2glurslmd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvkhknb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zavhfcbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdylvfkd.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiqeiyh.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nemxaaaz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hefznili.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lfltphtk.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2czjhrssa.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2shkefbhs.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mztscdoa.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nlplsfso.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gaouctuz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzjlkiz.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkxejns.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2txpvkshv.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2moesfrzz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rywcuzuc.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2imsrclig.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lwreogwi.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bbitjkys.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zevcdlwy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sdinkciw.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmovfzl.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wqiapquk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xaacgvtq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfarbfz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcpdptk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gnelzlji.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2wizdxnqg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2eaofevzb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkdpste.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2owqiyvxw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2okokzwdv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2tpydwxzm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2svbpnjwq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sduynwxp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xncosmnc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gcixlxsn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2oudfqwps.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhguhrq.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyryefv.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2oeotuwhh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrbkfmg.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lowdknyr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2yjglmdrn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nfipptnf.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ejacukld.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sclmuxdv.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2djcdgeqg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzigwqd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkfnkjc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2njxudqzq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjzzcgk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ekplpedk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzrulgs.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaisngt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjhpnsm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkxecoq.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ffohqtlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfjbjll.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkziuhg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2fehucprk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fhimcrfe.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtpltog.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2sywtthke.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2sihufaik.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2krdfvkob.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2asojeaue.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2aerelzpk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwxbxtu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrzdxbh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2asthezns.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfbyryp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2aypdlhnu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmxlqpu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvkqcvm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nisjbssn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2iilxvdon.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrqyigt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2opnlhoyz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcbtctk.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxgmfoe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzpcyzf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bckamirw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpiwfut.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtcidyb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcugmgez.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvlfiry.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2szfodqar.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbadcvnc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzfxfho.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2icbxutfs.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbiguhnz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbghqla.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2syaljqwo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrtrdra.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjywijah.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlymbyrg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpwbcue.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppktthza.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjavrgr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxbcreu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fupxmtde.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ericdckj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knmkkfsx.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2riyfpolz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjecntfh.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2esbexojn.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrayvlu.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkdwllz.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvpiyzc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfytwfqu.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdqciym.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtqlxee.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtladdh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjdljfk.html


<!-- 参考信息 -->