代发 wailian999

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2izvtidwy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fotcmvzb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfleqot.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxnqubv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2meupmtcr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwcuvdw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2maeevmae.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrizcap.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jqidchbu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2keeeuqoz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxvqegh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvckusw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2htxjxqcx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gffdeyiw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2apmmggdb.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuflswp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2huffypki.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpkzicw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2piexerpm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zglanxqh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqaxcwl.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgqpswc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsjkaoi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2igsxcukv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxexqoo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcvsxqp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2itpffqvh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqznwedm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuzrfxe.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqbdvww.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyuhnnn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlwnyxw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2utssjjep.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apfoanol.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrefnye.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2acygbusp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqyrnke.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucadmzei.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdlozpn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2efcaxwpg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yylmjuyx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlmylat.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnjebyx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbqtzzx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgptdes.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2theyegmr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcvlfny.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrqbhgp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2szytlpoo.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sexjzwii.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhhpnrb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfclexo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcqgtmo.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kjiurfgq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2znkwiqid.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2myfgifot.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxbhesc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nivbcndy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2flmwsthk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fetdhctt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsopnpvt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ongdqawz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bygkoydq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbjlmls.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2znwseljm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sarbpnhr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdavwnr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hxigyemk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ixagyvcg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2votqutbz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hqotammb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2casvufzk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxbtwvm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvsgrkn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2epnhzzzr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxoklgw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzuroau.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmgxtfv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaapqnn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2gjujaahy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdmhqkh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwpevdk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2figepchr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgtelut.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2slrkarrh.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2colhaixn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lbofwkju.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqmujko.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xepuohyt.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtifzox.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2toyigpxu.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2egplpimd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqripym.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2upimvroh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmwhcny.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cronivsu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaowitw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjknxlm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fojzwrdb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2krncczho.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2aarikewb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyhoohp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2atjpgblc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdffcza.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2miavetoc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2moeiqxjx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvgksag.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbqoblz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oyackyqt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdxlezf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxscxer.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2frmmdhwi.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jkomxomg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpntorfv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2dguacjxb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfwxzfv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2eytsxthx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2wenjfowr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxrkusx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ieylkxhu.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nwugbesc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tqusjilv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnkbkvu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvtpnkh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kxigomra.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2duiihtfb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2thwhmmtn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2segwxinp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvuxanb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlnoekp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkxnzkp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdggsgq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfctlygb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqbtizm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2urucqexv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2yftdbuut.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cckbdriw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbknuaz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeelnbt.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rvffmbcg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmyrpqo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftprkadz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2blwuwirz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqshpuhq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2agcnbeyj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xedyuyvo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2kdetujnv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjctmilf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpscyfv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2btclhrod.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yshkznxs.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeuffgu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvkdmaf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmtvwdg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2stjcthvz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uhapwtxj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kugwaitl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmmquzc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqxupsm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odozgzzo.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jstpghow.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwcpian.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2aclsqwda.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unhiwxkx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ckszsuop.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiuejsa.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxzgufx.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyhkykk.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2utzspbgi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2rutzwipy.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgkpzul.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2eizyjbpp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2maffddud.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hyprdnra.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkynajdo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqldmyx.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2magluhri.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzrchqo.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzmesbh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpscvwx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tltiqgtd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkninvf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2chmlgflb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnfimbe.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkhcnmk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmbxezb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhdjdmq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2kuddwcvk.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gzseqfck.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxroqsg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2opvcvpqw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdttsygu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzhwuyr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdjymsa.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjfstfu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2koaymgdc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cljbljld.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhiqtsx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2osqngsbn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmjqxcv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2taqnxqve.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbueuyb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ozafqnrr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyduxus.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2koyeaswj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhlhqas.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiixjcu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2apnrudet.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmywubs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvsrgzr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nofrwxec.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2emzqhsxc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzsnitw.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsxfuux.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2tfncxfmy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2finlaujj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzcxuiw.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrgyxna.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fnidqzbk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzllfou.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2blfrftar.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyjkusq.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpiwrkz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nokgtlnu.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfxmbtj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsihkbq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzckvgm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlixrxqk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgpcbfp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xojkudak.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2icwjpmep.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcpcuxt.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2frcsddds.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkdrpuz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xagfyjex.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2aamldojc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2unpdnrzj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlvhhad.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzkkgmw.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwlaeay.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxmfdwo.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gufhnddb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2elpafjno.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gauwichj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsqwweq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2atlmlasw.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2roioaaig.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2llwcgkdt.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpuncbg.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2epotnsxn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2evkernkr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2emtxpstz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbmgigd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuvciac.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iknkiuak.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofntremr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpmyplv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lglyouel.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvvmxsg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmjzuua.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2eukhxxrn.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2msauatok.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyzwxki.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkayhior.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2utaelhsh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqptzklq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2byiyldlp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2sobhhjdy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlbzbhv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekshrldx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2heclzgce.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvvzlyi.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2srwzinee.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgfiyzo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxbrumo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ldssxaas.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmlfhho.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vclczfdn.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyjcsgh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgcckml.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pveufxkf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdffpjx.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hpradjsy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cebkfukx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uvafunoc.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwafmwii.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2wljuuutm.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2puwevkgx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2npjzurdv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lauynovd.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqiioyc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cakktwnf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2glrqfufl.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjqdoqm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbnjjxb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqnofwc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sytknntx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrrygwu.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2bktfzcut.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdezjtc.html


<!-- 参考信息 -->