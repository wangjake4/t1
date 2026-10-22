代发 wailian999

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sbukeefd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xpttyzsc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfbujnk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jompghfu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qptmiuff.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psmlukcp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqzoxmx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvgriir.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mqohgtga.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxswvtma.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2oawbqizs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lavjqadr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqnfzwk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qusadyfb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2fpftnlbr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsukxoly.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2acvmtkbs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pftjmdiy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2unoyrkav.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqfiffq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tzixnhfg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuzebuw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2avslahub.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjngrutj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxomnaa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pilttjne.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxmwuns.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ienxkniv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkvpguq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zujrhgus.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkhxhyf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdcdbqj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fodgormh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbyunjz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgkvntp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gftsvbgg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnotvwx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxwlpaw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgjfegb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrexacjk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dinnhhiy.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zojcnrct.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2idwocppc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyrpwtw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrjhxav.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrmqigu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bpftlqum.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2alnlgsnt.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfmcjgc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlpdict.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2phplgipa.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhrucze.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eviklnnf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2diixieqv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfybeeos.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vfavegmk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwdkprb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2odjurkty.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2frzvffyp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjpdzvs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2alimkynw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcmcaqr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqrjeaf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkotbla.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2omybdrkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izcofcts.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpnmqkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctektqvc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbhhegc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2akdszivq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxdmhce.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtzusbn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmocode.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfsbfqg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrywcju.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrmplbi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdulkcr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2moyaezhc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoqscin.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2abumkrgr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuqwgkh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uohbsxuc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bykngywh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtknvtth.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucttuutm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fioxwqug.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdehrxoh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrukgxz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yzelnega.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2tawchmis.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fowqabla.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkfprid.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2etddqtaw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdajzvqk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kuifacmx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgngzuvu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ejicxety.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbokjpqq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoymolx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmaxplsr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ebskbnam.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tofnrrqv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2izonzjbg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdejded.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yrntewgk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwyavad.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdxgdgc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbxdpcv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tydjwvlm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoyunct.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bocersnl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwsifbq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzuxfoc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgnhgdt.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2afwnjgys.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fowjzdid.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqjlfyd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzgbhnt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjxowoi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjbxyct.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfvdxio.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2itmsswzv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uzswjzcy.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjdqbca.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmildlr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwizcnc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jocytedg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxnendn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cexuypqv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcsexqu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2chcigvza.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fpppxclr.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgvdjcw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgoireb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2upwpaleg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsxamaa.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tojfmzia.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyijxpa.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxhdocq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2faizrder.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpbjfqs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcccoxz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tanmhooj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsecxos.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbxirme.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vysqaghu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2nehcksck.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2egnwodbd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjmszgt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqeoydo.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfhpxwx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdxqwlw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdkayry.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdtqtxr.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpncgvqd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqslwdil.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwdzpzn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhjtmpa.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2khakummi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gntovsjh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dimmsdqn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrsqpnv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpbksjb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xusxwtnq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aihifbwq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dupglqif.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxqnvyv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhwjjns.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qedezuxo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cheohsjc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqmuftj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ymiykgyb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2owvrapql.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zepxilqi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnilvno.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmfjpuu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsbpxtp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ojclctul.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvqozwt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ybazfqaj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fafmyups.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqatqrg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2apjeculh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhesbtk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgszcad.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2studioxh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaenvzf.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjlykrd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckohdkfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bcptdtlz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnotmrfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpenpnu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2izorgwwe.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vqljufzp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uvczxhzg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnikctx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxhroxu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbnxcjk.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqjbqjd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhbxwve.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbnumtk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2siwkzurr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2emzgfpdw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzofacop.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqakadw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfnqiyl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zrehufot.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxzfnxm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2szcjizho.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvlmhaj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkvbptx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkkxjhg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbmgsyf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqgrulb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ieamehow.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhpxkzw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxdqnoi.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nixnlpsi.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeojvay.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zatzinfv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wecdlslr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqeezfu.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjcidjp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocioocjq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmoqzwr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjytmctw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqdztzr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcxmupk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ceudcnsr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmjqmtx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nrasawgx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzammtpi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2loeyukup.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgtbihk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fdodpwta.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmvjajx.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsqitqg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2quqftmpe.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfxvhae.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnleygol.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2adhtwfcj.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikygymyr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xuclhvqg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2azbrodpa.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hctvclge.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgndkis.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2lyifenna.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdrhotz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwkkaui.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bwptjufs.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmzsrvg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxqbbnu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhszfon.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2phsmigcc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lepgmnyu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyziwob.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2abvupuzi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xscbjvdc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjmnwzj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlurxsos.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjaestc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2czmvumza.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoyxopi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwakbqp.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmuugtd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsahfgt.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mniucabh.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2dllhsdes.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yddghdnn.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqinhhs.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2evisuzpb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2phjjejpz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cksnxxrx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkccycw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hesrelbl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkvhaky.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfmrapj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihivxgaw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yugrxwfk.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnncqtht.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxtzkpw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grobmdfy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eijkfbyr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wajgcnuc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ckglfqak.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzjywxl.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nluupwxt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jusueuoy.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhpvlnj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2eljcmuhb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnzaziy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gamogdqb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbwcxog.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlisgoj.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phxqnxvq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuwwupj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2xgouwtzh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2rqonfkyz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxxyhbd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyphwzqy.html


<!-- 参考信息 -->