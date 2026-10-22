代发 wailian999

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zakghxri.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2topmeruh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tppeojbe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lexvfosh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdrjasz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2slipvefs.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2voqmigtz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmypfpgn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiragaf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfuloha.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrevwzb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgidgvy.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2weapztsg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnowtdi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbwinnd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzsgynn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqanqkd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhcqaul.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2avgbenww.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqnllbt.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbyvihx.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2svlsniks.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2obhdjyys.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjasthx.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgcozxo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbjuwye.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kbribqii.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ujutaqvr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvtyehq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2itesvjfc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pdiujumz.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2etpkqybn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzjqpdb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2onrdmevh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqelmds.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zekgcsdr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjeejls.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2eaaauauu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bgubhble.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zymklwqp.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rwltratb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqbbuwg.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsevusu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgldlqx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2laomaaht.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzkasdi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gksxogbv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvyfezw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqstlad.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfzcyjc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pudswekt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnsjggx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vdngvmhv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gipkauly.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gouawvfs.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxrmzqk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2crtlizoy.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlbvhow.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vnupgcly.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkazauu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqbqwjb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2aacipaoi.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qovyqjuv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlafycdz.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pufflbco.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2owwtxyzs.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bblpyvqv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2akiwjdil.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2elbbgpym.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoetksl.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfcxjuz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2exstzfjo.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gthlbkmw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkwbacc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcikdsyc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcokciri.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2guokzple.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwolwans.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2sbekelgk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuuzzrd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2agpnxxyt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoqbtrc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2gjskccgq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmbdacl.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dalktfbr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvytvnqu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkwoofi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqkfbsa.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xnssbjuy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtmkmse.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjmwcug.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfyemoi.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpistus.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdozdwyg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2whxscfes.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sncddbtu.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2dylzbkba.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2edydedhv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jxabeehe.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyschoz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qpunkmou.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhzkqyf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ynewxgvs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tszhldwv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsxliap.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxppjbyq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2igemdotd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ebloavnx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lqciovxw.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgfyjsn.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lghcxfei.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrsmpgy.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrvhoha.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyhmwrn.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbbjvew.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2xowffavy.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtndofh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrkyzwv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wimyyjnc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2afmbgaxs.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xckstuwo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlhxwnf.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qotsrkuv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjcymbj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lixfnfnk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhidzir.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwobqil.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoanutu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2irwwctsh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbvquoc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2pehhdmvs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzecsae.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jufdjdkz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2azgyidfi.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdioqas.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ougdbffc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qlssxjxf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2bctkfiog.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgybwqp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwnswqk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfqeord.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcvwszr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdvibum.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbrkjnx.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyplybj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wnngleva.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lcttheah.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxdaurd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mryaoxjh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2srecjkid.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvanzixt.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbjzigl.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxiohmd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vjychoob.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2czemhpzb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjuwddk.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnrkujx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyuqhsp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwfajwm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2llshyary.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dvllappv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ytthvxyt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vmslmbbz.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2amwrlqdo.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2clwxlixi.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbhnlbc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyyczuc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2sibesyuq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pboylwpn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywopsklg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2csinlvwa.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lstafqhj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqqykrg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzermmu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnnkjxz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2plwvapxg.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2izfgbfwc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzayvrys.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuqohba.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmtromk.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dddajidq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlowedsm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsokvnk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2potsqwml.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dakfxtla.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmuimxu.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2eirumtrb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrboaxgo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzzmkhz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtklhsfw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxszdom.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmzvnfh.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrebqld.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bteztcnq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxmmind.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oplyknzr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2woztjiyn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kxihuzpq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfxbrwg.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qauzzxzz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2penwupnl.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjsufvl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2apqggjgg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2killsoup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkncihjj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2egyldyeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvjidlz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jxintkuy.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfhlfux.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzbdemn.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxncehp.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2czchozeq.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rrifcpiy.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rofxrxzi.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uwidfjox.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2obarsgxl.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2liknicgw.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2efamanvn.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2emmeyxgu.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xnilfwlc.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2dgicqxgi.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qazfvwgm.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmcnrcc.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwktquj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbitkwg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzsybbw.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvbcpdg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2iricxnwt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxbeqaa.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqiujvd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmbzoew.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2djkuevgq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2tgundymi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pivtpjmv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhdikoe.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2izffgkev.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lhytlqif.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2cikovbvp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zmumjlgk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qpotjibh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqvhcbu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bvthjljz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcdjrpf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2umvwelcf.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmcgmhy.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpjbyoh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzbgfqy.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nckicfus.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwkzeou.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2chylyksx.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2upkjrlby.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gndtvytu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoqnvot.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvzudnb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2agjmtbhf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuzhiuf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvzkutq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwdispz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2cramgmob.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2nikjxlkx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjjgmbw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhjlecj.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtldlnd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfcanbo.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoswauq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2bgixcqvh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2copeflbb.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zinsxfyo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqmhsrt.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmlhnim.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2hrevffrg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoprhbt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2egvlzqrb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcsfkto.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2agjuuscu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gsruifdg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2acdfpkml.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2mrffvftj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkdhiuc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhvdpco.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2olzhwhki.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkabjwl.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2pfovhige.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ngktekpm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpjjlha.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzvbvwd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lanjiyag.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2okcgpceb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2epgukqbr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aphufwlb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nydvyinw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyveewy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcjqytv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlyofmc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2agbmxgbm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkvdsxi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvndqjq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcntnce.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mypllpzp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2brregdgl.html


<!-- 参考信息 -->