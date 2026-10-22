代发 wailian999

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbvaplo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btrdhgvh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2olqzhqgf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgkcluh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvnytnm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuiywob.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rulbcqum.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrztodnp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgfenvc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkklzhqw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgvqugt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvnwcbz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2emjmtjrx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjblyho.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwlvcka.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxcgqdu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2igeueuix.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmlmbqb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xngguntr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2syxxmlid.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ergtscmx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbadnru.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxuyzwe.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wiagwlll.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2aktotkgt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaswvoka.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2tflbcdqu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owhnefnh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsxaepd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrivxiz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzvitnh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzdtori.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsrxink.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jljsapdn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwgjhge.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoowzcn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtarjao.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sazxiouq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fawmlhom.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aldykeax.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aivcpezs.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkkozaw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpknhqb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hhchtsqg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmbuats.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2shcnxpll.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgylshl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ldszaiuu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2inolfzie.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xfasualk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2usgztjdt.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2iabdjtxy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiligzi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rveylzmm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rezbknhx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yinuqsdk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsragvu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ywaiacoh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2juwbysdm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ehofeuah.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaxizpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmbodyw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2diaduyoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzahalc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxesfvp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdtvvzb.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyiheze.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrlqbuv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dvynuwfc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjykpwr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2irfatdli.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrftlsn.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgdyquz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2enicthcq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfblczo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecviuclb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjhiqkm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrdwtxa.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjsejaq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbpgmgi.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dshhwocd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvjgcfb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rycvwbxk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvhgobu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkvewty.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfkvyyj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuiuthj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2itqzvkra.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mflcdiau.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2igotvdiq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyjtcsg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiassrmh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2eabbzbuz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsjazbx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zsucrifw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jysguvml.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2voiwqbnt.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfdlcwn.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wenmvdji.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rthcvsqa.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhwzmfx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2icbshlss.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2idhjjlso.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsrgeyp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eaigxdnc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkmgifr.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fagwjyti.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oebtsaiq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oivhtvnu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2byornmtg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmmuhak.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftphrhyr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2txwbmozo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbppdlbd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2juxnoejp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcezxul.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fucqfosw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjflsam.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfzkvdr.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjdpawp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbvpjem.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqugpxw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsmguep.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeiwiuy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2szwlvjdj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwifzrnr.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ufalgeys.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aepmokjj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgyqbpr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2moqedpwg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qpafyqab.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2krihelfp.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tprhfxrx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hfejzpuk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuhufkm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pbybqike.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpfszoh.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxbohem.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fajntynx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2folhoqie.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xogzxneg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2aaquwbwa.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcjclfb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdnfqyw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhrlfgb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhbcgef.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2chopjbqj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrpmtit.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aafvwaai.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2iautennb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iugrarxb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khdbgdhq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrreuaj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ongrvvtp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2irqzscwk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxymujh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkkdnxp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snsnuyed.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqoisgj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2proddbrw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzicjqnw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyfghwb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2byeksybb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwrlhst.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxoccyd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bamfevwc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwsymnv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmphged.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pncrukiw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2caqduikf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hefurnbz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2neovaxnp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpjjdha.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gycotxtx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ektardtp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxqxfna.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzycfdw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yvezjfof.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqupbmqt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvzbilw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjetpcz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zauoaynq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqivalg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbugfii.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2poxygrin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfmeood.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcesncr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imkldicp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2byzadiyv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gayhqqeo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoypqwn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bbiztjge.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqivcmq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2saznqzax.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcsdozn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2amqmuhuy.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgmnlhm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbblrpn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwdjgbf.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtbmhmm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2aepoplnw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2iluzpqus.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2chutikrr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nyysnlgh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxkugdj.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrqavgo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhztebw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xibkxtyh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsgsqfq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpjwqsa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gkasropy.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2betgwidm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrlcmry.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbtlxqd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjozvma.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugljdczo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jofpfwap.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpofumj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkejnok.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrukjyu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2spnybrff.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpbjzbu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2owcopxyl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkgctca.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2svdirwlm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfabzxd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ounfgwpx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqslmunj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2thbllkqs.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdzmspv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgsdkiw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2qdglauga.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmintlr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ngegabby.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oqykishz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcppdps.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2uncbmrem.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpooivhk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2oixieduu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2osqknaki.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpyysxy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2byltcodt.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2plewfrab.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2urbiqfxo.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfnnugt.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2aillgcsg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2inuqhplc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mthrgopk.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2aievzsbc.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgwjaao.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ytoohcxb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbehuvo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2puwfmosn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxptugoq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjlqncj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2naywfqdc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2izjqovpi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgcpwti.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqjqjnx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jswcpwrx.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2loqdmbwd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwcshtb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hayvjrsl.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgmhbnf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiceyvy.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zomdepvj.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuhvqbu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtjzkhv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2eydpavoe.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2lubczdms.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcncogq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2whkibzfj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2aequloir.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fijdnvzn.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dkopigwi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqwepcu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tryoytza.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgyovqr.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cydpyxdq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmtuvly.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnwwxtd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ldveytie.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2muojihds.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwuhbfi.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgklyng.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkhyola.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2iclxmtvb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtczhwvb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwigocs.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbezwlvv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2subekbql.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2khypueos.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2scqqdvlq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyojeyr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2slohsieq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujftjpht.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uzivycjl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfwhcmk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzaftamn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoyqhdp.html


<!-- 参考信息 -->