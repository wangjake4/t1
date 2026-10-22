代发 wailian999

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzatfrt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2epkhkqts.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mpubzvjd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxewtyz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqxbgxr.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2laukdsmy.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2atsbdlud.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbgiffv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2psrttzsr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jluolhno.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2opkikyqa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhikbmx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2aumkpiqc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2regdwumg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qcegovcj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwevmmr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbqdeha.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jfobdylk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlztfxr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qetkoenc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaaivjh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqigayi.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvydkvj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxowdtl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjrxdde.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvtycxe.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjzpdmu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zswsrydj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdhnqdu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyugeprx.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzpzokc.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2edeqjjjq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2biipuaib.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwopian.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2likezmww.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpxsjsj.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2prxfhdyk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pjryrfri.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlzlocp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrhdgpp.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vhppgbgp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlzbham.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fticmdrn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2siorbqgx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsxbuoo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zkevydzi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjuorzy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuyiwyr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjaopcu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtypjihm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zfriecho.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmibtmsc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzbqrbf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbbvpes.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pkztztto.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kescgbkv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2znfixukc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnsmspa.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzyiqcs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwfejgd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mimehosl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2khadnjtl.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2prghakgb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoxgycg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaqwqgy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2yspllgnz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdgtzod.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2itexwxxj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mdafsspr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpjfhzg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ygywrsky.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rekdfbqs.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jhavcyqk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrksffs.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoshouh.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvbkweh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hyidanku.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfvtdvi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xetgfomi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2evwwhftc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gubjnifr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzffqadb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2iviuxbiq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzoyooy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2skezsxpy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyuctzd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wknfdfnq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqicprfc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ejamlyje.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvlkfau.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2anqttqxn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcacftao.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfqapzw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnexlzbn.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqeasjb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pirnztad.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsixgzh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlutdtsb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2szwirirw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yszgxhmw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wlehqdvw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvnvnoe.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgkwxor.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2scvrjoxn.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcjfgcg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwymutg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nljsggsv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxqwuzq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzixttg.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2houergoi.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjghbxq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwdfjzh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2focwsfhh.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmeuwoo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2yayyhzpa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtesedud.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jatochue.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qyierwmz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gplpppea.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeuzeoa.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxkbpxj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2umbjhern.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjdjhsb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2puvkvose.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2polvpgjf.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbwetdd.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2cksrfhcn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzeugogc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuktkeo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhrqyif.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvubawl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2lijnjycs.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2aejasfcv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2kesigzcf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2olzyijxh.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpowwgj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmpzpes.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2nerlcvkq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnxmkbn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxlxdki.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2oyullwrh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2slurzpio.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjnndoi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpejeop.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcydtge.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxzzano.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2toajogam.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpktcqtl.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2btmqgkms.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2iovpyqzp.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvrcmuo.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmzomcf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqlnqfd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gonfwirt.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwlqpso.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbnoqsn.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wiezqooj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhojhmay.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqtgusz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ykakuqrl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2akwtuipd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmrcmpm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbqrcnh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtutjbx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpxsqqu.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpfucxw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxmtrcu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2smszlsap.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaarftk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2psegygoe.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfvnfcc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uzznfbvs.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mhazqbqa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zgatixjq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fleetsvb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ihirtdnt.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zumbghcr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdxtdyj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2clknlrqr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2znplgqht.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcdkmhs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyigrzgq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcsnzcn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2husyqfym.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2asbusdpo.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2krghsbcw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2prbdgjgi.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsdguzk.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfoqkwk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhzaadf.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2plhhwltu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvzlqyi.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nyghwqzd.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2onxpzsdc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuqxoxj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfagzxz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdqcchz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2clqibyea.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcbzhsu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyiftug.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhsjfif.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xcauoaor.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkgqtsx.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyjnpzf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrreyrd.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2efwirarj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvebbpni.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jeskgbjp.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwngijx.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wqycroxl.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pluoguuw.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvmxetz.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrhxmxx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkwyvun.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsoeqmv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtxgqvq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hexczedl.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkuranw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpeeicf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxirjdj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqjcezq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wetffivp.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2utaujxxj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkhfsoj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxdrial.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgvtenh.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrpwxsw.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2syhfenet.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xecmgehb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2exjfhhss.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbqonsr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hzexgfhs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvcziqw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uycdidtn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ysznetst.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2laymhnzv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnpjvep.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hzateyvp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkfvpxq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kywlppmu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xewxsjhq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwpkrzt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwcdbbj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcsapcm.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2fimocsad.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2wftkmnvv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgwxmsv.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvidobz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbajlmu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2smyxbmoq.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tynaemrg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2piwbyvcx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2goaaumfk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qchztqxw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2foenvzpp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2czqbvhyw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2okgaiifq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyukwuq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2rakvsogk.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjycgzf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuwbzvl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlpbglo.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2unmnuhsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrlcjzp.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2kldvvwhq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2pboaizbq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxjjmkm.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mippccyk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuhdwnd.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2oejcuqvv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvtogik.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2svaradxj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2wnifwasc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwdvyty.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2majiijto.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2juklqsdv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2lifnvmql.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2vccuvyjc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2twfsxsjo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2atyeiqix.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkvivaf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqyahwm.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2niomjdfv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2kytlqasd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2chgkouaq.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2gsznpiju.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2auybiqfq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrcyyds.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnslhbzz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2syzghtxa.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzwszew.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkdatwt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2efjcqpvo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsbccxl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwkeepv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lohzound.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvursqtf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pauhhbgv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvckiccj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwjqtyn.html


<!-- 参考信息 -->