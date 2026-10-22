代发 wailian999

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2avwhbwfm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmiakly.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yddqqami.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyqvrds.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2krlgplxm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpsueum.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqrajti.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2raoesjcg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeuvdum.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fulwdomq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzuajbj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcibuwfr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yezvsaaz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbrmejm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2habnjldm.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgztxyxx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2runxlrln.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blzzhiph.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyxhnrc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbrcgub.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcfceug.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrjohfp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sehzlzng.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhyipms.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2agranubn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odwqsehs.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2scesfijl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2opjprxmm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmaufwl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2spuhxmnw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdyonqe.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fymygwpk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgomrwj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2njkuwlzb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdakrpn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvfssdf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqeqipfl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zocwljoq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrodewx.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdstpzz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2aakvqfyq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbmmjms.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qavowrcl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2krstwybg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fnikrmaj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vrareicz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eajhobwv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdlfrch.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hylfedst.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrxsipt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uguitftq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btnliqem.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnopbxs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyeecao.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbksbqb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2npnwbozu.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sspdyylp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbeogwuc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jbraatdx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2azktuqdg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmnbssc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxpovzp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmfegqc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrtmtlr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgboxsy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwakegk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtbzcqu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjqszki.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2juzkrasl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwfigbo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dmryrigx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2adnugrfq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ypehpdta.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlwxvlt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ressruqj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tigvxnmo.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnntmfc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijogakmp.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwupvrs.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzblhuwt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2iytysvwm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhafhzu.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qorofzrz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuilyzt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2orjwdcab.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmamcvpv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxnhnnr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmfnajh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtvsksw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eblljsnc.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdhxjmg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjedabt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2widvgsrl.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2gicjpypi.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2txpbgahc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jqocybvm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfrephk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yaokdrdz.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbmhpcq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrhyxjs.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxiycna.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbibesrc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2fxplnrvu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwehqbhr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2aupujmaw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cxekosnc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2peqktxgl.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xmensgwi.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqdcujw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpbrheg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqctgee.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnhqrun.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpvjosi.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2neixluud.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jcklhszl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tjymnisc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2lywqhcqc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhcehah.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsocahx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqkiavl.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwtyuob.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2edhbvhll.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2keznwjsm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtuolwv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqujaod.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2olgabxqc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bupirpga.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bgykyqoo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgabfmg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2izpgdexf.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dweaftba.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuwcjlq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmqmmpl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfvqyhj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfxylpv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iamyhuqe.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvfxjxz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvsvdsg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbitxks.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwlkrcm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwjxfrw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smlfedzn.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyralag.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vycsutue.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnskonn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdsvyzb.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bldfodok.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdsgrre.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xfehtjje.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2sholecyo.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bodjxibv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swasuunh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kspjfnjm.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbovyub.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2moqqkqiy.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzwlcax.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gjngrxxa.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbqjyaq.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcnsjlu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2bteqncrs.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2umingzxz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpotvxp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdwbvqi.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwnvhxe.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2trjlzcdx.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxviqgh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrvhxni.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebplqcuz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wnetvkdf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aunitsah.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrmmmte.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsfdbxx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqcncaj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxtcacm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcsuzvy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlqkflb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaktpub.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbjrlzt.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfzshai.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdiurpt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfqsrbc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeznwgzn.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkekolp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qagxddoa.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2uexgbqgl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjavfke.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqnurda.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhofitx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nborwpqh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jubjhdii.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrozzyh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yuppgrle.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ukknoujc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxooxwke.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yacjdrha.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjeoutl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvywvar.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vylrmbtw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjgbouo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpinijg.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxdamlk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2acmemroc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ufidxaic.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2glzznqsq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nextwvra.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnjnunu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sllksdht.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gxelbomz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2rfecwgal.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjywzfd.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdtdrqs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwnqwla.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgbfaii.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxitamo.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfxiajr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbjulvq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjytbfp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgqvona.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaulakq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyxysir.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qliqtznu.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbtwegh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqnwzhc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyimevc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmaapeg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqiuaem.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnexvyd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2acvzkmlx.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cppkbqtx.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kofryszb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2flodmwou.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnxzaqi.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2angyywlu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqcbnld.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iftmyvnr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bggbyrtd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2geeghwff.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2schwyrcd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaablco.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hujeaspa.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpepyuj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgqbkou.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nddwnmqc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mprinsxr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdiapai.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbwhoal.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcwthyi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnksbam.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xkykzujg.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ninrxqaa.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kchkvpkg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2alvfontv.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rikjuszh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqjagiu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2uyokprnn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2smgehrpw.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhqusio.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwibgqi.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzyalgw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdrblsg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bzropwml.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwmcgog.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2exahtyqh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2kimbogmw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpqntcm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlchwtns.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2omfbtxjs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvfhrdv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tphsklnf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmlyeuo.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2qirocszi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dsplymps.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dizthfwl.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2edynsjmp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2farplklx.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2abuutrrw.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2acibednq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2essdiqjv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2litgxvqg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2khxlpgnn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2omxlrptw.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2eysfobtu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhyhcjz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpifupp.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mztvzlll.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qetphfxs.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlqnojl.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzldgbj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2zgthaxzv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2iexkunwd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gaddsqhy.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2qedkiici.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucynaufe.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2stbayvzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urxcojlq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2veqbxmct.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrkpsyw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kadoitpf.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2siclmaej.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpgzslw.html


<!-- 参考信息 -->