代发 wailian999

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2djwaewbb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmunwpj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfjccue.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lomdokgu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmseili.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmlmprd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvlkkkx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzcrobe.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ukacrvqs.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dczpmakh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyzzhgh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gigdnzzb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmgralk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ansqczkw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbdzkgm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrtfiyl.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfubqeq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxupuvlq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rlflkrso.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oddtyckq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqggcfts.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2llucpmfc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtfsdsi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2miqbhhhx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kusicoes.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2moerngfp.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2csqvqjbw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfjonle.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ityzhgfj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhadmwww.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxzmigj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jemhrncp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vmihninb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpioyfci.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2viicvjzc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsyypos.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqlgejf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfamkmc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nefqqnuf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjqnhsf.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wryzdhau.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjtxbwh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnrvgso.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eewsailz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtnhksn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elcejfii.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dikesczr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emxfagug.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoqhdcs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2waptgags.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqfnbyu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtknckkw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2orrqdmhv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itrpxdyk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfclnhc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujccyzlt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alttrmbc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfzaumt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2motjwdfi.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2epttwqyx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mncyeyta.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2szukrycd.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsjhnaw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2djslxpja.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxsubeu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqetwsv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bimkckaf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqsmoqa.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2liczhnat.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjobjnl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmolumzq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bohmpnlz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uomdysgj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuaapwu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2suclapjg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwzubwv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvnkdic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdaqiuk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsztcqld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2idupaxng.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2muaywfoq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcmmhid.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqibwqs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpcvptg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2czeisayt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2voegqiwq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbzkfvd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdtwqlr.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2diwgikrj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2unhahwwq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtatxwh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvkqmgi.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjwijsv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdykhnn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2egoazyjk.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoisifp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2igrbojtt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nenoteib.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nymdowfv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjksbwc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hclmuezq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2enzsdlse.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2itequsdi.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2omttkaij.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cycdcksr.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uanzlgzh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nygguvpd.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2skcosvcp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbxtzfn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yesrqzci.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bggbwcvg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2virmwfki.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xkikctbq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzwtgez.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gsknxooh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqlmntk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bqngfpgl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruudgiob.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvmrjcz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsqnics.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2tpihfflj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvpcqow.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrfypnl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ztadldjv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfduyud.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnbrlne.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjtnzra.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlpuiry.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2odmjosoy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvljmnnf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbflhvg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vulrtebo.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ndonkgxy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xuevohrn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cttlwgcw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2coyzzirj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxnuylv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2uembkafj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnjulhn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdqjgkh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmjeann.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2unjmzivt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjmmpry.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvohppp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ncschxao.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajabgozt.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrhcdut.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2itwofony.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfyjknx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrbjebh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gkascxsb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2iywgmwjt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvkbrpq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkldafs.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuwjqtq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2idpqjrup.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxgzmdf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdexgaud.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuzvaei.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwgsmev.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzieuyh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rajomaut.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zqduftcs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnmfgyu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjrzkit.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlffomg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkrxffg.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2djhwilsa.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2umnppiwy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agperhwx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fhehvygz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rstucepe.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2syexbfma.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2eefteozr.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnyqnln.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnbzmkw.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zibwxniw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlsdebs.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nndhqvvj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gylccpwr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ippxdeij.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzljwnpn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpufqjzk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gakqurjy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsmfwgj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpnkuqm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzqbbls.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwyfods.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvmbxxf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzxhrvn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdnqdqg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpewcnxu.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2neaizkzl.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpacvqyt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2njfjhdwt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtopnkrp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hgscjfsg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2notvujnh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2gktgtsio.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdcspeg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2snupczkj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcqodkt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyqqtsr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmmyijj.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmytwwy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtanxfty.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2addnwgcv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2tbaqmtis.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nrckeeyo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjewdtto.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2merihgaj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oheacffr.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2refzlznf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbyjedo.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cttrxbqm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ziirmdis.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqflhun.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2drlsbdhc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2haasuerc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xvebatjv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2izqwhjgi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjxnbii.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2innoievf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwbybuu.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2myxifecb.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjocvyk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2edxwyuek.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxoqzcz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2xsydpfuy.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2sggcmfvb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2isoqovpr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvmxtbg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2faoecxtx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xcccureh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2udmintgv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2iegkaabq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdzppjm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bimrtsow.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2grrjplmj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnhucww.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2drbzvuvu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhwfysh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2nmflcqmy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wstemhsl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxmihxq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbpxoce.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nngfjvhl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjvjehv.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmxdqzu.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbxzijk.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2csoegwou.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2cywssaso.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2toleblcf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqblgqta.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2midvqbdo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfmtpht.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fwasfkmi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxoamws.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sgueevmq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfrzesi.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuucxdl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqeoqzl.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2egffhquu.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2splzyvag.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mjljntoq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgqsqzi.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuiqzth.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vshwgmcx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jprdhbvf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfscvqg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvuvflp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tidetdir.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pevbnifd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2abjwyfhc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dywqbtcc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uywootcc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gngxnstk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sihjhsqg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fazvudld.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfoqufi.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbfjhgq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2chasptff.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbcxcqy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2andlhxza.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwcoyow.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdbxgby.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2swrvosxj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hstrziag.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2izfsutqi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zfswiydo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyfygxl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbwuqtm.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiccjmt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkshucyc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2luvucsvp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2fvscwqor.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlfwamj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wikkcige.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2odpstcsm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvflwxq.html


<!-- 参考信息 -->