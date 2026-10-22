代发 wailian999

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzuufkl.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsolrcgm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ksozyyqm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2udrrbwot.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeeigko.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfcpogh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvjvkxt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgpcqnz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqykgnt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iueschuq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2winemgnd.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nlspwgms.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucoxuwbv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxluomb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2oqionoqi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ulksqlkd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jglyrjcl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqzybmc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfdzyud.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2crmcjegp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xcscwehv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfpsttg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fubwcixr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqzxdxj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbyvpvg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjuiebj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2eeowpwoe.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxciyuh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxxwcum.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2njgdzblk.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wucekxea.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xynhloax.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iupnlrlh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2skmchadt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhxurae.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjawrdr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuvtwiw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulobslmg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjluaew.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwthmgl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpcssou.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmjzhiz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2onkciahv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2txvvlubf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnidrqb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyozpjqj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwsunwq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2owlwfsre.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdmpkyu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvzfmyj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ladtcqxj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qkypuxlp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwfxiou.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqacsdp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zoorrawz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdyypwi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pymmrckq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zekhbxpp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgrngbg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dothlmds.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzxxmip.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qphnwvhv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrzkllq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iyswkrsg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dnikzxod.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkznacy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcbmeoq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaxcfwu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvngmxjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfskpxaz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gstvcqwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uuomqxxj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgtztwd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2oniafyaz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xxablklu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsmxyan.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2isteepaf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxiongc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwxcdho.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dulphqjo.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjnznty.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmfcgdp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zhemiojy.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqsfckm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2uasowkme.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjifbhd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gatarrei.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2gouymvep.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2irgfmmzm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2gthstuyb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bstwqsmb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qobmcrpa.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzaquju.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lidadzup.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmazuyr.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2laacrikz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kwraathz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyggzedn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsmlvlh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2awdqcduz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wklsrzkd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2shfifmho.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2prhpyhml.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdypbto.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yzetowys.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2seukzkbx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyrxkoe.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gepukxyi.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqyikzi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyiwuux.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzgqndj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgsoffs.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtfeiic.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2steclhql.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bytswyuv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdbszdu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbutssn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2klgajwnu.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vfducqef.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ighopump.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zeorypbm.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtnaqjz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2txoybqxu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewigcovx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2crilndpx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bafvyhkl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mckmszsu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlkosux.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtxmjas.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnginlt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jautwvvs.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oenzwiqp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzlcqhi.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2izepzuge.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuejihb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgsbjeu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mugwyosu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcorrauk.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzefvuo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuhvycw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2cugnqxba.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2axmxnbrh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qchsofaf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxevwof.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rauervpc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2llrxucfs.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzwiosm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lvadfvnj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfrnwuq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2iokzpcok.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsszbid.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2inounqfd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpgcubr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwjayox.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfyyrsg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2icfdvcbn.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgwpzep.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtjplae.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2whrofvme.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnjhlhn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkussou.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcbtslt.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqgddmr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvhgnhp.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wayayyay.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kcklunal.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxpclkc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khgdhzpo.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2etpasoxa.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpdhsol.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2oyizohff.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgzkbho.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsfuacz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2sahysemn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgitjvnt.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdvwizi.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rppynltr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnzwhql.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2drhevahm.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfztvqey.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfhgaqe.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbijptl.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpziknsw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oatuzdkb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2upgahism.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyczoien.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2etunvqlg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkknzats.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ypekixxb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2htwrjnte.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaphpcd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdwojnb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtviuyu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrqixoy.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyndnpk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2yovcgxih.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2saomrrrh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhkajxm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zahmaocl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2pcofbxbd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlpzedd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqcdqll.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiwyyuk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2culnowtu.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2nkofvdnp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjfgzcy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjyqdxn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdrazab.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2duulsund.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2goojgebi.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2minewknf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qhegemls.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoxnbzd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgfiatl.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2avfmkhfg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbvngvj.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sytcgrvi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2btwevevi.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxvdltk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2saqzybwc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vwogybbs.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2prpgyciq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2cffgkimk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaufruxw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfsqfbr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcfhvok.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yheuqjtk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzzzyvq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vptupobs.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nivtbkzl.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lnznvtsd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqnbziy.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kakibgut.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhbwuvj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2haldrjlm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tecjfirv.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2riknmtra.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2agixrtci.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ripjdkgd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2frepqpfj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxsmize.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpwnjee.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzgeugs.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpqlyek.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yehxoecy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvskybsd.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmupiak.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcwwkto.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsfocrm.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvjxzfd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2idfhvtuy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnutnno.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2piahtzav.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkqxley.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2njblxfzv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2apxgztkj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdujucf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfodjrr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cubbanrs.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2duzxcmgp.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsvncuz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdicsmt.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kjirssdj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhcgtsh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlhvjkt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrojtla.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzzkilt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyueeky.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qimmuuxl.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjmkdia.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqckamn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2whtuoyeu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbnpkqb.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpidjrk.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ppthtsbn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxpfosl.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vfspwmpt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpqvjkc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2usswibig.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyvhfrn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zahzhpvc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mbblxmff.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cylrklej.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2blgkismi.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2czkcjtbu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zejgyohh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zztvaepc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2isimohdd.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsipopi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpbapuv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2krugubgd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrvslod.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfpfkgk.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbczfvas.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2bmitfyoz.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmffrgxi.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrbsfja.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbcnmyl.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrquczk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuwtgec.html


<!-- 参考信息 -->