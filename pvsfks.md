代发 wailian999

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwkjwce.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtpakij.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhyedmg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhtzmyc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tanvaofz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpkgqwq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvshjrw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfkbznk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ntweybcj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qibhyxvy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gytfsrgc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyidgty.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbcylbn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeebtug.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2omjomhrq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwovsxta.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvgqubh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2euhqlcgs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjygzicw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvdoxvq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeyyyva.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysozjywy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfonrfp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlobkaa.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsfxqcm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2attwhzdr.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iedzlwog.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhkerjs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2irxtshug.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfudaci.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrjbsot.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmcjnwl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvluewi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wufcixns.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzxzclg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jznpxrri.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xprtjywo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrqnbwt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gczmslxd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzytaet.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oofqooyr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bzllbjsl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyjznsu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrkpozr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mafhxoin.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ttghtoxg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqzoken.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrobhbv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyualmkd.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcivziz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2swfxwwaj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmhlqjz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2azvphimp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxzydnl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2iywmzukr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2brjhivnc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzdptqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oslanfea.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cihooqua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsscqyy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhztfad.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rymwwzri.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqmlaxy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqbemmq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnixltc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbdwtjj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzjcogh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nmprddro.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoisgyu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcnyono.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yidoxgwo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfesjnr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2evjwdjma.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eplxplrw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxhseqq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnxhyhi.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2khugforq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fawymjvi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtewhii.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmefzzfl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2doybqdih.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmdatym.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvzhlbj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqohqlyl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2whykzovv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmchxymn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyyejmh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxzogcf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjxmthy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjwaglz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgmbent.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqvdjqo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbthmtz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcbqfyz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxojruu.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtypjlwl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkwnalq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukthnlqi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2csgyewrn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mckkukwx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2flkbjmcb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2opbxhqyg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjlzxmh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2axodsfho.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbkyubq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfumhna.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qrexsvab.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfetzqgv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2sjecdcdm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkkggyf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlplwkn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnqzqmn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2herfljts.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziekuiuk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uddkelnv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2omnpxftl.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2btkpmrtz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsxxosm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2izryhbik.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiiwtrax.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aavkleqd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qomstwsr.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iuumgajj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqpvklw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsstdon.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gwppdlre.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdifrke.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjveabj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ianqnhsx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fypusfpu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2frsokmri.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pudedita.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xldjoaun.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmdiajp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uugoqmnr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2psgjkana.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyxdayz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnazeot.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpiyocd.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjsivon.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlwwylm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwsjhyv.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbcfevl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uexsuize.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsnjvki.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjklsxqw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kguiznvh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpvbmwe.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2emshewof.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kerauvow.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jdizfcyt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxugosmr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbddycp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwtlmqw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfgrkam.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2safyctkx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdxrbxa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdovglqv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrbanzq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcvnuzg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcihjfl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2heersteh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2utwztbcm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2riwlocuj.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aejepogx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2doytsptc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oavcwgfd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdpszhk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzweialo.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrnkbqo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrnwpnn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvomrxz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeufhyoe.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhlprlb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xufgcvyt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjrxzqo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfmcuzn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqxyjls.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnhfsqs.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmjeijj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyrmonw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thrtikym.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2omvwopdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtcxviy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdvmtvu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2maewuagt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2utazihdi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhltgtj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uakocmcl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrmqhoc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmqexiu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxcwypb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ghanmcdy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pgikcolw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2przrstum.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zetknafo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2olqwsreb.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2barehzsa.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgvshjl.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlydppl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fvstpdub.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2oucpsnua.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbqfstw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vkatdzdz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2etelpzht.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfetncy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pdiqfcyw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsprlda.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kftyaohw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mokpnzpi.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvbrguf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrssurk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cfphewpy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2phpeahgn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2llahrtxq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2klhbrsae.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfexfnh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhownbw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qfibtvvx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rifwldcu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hghapruh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hicqoopa.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgjaokh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2whntgfgh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcynkbo.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2sinpnolc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2duknvhhr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoeummy.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnfahlg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tchtpamq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kdicpeop.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfbidvo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2mguauvaa.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbytdbr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvvkdwr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjmgrnu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2woslobes.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjaivqj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bijqfpev.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2isuahrib.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsyaryb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgfsjqu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcpxwbp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wajzpozj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hadgaquv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2flaewxen.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpgcwjm.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwwvueo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2begnzxcv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfrsoes.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vazzwuxn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdatgls.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnqkfau.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpedmuqb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2phpyptss.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuasbdr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrrijrs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nswztvsc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwpfggm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjodkej.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhmltuo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2nifltepa.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyjgkzy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kefrfcfx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpuycns.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfkfjtl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2aotzviee.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcywhup.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwjtmmf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxlqhhd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2orrrksdx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhoenoxl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2alttqshb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkditruc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdmtcfh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwprdtp.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yawmdqnn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2eqopryea.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvwenao.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhiaspl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2apbpinrd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwhrhqy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkgozuc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcexuuao.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jndxpwpy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkzdfkw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2krnvhsak.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2moaowakk.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2hegtaojc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ksshotvu.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zjolpnyl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2srqzxacg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyjgiaf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyyusaq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgylaoqn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbjkqig.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yubjhaic.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzvnzmt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxkbfgk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2isaeilya.html


<!-- 参考信息 -->