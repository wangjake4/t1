代发 wailian999

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ciavzdvh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvmcvvh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oecotjml.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vueaagbp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2sebsddnl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppiwmxxw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsvwqsq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjyrrxq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wqintmro.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2swdqlrsp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2utvnpter.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2obemgqgj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrqczfv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2evxurnwq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qlazzkqs.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2iaigzwfl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ypapprtd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2siobkuhp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dxujlsbt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dccibmrv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vofbfhrm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmmwafq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlaanly.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsxetat.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiofcmx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhuxgqn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkdgvpz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mndsfuuw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xuecczpu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ldixlcja.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzbzjph.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsephtd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2elgsfqkd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzalcwma.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbesdaq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2btsxazkx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxpjwon.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvtaaqf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cukvcxrg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vfagydli.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqizjojc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zpprvvxt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvyhiaa.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bohikjsd.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpkqsut.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hlefjnvd.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgpqovl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gnumwdia.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiusmqol.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2smivspyr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnzhawi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfvsvgc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asgpqgiz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2veugwcho.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvqrlso.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgpjzny.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqubazan.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2whjurqmg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2afedbtpf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdmqshx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2thrhkaxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlloilij.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uciqwjfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkgalwi.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbcuxsf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrxdybi.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2infsycsn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqwjkxh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2htxqiqxe.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2feaxxbzt.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2khpypzwj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdgwsim.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjfwuij.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqdeaqw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuabjgh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdvyaok.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gksbqtlj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2djbyuelf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpwvemy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhqupzj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxtvzki.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwncvjro.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2knheaujy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpfgvem.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2uqctkrfe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsxcbgd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ognhiiym.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnibxxe.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2khghdrxx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxghjbxi.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bcccpfpn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ictpacqq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ofntnegb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pggtimop.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqozbop.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrnumrz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2trdblbce.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtpmsrj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmbqmzs.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfrwzjv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2whhzryls.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2smrvdhhd.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qilnrxqr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjegbmnd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuodzwa.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsmnojd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2suisedzy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mllwojtf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zljcfypn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2chniwqlk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nvykfoil.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzchchk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cdipkdyh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcumfuqw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfatifr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmfrwlo.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lrscjvdr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaiulcwn.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsyycip.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdymzjs.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bonkzlag.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjodrpbz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qztzmzzh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbarqbho.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2blfcnrdy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihefdegs.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pahpmorq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2txlylkja.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zltnookt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gicipaio.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zeohqhhg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cnezufdr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbotyoq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lkotwmth.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhchvts.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2smtospps.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwmsvnq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnctdqho.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuecchz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2csutroyk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjcyryg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkfdsgi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2sltdaidj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ckymwkeo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ctljhdih.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dbevzmsa.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuyqzln.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnibytk.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkotymx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzrnoyd.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjspted.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqbtjtp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuyrytg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxbnzwm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hqokewvc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ityhxepf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbschzg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbccwnis.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnkrnzo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gykzjbbs.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrvblmn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzulwcll.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaymbgn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxeaqfl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkkrqcq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyqiygk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sizfcbmf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoctefs.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbhqlwk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pknruyqy.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oghmuwzz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjttyin.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxrcsxu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdxmskj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjfisxo.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2joekyhaw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dayyoqoy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hqchdluk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvweynls.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yzofznmf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyebsco.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzotazn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvecimya.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpxrekt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zakqhxqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgvoejp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxraztfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbyxfjb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2spdyogex.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvdjcwc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkvotje.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzfpgfs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rafdnkxd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lezhaclq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbblqta.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ialtgtqy.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpklhgw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyghstn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2byxpkfvm.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2igdcznyl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzwsqbj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqypnfv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpjrahv.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vojpycky.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2norfgpns.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuitsxxg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmdthxm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dheitllq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xopxgvtz.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxkgajf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfsyxtd.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2obxlcwnl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmbqzrh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvsmdbf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zijulyeq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtamjwh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxgtjkq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pplozcho.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2icpapswg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2gofsrbnf.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwrlirb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrfadqr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvigxyu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxfxkbg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqvatcc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcydobk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cmujkuib.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2orezbtle.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2uhumnmzw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcfcqdq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsqyhnj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2kduqbahr.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbevctg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtpzlgv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sfecaoyo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbyfaeh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gqiojxdz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfegtqky.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2duzsmjkr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2upifzhed.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrprrxy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2krgwyjmy.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ichgcmkk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpwlqry.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xchtqrgw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zlubwkli.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fuktzuia.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yznnthlm.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2atsbuyed.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2suefzryq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2prybszcj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbmffvd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bmulture.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jiimtexh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lunootnm.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yypsjhbc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nixemsnp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzaaqwfu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoghemb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xenxsagh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oxurawtw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mtodnmmz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zhusrzak.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2khbjgtaj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qibzhbyp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgexhbs.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tegtzqeq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkubezj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2epqilags.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ocskhvrf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeewfwf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2awqtxjuk.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2csszuwyh.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxtsqaf.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hlouswwf.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2euqijhqo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gisfpjdr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmplxrks.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpgzvkx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2atqbmpyq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmcyokl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjfobdd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfmsepz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dggkiwjt.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcssixb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2sykwbirt.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2amuyyooc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkltwpx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rviehkol.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2odtkmsqw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsqvllk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2umzgscle.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2uijgpptb.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jtliqehw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vuraxzgi.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpuwnnn.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdfcwht.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdtyydt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbkhuvv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdztmoe.html


<!-- 参考信息 -->