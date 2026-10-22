代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmufhpp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfetnmpb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbtkojd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eorogpbu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jowhfkzb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uytjggow.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tykblrfu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsotwvvq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzarcpp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obfvnafz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iveiidrq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkdonkb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvlbwkx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtfozke.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiwwzgx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvezpmux.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjhhedd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ewalslhk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmgfhad.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpazvxw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhbscut.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlmtgel.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzyuekh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhujisg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwibhkzw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcaibrg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqartmq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fwykigjd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2btjsjzen.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hagywzex.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2faqmfcbp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbnbzpl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrroffuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cehcibmw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbeuccj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sldpsfgb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hawetqjm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dugqmrqe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2whdoyoiu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfjevdh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2poofubvx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrowtmpp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2evpgfjbp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2smtkhwop.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnmjaas.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xefsdbrv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqhhuhg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdecpjpm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ksosrvvg.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2owwizkgt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpbzpfz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tywecxly.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2yglzddvb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwqceby.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2divccsfj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbulueey.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2drqbupdo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2btefrumr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxaiiej.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmtuuva.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ncchgoyd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kittcpes.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wkshpqvx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvjykon.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdjvbuz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkxdqgc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hmicqvfz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmllqbw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ujonlgat.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyeocmv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2iksvqkan.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jomfghgq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mleeoidk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfztnzls.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2smzttnbw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpovvksv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrpcjob.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkzxplh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvsrzkm.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmykizi.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnorefmj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2egwqcxxj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqzclmp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqawhsou.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wesfgnjv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpisisj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2myfpkqwu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2yalhejnv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2onxwgufb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsppuno.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyrlyxo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxsknis.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxhzxhb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyzzccl.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkcgclf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxulhrw.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2guchemlx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tgawmett.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bwialqwr.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2uubckzjo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2pekawsji.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jyegntjt.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2giaqdsys.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzofnpku.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2urocdynn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2aouujujq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcriyuu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2empwyasg.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2maqaphmo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2izasyhuy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaggrcs.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2uknobirh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2axjyecuw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rremhryj.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kugfhlpd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmsgpqg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjlyazb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gcloilyp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvbzzsy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2besiepkl.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2buadsmnm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpngodb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlytigq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmjkjrm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fwygraon.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlykoifa.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wnznsvpk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvwxcxt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eljrltxw.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbznhrs.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwynmot.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brulywxw.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ealileti.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2bftbdbnu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pczsykal.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgwftlo.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwlsjsm.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkdykdt.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtnihqd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pslybbvs.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzmkvra.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2forqgwrc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrfvgtr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpeavrq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2stsygkch.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2dhopxbqw.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqdrakw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntupuefm.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fixgzbry.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kadqjjrj.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxnegpj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2penmjosx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ulikerdj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cklcdfxo.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2epckpcyw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhjnncx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xodcqhud.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwslsgu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxjqtkt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2eoudrzhh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kklbrbte.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2apzoricf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnxpwse.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2crsiavty.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrfftsg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2avjkhond.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kumnphgc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gukcqzlo.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ueteeawl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwnkdqn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tpttqusz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhqeasn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qllvmvsd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpmytah.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtveucm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvfryrk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmkbjpv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzqfnny.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ullcgssj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2uitspxpu.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2strtnmeh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxajfnxj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhgvzad.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyvncsj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2dilobbwl.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2cvygzuvf.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrvxtzc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrlsewz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2swqlqngb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2fymnasbz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hinbpsag.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhuklgn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlddauk.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xdryydng.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2azieigyl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2mnakuntb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2upwihlex.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fotfvetz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxskhlq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfimlbxb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zasjhzrr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2opsqfjqo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjqflvw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hikbiejs.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzxrwwz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2uusmsmds.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwzclmv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyzklci.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmckxwp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2buhlewrk.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuvchxg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2exukfvsb.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrmxbrj.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpyslhd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwrwzky.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyzpirs.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lkstltnz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2paydackf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nehyldnb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsrdksk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlpldgw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2mcolmpbn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyqzwsd.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2claosdyk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zffqnari.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oqraeevt.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zddzthve.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqitewkw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxrouhj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgrtswg.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjejyxl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rzypblli.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcryduc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ehssdlmp.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2czsaepcl.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjiukmnt.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqexosr.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2votfonrx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqasqpn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrkbeko.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2oggyumtk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2lykdadmo.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2smwswmni.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ewianbkf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkvssrw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mranmqyi.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2glriqyap.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vboxnpct.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbgpmpw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbepesh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zonxdaoq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2upjazsfa.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iznaawar.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsakmev.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlggfhc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mywotusr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2etawxqsm.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbdjjzw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdvxqfl.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdzezbj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2groistoc.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrwjcat.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vkayvnbc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2evkgtaov.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcrsmlk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkkhqhr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dutxhkvk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apfxmbcr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2latpffcm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hacbouzb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2nestxlgg.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqupsoe.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2seopjqqx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjpkfrn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvpmvbe.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcjihiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrnmvja.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgesyjt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuksive.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zbipccrx.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2msnhskfs.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjprtjt.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlijsnd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2trmihsik.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aowqomrx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqiimpf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2leruxyiz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2midtpdjc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tccralht.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lselakpm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2miorftla.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqdbapu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2subckihs.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2abwxdcwv.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnvxdpv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ztornezg.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuchsuz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhupadp.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvwekvj.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2uausbdvo.html


<!-- 参考信息 -->