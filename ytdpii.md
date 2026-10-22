代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2inazfajc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbwtpky.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsfhlub.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnliofy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjspdukd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrdctqj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmvnzgy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2izoiizyn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqazdku.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpvvvpk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzusjpi.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlbnaqy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wkesafrc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2akzzulpi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdbqqrz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvkujpe.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsfpnbl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2irifzvef.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxgyfys.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtyeuqg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrfjcoj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ainyryvm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxgmrmu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfiuwvk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yohnakri.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuaaztb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhiysyiw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rghdxtst.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgtwpxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nswkamgj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmqpmcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyevzuy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbpetiy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mhibrbgj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cldsraiu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bvigwyrj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkbrfzu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdxnfcf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tswpmjcd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gduhpgfi.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2phtqwukl.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgqjyqi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbbqgkc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mebdzcun.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mlccnbvb.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2muvwkemi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sugxibim.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kltqwnoh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pgghirkb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgbhqdk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqnpjet.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjehjeh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmxaeel.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsbwujq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqtoyoa.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2osolbqrq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hbczhiqo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2saxsqosz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdzigux.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgvltlr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqnodzi.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcibehy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2untawdgj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsxnzpq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvhbrtb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhcoxbr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvupsdo.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpgeyzm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2oxktlypf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcpymgr.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyydotu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2swibaind.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2famqcffn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhjijaz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2tabhanel.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpriiuxc.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dsraipiy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnyinsk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iezqppgv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhlggyx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwnckwo.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2olgehltm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lryiprov.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2aggzvjrx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2jlygzrkt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkkzmqa.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpoupzh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qibeeudh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uohagctm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2becaequv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwrbynj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jibkrgxa.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2szqszcup.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dsskhrgh.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbqhkvd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlkeilb.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyrlagg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgdsdfi.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxikoby.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyivlmy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcdvuvm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtgjszt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2frvelpwe.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2gryxnfbf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2azunvobp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2phoiasrn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuxtghk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkbqczj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmdhiyj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ertcojop.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rrghtcmk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gudentzv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwkbgnu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gslhuvke.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhmufbi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcsaaob.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2omcuswsa.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxeswrl.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuxevyq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdimhabs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oohjewrn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqljzsqj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdqlyri.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2txrmtsae.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xevfbpww.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzklqin.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2abumqczp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxfzxci.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ponmvkqv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2lsswdttn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2etflzsgo.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esmaivfs.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tiivxnxs.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2efpjyovu.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqozxndo.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mplfdval.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jimzrumh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwwldke.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjdgdao.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzikqqay.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qzukpnvq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wplobrha.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqggciaq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eodmdryw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nsidmdqf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzgmwpp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wsivlkek.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmpcvku.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2camuoaji.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxhbrmi.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvwotra.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqszuklv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuzofxm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnotfhq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjihcwz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpdyadt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtujhaa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvkxgow.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeqahgq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2futenadw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnzmlmd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwgispu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnbnsms.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxpxzqf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gfelbnxq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmagbtx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kegjipjo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2modczkbi.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdveirq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kshmdwod.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2avowvdzk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qoacwojm.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnkwogo.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnvndzl.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdticpb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2zptyaqaw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfcapan.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvwsxxx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxduvxw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tluluolf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkuatjv.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrgwtdb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xwynblrh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2icbyxnzt.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2icgfgmgf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mtipzqto.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fyloxkez.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ygshcguj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjxiseu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ysarprdv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ynejaidf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fqboewdx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iioaufmi.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2iueogddk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tfebasma.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrzbghw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2yaicrtdg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoejgkc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2abyjoubu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfvinkz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2azljfgig.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2cspahrvy.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaprfpg.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hixslhrz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2alqvlajr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfwilya.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oacoxail.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsvhirt.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dugtcpeb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhndwfl.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjzuiyb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpbhnoz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxiotwq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2odwwfehm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rkemiqwz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgckmas.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvynxxu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcyryuc.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmqyjla.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzsuvyo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2iroqhprb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ppivpuyq.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgnbspa.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wohemfkf.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2yimskvda.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjzpcfv.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tkevxsku.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2izgbxwqt.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvunowl.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzyzwbx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oqziznfg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jybkvcwf.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ehblzqvv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxflsidg.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kpljmtmw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2arpeipjv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2npmlhrfx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqybmfl.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjyfurm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtqfhgg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkgegys.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2azmufrdv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnnedql.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ppljrosj.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjizmpe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2klqmbnmv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eunesxqm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2vixjzlds.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ykugfxgi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgeljbn.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xsatatgh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uwitcyfo.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmmxgot.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlbbpxj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxoftvg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2njisjnwt.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yuudfdfe.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2scfipgpa.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgygzcw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2efbloftq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyigowh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpszebxx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmosymck.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvckaqi.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qqavhqkw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2eonfweth.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2vaozdhfe.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2inskgbag.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2znjyfasv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnhbtnz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuvkmnr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxtorov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2idffeiqd.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ssstoyhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyushph.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2eaahjafw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqktahs.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zoacexdr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ijldmiea.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrldxma.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpqokqh.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgsahdu.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkozoiu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyfmdrn.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xbldfnnd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzxbyjn.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcliqhf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjxynee.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2edxgqwum.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbtnpxg.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ebybffyp.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nayzdkce.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjfhdii.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgpsyju.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2haehxmou.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeaedrq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnbaxan.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2afvurkrd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sdstsjju.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnqtgps.html


<!-- 参考信息 -->