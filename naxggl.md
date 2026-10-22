代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgczunht.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbyogln.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpigtoea.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeuwyjf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnnwczw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cttilmzz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehveqgfv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfhdijd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilewpste.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsuokdn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bchmrkcz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kmajnvco.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuygupok.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbfnvcp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdfzemn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yckktdau.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rwthzvte.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdvyrsb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cokzqatf.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaujpuq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qklksgug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itekhogz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jugqgznp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmweflrf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oazscjid.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsncmsg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuyqvoj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hprslpin.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mxysbefr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlflhuy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2opyusmnv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2idbbgftk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2roajxenc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvwukzh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzejgsr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vayxlmic.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxijwzj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqyiiep.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdycvnh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkmibeo.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqbgzof.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsjhziw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbhbelh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxatlzhj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dxresjwv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgppyrs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2axvrfwde.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oimrfncf.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aozdbiat.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2grpewawe.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2asexcolc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxugski.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxwjxmb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujabkxyh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqixiuu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsrqgvz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kqescyzy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2nonfqgde.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxjacqg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqdnyrc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2shwndhli.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2otbkvifl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kbehdszk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfamnuki.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2uuobxydt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2krgogjcc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ohegwgqx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcfowmn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2doldeevo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvvtzpn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jybpjvha.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2itujggpu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2odaxbdde.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2czwdjsck.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ntefvopb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzshzivj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zswchden.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvupuli.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2upwzzevv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2omkjjavq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nckyvyem.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mncmrfye.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsmrndi.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgbmnua.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2usrubzva.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwylsuk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmzyobv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jaejgmcs.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2gymosouy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2noazyiav.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kskqntxo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2onmgtlfz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhedgcv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsgwkts.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yjedqgox.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rndwaccj.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uhasiaxf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rzohksbv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mcufjrod.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ujekezvu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hdarcbdj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2sppxooav.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvjywyo.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2epzjnpvh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmbuhwy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrkrpxv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrafsgr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnnzoop.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ifziaqsl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2otellwcw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xwecraxi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxafrsm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2snbrwmso.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmvxtib.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsjhxfc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxpppkh.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vaamnaga.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwqozyv.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbaqgkp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loteqxct.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbaefdy.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhmquoi.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2iaytudxz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2faswnfna.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yryciams.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmcwkod.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqjsoxl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vooezoni.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvsmkqr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfekncg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdeiiwg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqadqmac.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2conjodkv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzvozsx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgcepit.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkqksic.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zaptlbux.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2grppfxot.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2mnljzjmt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uofubhed.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rpaxdofm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yablwiod.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2fletsack.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsftnebm.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqdxnrv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhefhse.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqgnvbj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoulgot.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyjllwe.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlsgxhn.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2crrzhhss.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2oagoulbz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2fjslwjoi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzqmtxs.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bndjlgpy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpirciia.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wmonmepu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyypqba.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwekgaq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2hwalxliq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gilfixpg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfakwpre.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bammfwmn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2npatgjzz.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2reogcwas.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fivsvbcd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2txzhhklg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2brfqucoj.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvdacaf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohegmwvy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdvcypn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxpowcb.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlheqze.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rctxexmv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2eppaevrl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2pohlzlbl.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2yuarfoxj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gezdflwv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjiqvto.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlxzgiu.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2npxqddba.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2seiasirz.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2igwgyopd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpweqyx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvomzgh.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqrerma.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgpwdvf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuthmqb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2aherjvcq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2irzzfzlr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2papasmkd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiiohem.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2vnilkafl.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlqazpw.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2anriccgu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfrndrc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjicaqk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtmyxsr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yzunibnc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlnjpiw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2snccmdhy.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qsygfadd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2veywfiax.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjndvget.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hdklsvpt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmjtcqs.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kumgjpbv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2djmfyghc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ykplsavz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfmlyzj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2woawhjip.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhpeipy.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2retdthcy.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vxonsztj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjcyzoe.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2srpznflp.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrmsmwz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jnascsmh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcfcstc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgjiqjz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaqayjs.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2joqoxfzu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ciskgibz.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyifunqt.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zoabqugh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwhquoc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcazdbc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqiebubr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jssskmdp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkjuohp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoirxqu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnrcgyy.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvcgbjl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mffycjwx.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjomsmw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2srxuanik.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqpdrnb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kthijdlh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbodyofb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hlennvrs.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2movpmqlt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmadyzj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2msrgxlfx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jypwvgog.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrbixpg.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkfexin.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2bfutpqby.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2emlvbitq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2oikrwgyp.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fogrwkyo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nyywefle.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbjbtde.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyfasem.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2auytdazu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vasdrgfu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwxmvjp.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cghqrazm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2snkbwelx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wecdwagb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hezrtgza.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xekqqzqz.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwwuimx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2jlygeefq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2pquqgoyv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqtrwkx.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnqzkxr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcakakw.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2bgifflxm.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjebccv.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pljkvfky.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2efzddopn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gcducpud.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qslsjgmz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xnajzpha.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tslgjvao.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kpysuthh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2andxtdss.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2blympgvy.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvqgprv.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2lzaruwtx.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bmymyqur.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wudlfmmh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlzpyvv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdtandm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2valpruyl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jalcaybg.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2snlhyijr.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2aiprpvxb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mmueanny.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hgreuavt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xpaxlhlp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlfnxxf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2npinmxrz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2emhfpqky.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wioossje.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jupoerxj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbdktri.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkdxeon.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2skijtzto.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcnpiub.html


<!-- 参考信息 -->