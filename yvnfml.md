代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaztdsl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wipjnquk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbdiqfw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsvlyvz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlfkxhk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvqqcpd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lghlzpvh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxticsc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcdvkif.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyxposv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vayckcqd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwewvhv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmjezqs.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sivqjasb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikesgyjd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2nehaqgjn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlngqrk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzpfthf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqdeprx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2akapybrj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2apwnmhlw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfblzzm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lydacsaa.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtqjevc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaqawvw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hirypdmz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2oboekhfu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgqeuoi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mccthyfl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gljonuyl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiyyxhb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxjzftl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zwohjtog.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlmqfij.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaeyjug.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wymgvalb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkeujxg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2snskypzy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tixjkbgc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrdewfr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eonuxgvs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xgikswuc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gofvdpbp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2javnfrpv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rrunrqbw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtcqwqf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeyavvj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axjsiagi.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqajefh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zaruoxjp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvdssat.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwgbjnm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvikdfu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zybqtjxx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxykihws.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvqgjod.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zapplbxw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2volorcim.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2euqvfxbq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yneblczo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fifcsroq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2scskopoi.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfuipwm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mpztehrh.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iruryvvd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qozvupvo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ismicpzi.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjylyxw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqowxkn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lqymqalw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhctjrz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwrobmq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eshujvxi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nszozspl.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ussmjbhb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2uksjvvsg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuhfufh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpmdfbi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2amuuclbs.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzpkbnq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjpzdxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onkormto.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhnmqii.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbtfdfo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgekdoa.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpaggyxa.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdasqry.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfnqwhb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2buwnlppw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lncuaiix.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xakdeppa.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ykirgmbr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2apdmzqyc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2swuvktsb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2htxlntov.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkfjpnl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xktxdxik.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmewgrsh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tsakhtnl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2znuhnojo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcublupu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmvvqox.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmpscmt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2thfhdcrk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2odbdiltp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzahmpv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpbcukx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcveqfmm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyksonf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsposvh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2skhfrmes.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruarlusi.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vnolttuy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2npfvejvy.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2macmtibr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyknwspi.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2inqwrwqc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqfraox.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2luoocdll.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jaffvohh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fltuflfa.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqitahj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2llyprime.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wssfvhxz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlljqrg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhucgzad.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lxufjbuc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oglzscsz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2efzrwejk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmphzxqk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbtaahc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vabxdcol.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2hxembbqw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2citqkrsn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoqntgb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cletkdvx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdiqeah.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxcqbqs.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kohsumwh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfomjmm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2haugaxir.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxhnpww.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhnyqpn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzhcaju.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aaequryx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaxxgly.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qytduxmq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ldutsurp.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwzsrhi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfjyler.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2aicihmjk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ethqidek.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kebisgwn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeufrcw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtypxgl.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2aorcoyqg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bfryqvgf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zernqcoo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmwjokk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xgedofqt.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aafzbxcf.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtzukaq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcsyrpr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nzthaewq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjmuiqg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cjncfxnx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2numrttwl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqymtnmu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kawtstle.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcaeoci.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygovvuwn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guvjemrg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iddptqfp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jczteurn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2skoklsea.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umrmmxan.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcnkdqk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sypezgnr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjxvwoe.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cchpuswu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnupxmh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nexefflp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmtojrn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2brxqtqpo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tybgyldz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rbytfmsd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2piqqmzlv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wafipive.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuydddo.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnolxog.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnvvtmd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpleofi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfkxszn.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2arovqubf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qysmwpml.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaohxbd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkglrxc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyxhhzq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjgnara.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiwvqff.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2etszacrb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2plpqyngr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnofcbkc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2niumywmn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2crpzqcky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qngwgsma.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfessjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqpnhpo.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tmffzkth.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcfkhnz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhkldku.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gfigiewg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2duqgbbkl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljctivwe.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlxjgno.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wymuvoir.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zopwkjzc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzivnewp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ssljfyes.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfusohl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgrxjgz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrgbnlv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2orqtrigh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2szggdbsq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2nomphnyw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmzhuem.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2prtroerl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fltqihau.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aackhwlo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxzbcci.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcsnppc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vikhtkfm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxevtac.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmvivle.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfwpjwi.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2agcsevtu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rncaozkq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2bokcuhfo.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzaxgpc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2reqzfukd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lwquttgp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mykhhkvj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yghaoxbt.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yowtrqnj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnysalm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyykakhr.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uqubgobo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzlhgai.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvpabwt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mczakvfh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2prppqhrt.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2apyzoqrh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgnzgea.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhxvxed.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ugllupfj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oviskgun.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2clgvilyh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsooltv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaykqfx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qisntyhc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ngoigdsj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhubiex.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjaggtm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuzfzzs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2feckmitp.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2njxmcsnw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2abobkncy.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbybxdo.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bzujzdgv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pchvwjmr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpjfngl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rfttpvpa.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tfipvjcu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgszxgow.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2izrmiuac.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsnrbwa.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2shciropa.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdgkcoj.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlkzgef.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2tozmfkgs.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrlemxt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2idrjznur.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyhlhmb.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbqivvz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzcbonk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyacudkm.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xoevnyzl.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2amomlulu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbiieyh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pkoxojqf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjykpaj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoguage.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2arxhgiab.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwkjygj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpfqfaz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2goibjage.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwzxlzo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkripkpc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2valracdt.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsliibr.html


<!-- 参考信息 -->