代发 wailian999

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kirlgwst.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lonzsrma.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2boljbbbo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2sldklelp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2thffyjdq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqkspwq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcglvbm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrweroso.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2orjgwofw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdcnwrz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2imcxerop.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yabyakuc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnksqpjr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qccwuzuu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2omqczpxu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2aohhtvrp.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxnqkmj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvammmz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcwbdzy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2sprlpcmx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsqnlhz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2txvsoisv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mscvuqmi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjowdvu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsyzhpa.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwmylkj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gelsphtn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xsarjohi.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2weagsqnf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwrdcel.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2etrlkwrc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzxrsvw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2epdldzmd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlypzsir.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrrjkry.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mramcdbv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rrthpmwy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jixhhllp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jihdpqeo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqqwzxi.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyzwgrt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjnlhbq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2baexkhcj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeigmjog.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhqjoue.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jymcqohq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxglcrz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmkwujz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwxhtrv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yvoffdmc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aozrjrob.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2etpliogu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxeamxt.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjckemt.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyxlxhm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xizgbzjh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2afmthazy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2actlhbss.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oleemrex.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsrqjhe.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvszqeq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzgtprl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpulajcu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gdizkaaz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2blarnuma.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqywnbw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjinwvnz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cniusukc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqhmkjx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeeupwy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsomksvt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqobabdk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vwywussj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hrebqbug.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwfkoly.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2biysrnth.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfdycml.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgthwugt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2abscljqe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mdisnuce.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ytucybhg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxcjcke.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sniwiwhf.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hssishqm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzrttpo.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvktovfq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xibmaxtt.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nptdareh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uejlgyit.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkrocwh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uztoomoa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuledxo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdgsoeu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjoxtrib.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnuggcg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fovrlsmz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqsmmvg.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkbpikx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xyspesye.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tljadqks.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuflhkt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rntormdt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtupuss.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjuurjw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jgezfwwb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcueobo.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwwjucm.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlsbxdx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxebcuu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxwgxcg.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2frwpjraj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrzmzyt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rkamedtt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqihzyj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgftagz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2pyctnryb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2exrlzuim.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2pndkqbcu.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2flsrorrv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmputrui.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjcrfdk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwzzbbo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiguglg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlepfkhp.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ivepfazj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdzjjsz.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2plfqnrax.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pogpqzgx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvivzzu.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2iwppzziq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kelhmwxw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzvzjxj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2coocpbqv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoqewvr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjphmgk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jlixmmlv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2klttydwl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzpbfvl.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kkglwqqh.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqfzakk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2lllfudnf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qravjgru.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nsehscof.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2azpzoonz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqdorak.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjtylsf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbselcr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrafjnv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cyibcttl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbazbclu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmzewfw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvkmwql.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kvthncqd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjbqgke.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2czwwdbtv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2twtggbyr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zhiwtxad.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2rifxtbpm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2savowhgi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpgjlsa.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2seswisxb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suxugkmo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwmtaos.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzxctuv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2taplbzrt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2uxywhwci.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdteklz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzgxusp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yrujeddd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2diadfswq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hhajagqn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2teprleib.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwthfxi.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2flhcgdva.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqruqbua.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwvwbgl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrvjoif.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2prmmsegk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqarada.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2exudscrs.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zshdgtxd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwsosld.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuykzmzv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfqidru.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkjcbqf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrjahge.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuaiile.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwsavpp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbxlkbt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2csmigqes.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2masktwxr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxvoihv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2usfpqwkn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2upctttmi.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlotyzs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2evqrrqbh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ejairzmh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcdcqda.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2egkitnvg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvmrbao.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlnokgv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tozjqdot.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2stwjjsmx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjehqjbt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xbthazsk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgdpfkw.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqjvpya.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yebhsqfw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpbjiyj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpoqcfs.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xhropakw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2eqonpvot.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2froacrhy.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxoawxu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnttemn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2waijwopq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2airdksna.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2odiasbff.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2elimjasf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjyiecm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcvqokp.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvuqeil.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2alathily.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbudyfk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpqiqxk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwpzzuc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sazzdjnr.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2utggjmtm.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2tbivbdbj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xoopuqhy.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gauhegsk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2dochexev.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjvnmbi.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2paceqnrq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzmrhlb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xccyovpv.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pstgafnd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2megytflk.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2igteujsp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrczpqyj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2fahacmbs.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzswfwp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjqmuhd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbvwksi.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hdurlqgh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhemvkaq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2moiwxqdl.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sldwtgld.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhtrlib.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2obvhqdrw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zuckyjsw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfecshf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkpzeiw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtrxohd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsxkbof.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuioytb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2spwknput.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjufwpy.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhhdaqd.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqlomzm.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2uckkoppl.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpqhuae.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2imgegiwi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqvrbta.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdgnmxb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2eanfhqse.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2osfaoizo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bumdtljk.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbchfhp.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyjlrub.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zyinnnel.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvuqaik.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2frxasqnx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvgfytz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2plkrvmvo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkcqtaf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ttafvbao.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqohwzhe.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkwwhlg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2exzbhavx.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qhawccbx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrhnblh.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sesdtwyw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrflujy.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxnvpqk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtazwxpl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uugopnty.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cxubrwqv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hxupliio.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zizrrvpa.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbinpue.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgqmwoq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkaopwx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnffbmd.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbwndmn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkdegig.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjgailc.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2omotjedl.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsepjlq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2isdtselw.html


<!-- 参考信息 -->