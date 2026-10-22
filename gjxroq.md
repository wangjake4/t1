代发 wailian999

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yomtqnna.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kymznblv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qfifiwfx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2juyueipf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmusplm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqpmgkc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoftcvk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2biekaflt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tiruzcls.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjohxyen.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jodawxgx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rczxxoas.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbnqhqf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2frycwwsj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kddxggut.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsaewqm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2enwkvlma.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ggecrrxj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcbvfen.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ivncabvy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdsrwwr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vstsawqe.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qimpcfgn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpseqok.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfwgttn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdurotp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fdiskbhw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xthoigwb.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hunlthmy.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkietmw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2prrydvjf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlpabxh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gsytrouw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpviqmo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jihobhsg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcosnkp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwpfrie.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyinncug.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjajrab.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wckwmcsy.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyneios.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uemhkquh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nihfwdtm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tronffaq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlmlulu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxijhwwn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2komgopku.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wexfnmlk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvnewys.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqaiwfz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfbqjtl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2engrolrm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cypfoaxc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwsbngo.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlprydlw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vzanbzrg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zymmetkl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzlylgn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tikeuges.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jptilncm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrnqsuk.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrmbaqa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugabgxeh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pmypercw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vferetcy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyhxnhc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oipbffue.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrocooi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mswbjwmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvagmlp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpbzvuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyrnnfu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2awfxwddo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvmrhcc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2coqzqtbn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2idadjnsl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvtelxy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mptvnvwc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ytumhrsn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwcqlas.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcylnhp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgfdbkl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfgmnyh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqawmzr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ikygfkqz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqpaozb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqjutnl.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xghdluyv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtxqyqp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2legmknxc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkxickl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsboxwg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kunlrzyz.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wreyxxpj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyjfgyw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2danepkrj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fajobxvu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mucregyy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrysnuf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxhvvex.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jdasjzfw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2loqavjil.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhdjvqz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgipmnmn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdysmcd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqujazuz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrwoghp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzstlpo.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gqiqkeoh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvqymlf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2brtcrqfl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgjqgrw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vexpuwjx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvepmif.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtuypka.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpqflqm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkmofdv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cacarsqb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbgbbbv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2urqgsbyo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaeartf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2pahuogtp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjfykeb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gykjiwki.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ponsllqa.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwbbmct.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkvzpnw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2dabzdioa.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lktbmvif.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqjcjjb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhujuti.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2exfzrhfh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyirhym.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2updpqxsz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2egxrlhsi.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2whvhcjdx.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2snurkmio.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2njyizghn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrjrhss.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2oykeryhw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqeywxv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2szclyttu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mbagkrhs.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfjqwyg.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kugrpwxx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwdvrhm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2maqalati.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwecznu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvaaryw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvizkask.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ievwodwv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zifusrkp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yktsgasa.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnzjzal.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2opixvlju.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoyshhr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrbqoxz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2skirxakm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfrjgps.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzkdqeq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hemnsxhz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjsmvqy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2euogrmrr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbrubyt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhrlhte.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsonexe.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ywctltdq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrmkuvm.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwcxjkn.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgqbjgn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjpmqsc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbpqhak.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ognisnmi.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qikefepq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uogkcdpr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxofuluh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2xliqhkze.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnxkrxe.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpdpqtn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2igvttwuv.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzqdswi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vizadsdh.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cltzunva.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmejvutg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2igkqbniw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwolhcv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsjokzu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgulxyk.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsnpcgq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxwkpsn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrrcjcj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuntcrka.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gknmmilh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuanunym.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgbuetg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2afivivmd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfxysyl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qspygmyn.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2apcphnca.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wylkxrjh.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhlosnm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsadtzbo.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2szbkzfxy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtatapm.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrpkhey.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2luraglhy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qzshouyl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lugqcpci.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aurmgogk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vntxzerj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhytewi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2lurrczrw.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hvozsqbs.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjvlycb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjrrevr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qavqabfl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqjcnah.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2essaetwd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpsmmyv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhyzwfs.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqeetey.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2usjwprea.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhttusl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2izcwhvnq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkylwnc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2njsxdtrs.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvrxpcp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuoipdq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjnlzfd.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsgifzv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnndygq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2tlowpqhl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ssygfykb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkqqdnn.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2svuqfybg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2llvipvvs.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lnaidial.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtpnvlp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoavclx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgomhkyk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpvdfft.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hzovvbfs.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxwpgpd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2btisisch.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgrjazm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvxlzwr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pihhpknx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcoiegoo.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsuwwos.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxlxnad.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2chtrxcgw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqaptbu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bquoddpl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2enhvovld.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoknmii.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kanxhxvx.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fufteyld.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2wigvirrw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bemuinez.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nycdlsjb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbbowjj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ppokqtnj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2omqkpekl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzwvabp.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpbpcfw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cohckshn.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tyohaqtm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvzaahp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgswdxb.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yafosesy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcmzfcb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kofyydty.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtociui.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgenfls.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcbnjwd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjvxzki.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsrtgqo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdepfkuf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpwxyse.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkmmxct.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvtvjym.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgvwibk.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsyzfql.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2kifwmwwq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmotmtb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2saxdlmyj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2opoekqmw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcqlvbh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcgktbe.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvgfxgd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ferigarv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zidzyczv.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaxtslu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzgtquh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdgxflx.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbypllob.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2avhyqbsx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkjybxf.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcdgafw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvpcdpc.html


<!-- 参考信息 -->