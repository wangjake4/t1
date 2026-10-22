代发 wailian999

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gststxpx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pakligha.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uqifawsj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qdppyrnf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmtucvb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bypjlhko.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkrbugd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyrzdyp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvnkiro.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbfoaoc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2urdjtire.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqsooru.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuoxhzh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhrvqin.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgndeqh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2updjcbpl.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gdttrbzr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjcukxc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmkgoes.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfklqglh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nyupuuxp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqntmnjp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhvidfp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2svtjblgb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lizbzqel.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgcshqu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2juapoitn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ujabbkiz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2odyaaxwy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2btxfuibu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tnibfndg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2alyxbotx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vdazukyd.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtdmeon.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oiijuejg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lisflexq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2unpamthk.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlcaxjf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxlglvp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqsrqru.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuiklqz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhjedtr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrryxdq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2agpsykpj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zlozhmgr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2miagmiqr.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwqjrop.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lummipfm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdasqcb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnpsfde.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpcmhpu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqokmsn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtwpmgl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoezoiqu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgkazgf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyyikak.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdsobaq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xazqxhom.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hktkxdjg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaznnbc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgjdqag.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnyrchn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hspxyrdj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dyghiwnm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuthfqc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2evnooztv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vanjdmri.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmzyijf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbftbpr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oinuymzo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjjjcpe.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2katpoyjn.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddudswsm.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyxfevk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2izwahsok.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdjjxah.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqubwtg.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdwarxl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyabfwz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2olamvlwy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2napkibnf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqnjhyt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdazsjwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcpvmvq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdjrlvu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2eswmkejc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lgupmbdw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdktzdc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlpufdj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyrfxav.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqzamjm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkzmsyq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuzlqvd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqmsosr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2buzqjayl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfykltfs.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjsgbft.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2exqdzuxp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhsqlbr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qikiggmg.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmcdvky.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwggvdp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvdgiuk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2equiujil.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fcutjlft.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhsbruh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjdyxle.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyocagtu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2willkykd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2quzraini.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2coifkxpt.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgglhbez.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ptelfqkl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsrqcsd.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zjckpoqj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfoojfz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gvncgrpb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2efxmlfko.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oslwmule.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2odqsnouc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2drlgkblp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpjihpy.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nahcrvco.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2soehhjwz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqogzct.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2crjelqhw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2aarxhiig.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufymeevg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyjzzwz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gyejpzfg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdwgaea.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2segimxpw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfcajfy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdorpvlw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2okgftinl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnthxoqx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2civdwixs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2axzpnnbq.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtrqshm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bladawea.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2krkocyjz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2atogjjfn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2glrhlpln.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2falcoqwn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfnvagg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ikivxnhq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ygudston.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2henlsucy.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdsgbil.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzddhivw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rcamppld.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgtuxvr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2iavovugm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvychaqn.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mamwupnb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2duochjtz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkpjsbq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2iusgbryz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jhysvxzy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrtwpal.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtyvkvg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyshhwss.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmyyszh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkxbyzt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2eolfznwx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlzhiwb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjknczn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qniqvgeq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwijiiz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkdqhth.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxlfaah.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoofvap.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iixmramv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdwlrkk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhyapbn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcxmqhz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaylrwh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyrfanw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2elokucdx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eboygrrc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uscnmbni.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2awiqrklw.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmywxwq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esrbqucj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgxyxbh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrlqagg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvgcgio.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgosift.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwnaszc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2aeamxeng.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrsndcm.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmzorzu.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2edfaabyy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmadaml.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2khrkiyks.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpghgfef.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2enrmaxdo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyiqpji.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmhfljz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xltgjjqu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2anneumfl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2raoekzrv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmtqkzu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgmykkb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jemuzulb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrydadhz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2veacglin.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfnsmhh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2usyxmbce.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzicznrw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuaqcba.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjoeyhl.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wzudixpt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2maynjnxs.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyrwiso.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kijbzbcj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwrkpve.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlrgiat.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bniszfji.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qiltsfea.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmmpenn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfreiff.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pkncfngq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxrusng.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tixpahaw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeihcjoe.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwymqqx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fsivyfbe.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbrmghn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2csjukwdh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrjbgoy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tthlffks.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vmncwvdn.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvfahbn.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrrheng.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxnwosf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2pmimsozk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2klzwitec.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkmxead.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwqbokn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2fshtaicb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbgyukr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xhesbvvt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzdejrz.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sjedynum.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2azawixwg.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hodxosto.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2otggowul.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tktrwuik.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiilngg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2drsqxapa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2wflitokz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfgknhp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bymdcqrl.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkconhc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rnewrvhh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjhoime.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxkicqx.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nehaggex.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwjryux.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrsradj.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bktccdjr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpckibb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2alocakoi.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhgqzcl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ravumapz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvowzth.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueroosit.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsactxk.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xbenihrm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwfivqy.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxxufkf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2oawusoxh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkrlugd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjnexmc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2omswmksl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjhnbgk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2codxbdse.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbqssay.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqukwcv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2nmajsncx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qtclfvea.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfaraea.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2agmlskot.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrgxuav.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lupjuwcr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2gouhsohe.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2opxhjzat.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqlchbc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuiaeeb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgoykqv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uscqegsr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgnjtdx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrmszup.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbjjmfx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2obowpuug.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwzfpkz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljiaazvy.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfwydsy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2psjpudps.html


<!-- 参考信息 -->