代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xibvnqlu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2whqtnsex.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2faihqtcv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuziocm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnjyxph.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlkowpv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqojzdu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2femxjpee.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhzoezs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgadsyu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iyccdzsu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ojasxggn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjkfzau.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfuavrq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zyejfyic.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2vsavpfqs.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdpqfqz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dndeajwe.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkywmha.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmxtdqh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2acwqhkbd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2slsofnqu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sobjbscn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igksvlrm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbhaphv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwoiggp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsnszxf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciekfjyc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hpooxspf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xloczasa.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaetxvj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wswtussc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfucqry.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqompxr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2apctqtfs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xugxxjvo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsdtufs.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtpzjpn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dphxniiv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2smmlnuez.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeohmgh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvnrrew.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qoexoing.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tgszjyyg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuvozjy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2noygdnpx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyfnuai.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2awsvbhem.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2afuvwisl.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2poyyyumz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhemtqa.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrcqkcu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hiodmlzr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyofwpv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmylysl.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiwfwwg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2scksytuj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpjdyhk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2onxccypy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaifoma.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2znpisgmd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2aqruoieu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dfewxdau.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kggariko.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ksabxdlj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjnqjrx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyapwms.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nluereyl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjbfduc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2srioyhgl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxsjjsp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lirxcktn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yedhylvi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpfvzfp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pajhldia.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2fellwern.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fiubkhsr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvubzgy.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ujalinsj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcceoah.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2flisspqk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyogvcdx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2awhxrueb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2stshctjx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2apuougns.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcbwhsl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpryrfk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2axuivizw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2pplrqupl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqynyuq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzqtemy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpfvdmu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hogcekjq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlwkflh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmnfqsu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtnwfpq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bhquakfq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfhsznm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiaguff.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhfxeqx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjloxlm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjsseme.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kedbgrml.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2eebfzhmq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyscjgv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqklrie.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdvytvv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsiragh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2bllztyov.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2insmkkul.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bovwjfzj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzukkwfi.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfhhysz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2obekgzzv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfnrnar.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2aqktidla.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pmokekyc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjwrtgt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cigqqlnd.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sowypmag.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gnphgepp.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaovtlg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmnoepg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jufrligv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qguygvby.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ibspwigg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbfkprt.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tecpcmru.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2njefluoi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sakopoqo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kycjdmik.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2newpqmew.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnipvkw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2outqsfak.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwgbwjv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcpojos.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2icvdlfcp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qydoxrzd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2laeygiff.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xthvfulx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2czhqigbj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wylnwtrp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vaprhpfh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2owcgxoey.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqhexbw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqgwzss.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjdkciu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvijywe.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjcciag.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlkcisj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ntawmnog.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2aswqkliy.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbqbbrg.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ghobxqwj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwuxygf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glfgteov.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbljvam.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmnwabe.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmmpdee.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiykhec.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2uezkwegu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrulvir.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kimqzpuq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2evafpfdn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2oukiiuwp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwpcexm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbvccbv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2iewxoffx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvpnfnb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2kunaclhl.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxyhwrx.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2axgfwuqf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbaediv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzwbvmz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtyxkew.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2crlkghes.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxlzely.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2owvpqlsh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zqodpteb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bebxtquv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2abuhkvrx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pybfrrtx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2huyqldcj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihadbyzk.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jraeknxe.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyxklgu.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pnecrmtz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2szzpzmuf.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2mesnehnq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2llxsjvzp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2oodfsfkn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbiamjo.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrgdxcv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuzdcmb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2potnptey.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwdavri.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qorepiym.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzojkqq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ukregodi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2kfayonaf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dumfgxxk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxktyzdm.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ipctjkua.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2oekfxkqa.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgrsvua.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygncmjds.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fabksuky.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2prhfurmp.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfisdzs.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2actlezti.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnsbhfn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdbdukd.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcetjhl.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2aloegkfm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsocbjk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2coooxmeg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpymvxc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dyupcusu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vowndnck.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmkfyxe.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tqegphzg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ubslxuvt.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2haibcokc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziccyfwl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyykgmm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtccjpc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yokxaxhe.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpswuccm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2uordcqex.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2uljtllxv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwdednf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgrawhx.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2volbywvv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfniddbz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcgrpvc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnaiwkse.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcoczwc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ueftodlk.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2idufqcsu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiuopfo.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtpryry.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2sznabpfk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2toiyzmlw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2srnddxrr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsfisyg.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkzyokd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsjwrrg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdiyxiq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwwnyzv.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2apwahdxp.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2trwdlqfw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbesezos.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2fabskiqk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbsruqf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zincuyec.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zergfdil.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2eahyrrwo.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgyaixr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gswzojgp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpinorm.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xluregxt.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2atsvagrl.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgrwfzk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhnjgsx.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qbglbczy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2johevsyt.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2obemiork.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkdhpzy.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uapdkoei.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbhyysj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yavxagic.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hexkhsug.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cylkrtca.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnttrfw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2slgfeafj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2bggaibrt.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fzripuoo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hclrvyqq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jyurqpoq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkumocx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kfugpqwn.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2pddjqewc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2myhsibge.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoclkkm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ismlzhcs.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmchfxsl.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cttwijbx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdqefth.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2esrifkvv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrxokam.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwszugd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyddgwqc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gisdxjjk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qblbeorb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2epdshncd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qipszmch.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jiybmlxy.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2bdopcxgp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2snvcucjp.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vrofljkm.html


<!-- 参考信息 -->