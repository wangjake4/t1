代发 wailian999

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogimxozy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqqztnj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrlvoeg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufogddmq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcffnxvw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzjhqxo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkwdnpz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jpngklji.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxrorxo.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ldurdhso.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2upnzrxjj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwzfusi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aakmuhtc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2htgdudoa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxmthac.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nthpjgwx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2aftpbmmu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbrjwua.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuroake.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqvxgsq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfheqpf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhwawyr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzcivxp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wureklyc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pstqbmxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzmenkx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyfqize.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2weeutvil.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jlizkjkv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2brjaebwv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cpupzzcb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2haognqsg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwipuva.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kccudwty.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2itbukdiy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2limuadlm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2buqnorav.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2muohsvci.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsazhfv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2faojtspn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqmkbdc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjxdczu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxfvips.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtkibml.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcfvycv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwbdlyh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zkircbvp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmduidl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pghouaxu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpjtluk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2krrkbefr.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2utxelagp.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwyjryo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhswjmu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yswazmca.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfwsxzk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwgrfnj.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbhbftg.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpfsjti.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2izfvxhpd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2otncngpw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxzzrem.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nchlcyhg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2alhrtgae.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kacegmcp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jljxzntw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lscfwaqd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2iizuypnt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2etafyfrd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2huajxkji.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2asdovuue.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zsftfiqn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxulnpu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkctnzw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgpxcla.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukebldlf.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbcuspu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhktyvy.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ptslmvwt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2uppdmjct.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zehnetti.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2uowexafc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2irjclfpq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2natqsbbu.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zgavfipd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zblvklif.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2crrvtqli.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2apkemkpy.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwecfkn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cehgmggr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxzksrn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzfdgeo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmdeldk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zggsujyk.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzryuli.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pueqojtu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2taihcyux.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zytvqgts.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wskswhky.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlyzkot.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgtrelq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2btbbwbvz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2odielrwp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2upwatqcp.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lwngghpk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvzihvl.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2idxizbru.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioojsihm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nujkxnhm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rlggyune.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqedqpz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzxblyl.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmhmjvr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qihwfyyn.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwclsii.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2striihjg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2libjapam.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvyhukl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2trfgrgec.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2jfltannh.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2itxbmsyr.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2auriaepb.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgpzlux.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlggsco.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cculrwue.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2eoucbbrq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdnubwp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrgwppf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyfbkhj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcltmemt.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2errujhtk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnrhdjj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vufviqzj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2opctapjw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmgevmd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgpfcoe.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtmwjfi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2guotjwsu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bskwokvz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtxnulb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhsxylm.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfotsmlk.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2syvxsfng.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oieostsm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eewoqmvx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2perdqrtt.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjrzvyd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpeuogr.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrkffqv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2luthhqqq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ujicbtds.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzsmoge.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxjidry.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2imgruevx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqbiefh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsjxqkj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqkngdy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2trphkctk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhidakd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tarivmlh.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvtcagy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyvjfyj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kddqmwol.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuoxaam.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2japcdtrz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgybyjiu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nampjfcw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2heabqqbk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqmyvav.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlepmpyk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ovptsriv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2osinikxw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2krfmebrx.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlpptzd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpvefhh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpylfuj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2cuishujv.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnshtwp.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkqeifn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbecuzoq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzrbykw.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hsektztj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfeidhr.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwivxmn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2sipndvet.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2blhnwloy.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jqytdist.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2tcheabdx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbuitqm.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jiauvhgo.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2peszfrnp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbiitokv.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2icsflzgn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjsfrkg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ulijhiwy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2retphajf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2usfgzidc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2quhccejb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkcmmqk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhsegpn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dumvzrrk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2spcvirra.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2erkcjjjk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaksjmxk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxaqbyj.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxocvuk.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhpuafj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mupwebvk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2futdkvdy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2btkymvri.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bquwjzjj.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgzkdnn.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jusrwwzi.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2czuhmwdz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2syoqnmwx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2edrgipdt.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2nddrobfq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uvishogi.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oyakkequ.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuafafng.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bxphzalb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tisgldph.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mojyvwol.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2emvsvsky.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuozvvt.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2memcplky.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgsamru.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgscrvrm.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgepeii.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2eozftnie.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrwqrwb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkecrmz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsyhpjb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrfzfyd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyoxrgm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdkklob.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmwnpdz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ygydxygz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bruqkbjg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjltdxx.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2viqnuzxq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaqxjmu.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqcjnoh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gkroazbh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfvjwaj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wopaymmi.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rothnhib.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wiljtcea.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfwcodz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wksuaifi.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvmlvly.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmspwdlf.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2waypbmjj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqomqnpj.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uoraahco.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgywdbos.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cobbrzql.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdmiaup.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvsgwwa.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhpmtwz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2axsqxjfb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdklcni.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2tbutijqk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xinhxltz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2zltcccaf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tssfirfd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkqlzdk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bxblwwfd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nscjrwah.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xflvcdfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpowmtbl.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvtuxvy.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvnxiqw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2atcijmxr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hpizxcar.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zvquzycm.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fouiypqo.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2efjsqiom.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxkxgzj.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xshaslbb.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxmfske.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxihqwi.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyoiyfn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2klewaliq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2oahzaszu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyrwgve.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjntcdr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pyketyjx.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2krpwbptv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zubimjqw.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgourxv.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwzlylz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuusgnz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uwctfnys.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtjvkpt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qlapcrgr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2iesxtxij.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fsojidjd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdcedyy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2psofvbac.html


<!-- 参考信息 -->