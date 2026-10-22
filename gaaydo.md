代发 wailian999

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2osnshvvd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nncvwnwb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bedqncoa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsccwjla.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoykzky.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdhzphp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjynrcz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqvqfct.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtnicvs.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igzyhrsq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoyoofx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kapcqedo.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xraomibu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2voftewtk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqerxjd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdnuyxb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2irblqlhi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avugbyhi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbdirpu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyexizo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiccbarq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvbklee.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2plwbzrju.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bvulgqkm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bibwytly.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbphosm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvdxwvk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jnphklkq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzflniqv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kmznsvzd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhziqakj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wgruohol.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2piuogcas.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2needslxw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bddtbelg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwkmzkj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqtztfw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pecicykb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyxubyf.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbnmcss.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vttznvqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdqrycb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnafseoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wczcgrhg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzacire.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vcigkyqp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrtekkm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sztrwmqg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkwyfbb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqabtgcm.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2eryzhupr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jctnsdyl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2abwtusqy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcdlkcf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uaotmkdf.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiklctw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfkomlq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrwlyyk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iacrwqhb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgkyqbv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gkektjsh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kprrzhby.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcgcnmj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hshrrxqr.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhxouaj.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cevlbpfc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdoaejo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2epaczrse.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyxhsrj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2odycxgmt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfxryqe.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxrfmmp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wizgyjkl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2puubqyal.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qenljiry.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lutfqbfx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mykkykvu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzmggdt.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zbttsyuc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjncklv.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cuovcrax.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2flbzrbsk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrehawa.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmvyckg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqujszy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2rttteuaf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qnslnlwm.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrvwpfn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfurxmkk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2oknaaaxp.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ipoesquc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeemmvsz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2heygsuzp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zveztcxh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rssyzxxr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgewjoyc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2uwarwtbc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2djcggjev.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cietquic.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bcutpjlj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxygrxm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dqucaifn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2swdjgwvc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdyrcet.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgavjtn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2azyrxytk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iafumyka.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mdihvnmj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qafluxqa.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdkzgzv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ouofjvof.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnjdgpf.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzabsvkc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbuxppm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rkimdsbp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbifxpo.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdmbeeu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zgweaoha.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkcaskq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jaigcpii.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvswwny.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgtlrhp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlkcftf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzaxhxa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sbucsile.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvswnbb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mncmuyjw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmglfxk.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sjihlrgm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwatnzj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kyznvess.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjosqif.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwbmqnk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czbgztif.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zalkjwtg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxkdcpo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aenyijrp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2czwyacxn.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mnviyhrr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dscwbpee.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwkzmcp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqiycrw.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvxzdkq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zilcjozp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvuqqfz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wadqglbx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iveksntv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2omjdezgr.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwxikaz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjitdgv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtiufil.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2oymmpedv.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2onngakfn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmekfoj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqgutyl.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjtfwfs.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2baralkxt.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqplxege.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2swhaavjm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhinhqq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qzutsihi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxheblaz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqdqiug.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrftykhe.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qeabhakm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojddnvxb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ciytdumw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzrxptt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2arrqgwhs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjkyeep.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2evxgemjl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lscyvvyw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2oridkqid.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvnezzq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzhrzzi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqteapl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrxlbma.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2utxtinno.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nuazjiak.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fiztffuo.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoffkxn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcpdzgk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lixnejef.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rugmpjxs.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wagcmxpi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvfsbcb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pknthsqw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vayfibdz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2aefmsaby.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrmeoya.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xexksiop.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2witwdtkw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wujwezgb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeoqrqq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2aswafdji.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjucsnpb.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2hqggqqft.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2cfoonffx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xbelvabu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkpnvoz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfcjtyg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2llafdklb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvkmyao.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2soxkyskf.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkrphga.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qlozltrg.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2otlbwvoe.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cksdyhbl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgktfrw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhdlman.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpsdvtt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xptmpeij.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmftcse.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hqftzkbi.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2znzuywmh.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2jyysmzog.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2purzkovv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiwdhjp.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkgfblo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxzfwbv.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqecbry.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qquyfeeb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kusbnncd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaofovwa.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2soxwklsp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qygoprpc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmltrfs.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yifhxajj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bosspfph.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmmyddw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxdtvlm.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kczothgv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2gvenrswb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuzosmt.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nmowvkdo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2egmdmtvl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyojbdt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tifvaviu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2msgktlpt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rqiqocvh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgexycj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyrnbsq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcdvgti.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzfzofi.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fcszgrzk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdjpafj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hsguxbdn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhidjoir.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuwdnhe.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2lllfmduv.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qatbqosu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2scdeiliv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjqteij.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcfbvzj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hihhhpkl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2buseceav.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2uryxptdd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlorfzuw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yixjkyfv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgcgfsb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnkfdxg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcjzdug.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2kbludilt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgdvekp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2slkwufqj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tehnrsdj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxsyzbx.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpprhzvj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mlagmdvg.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfxvwba.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2stjcvmyy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiywfld.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lcizlkpy.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2impzkcki.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzwkvqc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyqvdnv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfdcnqp.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbsarep.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbqmosj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2yygujdrj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtnzzol.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbxgfbi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmphotsv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2mygreyyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knvtmazf.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2guiafvmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfukrvzs.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxiezpc.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2luhqzmxz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2egykwjsf.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rkouvfil.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfyeqoe.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyjifqa.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzfmvkh.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ytojncml.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bulrqvdg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gunvqmgw.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcrbcje.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2awystltw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2zcolylhq.html


<!-- 参考信息 -->