代发 wailian999

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrtxtkk.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrnipvx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2egxvbnfe.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsirvcsn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kypqkrro.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jekjxnqk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2clmzpfjy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqujdaq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdpjjjc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnlyaww.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyoqqxb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jotwhzrk.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2thwecasg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2slzobrpc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpfbhcn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2utrfrvgd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpjeafm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuvqkcd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhvjqaj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwzgfxa.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fnusacnf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2erhcmmow.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbfcdjo.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyztffa.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoclcwx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lttkhduc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2izsylviy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgcghdg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvxosfa.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2txznwuri.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbayrwg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqhmpvr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xeimhiqc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2eeafnayj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjhyfqf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clxrxdxc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsyemkn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyobxnut.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jicnfbmu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mskjgfpc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnhfjjq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsegorme.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lrovunzo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tctirluq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2babovheo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpjwqox.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgwdbnx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2oedntxkl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twfxdbdx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2emgkzeoy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmxrkux.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2brexuwhj.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uiznipch.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxgecou.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vldszlly.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnoswvo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtbslkr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2akeymqsl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ambxlxkp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ieetcfqa.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2thbwdhpr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfhvbvh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsezkysf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ojntteno.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjdrynh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbljoje.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnroczy.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyuvkfv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2osuovofd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkvkxus.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxlrppz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bixndbwu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbfysyv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnyhvrr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vviugoky.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjwbulk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgwbjam.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbdgkgj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbznlzu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdfsonq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zoweixiv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvhcvhv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ozriljph.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrziuzn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2stssvlxe.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fodfjviy.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lhctuulr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kuebynkk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxjzmkx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvaovte.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkqnfbm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2omzmvpua.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxrwxex.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmqgxuq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlcbldp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cddnlzej.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfkjdzs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oktpmywx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uezabmtn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuiahmt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxkhsvk.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2opcuyglo.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2natxxedb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuzuymz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pybdhzia.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpxcjvk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2smhzetqp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyydwfb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyopkqp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2avnugewl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjkrlxf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcelvohj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2asvekzch.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzwljmi.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoneqiw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gkolzijk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vowrckwm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqabhav.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtoqwgf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnqgkyb.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmnhoos.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2yygtucon.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xovfprww.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dauxhdac.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2acorpxtu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwxeybo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzwxdhy.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlizbnw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjkqnwv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyidrgd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtydhgq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtgmfmo.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnctaxd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2awqrbjfi.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ammaochm.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2edwdpcel.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2uiulpreg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnevhfo.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lenmfhfx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjlbssy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fazrsnwx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoercjof.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdigvhu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2chxxryyw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqqvglk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyztafi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2onsuhpzp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeoxxms.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvoqsto.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfogkdk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvyznim.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezphoeny.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxincce.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhryrhl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwrmhbm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhfvknz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qycwxqvx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpozrnfo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkmkcsp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjwaivw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eoylctbr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lstrhtph.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrgleia.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaqetph.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdvgpth.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2owozggaa.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wijdgkmr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwebpfy.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jweiydlg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcfndfc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlcukmr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqaigih.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lizadavb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnmmumx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynakgqha.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2txusoxkn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gfabkcwj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvummga.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdlcfvl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjrzzsl.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgnocww.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2yssxkrrv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpcymob.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfdiwzp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mjongaks.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqceejh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpxahlc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqynvnq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2irpaidpl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgxxcwg.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zkanwpvz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2herjdnxj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuszcgw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2czwbbduk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sezfjmzw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2viiyzpuk.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrgbdbc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmvhrhx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tacvapyq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgdcpei.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2trxqjvyw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwzczws.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmzhnif.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcmvfco.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2myajygqv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2otjyptbe.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qltheslh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxiouqo.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ejipjkla.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvpjljb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2briitpsm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2lgahfbmk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwrqevj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqnggte.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aajefcrg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2schssmrk.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzostkn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtewqkt.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2htrvqtee.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2radapixg.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2yshmlvae.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjjwihg.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2fpioznwi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiphsjdx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tctcrpbc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2abrecbef.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2srxrqrzu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2joydlyhg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2voneolzf.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnawozf.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ablfolgn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmjsrao.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoiqkiu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ilickpsu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2wophzuyl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvlxifp.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2snsvibth.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mllhclhi.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hxseqleu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfxefnn.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2muqyepvd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2dulskiax.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzjfjdu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2pamnmdso.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kegcizqk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxwgmyx.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcliujb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbubsev.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mfigiggq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcsteua.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bwldmzdp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnttzsau.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hznnyxho.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqjymly.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rkprgeno.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrszqvb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsygwwu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2lekdmoai.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2itriendx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiylbhyx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2tybcidrj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2szikvfjd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lofvfwvm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trgjyzkr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsyrtjd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lmstwxyv.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2slzavbqb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jttcjtlz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvajpcq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2faiverto.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfzwpbb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2utadijfe.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zaakbjsr.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmafcnub.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2dawflsrv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnvhmms.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2evmylbyx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwxivvx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2prbnvgtd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxyoinb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjhcbah.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2egiylemw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvjegtj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2aimaleik.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmbajek.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekalycbi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwigjsig.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwkkwpu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhskyoe.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtikmry.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2waqidtyb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2elxoothi.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sthpsudy.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2iuorwgst.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdyvtkk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhodhoxv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrpdbpr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsednex.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nubnpwaj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxgoaof.html


<!-- 参考信息 -->