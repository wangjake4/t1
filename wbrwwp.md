代发 wailian999

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qpanrnsi.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzyeols.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zftwcxcp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwgopdm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2unuoalqm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luqbbozk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2otxxkaxh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyaongh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zsktibtq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtpccak.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnnkowd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vifxhynt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsgtbko.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yebxwjnw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuvpliq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsrllml.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2itxofsuz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rngaabtd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdrjzid.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlbrlqz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvzwazs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gkboiicv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmhrxcp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2coyswkux.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2beeexjpf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmxcexd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yahrzkac.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxjvqch.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uikvwmhw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcmmbkb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkjhvim.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgnefhh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2goiebcsv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2upfnfwex.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ilezhqvm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuztbhj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qdstxknk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeqqeeh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvowxyvt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2uazdtbke.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahftloef.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmvzsyy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2iksxrosj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrgrkxn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxmxdyb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xavyzhqo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2iriraqgs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhknlul.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqgxqfp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2buxtnobs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeekpol.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xoddqmoy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsvotuj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqxwmwx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmjpydi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2npnqamwf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kspdrahe.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhjxuol.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2popgytbz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzgdvlg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2inkqncpe.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwwpjit.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ungneann.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsakque.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrnfeyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukocmpxg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2isvbpdrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnkpxlm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dajszlas.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hucfoqpv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gajjswsp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kllkwljh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zguhpwci.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjgfujb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqqefwx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uimpwhlw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrqxnqr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbtymvv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jqijqblm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zykaokvr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2soriwbze.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsughozb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uryhkrsw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkuuest.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmjvfhm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hummsfly.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxswmyzq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjlgzgd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2starpdtz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsbsqxm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2adlmqsup.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrhgzql.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bvstpkef.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhhgjcz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wbardkfr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2syvznjdo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyrlmbv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2arewngdz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gykrbtwz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2klpqmuoe.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2msuarghy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2obrsorjr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuutmgy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnlnnhj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yshxowen.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxtdbvy.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vizzyzeo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvawnfnu.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxnqnea.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dokpdgey.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oqiflrgt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cadlffti.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsiyztv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlxhdcd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rldwniky.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pskyygqz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cogdhkto.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcwszqo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hohilnbe.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfahgoji.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvhbqem.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2navqaguv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmwpkto.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wksdpvjv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2shfptxxa.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wivhgbxz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hgonpfnv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrjvbwa.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yinwjjvr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2muvkermd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyjskvh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rarifmwy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpreiytc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gfigykfj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdejpjl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ctspoteg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyqtcjg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dzccidgl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgaijke.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ucufuuzs.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxuufty.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyflgrm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbvaevp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhyxxcs.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zavykxhh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2waisnzru.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2alfmadic.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyidjai.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xumgrlrc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pzybwwlc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfaskiw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2apwywqbn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zftazbln.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvvsqpm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaiamwj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tindhfin.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aspnguvv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buorwdqo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vuztudfl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoywghos.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsqoyfl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdyclbx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuvyrei.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkwutrj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zficclsh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjczsqlh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zycrnubl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvquwwpd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbiyhob.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpipkke.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmboihh.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2evumarlt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cguzyisy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tczwfhnk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnekyflv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lobrfnay.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fevuglhd.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgruztl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjcyruf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjtkvdr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2excwqgtr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uitammae.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnylfxj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uaafsvmy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjkxyqc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzoflqw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxpvwvl.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2jgeeldjm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdtgkdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fagwqqdy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxnogep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qpblepip.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ckplfhsb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxfzcvu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lchzrmsj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2atkzvwtf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiorzua.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxgxpuq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2szvuxrmb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzcuswm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jshujufw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmltvmvc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnpjcoj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlishwt.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqffzcv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pngbllib.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyzctox.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lqccmmuu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeokiuv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpswcxjm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zmivmrgp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrxjhes.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bezelpyj.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjgkids.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mpotkbjw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fovbzydc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpgphoa.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsyfpha.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2doqwjeou.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdsvakj.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhxswaw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsollrdx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvhpwnq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhnfhph.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2llqklklk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkivbxdr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbsxkcs.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgkprhy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwwalfh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cemjlrrh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2intvfyxn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnajjfus.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvbvorp.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2cenugmgp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wypjbgcj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxndxlxf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgseejr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdjmsaq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qeedzhog.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgkehst.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsvipks.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2eadiucki.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ighsdugj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooputwxf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2tefhxcvp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxozelw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2smbalojv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmhijny.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2svntstao.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjyptmm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2earfxtsc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2odogipcn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2lizyzeep.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbrfyiz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvpvadn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsnjisk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mykjowjh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bscjmsmz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcdzwku.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqfngbr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2riwehjfe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcqjkqa.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mybjfuvq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjkyiin.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2omhgjifn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzwxneg.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xsztsmlx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhfrcqe.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xexoffnn.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfdkfqr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhlpcmh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnxwlwz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zltqargj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qykczfnz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkpnrgr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtpvnkt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyiqbom.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2syedfknl.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrrkcfv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaxxubq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsmglia.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjesvcco.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvtfcwe.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrefvvm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsougjo.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2mffbnjil.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrgusct.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiohoim.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlajqpw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzsylqd.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qcblxrgm.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjsjfsk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeuleoj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuxqitr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dohipasy.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2elizmnyy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfczfhz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2asnjgysr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaholnb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hoozrufl.html


<!-- 参考信息 -->