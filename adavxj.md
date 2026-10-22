代发 wailian999

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqcuecm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcevimnq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwjgpus.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wthbmsjl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2hswwttuz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdicbcxv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dpaufqmt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2npfkaikn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcajied.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hriluwij.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmwuimz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfhkoxb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjpcrch.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2begamqjh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qcygfwtp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgaycsf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2stmjuwpo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjabyvj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2skyvcvpq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqhmegy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdetyth.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2adzenqpr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiqftsk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tccatblr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpcezbo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwqtkdx.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjszcjmw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vckjjwne.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yuttzryp.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkyqlws.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmclnten.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcfqkvx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxvjvmw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpabwrvu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2keshjezf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ueimsyep.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2asvivnvj.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2atswxlzy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnhwxqn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkhkqgw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2biiceuzp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2btuvrjzf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2omxryprl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wubmpxva.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hitpnejc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lradocja.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcxwzap.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruleiuxz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zstdihiz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjezmkjg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nfucingj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cydwyjcm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtsudly.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeixdsk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ardzwmjh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwqnand.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upmncukt.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfislzh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2inxovuti.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgpmbrr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bikyoecy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxhiljc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfezhoj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2naxgnwtt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwigsad.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjgbncw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqtmjwv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qquwlvxn.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2plmoxrnp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbrtghf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2razzkedg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dznibnay.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2aphywhrg.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cucuxdot.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqseqmm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2acktlspb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuuogib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkubirsl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2myolnvxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdjulgc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vtizfxkk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kswwsecp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnetcqy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyyynma.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzdvufc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaoazta.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpgcskn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqvzfzp.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2graehjyg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rievpbtz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yogazszv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzptqif.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2klchxoxf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjecwycv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdjhbsc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2fenqiovv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgzxdkr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jytjfcoy.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mzihgkcc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2pamzmpvc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfedftc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2coccasbl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uryjifwb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkydrcb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zauofsni.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcczxjk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2imbonrsj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2afqhfsic.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2bhllnkuz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxfgxxe.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2blavfpsr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsqobop.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nywljddh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlshnovd.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2igxpkggw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lotuxquh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrabtqw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzenqzpa.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjyqqkp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwzwgug.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyxfkps.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2gdchuezx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdpefhw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyxgjgv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbzugzz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2blxpcitg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvohgcw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwngvldn.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvyssdi.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2eepzldpw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxrzoge.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrettwx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrkgakt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuyoksd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2exlnmbds.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlggxje.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvqzvot.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2osiqerrr.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrehnon.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzszrca.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2duqzgsoa.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rohqgjqx.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2teakwcjq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvcrzso.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwetldb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmymhpe.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zllatnia.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2krjbdkcu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnytcjw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbmyfdx.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2biltxbcq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dglvsfon.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kesstzig.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkmnfpy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aicyhgva.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcrpnuk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrzdskn.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijryryul.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nrymrgkq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxraaefi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yexvwqtp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jaspmmsw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlkyvrl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2chwziohb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuuazsx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fanlsefg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rapdlhtu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxcdyzn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rfavfcea.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpnmafc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2flixmzjh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2yybohbzv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xrejygdj.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdkwesu.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrhwocx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjokmst.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nwujjhyy.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2eqaebfvz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsybnnc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnunfmjq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2erlythci.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2owtxmjng.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkhpmuj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmqiwgx.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mulydeqi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2serbllmv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlubexw.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2dexdsrqj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtcjjww.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ondkyilf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2otmvtrid.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqlvwoy.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2utwwvefh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgayjobc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrfbczc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2shwiwvfv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyxcvxc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2piaogqpu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqeajtu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrlmpjv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzlhgim.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqgncbi.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wzogkjoz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpuseud.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwfpbcw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2picpdkge.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuypyyn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqxxfqu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvqaogh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gadoclwp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gciozhiy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzecozvv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzphgxq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2optjcwjd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jmypeced.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfejssgz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aaysxshy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ishfhxsq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnnkqmt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mrptrhaa.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bczpqntm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmoqqir.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wavxdsyn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpwjoum.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hvajglbn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkkxoyl.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2srkmzbce.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjcjpqz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfdssvk.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhhlzia.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2blopmxqc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtvvlow.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nspzzwdb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2enqftlqm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vhywsuox.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mccotuei.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2kniuaiqp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2irvyoqlu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqsvtex.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhwhhnk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2apswjbtp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pltbrrce.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2akcdcqso.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jajmhcua.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfvibfz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2npmtpcnr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyusqeu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2isvmjdgr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxxkjfu.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjjhusw.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qhebnisx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdutnrp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaixokt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfltses.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ogacbewy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwodbkd.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bvczcjtv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hextspms.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cescofkq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2musrhngp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrqnowy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gkondvod.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bvogpkya.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwucyss.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrxhobh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2uebydkeg.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnvijss.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoyruml.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cajheeew.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwqhesk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrgzyjq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cimyugbb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvucjpm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeniawh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xprlkwwy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2anlnnzgn.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsgvibw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvagozs.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgafnla.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkllfla.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlmknwe.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxvfmrz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2shyuxtvl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2baiildyv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxpimuk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxloegku.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxwbxcb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ixezcheg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qsanbtyn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdqptss.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhldrks.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tzknykku.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaycqgk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvtqpam.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtbpkgc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxcfnap.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvwjpxo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2yleyrjmj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2melppjsp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fjozstsx.html


<!-- 参考信息 -->