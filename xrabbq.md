代发 wailian999

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdjqwrv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvhgqpg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzamtwi.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wonejkgk.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfpirov.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zraomtyp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfbjjsv.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2olzrslyn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlgvezn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpppalt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jddehdrq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwhymcw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hinmbpqk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcpyext.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyalizr.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwoqemy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fibfchqi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiszgla.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrxmxip.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjohkeil.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uhncnnfp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbrokxy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxlstkw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ibchumil.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxmazic.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2dymmqkjp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfbsmkn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvymhlhq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ariqyhen.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2khdkcfnb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mdifmgon.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2phuzntjx.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2opcmgrqw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyifayi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zypfquku.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsyxvad.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzsqvdw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lchwduco.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnyoptg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlqodtq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzwidmw.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2evtcebeg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlcyecz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcnejtb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uqggbsuk.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ntddxqhm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vscddpnz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tedqltle.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qvedfwzk.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2crccqgyb.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqoamhj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgtzfpj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2eiorvrpu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hffdyype.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2btwpwjwn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2dksyugee.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnxwopy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpcxgvi.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgkfoyn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoywcztq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfznhcs.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2flighgrx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2oulwjtyi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ussliitq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ewckjxjf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gymyjnsx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgoiutw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiuoztl.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoiqbuc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwwaunm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vrutudgo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2oydflxub.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sybflhlv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufopzcxa.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnidbpo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yognntmm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnhjoql.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcdsexd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsiuhpr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mevygxyl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsqflrh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfatgucb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nopzpobu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2suwippkn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxphzxd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwxfmrx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2andomrsf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdhtevz.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgyizmb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmnlhpa.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzfemnm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2coihmhtw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2beiihosd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecesynup.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwgmnyn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzexdxtk.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtrahlb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjgdrhz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2fynlxrhe.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqifpdzc.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2dpevhiwd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeirdse.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvqqxpu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2eeakvlnd.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ctemfsjy.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2idknsslc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhjgirg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkodqnx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlvttow.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrlylnt.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuujkui.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pakyhvnc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ozljjbad.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvqfknq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiruwik.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhniuzrp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kuatthjh.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wovkmowt.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yoduwsmi.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqdjtzw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yiephsem.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2kreqtmyx.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfwexrk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rapdhiry.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bflffakr.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2amgdxioj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdzrjvb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzmqnab.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tjffrpyl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ugttaqsi.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tyllauwj.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwkxpqa.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbnbowc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2isinpvwu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkclojih.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2edxiezet.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wuozcbsi.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2svzguzig.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvbwjto.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfvngvl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmqjssf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqgdkrm.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2utscihpk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxzwdse.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxgrqyp.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgzelab.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2stdqzsic.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrrxnhh.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jtshnkjg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhthfiu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pcporvif.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqvtfan.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2egveyrnf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2uizlnded.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcniqus.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnkeoto.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcfriyu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpasqub.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlkrgzt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaxwkyx.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qovczfsn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ombsezem.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jocqhcks.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbadisl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2efyhnbnx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fohakzpd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2osmotzhq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwxgauf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqxyfxa.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqdoufc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ficqrfrh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqvmcog.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyuyxtq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2puqhvmda.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpmhxoa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uatfmptj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqvjhxa.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rousxyjf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2txwkeuss.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fngjcrbh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdoccsx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2huaucjeb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqahbdj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2yshatzft.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2smvwbwdy.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2pmztcgzs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxmbkuz.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bsltxfbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkohelg.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwcuujn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnpqghj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwnjeal.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyblljg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xueolyom.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsdabiw.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqihkoy.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbqochq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvkvmfd.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2izrltwjp.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iuebxxfp.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxofuto.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxstoph.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgrxggs.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuhxxhb.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rfeuzrnb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fbexkvkg.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhkdwnt.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbbiytn.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iohzebvc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmpmssy.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2deadjatt.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrfkrjv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsrurez.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uxekrdij.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nafzoxqz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2sipjdjyi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhryswg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2inxeimyh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2echqkaoz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmkdxxr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kfowdwgu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvesrqq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yypyrkxz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gnewiyyi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcsxorb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xungsrez.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2bxffubfs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpllyji.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmodrsd.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhrzkuk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ypooqhic.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhzzdmj.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvfnqhs.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbbooje.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ardmtpnx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2utgicizp.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2komeqcjy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2icctxcyl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vimlxunf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtkjpxo.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2icnnxqbk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvduykb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhnmbmn.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkjngvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krzijspc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmxosex.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2uguwmmym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmphplq.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2smdrlegu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxkwbtn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxxlxmz.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfylsmd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2gseirejc.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcxncmy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2gvknzejd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqthewx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmgusla.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtiazfx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ubipxmll.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2vocmpbrw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2mskdoqjo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdpwzyp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xttzetay.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkzztve.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2czyixcen.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2smfwwzex.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2kohryjdv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2vfacjrvv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tgayvsyu.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2fprlhkdx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vpawyorg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrzwsjw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mecnktej.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwhpwjs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpozowg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbohvqc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2icoxwjqi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgdxwuu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqiofjdo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aaobtfoa.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2psxqofzx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpoazrn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypovczdq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2amoxfiok.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2razvgcgu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiogikr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvxcxtl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2luxvkewf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzarise.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2auhlffih.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2avqsirso.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmijjtg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuntjox.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmrolaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2weyilotd.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsfnwui.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2agdnoojh.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtulzxo.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sefncsvl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmckhdk.html


<!-- 参考信息 -->