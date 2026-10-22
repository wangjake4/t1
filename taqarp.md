代发 wailian999

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdjxgvo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsavcjq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoefcjd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2butlrhjp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bznobhbi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iowtgksy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kktpmasf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggehstrw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcziqwx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hadbsxea.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ulenkyai.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdurius.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qkndfhav.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgvsuoe.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wivbafkw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfcwzwy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqewiyh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwnifss.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mutphlbm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2syzeauyw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2orlfhhoy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gdswydbi.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuedgbb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmexxkh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlsxppa.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2caeikdmm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhedxkm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kipssvtb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cndshgal.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2duduckbz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2erwsszum.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrbqsfq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsbzpko.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgdqwhq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlgxqdr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfpzyhb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvyetup.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qywcwriv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqzimxf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoeyudb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjyngoi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bjanmlbi.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtckdvf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxdckyn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fktchdfq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjlqxgi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqcyrfl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cobologu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zorqylbq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2raghfsdb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdgtmei.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2momomaoq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuiipvha.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2trgmepxx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyafqpnu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzoucwl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2awwohyjv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2crfqfemi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2debskpyo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dexuvyxp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2phgsadrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtsdlmf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvrvsaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrabwdz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxzxade.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iokbedhr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvyffcz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2shquigzk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkuuhxv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvvuvut.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fcertonm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjhabhy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2akwsbtha.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqvtchn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgmhgdb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2srkmxjsn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pbevdopo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhngdolf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jijkffki.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgkqoth.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2clmgokga.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2eflftjal.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlgtvga.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2botahtqm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnpcdxy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqrbzof.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlttmea.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcyrtkz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmgvhlx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kckkpgbj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yifpldjx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsgdmwa.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ylksnzfm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfncomt.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxmcgou.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2inealuzw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmfhbqk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2afntsuno.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfigogn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2khoogfwz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeorodp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2amtotnbk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrgxrdb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqssrgq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbvonvc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmjdpht.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfxijnv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyscvgp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmrvaxp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyxbstk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2uwutpkrq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eefawgoo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvbevvx.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kylodehg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bzegfvds.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpiowmm.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbvogih.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpbqxex.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fiucxlnu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghztdazn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuvgzyx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiwuugx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2flriebdy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpylnobb.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yoohaoan.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdqvais.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2riluvman.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfewudk.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyymrxwv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vagnfisp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ehboycey.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyciqch.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2haulucvb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfmrzld.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wptyxsix.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mjigzuin.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fhisacao.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtymmdd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtgafxx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rjozszmu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jedkqynf.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2widaoogo.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmigznh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mkktpxfj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2txjdvmoq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbtqdsd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhuthyr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ansrohzb.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhnwdgj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2erucqmhz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2quovyhze.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgajzipd.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyvuowk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swgrzuwj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dayvhtzs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbgoclh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2iteeftqe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruljvisv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2canjmmtz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiurtjz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuewqyi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znztdqmj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ompuvrqe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxdgejq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scyvrgwd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nictsyqg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcjabuc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xilfsyrf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bcplkjmw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pillydoc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiofkrm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ickbbrds.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdghsiw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tlisywwr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwivdos.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ykehowgv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdewqzxr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2geavnsrn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsetzxmz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzprueb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gjniyvvn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfcfytp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmheust.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2imijrqmq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2waxzrrss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2senbkcvm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyklzwg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zouzzxcc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmshgxk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmocpje.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2apfpuwwg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iedzhcig.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rywujfkw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qigstlgt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fngtaozl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fejonkav.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhhjdsw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkbhvrb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjsinfy.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvahtsm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vreztytz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2olssbpdi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rlybfrwb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2bcamndva.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2oedidwmb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2berlmrfh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2skspnxgw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2inskimia.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2moofvnbk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rblguxcq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2megwfzzz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2txlyntzx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2anwmdxyz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2owcownky.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2awryuvgk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaeuiaa.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fucobsdv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2otbjhatx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgbdsae.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xikleubc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqezzbz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2egyehtzg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lwoawogu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yewvcngu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2telgodwi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2okjyogil.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2unjupzsc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcylyyc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuufuom.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jigurfer.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2lrssxbbz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2msalnnae.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2imuoxofe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2osilmaig.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrdvkjy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzffdgx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlatynw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2amgrafpt.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiruqzp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2rckxthyh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2artmszgj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2erzjqrfi.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwajszn.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2llxkegho.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvsbwmn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwztmir.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwgezjo.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqvtsrt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfekoqf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2sduacefj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqcpfgq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2afoixlrp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nicddfyj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2turqtrmj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2batfrwjg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2foxylysp.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2frmkgfal.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2guojhhiz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvnzinc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvepzgl.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uownfizd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlqstwn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nirbabry.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2deuuyaig.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2irafahol.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqgewyw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2elugyqny.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmcoqdf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkswpho.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hajsvaep.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtdgmfi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qooentvw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qorchudg.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfuvhcu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmdggpf.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgihsqot.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yiiijrpf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kucyisgz.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2minzuohf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2oowkyxjn.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2omwnvcjh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxxuoxv.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfchpzc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktiucwkh.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kishxqtp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgaermz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2eoueljba.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2spwrrodf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hztwvrvs.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjmaeyh.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrlwsvb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnpuaxn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmvxvie.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfgkrut.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2egrbxafy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlrpvui.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qimtebkr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtnqzyz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fguwvlta.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2voalhojj.html


<!-- 参考信息 -->