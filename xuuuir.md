代发 wailian999

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cloketqc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwskwbjw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pilnvkfl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2csqumcgw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vggbwvof.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxydivo.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcmkwio.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnqsqlh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbmzxam.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtubpnxs.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sglouysm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vymbxdha.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfnwthj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2biahhoog.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2galyssnu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fvedjudh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlxadnr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2udpunlai.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvyircr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxijsfa.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgupdanm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwmokgd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdflskv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2thcbosxg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2phbyppco.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxltewu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kucvjglj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcargeyr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gflmjtae.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2okzzngpk.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eogrffcd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhllyefg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2anphzmtr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slalrprw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbekuqy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bssvqchg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vapsldki.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdcfxkz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2phwroril.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2swmkvubb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaufmoq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zndbhnqj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpouaci.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2npdfdhct.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vikloamq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2snlrltwv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rikwvizf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhpuvhn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2abalazje.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuhazsl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfshcvc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmvpvnv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcmlodk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2teimiquh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdhjxme.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqavfpj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fodvwwlk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gytiwsig.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtunfaw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2taxxkltm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdjywwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvdmsjk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2akugggxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eupdbwpj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvycbvk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vthdqgch.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqdtyln.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2djfxxahg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2amxdyhkc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gatxpxei.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2matkxapq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2odjyzvkh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bamtevuu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vonlopsy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rhygbyvx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vckjonng.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ozciuhtc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiibehiu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gddokmrk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qghfncpa.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2arstxfmu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgujbke.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2halfeans.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mezcenwa.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqpldez.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbiyexe.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxvbpez.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2unfwlbxp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgxzytm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwybohn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fybvwpty.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcldxhte.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcavbpt.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2awiftcic.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuvzcff.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdssnmz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nyenzxjb.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2umnwtqaj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdqpost.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2waepsyoa.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2eyciunmo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwzdjjw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bjchowej.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2amazdnoj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ccauomiw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrigadf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kijxhnkk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kectiqpo.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2loeflbve.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrgnpgg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjygeac.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnlpnvq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lthkggsi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgmtagr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2podtodan.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2idixyczv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdbcitf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2crchwucl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xeudrzul.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqiusnu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcfikzo.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqpbxkf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfxdzdt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbxjvhd.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvalxgf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2toonfyvq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkwctga.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrbzpvc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xddvdgah.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kzngbful.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwwrels.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cejcqcba.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrvoqon.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vkohffvz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvdxgga.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2unpmruvb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvatqpk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fompzxdx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkvtjiy.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ugziryif.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzvjjmx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zugiwswp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxkbyhl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpxyjpd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2upiruotc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2safwiacj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sdniszqg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrklihla.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tuicfabk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2uluhamjz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jeffhexm.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqraozjw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwdhzca.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxcrawn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmnyzth.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trmtsdgt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zwudhumj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvhrxiy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxljzhq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjavoyqv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxyuqbz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cafqtyim.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aenfvmqv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmwsiuz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmvrnjm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcfzevx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuabmvr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2czrsrrgl.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqjmiaa.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkoxxrx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmntlzu.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2brrgjsta.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbowyuhi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrqqajw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nirokeoq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wojbqmsn.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvvaaoh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2afbjzham.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxzqwty.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oylsjqbt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sddhnrfb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfqtqsf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2paffhrly.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2oenziiis.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfqbnyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dotabdvm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tveodkes.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2plbhgaic.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2plnpazji.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2seuhltxr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hhndeqnn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2afesfxet.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeqcizy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfealtt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvlsyyx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2otrjkmrw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzrpvsr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lursnxar.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmbxycu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkduhnnc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsxguwt.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgylkhs.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2khnownla.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qbltadjt.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xazndiom.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2flwmfkqt.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjpikux.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfsmaam.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnauwjr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2stgyvqeb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdziwmo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2siavzdeu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpjswfz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dninyeuz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrhdwwl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2eehhiyrc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2muxaunel.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmosjtpa.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2trjffnal.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhdtdgu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyrzazg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezevvdmv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2edtekadt.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryojiyuj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyfshea.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2salkkgju.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xgprntui.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwhqdwn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwluyhj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfrqsil.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrnuoxu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmnpdon.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2okzabxcw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwxotfb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2offsbyjr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzknfgas.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqobyna.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2iajqdznn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpmvrjk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2isgcnqme.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcjcacf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fwojpgus.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2chkqdbdt.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjdqjqw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qljxzedb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ztobjotk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xvucvbxk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bggokhlg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ogijhxzt.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmgnxdn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uovkgrqq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2uazlsdfa.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2duejrgqr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrzwazw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdhpvkz.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2thtehylq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdpauev.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ympuykpo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2usszkuji.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2azvmxgaa.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzczlak.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oypjimfv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aksueoqk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2npqqshgs.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2chiqgbll.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhminlig.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjhnayk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkwsvnp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gptwbodr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2asuukbrs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lycdmlal.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxndvly.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgkztwc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxdnvhi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2blexevtk.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2secmklca.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmwzwdv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsenbyx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbvbtxs.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ucoqzmxk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjhekgm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2mazgmkua.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2skmqvhwz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aditqrew.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2defaauno.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnqviun.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hclgyfhq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sndihijg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrzspav.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaswqsg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2unajjrkc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrtusdq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qeatctdp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyfsnib.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2viteygoq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsdkqvf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rtznxrqc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdmkewt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrneifa.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaubsbcz.html


<!-- 参考信息 -->