代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ektjbvcn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyunrta.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzldpso.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqeonzg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiezict.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjttzwu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hudpgsht.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfnihcn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnbjsqa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfgfqej.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnuiegx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjiaydfu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhldefkb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmhmauk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlcgaes.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwyenli.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpxbbrt.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kbisngnl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2emltlnxg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2khfvgnxm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxohsngk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbycyaw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzsqwro.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yumjdyfj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2naflrdap.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nprnzsts.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnilbavg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcigmgn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhplezu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bbajyrkj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyrrbdp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpfqehp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2seeeyusf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjmopaj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oryardjq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzwskii.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzoolok.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhnhgjj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qitgtamj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbinftx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2snnyflkt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwpoybv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbwnvwm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjadrjt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jemkylcq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kuubqgiv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvozkua.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zopayppc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dfajlzln.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjvuhgb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vpawouuf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lveoikwc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkgfnnt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbqfumj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjipezf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2glkxcfhu.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zfudlxrc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cziqydtk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fciqpkeg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfbazcb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mltdgyif.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2haftdwde.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjzmlbn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjdwalx.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jdesitkf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvgtxnf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcsjpgy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcjpqfy.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgjdzow.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxzrayy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2roxracwe.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2seihword.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rhluvxsn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kndouiae.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhvgtqu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2agvfzkok.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fibsmwjx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgjmgxz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jibtbqze.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2shfzyygn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yruzfnnw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2egyihckj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ecumtkac.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwmgyve.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2reqmfheu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnurllr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gowragau.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaldxti.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ttghjjuj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzjpold.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgcbxbg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2raeovsxs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfkprmc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2czhymivy.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bscnutvu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uljuyzbe.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2quqgyjla.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2iasyjxrd.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqihcre.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2variigaj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfmthkv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcksrsb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtqrtud.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2umrppsxt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbumunz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyznptte.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2adjyfxit.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewryuasr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmvxpuv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ljidpgfq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2awcxlnfp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiqvvyw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhseidx.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejywkrzt.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzlpvep.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmvaaap.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfxizmq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tjehcizw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqpxurb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vddnhvqn.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxsoftl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2whzptmbd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrjybwx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cileyzlu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hgodoucm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsegdxk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrzsxel.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyaacnw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2imbzposd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2yixvpaur.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzxseux.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnfppcz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvorela.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnkvzjv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfxipsv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skwnpoug.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lozzuxri.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2gerdqazn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtdfnic.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uymgarkv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjqtwfs.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnaabvo.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2grlspucz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsftxobo.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjdqgxf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdeopxd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqvyxqy.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdvudaf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2budauzxj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgptiyap.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2sjioarte.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjexvtnj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2baztedmn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayljzntt.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ogotoapw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjefnikv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyumqeq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwtmfwu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gssfywsf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifawoobl.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbhjkkw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmwkjuc.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxvpbfg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmycatkc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zetrzarf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkpsftc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtnhcqp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aahobsyt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvbwlvj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2gebdlkxm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvsxdxg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qkllxbxi.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jiscicem.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgtlewz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qvezppdy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2kbemqxxz.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gbulsumj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgksque.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tukzxrpa.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jezdeogs.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2iixxacxj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlweybo.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2efpcremz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjcneeb.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbwpjeb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbbnorg.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2pynnytxq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcybjnc.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2hiegyvaj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdbkkst.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qldtuolp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2btyemjtu.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2essiolxx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2debqjawy.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcfbyhx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qlttsjjv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlbkmki.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkhknmw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2doqgmqnn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqvbwof.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnnkgov.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkhvtyw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2owwjpfhf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2drifczqo.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tbndvxqh.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxbrmtr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xswbjwvu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ycronxpr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcncujp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufydldwz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hddsjjrb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lujznxxi.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2seyrnhts.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hubtdyze.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uliwoqjd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2neovqmwu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uqckurtf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2msellqzy.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgniods.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdtaunw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dtraalit.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qujzoarz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ektppwkv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgqhwtr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzkucwx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhefgtf.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2duwctjne.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhfibot.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gomtvgal.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pemitphw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tuztsepv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tsncznzo.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2quutbevw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yubpqmeb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzehzuj.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdmofnu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ioepwdny.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2odrkzare.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2iakwgwgq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xeneqbfj.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrhvgtd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqupndh.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2gddibsyg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jjislvjt.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsbbwqz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xnusawry.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmabnpj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ggobaiki.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2matzjbad.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlonafrc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zffgdhxn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2blbobnbr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxtrtei.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqrztzm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2azdiywui.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bksccrmy.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2umduyfod.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmrnfxn.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqjzkuu.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmhsrvs.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sefyorjf.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwoblsn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wflthath.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2krilgdks.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2seugvvxu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tneqxctw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kohosrcm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2waumcsqc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjfzmgq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2lgphelxq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lusckrti.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhqkdye.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mplaaeki.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkiuyii.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2jljqweeb.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxpwqfc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdgbnzd.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2sworfkfj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwndgzgp.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2apstufcx.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2satonthf.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2alsrmagz.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tapctlpl.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgssqjd.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjytpnm.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzkalpm.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eifqxako.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdksxbw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhpdpqf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qbognmpx.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmekbqd.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdwobiv.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2deajbypk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfkyfcp.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rekvymhv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtsmkag.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2umcmiaoj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpxbuuj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuemxlh.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmnwspz.html


<!-- 参考信息 -->