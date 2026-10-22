代发 wailian999

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhftdgiq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzknyfb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqyrgol.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfupetrq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2khpygqqs.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2weiciskv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jqonamrh.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qimoypsc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2inzdxvhw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzdeics.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdsgzvu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdiyxgde.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxjorns.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgftnsf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgjsxgx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2siywjpvn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpvjfjm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqakcbjy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kyysgmno.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnptfpv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgyfxep.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvdxusc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvwjdar.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bdixcjbs.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfqbolu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cumyvtlv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lppasbot.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vatwrgxq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uabudwes.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgciluiq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrhatrc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2eycicxmd.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eukpgrob.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjukuau.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmxtwjv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmeorvl.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdzfjfc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrvdojm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtsddlq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwpegdt.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tgayvlsw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsxlqgm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2puriyaaj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njltykso.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2arfikypt.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfplwegf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2agaccnop.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtmivbx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2comalfem.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hunwfwdv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvhixrv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgidoygu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2duqttylj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksabxxfa.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlwvpvk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bandptru.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biboarpy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2drqhlhaw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2skwzwguc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjamins.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cgamsohl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbqzvmu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqjyffn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2opzfjnyr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyzwaon.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2saiopczm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2muwclxzi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2eziaxhud.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxllfrbi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zurlsejf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xezdskns.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbqemhi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2irtoptbs.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcahirx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxjepjv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2clxbfrnx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsfcwhi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxktppd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuoazky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2giuajeyb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jsijsdnh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsjpvox.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hddlsbzt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzzviny.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gypairmj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbutcac.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vskiwfhk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gndnyuhx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwoyvaw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2scewzshe.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wmunxzxm.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrwzear.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrkgdyw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2angpyxah.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuqzvhw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2znwfuxjl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrjhnqw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlimkpl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpmsmiw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfenmdr.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eujpvbdj.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyvyiqi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mitvivcw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgssnrmf.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zycrfdpu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pggyraqd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2evznndmv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvvjcdx.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2axsphwee.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2thsipnkd.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kkinzcbs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rovqthtc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2awhjzhum.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxsllcm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpkxwtr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvafhoa.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhwhquu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjywzlhz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqfwosg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2uouizhoh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2msklkmfw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhuedgf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjuqibx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2steasbjm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfdmhwf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2itdsbyuu.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmzssns.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eufkyvdl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2didlavho.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2aebrbmtr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqmmxvp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoahofm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2akxeribj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2sizurxri.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrehjmr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcrxhsz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhunbfn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbnkqrw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvlpemr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmmxiof.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2coxfdvwn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxgvnwv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxjyrsg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2canvyfbf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmkvssk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mncfnoik.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zjidhiti.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kczolhvx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2upvewbmo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvthlkdp.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uygeymxp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaciwjh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jgebixmk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2urmhmnit.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2amxqwmxv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2osdngdhh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2krfnhjgh.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2udppiwvw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlliipp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoinarj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnwockw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xziudsey.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxzaith.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2khhasakt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdvxzpw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwnmkow.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uglfqrmn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwwhsbo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2izgznshp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khhbzqdh.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oicxhlgc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mucalikt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yoibgiif.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2idivtolq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ibykzbwc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrugysv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkkyiat.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2crogjhpf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2cklqqlwv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovapktxo.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmkobzj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcgwbda.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgejguv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxvkvct.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2yzeddqpf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ryecgrma.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbrfhvq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhbhoul.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqwjgcm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2axximext.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdqnyyg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiclsfsf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkzsoys.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2omcvdywt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmcpinf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2isewnrvi.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuutfed.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mafnnxlt.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzyaydn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2baorfjgo.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbuydij.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfoaqdz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsailtn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxldpsbs.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eecdreww.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkhxpst.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqromxo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qderntdb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2khttmzqk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdjhwwu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfrfidk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjsokov.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvzeafp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2phqaxiqe.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sakkqfrc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvvhryu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmwcfwt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iondfaub.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vatoxnbj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzwigkc.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkanazz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyjjebn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuzksiz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2zogrbkjh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2llcdcqwa.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsenqrkp.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgyxfod.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgowpnf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pftukhbc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gtswvmpr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkzimlh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2sawzdkxi.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mfatitwm.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhqfqgl.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mrszqhjn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2upktpaww.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdanfym.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vhntiwcp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2uedadosm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqdexnb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2injzwxmv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2eblhbzno.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2nuigogre.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdjmhfy.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bslpkptv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzbzcmw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbpyego.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mgokwjmr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2svrmicbh.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjlsita.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yespdcyd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2udcezphe.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzrkztb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsbsbuy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bapgcmcb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kplxikik.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zoggitbq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2janixrmt.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2frcsatlk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2soetbcdt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zdouvvau.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2iflxyjsk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwewhgf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2apgxidig.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjsrhvp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhxdypi.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzxwege.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kewzubbt.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcysmab.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlexuec.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnadfnh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulitbbvr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwatryj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rroxdshz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2duhpqnjl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cxddhquy.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxbeifa.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2whseoatf.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrwutxz.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooliscqe.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxpbinn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfcksiz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2nspswbpm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkafynu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhuwyok.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmpqmlf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jblvsjwo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzcqjvp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkpwhxd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eeesffvc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgyyysv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsyakrc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hijwazro.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjbhzxu.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2czxpkmnx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lljxrljg.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxfftkr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtdlgix.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2btjzwcqw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgqrqsn.html


<!-- 参考信息 -->