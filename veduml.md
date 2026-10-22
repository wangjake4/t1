代发 wailian999

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2einicuoi.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2exukwoxq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlfzzlw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcbnwrf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2htrxnkyd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jnliqmfh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2skrcxqgk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsirmfh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwivsta.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkmmtfu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nihzczfw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkpljhv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nqermofc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdernqng.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpsgnlx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mghlwtzn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlmpqlu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkduwhpi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyapnaa.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2isbdsvto.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oueagedm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kasrazlr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efwlpvwl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhbemtr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgdmkue.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqcyrmv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aetyszpe.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiwoxdf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bccaktuk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcwbvcb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfsbalp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcqqbmb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsifwkr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2saaqmjas.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wchzkhla.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wixvqsck.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsafqua.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkagttc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpfvomi.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mpheypcz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjebjrc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnuyqsk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mksgpthb.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mdobugeo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2eylfrjdp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okophuog.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eoitkwmv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oslxfnao.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2usfxtyid.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2iienwqpo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jkehdylt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ottuqfdd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uojldcwk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgjoywt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmsmnnz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvxswgn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qudibewe.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnvdjgb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2reenjffh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pimjnwun.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyyzhlk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cscncvgy.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhkdlyp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2gnizyytk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2etollckq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqowadx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2poetlvcx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdimvze.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uuklecnp.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoymoui.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lafongvi.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iohaasuy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcpuijb.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydydrtth.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bpehnkfg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjaihoy.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2bsywhbnf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmzwotq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2oahsevxf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcqnxfs.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2chgzzrkm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmkizha.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2agfddjth.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lynctahm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xogtgmpm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwjzbky.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmzqedy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2whuoszkn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hedzfulf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fctkcvrx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcjrkyw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2goiculgo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nboegvut.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2byhcpunr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxyvrqe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2prpllhzu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgxxhng.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2grgbdbgx.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfxovcj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbrgywd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdnkxzh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2gycmgwto.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuxovlu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tzixmtac.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2enlnjztb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2frooxtau.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2szcpowdl.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmsaptg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gufmgpqt.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrsuays.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eagtsxay.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2amsmpqac.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2quprmqtw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xslynudq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2evmyopnk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxjeino.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgrabbt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrprwix.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xcksqbsm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrnkeax.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxxdztl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoufjgi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcbmtig.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2shanpdes.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvtllvq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwxhrni.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lftgqyoi.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdlhbyr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsmwkof.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgnhycm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzcfwal.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2apuewhtt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zuixkfks.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmdcncm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfsyzdy.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeooojk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2slxzesas.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pohcqftw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lhouvcjb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2krdtsvyf.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kegjnfnd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2cnptgkvs.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tczgwtwc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2felbqxoc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeepnnz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxyexup.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2robieidq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzwpgaj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfhjusl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuikfzm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lufryfyv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdokqso.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2huhykwbc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2oiknosoa.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gibysyft.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbasgvl.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pbypbswt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lthjeobg.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2opjqncwy.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsadote.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2snhqvizy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdgprel.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvqsnjl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cftxmatz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxgqavw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwhcfoq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2uijyhslt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtcgupa.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgvbpqw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpuqthf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsowxbh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fuodshue.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuoralv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkqcwwd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jkssnojz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqxreim.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2byyuvqnf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkfjinj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtbtewt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpmwrfh.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoxstcf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwdqfme.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2unshurdw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2efpqkkrf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuezmgu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlraehw.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wchsqecb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tttcpmwn.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvwppcd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2stvbexdn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzcrstb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqjtyua.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2quzlwhpi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2avnkpebw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zmabezxq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrtqklo.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmrpvld.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2epqpplfd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2geryipyf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvihviyn.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwvcich.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzkqiea.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtpiuhh.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jwalqfxk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgngsmb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bygpurfd.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2yzceteuu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2otomsxck.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlfemya.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbprnxb.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbeswqj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtjpgtp.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkudyoh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcfpdla.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xztslpwt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzmzkxf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvpphli.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2osgqbpfs.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmsgfih.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dflqpicl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjeaxae.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbvxcuu.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmqpifb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbsypzx.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2huxhubmj.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tzugtgge.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwcrxap.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2meqcrvfg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tylhsvzh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cyphwvwj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xnarsicb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcegsqz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbsytoa.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuxeijk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnnrfre.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2otyxwwyv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hthnhcqq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2efllttyw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bmttrorc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uitpuvgx.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2coybkmra.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rieezlbm.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gdefyubx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2emhffagf.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wkykfwbe.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2irgdcqqv.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2erozpgzm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnonrsv.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rtinbsfp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsswkcg.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ftecfems.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjtxgkz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2detxofpd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwptfehs.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kodyjtny.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oseukmre.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bnulbruu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2asnpckow.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ruksvrpc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2nvssejwq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wplvlmsi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmchpywg.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2smiemhbw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfnyqum.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qachqxcu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjekqhi.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2syswzdhg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyfkszt.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfwlpej.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2llxsxbhs.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuahion.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmjlxti.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpcbpjw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrawdcmx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2decrwfso.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2krhxzjlg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2psrrdwwh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqezmop.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfvvzoj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqshpknf.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2thosqgfc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbyxxdr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2culukcrh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlyfuwl.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxrlzpw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2khwfjfzq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukraubeq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zcynhmrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qffngttt.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoucsuc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djbitcrw.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqhiehf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wactqxgr.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnyrwra.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wgulwyoc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rcebvqiw.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iwknzuxy.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xleauviy.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxazfew.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqivlat.html


<!-- 参考信息 -->