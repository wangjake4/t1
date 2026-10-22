代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pepfeulp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cragyzwf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaupkuj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxpbove.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2thouqmdv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2poxwyoya.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2upgasmrt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sflfkplh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gqluheie.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwninje.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aajzyosa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2icfdyjue.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2djfzyftr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkpelsv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxsxtdd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rhawikjp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ragrqquy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2okcswtgt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xefxyslr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyemqjr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2geefbaup.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lymxwunn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyagdjg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiolydoa.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyinmmb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdojvrh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqclxapk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgdkobe.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jncaxttx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wotpvtat.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dilgqolq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2thexipsj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrjyicc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgobjpo.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pblavqkw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbofbkut.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2extspzan.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2esloxvgp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yvygnxes.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxejdkvz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdhonid.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwffcdm.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrnemut.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfleaay.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bjovzuce.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvpshsd.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsprdjj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vppwaiaq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcnmkwi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2btokcigv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoausij.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zvazipvw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiiyyrp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2viyhtrlv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ciatbfqv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtaipsf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2uekdvdmb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2inyvcrzx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2akzanioi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjjrxpn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lltveeht.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbpcnpd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtyewnk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2alfxenwt.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwzqgko.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmadswy.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2prtqgohx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2onwgvtfw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnoyjov.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbekusfx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcezbpx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gigixqcx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkwoftj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvkubrn.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjwfzdo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vxetnvsw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bgplpzqa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhnoayk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzeebzc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyzibin.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdjlnmc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqswlgrz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iruziuck.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkctctj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oncvioyj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnivewi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2acuqqmnx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hqakohvm.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lyakclyc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrwxztj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmtmnhr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxvehtj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmypdkie.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2orrlclpg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtxwjez.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtigqjh.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvrfjvv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fedsoaay.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2axibvnnq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbyuibg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsjsxee.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpzjyku.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxfevhs.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzdzqnl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2egplnwjw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guzxbkrh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuarihr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dudwvczh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oomsocwu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2batkhtwn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgniefct.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2smrseguw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsvzzfa.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uettdhag.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgjtaac.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzbwocz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhmxghv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2moxzuxli.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2acbwhulu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ejegqwjt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2aliqshyg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sashyigo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsgkvaj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cdltzeyu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcowusz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2elhnbwug.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbuvlvb.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2btofdtkq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvornsgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsqbqso.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhpovyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyzsats.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvtmznd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbyiaut.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrcqmye.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlbdyig.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2clgfjiqa.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbylfctz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxteotk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvxvthg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgfnmie.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvelzyw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeqtrzs.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhfyoge.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaocaoa.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zowmhbcd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uhblbqay.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2eydxscgv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2izaydimy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2spghicyu.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdwlsos.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fcutsrso.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qjekrvad.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxpvpap.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eegwkkzu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sttaibnt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eneuepci.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2omwlpmkp.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xposxuvs.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uplobpiw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2laigadam.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcisokh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2lggfrmbe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxuzpfe.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2txzyixez.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2thxnaavu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnupcno.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcztenk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ykacklys.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwrrfwt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vkstpqqv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbsnwgg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gojigweb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmsxpfr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpecpzs.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfubcar.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2effldfyp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpkmpzc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkyrcbs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzniiby.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2clkkbhlt.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2snokythb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2reqmtadc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtgxxkt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2otyndpzp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxkrmmw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwnnwha.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nyztcwdq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkmilyz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkjuuqe.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yjggmusx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjycbam.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnuwbmu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjogmru.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqzhnbd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbojgkb.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ygueyeut.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbgqhei.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fftduxwr.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tylqadho.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzingzq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ounrqfwm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkmpiaq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwjnulr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2eadgsfvu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2eouidmnp.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jllhwzth.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpwtcqo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fodpsirg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsbvryu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqwzfqt.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2foeousaa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2goqkgela.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2exfbyqlb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfcjmsd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxueaxjt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdnpfip.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwazzrul.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sfaekulo.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fweywznf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zogysmdy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwvndlt.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yuamtsop.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjfiibr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aslxpzct.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2oopyfhmk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjsqadh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psakpqsv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sosktdzl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfhsbap.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lemhbbvs.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpcwqvv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfurkhx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbqbddy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmlebsg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2beurgjjk.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2utcwvyqz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgtqeay.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dtebenyy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2wulxldxa.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvspzaq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpkfnwx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkdnnow.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yelcaymr.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zakgyvlr.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjlvumm.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsggumz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gewldazf.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnueeab.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jowqmgdq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2beotkttt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnxvvsc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtefwqb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmctyfj.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaffaxs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdhhyko.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ghclxfqe.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmvhthx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgttwht.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgljkeb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tobjortv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxczpktl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2cqajtwlh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfenihb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2aaohprif.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkzwbfw.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uitkqppk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2azehiwke.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxgbgok.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcacyhaa.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyfdvrx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ayifoiwx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqptcui.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaanida.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdhrppn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vsihhhzz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlgyttu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2zptnnnni.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dlususok.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgbtozm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zroftfry.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcnygae.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqbqnvs.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxzlsom.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2udiuewhq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqyvdfm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2njllcktv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2duvwiflo.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtiqxoz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2psimojqm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lzruqcgx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2xidvziuf.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoiqune.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2tnglvyry.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2redxcyrw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lduyjudd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2eihmjomx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2izbzbfmv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmqyddk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2grovofvz.html


<!-- 参考信息 -->