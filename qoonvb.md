代发 wailian999

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rhclxybx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqamihmm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrhjthe.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2wsidwxuw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hyooqtmn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2iikhyyni.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vuepbrdn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fayyikbd.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hphyvwau.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2yoogshgb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2egmdeoih.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxrtgdn.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzdeccy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoauczma.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqhuchd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdgbsfl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmvlccy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usewwhfo.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnwwkhe.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlmluci.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ircfaxhf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpydoqf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhosxgvj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vullmrle.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hussqokb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtpuozs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeyylkb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnvfhcb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2avjyamsq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vepxsqlf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xafqfpex.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwtzuvz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pihizdtv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkyiwqd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvztnxb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2pejcsxyh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrqthtk.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsqoogn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjqkdij.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsenhau.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfoohlu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtcenhl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyxnwgz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rzawfrxu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvytqeac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihottfip.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwvukxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgdimvv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpxesjl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtbjodv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzpwpjn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2phwefsau.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2efcaaxhk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewttausm.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrlbrts.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlnyngk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mzthjyuf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwinvwrp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wsenmrfu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2prljqevg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyljhpf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqpasew.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nnynwysc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrrwovq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2eipolncx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlkirsd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrbkvyc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2haejwzyz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kuflbgun.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtqhamz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwiojwa.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyzvijw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2thdaexfr.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkiocnd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sloqtlab.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfmkycd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2padqgetz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiibfvvb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbbegog.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hymsiwpd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqfdpiw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssppwjpc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxbzdtz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2eizsezqt.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdteutk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqorhemt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkrgbqr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2eunlsoii.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lexnsvwi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ynynsndt.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gwodxflb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsnyzyo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elrtddnj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmgaqbt.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2osngpndt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrowgoe.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2nfazywzt.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnkjxrx.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kovnoxmm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdvkbxk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2keyqxkgd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2njfsypun.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2esfvvfbv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtcmdjc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjbhrcf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2sogpgdeu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fhoqjpuh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptstnvwa.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2udcvepmv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2yarkysbo.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jxktbhgz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hlobnovv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2rrquinox.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxuxyde.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdkbmff.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwviomv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2huofgfmp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuflhprp.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvflaiz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbrjzer.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tfctmbxa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rkntvriu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbbycmd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pesoetnj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bnehlnry.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2oeycheov.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxwzadv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnmkrto.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdrhdov.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpqfhfj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ktduommv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iljlpmvk.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrvvflj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbdkuyg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqjzvcv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2psdjsdbk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2syhapuop.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxpwere.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2klwjoeky.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dzivjuwa.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfcasie.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fczesurh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxtaxmn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzfakhk.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nbumjmio.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhyxbam.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2geicfaxb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvuidmj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbmhmpz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vystpauq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qccrphal.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2daorcfpq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2shiuoriq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzbzhwx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2eiovyauq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjsflan.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjvquok.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2maoxmhpr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2krgpdmfq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrarsxmt.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkvjixz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvubsmnx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pdogdglt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikirlpnn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuchtud.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtodrlyi.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2guzcmhhb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxvipia.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lciycwqv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tozmppvn.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjmrijt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbqbacf.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbxtbub.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynubwseo.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dirdddwd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvluzskt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cygmjcsx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlnpzcp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2urhajadw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoriomk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xmykfwgl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhzmqwm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtkixzf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rezvbelk.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2enhddpzv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2inmejfdg.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2okqmofnr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2etbbuzbl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrddhsz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvpkfvc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpgnuza.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2dwszasjc.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdbvbln.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2eepztauu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnaaury.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkgpccw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrznbqa.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2idsaujbw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2owxscfwj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwqoldu.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ozswhvgp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkbdsaq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfoudje.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdjvurk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2slkwqqrq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xolrebaa.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmgbjrz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjljjqv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbijdxd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpyborq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiklrqf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibteuwdq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wyztvmdy.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrtbkwo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2egnvlfvg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeiocng.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2vknoczlr.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsaftsa.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yoynspco.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2sygsdmvf.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqogner.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkiryvq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcnqjou.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhjzvpj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2trwnbbdq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxpnxns.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jouqllcq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmkyisf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwcdszq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zjulqjrn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aniwbnfp.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2apixfopo.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwpyvad.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2thwpplrr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2thhfsfoa.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhxvcrk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kummjalm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwysgtw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2koqmqwyl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2neqdjwgv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ykohflxk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmayogn.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjqifee.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2myxdjprn.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdmuxkk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjsrqal.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zecqwzjm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpnqfdp.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2acswwkin.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaushiff.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzamvdb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxgnibo.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2dntscara.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2zazqywae.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ztogjmuf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2endyvtvv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mizoxcos.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvlajrr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaginba.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgqxlor.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjjanvt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2norebabe.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2egzgfevt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtgozuc.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlloeqe.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzjoofu.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gwatxajg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nzixvhcg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlypkjk.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnmefyy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2nderqsyj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2btaghlog.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2oahpxdun.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjeqlkn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjlufxk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbxtcfh.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdsawdl.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjqctbi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmkzktp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsljmzt.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2udtnpior.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2drnpgdff.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2bybsknfg.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqfmdsm.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2zatajoyb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2omcvelcr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpthqsu.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2hxylpuxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elepohvw.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2olranhkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zptgwppn.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wszzblud.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdpdlos.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dthdkyfm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjnyiyh.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtqukll.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgltxfc.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ykimatvd.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lezbostc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbguyur.html


<!-- 参考信息 -->