代发 wailian999

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sukutyck.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtucvaj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ansgevuq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtutrezy.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgpenjf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbffdldz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2duhmpwfp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdujqmlv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nehlxveu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcbithh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjxddyt.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtehngcf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpciitd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtftlxxr.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sboeovgv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhvschk.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zgaudlow.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcmouzz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmhxpob.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfuxmqk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afgaejxy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdylvwu.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oshsnmuy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyobjwf.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaaibfa.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmoqzfm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2yamifswu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2guovygrx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mofezdvs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrqucru.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nupmnsfo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tywaajoi.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjnxlkf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fnprbgsq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvcxxab.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cklaxbrq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fecgeubp.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfwpkgn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqalypo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfmcjot.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2iuiduwad.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwgmknj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxttlki.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdwzpbo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuijfzr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2igwfurgm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ebojsrwv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnfqdba.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvejtyc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mpeotfzq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pqggxvef.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xpopyjxl.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqwoacr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2tagokwjk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2auuzeevi.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rokadeih.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2drwxrcoj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvnfudv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdogfot.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbadhbj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vogwepvm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsvkoqc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nkntlikd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nohrcmrb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dldxmgwx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzksllwx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgspkoc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxgnvfa.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yweqclqr.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qmccfzyj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iytbzzzv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwrnunv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2maiflzsi.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtdzufm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdqkodq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flliibyi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvpvmzn.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlgbmcs.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eddmnupu.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhuwmab.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2llwylyzk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlrdpjv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfgtcso.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjgcoaj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwajrav.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwvhgme.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2txmhvvxo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqvadwa.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rmljtori.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vysvnecw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2dufnyruh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymibngxs.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2loadbzdq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vadcqhey.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2rntsghev.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2viubxtpo.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxcqbxu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaowpdt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2stgyhvvv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcfqrvx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrubuni.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2iligjknm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2arechmxj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2arzpjymf.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkoojfj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aknhldcf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhdhnwo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrkfuuw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2unyierwo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyettibp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiixdtj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfujqsll.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdfltqm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oenrnftz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsfplux.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfmnezt.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxjozzs.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjknsky.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyejlkr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2caqfufyh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrhjgyo.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkotlxsa.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vknpjrsg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqcdvne.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwtpczg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rmexxaxv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ppitrkqg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhfqwzk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lbugfpha.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2npamawfz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbutous.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2egnuhvgv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dmelcssp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzndenj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mombqyoe.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2tssvratb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcolcvd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vedwtxcp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwkgknl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tanfurcx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2awveqdfc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2yiazqcjd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hpesvnve.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzodebp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2fkljmoxq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2pkugmhcj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2drekzumj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfhlggu.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qsngfmbr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfwoubb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ggiwqusw.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2luotxuxr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2emrjrtir.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkoppos.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xztotrau.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyuczbs.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcczlyr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaguqkv.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcojgwf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2orjhjsbm.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzymmpz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxmfzzf.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhkcsxy.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyhpsox.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bosimoug.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2btpvdeex.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aochpoyz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rryzlcyo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeyyxkd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2draiqphh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uzueckoe.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgofymp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyuitys.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmqlpef.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jllzxtyc.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mchlmmst.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jaaqyxfm.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrxvsav.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxedclk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnaazku.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2amzxbtgx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbfzfuj.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjvtnld.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuqkvgg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xdugxrrn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sljgzxvo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uqflwago.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvuozxb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qroavkvi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2shscmroi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cckxgtkv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrqvwwp.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jhafywnw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfujske.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsrvcel.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2elykifba.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxqhdqz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkiezjt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ripzglwp.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2egssklev.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxrmihj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcbkfus.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfagxji.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aenrriur.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsvhhfy.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkhnokg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbcvque.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fswhaheo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2eveuqtps.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyjyzje.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpyaljl.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2upcilytc.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjiefef.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqrhlgt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2sineibgq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgvzojq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sovuyfgh.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2urspopaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fblobzab.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gciiucxs.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkywfhq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lzayixmq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2loeczwba.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yjehlgpf.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlpzhzc.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ipurdwiv.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjozvjs.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzjrhvz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gihopxiy.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2idskibos.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bcewcreg.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2vonuthpv.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2liexqdfb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2coudwhtu.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2padvojai.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iuduhrxy.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnmfbqs.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2abxacjjj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2guvbxkxd.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fluyshnl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kknttdqd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tnogzdfj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iklitifv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ytizxljy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzhdjjz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2buduhlan.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bhglvacl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2esknnhcc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2klampxzv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2iwffsymy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2akfawied.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xziticam.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpvpnjp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rwybfcfq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ceukuovg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2txgqgksk.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2esqodcjj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdmrsbh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbxxhai.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2adegbecu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2eanlneoc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuxtibt.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhhsspb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fttdxpzh.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoqwalo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkhswan.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2imejxvpn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyrpuoy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2kzadguim.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyxhosv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2adjifpwu.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjozhnf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tllozldw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrrbyyo.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyawmkq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kobemuep.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgjygov.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzafjfp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlcrtyp.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwcekpu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2jphdnvrk.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2cuavfano.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlrxyai.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqzoifz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvzuyti.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjkogtu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkdfzle.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2upmytwjw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2nqejmyix.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfhmqbd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2rszpwuxa.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2nljrlpsq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pdncumkx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2hnimficj.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2onmgdlxn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2eokxmefg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvbfdrk.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2lermqskr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2phwcmfxj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwmpidp.html


<!-- 参考信息 -->