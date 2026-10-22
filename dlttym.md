代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pacclegd.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alpaseio.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbzhdkg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpimhysf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wscgdkjn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jymgulil.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zojkeqli.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2onbmtjfs.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcrfpdy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwimhpe.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjgsfin.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwevamrn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euxaqzjf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxpsjyn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwikfltw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhypfowg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrkjjhy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sinvhgrg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvndguf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xruwmqsz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfuwgzu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kxujjomu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeiybpev.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jnigrmiz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2siuotfpr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2btuzvufu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjxrelo.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhzconf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kmaebpby.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2almmfdqw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnqwlws.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbgacev.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpdcman.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhjaqec.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhxknom.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdprmsc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xtulhrhl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzusdzl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvlwhdp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bgibidsr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlssdhn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhrcvma.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdtgetb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tntwqyoa.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhfknwi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2twddibut.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2atvkuvfr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nckpiwwv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2omnkhrlq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrsulnk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eepprgmr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2geflvmbn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvdhegh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvicclto.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pitdxdjo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zrloqhxb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2isvafphe.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kilsjltk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2koamwhvu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2htbabwrh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxiqdql.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnzgfot.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yochenup.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ginpaqeq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtiwajj.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuvdfzm.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlgjtou.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkxgwyc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eetuwada.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2itvwtgrh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lryqiycg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hktqubzq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwvlxjv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwpmlug.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xjckbrph.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lentguth.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnzgdoh.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxlfyxo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwhgyrz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cgimaqou.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zikssipx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgetopj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2syvrtlut.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2trqkcmaw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlbxuts.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmxfgge.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlpbhjw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2sykzwctw.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vvggtlob.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqksmfy.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2grtcblfy.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2acpsmspo.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2eagsqrap.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdbzldk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhwoqmd.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmxcnrd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2povxhbim.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2roukvnxc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrsmclk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvizsqr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2aidlgvhv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhxoeel.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyfqzeh.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmtgdna.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtpckxl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbezgsbz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrtwxga.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvqrkyf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwtrwma.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qtchamcz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjqlozu.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2oabfclwi.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzwfsti.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeqmnun.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqsrmcq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiyhagb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2baqexwqj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2adpafyjx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2oredbedr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrhcgtf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlozmlq.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeytizg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iayxhvrs.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaxbxcs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2imccilnv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbsbsod.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjcpqxx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkgaexh.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjvuxzs.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gxquqicx.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmbrqfq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxfskpw.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbokeun.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2osefpvku.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzerjvp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wafuovjh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2iioelzpj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2yznsqvlt.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnygiasy.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdyqnza.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2pchnibng.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2blgbxqln.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkwufiz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgarscmz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eriwakeh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wchkuvvk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzovvhbh.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdesuana.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyiqdzd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oibqgghc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qvckptxo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhbqtcp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfcxfgr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdlgrpt.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2aozpedja.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvekqpz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xhevsytx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjwxdek.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2asfrtawk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzeqjta.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2muxwmfuc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2icxbtgrr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2phrwcivv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rmszuekt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vidbjpfh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbyzzea.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdlqqoo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vntndzhj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2clrzoaeq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wweoqfbv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjsfenw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwolapx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2klkcylpd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvfnuug.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtdirni.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pitnupio.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwkrssv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2guxscvsa.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rabdgwwi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwjytfr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrsrtco.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkrsfkz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tnicllqs.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajennzcw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2gswhkuay.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xnycdeye.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxlbnfn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2dygjdrvu.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvlenxk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2pegrzotm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbytvkj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcgyeze.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ijarsvhp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrulids.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2pccccyel.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ksigzehs.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqbayaj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnnaeln.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tyukodea.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnfdfpa.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnyxvns.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjkgaed.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2unwfkrxe.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmoutce.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxvbfwi.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqitehm.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wbooxhqy.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2opguvmkp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hnygqmqb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmdlsbg.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oelezosx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmuofbz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmyfcev.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgatvxi.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fkavherp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhhpakx.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxijhvl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2nbecmqjx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsfaejw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrcwxaj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcipgas.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fdupdfpv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkholph.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmgvdyo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wchsxvnm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gingiblt.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kordktej.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2athqngdu.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2swvueoiq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuqhvqj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nzujthnw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcmycdt.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dhemrwyx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zibsxxrf.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcdzozq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2opjoxube.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgvgagd.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsbnijs.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2afoogzgf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2cixdpdvr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvhjksa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfphpmxb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pahxilho.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqlobag.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2sugigdhk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqtwxza.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsvpobf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyxiwut.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbdxgta.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdykqsg.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2otzwdadm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rqorivuy.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gikauima.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqiqhgu.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhyjgfj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2eiselhfz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kygsvvnk.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2helimgir.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgouycm.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytesujui.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaqhuma.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eilfugcc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtydpwv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxzfsiz.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2phmdtofy.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2puyhdkoe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2krjbvdxf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtwodzt.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoxlths.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ottwvbnk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yubercuk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2syffxvcz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsxedil.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcztqea.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkvzops.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnncikl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyhdmjp.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vytqsitx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbcfljs.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfjkhuq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2omkphgly.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xitxnbdy.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2flzcwzrg.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nperbqvp.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2figwraew.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rkohkucb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2phpsdgsm.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpawomc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzzdbok.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nksigahi.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2armpbxdr.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwgpacg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rspinumn.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiionum.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2onutssvp.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zexssfdp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2khbqhqaj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcmqusl.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyfbqas.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2prglxowf.html


<!-- 参考信息 -->