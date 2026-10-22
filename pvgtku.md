代发 wailian999

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2oldbxcvk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcakuoj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwdiaxv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fwicnaas.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ayusyvpq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2igzqmbgh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbwoyzh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mocwdjky.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbvsatr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xijvqurz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2yylcgshx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsukbyts.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2aobqatjx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2daxobgle.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnnzide.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fabtfetg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mhclvjsi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xeswzpri.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jhburcfv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nclgwwaq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dplnoxby.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbnxrvg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwemkoav.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdxfndt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2odxnojhq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqkfzdr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wexcoowr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvgdjqh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2emzezcdo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyriglf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnakepm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwenhrc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfbigoo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfkgaah.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxwzina.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2oocjoadw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2suupikqz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmsqqqx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbjzslq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vatvhcbr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2etboekvw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2afsygils.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2quiwjqqi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2slcxrkoc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otkhsxtz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2giebskwi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjoeuav.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uancrohx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkyazlb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2davkiwpo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxfmxvx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xivntowq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjilwkb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcxoozg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjukatff.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpkoisy.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jirdpmql.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kgapafcu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmnwnxd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdgciqx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2clcjukch.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmkpygi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcwdsvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzipnhj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2npwnajmx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyeaqwt.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nywgviff.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdmroyd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmqvwro.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2csjacxbj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dokbpuio.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hntxghqp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbxwjui.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkrvhwc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xrktvgag.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjukdqay.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wufdwbqo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeguagd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhmneki.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmrhllt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ioixbqfh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsnmrbl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpncgfs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlcckax.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2prqmbchx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxqreas.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwdxxgp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqykjbms.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkyppdb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aemwzeuu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2evyjbcim.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbltwqmc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2sypcyzac.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfgrbld.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzdfemw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyihuff.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqdnjna.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgcjpsf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tctpmcuf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jatxmrly.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwhauhu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2irzrhkwp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tbltrlyw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxtzple.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvwebya.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2anduhnbb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2brhjrita.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnhmjmm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmnjxur.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkjjnpq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2oksiciea.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2twpwtoch.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlqqtpt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrexsye.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vrplomoy.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lozxwucy.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xzipirom.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrhqhfh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjxopfz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2aziextpb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaaurjm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2afjymcnu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2afrjdjgr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqucyio.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkdoxhz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfrirzv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpcjuuw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnmksxs.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lurqdmov.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cyypleke.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nemymfem.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwzxbds.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2adavmkmg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2opmtihte.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2shqcqlyi.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vafcnjml.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkokaux.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbygojdt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2overbtds.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxnszvk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qyibfdwh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2krwgsfmd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2okgswqro.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqmkbdx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yrovicme.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsrhkwj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsagrsc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbiovvd.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kduohugf.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2kshpxdfk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqdolox.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2soakvaok.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2khffmkfq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udvmpkxc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sxywswyx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2envoyjdb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlagxrl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gchnvgxy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rqslkrsp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsttmrm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdumqjd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgsgfho.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ryikxklh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkywexj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdlpogh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfpvglr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2toqilnsc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rrikivvr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmcqbhi.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yagfgfve.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kugvgqef.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2novcahrb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tysybznn.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2luvymcvg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkpksbu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zalrjjpt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzzevpl.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rkownxgw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2owmxykfj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjkitdt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fstqwaxq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ookdmvjj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtlbdxn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpenpzo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jendzvbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tntkijxi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyutscx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2paoebsxt.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2maiyiusw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjvyljc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqwtbxb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kvymfchh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrsjvtb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvgiovo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qxveruyv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nisighra.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tmthelfn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2djueetwm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkpgiaa.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2leanngbt.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mppiqalx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjcwdwi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hijafhtd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2cncabgxp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uwibvctd.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggocalgx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzfcdtf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmcrclg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yphjwxnl.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pypnnyjg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hutgybpf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfzxuoi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnnkdea.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zobvjfah.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyvscrv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzkljbh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbqamia.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yaombuir.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpukccu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wogawzsv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuvwfpw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgzcxsw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2piogrocd.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2crdlpcns.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbyjuib.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofljzixb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sloaifpi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzkpgxx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuttjqj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pymvodxx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsxvgnx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxzgcte.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2plrnizlw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsyufba.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2frjhuzgw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwveflcx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwxamzb.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhbrsmr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vujtwqfd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtpawvc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrqahay.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzpggkv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2omusruom.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2catzjfcd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmahnpq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fbykmwee.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwujrsp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzgnozd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzkfgrf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrgzbiz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhkjnvb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kefgqcnt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2iscenetq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2obihwzpp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrsmugv.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsaadqv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2tkitwehr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiydvtqa.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgguumo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcpbtir.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbysxke.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2onisklan.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cmokqdyt.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tcinnxhk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2polgyzzp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2douzcpva.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2szpgutiz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlapthkc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sklltmsb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2yusqcvmr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiwdkwf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpizizrh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdesmff.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiktnakx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbjwgtc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzsayhn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2umlovfgy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdgqibk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pniglodw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsccfmx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nfldgzei.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2icpuktjf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjtxdnz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwthehw.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhfeiac.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jdskwbtz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwsvxxu.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjrzghk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2koqjqmgo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2stqmxuql.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jumnstyp.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2seynbocr.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2uehezxif.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmatwpmm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxowgtc.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjdtxri.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wfryhzoh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkeeldc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwasnbqp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyopbjeh.html


<!-- 参考信息 -->