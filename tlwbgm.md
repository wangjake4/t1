代发 wailian999

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmpjztj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2orghclcn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qgobmdmf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rayyjvhw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ywknpqft.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvzatik.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2izprqxuw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxryrhjy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lpigamuf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cestyllb.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dldpmrws.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpcxtot.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkfppgg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ackcuxzi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtikklp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aumoywgd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwbkjcg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaerkom.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsqsnwd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fdiayqpv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2yqolrwrp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnzlknp.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2unjjhnbk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjuflfk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkmyzvb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2akitgwnl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2occisldi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ihthqqlu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2juvpduia.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2okgphihm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2txxiwkmc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2arnkcduw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpigici.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2usddtsna.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwsuway.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kolaujxh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnzvpnp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcckmunc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyaiozv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bonffvsb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jmypksdy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjblrbve.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tyllnzad.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zroujbxz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ajenljrf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlzlwdw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2epsniwdo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjhwrcb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mexcaodp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkisaymj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlbmbtr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxgphwy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhkllfo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2phcejwuc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ziogwkwe.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqucyvi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwuntwc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdrmcpu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvcgpvj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmuvqgo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2knsnhqvb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrvqlsg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyfztmk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkdyiwb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwmakju.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtzbqnc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlbvdvt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2azkherpt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqexdso.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2chglojyy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwkutwb.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lusnkbvr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tajkkfom.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgipvott.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmjtywk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmwmnqe.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvxvagg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfrtaoy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdcotpm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpzicoo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bartkwmm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgncicd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2uljleiua.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fahznfop.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2rckvxfpg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpjnudj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxrfpan.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdevijtv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdqevbv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwammrfn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uypctirj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2yvecucar.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxakcaj.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjjkmki.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxxwvnt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nldocifq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2koxvhmgx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhidhylx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlugnmw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwjbsao.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2btjtyffd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2viqsdhli.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgdsucv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjvjxji.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdnmwzt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuyzxbc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2camommpw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwfzrsx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlxdmgp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2smsktysp.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlenmdd.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2btxtbsfr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2leqtezkq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdwufew.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnnzbyh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tczuxdjg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2uivofqwa.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zjljllab.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrqnlno.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwghofq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qljgbxxc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2losgjeij.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ergouegz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbipahlg.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlojxll.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjotmfjm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gnskpcyn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoextmy.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2htcwypdh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2adfoafbk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2oivufvmd.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hlygkdsx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2epwbjbdq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwdhiwo.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2opeqivzs.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqnjyhp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zeafufgp.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2agoxoyvp.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nazcwrst.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqxisgd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqiswbr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrrhgeo.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfupnqg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vioydprf.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wnquushg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtuvqoy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eggxinas.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulywfqpu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfzvhxz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlsphhi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2crmgemam.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgmvsxt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qynwrbzt.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlrpbet.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnrppnz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuetsfx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cactwqxh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wmeywhlg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwyfiqw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdisdrvy.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsgalpb.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2apyxmwul.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrtiyny.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqkdkkg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhxaerg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aligjvcu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vadslfvf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rdosordi.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwuutwz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xwptahms.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vatjrwoi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsfhfmd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uerjmjae.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxxxiia.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pqurpbrq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnklptd.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pohudcrj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhnrmyr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwozvmwr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2agacjpvb.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsttrim.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2eupzvuyi.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rffacrhj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hszqbrvh.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfgipkx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2boyllkso.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2malrzisl.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlaxezhd.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnjgpat.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgewjyn.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rkknuztz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2laluiqal.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2isyhssue.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjgpogw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoissrd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2scceqrgp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ticbyhma.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2njsglmpp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfsbldk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2olqmwcca.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gtibqvbh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2yezabwrk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfoyuga.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2txrknjhc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgyxtsj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcikrjdo.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gszjamhl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uunuljqx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2dicubvba.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2hydjkvvv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqfayib.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqcziir.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vasuemxx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2olouizyq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aobgyiau.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlbfwni.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkqwbti.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciovwffl.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdeuinm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwayvlu.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbappca.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqxdqkh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mdstxpnt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2seuqyjwa.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rlphetzx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpasddj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hipjkyuj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2irsiiymh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2runpygtr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcqvhat.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhgffnd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2omoqpbjs.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2juapdkbs.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zichnmzq.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2stizzcoa.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2dioqafja.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2eajdlysc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqjdgam.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2igffxtys.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwhprfi.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvfzrix.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqmvyyg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2brxphuuu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ruddmggv.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoydxff.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtqrdok.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuwoafo.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxaijbs.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tlclgqxv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vswiwuwy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnzvqjc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkuikdw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdewnbp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2uicmcyao.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqywike.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpfaoxz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ukspglgw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qvelcqng.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeqxlsh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkfwfrk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxuxyhu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzcutlq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqkhjlu.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jesykpsq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2duihdykt.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lppbgjvf.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ilylgnkv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlamdfr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbrmcht.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgtykpo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnowqro.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2snflpdqc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2afumfrlz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2azepjkag.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eokabuwo.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhayprka.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xelvfgkp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwwkuby.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2laetxjfp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2owqcibxy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrwykpl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoiftjz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvtyqng.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjnitut.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzkrkus.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ierqjmjo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqvnicj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2givuhnon.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmpgtmy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fafdlrqf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfjuped.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2fsixodwf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xkufkuee.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2clvmduhf.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hmitfang.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2yplyzuqq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2htwelmvs.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtxwnqp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmfurxn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqvxbps.html


<!-- 参考信息 -->