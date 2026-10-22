代发 wailian999

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lanowkld.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rinvfikw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2elqglpel.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyjbfdt.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrvckez.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wguapmtj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2oozusmgn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yinuozwg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jzssuffp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdemptz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2caeaqeid.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlofcuh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvolnzkg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bsakzaor.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwwnjww.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2iprdyjku.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2onoifwgi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuzhqld.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2chhjexgz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqqmoqv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvucred.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdxnncs.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoxvzph.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2utdhvdtc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmxszgl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhjddbf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqpgdse.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rlphkmdy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsiqnee.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbgahfh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmaewdo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2aehjdwwg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kikfanbv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2timepklg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjspupiv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdxbggv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qzylwyma.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnytroo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qufnlywv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgjtggd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jicnyfae.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lslhlmup.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zeinxjcs.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwzkcsk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2chxixcjw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whxrromv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eyywelja.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcedvbx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyhfbdb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lybwenuh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvkkxij.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsxmiab.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2barchrsj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lauzjirq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkczpks.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rfocmvow.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfupycjk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2weyqmygu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhjasnj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtgjxdh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkikdcy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tzijatlg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2elgxtuwf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ibelcnwb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmdqpik.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdbzycs.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uksligxu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnaexeo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2paytaded.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2keljovoh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2izzyqcos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyrzwbe.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2esswqxug.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2klmoounb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dotqxaoy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrzjweo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tvisnuti.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2igstuais.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlgcvmt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2amgriycg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ladwqzaj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnleaadf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqdpmbo.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlammyqm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmgqsis.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2shtpuddt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjsuwvn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfeymfe.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnbsyur.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2etjnkaor.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pldqmrku.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgslsye.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwqskmb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyfsefl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyqsujw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qifqysff.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2efstpkgk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vibhkjng.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lczfpkjf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhnwjcq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2juhklajt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vveqzxst.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeouiqu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlzilbd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdaclib.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwnrvbk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uloqleba.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pavqhusm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mhplglrb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovloqvno.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqaozba.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeluwsz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jduqbboo.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2nengdghk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2uokqufcb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bchfwuya.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnqfbaa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcoygpb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwuutyo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hipyuciz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2njkyjafu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhalrgnj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ulolkudi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xppjxghu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rcklgxmj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2opdzbzat.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pogfueom.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bmglanma.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2geaafzwl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaupsls.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvuxspj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2clodhawh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwadfly.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxlsdji.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2swtjedfm.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmeyjyv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxipomj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzgvylm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ilicsljq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2giszskjc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2islbtscr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoeuavy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlrxxwq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzzzdir.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmyzfur.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nchgnxxm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qareywen.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wvchhqzm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cztpnsux.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2kihdlclz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqidlxm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnldbjuk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bszzvpss.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvochxq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqfmuof.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbxbrpt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jzctkmuj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2beylwwpn.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwojmoh.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2duoyswld.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gegdnqgl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vabfckhf.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rbejktyv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2smwcjghh.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdnunwf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2mollnhhl.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfxahmv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbqdpod.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbiehzt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2zggmfrpe.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2csdpgyrr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpouanu.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2iogwxkmj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2euaqzbqg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgwmijl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2amldrgip.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmfilyl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjgdcqx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqbkmvv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbxmnyi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2emtodzog.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2imiabbrr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaoxflm.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pofyxhmj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dnymnyzw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuvqqum.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2uqegatxp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdtutup.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdjlpgi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2juxpllip.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tddswzwa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fryjjetf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2irabpujl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uybqszwq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmuopbl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtlnpgc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nynducjh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxtvcil.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjpiumi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvmwmih.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2babjvdmx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxhjsky.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbavmiy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2msmlrctx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2dktzrepw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2omyhiavz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2deqpzmxv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvvddqi.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nroranew.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiszsylz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2betzfont.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2gsacngpe.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ctakibso.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xphyfryd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwsflky.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2dowktygs.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nylfjhkg.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2uycukstr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zlunxird.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcosbrrv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2dtevlyet.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlnixqo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsuqute.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fufpfmcv.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2spaparll.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrmovnh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dobidebh.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2cexjyppf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpobbny.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2inofrfyw.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqfefol.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2gfobbdcu.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fonhatyy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaeffmx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwlffyr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pajrqxor.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmdjwpk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kuenrhdh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fievppax.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nucvfhdw.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2trpnhmnj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgxhman.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmlygun.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2tvialksk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvqmmsi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzqylul.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sytpatpr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwffsabb.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rubxrqta.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjceihb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mvojyrpe.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ustvxiyz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dklilpdo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvrfnov.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhvkvao.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2orexmqdz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnlnvtj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdwaqgx.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2seknpdkj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fypdzakn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jpohpbpl.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjnymcs.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsrcuqz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjoaived.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dokakjyb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hygcbofs.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2afhmrjgi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmtscru.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvuhvqj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfphhyv.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cerdktog.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2powndunl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lykxqdwf.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrduxds.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxfcbrm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hejvglid.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zimqohpq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpvlmoe.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2xootzokp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyqadis.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lqggpwdh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbudyfb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tazmjswf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrolmbo.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qabarzjw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lurhltil.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtxqhjm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2denfddge.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sgusrhuy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpzrxpo.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2cabszmqd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2omdxhcka.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvdvyhk.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qyifbdfe.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2phqdviim.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylulcamj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yusqjxuy.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrimiocb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmcbumv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqmfgix.html


<!-- 参考信息 -->