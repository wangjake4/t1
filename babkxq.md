代发 wailian999

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqrurpm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvbzhys.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zomqyeoc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2grgalomb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dejhfbzd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuowexk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cliqguhf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lbicyljm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bfddenwe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpbkfwf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwuwcxs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrbkddr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyyewsx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rehegiqq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2touulicn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhsdamc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfwqihy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjomqcd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pemgybdf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2utyushyc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nivdpktb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2elhodjhe.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzkoluf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsihlbs.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbukuod.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdqueiq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yavfowic.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2subdlmmk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2okrevapu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvqcujw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgrzwnf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkgxzrj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjuacbm.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsffvfcl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jycacvzh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaifaptb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ippuhcfe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gcivqbnd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eggklwhx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npekchas.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yygayshc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akplgefs.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kapnfaxg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcafmfz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lljilxdw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsupsvnn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwizsvk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wftxntxd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydovujsu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zbthlksk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uejbgvep.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wdncbjob.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trhsjqjx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxbihmr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnjrurj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyrnqic.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxqitqq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wifobehk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzshcnm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvpgpuw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hitpeiom.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iwignuvu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpfvrvr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvrxymx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpennuw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwcmxjd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vebusobd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pclnclxf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hednualo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oiapjocq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqahvfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdbwjmn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdjxwfd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2djtswrwt.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcxxygd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rezmwpvp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqvczpr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2aoupldbv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmejnly.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2arndztyi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhprbag.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2crxnjjcn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2maszhcrc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbewpwut.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2opkkmmjf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yivbjbab.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2skswqldt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mspnaren.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxtqaff.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdgxsff.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ociioqox.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzvojhq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2falrsgrg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxpyejh.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nddregkb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnhvygd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwprbot.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwerkpue.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2irmftiin.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2coyvfufq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjcmuan.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcmjyqi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdtgvst.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoftaqy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dakzhest.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmensei.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uappvzse.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2duvylztv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zqicongj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaskhfx.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nylptwcb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrafevkb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dvccxnie.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyukwpt.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzhcvcf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgqkcfi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iorncybh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gscxsndb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkeflyy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfaaxsz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2thkcduta.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkxpaiq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fcexntnz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqrwzzx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2scqsahez.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmilfdf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjqbfrh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2afynlkqw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqlfgvo.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxvnlhf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwzxhgb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2unlwfjny.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzljgix.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtscigrl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeohbgl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwquqvg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnhcshs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzlesxr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xghfppho.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qisphorf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmsnohz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdyxyqh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uexzqwat.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bifgnxwz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgiukdf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpupfln.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvztslvl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbpuasz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nidyeefa.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vagukiks.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdtaluh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjdtdkw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpcoxgq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgbuxqw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xjetcvyc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqzedad.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wbffcmot.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbddrajs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjbzitd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erpzmari.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tfucqizk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhjxlgb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2waontvne.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyfkenr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlowgzy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceihdemk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbugkug.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkhoeza.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqvpxdq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xangmdhw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2juwrghzh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uykfmmab.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtitpug.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhavyhe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxksdgzl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2izymokwp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgtlegb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ippjgslq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2txosgayk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2irnggwyj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cptxmakq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkayqaf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfmxdye.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsbrpwo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2axrhgrwl.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uqldcvmg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2krdalkbx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kvllssam.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmgrtlg.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxcibop.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2grqiqxvk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvyfprq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsmzlis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeylfdi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbnzfsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtmnhoh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnepczd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qoeooysu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpchsdt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iunxxkxu.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwyffli.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tybmhntc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2swddjbub.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tycvvzur.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2cttdnkde.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvflyfkp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjjiqwn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjibulu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzurrrq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzuahje.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iorhyyxf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxacskl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wknzqrdq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlritpa.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyantcy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bcboheda.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yokctqqf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpadzrnu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfpxogp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzdrkph.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xeexsycu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlclptu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgreyyf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkaqybq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbryhrt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyledvh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2azcuxctz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vogjtgao.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rchjartx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzyesly.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrswrev.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfkiplp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyfcsot.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvaqoain.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsxdlzu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctooqlgy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2srtqyajt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvbcsdr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsdgxsr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bneptqpi.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2phwinqxu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrnluwg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xcygiomw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvvnmcr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjllkps.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgqfzll.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzfojos.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2sljfoacc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdrmdrs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpfqgma.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zkncomjw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqvpawf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwknzfh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzrkpwx.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2orxvljzw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfneeetx.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ethbfeus.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhwshyt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpnxrpt.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2muqwezrr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnevour.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucebctpi.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ijznznwp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2nehhphhc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsjndle.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2yejmyjys.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xhojswnp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zponkdxg.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kysosahs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwlajbj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wicftzxe.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzozkcw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzjozbg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqheommr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zamkzgmd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2imgnzqwy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lyubwcyc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdnwhvi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2iewgeiif.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kluclzrs.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2eogkinyg.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2aswhaebx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwgfrmi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2owxfplxz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrpughn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkwddpe.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvxozys.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lotthcqg.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzkfwng.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ieslobov.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hixswhud.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pctlrtbd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxkrngr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvbctrl.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zwosccev.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncurciow.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkudwqf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtwlcpf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwddvfiy.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoqrdmr.html


<!-- 参考信息 -->