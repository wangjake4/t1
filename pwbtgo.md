代发 wailian999

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2aofweqes.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgluvln.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2txpvmhzi.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtlvojr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wnycgmxe.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zygexipy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zcklugqv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2buwcjwnk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xembmlgj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpiryjg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjcnmki.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwvbjoy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2iftpsiid.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozopqivc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2stczxzkm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgvxrya.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ilytqiof.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcxjmjx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsazzvl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbfivra.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2uuocryic.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwapayz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2znzjngfc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrlzkbn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cwigqhvc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vuebbdae.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hmteddfj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkqqtjk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiplzru.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tagmohei.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxafhmj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpbegfr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrhnrpk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlllclzy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lezcxvqf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2redgjrmd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkjqeod.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2awdqweyt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2shluhoeb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhtwija.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtydmfp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zopagjro.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrvgoay.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqmcajz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cezaggcu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmgcgns.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ldznnhki.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyzuqqd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2klhzijry.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnbpljq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2amracwnt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlmgmwp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usmnotck.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zvglaipl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpxwndj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2awewznrd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbriamp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnvcmzj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqtqkhk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuhujnc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvoudcf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpfkbld.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tflalagx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdjqsul.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2owxkdlaa.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhfejst.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tawavezh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdtpnup.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjvxphb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhnhqwy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wquadbnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdsdjal.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nvejuzla.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnernld.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdmyikd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2cbicrnjn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2njnjcnpt.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgobyulo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2thvnolvv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrtfbdu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsrixxo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfstwvs.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmvbuev.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvndsyhc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nneqducy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2krokdouc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2onopjymc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlnctzn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqtjlrj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsllllz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvffwhwy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtybrylf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rptiylzl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdupior.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2brroifxi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrluqiqc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dmexafuy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfyeuks.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdubmgp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyklrqsc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2edxtrhoh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzugshn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeoasks.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2auiourup.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yictqapd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjmwdde.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eucjbjnn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcquflz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2djzurbkc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zewzhqvq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2piqegjee.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfbylzd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kejcbfzd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2thfasfme.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbuxgif.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuszdsu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgemwru.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxfefoe.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdydrjx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjovpqnn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nbloqays.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrqsmyr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfqgqaa.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiemgztc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqxwgex.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaehgkqy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fxthrqsr.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuvmfyw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2oeejsfnr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzggibgk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdbjiit.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwldktwb.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yykfwfec.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyyxtdz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2emdllxnd.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvpaetx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2svwrhera.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2aswasvaz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcijapk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlqquax.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxlagnx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjirwxe.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjscezux.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhhtrxo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeglioq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xeszhtyv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnyctcd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2njijqarn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvjgjed.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdsqult.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dloisecy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzagqqv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bugwsgdr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjzwnvt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jznkpzlg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dabzlowi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxtggcs.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwualqfe.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2anaelbir.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nndwegft.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lxadhgjq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxldcsm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdsknwb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkhclvd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2drmpqjoy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdpwgol.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrjgsum.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwszwgdm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2inkiuanc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmxfrby.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2shozlxyg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxcpbvw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuuhpja.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tzimofqg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtndckdo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjqbkft.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnztfcq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhhisvj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzpwggw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2syakudea.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eewhxtzm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ggamcnhn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzoxhbi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ziasuklx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgecivpf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwnuldf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2riggoiuk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfnzyvd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcwkzvh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkhkdzq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkvzadz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rvadxiiu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrgqyos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkrfetu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwvinhy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpiblgh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2aroyrsnp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxoagis.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2npntgvbo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vigkicnc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrewpkq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2acjfqqvw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfwqctj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvtxwza.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyfgsza.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqglraq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwxmiah.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygluivqk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2jepkoplv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cyefktrj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbzgxal.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kfprajyw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwxttkt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2azivckny.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhmmteb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kndofjof.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hipedvqo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dggdirwa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nexramuy.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfpqgig.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2apwwvblc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekddacul.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkebbpm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmpxlig.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqrfcrx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsuhdlv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2atubvlbb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkuzfjm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkdcxkd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrfowpv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcxmcyl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrpbzpa.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlawstn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgdzyvq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrgnjob.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgwedtu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvzdkiy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2evniaxxo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqcuovy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjtsqwa.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqbjmsf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2rnamyudn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrynmof.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2veaajlnb.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2iuojlrmd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2esknhpfe.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbfryjw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsokdaac.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrhofbn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kcoiqvln.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xohuixzu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bjurhuch.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvyesaj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2adwtsgoj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfxgxyj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2goqgdmcp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuojvaa.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvoyprw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qjntnhxb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ewznmqno.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2myjyjmio.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbkeari.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzsrxqf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2irlajsve.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2soefupsf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdiaiecs.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2feotsons.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhkrlet.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmfilmc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qscegebg.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vhirfcvl.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xestklhk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zyovztka.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkgettv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sovsyaus.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjyjssb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrpmewb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmyzgtl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2sovomidy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2riuipgym.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ajertdot.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzykdvam.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ueanutse.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyyqxrk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oueccupp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axxrsyes.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvkungs.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfjqdhd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgxahib.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fedexncz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bztawvgm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzkhlja.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwkrbub.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxfiydq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2mwopojmb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsktclhv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2iednxxlz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiuzzql.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpzwtmz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdtnfdq.html


<!-- 参考信息 -->