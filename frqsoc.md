代发 wailian999

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmcvqvl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2koqoouuu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xflwquaw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2nqglwynb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpxmunl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzowuthn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbiehsxd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2evhlvdff.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuhnfdl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ammgjkvx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrgygmj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jvduehip.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gypmdyda.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nnaidkba.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2irgtbpid.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziglqceu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwdrbkn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihocujje.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwevosn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lddjphjp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlrnhzj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyechcf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fremuvcu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zommpnnb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kybgttqu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toohjhut.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eamozzyp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pukjyoih.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjuusib.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drzgfsic.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiahgyu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzyzvsc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqnbjii.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2asvvpugm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2corrlkhp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzsdezw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gasndthc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iynzwcwy.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mysxgcqd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fcffrfhu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwaneaw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2agrgfwwb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaloixi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kilipxve.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpzguae.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtyoqoh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkweegv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2relrtvif.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hoevoebl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuyywgf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2djtqdrlw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkxgsrp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvedwdlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuvdqfk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxjtaet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdldmve.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2stzygmgz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bnckmwdr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwsbfxj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjqnenv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lskxaomd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrlpysa.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wqndomzt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2duqkjymm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2brufwumx.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tdodsvto.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hznmcjbk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqdqowk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbnbgit.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zsarnjns.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoasdfo.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2bvklevsl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2vdncsqwr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjkmdmp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2srkswuyn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhftxzi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmljxin.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2miegxjph.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtuqmkr.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhxegcf.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uljnvkud.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lllhosaf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rovxsejb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fngbzyed.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsypadx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvokggbf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2yihglpnw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2msbocjvr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2deeftqis.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2goazpgcv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqpyoqw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgewvux.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcbxxgz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzqgvge.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2aavcmkrt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2djfbltao.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyfqfwh.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pgycyqrv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxogmrn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsrvrqa.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2buarbawv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hahvnucm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dretajmz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2azzrtmyu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2sylenxwj.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2esatgfic.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rfeuzdzw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcqhcfg.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2prafftfx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiclfxm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvhxkgc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2emofqagd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ksenmxqi.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2rreihiro.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2povcklbi.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oymbawlx.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2mljyxple.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2idufqhjn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uncnjgut.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfsrppk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmzcyke.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2cypbuzqb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjvnxbq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeligvgk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbtnctr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtevduuw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvifovh.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqvkwlb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjghmwl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fddwukkm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkkyvnh.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wanmdrji.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbtilvi.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrlvher.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2elzlzyyy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2azhisphh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2muaixlif.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2nmklhros.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvqchkh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eljjjrin.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ofddbcga.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjsuqbh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfgxlyj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpuksub.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uacjxpap.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmrmwvt.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2smhhlnoh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zelhbrrp.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpdpmfl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrafqfg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqwojro.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huklyifd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2khaqybvt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kurxxhvp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gosolltr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrpwtxs.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jksrsnfk.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cijkwccm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwljbsbf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wigadhdi.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2dahnmkqz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjikxfr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnecsnv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2xecqnexj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqoptrl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2upvbsqgb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zabfejle.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlizefa.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2svgxtsdo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awnsqqvq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hywqlfll.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2myqfugvd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbbpixa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvyijut.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2nasjnsjj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnxxfqu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdmjaxr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2buynuxzs.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2indermzr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaknylb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wapvnaqh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcifcwh.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yfarhgpe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbupjuo.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoirpnt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2acftlpsc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdwhmeg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaewhcnt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kttrpcys.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2febcqiao.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnkebcy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfclkkz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xolnogat.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2soqcpsmw.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkrkrqe.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjqhbrd.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ahswkskc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvuvzaj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlczhem.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbnrrsg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pguffreo.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2umkjetas.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjyvrjg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtaokeud.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zapvclvu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gxujsbrg.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxfqbnu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjvbjqb.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqkigkl.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2nafsjchj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ilawqotm.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2uappbezf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gktyixux.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyjbbnv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2cucheqvs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxkehrq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uurlptlm.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlbbnxp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxyovcq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2brqthjqv.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwxbnqd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2iialspwf.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2svtoxeuq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpncemo.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaioomg.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bndbrbas.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fbavegwd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjcujln.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2efxlfqmv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2gshukxsc.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hmivgahh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2svuqrubw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaolyig.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2frshzwxt.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kcztdtzj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkouroyc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qmymkitk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2doiiqykx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uulkabae.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgdrrep.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhdncpq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwemkli.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2moiitwyx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2occkzsmo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ebafkmul.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2opdwchlj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2unqajfcu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjmflnm.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mtacofjh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2shgpjbzn.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ublljpbd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oefpjdqx.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcmzazr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2otkpkmsh.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrssajy.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjksuzp.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iigplumv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiehrax.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrkprie.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwdojsf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2weatkfvk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2uaacddpc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbsplvh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxvsawi.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rekgukiw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkgufja.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhivspu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvzuudo.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2raqefddw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kovitiie.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaimgci.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvizhal.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcargwp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsptdlzt.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2negfzumw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtghzhw.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2feohlfca.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcntafc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqjvvfn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2efzwalki.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dktpviah.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsctfbhf.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnatxxk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhouptxo.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2aonjpygn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiafljr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgkbpxu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ieynauul.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2molsqcxm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2oltvrhhd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlnvxvq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2dmffuaps.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2enwcrcoo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrenwsf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nucgosxf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvbgzmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmuproj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzuhhmz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfyangg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xexkgbqg.html


<!-- 参考信息 -->