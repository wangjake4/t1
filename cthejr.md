代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfewbmll.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tustrdpg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2krawrqpp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmtjndg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgejjgnh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqceknm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cexwcrfl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aacsiuwj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2izymooyw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwfjhok.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzfsrmx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2eqijxogv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjotksh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hvskedps.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2csbcsfnh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oanbodms.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkcezds.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evkirtdp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxyrffk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2noehvyso.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wsstnhzz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrljzjs.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiaafmg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2naytjskm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2skklhhuo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlpsirj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hgguikok.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2byfoipgm.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2pefwtzgz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2duwjhywk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2skuyfeiv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ithvoinw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqufrew.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2axrjogla.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfvmjin.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjvzafk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rigirjnj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgkuliz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mekyntqz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hhigpiyu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvwothu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvpbsxt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnpquqq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyxgauo.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfoteys.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kpujqwfm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fclamraj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrbkavs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ujggegpt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhzoudp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsyidza.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqavaey.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvmnreg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmumkiux.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpynztd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2anbdcuzs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hprynlce.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2acmzfrxk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2znwjrzir.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxiboof.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfgcddh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvwumcb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2otjnslnh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmhnofe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iilpvwrq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fznpmfas.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsomgam.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjsgywc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvhzbix.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxhehpx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzvcyoc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcfktdn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fywczbks.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtjxrug.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2atsvpfsk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyrauqd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2egzsmqsk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvmzvcl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2grdnhjxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzykuedj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmucnho.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfiltre.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2satdlxqf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvzjitw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oxltixnq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdccbzne.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jwejwmhy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jozuytov.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnknzoh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrdyzsu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzlvdia.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqocdtzt.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ynztcinv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqpxgtg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zryzlcyc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2plpiborp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jytdtvpw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sunzfiar.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcgeswb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeienso.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qroimird.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjhkqqt.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2npaurubi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqexcex.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkvdthe.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2teojxwco.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2leqzyvqw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2swyarnbl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xojkiyzx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhpoenz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wejxwvfp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyiblsm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgatthc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhwvuzh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2smopfpxr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2amrbduus.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpybqtm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mphpnokz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2njvawjjh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cviidfte.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oigvkbtb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzfliau.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzoifmk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rofutwjj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nsduwbgl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyokpwud.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2brtbriel.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2clmkzpdo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjzuswp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmdxhmo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xotodvtd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cazcbenv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnyxzue.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdggwgt.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxhwnds.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xycbxhde.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lgksburv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2asbvpbyh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2knzjbwdo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zidvqxzy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2idsjypgb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqhwszs.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uhokxdtb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlejfkv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhobkowv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyxgdmf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcdtwrf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vrztrfec.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bbybkjmx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2abopkvlh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrskaej.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxzoveu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2khabkeja.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpkmxhj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwdpwva.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgwalgv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2juafhmig.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2anknoutn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2twdbnhje.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mbccjqkj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fembbztb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pvikvjvg.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvnwzio.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrlqslu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2neguxfjs.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkkszri.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfatrxi.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxnhvzq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqhpfce.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icutxfyy.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlwbkmd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apungaws.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmwkvqz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wucqqyxy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lppmphub.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fecwjlin.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iohuchlf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewomeprq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqagaff.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxblpvdp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuqxrdi.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcofwvs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrdppkg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2grxyzadc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjjlayt.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcieihs.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gapracao.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbiylta.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2phsgniiq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rttjdjri.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrodiuc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwkjqkg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2osltkrgr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtcoarc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmbksfe.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ilexeveb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnfoggc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iqreynzk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2utloibgm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2npbfdors.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgmcucf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnuvonv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2avpmjqvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njvpcdkl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zedocbiu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vdamereo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rergqqty.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oouwaozv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wdepiiok.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwelyyds.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpuidqp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiqrhdn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qowwntzn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mopzfuza.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoidyfb.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2brakcwhb.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxivvtu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrvtfdn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcazqbn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dypnrtcc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2guqceygu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdscsblk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pvigbeha.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xfihsyqi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqlwtkn.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbnqlxa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ylppogms.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdivufm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkjugwj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzepibs.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gtycbcqq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2srwtjvoi.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wpunhgha.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2acwtmwen.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnwdpeo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrvffyc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxrlqtz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2klvibhqr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fahejheq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2njckzvpc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2pysunxct.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyvujys.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tqotrsoh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xktdwjcs.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdmmawa.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2iywkmeju.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2htqncuhi.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2nsccayew.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnkusey.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2merycmlv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aimtsmgb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtimtur.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2udqmgqmr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwsdwws.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwmxywr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlmtqlm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2skpmiavq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zadnbakw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bekecgem.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2yciuifja.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xupjxjwj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2esrhpgtb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkvwczi.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdnuaat.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2njpdnoft.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbxxvwy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwdrylh.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbagctt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjgxdcj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbsuhgi.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dooxatqi.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvsvysr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2buodvgdi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuaqlwf.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tuctfiia.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzubkrl.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2exbpmflh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbnxzps.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2llgqbzuc.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfzjthx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zholkbui.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgcoxuh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjaeycz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtimsayv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bggxexpt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmkvety.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdfyrqo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpeopozj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fisvrfiw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmhpwke.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wlumkyiy.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2harcdmhv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvmhlnw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axpnbcny.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lccqnune.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhpoiyn.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lepaznmn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2amltkomw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkgbbzo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2peobkdir.html


<!-- 参考信息 -->