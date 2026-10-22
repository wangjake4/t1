代发 wailian999

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwsboql.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2puhdbyrt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2diskabkd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcavbcfk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyydtui.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfkvfdb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcqjnmk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbfrzio.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyddgnx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjjvchy.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrbcvxv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmpscjs.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hljevlgl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcszidvn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vadudtqd.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyclazk.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcaqmyce.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pxocxchk.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2znalcnar.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxpknsx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbwqbkj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2izcsmkqg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjiylid.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2aotnlphe.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnsnear.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2krnryuvd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgimxxy.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2oriqkrns.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2upmthuqs.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zomanrcx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoqqoaq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ynihcltc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcalkfo.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyywrlu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsqucjj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjofznee.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsddsfl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhcsoff.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwhptbc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blkcgppo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ditmuqbr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbujxvi.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiadiil.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrvavtl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxkpncp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzewfpe.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2odynipsd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyrfsjy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jeofgamj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsnvaki.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbthpzgr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxwxuka.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwnijuc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcdvpgw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwsymow.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2amshpjpx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pbawjccn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yoweifkw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjluxao.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uzplbnmy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqctyuwr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eziiluqy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2czyfhlmy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgomnrw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rygawhbf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrldlzj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcewvun.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2htgnvdeg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxyasoa.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdjsfry.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2izzrsdgz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2sscehgmf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqazhand.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smvrkjmq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlanzvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwiyabh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xiejgzgf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xorwqnrz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbrecmq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxenovi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hcltwfac.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2svvusqke.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgiuywt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpwtsun.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2alyjwdjq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iludvpdj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jusvmhoq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcdmcsf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vehjarwv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpfpstd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbxnepi.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkjcbzk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjjckfh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuugtqh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgsulfb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2oemabqqd.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dijcylsu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoauqml.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsnckyq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxctyhdt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2htuqocba.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmxidtz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xgarqbam.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipktzkhu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeeoiad.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcleoqwb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkhoatu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2oocdfcvb.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iainnzax.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpagnrle.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbaeclz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uemyxvhj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2brxrybbe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mglhgsqh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnprpcy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfsoild.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zfamnxze.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjrtfte.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gbokdmed.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkxwupl.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcevxsh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kwijuwtw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvxvbmr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2crupcsee.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2eubpkbtn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlqwqcx.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwtnzqc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2svtbizyl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrpjloq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2gnoehkyh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ampezvvt.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2lbohqbxg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2urtxgbbv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jygfmrtv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcegghr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdigykpa.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhwevae.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbnezvt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tqadbxzs.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrlfwbd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qaicodqy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxdsrya.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbldfwy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2npsfzuon.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bipkvvwl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2azclhxdk.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zreawqgl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmicpkio.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ciemclkv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjmfsmy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzntwwh.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrcmieq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2otnnfjla.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2glicervj.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tlouywcz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bogwobjx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuaqyvw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmpmzup.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdoypsz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrkegxk.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gyawcnpx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjnfexu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kalgoglv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ladqmbvh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eisbnizi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmujnez.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iljmxjry.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dsixusbm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2couvzfvx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqtrjij.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2icsrpxjl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgqqdbt.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vatpsxgb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcyqrav.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xhamfpwe.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdxnxhm.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcsbjus.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkbffnc.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2easzminm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kemcwwuu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2abpvrjwz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmsozca.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqumjoq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgpizii.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lecgljcq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvztjdt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtwmckb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2njbbbgft.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aliyonkt.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjivysi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fyisaxre.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlvowbp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aswjdpyw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcrtczk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqycjcj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwcqoyu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2eolprojw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uavgyfju.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbqatwg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2udtjfeyv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrdgucw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzdytqw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aghqliwc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2msmwflhw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qnooedfd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sigrvpbc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyitntn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2skvuzcig.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ahogvurw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jivsblmq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eazqpkcp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtaxdlh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2soisahcm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfyrdfn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qsltasiw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ipabnnbz.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcmogdq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2evunkvjt.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqjvstn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdrddht.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wouinzbz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2czewgnrw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2isdoxpqe.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2njgebble.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtuaark.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaybjvl.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2slvcoqqn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzrywbm.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ckafrjka.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnsgvfh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfapkgw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpllqsk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2yocbizwq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdseyey.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmqahgs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2trtgcoef.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nsycopxz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxvzxou.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mblfxqqc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtvfmmw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkyveup.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkozkjj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvjwxro.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhaleev.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2awrjjgly.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbckbar.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cmumjxrv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hializmk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgspbqz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzysnpcs.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsxcqbu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nycfqjgz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qowkggyc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2weagdkjb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqfdcdj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtwhtmb.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2alybcmwq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyqykiq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2azcsqgpj.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiyswpj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmciwff.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2mktvgikl.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbtwvka.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqjjogm.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ijndqbhr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2isomkqos.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvphjcr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnnjkgw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzqfbxf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjpphcj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2opwginjw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpaaegq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbkllrf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwhdtyu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvvpdfn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuslqhok.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2djuzpbib.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiwyeik.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2akmwmoju.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2psnfljjb.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2luzceamk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hspmwtuf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2tgioxntc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2plpmxpcp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wdaiocfd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lluywtfi.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2grgtrdwc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2eawfwdom.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2iayhjnkf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnaxgex.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rswimpow.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2maaorepa.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dygcngfb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvxwgyg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hshmrtua.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpyrqpy.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgeoxjn.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlqiune.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzmuneg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljapbcln.html


<!-- 参考信息 -->