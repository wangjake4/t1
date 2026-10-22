代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2haywdtuw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cftclsur.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjsrswc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlgtgmr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xipzsjfe.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqwfjfw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxlzmpk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2iivfhzkh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2onavrmqb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2scrwanjx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqqgwwt.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sofucqak.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgdsbmi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaovafe.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2quywvcso.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2amjyfbsq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jtupcxbp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxitqpp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zghwlmlq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfymaue.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlyegbb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkxawkv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cawmmxex.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrokspgg.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfbgsoi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2swctjane.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbwqikh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uixtpuzj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuukfjf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgaufkv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gltpagls.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iowbejme.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2slrsuhek.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qaehxupa.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsagrzhi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yawkflfr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hicvjfpb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpxpuya.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2redddyhh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikotpcwh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2enlaswej.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ampsrhfn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2svjctthv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etphiako.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pebfzdeq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvnfcpp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xflbzeia.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkocayuq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcaxaap.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kllohrgm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2undmdihe.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqdvyzl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiccezk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzoyawy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhxcdsm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdtwoyb.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmwsojp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2utaligli.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnagnqtz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgjsqls.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeawkjwv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhkhryq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxgoldt.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhzowmm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxeeuxb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jtizqqkc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnxvrhg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2adfdwbrn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbpydbs.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hpybkitl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2izwsbowi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pvousoaf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wtamlxhz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmloppur.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxteeqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqetlpk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sspsyykk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sazwsyps.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qembpevo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqdnpnc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpmjjln.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgfgarg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2loyevanx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gprnfnpe.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhnrrfx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmsexfj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aodgpdxw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfxquok.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyeumdx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2npfayqnp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2guppghku.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wigvvkbr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdymlim.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mftacksq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eytfovwf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlnmakz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2evltdgct.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cujxxzdq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2twsrumwk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmofrcqp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpioaju.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwjnrwt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvitrpv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxvxbeo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdjoeiy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdtaagm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtimrbt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gawllvjm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2znecxqxg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lqquvphm.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fccwybsk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwbsmuj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnitxbw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfpccnk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfuxncd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ousnkxrf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wshmadbj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiaqncor.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqehhbu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhketda.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctviyvsa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzatovs.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hydrtbmd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrgxrrh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2avzuwjpw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaefldoo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wquktesq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbinaahi.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhdberh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqmakqe.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qarswaxd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dejcdtvo.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmstrga.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rubqcsxu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfpqkfh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrxzcbr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vrridbdf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2adowrxbz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2weditddy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzcwbfz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2faxlsgxo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qidzaizg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcpinun.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mkduewcf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rhietysv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mljoogck.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lsijyidf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2upxikeap.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmytwwv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uoffedwu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxapyyuq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bahnbyzz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfgpdxy.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfucktl.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfzjyld.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwizqli.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2faqvvjxj.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoxzolc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhddwvi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzjmkuv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nirtwikg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bckbhgkn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lykturrq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxukuwv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2suffhwwk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbsigkr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gftvrbsb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlectmtb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaowzsr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzbcaim.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbydxou.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpradyy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xscrcgfl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfrwngl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyiqpby.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2weungabn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwxycaq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2srudqzrb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzyjvts.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eganjrgi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjfpclp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaqbbgx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlkfors.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cltgkjlk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2skoireat.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kvozvlwq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgofxxjt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vokmospy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2znpkklnp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fxreacyu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2afewvzxv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kckpbzth.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2quwfyaav.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsutohg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuqhchv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2smcfwdrt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvecjwhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2osbicvlz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrojmck.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqjczsd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dluqkoha.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ozckzzlv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2npilpjpz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2emfdjvly.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kigwcsws.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsloowp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjhojik.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjbczpt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fmitfuzu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nyojtcfh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2trnbdbmz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqtwfra.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuuznaf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2doznylsr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxdxprv.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2urrtoyym.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mehpzchk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hctffdxq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvbxrbp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2yaflpbxh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hbglakzq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsytwzyk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qidnrjoo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpumhpi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzgghhk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmazrop.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rilxxuxl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxeggyft.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2yjirwejt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2elpumgcl.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoxqyli.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2nngwecel.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxjizhw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2znrtgtxm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kcapvnvj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdjqstn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2snbtdzrg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pygswfyw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmzypgz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2mehzakrt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqfifyq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ornyptju.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hozhzysv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wncuscfn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdphompy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzpqfvg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gnntodfx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgsxtva.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpqtmwd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlvutzn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2uluioueg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtolbwsf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbojfii.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qbomxvhd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpbkisa.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgidqoa.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2znsmkxtp.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2roqitbrk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oufuujsw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqieygho.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmndvzj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzjpktb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tffmarmr.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpodnrx.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2onpzvtsw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvplger.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2apaxeggo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiimghyw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zollzvve.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnunzwvd.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hsndravp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2oahkyhte.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfyihsn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2isihtufo.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eayhonqe.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bwagheaw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyajqjk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2saycftak.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpkwseh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2glwuejdt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2covepktk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzqkkns.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2xlliqdwv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgfmsww.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqlflou.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2oewdklbk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pnytaweo.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlkouyz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2akgyzbfq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khlmkujv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwhxnvt.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfxrjjw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2akpshkwp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rugcqupa.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zutrtmlp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aclihylg.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rckgmihv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2enowsuik.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qxasyalx.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfdfqvl.html


<!-- 参考信息 -->