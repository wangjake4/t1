代发 wailian999

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrjpprq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2floqrhma.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jekjwigu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hzndgztf.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfxymrn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmktssc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqkondd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2drlbdbnh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2seqvanvk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvejvwq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuwwwcf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuqctgl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdjpvwg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfygfpz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2paeiiacq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ergjncaf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2axztnxsy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsffkne.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxtcmgi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bleqfrti.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwfclbv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiofwxmd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2idlskoil.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrjobuo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xiewdawb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuleftb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvmjwhc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuffoqa.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iahyfbyi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2igupvphe.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbqglvs.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrwmhuo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2blbxclhn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yajzazha.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2siwhwubz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdielmqo.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2obetnevu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvcjscf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcloupd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edrxnuvw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2unruscmy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbdsyga.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2frepyhzm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgtwxto.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdijytm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxguapnk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcehngw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnuxbom.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oygqksry.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qkasynrd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yxscstzv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fofxdahi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smepvklx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2spblftor.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2irgqbkdp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjnpbev.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwxujjf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lemjmunn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzpogly.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uatwohvb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rywwzsmf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zeldwjok.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgthunsm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvaowak.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkscvnkb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrwdatr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2heeawzhl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvggpmz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tarxvqyu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqlinmk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tiscowow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2esrfxore.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mynuadiv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqymnuob.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpfdwtm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ehknssxo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2icymiris.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2etwfiyey.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkeahuf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2imxszhxo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oqurfief.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkcgoeh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ocibgsgm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxiylir.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2icdlsjmh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqcjtrd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxlwppg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcyrdll.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbayakj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lylvimqx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhowoaxg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdephjd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2oufgoqfq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeuhvob.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2evzsdjbk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnxxumx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsokily.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjllymsd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mfroykbc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgbkxbp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2eytdbobf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnzpede.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qgetzspr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2okatjxvp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2grwnspcq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2htuclvot.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uboipjcw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2avivaxjt.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsowtpv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eelypizo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzufjyc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgufghu.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xaooikhn.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gizwhivu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqfsnfh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vscackzf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2baobagwc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbqeyse.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ervvcikz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksolhcvl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcxtskh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxslijc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnxjhtl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcnxbzr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtudomd.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwcmvqp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdwgobp.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzfthpb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2puzbnnnh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2emdgezaa.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwutpgp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpicinr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnomjin.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2agmwsbxa.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyrztvr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkogxzy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmcizxq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrvjbvp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvlulmb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkukzff.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2eivgzhqe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkspfbd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbdsiib.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hfobmety.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xltyqjon.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lchvitba.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lripnbbx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbkxnsl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtijvbo.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nraxzvxn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2izjmygfj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfozvdz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwuubei.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyjtzrf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hfouofru.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2aegssgyp.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdqkyyk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrtzyae.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2apojugwi.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyurlnhg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2idppmrxy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmngdbii.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqbnlca.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kshovrwz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cvprqsfb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbssvqrd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaxxsnw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kovsbita.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsiojtw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rovbihur.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqjheil.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2marhvjxm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwnhukq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sovaojcu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjeqptg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2irtfoiyg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2odemzrno.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwirkzy.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcxordi.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwmyxct.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjprwhn.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2stqdefui.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlsnjwj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mfaabjgj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiiytuhm.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zpikdhab.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpdxkmo.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrfgbim.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hczujmko.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2awdjossc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2azkfmurk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqcgjue.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrppagv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrwjcfi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kideiwsu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrumhmy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2asikgufw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2cglkzvkb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrcmjhv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2csvlnmnp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cahxyieg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvleiwr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtmvqba.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2smnvbodd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2yaprpfmo.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvngbjct.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxfkktq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2barimujb.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvnrqcn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmamlvj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2drwxbdhy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzrzmwy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2sksdugzt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpgjpos.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eomootbd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbfgcca.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcvstgv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxswoejs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fymwdrbx.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ootatiwd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ribxyali.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuuopwt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbuvvuz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqltzith.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlyjlli.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqmgqpw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxjcesd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2axgyjzrs.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzhmoto.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gczfaucr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmeauzb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yndlrvhy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiavqlo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mohmspjf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjlkqhw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2iovhhmnu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgvczss.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lhffnzgk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2uugjxftc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwizpbig.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dohxeoik.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2sycreyil.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxtidqb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebosefka.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zugbdgac.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiblukgf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoztpkp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2cebspqia.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kjukrniw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqumobt.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpzpjtd.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvukpbg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pspeutwd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tnomwktq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yguyrbzg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hljxqtfr.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rgftqgrl.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvdchny.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nrflvhhl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rytcyazy.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxsuqep.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2eglldglk.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvuhtie.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2mspaamzh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhqmlow.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyesrvao.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tawcrzci.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpebhas.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqqkdgh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rdferxjp.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgxmyck.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qaestavx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jdycxmgh.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2nygplyqd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtpkulf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzagvqeq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ehselvug.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ookguovi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmsulyd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2brlxlhcg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bvphjjjp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2umsusble.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2maujitxg.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcjzfkw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iztnjtoz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrpuizv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pjklaelf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2aeizttms.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wadkiasn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxjtdpd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2voistmpf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkzexke.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcgxmag.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2plyealsy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrcwkrc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyoiwgi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmuekpf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhjlgpv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrendzp.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjngtdng.html


<!-- 参考信息 -->