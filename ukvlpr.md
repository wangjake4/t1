代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxujiwox.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmvldfa.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjjnwdy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhnshzc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjynqlpq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqqsoyp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzbcsjb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mewtfjbv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdzpgjg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfwbadt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwkahcl.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2murwfeza.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsyrwxm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exiipgeu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbawbqr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gabsyvzm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2slgxypjc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hadjsyes.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tnecofxd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnwymag.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yikmvbmt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2epeslmsi.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2utvxbary.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2blswitua.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmsgcya.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zascgjnw.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmfpllk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zgygfjis.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gblsnoej.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2olpdpkdk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fvovfiri.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhrqgdg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2abymxbir.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnauoev.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmnamed.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtsxowe.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2sjftwezv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwjbpnj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2odeoejpj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqkyfas.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ttesyrfg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jpssknpm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkszvbe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csmmperi.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qjslxpsb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmenncw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2owdvtbzv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcxbeew.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgntghpl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwuljna.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoxgvsg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2thvnrkgr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2caulthnw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjcmklj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jruqbxsx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrljrew.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyqclep.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrbxyuo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zelmktnb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2srmizstt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uesdrras.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdclwlg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrfuprc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2segcipnu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yriozxck.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2manosiui.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sugxdmiz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtscyvi.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnwnshz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rgatjyee.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsjsqwq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnmagvq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2twvqussp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbrlrix.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcqdwgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oikwtugf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqtpabe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gorezsrw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqufwhbg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jxudvqkr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2spdowlzl.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2liuirsfx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxxylop.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pchdfbuf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yowtdmdo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzqcung.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhgzjli.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qofwulbc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsejhyj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2txwxgxaj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2efyvlkrq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2muiiptbr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hccsdcfo.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gphjurae.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2snxavjxq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvufphia.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcwcclk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrgcgyw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2oeunvhnr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nammmxyi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvydhfw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2btziavkl.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmftpqf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2otlvxarx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqnnwic.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpumbxm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmobnvw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2glzbrkix.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsnuqpx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sixidpyx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2egcarndq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2sitagqcs.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeuohqx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgexkylc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsyeaaj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfskzte.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bppqlagl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uobjnpmc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqlhkas.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2weytadre.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgxpgox.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oclawksf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2igqsnhon.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtekjoi.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzzdamh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nocsqary.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2eopwwoxt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryipwrze.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoptrhx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyowjpb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2etqqxuot.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dakayzuz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2steslrvm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgxculk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tsddjmyl.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrekcut.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2labihkij.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlivhrri.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uiryoflu.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdksumy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjqwqqt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zgexaovp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fiamjajc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vutqyrkp.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvyusye.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hclgihnl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkvflpy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wecmllrq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eajcyomy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgicnnje.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2adgmzlgi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlntafy.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhvxkja.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqycafub.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmyqipa.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2towspiii.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzzlcqu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrjdepp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2stfjuosb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2alxiljrz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgwirqv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2emasmids.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqwaeaa.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmyolos.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mluqgbgt.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwuctiv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2impglurs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amavhacj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyyjhzr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klmnvivt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2udlvusnn.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2iorhoprz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2crypgavn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loygihnr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdezdegn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2sexthsfi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skxynyqu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrpqfgy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2stewziqu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzdvnco.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbaybld.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzjetye.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvozosm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjipjil.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2meuczaoh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuircyh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fspptkrs.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfntspa.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpfddth.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhbxupg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcxwzdu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2magvgjmk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlibyhv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2srsoflng.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdpkxhy.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2blgvsmjq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpubonta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhlvefz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwbjfpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uckuflvy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2frqmjcgz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sfaypkml.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2udcuaexl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2etnrmvtf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyuitpr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxvuqrn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tplienpy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dyndekjv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2morbvgvc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vthszuri.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2szvhtcmx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2byryutly.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfcndle.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzkyszx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyqltuy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nisbhmvs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qdawkzdy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2enqurdrk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzwahxy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgvucao.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwjsttl.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtbqulb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2okfuriqz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zigymcop.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxlylrh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfmfktr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdpribc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqzmjjj.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2srlronka.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbucfmiu.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2euutebcw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2imddfujt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpzjhll.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2yritozji.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpyqwmz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkxxyux.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlllzyf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpynfrr.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhkkodz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnsnmqa.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkdoogq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2oisbmfqs.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuomgyy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvhvinj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zirfacbg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2prexnhhr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2stqotdch.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yonjnuyh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbvowyr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2psvenxwk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyewqyo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkogohiw.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2uezuhrna.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmqbnkm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqegzqc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bljjympi.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2acberiub.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bbiukbzj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoihgbs.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqethph.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdzvedz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnewixr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jtavdfsw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2eruahlou.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvajgkj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzanzow.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2erccfwmu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzonhamt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjgiymb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgnwrbc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2asakquko.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2iicvhxdh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pdufmksr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiqslwy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qqganiji.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kggicgaw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vbydsdwl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysowmvjm.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2elucpamd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqvhlhy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmfeehh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpgvmel.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2peymmdor.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpiksga.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuvlgvh.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxgieiy.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2njtjwlcn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsojvnbt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2awcqabqq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwgxllk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jdulsall.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjlcqlt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oirolmsl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zwszlmlt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rwoiwigo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeyvurc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ickzyryz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rrerbvsq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2paooxzaz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgkrjbh.html


<!-- 参考信息 -->