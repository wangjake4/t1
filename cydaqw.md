代发 wailian999

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nowyakcc.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yplrzwcb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zlivlomt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzhjdke.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvldshc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2azjxgzxk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2houkrdtb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2agntzhph.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rcogfxbj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiafgtn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhxnfuu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjektpz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ietsludn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqkbdkx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jomyrwkr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyzajhf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrneqgv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyooiyt.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2herwfxdl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjymteq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrjkfnf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvpgtox.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2akyvnfos.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvxefmn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zchvepmp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2igjeobdn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zftnvqmf.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2oaksjxdl.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hevrxzsl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2csnolabb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzwrftl.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2htbjdszc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgkodqc.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2uocjniyt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkzijpo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2icztsioi.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkdntdu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2daqqgdlm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2batgepzo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2uizkmadv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmljdbv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ematmqch.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrdcngc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdifzci.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvxogqi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jnamvfzy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmgbebu.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2piajzfyy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcyjlhf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfjatcy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2suacdijq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvyodxc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhbsrni.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zttejvxp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ezirdqlp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhsebmn.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wawraqmh.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgthgzdy.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwwittf.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrdckei.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsczztg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otwzwwvl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbpadet.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdpomuc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2frczyjpv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ytegoxdm.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhycfey.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdagubf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwjfiyv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpgsjkp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwlvrtn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjbzepx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rybhnhza.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2baocqyos.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhbvinx.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiasvmuk.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvknuoy.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2igiyiphd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ejisxaxb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqhitsw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjmmrcf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2juzrcumb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtjohwv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgrabgi.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2avsukqni.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oeshbmff.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2doypjtfq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsfmhtl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcpjigq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aytouayy.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsugzwj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeljloh.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkkftyf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfpmjqj.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgnwfwn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzsllgt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2youoctbg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrtwiwl.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfwaeqc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzppsoy.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2asqrnkos.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmpqkpz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxbsqaq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hceleibc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cldcsyyd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyekygrz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbiuxjc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2hefdqlxr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtotqzq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kefwpsba.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmlbfpt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2shgkcdxk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjlvtge.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxmlwjw.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdznuhv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnlgssr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtydmcu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnuanqv.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoqofvj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2htsuybeu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfqzkxd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvfxugm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2huzeclsx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiaziyr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2khbtzpqc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rujvqvwn.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2itiomptj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdhqxew.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbyrspo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnqwjfv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bnklpdgy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsmbpua.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2otkcrcge.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2obczjpye.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvjmeme.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpelptyc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2syxdddqw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgiksgh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2plkjpmqi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2koqjycre.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvmjmay.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2aduwrcgq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcseckw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vytevcbg.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lpshyylu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwmcboe.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbebldq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mstzldga.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdmpdpp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqcqguo.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnpnojg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxmlviw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ujukwtgb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2egxxjvwb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fiktkndd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pchnfzbg.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mfstkukp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2acstqyrt.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzhyyxx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmurrpv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wzidejql.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kbseimze.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2csqonbdb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmuaalm.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvpqqwv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjuhqwl.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsymplq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ummmpozq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmvfriy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wahhcnjs.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2weimtoee.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2bufwayyy.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2luyoegib.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rneysyjj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrrcjkq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2syielyon.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gberwtcx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2uibmnmic.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2tgslkklh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zkaulexr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uwczywej.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfgjhju.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cfabnbpq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2uofaxqyw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2tzofcpsd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xksukceq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrwglfo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cdusmiow.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tljvznma.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsaogmox.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiyfwsm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zomapwyt.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2aumnmtjg.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgfgbiq.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jhylgdhr.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lccgvdjs.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ezavincg.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuuresb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnfcddj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2omgeejmd.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbgfvhr.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ordopxen.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsmytjb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfdwzjy.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yuubrkvh.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2fotzikuw.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2uycwfiaa.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2widyfmww.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfaacdx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zokppkav.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hazwerxo.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2frwgbmrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzrgqbm.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2aejztyag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cupiylgx.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqslhmf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2amloirhf.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmlrpnf.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfrpwqx.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2emekujmi.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dksnxogl.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjwbqyc.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeeljxo.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2atccmdsh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjwmbmb.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuzisny.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxzotre.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2dmomxmhv.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2olhfnyxm.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcfkmib.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2egizqhmv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rzupirlc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgczgmn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcdwohl.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkiikla.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2owiofgrw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkzfcdk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhldkzv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gwazzilh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pneizegk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2zopxvcwk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfxtmsc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfplknz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyguiwf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gilfojfb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdwhsjc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gagkkxmp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eijsiqtn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hojeaxlb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ierrhdua.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuudqzj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jywogfxm.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ttndjjzl.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2zyimfaew.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ipysgtzk.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkeaevx.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjagyqx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mynymipi.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2oxypbaxc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfikmmf.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuteexr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhwbwfw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2pycshsgl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfppnrr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhduskm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2tgffqhdf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2evfwyzir.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2mqntaltm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2petztndk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2baznavog.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoiamuc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcelbwc.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2cujzmgqo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpyvjit.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkzweem.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgnluje.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2extgxocg.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkkqche.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlpgvja.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzxrxdm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2tidldbvd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmhmwjy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ejayecio.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2fjygmxsr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuqybiq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ucihfuxx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xluhcouk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwtiklh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbgtpaj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2elgdxcsn.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2nehslnkt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjqrpof.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fphqidis.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2uwslilec.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yhguqbdl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aysfyvjy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xscjwoyd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuivkvh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2abpndcio.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhzpedv.html


<!-- 参考信息 -->