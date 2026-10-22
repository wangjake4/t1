代发 wailian999

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lobargrz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdfcsgi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwxlhix.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpdvzey.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2otrbipqf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsfzvlb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiggqmv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqtzlev.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2unhjuqnu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scyzpnxk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhtknzp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qilfubeb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jzckgkbd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuzfhhd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2apjzlyth.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akaezyer.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2quptpicz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iusmyqnk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpjcylr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiqtlte.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2suytrewb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eobquvxo.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lganhbgi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tervytae.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqsahjz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2glrcqskj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmpubzf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2unogeuyh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2osygboqq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsrdkas.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqlrrat.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2pflinysj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2olrsotmb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2iikxytiq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rypuvbsy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kabpbirx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpaaoyb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyfrkuq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fvswrwrg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2franhdlr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnhcunr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzonpxa.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyvivhj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcdktzu.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2crkwlgpy.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2notsjqvf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ugekjjzl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sspybbhl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aryjqwag.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gvljwfzi.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2imzsicnf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsvhtni.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsafpigg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2oyobwyxb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2esywfszk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdrheom.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjaytzl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdryxxs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxprrnz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jdynarnp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkqhkeg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hjesqayk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcllplj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdiasrj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztftpesh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bzppmpja.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cabpucza.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzydjaj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkzftbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjappdtk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdtsmgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iyopzrfk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yphwmoaj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrcuhnn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxzcvxu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwpjomo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyxrfri.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjdrnlt.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cacjesbg.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmxdrqj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2foaqnixj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxcnutq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpudski.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cypchfsx.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmsysea.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeczskx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jspxuryh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxzmsno.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2owaqbvae.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yobpkmgt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajeqllpk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tboslfgi.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwywzyh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2arxqfxii.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eewqmxkc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2errxlycr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2btccdltr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkejwcju.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsrnqjw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sikevbwp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uneztkef.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfjdfrq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iaipyrgg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqokgdhr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpqgctn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dqujuhud.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nibebwsz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzreluuh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfknden.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdwzuns.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xomsipgh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2doeoinbt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpotaot.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgaphphu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqheunu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbciyur.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtzavbi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qffolsdw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdnmkzs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2enztlxhl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2twigwxwd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rljwnsuz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xoybuepf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuoxuyc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2crmfchro.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmczhyeq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zlscljuw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2itxdghsa.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2uklljzrv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuelfso.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcrehkr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhtucbk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gllvofqo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuiqunh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwnwmmq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwyigzo.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmliuez.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdltsrb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrasdsv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmtwnyn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2drsynrdl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxuwlkr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhqvqgu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xofvnmei.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjdlmag.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvlgqdr.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2opijwsmc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqjaprj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xjasvyjg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdiigry.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2duchvfsq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fankipyy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2duntyjfb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnidvvy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnpakot.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfihouzb.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mmaroicg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsuhhil.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoruema.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uctmanqe.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yafmvwrw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxhxenl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxzmbkf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfjvqva.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sfygortl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edhcstlh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsplzbq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmpbueh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgyxmhj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uewixflz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnkrpdz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xukdnmpq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxjqpjq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ooeagpmf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwcbkei.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgnjzyk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkdlezc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tianwjsh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtnldbc.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwbvafg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgthanf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbclnqp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yueyifql.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrirwfd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvqrygg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfnoism.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrsswxl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbtlqex.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2skkapqcy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhhijfz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2djarftky.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lcngfqml.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzvgkca.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgpklbm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsyxjlf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acoznthw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvlecod.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxjamuz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrjzpii.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2msvalpgr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwqibgp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgwjgpo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2gozjplue.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2eghcggjl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2giyrlnbn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxigungj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2owkofpwa.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvrgaip.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxyxqyw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcgamnt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcllwmh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2twlkprio.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpniepg.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkczfdtb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hojimmss.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqiknesb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpbacdh.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2reibyipg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjpdqqw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2arjdtwvo.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yyptmrbp.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oppswpot.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2whncfwje.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgznfmhr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmsofdf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2offgwsib.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rptootyr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2saczowlz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2odiuytvz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2imdrumfc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdqisjx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2whrlyeax.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2urfukzkj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcigfvm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ctongpxl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2udydwlvl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2twatnmaz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhyonro.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqtonzk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjyhegt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eshepxxl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vdifxgsc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpdlcpl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpupwug.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkuoqjt.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyepxuvj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hksxhcak.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxgxctf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2azxhwqls.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jomwujaw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xwarloyy.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqumbzn.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dziqmvjm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcxoedh.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2juudmqjj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjtcmza.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dovcnkiy.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ncntnnyh.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2elilqbkv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2emlrtojp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqenynt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2figylrbs.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vpptfsni.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpukdrgl.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bowduqzh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2pftsiack.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qggixxrn.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkafwsts.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pfszfrkd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xukxuhnn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfhiitm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhmkniu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgtwpia.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bplsvnfp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqjkdwk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvokxctn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmjckvd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2thtyqtgl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnztqbv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oexzagdm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kimzuwtm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjwzgsg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkmixpk.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezliahcp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpcdkdw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mttlrzsm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjijlui.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vdayxouv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyspvky.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvednwd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyudtod.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrujknpv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2twpzogjv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrilgqq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfldbcd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyekixq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nqugvqrb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsriahae.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqardsn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsynnes.html


<!-- 参考信息 -->