代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtijvsb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akfjvvsj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiktaik.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dydgeuhf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qewrkxfe.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sexsfeyi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmaslop.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cvapnrcq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2upjmljpn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzipdsw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnlbbcw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2quwswmtj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbdtgqh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2fncpxvos.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiddesg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkvjiiw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yapripmr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2elixbxjh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2atfdyktm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2czjkiyxe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deeecoik.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2crcbrqgs.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqoodjn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsdhglp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgllyab.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dpglpmmm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bnntxftl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqbaegk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lgakhwdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egzdzvpv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbjfrri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trcwzbgj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtorrab.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2whepidyw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwntgve.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kgncrlzd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ustlawzq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2usvzetod.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ojasflgj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcyaddr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iazrmlna.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sofdeywi.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwofzug.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zavjyiff.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuzzyyp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzxtczz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2slhaoaep.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vicjoutr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uorpwtyb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecupnwtn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yaehsbep.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mptdjqsr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjwagzp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2swaruvxz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dumkqfae.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxysssh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xgplchua.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzjppqk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2minfqjji.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yslxluvw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvpegll.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzfbyte.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hawrvesa.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2acjjpwzc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bmahxqux.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyejttc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzrwpqo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmqprzr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvzkjcy.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccondfuf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rlajtzpv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxvejpm.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ylarnxvw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmxxiev.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bcarawdz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tvokfyzt.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrpvuaf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yikfkjwg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2adkbezsz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzfwxye.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xnktgtga.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksclpaor.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vntyqafu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrjkptk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqgzobb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtyyizp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfdsdvn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwwyimi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2aqplbxmp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2seppjfdf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdmlklp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnspfzvy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wpudnjdx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2erikssdh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aoftejix.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kshvsswu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxnrjjw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfenrmp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2arerjunw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qpttxbih.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhfkqfz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmvazkc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhekilf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vaplthpb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2okbbecpe.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2imqavuoz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvghfxmk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2oycroicb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfbarwd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2geswanki.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zpurqbxq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hexsbdgb.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ferkufax.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tozrlwbi.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgbbpmx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgzxacc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2giaivkup.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnywaxif.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqfsoes.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkigpihe.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaahqts.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqpfaze.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzorpbj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glkhbmvr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lyckxgvr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxigpaf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhfvnye.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rypqolzt.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjzlonb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pepgrcip.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoxrjdk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbubwfju.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjxflyv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtkizmn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjpbebw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xowzyqba.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2maegjrcl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mogwdkci.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeowtxf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxlvgwy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2miwxyxdc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbyglum.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhegoex.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2uudtzmbr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvtscbs.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsuqqtv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iofmcjxs.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2trrwhqee.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yegaynod.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpavxms.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwokqptz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2skpcuatp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwfpppl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxwafdj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpmjotx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aahhxryt.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbmikez.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dartzubk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jmftniqj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2arozyamk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrenenf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgnvvcv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtlyawe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfpagmi.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2scfgaskh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrbqasv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dccpdvmg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvdnlqb.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2disrvsbr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftidacka.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2amjyannf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2btmttegm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvnurwg.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaloazje.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tcititse.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ziadatbq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pytiuqml.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zellilpc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbdusyx.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdramtb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxcqtxm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cztwdgqv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oqirgowh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzejpnyf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrqldsm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdulkeop.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ddudwxys.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ieieipxh.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdwarzx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrodlob.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzadwer.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvatxsbf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqfuqvf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuljqhm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vqncvvms.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqdzzdf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgoppoi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyfcudk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtqcbjl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkvcxju.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqxlgrj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nicfibjk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvqhiip.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqtmgko.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgswpwu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgextshs.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tioavuop.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrucjbwt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrfuwqf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qgttdprc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgxvmti.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2smxslhns.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2egakwzsa.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2aewsbgas.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdqphyu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cznqqltl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmgdsvj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvukksw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2opstvdea.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2xtncghir.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2aobahcuc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwnbooy.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqnuyxf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqahszoh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvywwiw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2riosvjbt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnsztbp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2mliccjom.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhlpezx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxmkyef.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmpcifj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jabxbhuf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqqupuz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqmajmb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhfutsm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfjjqjz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmczduj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2sesmgawi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcikgha.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkyvuza.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lscpybzs.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyexjos.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2samifmem.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vddrkgfo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbtfpdl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duybalsv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dhitkzja.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2cthyvmbd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcrroiq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoqtetm.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdzsksp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jidvuesy.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lccyjsxq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoxdpdp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqwpici.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyecjze.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgeacaq.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2etjjzyzo.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtsuhdl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqcgwxl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbpdwor.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmodfss.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qgucfpsv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzbvhhf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzbebrt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyyrmgp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeaiunv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2banptbbd.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2seagwfmt.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkbawgt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2dlphtlka.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqobvoj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjvzmbd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjdavqi.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wnurypku.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiuckqw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmoqtiz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2srlyctmz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xhppfjpr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2laxiybqy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cllteamu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnjntsl.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iglgxizk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lympzjqd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoeaqfg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfxsgit.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoqxfkb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2skjbutej.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnkvhap.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwzdhxu.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbdawhb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qidrygye.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhrgupj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcchmmwn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlssvzs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2umhhrtlo.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vdakjbvo.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmgrxav.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2radbtmhk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbagftu.html


<!-- 参考信息 -->