代发 wailian999

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhlbitv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtuhzdf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmugsml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egvhiuvl.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgqmpiz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2joczdxzj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zuinlouj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2apancxst.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjrsuqo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmimace.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2huojhjuz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qjltbyba.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rekkzapj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxgaqxm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwlpegz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cunkyxqm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaqtrlh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoyussb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nsynneux.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgrzsrg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzajzei.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pykiuoxf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsyxdhz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuzxotc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2esjyvlwn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qusqgxbh.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2umzzyczr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vppybjox.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bgljcipl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fljphyov.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vywqpono.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrncjzrv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxxdvrv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwepxcc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gugikcqb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2poeunxwo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wpamksbv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2duyyqjdl.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqaxirg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2puzjpfli.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpegcxh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwkxrzw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgymygb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2otmzibdf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pztwlwms.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiexeqzj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2smonymom.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjydepg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pynoybbw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2quwlqkyr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bojdlrjk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmndovme.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qthcpxgg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrayunh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gybveych.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfllnkh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sadzndsd.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvezwzov.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jucsania.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2awlczmsf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jejztfsb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nelcaasi.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2htwmbozr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jslamblp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmvzchp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2coivqvsw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pagjhwgb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzpfhmj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwbwqbb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfrante.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wauwtbja.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dakxpxmy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vwweodye.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsxjlqd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cofgmuus.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hajhvqdw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxwwftw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmotksr.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkpahew.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2amsdtnni.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iioymskn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnfxrkr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hniwnkaq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkoocqb.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxbzkqx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzuoxbo.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoslpyr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2abzambhr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2crczrwru.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfirrxi.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2exjsybxg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpqymxt.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ljezhkwn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkculxes.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmsqzop.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgwgixr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2inkxcbok.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyrtcxh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrkacdl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2drudvyvw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jchxbjct.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jafnbcpb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2swxmpqlp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzgxhfr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzruhtm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qqacpexv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrgznjl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuyzynt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnpwiwg.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zghfnoen.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jejvhpwa.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zyddwktr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsjbbmx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnwrmzx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fagywzur.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2beqxtjpq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhgaiwa.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yxihqcec.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvytdggv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2amggmddg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzkegxt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xamqvmfd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2byuhbcyc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzgzlpv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2izzsxkbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyygiof.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzondeck.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bklrehmf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdgikiu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsreomb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2iplmsear.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqvysdm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfxsfen.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcevmzud.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2svlkxxsc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hixxfvry.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hanqjvfy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrmuynr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uoizpeoy.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2namyshfj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwoqqhx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2obzcfjho.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgtfoyb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ocztmabc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2agjymkir.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2drvnxpma.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlmyijd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2phjhgqbq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2grqcvlmw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqivjhwn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkhqjuf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bieazfym.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnpsppt.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjpqdtm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kqaskuds.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2peyqdgki.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpjqxqd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlsrzfg.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2snncfjvf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofytkgmu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oxognweq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkueosa.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqgmebp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoejuxb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlsmals.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2imffhwki.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdpoicg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2uquxfbog.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxjhqne.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hltiwaou.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjbhinr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpxsqhb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmyptri.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbmtoup.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjdeqyq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2echdfxbd.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qtellqtk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2plwobila.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdaktty.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wupmsoht.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfsomgx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nadpvxzb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcnfugz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gfunwvpa.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzchsns.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xowzvadv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vacpwezz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xatrowfa.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2soglffla.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fodbfjhs.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2evirysiz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoedtml.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dxahyojf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsemkoi.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2apjtkzmb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyufruw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wveocnug.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuyhrqt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnhxrdi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhwhmsi.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2blmfgtsl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2iyruxmdv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cipfgqxr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlreimw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdigvxb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bznxpsrd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsfohgy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2swmrhbro.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sllvsmrs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2yizobrkn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2chburrpb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mthdehra.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvoqeer.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtefjosi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2emxbgeon.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcteehin.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hlolsczb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syeqfsbu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mricvhem.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pxepgzum.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcmlwqx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2csjdefhq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcgqgdf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlnycwl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbbnqte.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2iqaekogv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwrspov.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvaatof.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlkvbzc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdrvenw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrmlavl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaypuvs.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wghkfiev.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2iejygpyf.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jfteuzce.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kypfyflq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuiygqc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2krvewekq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tveirjif.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjfwyoq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqxquws.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjyagic.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2yleokypl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrctmiyf.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyqoiti.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2axfqcvzk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2vqplxezt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2btssggpl.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mgauilpr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgknyje.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rneawksv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcpiekf.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpjzprj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxeezdj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2shyjduns.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaqbzke.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnwitcu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwyvodl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnvgsbd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rucvrbqa.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbasihp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjcwitk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmbhtle.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqdhflj.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kezzdwmw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aioqqjoj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rybdxyrw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjsuqjj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2meisrohl.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhgzjzj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqqdxfy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtnpmmq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsibkhk.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxekvyd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwhfvli.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqfsxzf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqgapax.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvlccoe.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdxljsa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2funlnzlu.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2idnvkrrb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2witjlrte.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhiwylz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2slbomkqu.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdpxuwy.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xgupzset.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2afbujpdt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2uytkwwzq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqqmwjn.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zijgdtlw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnmgidn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2edajnbfu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzyvcxl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kafibuew.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoxybdc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpopizjz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2crsjfvup.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wdorqdin.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2blxnirlj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ecztaypp.html


<!-- 参考信息 -->