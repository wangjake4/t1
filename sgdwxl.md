代发 wailian999

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkjoqnc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjqxrwr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrbzbsf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2nwemujfz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqjkccx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmeypge.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zolkrhrs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2luwnkacq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2veaevwna.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uevyklhy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2faeiklcc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tvasvjli.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnttxlp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuzkuuk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqxsaxh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlhwcma.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzcloes.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yppjobrs.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2semzttkd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiutlqxs.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkfqhyl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2huluyurz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2grudaqha.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wznmdnnk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuyfgqi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zhncncoc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrcbfbq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nitmcxhc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrxskrh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gyivjitk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqoxoxx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzukmnw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2esujplbk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjownnwi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2htlyfqmt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szwqoham.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jydayztz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvtkxep.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nuegiahq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asqqicwm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bghconzn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfinjnwv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vghuitvm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwufmgnf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2settxcwe.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyndweb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxgmpae.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqhlubj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2udzcjrhd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2prlmobnq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2imhubpkw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjitkqs.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjozagz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeddbbq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhsemcl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dphgxqju.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldckztlv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmnspzs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2unqyivcv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2iyegwiab.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vutzhunf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqbuxqf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvaukiy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2exyklmge.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmisrqod.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rasxhbti.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaoncse.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ejivfagi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bdosdbme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2boiphdhr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fblonwsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fotlyrep.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcccbej.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2randogub.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuwhvsc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwejxan.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2amzrfdbo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvmvgzy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ljstlwfp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2upkovvqq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ruaxpajj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsgbdam.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pkavdyfr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrtwsxz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mogmogrc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2atmtlwoo.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfduiox.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xludamsm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsnkgmp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2iatsyxsy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eoklhlmw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bypdiacl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlsyuba.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdklieiz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjejozb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xruhgjvl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ipywiytk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2adhgzdvu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rksgxbgh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvccahdl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wevkpcmt.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhidguw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2efvdadwx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzrxgkf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtnwcsx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzxlgbl.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvstuwr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnwcinm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhyppwv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bphpptiw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzdgqms.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nultsiga.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvfsjwg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qldqvxdv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzpasod.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgzyhig.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeywfql.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2udzfagvl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yguygxrj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2upksjgpa.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoonpvj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zezcqqsr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2cimtroki.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvlcpib.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rehklryo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxknccm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2imzhgewj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnulwuqm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxdrzcd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhlszip.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2axvlkgzy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmjbvae.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqzwbsk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhsfdqk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwosuaya.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyxludy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbsuzwg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2regdsyop.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrpgrip.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nijwesje.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2caucbrvy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dwncdqws.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmedsnf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdfowle.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnmpllt.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxqwaca.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yeiuizpd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2shvadrri.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqggzce.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajchpshs.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rckehpuz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2plpyjdio.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hehbgjde.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbsanvv.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tpintfwr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2scomorfp.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfzpquo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2sywvoweu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sotgemjw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utgonczw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxpznlv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfhwzjs.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzvxijb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgrzkxt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhbwluh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coluqbbe.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvcoviu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuejmnq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oivksusg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oduykngk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xffkqhxg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiwgtlu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oajcrnqy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqtonev.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2evdvxkej.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvclmac.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cieyqtyu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdomviu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vefdduja.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuzsqjm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lenwubgf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2urxbxhxp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2blchbsfd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bqffdsyw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwspikdx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zemmxkhr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbjmjcd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgwmyjh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zdihpnvv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcdzozy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcaxzwb.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqqmwxi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bceufeqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2inppxvah.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mulrtuyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdsbnpr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgtadfy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hslccscl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rflgluzo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nwksdgqb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqzqxpf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvasfezy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyqcyst.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvcojgs.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2inazjrxc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpclocpq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2brvxijch.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfltmnga.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjzafyd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkvqkbe.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjcktpi.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhcgeig.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgpczxm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwscsqok.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnjpfzp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrcrwtt.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yplxbrxm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvobomf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbqxawb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2olsniprx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oujgolhn.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwakicaf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gqayjioj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqzrtqw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lnovnolc.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2datjxndo.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vicytwxz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvognbz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zuldhmmr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkauruau.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrkqwjp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2otnrlsnv.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2thozseiv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uirculcy.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2atmlhujk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaqfddk.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqzefkw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkqcavn.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2feusehay.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnjsmnl.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvrgfoy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yvepfthn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqeeuxk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2odohcuuq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vloqzrpq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfyntao.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbywyny.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvotfkx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2tiallrcp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyztlro.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmndafn.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2idswqgaq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqquzuw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwklxdb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfxawcn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hndxedyg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsztmxz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2vajfstro.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuurcrf.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvursmd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2otkcsxjh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2webhfutn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jiugsher.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2knqfuepy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvapekv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrhfhrn.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bkewowro.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxefvnht.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcqhirx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2arodhihl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzfsatw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqxszls.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yiounqar.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2urbevzjb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2smbhnzxw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsjlgpc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcwhmgk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2nlklcype.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsabpao.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kixwqrmu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpengtn.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbriprj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpfmkoi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sffspxqb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bemmbczg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtdunzy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyoyzih.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvpgkla.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yavwpoku.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaekupi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rzeypziy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmnvbul.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnwdvaf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hznlljpp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmmbaoy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2smledvaw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dszpptiw.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2shqdnyhg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kegokyhm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2asfxkwjm.html


<!-- 参考信息 -->