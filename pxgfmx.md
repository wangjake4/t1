代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2togkjftc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnlnzxu.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2filuwohp.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkyzktd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcxdzdd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsxmyag.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2onjvxbjr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdpzdge.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yvthqlsy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoxauvw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhivslg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2usoyqjdf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhxhjri.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjaypvi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2brkyxmxe.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqjcijz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2pukgjvfi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wckzytvw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxinilc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jikdmgwi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbihhfz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2henukiqq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sktfklfi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnbjotx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iavipbhf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fipxjyvl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jreuibni.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwjuabq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeyjhwr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vryyatif.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2knkxtyny.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgwriqc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2howhmuws.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rldlhpyj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrymzkv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wdehkllx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkqlaws.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2buhucymr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpwlkkq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrinird.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yelhyzdy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbnheqo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2icgojkih.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbmorsh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnfvodw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orxbugzs.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwbaelr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2skehkanh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfhistg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvyovif.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwhwbrk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dnecxzbu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmofuhic.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qjepfhna.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wycbjocm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2siugfkht.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnykbsr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lkztzopp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2keqnxkcw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtchxyh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2keqcuhkx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2syjagshl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuehquas.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tijtzvks.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxegtvq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iynjygfy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdulhfvy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzwxoas.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnfmedx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbetoso.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwnaiai.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxleafk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrkxotu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czydzbwe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvxmawf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrqdjpp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tsirthkq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfflojf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcdkmqi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjjspqa.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2giahyhrk.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2favamgve.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkghcwf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nejjyzuh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ephrpbfk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaunczt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hosnybfp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbhinyf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2abonnmkd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oobiczqy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nencqhiy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2baxpuupd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbqgiwa.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqetjurt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2srepwnzf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gttjplqe.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hepkxkjo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzplmgmq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbahakx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmowbvs.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhcraxm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpeojzp.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2owzpubba.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjvbyyv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwwsokp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjnteqx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2htwgebtl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxlcpal.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlxgrgc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2icafetnw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bedguhfj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxwuiyi.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmyzxhl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyasqrl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nanfjpzc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsyysmp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2veftdnoj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2venruidc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pukqrajf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2umatskum.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2akpfvcrn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmguwca.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnqheqy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiixvudb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rafhzxkg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaflsagq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdbwbsu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2piggkckp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwlgkur.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oahuxtlf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2alaosfag.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfxhwzs.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2omblsjtr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmycvcmb.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyaowpy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoaqczxe.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2itpjmcpf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rldymgwt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2njmrzqwd.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbylkun.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2znspypuz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcictxv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzqbmbu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kolaqzcm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mqimnbfg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ixseyxox.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmphmmgy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtcashg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2offdsrko.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2byabwbtd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aehqvjpr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxbtuzb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vbewuvhs.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfewmtje.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwaksck.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvvihoz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwemfsy.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfschnf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2udpjponb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2blfvknxm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nbiktsjt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2crhxzbqz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfpzsyz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdohwnpg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oocskjbr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfrzvpl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2whkoyvza.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbiniuhb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrjlyhk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxvmnjc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vdblfrjp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2goiadakc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2syxwqstd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqtvvql.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbwhkbi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmittsxk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mohzehmj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmkbhlx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfuzhlz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrfgpua.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2slvtfapw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkyften.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtlvxoq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2juvutjhu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uncejpqj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kczpjepg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrkycol.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2empkexqp.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrddblzs.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lejqlxsz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2olhihqpb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqvaelm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnhtdzm.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dntlvhvq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2futnvmcj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2spyvnvpj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwloenb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozisgrjz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbwzuzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tiebiazm.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hpygnfwq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xdefdjyc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2keblfdfv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qxiwadwu.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2czxcrrvw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2usowidrz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpinywy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhpuuws.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzgtpmi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2azwfwniz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgtbdhj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnglyap.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hxryghsn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2icozjfqh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuornxr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hlamksyo.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfasyik.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2umtznacb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuvoeqi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhqlhiw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrnzten.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqppifd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qagrdbsz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kglicovc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cadiilyl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2avdwwwhx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wuitpfmy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvvuulp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwdoyhr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfaquxy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkbhhzk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2eaawyuam.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2obkgulja.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlapyfjz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfxrjfe.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsafxwz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgdczbx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmrflqj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtbdflb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhieuagv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxwdomo.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2iliruqng.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2yqttaoxx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdlwetw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oryxqxnx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwxeesb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjrvach.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlomgoaz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvtysyj.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnsfxcb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nibtheun.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbdiyhe.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmercdy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwiziya.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2idjlpkgu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2udvpqwza.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcgkqot.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqxpfad.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsiqtbv.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbokmihi.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dvldgeok.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2vxohfhjg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yspdutfh.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyfitun.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxxsmcm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjsutdq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkpxqvz.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbkiamf.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mibbookc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxcsmyb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqcxpmx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxfuahn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrukuhe.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwgkipk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ljveuaob.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkfhcev.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnfvylh.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2vakqlkhr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hxncqhjw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2asnaoxnc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2aioudxex.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kozljfix.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2tauoleaa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiekdhfa.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2aerteszn.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2essmnfmx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhfydbj.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvyqdrb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtumeqb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icxlnaqn.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mlntevdr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hccxgwwl.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dburfgtb.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfisegx.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oczlxprs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hthxkocg.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2udeakuac.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaxydit.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqytzqa.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmmfxyp.html


<!-- 参考信息 -->