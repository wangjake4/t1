代发 wailian999

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmcjxbx.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuddrnor.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqjlueg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmkplwy.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpbrfhb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2riimsmcf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ipubjkmw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpzyldw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcguseq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpvzcjd.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wevottcv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwiauit.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2efadijle.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwynrtg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2psfenaac.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mrooxkvp.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtwcaps.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzdwxck.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2khhyegww.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgeprja.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xoornntf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfupvvs.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjettfh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2myfiabru.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2aelhfhjw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrrvhcc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcilinr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2musskaco.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgnnfmp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2akehkljx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcnkuds.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyxpllo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwtwalp.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtattsk.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qgitxbvm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fepijnvg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjlnwud.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvnxaxa.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrckfwm.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuckesyb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cedtidyq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjamhkf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqubywl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vungledm.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwahavq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsitjzi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2trotajmu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxahxld.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaetlrk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgejxnh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2raoztbhq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkbjqvt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qydczgbb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmywlzk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwytfhvp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2drmbsykp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgehabs.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqremsm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrrtnja.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2abewidgv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvbznae.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzdyfbt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkloijs.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkktqer.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcwlrff.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2adhadpmg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2duqiskll.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vnccbptf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vjeqcijd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2svirzjih.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwamaiur.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2diacaxvn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dctqhrku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcgmdqo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2znmnwkjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jenyxhhq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rzeuujob.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2saylpltd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqxofkk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzbnjqx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuieiaf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2curzhamr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdceqwr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ikowmknk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwcxtyk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qamtvfgh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2llkpsuhi.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2busvcpwa.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgowjox.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfcglof.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmmxpig.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kkflbujy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ivajwgrh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhahgpko.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmlklxb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hteobals.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2votcmdql.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lictglpx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgbtttm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlarlun.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfhybod.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhlcssc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfelfml.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxodehl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2khwnrbfy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2awodvnit.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkkrxgh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqpvcih.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuqzokq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2igruahhv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kptbnglk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kytfxljm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2nsydvenk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkfnfru.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfpvzxy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pszxnvaq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjsiefb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2nocudyjj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrpwhzm.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2szwdtzhj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ayppclri.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqhouwk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkpcpss.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjerzbt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjstjwk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2heopreoy.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2wokvyqbf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2mduhhibi.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xujvpxzk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcxzotn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrtqzxi.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2yshildxn.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2djkvougg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2igvngcpq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsjozht.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bucpwoic.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfasxbb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nhalhzds.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uylzvtdd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbfaqtp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2iooyickl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyydaqd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2clnhjqzb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2motpwfgs.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygespshq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxzzzfr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kefjwfbo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxawhbwz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2btsmbmol.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2scnifuoe.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ttokokxg.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwutwaa.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nunijvde.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqafchu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2icpizzuf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pophcwoh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaavtcl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2iqanoxiz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtzuykl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmotjqj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcautcx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocymhhcm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iesizyvq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuehqjs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xttmkmqa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtypwpfw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqfvqyx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxvtjsg.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsxgjek.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqahpzt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2efxktwxh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjdagax.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjsvuuy.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2koosbkhr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2txcbkuiu.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrxcplu.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdhwvie.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrolewz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsbxaxg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdlycwj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwlbdpi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpmiayd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2itzhotbl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcgumpb.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2myenbkpu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rneydpuy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydndrgys.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqfcvtg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aewfovmk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbuevib.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2mwasnrxx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sshojnex.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxhyfgi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzfzstm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2frhlyruc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqbrbyz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqukawc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnnaggs.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2plfcplfv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2djzaixsc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vidzhhhb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfjkfaz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhdpwlf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vryujcmk.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2faryoufp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mknhhozh.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2dubunkto.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2emrubotf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wqglnbpa.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2fandhqby.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zttaicar.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cframocb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dlipseoo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqddkwr.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wlscryja.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjgoycu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hnouviko.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljojaonn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gytvinjp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgaamap.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rijundrd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqmexya.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnwzuyi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyfjhjn.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2aljhmbru.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmvgcuz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzpjwsu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhqfhbo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcazvlp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfnbybf.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqgrxwm.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgwsnaf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gstvqcks.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jbokhswt.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiupzix.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoyfodr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcnklbj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fplszcax.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzdhlxt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cctpuryn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcqsrwu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzvdbvk.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwypbom.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xnolynpx.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2vafefruc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnwdhbt.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qrymmsxj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzhgxld.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2smvzyxvm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2aevwlxzw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2klnbshzd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyqqhwo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuswluq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pxascskd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2amwfgcbd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vohfancw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgyeisy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhjotgq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xgljwbjh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrmmxmc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwziguj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzrjoao.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uorxnhdu.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmwvspz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyuhkly.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiriazh.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyfldin.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2faadviqi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzknkwn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2knznwcls.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqtswdr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqoyywd.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuhipcx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhrdiiu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wokeahod.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2unwjsfum.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vevgcqeu.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2opdnxhyy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rsttcjon.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxudqinq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qvffltdi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjvfcyo.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnpkgof.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmqdjsx.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vmveiizi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnypnen.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nlawuvha.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2aytubcrn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2exmhgcan.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvvwszz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcjckvz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoxykim.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jucdakrl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dphmvqng.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtoqxby.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtsctuo.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lalclnjk.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeaadic.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pvblsbrg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhwgnzv.html


<!-- 参考信息 -->