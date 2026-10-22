代发 wailian999

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uipexrxm.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaynbgp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2burdsomf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2uslqeigw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2akodsvrh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2amvjljrv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjgmzfm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzrtugq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kcorheog.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjosutjk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oycgqpdv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrdhejd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2scgravuh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2lwukhupu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jkucwepp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dhftqxyy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkaxeay.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vorzmsbq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2padqpzok.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdbcwcp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vchtwmuv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjzqrwo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sshwouin.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsecbht.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lywwtnfr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2thdjarae.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmdnilw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2roylqogj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pveafnjv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhlkdfr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ofywivwb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2evdrfldh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2auxchmfy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qshrkynw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nehafiby.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qidxybyb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dblhucga.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icrdndsz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hcssbmmn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnhwptr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2yunjklue.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ommvvcsp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyykuxj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2oncixdek.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aybzarja.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiadxofm.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yavkzluv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgpeacx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyparoe.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2raglbxvr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zobdhqrg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xhidxdsc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwwnngy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mffbjleh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcapvfe.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtumyub.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhixuszd.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2olotkxxp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaztivr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vbazbkxa.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyykgdj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqrifkr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbduagz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnpgggj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2btpuqydq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jldcgdrc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gndegygb.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2alwfwkix.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsywcpjw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yurqnqao.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmzufly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhbkkvd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwrmrtf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmbybho.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxjmkry.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgeuvmy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pggsqslg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkczgcr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyfsxlb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2twfkrtev.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2deskzszm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuhlgan.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fldampiq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkecxis.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdacccf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzijxqm.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ossdobtu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2onpddxxh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoavlaa.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwbmtnh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2crekgpmf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jctkrlve.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhgqvrx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqrejet.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyhpqxo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtbtcny.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xrylxlzt.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmltifpa.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iuycjivf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2iteetits.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiddgnl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jamttsea.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nuokvnry.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcufexf.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhrmvmj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dojhxteh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qrprwmwz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxgjipl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gfedtkjk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgjfcfy.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pyciqodu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2izvdjaks.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvbvyrz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lkymksnb.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfhvzrj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyyocdk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgrabxv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zscapmwl.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2buzcaufg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjfuqem.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsptgpu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vncdwnwj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvzrspn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtiqvnt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrqktsk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2iasclrfz.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2waebheev.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsfzucz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2phhrfzvm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjddutb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwkfmxs.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcjptuo.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkrtkpw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2uijssjdu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2peiqznns.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2otlonwkf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2agblgjzn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkzggvn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuonjgt.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbstfng.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfndldy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2oysiozxe.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dihtylkq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvlfkzq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2atvyebdu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wicdxvoz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aesepjwo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbaiiwz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2khxhwfzj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zljbxqqp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uurqsmif.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2medelicm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfvtirv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2miaagnmt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dirkcecn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfabojsk.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpciwgg.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xshzrlom.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dlssiwwi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcpdrkq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwihvaj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jptkmdkr.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2unioizwv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ikphazec.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2girjpyto.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2lnactlvd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfdiplb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwbrmqc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hibwcocp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjvjmyo.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rkawyzdi.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hicchbyr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2psockfeo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwrqiuy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2crugdnri.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrkobaa.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrdocua.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2aoduaasj.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2smcfcbvq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zworphlp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqobrhn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhqaahv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zioybekl.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqmgumz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxhxene.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgbapvv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zprrvxod.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfjbizq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xvndmenv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zekdulip.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfhinsf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpmlfbc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qcibvwji.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cetshlsw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzqrmns.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcoxnne.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhbakzu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2usrljnoc.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdfgjcd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcglwzs.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqmfnzf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2toydeiwf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhtuwld.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkavauf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2yatnhnsg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2lylmmlpz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gityihzc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2omfffkoq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkfkdsz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdlqlbj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aubooryh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhitvdn.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhjtkca.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2oirhytqo.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjtnbrn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rewtugjx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vccgfrlf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2isihejkb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eclkjxjd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2dowihocu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2bamlrild.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vpomamjz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbcanfm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgdlatw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhvuczk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqmiapo.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzcqfir.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2azlwegxa.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjnqdrq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bmitgone.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvsqnxw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlkbcll.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2oomptlos.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsqrqho.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2lkklfsts.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsphqgob.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lphqfiua.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjkmaue.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2eboskbcp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2idwhgzei.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzbppof.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2djzlufdw.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmtriul.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxfkfxt.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dybdxkdo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdrkqln.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jltnxfup.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpejxrie.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvucpbd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2uspwoqdd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2doipicvk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxhjuzf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlfokov.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcocqjt.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjocpvl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrjaeov.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yeaflhgu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2muuupbkn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdnorex.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvlfqjk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvfwwhl.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqgcyyo.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fovrjujx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtpjzja.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2cphysvvw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxetamxg.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ralbrubl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbsbpcc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkhaeuo.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyieysj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jivcqrew.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2oertngzh.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hladhjjf.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfguakn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xzplznbk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvwomqf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2djjcucko.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzawfpcp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2yppgcopx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfaiwtb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsekkjt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cltgbgwb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgfpmdg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2nulfwflr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxhhdkb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoiksnv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjztuozq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2mrctsuqa.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2apllduqt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivahcwlq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2edshbieh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpdcvrw.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rfksndaf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2cysdebjc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2yofbguac.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxzhlaz.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mklpicci.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhqybim.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2guenifeu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmiwjth.html


<!-- 参考信息 -->