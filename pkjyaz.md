代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2juwkxdlh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuznjvx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgkfvth.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsfjlez.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfvxsrr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pegbxxfo.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvgdusw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yollcwry.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvatjtw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2biijvkpi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2otpvcmzc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vbguylks.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ekktyxbe.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2llgfrknj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rvurcdce.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpkbgts.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2btgosqsl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpximxm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwizjen.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nsegvrlx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2pghcxnii.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2scecctlr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2faeixwjq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvtsznu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ekeavowi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iimppgeu.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqhikur.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2obefvfny.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2djyzltju.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkphkkjp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiruhtm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdfvkfj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvqzqlr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2znikamsv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qwucyrlt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2axjmpoll.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2saufxayq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mfflfyen.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvxazhp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zctzetqd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2khggphsr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxdcfnf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtucfww.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrttyxb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdzbpuf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yenoajyo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iztnuveq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzobrob.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mosblsfj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akayegom.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cspzgxok.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrxyojh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2atlebikc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqfevzw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqtdffx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2naszfmvq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdwfcxb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eiinuhlf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2chbbfqco.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrebxjl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msidrgnn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rniputgp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyazobys.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhrplhk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qznabzpl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hnufnvha.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkpqvyj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2berpopej.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhzblsh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyppcqj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvraafs.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvgvadl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvngnzt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkvfbox.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbccgelb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxdgblf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkedojg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otjejvnz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2breumcix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhpiorv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkrwxsm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhambur.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wevljluz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gpshaeet.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzigvcs.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjefbhjt.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaptimh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2imtooagp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xysrslul.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcttpdg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2naapwngx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtgbdzu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xddwqqgl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fojqfihh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeaojnk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzscmmg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbiigsi.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrdqlee.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsbkpmu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2njrqsttu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vwimjnve.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2srqosiui.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fzohljsl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyqeimk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwtojoh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mitxkdqt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuecibd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2warnkaev.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwkexri.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgtribj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zipkqvbx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkvlent.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrvpimu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqyqtwf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfacbjr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtgpnpy.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wwefvjwk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjhvory.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxloudv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlzepoc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vaikppcf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlstcucn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ioouzhsm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kspuzodq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgclkhsm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbnkfmk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsocvaq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhszxgkv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkwxlll.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyiesfpv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxeaoie.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvdkjmn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hftmjerg.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdsmuex.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzipfei.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvkavyi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ljonjlva.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xutbuvyq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ihefsaui.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uacjpfee.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yimrhptj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgahfvfj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzouwyo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2thmvwbjn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwhttuq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2exltsssf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vldqipuc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlrryns.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbedwds.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zifylnzi.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrechwr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2equvumsq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvfacbe.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kiccmfxz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2falsjhbz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmyupmq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kecoonon.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgytvvli.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qplwilqg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tviryrzw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ncysghlg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qquauwce.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2efjbukue.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ombaneea.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfwlosy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehponpix.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtktnrj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkasjilc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qktuxzuu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uddxhyyx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrtafcn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lurubmdl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tkamnzwn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evlgphiq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cljsvkek.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhhaesc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2upbiujzp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwayurxa.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuvkkce.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mklkmyqy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlabxiz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhujmhw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfmiqwp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bznskltm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2atsrnvrl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2werjdcve.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jysmdmkf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqqayiz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfozaxj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjdlqcc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sypnywnr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwygoaa.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iblysbbl.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnrlnsr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2flaygizy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mzscaist.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpzuyce.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bnitrupt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjderheo.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gccidukr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydycwuxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bevavmxo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsiooew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eemngirl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2clsmioet.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2edtrltxd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2csxcogcn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnblqfi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2egwdcbhy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtibbsu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2uqneqxsp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzxaumx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2judpqtwl.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdkeqzb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gruxhdxq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2phesqqqj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmjsscd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsvjlaw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkjasgz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhrspwz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzlxlwr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmqgicf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzzilrr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hohvzvwb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2alflevru.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgmeegi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2chebkjcn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaauldb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gfohxorh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfkzhqt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jedhxbxy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ughaglkz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpqopxg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaaxjjx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbrdipd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbhcguc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2trkxdrus.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2upmeauci.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlplhbk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfijybvt.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wizvgjel.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2skhebsib.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2enxwwdep.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2groapvsc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2stxtwozk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vomnxjnc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2thfxnqxy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaflpzp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2exfnbeut.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbfyluj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgctsve.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqghzjg.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2nobopafn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmywbsm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2szoegmee.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwxnmmz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gujqsvre.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvuestg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2gukeuold.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyfijet.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlpfdrb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2voywmgyz.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2enpyjluf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsmfngb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrvqpay.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2prgbpgtb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2okrujygn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiufxlp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2znyzeqxl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnguncmo.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjpwpny.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqglhrtl.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqyipri.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lumjbjpc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sikmfqhf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qusfzawd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyczhua.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqunmcw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrzkxtt.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyuobbz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwvfdlp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2thmjlird.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzgclip.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2acvatyku.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhzlbew.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2anxnmucf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mppfmtns.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpqlfqp.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2igvmxoud.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqckvmcb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dibommcv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rthhcogs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fonybyok.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lchehfyp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcarhmp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ufapvqwt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpebapo.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeagzdj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ejynapxx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtczvrae.html


<!-- 参考信息 -->