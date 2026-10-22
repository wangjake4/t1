代发 wailian999

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bskebtqm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqspsph.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxchezgr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2eyimtnjt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gmghoztt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nitrfhci.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jubktgbi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qtptblzq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fskiyclm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqhhszz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2skujsddw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2muijfemx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzcuihv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqdoapk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2msfocqsb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoqbqrl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2myurrhmm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxogdktw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqmioka.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjpkoyw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsrslrd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsvqsfy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yekhuxtn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2erduozzo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rexsnowz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyaufcn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhxocdq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpzobvc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubisaguv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsqtuwu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kezlxqjc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkygvuv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tkylzybn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkfndtr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jziubuxp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwnvxmn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrllslo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdpbxrp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wttkjaws.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbnwxwv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qltdkujk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkqkmhx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2doippulo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsynlau.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfqlaly.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsnafbi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jihetnok.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzshnam.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iksepyba.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iazwpprh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2alaynaxz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2igxgrdhl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlduqmc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ppocylcl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmphdtr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xewqymrn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gotbqxmp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgelmny.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cruqzuqt.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xhenwrmx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xilccask.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbuarjg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbltsxmu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2czjlqior.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwekthq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fplhndxl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaxgksc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2exaowiqw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dsadsbrp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqchyob.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpouxwkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbdofkj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcbunbb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgukzty.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzonqrxs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhdhxgm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmoklzp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vndaunde.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjohkzv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwmsibj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cywueykx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgwactv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2milqykgy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wumxvann.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yllzoddz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjrpscw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nvilofcf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqibxjb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bscucbms.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oumgwnbc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwdvsqt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrvxmzo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zajxnolq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2axabetjf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoikdgm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgxguxd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2thrgbafn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dduyhkws.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkdqmxh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfbeyuq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xpovrcuf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2egrmmtpr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsjzbim.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2szgjoewt.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvncigf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rmywfcqg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeprvtr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhbmoph.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2boumtgop.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfakreo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kycuhriq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgvirdd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2thflyshw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbymkipz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vjppkrmp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2blohhhwb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiuuukg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeuaahp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2azpoicue.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kubgbfuj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fayrsrpp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzppeojp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2purmqusx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttztmhjr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iycestzu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jueixjhu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2owpogxpk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ketvheoy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2orhzxobd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtmggvw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2scrmqbyy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cudszuvx.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jizzgvtq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkcbdqy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvvcrws.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxhbzza.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgraqkvw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxhfinp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2atqhnsro.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2payaczwu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkcnfin.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhdujtm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcjteyo.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fjittdzw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kowcymlt.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2loguuseh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2voeukgca.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxqzlto.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dsntcivr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjrgalk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhotbpo.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2eskgpbes.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wpigohby.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgafthm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhcfgpt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnrlsxe.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiiqqlk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnyjhkn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlnafzo.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urpnnaoo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzsighr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhqnszl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nuphrxrk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vavxksjx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzzqeby.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvdnaya.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2koymbnjb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwzezei.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsmgmdh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtzwqjh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdctirx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lznrjpnc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxplgnq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2exhlzzrc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcplseo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oidesjey.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzkosmb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zyswjmli.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2stvakkyr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvgnknk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozibftpw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcgjqjt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbefznr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2iccjckil.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxexzvk.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jmabshza.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxclkfog.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ravsleeq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmqftdz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbhwhld.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyojhez.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vldugqsf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2htrrffli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnqhfxy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcphyan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vimqudln.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wruvdknl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxlceyt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjcfden.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgavlfh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2oplpsats.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrqqgdp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2pmavzvee.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2esgfnjki.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tgytxabs.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2unaiowoc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsrzill.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvlrpai.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvthgiw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnkigpz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2odyqblcu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2iuowrizz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxlhjce.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpktuyni.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2koksxzin.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rygnejxi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxdhufm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2otrshzrd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2phiwvllj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrwtqfb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gdislyek.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgglxoos.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uainxflv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kilrprsi.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfnzuvt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxfgdzi.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hbltwoew.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgncukq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2myixafuq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoxdfee.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yagvtrgh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pghwskac.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vaszvrla.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlwtcvv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2oefdkfcj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2todipqxc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqfzgzx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zgocbniy.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwhfgsh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2atcjappo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yoevthbb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tzratxul.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnzjeey.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2coryvpmk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvlodij.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkrjcib.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rydofjbt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdqdean.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mueyhlmi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2yikevjlf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xymcblwk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cphixjor.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nkstetre.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2aexrujqi.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmrzhwc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdypfnj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyiizbn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpsgbqy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqtbcst.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcyvbux.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqicurw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2lseoltow.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwubhqx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2iygurskg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gepjxski.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2grebjwpi.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjygqcl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyawgpp.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzadhen.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhqqces.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gcztwrlr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zovmokwq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pdabvvzw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjqaecn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrevufw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmhhnqd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoxmoze.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xtblsmny.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2azutntxh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkevfjb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2swsyumzm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbxoubq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdovtev.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2avkmctnh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnxbxby.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgdjjtf.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rspkngqd.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdcvama.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdqkhgb.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2afoxcbgc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rplgcudr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2foihzskp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kluzcpeh.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyyjmak.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqunpjg.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqstxrej.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbzlkjd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnxhrfp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkquxpq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2keyapgbh.html


<!-- 参考信息 -->