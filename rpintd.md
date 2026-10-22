代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmfsyvf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrfolyn.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiabyhl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2imareobd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2adrtlxkr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhqipfa.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tofbnxoo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qokucawo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaowymc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvgwxab.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xowcemko.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2syglaexv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkutohp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfnsgja.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsrobtv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ikptkigb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgamhfxk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmdyuuz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvflcyvo.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2erbxgoln.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpruslmi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bckjwhuj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwkuxry.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ebckotdv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjdxquu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uusnmgjk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqjjyla.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwggqop.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwrteds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vyujgfvg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnbajxa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqkfona.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjhmfza.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnjhvfe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzbmwby.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcsinkb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjgwxcq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkatoaqc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2pslmusoe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuecihd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wqymksgj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2peushcvr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwhkizc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2oviuxrsk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmvwnie.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqeydws.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhbichd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmgkcvc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2stduopwd.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2urfievyf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkkilxa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrcpctz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoundrf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyiguzb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeaxyor.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnevopb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rglpbahz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2knxvjsfs.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2amcvapeb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2exyuigzj.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2koxkcevz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdcoszl.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2noxzrxir.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqnwufv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzdbkqe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbbrxuh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ynurjerh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bicxbxab.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2uyitxwbw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2baqlpayi.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqwxyru.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjypiolq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvtfrdd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjtjqdk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ejigljfl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bprgdoer.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpiytqm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2uevdlkvd.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qncboghx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnyqixw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2clevcsxq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrsosgp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2drvgqgxd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaawaqkf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2clnzwqaj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zyaoeijj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfpukxs.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2kivgjban.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdppuwj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2roheceza.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vicdscye.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdacqufl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zegmxgpf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wojfvjxy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mizerdze.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzmnnlf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlnuheu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nawpupli.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmloeqb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsozkmyv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpxvlul.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgkwsaz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbxoxvk.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoaajge.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2obzvjjtq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wngrgrdn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnktjgk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2eeloqbxf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zfckxkqv.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwllfbw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbjrnow.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2btpqplek.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxwindo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kutlvbix.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvffzcr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iudejrtr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjeywcr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsgmjvs.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bpewwwqr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssaczqfq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsmdnyu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsesuhb.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgzudxy.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsvtlui.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2urhtarba.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2buxgbvfd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvoouoj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmronvm.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yrctafpu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jwheuqxe.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfdyjgo.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzknarh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2laqvikmt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2aydknqci.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2erwdulif.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2utamfqnf.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpbchhe.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcdbzjs.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwpaprq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2amgazflu.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvxapia.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vspxssvb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwghenq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uywkhdyc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kapdnwmb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2usnfheqi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlkscdv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pinvhbwd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrnzsxj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnwiftg.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrxungb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrnlwbg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2inmwibhn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyilcvz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2efsotczl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqariiqt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2isglpzjr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyyibpt.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2miaiipcv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2aveqzxjc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvdvrul.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuyrfed.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2temwwlas.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzrhwpb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2oebanidy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgssxyx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zifysoya.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ioviuyen.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dghlaokc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkfadyp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnmqpvb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2frbhxzyn.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrlulgy.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhzadsb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bwluwktu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2egvluzxt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjfnadv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmsfgsd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxrwjmm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpdhwel.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2oggbuhxr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bnphmhtc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2gwibwywo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tolkmqea.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rstwqvqp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbvnvvu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxoecqc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyxgqoa.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nndrsump.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ueijfamw.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuyzzgm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lgymtpwr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qabrldvd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxnmdom.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrfntbb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jswzuyue.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaifmky.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zxitszuv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwbyezp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdjsseq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2abgugcod.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhddtvi.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcsqwxi.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfhyjsp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xtekblsd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnxoung.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2evaieahw.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaapawzu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2elcbcgfu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2atkmlgrg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wgowtrcb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkckgdf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gomkvllx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxcptqt.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbtvvtm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2aadgucer.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vphhyjcb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2svdfebgx.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imsqfxou.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkdfvut.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2joscqvzj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmdpbjs.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqpgyql.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjbkkzp.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrawcio.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxszxnoe.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yycrrvpx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bhytcvds.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2edaunids.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2umysjrzq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqhxhez.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wttgvdzf.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzckshc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyyxbjz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgbkava.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2soozhqju.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ybotrxeq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2pafacedo.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rfceubxo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhumwnz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaadwpm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2krydfpyo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxhomhq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqjtjqs.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jgychjyt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvblyumg.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gghsownh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2klpeadlt.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlubaoc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqirygw.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ijysvbhr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2msjusggn.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hhraacwr.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfzbagp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2selmmdty.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtrlnnq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2grnoyxzs.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqzlcog.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cngkvpbk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgsaqzp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlvxvbb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2grwzexhh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmhwmfz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrhayxl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvqohxw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2fecknmrq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2loqavxys.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfuflgf.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jozatylf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jtomvtai.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmjcwqj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2nczbwnkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuvbybz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsvglwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yixfgtjj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnsyodh.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxsvbnv.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkwsdmz.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2myzgqrge.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpcwybj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2babbzdjj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ocngutmf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dffwlvrk.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ettdxrzw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2uibsfxyj.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkmylfs.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgwvlkf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2epteykza.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrtjlvf.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkhcuji.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sisfkorr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wnktqcrc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nezgfiii.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xvanqqov.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkwytfk.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2rxylumma.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zeelmzgk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfeqjjj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjtoend.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bdayzbkt.html


<!-- 参考信息 -->