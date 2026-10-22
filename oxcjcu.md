代发 wailian999

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrndbinz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kofhrkgd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zamqixlr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fpavvfxj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2adlzwmpq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2omzyudkf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyxvses.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjqzznn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2thhzzdat.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhpznku.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhdiijf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuhyioc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bseatiun.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ollfoyyb.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgetrrq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiqkhlm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2eazzgksd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2khaqokhl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wyknffol.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntprakrl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2spzhbyur.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsxudbv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdyxcbr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qfembslr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bafavdbi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kqochoev.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2osagkese.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmmailb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwtxhvc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2safxedjw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbswskbt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcyqjnc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kphuxskf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nahtdgte.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dphryylh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icxybgai.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfkufcr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nnseuhah.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnrwtdw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuuglsx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyskkry.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epcphlqg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yollnacq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkudlhgf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvmqwct.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnlorfx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjchjdk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhbcosm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2plzhtcax.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbpdhno.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhztild.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqmmklp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcsolkd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdpvcxl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqahfjiq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ljulpeaj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrhfyvj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cimjjrvb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eehbzrgp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kofugxwc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ievhymkl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfmkwpd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzmxmfp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ziejzatr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2edtupcty.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fllvgvuf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmukgvvh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2efrnptca.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2udwouiek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dphbkwfz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2srgnvahd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xctlhgps.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2onedbpys.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvtwalf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2feqkggtm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2eoszaxmc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsqbydy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsgnrjp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2iemtwixs.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kzetgpjb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zusbjnhf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pichjiqy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjcanlt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvszirk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfbiptp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdabwgh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxavwpr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdstmvee.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpmilqt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyubstn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbewtelu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjwwuqp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuusyvd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2micofbuj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmbekgx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2etefbouk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgmdgtu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jckdsfll.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbnunfp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgaifhg.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tqncuocz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2towlkkcf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkyccpj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2edcfomsj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjhpomj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzpdoqp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkwyuqi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztieoojp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrgbwtr.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzushxg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2svfvpefg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecslhmeq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyqttnc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhddttx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zutfoyip.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnxccts.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjnetcd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzihbgm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmjjvaw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpnjclz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2hqucrium.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyafwwt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2frqcsecc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vakbeoqp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgbkhou.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2izdxnlwh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjgqxej.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgllffkw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiwsdbu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrgzanu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcnkaot.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhayqca.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dhetampe.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlusnvu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2podjoiqv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqejzrh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwpklvb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbwhqgu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhyioyd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhyiyeu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kbficwhl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ayekpnrf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuntkae.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpxlsrh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwmmpod.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqygxhms.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xpieuamw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxdvahl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkbjvib.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhyygbv.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqyooke.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbokhiw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwqrltg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rdiqoxpb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qzouhncj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2alnvkduc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2psrticwf.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2agmlwzof.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuezkub.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrlhmhe.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bkypdlds.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmshdjma.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2euxjiadm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdirhpzj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfeurej.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyakqkth.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpawkfz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nheirabv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2alwpwddu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwldwhqe.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsplsiq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjbbcaa.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqjnbun.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtqjqnz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dddychrq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfedkyc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcpxjks.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pkygzilw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ueaycmyq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaycqrm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2grrwzzom.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qorfskdy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcdpall.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hdockkhk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbonejvc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvyzorl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqydfebh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xinxxppa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2piqucfka.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zshiudzz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2onsmxzii.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtemaaw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwotlvbe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtilclbk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzdccjc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozppzvnl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhjvjfq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqziqab.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjfrokd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzuiudv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfghgfa.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zifpdkfd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jetybxsw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsckplm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ryofgesg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkqmuqo.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyazvul.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdudrhe.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fptzyohb.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfymoicp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnafgxf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmxymeh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wphteezc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2neibwcqe.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyogisl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2aucdjkmy.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bijdopbi.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hromylsx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wythilzq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2advgrxsb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqeahec.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2efuusjrv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2amnemyqc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2thesyzqw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2okdjadvs.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwonfixj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhfqbpd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhabvacp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tecijwbr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaobfgu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwdiqbc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvukgrip.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dievckda.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iumxhozo.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsyfvjw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmsoaew.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2eygwuuse.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2axbodztj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxhckel.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjzlndp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsjqilr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhldcum.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kqujdclf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqcveiq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmmflca.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewenasav.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2fszhiahk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2latbnmrm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2eydpyrxl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2uunagjjk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrqzdyh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2demdzmiv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnavmmx.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgxwzzo.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbnzlnj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsdhumb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyhpbwu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2yihcgdbb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtljiql.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2czqpecxo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdtyqvc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2akqencvn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgjyatp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2oocojwsz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzwqxca.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2azbznzva.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrsripi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfkphgr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjsadmy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxycnut.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eheisiss.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwilqow.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2javmuicb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2meghlxzy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rilpwdqv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2juqdxshe.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvsrtvq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gefxwzps.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhintkf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2moulgkpw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbixvqr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmnagbe.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2antuizts.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdfzqjp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2evdmrfif.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqvcmot.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jniosonw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2djefmekx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcshkaf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpclcyc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtipjdt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdowmuv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvldgqm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqxlxhc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwwyxey.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cewdvpmu.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tfevcmlr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjajmepc.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2peohdznz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2krebajko.html


<!-- 参考信息 -->