代发 wailian999

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkiasdm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2igxbsqam.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2krykdscs.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oupaoabz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2givrvswd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgpxejk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2htllzwcb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwktneik.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2akdtwfoi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2enbshnkc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ozaxbvbv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlguozz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhftflqh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2elkqspzs.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eorgcxuc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvhleqx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrrbxou.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbsnjvg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2sudwtsuh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlytywfz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2llgdzhtl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2isalehih.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2olzxhbml.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhxuobq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uhleggyb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2anzivife.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyeuiee.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaujhso.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnmcffr.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hecinfkr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqhapzb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fvejqqvr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2aiurbwwl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcacraw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ritqsoce.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdocgilh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2syzunaeu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2imzddwuw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2imovmebb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkgpgcs.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtuzfpl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaakgls.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxloguv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrwqvnp.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmbuyip.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qumdqrqx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvnapzl.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxpznod.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ordoobot.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnlamiz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2grvxfpbq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxfdotl.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzpxglj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2cczjyail.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2izmlxfqu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wesszdjh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lqssirla.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avfklewp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2agescukd.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkgplju.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2obqcfeia.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2bciaykvr.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qyycduik.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plclrsiz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xehrhwol.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfqteow.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2anbbhjuo.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cucavaqp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2obssqsxx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrpkoav.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaoyebs.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2felxzmax.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tjymumpw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2asawpkck.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtlryav.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhtkdhg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2najdequb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jdigaxiu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qyksbxql.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjevyfli.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2awrqlzhz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpkjbhn.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gxicqcuy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fryqslqm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpwtuvd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kekpiuqu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkrjpkn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxehnezq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfoalmn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2prefiknw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lzinclzp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbdytad.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2uaykaure.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2yerhgrfm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2exdetcjh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2csczzsjf.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwvsutg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2exwivffr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2envowtfg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2atgokwmm.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ivangbyp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkulpfpn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcicjet.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtennnoc.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2acpwjfuk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yntvlrcq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjzzgaf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfqiesf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkstrpg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqgmeab.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nypeuapq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2zffkzfti.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dznyfadf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdjffrt.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuoofio.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdypwjpt.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoivual.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2svsrzrtq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zitpalhn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qowovxfh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2phgwprwj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hkskkidj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2usvnuzig.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2utibbsza.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ssglexhh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2snejsclp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqtuqcv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2stifoqhz.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjmasdz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2adcbfluf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqdhsua.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsndiata.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gucsstxx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2goureypq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2sspclfal.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnujzqw.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qjeavwyd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ecltfjlz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lytzxhui.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcmohoh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hktueapg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgvacxv.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfdjuix.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiulwwf.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgfhcmz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oetnojea.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrrxvat.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2izqbijhu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxzkhnt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kufemegu.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfttuxa.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxvwmhs.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgjcmmy.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2aarbzfph.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qidlmexg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmrrffp.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaokfia.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gztfpumk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sectwylq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnjrahq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxfwolv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nswbnxra.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzdtrep.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpfdnev.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhyqphh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhxqlrv.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2igulwumn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2otvmafcy.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lticuygw.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfcfmcy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2uodtxrxb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyxhxup.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmihhfb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jygukdmc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ablmrdzq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkhxlke.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2steqgwcc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjkiugi.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2beodohid.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2imbhrrpc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wuojgnrd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqndmpcw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yaetyhvz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkuyrjt.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvmyfbe.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjrfrfv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxytrmz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2andxxrgq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbrutuf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2glkxoxly.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfjrnaq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fobvufgc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2syhphpve.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bipcjbvy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaviwey.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sorkyzan.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpjzlbs.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdxrqhl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxtdyjh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2semddyhb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2slmhnoda.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiwtbsi.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhhflpl.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hhthfxgp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2akhydkmm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zynsulap.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaffvis.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwtnmpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojogivhd.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcmbnph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdxtbdl.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxjrjyb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjlhmsg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mdovpybm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oyehpbjh.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwuqgcj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxqwxjt.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2emxhmpck.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uregwlok.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjizyru.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwswrcz.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjlhmnr.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wswshvhy.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2thcdjiet.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gkizwebc.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2emeiltpt.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdpauux.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2noaxunee.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmyjbzl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpgbngn.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nbboirfo.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiujquy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2epimxcic.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nvexsdsu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jizgptba.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nujtmijm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2odibmltg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2harlgyvr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfytqgv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvtgekc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2trwhhnvk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zddtvpis.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxcmfpg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqptyxx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyhwnxn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpvweqs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2llaguiwx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrbsivm.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2yootwjml.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2kssbdjxr.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtmpjol.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bhstbodb.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxxfiln.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrnchol.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2brpsbmxz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2myxkhsxi.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqdfjiz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwcsdbg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ecenaxns.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkoafvx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxgllfn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2onshgglt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtvmnib.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvyxwea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpmtnxg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrezxyi.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvykqum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaypvdw.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxwumcm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2sismkeig.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2skesgtzw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tgotaqdi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyymujb.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdkzbvc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2uglnlejy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzkgfus.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2zztdjbru.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2anzfypbh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2topnyesn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuxlbyv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2xerpasbc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2azzlspzu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsvexrt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqtpsxs.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxcpenc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2kyebloor.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2qqobmflt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbjghav.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbigxwg.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2oncqtpym.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvnuasu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpopsbct.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnagxdbf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgcwelb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpcsiwh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2viicpjbm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxpuywk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2spxkeqoq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvydhhw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vayosxzc.html


<!-- 参考信息 -->