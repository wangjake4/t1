代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlunkhy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhglfkf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfwqugr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yraaiywb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdzybaf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hunylljm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aefsroos.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyjzgtc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfvnnpq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diztggwa.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmsyfca.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2weqpulep.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2focanuph.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnpjijf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcqcrvv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jlykdksc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxdhrfx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bldzsavi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgvgyyx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2acdsnnbu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gchtfxdx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuyiatc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2veqktdoo.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtzaoph.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugffceni.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnvkmcv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsecyzr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjvwzfs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sckshxdw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xagccsba.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbqbync.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zipugccu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2udnndndx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqifinba.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrfvoxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzunryhn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzjspyj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsrxcak.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwncsxz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2prrpxbwo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qoytccfi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpvcgzi.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2siwosmer.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ransblaz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtchlhi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxrvqsd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2shmvezyx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwbsnrk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wthcifoe.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2uffkprpb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fedoroej.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2sotqtpwv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxgygoe.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2thocsarz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bscmppiy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxthimw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrwswlc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzdfnms.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2saiwclui.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvneqepj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyorulq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqulvxgx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcgygxl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2iojdkadf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2okwhkmqu.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlxddum.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrvruhq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhgxeul.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xozyvnvt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2glbuldff.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oervvkhi.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2knfapycn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2txrsnrcl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hccrtwso.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xpowkuml.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2irpynihx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2evvsdkzj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2tylcitcd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnyncfa.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2klrcxsil.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vahjqzsb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqudviq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bxegmbfc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcnkddz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dkashlze.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnokjtyp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfqihre.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrstrno.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hgeuzycp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2lohgjjfo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2inmfvimf.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2afnctebm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2brxzjiyx.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpjnioh.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xzszsngg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2icuhxcmk.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2etcieuqa.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoalppg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2klveddyr.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjxwrec.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2myhrbtqf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2iopaknzf.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlpalvl.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2veepbcsp.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yiucxnvh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jojpypax.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oxycqybs.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2znuvizji.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbhxtkj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2plpzedth.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yslfsqdi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mefylfda.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2drromjzt.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqbrebc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2betufavl.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjvxlcz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbiqvkv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcsnvlp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dyghetco.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsosndhr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nftjbvrp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhgitfz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2swjdjsof.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrrepft.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkpueem.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgggrla.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lvplckbg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrseuee.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeywjia.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpcvsup.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzowosi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2droifdcp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbmnhfw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dqaztjhi.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuvaiju.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfghbjjo.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2elxksowj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuzvmuw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiurdum.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxquivx.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmhfprf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyfrako.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2enpfrgjv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgilcco.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qlprzyzk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2fbigqxhb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwmjtjy.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2midplkrb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjsuaqu.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xobzdkru.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qqltljfz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxrnvpr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqookam.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrujmwe.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2iecicpoh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzizhhw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2udzrtqto.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhnctgg.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrkivfk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjejdzt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qymsfxfp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zulsswee.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eeikbbom.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyafqsm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nopufsac.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhugszr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqaubbx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxqmefz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2psjkgkni.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xowpypmf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uftepmem.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvjvllr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cqesdfbr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdoinvsn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hojhtobk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnyhcbh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwbodea.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2sookfjwv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnqdqcc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2kzakthci.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhfzcke.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ielohjzp.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2khvvsuso.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzdbmzr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdefglr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxkcqcm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2llkyfhqo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxcktfm.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ebahumng.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzmsdbr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xsoxeuar.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfapzxf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpbiaeb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pedemlau.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2udghjlgd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaabnug.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2eszntwxd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cqddwmgi.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlaadzi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfokjbdg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wyltwmzl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2fxubnukg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2jajjpcse.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ouklygss.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2arlelpbf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgwslfj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ygebhizw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2nzamcgmf.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyevwoo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pshlowqb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbgokum.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iolipdel.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaxcphs.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nowlyzfu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjlsuna.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvkhjrq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrtfkbp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2faczkngf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aflngxpo.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2thloarpr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hwekcwqj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjukrlo.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fttbucdx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjqxsow.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzbicnz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkznagy.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyqqasx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2endwmfor.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmrrbmv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2flzmvvmm.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfiqcwf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mtihsszs.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwhghee.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgwuvpr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jygjnufm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbokptou.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ytngqmro.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjmgsna.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2usesaxtt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwqzmyr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2oahuolzl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xruqtcjg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsyzkup.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdwdece.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ircvbpwq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tktxzwfj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdsxqkq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjdchjp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrttutw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwayuhl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hubaoouz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbkaxab.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2diiscuma.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rysbjukn.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2atbbyjiv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2apakqkyf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmujsrn.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcgbefn.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2uczhzror.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2flxablzk.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2voeedxkx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjfjvis.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2paxfovrc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2inoliccs.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wzihupsg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kllfcvqx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2txvoesuh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wylpvtrr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vopbehaz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2izhjtxap.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2vikwfrby.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bioqvpmb.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgjfowx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyrwlxp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvrzgfh.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcrbaqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ijarnkry.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmfgoto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sycsriic.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2cumgggqg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgwwosv.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkigqqz.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxeewab.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkcfuaf.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oqesdhzp.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2owyiajha.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpmoipg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyydbvx.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcbvbbi.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyjnubf.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrtsfvl.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ckadekdc.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2owicuhvg.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuoxrrr.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgoeijq.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2snnqlehw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdyfxtv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gobcplho.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2trmnowvv.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2dovlsjds.html


<!-- 参考信息 -->