代发 wailian999

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzixrheb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsszkjxf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2laepxwnl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnktwci.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nexbkunb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2laxgmizl.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wmthhrrb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nedrvsoh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tigkfbxe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2feuxxqid.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rafkdvxe.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjrcerj.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnmpmus.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqwajgg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqefqmc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrazfffk.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxlzyeq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuaxzsfu.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjqrbga.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fskeagxb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nybqyodc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2efxvbrfn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcgoczh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qonqoxro.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dretwutr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zobciukh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2okvrdgox.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqqawot.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iheffdlp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtezjoo.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgltvgv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2nasvurjz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2okoqmtty.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrqsdyk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxxgwnd.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btnllydc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmcyuga.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiupasj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpwirzn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abfpybqj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhfhpuq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvfwbgv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbttjlv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2whthvmbe.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qinntfko.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlicxmks.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrwrgnm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaigbvc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvlvojm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wewhmerd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cggpcekn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxjzdcy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2laxmknfn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvhrwfu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeehyvh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzzugvi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2couwkctg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbnkyjx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2utoykdmy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeujkdi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntafavaf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2psalozde.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzcjnnq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2etsxcyti.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrawbrs.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iryipnlq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwglfvfr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cnankqko.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2niydlvfc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2faadhqxq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvimaxbd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmezsadz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjlatqx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnizkqr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aikbvcqy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvknnkh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhzvoat.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwybfdy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2iezgxotu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hdieghog.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeqbvet.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vyomotdt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxcyhwg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2coadaufh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uejtwvhd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgepqwc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsbkqoy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qugmjres.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsrcodm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2agqblxit.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxinawcx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2efupxhek.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2izorzkxz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2swgwuvoe.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzuwxxv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpmsmlm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vkilqfgb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjitkxsd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzwaxxm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uebzquzi.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqmiyba.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2esqrpcxe.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2quisktie.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxegqet.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmzrrqb.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxmevny.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrvkpjt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2olpxlfzd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdqymrz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzardkyj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwyrkdv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqthlxd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2foalqpab.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxuaqeq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qenwecat.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jstsrbtu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyywuct.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gozaqssx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2opddslgn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nszjnrqr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbzuisq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbqqzhy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2srjjzctm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxphtbeb.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfifdth.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuvgche.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2svccrhix.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjkcrva.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vjogshly.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcorsch.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2giaclwxt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpdmyoh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuwstct.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzkuial.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qfeamyyx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnxgiua.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvlnayh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfoqqjy.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyjvsjn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zajagufq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoiwoeq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfyfuoi.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgujkml.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2uudbftff.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkrujfe.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eybafnnq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2evzzmcpg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxokwxc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2haqnnaje.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqenkiq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdbhmoj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfncaza.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqybdmd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2enkdmgow.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxlckok.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxlapqt.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wifatiqg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkpkbpr.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmckohz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tikgfpac.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfjrlkq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgnsjsu.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsohuiw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aghemktc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzqpguz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuvnpvq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eygktnin.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dijoyced.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjenmlmq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ienllyoz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hndipgjr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrtltxv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaudzdx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbqfzod.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rngffsyy.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vpambqqb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzrgrfz.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcmzmap.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpeszzr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnkfdsu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2anecqrnr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rnarjbim.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbblhmut.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2srjmujpv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkcwylz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wigjbzqh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckajwowx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ojirgjaq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjwdczl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2voujbqgr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwumiow.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zejvkoug.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2daapahvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxssdsd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpgzrsx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2miqbwcmz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bobenfgb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkvsgyj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmtlcqz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2obwkhrfm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjmojsj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgmbgds.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2evflczwf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyaavqa.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bscaiydm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kajhjkyu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeysesx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cghneazg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2prxaumdl.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkutctyu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gocbpnfn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfqvyye.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlfjcmg.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2popdugaf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2alllztnu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmlepce.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpholpu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjipooss.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbzofdb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmihhghh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gzauxzbj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxsnlcb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmorgyz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtielvr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zsirvnjg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwbbzbv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcftsif.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmavixr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bhblbngc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhnabtr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtigwjd.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjtqgsh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2pqblqsgz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuzfivo.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fqffxmae.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrairyi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bazmsata.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdjzkqu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kprahfui.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2olgloblb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fajzpwoo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2icwovbzy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wultuhoi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2efvfmyyh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwbstqe.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcijxbqf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2iaherdny.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoytuyt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2swymnlps.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2eavjhsiy.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeewgro.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgwqiaj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tppdwkgh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2plorzktv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gllndfsg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2krhdbgts.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2pwabdnhq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2krxivahg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcsydeh.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fswqvaxt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcgeubi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtxfbxd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hovtxjwp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsthzja.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjmnlba.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhiiftc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2igyleowf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvuxsxz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hthjnezm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqwfend.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjoxrzr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdcjwpx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2degxpygg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdguvsdr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrtlcxh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdwwuiw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnxtupi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwmasut.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpkwqcf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlnjieg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2evyzttzl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2epdvlssu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2igmvgpvb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkulkyzy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2efrlqzfx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npjuzvgp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgnrtwl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfhmhuc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fpocovpp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ygithqwv.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfsawqj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hekjlxjf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqsqths.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdspetl.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbwfwhg.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2arsmldfe.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlxjpfj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2esyllxer.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dnilpyqm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2thpwlotc.html


<!-- 参考信息 -->