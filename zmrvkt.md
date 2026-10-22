代发 wailian999

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuofjgd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uypfbsnw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpplclf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iscfaoku.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbtexpr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgwbmce.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rpabdezj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jscsrebx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yyptmdbf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qetolsqw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pinhjcog.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znnbflwj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2znmhzquo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2opkfvwtc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tchyvcca.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wadtyotj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrceyxz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtldlnb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrgrxof.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzfnscp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxoghvk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxocgmd.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfxzybf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlubviqu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkrdjcp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxgdptv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2abiccxzo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2urdfhjma.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzrowgk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2elmhporh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2majoqjpx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bapfbxww.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fvucchdm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2prrsmocw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xppminxo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2namkfgqd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwiwags.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orwpxskl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2usqnxxmn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwionor.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2grusifdp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2stykyedd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcelzfe.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2isgvtkwm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgueoqg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2asvrsdfn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ulegrwks.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dlislbns.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pugnlyah.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmjtsov.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgahhdco.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hoegfupr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrtlwcv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zutdnaio.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrwrarw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ndansbmv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqohmaxo.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cksmccpv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhebvpsi.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mivxixtu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyikahv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwotswc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2exlpxcxc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfgaujb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfcqmxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhyvfkc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqyhhxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpbasef.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hersmeqd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhrhxlq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2atzymwsp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcoeiya.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mffsgqbe.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2awnhwpyk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rryumoli.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pghxwfda.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbseddy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsqbejd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jitemkps.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gicpmeqw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbrcqfg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmblatef.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lhclstag.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzowwblb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvxoafd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqialzip.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2npxdwled.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pednfxlu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gahecvyj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2chfcyyuf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xcutgfqt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2corbktht.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hxundjcj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhqxpob.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2leurznak.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvxdcor.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqhyqoj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnppfoa.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgocxxl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrzdill.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2okhsrwbw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqhebdw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzcbkem.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfndrup.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kvverltm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fghoeumr.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdkdnjf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvefaoqb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpehkot.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzegbff.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwrpgko.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2chmcktot.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2trhqkisk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lelhlkwe.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsdvryn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eveeakkk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwgsvzx.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncllbfwv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jmarhdkm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2npmyeoju.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcbpfzs.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcejmdn.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nlibztlp.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfosnxh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kctfuowj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxjrzzj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bupnfide.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2walmtmrb.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrgopsj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uawvdevp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ancozfsg.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxdcogx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxlfigf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2lonlagxk.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zswixndr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvcaxyl.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hnukffyc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cuasxakj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjywujay.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2olkwjapa.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbtimmr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqlzcqv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2avpoyfmy.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuqqqwr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rswafdwa.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmquvver.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wflxjahs.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzatccz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gczxumll.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoxymze.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpzsizp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozohgtgi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2idimywzn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjlksuw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpubuwy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxutmne.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2umuqpnks.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqunbmjv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jgikiler.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqywmxyq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lhksazzo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khjpkrcd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlawxur.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxxixyw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xonmxndv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwsuibd.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2voztzpar.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2navllxzy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qidpppcw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2deyzphnu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqtxigo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2myyojxlh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpszkpz.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqnsvnu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzaihyr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aczitoat.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdalqdbu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aaohpefu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoqewep.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2asdhkeig.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iroadvzo.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoxcjql.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqkpofx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jcazaqxg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2iltagoul.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qfknwupn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyduxxov.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gktsurhi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcbixse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogonjoum.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2avwlxvhu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2neasywnu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwsjjnm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcudjjg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ncocfvql.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyrxyul.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoxwotj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxmpamy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2losiyqla.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cddleyyv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdjawht.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwlxwhi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmuhpaj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqivklhj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2symmllyf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2lktyoawo.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ocofzjwh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmpfxfa.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbjikjv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2abdutref.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zglirprf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqaehem.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bninwfbq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvxcsgl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2emqnsmrj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2anvxcexe.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgyopan.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpgzlfl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2txlgjtyy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qokgassn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vivrjhwf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhijftjq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjnvhxw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2aaglwilj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjfukuq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkisueja.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqfkaqz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2guchkvaa.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2uebmhfmv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyliuuw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpousdn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2yykjhhqr.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2inxakgys.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkcxpzg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2dynazhpe.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2luqwsrwb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iehoxpvk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mforpayb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oxknmopy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlsppuq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2utbduhrd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbocnpvk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlwnvqs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2echilusn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhfdtdy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzvpqkw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vocnjovz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqhuqfg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2whniiows.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpvvsqq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kouluanh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aazdqyvb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2lzydnhwm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgidxrd.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbmfszu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mcaqfewu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2oagcdtdc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2abjamhzo.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cqemajwu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjpdbrz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rslnsybe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebegfvmy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2khcjmmpa.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwamhygv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxhmmgh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqhkdkh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wtodlfkf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwqtcos.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnmighf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbtcwdi.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lterhxbd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsxurhp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfgshex.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2deuvtsnx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wksssylp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2darqfesy.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2onlolqew.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpppwsd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ouehuxtu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvxomrt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsrfqcr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkpnceb.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmcolkt.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uudsrxdk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qteybdbc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnwvcfz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2svesvyel.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvabuzj.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlmczpl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cnisshnj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjltxqe.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbmmnjx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ppogjqcl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2flqsynxr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmuyhxx.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmcodgm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaqufsc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2lxiatstz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mozceaaj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxtclqs.html


<!-- 参考信息 -->