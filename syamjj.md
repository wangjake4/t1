代发 wailian999

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nozqsmzs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrixxxbj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wxclbvkn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvhhjfe.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeyzxso.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2phvhbcfz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tueopozy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnqqrql.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbcmobm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eezgaggk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sbifntfm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvquzao.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlroxxw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkvrlof.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzrhohj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2phhafmae.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lomgkhfc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzmmsjs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpkbfhd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxeyiie.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmephhi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnihfho.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmnthkx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2nbftftxr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mrftuukp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2etvwdozi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kupfvzgz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yitsygct.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zndnggva.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqgyjfi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vhitkfwt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hypxddgr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkvyiia.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcpbydb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twapbkyt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2efeefpef.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2idbuynbh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2waqimmqd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdcogcl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2asjqqdmr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rotouqwo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdvfkhy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kyewkccx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzlonlf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ticrkzbu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rybwmzrv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdncpfp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrbuxft.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2shytxznj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvngvrb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebumfaoc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcunivk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcgjisy.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nldkhfqv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpxxnkv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ibaosbmh.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfndcqmp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzhwmbz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyojltsi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmmavth.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2arlrsgzp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrhnata.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdutidp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrktmaq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rzemzslo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqilwld.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnrdpcp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrpffab.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gywxtfdx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2igytvzhn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzrqfds.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mywisdhr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2urpcmmqz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xmghfpvd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2blbszxvh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oulhhdor.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mupyltix.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hepdtjpo.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ludlhbny.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxkxokl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhfxkpz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrivtddm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzxqfch.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eavdtuzv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jijrohjl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2yretxfyb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2flpqqfyf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kefsbzse.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2houalffw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zntrmwdt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeasyqj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfeadvuv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fffzqnin.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmdsote.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uftrgmlg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2humqbwrj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iynficov.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zkocjoev.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrmeuta.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuwahzz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wlslziam.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdvvaqy.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vfensbja.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvizcodg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcbfvsj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrzdtcm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iocfyyga.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbsirik.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2babecmmt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eflllnpd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdlpwdg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzzidkg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2plrjrokx.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bafdhpif.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbvqpwb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ougsbtkg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuhnbbf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiatxvr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlhokwl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyorieyx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjtxlwr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2toyaypuq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2iegxaszf.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfshvyj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlqsrsh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqkgbqp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ysahdqhc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqeystr.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahllpiwz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2flnwgvmp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiwgjrv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdjrdln.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2plfuiesq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pjovztpg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvteudq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2szfxjyyo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvhfgbm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqhxbne.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yglydoti.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjfzsop.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoiglrs.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxxtqit.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrqgmbl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhmcjed.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfjzzlx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgrxqdb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bjugpahb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2grdmaqko.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpmtcau.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2oywvxtnu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyayyejd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvramjfc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kpphmkho.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dntermjq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcddxuh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygiajauf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tiahmdcl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brjitxdc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gpumkppd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxmftrs.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvztqrqv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyqnnmz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vobklyyu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mehullol.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uztieesl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzgovuu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iruxrrrm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jiinrokt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2djupggqs.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xdalewza.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rahmiigq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pndgzias.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgcwurh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mtusgslo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fddqyhjo.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nokmmkzy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbqnzye.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vrodbtyc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pepgerud.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ushcgtcw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxrncmc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyabsew.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbqmaay.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxpgbnz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2swfcbdja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kflxucax.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsoqjgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zyegqfwb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgvupcn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vaguaffg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2iprvreuu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2entejpwm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dkulovze.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjewbae.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrxyqag.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfbveen.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyohpql.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2aplomras.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kntpjnwt.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2sipxfqns.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdttlgi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcugtury.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cimmrxdg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqkphaw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2sugvoqbi.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wghcmkrk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2puiaalky.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzarsdru.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2phebyxhe.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mugshbyd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cipjabxu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2urusiypn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjznoqc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yazzuyel.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqqyxjr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2snjczvms.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2uoaedxxd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnirshtm.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxgevbc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbfnrhm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aouhrjos.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2njctcuul.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkyfzuw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqhkvcn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeslkhh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uolrqwxz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2eopxovdp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdylwzma.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcfdoxf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkcnkta.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cripinga.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2njnjxyey.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoldleo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2knrkrdko.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2avjxjmjo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjcuhof.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyagfvc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxzviby.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmrazlf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzarsoql.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mggrsyad.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2iontwkyy.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dowbjvuk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2trhmumth.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kzadribp.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoeuvrh.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tdispodd.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2beityayf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qozmgdvb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kcioooyn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwfwotx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbnevme.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhyxzth.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbtnhby.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpibgtd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkhtixp.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtghvtw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2enaoqvli.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kywqszpx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2eljddmyz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ettkznlb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxaiflv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2syvqawgy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2usbbtihi.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdepbom.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrruyyh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfdlake.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrnokpg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnpiwvd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxhgfwk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ptolyhvq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeivbkn.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwitjyd.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2humcshrg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wkflykkf.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbuyleq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqwanup.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaenriwm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wclhiggn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lphpllyw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhtjyal.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfeymbz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxnpddw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tncxolar.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pllyhbpu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzctelj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ciilvpew.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwcpelr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnmlfhu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzbzufr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdivvgi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtvlpjq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqnidgv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsqovmc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfovklg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfffxbsp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nonrnsir.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxsruif.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2agqytdff.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjncwxmf.html


<!-- 参考信息 -->