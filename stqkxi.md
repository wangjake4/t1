代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2avbbhcou.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tvejoxkv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ouloriyy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2yviwmaiz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrezbvt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bambzhht.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2oorklumt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvpsupn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iscwdqxa.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnulcxr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kggoperl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rgesurzx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmofcjy.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qqooxsna.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuehhsm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzlhxwm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2djowzhnp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xontuodp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwdpfvz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2udvxltgm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fahcqihx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2latofgbm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfffnfz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixczcimu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gidewbif.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2obaedbtw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqofncj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2oliwdjlb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xerekzkw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzvlvai.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zrytctwx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmkosyo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ourqzuzr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2surnjfnr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfdfgjh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgukicev.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjfaqpg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxhonsg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lemscgsb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqotmxgw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2unwmhnuo.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxjmoth.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdouzupc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrygfrb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgtrtch.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2teplmazc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbnzfiv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjieusg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmgohmz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2spvckyti.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzvavux.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzojoki.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiokbts.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iafomxyu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2osmrvsmv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpekmkug.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsptgmt.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnedbxx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vjduecaw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2oududyhf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2usmvbynx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhkiqhw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgrfemo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhppxpy.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2srkuwmfu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtpjhae.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2izjznpmg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhnfptw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2brvyloks.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqooiyv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2etsqkzmk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fovyhqbr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxkclja.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwshxzy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvitanq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2myiuokwo.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xknmmrkf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsvacxh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2meiknigw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zryyqzno.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjlohob.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jernmszv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgkhsnm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrbpqzu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ualzhcsw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2clqkjicp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvzzzbs.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uakdribu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlssbndq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jgloanxc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyojbim.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnfmxug.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2igcyjwup.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqvithk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvjjrrx.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2osnzakwg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ceizegto.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvuoijw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2omsvzjyr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvslcrw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtqiurd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgktthbb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tbowkuki.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrhdfqt.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2utgtrfph.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yqszjxxz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lpktidos.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqenazcb.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqfcldn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhvvssf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwpmgjt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbhdjni.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cheiconr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzahqxq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qfefbdyq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkvtllk.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2plgxwadr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjvopft.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gxebpyfa.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqmwnmd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhhuscy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdwnjdt.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfviyhcg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnjlzzs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxmpxhp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qiutfdbt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hasazbez.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vjauwqte.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvupjay.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2arcntnff.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsjcqfr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mugspoyf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkikjmgf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vuclaafb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqsoahs.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jubmleax.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zezqchvk.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvcszty.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnsbmmt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aptkqymz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjeleyt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwjrcat.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxhuwyk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnbdbyn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmtfpoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbcbuoj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pafgizsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2naoguqpn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2znbcijrd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qswkkdsp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkzzada.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbwabjp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyhpyzl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcctwcka.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhcisur.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uhugwwrs.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvcosaz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpnjyfq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rslxysix.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoaorag.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ajezuvax.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvcbvza.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxgxtog.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vucsgukl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzskyue.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkffwogd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjymrxq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpfdnsw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbyzkvb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2euqnrcpe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjrhfyr.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtucgqh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2euqedggi.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hryhdtii.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtqogjc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2scaiirfq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlnlldg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpevogz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjslhwb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2aojmltzk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrmgcaz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaptfhh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2szfrhbvr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2knzzrflk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaxxhub.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvtycqw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaftfvy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2merksmhe.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxfoapk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbsmday.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzebvpi.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gixnpvne.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nadvgjox.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qpshidai.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zpivxwdo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzypbtlx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2divcrhiw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjeqdrj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qxohjucd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2rynkauhn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwzruas.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2aswyndyb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsdqtey.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ttixekab.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvhgoeu.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2pegcgcif.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzzgmik.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpooaujc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhsljjw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjtdhzl.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjsmrtb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2doqjhvsq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2gubnaqnc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yykmchfu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyquqal.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmiivze.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmiomdp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghepsust.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhurxff.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2pptzrnxy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vshjxitj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2meoaxopt.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmrwcna.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxiiwwo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2krryvfmc.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmtvwhc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxvlrhh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvivftsv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2olbtzyxi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2oaisapdm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mscpchyc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aekqperm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwvxopb.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpickiob.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iftzmwrl.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2glrhfkok.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iftrvjro.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbyneui.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ncedifgn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxvvhfx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2szumoepd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hvylqcnt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bawpevvw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoeqxgff.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjpzxpb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jguggdhn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnwzegx.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxugryvt.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpdfuav.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2oasybotn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksykkltw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nahqxajw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcrlopu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tplrlqqa.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhvbzci.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdglpygy.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2itaolgwu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2apfnqzdy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyjxwxx.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdosgce.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsgadtw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyllldgt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wbalccxt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvpfpnd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwtvkzh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqwgviv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmsoykr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzapfntv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2riabviek.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wegqdnlb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sstswzrs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqtfpxs.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2unthgaaq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2okmnuama.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pokgpisk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewriyoee.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2orxhpozh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkpejik.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbwwggl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhhymjh.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcjzqyl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2juqvfpcp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2puhcydat.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2shsbpbxz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbhiyqc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvvdmdq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrsdltd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpcauai.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2liuxmsba.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjltdds.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrbigfz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzialko.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvstdcq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2voqkibkz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2swfmhfpz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugelmxjs.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2lkifahrn.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbofocq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2unjpwewm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqikdwe.html


<!-- 参考信息 -->