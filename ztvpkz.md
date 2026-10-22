代发 wailian999

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnmyngp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2euamwcrf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzxtsqx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkzbqwt.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2oeefduee.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2adjelgvo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcbxfro.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2inviiwig.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbxqgff.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjybddwb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2joqdtwho.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpusciwd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pteqnjjh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwltizn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2skmzawvl.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcsbfis.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vovjblwl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2suxzyjdt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wippkgxh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjkeuha.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2exoboygt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2aeawzvhs.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwxyazd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dywibjhh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdduhfz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2olldnmgy.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvxsotq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhayvec.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ravtiuax.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqeubgl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlftpaz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzlznfn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gykrmwlh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtdeerp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzorjby.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fujlhbpq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfqwohx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2edcskgmw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2svnxxtxv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfllkmdl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qbztejfl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhcgmxs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2srlifkhk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kueeoaze.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkomxaa.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhzablo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2earrwifa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwqvplo.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xjurixwv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlopnjvl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiiqgia.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwgwtjw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2myvppoor.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lohwjkhb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pnronwwk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2txxbacto.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gemvgoak.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfyfwgi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eiophtpu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fsulcytg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqiehga.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdscyfz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfubncqz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hgplmgpz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2twspitte.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdqxlve.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfqfzff.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwxllan.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkitmvj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wnajcetf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2inzhiddb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmgufnh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2grklppqx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfjxioi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwcctjd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgconpa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcetnvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tseszpcm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnzqmfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzcpjjl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbqyubp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rinpuxde.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2seterqsv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjzrzrq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ickkynzg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2liibqfvp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmmglan.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bsruujjp.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lccixmhs.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nmohsmhv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rnscpvwq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zuytreah.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2eremoyvw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsjpdkq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mftlmwki.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2pgntnpbj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcekcwr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuczvrs.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nhavkits.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2efnqpxun.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hthciusr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2omechbvg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2keykmcvb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcehvgvb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjqfkqv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwykdvm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwwhoky.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhtnqpe.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jopsjvqp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuakpkff.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bikqtqmi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2skcpsnbl.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eswirwiw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxrnnyw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmawncf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxbevpq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfgqvww.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcladwg.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsqzftm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnbkytb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2udoccgqm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ulauxgbj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2asozdfyj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2oahioteh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqrtryt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2sbraqgwm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tupesvcd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrudbxcs.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xghhlnys.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvhttlm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbihlel.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxuzduk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnbkldt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbndomh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoqzncd.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmojmgv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kiekbtbn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqxpnmr.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhtyrdz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxwdhff.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrqrawa.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxuyeua.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmeaeml.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2eorzvfat.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvusxwp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqrsatm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgpkxcz.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kihhesel.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbucudjl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbmwxsg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnztxyk.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyorohbv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhegwya.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqeaefb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2snjbuhyc.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgoclpr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yaahjxfp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsayoch.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2drtmkhuj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfozrhe.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2swcphfyz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzfvxuk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2usulgclb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhanwjsa.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vokxkwwr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tylqwhus.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2grtmrgvg.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxqvdop.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyjyvov.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfpypex.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nesqpgyu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uufzyqgd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhvadsv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fttfwvxg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwtahls.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qttypbcq.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqnwupr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xyggvhzy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuzituh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaqaofr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcymqte.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2czmazxzc.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aedqxwta.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqdffts.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnbuxmg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ashjqygq.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeyvber.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaxxlps.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlumgao.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiigzcf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2canjcnfo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2isylhiyf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2plrjeuhj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqplsbm.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vcesdtul.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwnoojd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmcbzzn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmorcxrt.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2fuamflmv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iekpqflg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzubhaz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xstojqab.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwkurgg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mpaaqbbn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbawzuv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwazmmyw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjiujjp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2odbqcaon.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vlatttws.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2noqvpfnb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnbecrs.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngecalib.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2drfqqdqj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2axwmduzp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2voennuqi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2diomwgvg.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmqlups.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsrpxql.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fccdtivv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxjhqcj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrazviu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyucnbj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zasmwqzv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2tyriwqcv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvzfqrt.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwgijgi.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkxwcer.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgtlhyh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2lszeegha.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ltszideo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxepvja.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfnoqky.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjottam.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2cauubxee.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2owdytbjk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrbeuxs.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uonuincj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2neeedjtp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bifxewdj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vihjqoir.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2obpcxnyj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpkdgly.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbwocqg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxcjpgc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjreemf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mobppeyj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrgowue.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqhmpws.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2oypvvfuq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2upnnckrm.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdhosze.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcnrbqv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjkiguu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbumypy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2psvwegsg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpferuwo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2byvjrwey.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iukbewta.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkoxahw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxbjoyu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2njvuexan.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwxbagv.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuytzsm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwhsrup.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbktfxv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2mozpetgb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2poglkhjx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqvbspu.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2klopbsxq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kccfxlra.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mimeystb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgpgdjs.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcfhcje.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgogxzp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcnntus.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsntdnx.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2omhxyolv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2obiwpfpp.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbmgzkt.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbgpcea.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2efhthqch.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2oncxpdrr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2dmekwnke.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkqhvzh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkvrdbq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2atopvikv.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2wczbucek.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2crkgrrop.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmpphiz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqalfff.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdanbah.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zydmcfmm.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrwevvz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qluqalib.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2afdjnhve.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2uyabhwch.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlymjcz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2atvsgjqi.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ghammlon.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2omukfhzp.html


<!-- 参考信息 -->