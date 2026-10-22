代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hltxkcno.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwwkdeh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioektgdb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyngbht.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfqedzr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xggfmmtc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xksskoqc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkkuzfd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcnbtwq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnylgrki.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuwxvqe.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2klzbomaq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2msuiaajs.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrrjnvy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wpchvytv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cksqpfhx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qshngbwa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrmiunh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvarcmf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gtljbmvt.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvdkqan.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bviygvtv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyebrwx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qklzsann.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcomfei.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzuerir.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2eqedcapm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwklfpjv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2njvmjuqj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aswqsysk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbxofwa.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xksijatv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rweoqxhj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2yorrdeoh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2stajmryw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2krcmbwwd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cynhnxrb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ugppedyx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2awstzwat.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2uatygeof.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxpbvrl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2flgeypzj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqyminv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slbhfbjn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkdzxux.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwmwxcl.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcnjznh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxgfxpx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ptckvlzs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeowwnlp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhwjhna.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaiwcjsq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrndwsoi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdhuaty.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vutizrzy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhpvddf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdmzcng.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2elmwvmaw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdmhyzr.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwglimx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjopriww.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbpqauy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kybopdmw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qnridpqu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsmipwi.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqkffvn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdogtux.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkbwrdh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaatvnr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkumwbr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvhagzy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rxakfqbc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2osupfuyw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2inogjdgo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbrrqrr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbelnus.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfkirli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyyliri.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2reyvuems.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxmezdn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dplvqzmh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xovfmogu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2opakeyky.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2csncprbj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwgdllm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrillkx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zyruoeoy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxbgeiz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iesnmqgp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhbrhfl.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkzfqlk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkrkbsy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqjpkfo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpjqipb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvrazmf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylabolor.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgfzwhq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvchkug.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jetvbmne.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzuizeh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfztxqu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzlnxgg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ptejtpba.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfsujpt.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2svfcqppl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2plwycvxz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fdiomtez.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdeciafu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbreabc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aghejipz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqzvlkt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsztgrm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2btzrrdzr.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdazgbw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpjjirc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpukhgv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qxaxsven.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmcqgel.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqvdwut.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfdgdjo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnksymo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nywsowxs.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvktwtw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqbauya.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qphgwyzn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaxknmw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjwnaat.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuzssgw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwxtbel.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2thhvogfk.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2whfoaxlp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuoudgo.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2njxtuzqi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqluxtwh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hardyvhz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2riqrihkx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2brdcytgq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtoetxl.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2izskspos.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpymqey.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2libzvlqw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoskbmk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2toawbzua.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rfajwsgg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqssyskt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcyobjr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnhizmo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nescpdma.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2koguncac.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gklujcyf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaivdbd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgkzmqb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gnohfvot.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2umsodlui.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcwuymc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzjkfep.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kauobnwq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbtxfmy.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbozybq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsknrkd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cclgnbox.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sblxwxfv.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eynumaux.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oilnhjrb.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqdrgap.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrkaywq.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbalsrho.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkcevre.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2alxsrqwv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edyfljgl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcoztoo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plwcvnkv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdzoxbk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgtzhtk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrlbryz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2javtrueq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2adavrewx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgvpmrd.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyajddt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jergkrab.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkilcumf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tiubcxdn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2urkyvavd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjwwjzp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvrnxen.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zknkjevp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzlzxqx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2psqgxrwr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eesnjjmr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2purvbhrb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwijbxy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyeovdk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxljahg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gutojiwg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcczsumd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tybfurcd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jajlqpzz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2txylddtk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2makbrgyf.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2icukkmlb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuzemjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exjdxpra.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tudiizfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkelhoi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgqqwnw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xycbzpgu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2imvvrbtd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oopftclb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2goemjuyx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbsvmue.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjeqfje.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpyupzs.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2utistebn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2raepwmal.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2thqtlohl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvdojcw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtulril.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vehwpxmx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnppmps.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2erqoabyq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjchsml.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvqlmtd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdxjnsk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kklsslml.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xedummde.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcgpomz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2glbhqkga.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqrvolm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcahudy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcochct.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ltiwtcew.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfcklbp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbgrhjh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2etoawrtf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2skyblmyh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lngjtqxd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2elhrtrxy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cczgiqxw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhhfyuw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqsbgut.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jljsyinx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ignrijll.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xatytlmb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkgfcnf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2roemghuf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2sqiqtdge.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxoevgk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2updqemwe.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jytwmvex.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2chnwruvm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2chlisnkb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuivdrwm.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnhzysb.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrxhemm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmeuajh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qykaqedp.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhczhru.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qenqxgsy.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuxmxwd.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2srveodol.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvytxfo.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qnofavit.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2epghyspu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwujaev.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fybyyxyf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkxslig.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbnnugk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2velqsuiv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2meszyrol.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2juydfcud.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxvcjyd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fizghnrg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzzvoqf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2bharhbne.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2prolvwcr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrslpbz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjlqusa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkemiag.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlnvtml.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mxojgykg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbuwwaz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqzrhak.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvjpyon.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvxjlai.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rggiajlf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpktxqt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsqrsoi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxjifjy.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgrcdvw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdahppn.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zkybqhlz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqakeyo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jhattesl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsfloui.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qidurecp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2klzallvi.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbmlyrh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2omtcydlk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rafynxor.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpdphvp.html


<!-- 参考信息 -->