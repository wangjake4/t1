代发 wailian999

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2utfiqyjc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2corotyro.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2atyejpnc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xecvmhdn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ugccastc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmxqbfn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2znxanqaf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fslnpuev.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkpjenk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkstfulf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2eeipdzyg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqtlzfj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkftnzs.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2msfodpor.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2raioxofk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bryjpezq.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yoriwkzl.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iozdjouc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2txbaqaah.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdgzmck.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ceomfyhi.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2otiicfpw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjulifq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2skmxvzrt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2umillmqr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhmhugy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2msiftyul.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjjfedw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvpppgd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wppbyyuz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2snpbuyfi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2slgexinc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbwwken.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2epgknmhu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2svjarfmq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zwewarjo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfblnfu.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmudbja.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcyqnxv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2urvfwpdk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjdbogd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqkdfmn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ysswrsnn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ekffsmcr.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvihaks.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fzchsqlw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ylceebzk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwvvtsh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqstjxn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwlneoc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsvatiw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnxfsgt.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nudgwcwu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akygelvo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ycclvave.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkrcetf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnsqwvd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwemriuw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjqoycd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qljhbidi.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoxieaz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlsxwih.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjwcpee.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nugwbuwi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iskbajij.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tegmtang.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzwktjo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyocywh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ikanggua.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzeqnji.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzgqmfi.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrcdcej.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbymrhzr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcgqcgo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqmyxal.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmmtqxo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ielpxjtj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rectiwhe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uytvcgjk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfsqvzj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ueszpnfk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbgethq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gciuqjyf.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2awpkoaqb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbonxtc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlcacso.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2awbnzpmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hycndopd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ihffjttt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2phcothkc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtysasm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2duxiokoh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwngkng.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2awrxuvaj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hyahjskv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlxxhnv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpxknfi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yitsjjwu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjxplvd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwtjcyj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhbraij.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqgoxgq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tiklhbim.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2drwfcmls.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2byrsnpdt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yngdrmvh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mdalnhqb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dccgffky.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2crwnpddr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvouoim.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlvycot.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kawdeazf.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ghugjigy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2exeoesjs.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cfawmfnt.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2omivyxky.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2oddblxkb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzttrupv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tskpvqpm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiedqmj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2shaoxtas.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2adaqgizy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxylcmb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhbhsgv.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtzzbnd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2exqiptfb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2eahxnweg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwvasut.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpbkeiz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbtdqyv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpctlcb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjgnhrk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsrzlov.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwhrslj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdbttky.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuoldle.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2viptpcqh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwuwaoz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvzczfr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xorabusd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2aslifenj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2oiethvwu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrwkyui.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2acugcrao.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cwezukvw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wwirdstu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrxzqvj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvrcyfn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwlibko.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrjtqvb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvqwmwz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2opnbkdwk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpvxttp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjjlvec.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2aokpqxgp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2mifgqzxx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yurcwwrd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlidbtza.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbridsb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqiwrph.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqvcbrx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2afjofuwe.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwtrrew.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xefqeipd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxxwefc.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2kghspehr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjnucwp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvkdwgc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gajpsmja.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kzildzsz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2uukhmhed.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvvnmrt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmklsfr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdyvpxv.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2czxatkep.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uesmuxyw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvnegdr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdffdnhx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lleobgfr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ygogrhnz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2shmervcn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdqssyu.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoghqxj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wptozjhd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vuruxeqb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtgdxcj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ykheisjp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxysvzwl.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqdfisz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2orqtmgjy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2howbgacl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yocqpvhd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wutsfzcj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsjhjil.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gntmgmbk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2suspjkee.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qkucnepn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdztemd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgydqkxg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhogcpo.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrizjkn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gllmwpig.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2igcrzpsk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmvtkwz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzxanki.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmgnens.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2siuohaaw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfyalfs.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkljese.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gomnltcq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jydaoufo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcjneqv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtnvzko.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2iryoffsd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ghidmagz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2btfpjesp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqdkucu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lozeacld.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdwftue.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2llfcswzu.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuqbknl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxtmumj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhnmnfc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ltatlavw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fonmdfqw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsfrzcq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvenwkw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbpmcxe.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ketslodk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhwumjb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2anrokexw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lemoeyyp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2erxmuqlt.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnqkrtm.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkzdoiw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgwlirv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ujofxzwc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2afiubcio.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzstxft.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2djahnhpf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2txssastz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2yucymled.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdulhiq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrzidyw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2prfnpfwi.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2gumbhrzf.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgorljv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbeappo.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkymsej.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrjcowy.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjvwwgc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pywpjxnb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdvbsmq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2yixpoket.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxaipfm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdymgpj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvvqqwv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xuewerwb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dzivonmo.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2sygcpqxo.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2apxghloz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejngbjkf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aoboclfv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuquwcju.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfplowe.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2sommxixe.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rudffbqd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2knnlaxno.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2drvkuezg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2nwufqnbb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sawyjjne.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoohopjw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbkbvpt.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2enbvjxtq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipztwzmd.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsdmzzh.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyapukx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwubmar.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrbymkx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2obajpomi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsxthjj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvickwc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2psivystr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvdojzm.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2odxxwsqo.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpfdpvt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwjripz.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2whptuyew.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxenoxo.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwayubwd.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2mitshcmk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2oopeccgr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qahusoxp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2egnzkgjg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzirwcx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrgieyl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvvevzk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2olnuakuu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2avrdcgbh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmhzevc.html


<!-- 参考信息 -->