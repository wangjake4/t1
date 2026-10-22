代发 wailian999

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuftxlg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyewfjzd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ddygvngx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2twupkqxw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkcpyrd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrvycio.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnigfou.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xymyrmtg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnvftll.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2awotqpiw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhnnvui.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udioetia.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nimfdxit.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvinkxwm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2knqhrufw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njqqdlwh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhpaiag.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auuitxox.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2upoqcjuo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhcrvxs.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pniysizw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbepgyih.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2svagwdvr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2baequiis.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okitkafn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cugiqpzr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwocqxc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjwtvwa.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iggapsoz.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcrwlbm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfapbucz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wepgzkjd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2drygxexp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wnduysqb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2caelfspq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqxeihc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpmobgu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jeplfzkr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2afahfzby.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzqwhzj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjbzlnm.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtyreps.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kimzqiuv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlfadtv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dshvsjuq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wuucmlmd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2almybjsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhnkvil.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rwclmhyx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kifgzwvp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgwlcci.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxrbhyk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfriqba.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjaeidmz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ldalpctr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyxhxad.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxbpmde.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uugvcoek.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxawjwr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2uacentvr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2znlagysc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrrijrt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqiyspy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2yauzpkch.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2resahuts.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xorvftkz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ddshgypf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrxgbka.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fefefrwd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsyrugd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2biobxeww.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xazsikwi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2opsuiiyw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2eudgsuru.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkkaymv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqzkwbs.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2qskmgeow.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxtyjdj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jyifdbig.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsckrxm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dbemvyzb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqgconm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnnqqbv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bosozqea.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2drxowurz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2heefaxue.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2knkvhewe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzslkzx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrrvoqx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2majjtoqh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ullpelbd.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzgwuoe.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsbamwf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2aunyorvm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxqlkrs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzhboty.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2spdigcxc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxmzxen.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkfmcte.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaghlyc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wotlmmtv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrbgjyh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2oozhapny.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlxxzzr.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqzhtnl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2sulckxgb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlrjbvl.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2duyaigdp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbellnv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2attrkkeo.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wecrdaxo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2npefpdlc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nidfpyui.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcurahuo.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ebafdnbo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfamujbq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2arckqkjy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqxxggl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hncszvqg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2isyxcpcu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2idpsfntv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpuekvo.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyelsek.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wydgmncg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnmrchp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mygloyjr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2btmgsxag.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyjdcaj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcagvki.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2niexgglg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2edonzxmq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlomllg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmghckk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2luvnfnzo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2slomjaxn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgzcgre.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxakvmx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpsutwp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wbprupwv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoonbmk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnuvbmk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2waaxlyrc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2laqpqquc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdhilfy.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqzeyaf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzwatiq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrspcrb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuycaitu.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqlijdy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpylium.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwszcma.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhisfhgl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2enbccapl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiyxgjh.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yumoosiq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2osoxftqt.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dieatcuk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2dedbnajq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zozgcwth.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2boitpojz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2breswcqv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xylfzlrh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtxwmig.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2otxemixr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yyykftpu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrhgmvr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ikizdhrd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyboqixt.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rykxglgm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2imbnybmq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnbvjys.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2syuvieul.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xstflkvm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzvpuph.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qlclvlkx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfievri.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgisbdm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2snnvxulm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2dqocendt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iopgkvfl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqcpxuo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuersakp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dludverd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2obnpqeyl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfmgfil.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejijnvaf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkkqaff.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfmeaep.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpbwzvk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhpqzdo.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ouydnccv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzpwtcn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvsepyo.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxskrpc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dcepkspi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xojjwxnn.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2afzbnqux.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2avtraiyr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2yozmpqdl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2osniglwh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsrltsz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmvijwa.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoynpvq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcvmwym.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jksmmkhd.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqhrrpq.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mcufzmqi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhttgmj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhzopua.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2agyvxjii.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqevtjc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mktkxoyr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2muatvifm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2swvxbhfu.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nrciqpwd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrzlhhf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlbhqwc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xikwpmvm.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2trenxrdm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2mnizxqtc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2etrrvyin.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wybgavmv.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2udikcofy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2idtxestl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuxxdsj.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2sljjjrjx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qaziorzi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjffixt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2anwlcgdk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtxpszg.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wycnfxtz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qijfkgki.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwdqthx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqcqijk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxooajrh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2polxssgq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmwfybw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2swyywnbo.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2twavznyq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgugnddi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rzabpboi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtwiayl.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkvbmlm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdgtfjb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ervgevew.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzydcyn.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrhyjrr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvovqtt.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2moqfpdoh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdogxozn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2awkxzdfe.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2exiwmlzh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2tgncqnkz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2idhmzhma.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjdumip.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jclzunuk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfajisu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rirwznmb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzrqauf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2kbntvviq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwambfm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2okaiqfnl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyayrbz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wgktozmv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cmknxkav.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwltuto.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2keswmknd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcsvxrg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfzenth.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdqogho.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvfkrxs.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pceyjqey.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hcowcwjz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmscmqyk.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyoolni.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlcauyp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdscdoo.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qurwvlro.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnhjitt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuonlds.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjglrha.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rjshimkf.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxvqvrt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2aywihclh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfkumec.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2kzphqgzy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2frblioky.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2uaueiisn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlwzyqp.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2bahclxbd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeuyhjv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2nipelbpq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmtafsc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2usxuhqix.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwtnfkn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgdsinm.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2myhdcwwj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2megyahvf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmkbvyd.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnwwoba.html


<!-- 参考信息 -->