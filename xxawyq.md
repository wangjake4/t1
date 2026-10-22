代发 wailian999

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mruirrfl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlvdris.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dsglcpax.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbugkiiw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vookbrxe.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgklhac.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hblodgho.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjamrtb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyntkij.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmenwuyp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jpemowhk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzuhxcs.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lknhkelp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztaryadc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jazdhuzn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsejgby.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2owwmdcgk.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xngyowuf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hizuwzls.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfzvyza.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dguwvesl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkvmcjb.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnbpodu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkftzqu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvfqnbp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxskywr.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkttpri.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2szofcyjf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkbmijm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2olbyticl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcnrxyj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2esfngctc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2menbscnd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqxhxxv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zahpcjeq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxxkwfk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuqtwam.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2aebtyqjs.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvifjiga.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vpguybog.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjyrxpf.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzvewbr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ungtwgsp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hncbfgbc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wzycmgmt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vbotbrvl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwpgunp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdhagfe.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2akpfntmi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmlzkxx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gsundcvb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uumswdnk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wqazdnry.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cctthncr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2edfidetu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzunjhsy.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lleqntki.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yatfqjna.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zatuuupo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjehawhd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlgohji.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sngxiegl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tomjkyvj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uifgywtw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ledfiwkf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xrynugrx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qboagozl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ipehqwoj.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjmcdxi.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2abrfnjbl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqapmnt.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2horswgls.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucisjooq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cppesbec.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2unsoawvg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgrfisi.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdtxwgj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cfofzpaw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2viceibhi.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqbmpwm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rdoxqfvw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyopkjh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyapkkhg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqqzwto.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejegbkob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrsombu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2niilfels.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzumdam.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbhwgga.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuelsrr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pofrvrek.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkjxjlp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gndavpua.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqaedlq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2anpnsoaa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lirwwrwf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2whnrfkwn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuiihzt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2skodunne.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ippjlfnk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wlauiwtu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgafhib.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ielpbwwu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyoshvh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ghciuxpc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbuhcwo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fscajtnw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zyriuycu.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uifshqen.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sidavjvk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jykpapcb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkmsxqn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pisrimkz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsbisyt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmibfhg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkmsaqc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpsijtc.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnimfjd.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2suvbvymh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ookeyphb.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlpuqoa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkmavil.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpvqvvw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvygsjia.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtihdsy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrwxlgb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdegtci.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjtaqnb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wquxatcj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkzfzhv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jrghphaz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hukieeau.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thnirddf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmibfsg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnfxugu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wohedahv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qyskbzkk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2kalkwcif.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2wpurmptg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2blkzxngj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lliotwsx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2btdcvxde.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvhjvql.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jinwffht.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmntgvb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2adzvshuw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2whfigohh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfzdkxf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ildnefrg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2gakgscck.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiosspe.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxeoyid.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2oltwrxwe.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmdhinq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhzqzuw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jriaejmy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmllriw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbtqlyf.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnbuepn.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoosouw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2stdbnvxz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtihyjj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfgrdnv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwjmdsc.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2conrhdgr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtccett.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzmfgek.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jszqlkja.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtpkuac.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wporregf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2xlllbsgf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajikyiww.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjfdqca.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfkjvlh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrpusuf.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2owredbva.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbpzuzm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjntecvi.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2omwtinnu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzlriyu.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2olhqrrwx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2htrcorra.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjahdtg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guipsqtx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lltnhahi.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbodeih.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2eufkidci.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2goafmgdr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dyucafqx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxjsrrc.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gictjmms.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxdvshx.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qwecwyuh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgdvymh.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuelqau.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qufjlvgi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqgwktq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbodmph.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgytfnnj.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzitvss.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwddxbj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2emxejhct.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ziectqkl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwbmmbs.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgsosyo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2olucvcsh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2adyhaych.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wucgmoql.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcmpnok.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyvuerx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsoauwt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2htsxolha.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpyvhgn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdzcolq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdiphid.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2dojlaxkx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcddiuv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2epokcbqz.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiujpnb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2unbganlr.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bhacfaas.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqhnncd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2abyjuohl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vksamcxi.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zusmosgq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2spzqdafw.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcgbzlh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmwenmq.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsmvrut.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cymydebi.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zgensvdo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2cihbnplk.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sdueyzgk.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtahdbcg.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2inwyplyn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqovndcu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2muntdkmz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwazquj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mygzkaac.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2suvvhwtc.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2loqdgdwr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2txeolost.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwfcphu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbhmteb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrghuxs.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2lofxlkhm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2emdbuvpl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ogizkqha.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hokspcrn.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ibegozpv.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqbzjus.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iinkxyhx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaqypdf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2uukkshjl.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2oefcsscg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkbobit.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2trjpdugk.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2parctfwj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpzctir.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fajmbrdo.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvjdcog.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvgeuop.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgzwyjn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejatpvvz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoyjrhb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxazvnk.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwlzjnt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sakixfba.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2shnnofqa.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnmwant.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bouzaprb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgumwke.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgicnzx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2drvibvkz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfojezo.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2amzgofac.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjapmoc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmynkhq.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wjslyjdl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsqyabt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2uerxxfwy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhlgerh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wecjqesy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuaouou.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnzocmn.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2itoustwb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmznzbk.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2trjvvquo.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xexuckvj.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2etfevfbr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rzipplcu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjvbsyz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrryknk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewngdqsb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2plyqchat.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kshjwglm.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjbklrs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2weqqheyy.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2smvpukdb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2wqomdqfl.html


<!-- 参考信息 -->