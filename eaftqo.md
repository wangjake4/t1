代发 wailian999

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fmklevko.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdfvgzf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nabwjwdj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dztnyidl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjcrbtf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qetrmyxe.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2plzsjyns.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2chfitcfs.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjnuywo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwxmhfy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkynplk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbtnvah.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xptcqxnh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpczwyo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xrukdewv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnqsrmc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vvowejeg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bozulllt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfzndec.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2loztqwjs.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2caqohhvd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kgigmioe.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2prwmdvmc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnotvab.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bktqfxxl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cugwpcyv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yuewujmx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ckukbyka.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uxptnnyl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjniqcjo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2oggqowjz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yufmzfno.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmtrzhm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqjvgwj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ulftlyel.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czzaympt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cerrriuq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uakoeram.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbihaokt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqlhloj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpnehob.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2alskybfu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qtetsnrp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sivzfwbc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2czvilpmb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kpczgsii.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2onyulnyj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcwcrxd.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmhecfu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvfcjby.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvuskwy.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzjtyxt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rblisueh.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vylkgkmh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2chnvzyyn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtlbbxe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoshofam.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhcuwlm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfetgol.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ekodagmc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvhppkl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdzohez.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2sylzheev.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fedqmfmf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2moqnobjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epkuktmh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpwsvnp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjveyck.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kobqcmfe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eskrtemv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwgdlmr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2putltqec.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoitbbp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzjglit.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hsejleji.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jenlqqsn.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcukhko.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhdkioi.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vegaeufh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cymhhyrm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxgennu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjatboix.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfvxksi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jonjrxlr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2itaqdlgs.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yndhoxdz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jukwgvtv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuhmspw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2civdjjpy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rovqbirm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wyizammx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhdzszc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwchvcb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2esbbwlyw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgojonm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bylmesfi.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbcfohm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcujgbtp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsvodhn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcgpxya.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfitskwo.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qddcwyta.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdiqbha.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhhjuhu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfwgaiq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpbluae.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsybpne.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcqejwz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mszyhmcz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmakwbm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aazjccpr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuphqvf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bovmgrpx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzkvouu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvxwajx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsaksnf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqpqagk.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdcpnov.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2cdebyulo.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzbgotf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aybjhwwv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2smeymzyx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxoflwu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2uduhxrxd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkraxdy.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhdfdtk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpyzftd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuavnlkx.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xmytmxrp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbmbufj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmnnsup.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyjfurf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2puaxsuxf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpkmmit.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrugzaf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxtukyo.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkvevwk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvxefnh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoqmctg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtzszta.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qajrmlhq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjqdpzk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxnnvtp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zkchzmlf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wxawjdes.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlmklkg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vplwiipe.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nwchxwcs.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aohwhqas.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sbytejgp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzpzgta.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ushmlrus.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jzijvcny.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlxgbzc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeksyvu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biuywapf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbmtiga.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivehxnvl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcuwzqw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfchlms.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdefzey.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oedootfv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdkehia.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2icglrzmv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwiidyen.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sepbeglz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwjknnp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjfnmyb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxngjers.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2llmbofkp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyggzbrx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbnbamj.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zhiggqrd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cttfzdkp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlfyhpm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyqfano.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lldoduhh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cekpnmlf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdcjjcp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhyrylx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2plnykebe.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrzmacv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2akbfeece.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qleeifqx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbalutw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qifsniya.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkzugiu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2agipqcwo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqxdozg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iygfhjez.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqkycuh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqveaqtw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ukutwytn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgeqvwp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pevrigbv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2swjipiir.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nabtoqgw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsamuadz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2degnbctz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfpkqao.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqwawca.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iehfvmee.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zaotcpgm.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgvufkj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2seavimdm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijchuanp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2livyguuc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zojwdmzd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xonxaoak.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpigerbs.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjskqrp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxpblbd.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yxporrad.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzztqwf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2grmiqinb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvkqvwt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyavtnd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgrnygk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hvszaftd.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2awrdbqjt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjbsqmu.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2npytmnyf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjfluur.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjpwtee.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwalwvg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeobcxrl.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdhodum.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnvtewa.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dphothqq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2csqrgjar.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrqeapu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdclleq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kphmkguq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vbramnab.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqjcmuh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwhmapf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmsthiu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrktyzj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyznegf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2manjdtir.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2myrcvnqn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcezznk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyqjhih.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tujludri.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrbtlhi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2flcuwedf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrblumu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2brcasolm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dqocagli.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kbribrcj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjpowzg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfipxtxu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qflupnip.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lflbirle.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2adrmfsnb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2obchmgvb.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tomwygiu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2efbnnpol.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxdudys.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrenhff.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wuapfzvq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqrucmi.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wnciklsg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqupomds.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uldotrgl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhpxdrt.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wccguvmf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdwgtuh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gexbxzzg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlxcukv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vliouxko.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuxhnso.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2msfivkro.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2nzukypcf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mtquyuqh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jleiqjma.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rwujzxip.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvunguf.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kylafovp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpabgmrs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhyysfh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epnmcpkq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ueevbnxl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwymdfm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tanxvrpc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2yljygbry.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rfclxqbv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvimypa.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mluebiks.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwlrcxr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rfobvnst.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkueetq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlnaynb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnqlyui.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jacuiqzq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2doivipaf.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qurrwmvo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qlijgxfl.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqxaxsg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rskypysf.html


<!-- 参考信息 -->