代发 wailian999

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2twrurvjm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2upmcsnjx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sughyhad.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2crrrmpwy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxcbfau.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2yinkeuty.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrnkvna.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lexhmxmz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dcshqkvq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuzeyki.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2znslnyhh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgbonmb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2phgbuzeh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etprtaxv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eznvslsx.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdkxkvg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocumlwhz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kprocyae.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqefesr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjayrcwq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqubysq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fqehiqck.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oveglriu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdrygma.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbwkwyd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjjowwq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnuekfy.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkcwjlm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2resoqdek.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxnvpye.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjieizf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkamqwk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhqbvto.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhbsaws.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zukjootc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkqhepc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzjvxrb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvxecjv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwqsexb.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqaswch.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2berhvepf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyfotap.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdaxztk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iukrxaym.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmxdzfs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwhnhsc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhmyepa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbzcfkc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sexwznbc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqmdycz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jqogiqpf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzxauce.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnmbshh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrutxvs.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uqewwkey.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgseaezr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqixbun.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcdmetx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjltjsr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2koxvblml.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2erkxoztc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2alrnmfpu.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzbunpl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjjkmec.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jdalsbwl.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiqicmc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2elubozcu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oftplpjv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wgejrfal.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sapultdq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dctzcihl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwrlmfh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2idlskmnw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pklvordt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcdykyt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsogskir.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfcgjeu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zywspewy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2erqomdon.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhufmtc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vylctqmz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bguyqhpq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfnlwgq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqznhivg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkmgpdl.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoivzlh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzhvgpm.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfslpxw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bakeumty.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiauzxg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tjaoznpt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsjoiwi.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2osyqfsug.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsdhhzq.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tspnmfhy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhdykkf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gflxijta.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfkeduo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hfurptwm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjttfsl.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dauptdjr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lyntewhw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vyekgdic.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlnwjdz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dubrqipl.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nssssiup.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmziqea.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2znzllxun.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wlntqula.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiqlnmf.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2umzcbhgp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2obelhwbv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgnymiu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2axsmahsm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iaopdjzt.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2teiymvno.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdmnlsg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuhbjer.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnjwkdk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2exfgybuv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bewndadl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2kiildgzk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xojwgaxt.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvmmuwy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2annzqgcf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2sfexhhqe.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwdzcwx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2raqqvhws.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xxokamgs.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqcpzqq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uqddjocp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2intqlopn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgpsafe.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbiacje.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2scuyodxd.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjreank.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwzydag.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnmsyla.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bezpfqqo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2geziehlx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbvedrc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xuawepsq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2apwrntde.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfabekfv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2talxkbzx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zslnovhh.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgxabzv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2chncczsj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bsucobvv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjgmkhq.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzbelxg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbgwwtk.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuxyknq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsyfrok.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyevmma.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvzwakj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfrzsjc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fackrvkx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2kpohjfbl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqcykui.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2swrswogj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2agjpuoos.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyqiboc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehencsls.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrmwjoi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2htpkdewq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lngvwkvi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ntggxwxq.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nosddeky.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2nezgegkx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wdthgwir.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lovwgjss.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkumrlg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gintiiew.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2oiddlbna.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2croyvptn.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2swujdaow.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2veecqajz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxkzxtl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmqizsr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rawigodw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwhfcee.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tygracdx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2hfptipcq.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhzcjzj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmoqgvmk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcvzaqz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2silorcas.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rvstzryc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebioaprt.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsoimac.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgenhmy.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2asmijcka.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqpivky.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2vftpxefd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcrhjrg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2sndkgobh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2finapjaz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuwztud.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2cdovtsne.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpttsjp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2yakqsecl.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqtcwdo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfxgumo.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2puzqkhtp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxtkowb.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2actpwkaq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xijfccry.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqvywfb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdfaknm.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnfmztv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2dljhkgih.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2myqempnl.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2rketkvvu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpcgqrk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2gckbzjzs.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcggxkn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcwtjdj.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpjbncl.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zicvrcdp.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kddexayv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfenpvu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2otvhncay.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gragpltc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2stwcvgbm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjnyfqi.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2twngasnc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2plbinfxh.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuexavo.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tunixpjj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwipyeta.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcctkux.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kkarnial.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lttfumun.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2apozwnap.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtptgsw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2abmymkgq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2icyigpcy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hunvynno.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dftqwvaj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2pltqqmoz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pqacrels.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvduacf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgavuins.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2venmhrpa.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyfjdwn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2tutknlqd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwuwghr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnjbvuc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2supfirjq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rzphfseu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzzwqwg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tncbnesx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyfqdtl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jjktmgdu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2niyeulms.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxdkkkw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnoflxa.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfismgg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2njnuavwr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dchgilcz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2andwgaee.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2afvnmfpg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dawiimns.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgtvpiy.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bimojmqw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2iwficemk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2spivnnxr.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lomepiqk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgealus.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sosmcmbc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2utdghxxi.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ntudupaz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrkqwdy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2yoauuvon.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2diobjijb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yygvloxq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qamlvtkc.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fmanjgfg.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2svptidov.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhnubor.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2bivfcxnf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmcgewp.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2scfvemni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvikmyk.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ucftmonk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jazonmwo.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2qkifqaki.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vydzsjzp.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxvtkgb.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtawhcr.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2orsquevd.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgqsfna.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxgvxdn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2peqbqonm.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2maludqjl.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpbwhed.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2sevautcr.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmofcyv.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2cqivryrc.html


<!-- 参考信息 -->