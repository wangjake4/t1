代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhchdxbb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sekczavf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2swlxjsce.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkmooox.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzheurb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rafmkblq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpixrdv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fxarfpnw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2keschfde.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2klvyfutb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsyjfmc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fndvzvye.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvvuwpy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpoquies.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jvooeiyj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rolboofc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2eazlmvtk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2byouocug.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjjkcyg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnomnbsy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zybyetef.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvubcqbn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pmohblut.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2twwspiiz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbdkkqb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qitqavlz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qblwdoqn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfnegyc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jcddmxfm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgjfflp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuxgqcs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bixugpfa.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwztukzu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2csoaqlfi.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvqjovj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjvdzts.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqbjsmu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qojkjylx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ozorltbp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgfxecy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvmvyuy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pxswtqmv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2omeiomtt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhdgxbz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfayqlg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myxcdxuo.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuhvbgf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwftfmj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2foffkrpa.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxscsmiw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcqctle.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hgepbqhe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpubwgx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qujehiiv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpfqhne.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nrudjelk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wckbyxnk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxghpwu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnecxmz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fatvshzq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2adhutpoo.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yfutnpad.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujihjxge.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mluwsvcc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aycicjyp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjtwscu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwvxvyz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dngzmqje.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qggosayk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tihhtked.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqmdteu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtudpej.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkboiqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2doyzhcag.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2valjigri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgokllb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyjkwdl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhedckon.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoapvoh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxworht.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2akxvryuj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkrsvgs.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfcwquq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zhixtbmx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pqeawsnz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2iyocltzt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyernjk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejestcvo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2emptcqvg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdfnqyt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjchxux.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uigcamqs.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uflgluju.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgokaqru.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhaqnpp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjvysvr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kogeqias.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwoivag.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjyzxoi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gquuqdln.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2phfvxina.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qczqavui.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gjritxhr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2afcbjseo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2egwnzvqs.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2imgshvva.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhjvtcd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzjrfrx.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uavycwrx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvdxdtq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmhdvew.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hivjgkgq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdtyxlo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjurbwy.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkgrrhd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vozjdccd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sizixftk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uducipwj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwjkmzk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qavibapk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iiavzies.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2stxyzjen.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxgqwga.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2etlbyeoe.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlfbrza.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsrtdzw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjzlpbb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rchgraok.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuqtxol.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jctbvufk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyxldso.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkokryc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfdjmte.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yowurrji.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xsydnmmu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2abxzuapi.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2brkjsniy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnvmbso.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lilqeyar.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaplnhl.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2inwyqftd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcohouw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dmevarbt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tospvnul.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pouocmmb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rwltexix.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfrpcpf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2sjskjtwc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhqaowb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tesvxwfq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqydyxha.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wyogwxgq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iskipquv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwcpger.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzdblii.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ffofzris.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ndolvswl.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mkeyvvjo.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2avjgrnni.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yneaanqj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrkjecw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqznyhc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2arrthlig.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tolzimpo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2chpqyory.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orrwlzwb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzgtnsr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crstfmdj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgomzlo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbudncz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dufbybia.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxiakld.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkzjdbi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmbmieh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhoxchp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgvllcx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgolhdx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sprvmzsy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpqhzbo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2geymsylv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbdonwj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fepsuqea.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnklzmzr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uwitmtks.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhzcsop.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2drpxuott.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuvulkk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrkrvkq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2otttowdc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zrraklvq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zugwmere.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcqrhvo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpkfaxe.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pyymyemy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jifwgrbm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2sqazdpxk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2amparyxr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdijmjgp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2axsvoiew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrezzse.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxmrjel.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2epsidfur.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gponjiep.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bypexhjs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2eeulzfvb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2oiczokap.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fdidetoa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kllabhkj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lraanraj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tesrczbt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2akrtqsmi.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jynphdoh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mohxtfsf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2oncedrzf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2stpmowkj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2uffihhhn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zguwolkb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvelzewn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rambxtgi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2opjmpvyi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2btrbgwsc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlldhhvc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zdogswtv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bberlmid.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcefgiy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2azzeuthk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kantkhyh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2noloxdmz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzrvvuf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnhnoxq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2llllwksw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuphffji.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrfhcam.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvnntad.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkyuwta.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsiueff.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqnemlm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2libupvcf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jjclkzbm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjirlqga.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2dargcecd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fcashkhe.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjafohu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dckebykl.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sypgudhj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoyqkds.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rwemyvpj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdwkkrb.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2odfyiqzc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2llgekxdl.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2oljzguno.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2huhziaza.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuritcq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcmmoyq.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdaugit.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2kacptyxy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkcfimr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2havbfkeu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiipluq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sankhlsw.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgqehit.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wggioxav.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mtszkibh.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2sggkqrex.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2msutcbnf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtqftzn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxijabl.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkoecjyb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ulddedon.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbqrylu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbibgkd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrsnibo.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cdadlqob.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xridcmhu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cupnbwku.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rweufrwl.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoldzmv.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2irggnpim.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cfoglgnu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2skiegfaa.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2beromiem.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwktnsv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2kxesosmt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxbhqab.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzyjmar.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujujxtuw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2riywopwe.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2svhpjomg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sidiyepx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmviwxvq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtgxotg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2czflrcyi.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpavrly.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jdusodqa.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsqbjet.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coayxjqc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cideouqr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2grfhuqne.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcqligc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqupwlb.html


<!-- 参考信息 -->