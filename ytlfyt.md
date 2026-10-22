代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnccloro.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cbecocyf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuysvoh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rloxdrwr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkcncfm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbroakiv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2oulqyqxg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2iduoooho.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwbthvj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsqlsfh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfztjwu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvoagpj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fvixaydi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pghrjywm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpvyrzv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdclxtw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyfpuwu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbjsvdg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuvmepe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsfvvza.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2krrvzsdb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnbmvdu.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2chacmrbt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmowcwx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jautzaom.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdprolre.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqebugb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqoemle.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2txclbigi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlhxpyl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oehihiar.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdatiurt.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2onepnbsd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eijkayzd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogojjips.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgwxika.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2njlavuoo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyoogec.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fflhmbjf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imsqwacx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxbmsdn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nmscqbxh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xslysngp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgxvuri.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fymifcxl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhejsfaa.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2btcycrfa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmpique.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2khdrdjem.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrabdsfk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbdjhtl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmynbdy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jopeaefc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2boycwhkz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qntsrrqx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2apsrbavj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uocznbws.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pioiohby.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlsxakr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgbksfh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyxcayt.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2utmbxzul.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfianyc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zfieliem.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsowshtt.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aemllptl.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aonsdsbt.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cejjwioq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxwupor.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjolbrx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngugugeh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzjvarz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhiruep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nztlfqfs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbhnatt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gretvpyt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jtripwkv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2advzxdeh.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2srcrhhig.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkyhjtn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iyheyurw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfegzjf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wkunmshh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dscmrpny.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdcwtxa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeokvsx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qneotjnt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkdurln.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtitijr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlfdvpr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cagthdsq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcehasw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lknnywoq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxanlwo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpcmbrx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eryczjep.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxvilhl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2spxkpyqh.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsneequ.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2turckrle.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cavjxcyh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsfysil.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmaxhbj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxbkder.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uiugufkw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcrecoq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2satimayf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuphvezh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpdqfsr.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtxpoxo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2inlxextv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtzkytx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zsivxpav.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykswhwjc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvfsaat.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvbvatv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfqtmfs.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxhwfte.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvzydzq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxmtbyw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2auvliddb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrueparv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kraagipl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywunuiqg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmtehga.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzxggfy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zmllicfz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2leilldcs.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wrscvkmo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqxrsiz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2esqjtrmt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnsmcfo.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhqpgve.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqcjasn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2uarazwgr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bugqakyi.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2anepojcp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubinfbpk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoyxcag.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfvpmmg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbvrmzo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xssogmwo.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yszpnbkf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhzgywt.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dicyahva.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kdndgtws.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqhrpnr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrpavrk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2brtjvmdf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfomjhyf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrtntga.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kuadlvpe.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xddlrkti.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfewckr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zjifpcbe.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqdpkmc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzzypto.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mbicbzbu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzuxemu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2asehpwic.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2meopluzc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vaigdycw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbtekej.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzeihyn.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2obsbwnfr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsyptod.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnfqomf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgchuhr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrurjny.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prqlobfa.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ilchnufy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2khhudhnd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfutnzhb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxevxrp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpahwyz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2krpdmwok.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhpgiaz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2emsghapw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgmyzkm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2avfojhxp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyvvkfr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2csqlinbv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hehntslo.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ezloutzq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqryerd.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2robqitui.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzhtvwi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbzotga.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiizczj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbmylsj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeiozba.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqqsbdz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfouxtw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjngxna.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2adsjueai.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xclxrhbo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmurvtd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ustzvqzh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnossjoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unsqsajq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2txmiupjb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jpeaxroy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cefnvsnt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2waxoelli.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsjhfib.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qftcpzwt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2exqdkenp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyqimor.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkyovnh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmuizao.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jgniqpwr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2znaceuoy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlkakfd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhkqtah.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgqiget.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vyetjixc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuivlcr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjueddyi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrmtsjp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wziupizm.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2splqncqw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnysotw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqtjgae.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmprszsc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqmoyjb.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmotpglo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtonidn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpddamcu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2apuiccqf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yilepayx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdxazkx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxbrerp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ewothomk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fegpvrpk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2locdthyn.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaaiidu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtozxnz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwhtpkw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwvubxi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbqcgqz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2eexpbrya.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2auwqngig.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2dpatspoy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2aygzjaqk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pswbgnis.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2otyssdfr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjwbgfd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzsexby.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzeywpr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwfwhhq.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkpcbja.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2csbjynpk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xnffmynj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmffmpc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbkougj.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2llqswljc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2etcztvgc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjoweyn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmyfqao.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qazglxwe.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlkzozg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2egfwzuvk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dpatbtgz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2yaemrvqf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2adcjmujz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvayvgip.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfghrlp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2narvfmfx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuvwtvq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpoeaags.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvbovmw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmxizaw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ssywhmvi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfnvpde.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvdqpkn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhcdkwv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2babpnrcq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bitqkmcw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kztjtgcq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhdmqmt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lsupkumv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rbajpdpu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lvelhrko.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsmxkcz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2anoqeaoq.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2kazhghlk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lymjnvvr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfhhgxa.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfoxany.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyszpyg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cckyhlyu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2iumebkuw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlrqhdf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ujglfabf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkhxmub.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qliruvri.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fznadgdv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdjohqu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lljhtbgd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwfoydt.html


<!-- 参考信息 -->