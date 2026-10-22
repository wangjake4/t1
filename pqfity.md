代发 wailian999

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkpnjtw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fkikatth.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpzjaev.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dndumhdv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsbmwzq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzlmmsx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbsohpr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwgnjif.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuwnnhn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbcupzo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpwvzux.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xytvhcys.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdidpvb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwsbpqj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcvxqhs.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2iglbtnrt.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaftwzh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhfrmwq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpsvxgp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvkykfg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icupdvez.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyrcbhl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xktrphtg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aufwgbrf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgonsep.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yysjuilw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvroecgi.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcgklmi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogktmmtq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aijucdfn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeppwwkh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqqhzwb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvktrkj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2phirtaij.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2psbruagz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjrexti.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrmnpyh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrllgzj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sulqwadi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhjjybh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqsxcgf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnmtlco.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryifqtea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrkypfh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjycwvr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtlecez.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xxygiwyh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwqdmrx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dnovkysy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsgqftt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjndyzw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uahjewkg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nvskctyq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyigolr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrkwtkl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jukpykod.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqabxvoz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjkaajk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjclamu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2pyevwrhb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bftbiyqo.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2udttsuhh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iqywrwfh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dspabcqd.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vablrcha.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwvgfss.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nviwlwgh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnufmrd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2skivkdga.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdioswo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ypljcjsg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfovlhbs.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ttriupjd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvvrdtx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfbvdkc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkskctjh.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tprzkgjr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwychyea.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2poogrobd.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyagtqv.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2sevejcfl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2exhsylby.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnrdibz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjdnwim.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjumcpv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bgprsmcz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvscveb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnsuqbi.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwapmwvf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvbmksi.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsytnkk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2myzitrvf.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhfnadi.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqsqejz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkzrhvw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgnmemq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmguwpr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bfclooaa.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ailaklke.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2voshsymb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2snyctmvp.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fhexrmnp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oixbegge.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ricopiek.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2srblrbir.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pmathowx.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kkutpxtu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxhoecu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmbjirh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnpusfr.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqdnnxq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zegduvlm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwbfhzv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfudnmpy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tylbbcjz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgapwar.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cfupmwbd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2eukzcyyl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbaneed.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrwrdfk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zqywfsvv.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbityai.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2citqdion.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxrpfja.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdiyglg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfnkqdf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgpezne.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2slxkkmih.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qcimxqpz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlonrbuy.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ehecqktg.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2viyumuoh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hibpxdgw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqabzcu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yckzvctu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2bqromfbc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mbewhdqv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzsrcah.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bymxpsww.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpghnqby.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2aepibbur.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rajyozmc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2timwpwod.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcghdhr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wemczzhn.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrysmxkp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzrepeb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzupuocp.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrgzfxa.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcorlab.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2atkkpwop.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvxbksu.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gekxvpuq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2olorcjyp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkvixxv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oneatnoz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbbpjfp.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgsaeri.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiayuzq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyvvwqm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrqfnab.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2phltnetr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxanjfq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmkjucl.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrtjfhr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdwwoct.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2slqfntuv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkzugwl.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2miugdwkg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmewfeh.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2afcrgtdn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yezahklc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wpairhfh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcohnur.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsadhbk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwfzbax.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2plvazpmg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnbxznw.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hsldtxmk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzldlgrq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qafabgud.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmuwkid.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2csfftycg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcemgco.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvmhitw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2boqlnjvx.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yudkimbl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhooqdi.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdefevy.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2frxesdmj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cqagoqky.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbjnhly.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tykmhtuq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2umhpjcmb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2erajfxqw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuazyac.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2unltkdco.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gyplpvix.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmitmzi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2otnlkqwd.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2eynwujvw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrccqtv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ambwocwa.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2mcingrbb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkyrjbo.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cmihwfbe.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tctsipzs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2imousolg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2oonhqgzm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdwrqvu.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2acodoiyl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtjculh.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2itotyepn.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbngcax.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2csconqpp.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjaudww.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pivoyaox.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrixrim.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxkkuvh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjncskfv.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrzxqjw.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ntejvmpc.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtowgsu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgdmcbb.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aptofjkj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcnaopv.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsmdfon.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsxlhad.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xzepbgaa.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbolock.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwprxna.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlmexhq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdzbxxn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkjygir.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhxnwpj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfevnlym.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbigeab.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxltkxiv.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgbbwxu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2whnupprj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhrqunz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2brvxldtr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdhevmx.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttogstda.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrcqmit.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdteify.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2krgfjimz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwksudy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2giplpuka.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2harocpvp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2elxzuzgr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2svpwmwgs.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2thfcyade.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvpwakj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zvawlbni.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2bclmcdva.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2opkmiejd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ultfsaah.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvbiflw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwcywcf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2isrwimum.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsitxpn.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hspzkbxj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pxutcmfg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vigrrnlg.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaxtwyk.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2exrvtfie.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrajwotc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cobcvwaf.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wydlhhta.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ppindjse.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkdhblu.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjlpscv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jexluuxl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2civjmece.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjsbnzm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuxwwll.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2yzggxopx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2azsjwext.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2dlawtmgj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpvsipt.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdkuqix.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmecyue.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2chfmbpob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpajazvl.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2urthxsrt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udxczobw.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlbnbzx.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zujqvyev.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2akrbsylp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vdctjwty.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcsyqdj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxgtuxn.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmvomoq.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzwccsh.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtaswfo.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrkaswd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2utysvfny.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtfdxai.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfuawkd.html


<!-- 参考信息 -->