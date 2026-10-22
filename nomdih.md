代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhptrjvm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqolibq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2utmgoeyz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2thkhddpc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcyiyss.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ottmwvyu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtdcngj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqavofx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2celuvakj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zppiocpa.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nypeqgls.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrajwvb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrflyqx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2euydrshb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmxkbbu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhvhncl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpdkzmz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2padjddpm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2okfxgfhd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rapipdww.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrqrbww.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2movoghkw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rfikvkfp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rcynbdwf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lihyympi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrdtzbe.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xymvzhxa.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2osubslpt.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oibnyqxz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdfvkdy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yxigjbse.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohepajcf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwrtgmq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tywergcq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bukqgagt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppznajno.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoipsyg.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcajnmhe.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2omazczlp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhirjqsk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdpovzq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlidhdaz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkmwjmy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkgcwop.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zempyvpm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlajdiog.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xdobcdvu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsouuieg.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2caudcmka.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwstmwv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sotckgjs.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2stfvqzre.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nboobbke.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aulnvdqe.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaecftz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqnjlao.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsvfeho.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcoglie.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rfungsfr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwflhwdk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rieofgpe.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2koybqwpq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zygtccjy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsfiili.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pptkdjvk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfscpgat.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2znwtlhyd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dedhqivg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bluneyms.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvflzhg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ahujxqnd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvgcctw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tskghcrk.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwpvhgi.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2monaqpuz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpqtoeq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfleayr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjzyrul.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2cynhyplb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdnfxpf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqzsptg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbdovtc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2peslvaro.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nphqwrry.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtdyhoq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcuxxya.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yatusjte.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaqipcx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jizqbwyo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnzkncq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpzlwvq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwysdpo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cksvxgdk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xekseblz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlhmqvf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqnzbbf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjjlotf.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqsblgu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xphrgyae.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jouwplim.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2olruapjc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgpoyga.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2brptvtzr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqqxlyh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lmozzski.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2yszgokjj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2syrfhgqy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcgyrde.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrhjnto.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emmfeblu.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmranle.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqupbsvm.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtxnnqz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdgllto.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vugylnyl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxocpkdd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhpefil.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2weemdoya.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2onnjrgxu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ormfngcq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sizmxson.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uepzwrvd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjwieeb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2clevhwcq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcbqdeb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jddlkqzr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvbtvvh.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nttiegia.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhngylag.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2livssjfs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkeilyl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqenwmw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzfalxm.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2diqknygw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2btisohqe.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzbjpri.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fllxriwc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rdicblhz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzeafoc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2jagswrej.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2igaireji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqnqkja.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlzjjks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2earnkmzr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dslvaemm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2onownefa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpegize.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqrlwpm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkpgbfi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dczawceq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2flxgsnny.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaeopey.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ieykffha.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxfyvbl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjrywnw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hoknpqwz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmicmsk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrijbbjx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ghljebqg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqdtytq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmpjwgp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlrjvod.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpkqrdg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwclwry.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ijulvmbm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwyrynk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ayurapan.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydolofoi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwhzert.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2blnqewgu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2njcmjafc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jitfynyx.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlapzey.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmljpjup.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtwkqza.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dampvejj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmhvniy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuiaojc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhmbfbt.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2eybryfzq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gluoghqp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnkwqaj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhopbpq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfjrtys.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhcjclj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcxxvyc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmavwcc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrvwhwg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2osdsbsfv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2esxyloky.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2habclfhv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2angtyklk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvnvucw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2swwffaat.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2efiyatyk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fydeyspz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcrtbyw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgakugh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmcdmwx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mixzvxxd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkllpvt.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2akqopwwf.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2glzgbpnk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgkdhde.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2htkgsdso.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvfmgsm.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaedloh.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pofufgao.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nbibphun.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mibwyokb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wemwhoik.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwuxldh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mculzqbm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypirozsw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wcodmxbk.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2txtaagoc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdsdawo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2iuduanmj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkiwfvr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rfljadzt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmqtear.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzanjkg.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2crbuwxpk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfjakrt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kcicfsoo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvmxnrd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxzrzyo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bepfblqu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nsaausrp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2btckreek.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oehfgfxw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezewnwtn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2buggiwfo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdvsdgp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2capvlnzo.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrtqknq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aoomdcgt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmbcegy.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvmtzor.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnfatjt.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbbcrkz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ogaxqsed.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2dzljnvfk.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2smtcqfcm.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcyetvd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqqawlo.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2todhepbt.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwetrlq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2umaxyisd.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2wiigbtab.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jfttvnza.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwnqnpg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2crywolqa.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdtgkwp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrqsmho.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nprihlhu.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkjqobi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qejfpwji.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jiypknod.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbxcnus.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpzxqvd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpmhdco.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpdpnzc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ambmbddd.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2afaomdge.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhjrggn.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgyqnoh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bstjyrmn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2stvhidmv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbdceex.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ioftfgxg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2zogvnlcw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqjpaef.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxsbwsy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkgekrq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkarzfgv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2tryozkff.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2syqxoddo.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2puckkqvy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyopxyv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2svlqkcts.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpkgtsx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kktyvijo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtlqpbl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cetkceqk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kidqwqog.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrxewub.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2brrvzfwx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbjwuce.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzulptxr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfjsila.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2bayljaal.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcjwoyj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lyradbto.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wgygcxbl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpkihgs.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2waowjqmf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrhiktr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxqndrb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2thhiiely.html


<!-- 参考信息 -->