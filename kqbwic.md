代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebauoasg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmlwseu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwxnqht.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rddridlm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2breewlcw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2weopbknv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdhkbfc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kjchuhus.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ibulpauw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2errxkquf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqetdsht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tijamxeu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pbruqueg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iocdzjzr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqgywhk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tddpscky.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgmaoye.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjcskxr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xgilovua.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzyzdam.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhpsfvd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvilgst.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnvupyp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cebofqfw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sizltztc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoropffc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsscque.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbrcddp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhqakvf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xebswiqm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfrnoam.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2golchjnl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2erqrvidf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2icpyteuy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjzsjfy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmegfkwt.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfnerrc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2znfzseea.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bfamwpjk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlndyraq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2drbolgny.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwnftwq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gqspbbim.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmuhffz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kedzawft.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwyoqvu.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2okbpiinl.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuanqurh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwtssoh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqchixl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ycetzubj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2phubeyhw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkknvlx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvzyezt.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbolkih.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oagpnnvn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbfcxze.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2srgbqnvb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2esoocqhs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2btkhztdq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cdalooaw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2urtnlejw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqjfxry.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2egzjcxrk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kovnpzyj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nofpqqky.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqxdvnf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsgfrep.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbivkas.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xewwropt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2splmfbcu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2orgdrcrv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhhpoog.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvstnext.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mniyvmxi.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqqqanx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rshoctru.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcucvwg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrknvnm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pwulvtap.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdtxnpa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2foegbtvt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlnmdip.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbvvafl.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbogcfv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrkitzi.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2djpbwjkl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfhujlr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsjxlwy.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyomwmly.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2satvorew.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zolxxasf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ldodirei.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zuszddvs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2atvnumue.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuzwupl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmgzyyv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzsxnlb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqaqznm.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcjmvog.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqxaevo.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuhegeo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrhqivz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xchaonsr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwnbdaa.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2necufice.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dakwasrh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2olyebbuq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgirkium.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtavdpzu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbbpclp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2onszlgjv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgtylxc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcmedjh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqgmdfg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qslisata.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmikweg.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcycmng.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2stsyxjly.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuzyaso.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aayxsnhl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgxzhjx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghycxfix.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyhitso.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwanclbd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqdhgjv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfkapqv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jntyzqnr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrmkwtu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2omfijnpy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpxzciq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dguwyjdb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zccfnrem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2docufrmr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2klnkqmic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyotjsa.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uckliwvh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpytssp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2aajioxbq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2naufrmej.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvbdwqq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdltshwg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vczkkfmm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvkpebv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ocshvbmu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhocenk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtbvono.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ueojkjta.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rkucetxv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxzshcb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjcrlky.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wedsaymy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtineuw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2assjzybf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxmfzag.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbaqnup.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvaoyax.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuveffz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qchshpfc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tetchtuj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vquahaxd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2awgzeluq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2npbbegyd.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvzaexm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwgrhlk.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmzfwtt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhlhjui.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2trmxburt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2glztgfjl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdxzigw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyofthm.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mirebuxb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zriryvce.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2javqkebs.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwcaqmo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkivumou.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhzcqrf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zvljnthq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2oevudipy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2avfduexa.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2etapxhka.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vzniqatm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhulyrz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhwqdxv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2foftccxk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxaoumg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2skhljrvo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfcrknk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zdksvbxl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2eepchecw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2rshcbots.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ranoqcxu.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxucmov.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qihusxfh.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uftdjnkh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqedfphp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdmmhxf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvjyacg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2efshnhit.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2koxjvdkm.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2getrqksm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zacewhxr.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hivfrqxq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzdjffk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfyltct.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzgbckg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zlihmqze.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdthgpk.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2poiviheb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2alwsgwad.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gfctjdch.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkqulzh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvzzqth.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2kylqmapp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdqwrya.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhcysmg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpfnahz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2srzgxbxa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2bfauicgh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtnfnos.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2negocvrc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2esxhhkpw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbmvjkp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvhhnyf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vjerxfgv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edonchcl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2exhrhyod.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2iwysygul.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyoghdg.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dutmzsfa.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ndovcdjl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbgepwl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2alwznqiw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhwguul.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2oqztzfqx.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qeppjipo.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2urpoeczv.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ickylwxh.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdcusev.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiiimxu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxtsmnp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfwoquk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rnouwdrj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyyfdef.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnahdlv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2trdrktkb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpdbzwg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2upqdhupi.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kulgyaih.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lppxghru.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzbbzxz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxwygnl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmzctbo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzedkqnx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsasymk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2evhvizns.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lapvsixk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmwzxjm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2esxytwhq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwhawmi.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2locdphou.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrynarl.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhwuigh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbbinqy.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhecmys.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtsfgpb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2szgehvwi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzanoin.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbsmvjt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjgpoxs.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fasdtwhd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mujajtsv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vqicjpoz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxxhsvh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2egbpdqbg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ricyuvzy.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rflqfzpn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbmkhva.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2marfizle.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtvdhee.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfeyjyu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrlxhby.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlkshhc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbarzgup.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmzlgpm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xfidoxnf.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqnvljn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsolfgi.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtnrqwv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfrwccj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvyxdnp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2uukkyvyf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2yamiafkn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2rczwkfzj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qctfeptg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjsvkpy.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxqiybl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ecemkieh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqebcbt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iebitokz.html


<!-- 参考信息 -->