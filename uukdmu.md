代发 wailian999

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpejvvf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2birkibqh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2alonpphx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfruuho.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bertqaxk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhonuub.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2eggwujio.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwtjiuf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2znaalaig.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2abxmbrun.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcnyjwm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxtumyw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zqebmpyi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tllkayuv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2synarqey.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdvhypr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnkhgph.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2yuphbfia.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2knmpiped.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwwiwgl.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtodjyzr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdmemfy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2atueopya.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrrftfg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkqoxpz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yftmnrwl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2skcxymnn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sittndxr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fpenmnpi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sowqxeay.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxfvhyj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttomueob.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jkormzfu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgehjjcm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhjcokz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2muzpspon.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfduscme.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvihionw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdukruz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kacwtvnr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaehjzr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvwypay.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzxlxpm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cyghbwaa.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvqvocy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zkynwoes.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcdqlih.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoxkrbc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xunhidux.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxjhmav.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgwwevv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwvamxy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdftjdsy.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgrbqhu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpgwnez.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pirlakgq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdtzqxi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kekbnouv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxbpkdh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2llyoguyy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pksrczrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tawodwgu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2saevtkyx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwdagze.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmfpvgk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxgujpa.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ompontgk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpeqjgg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxcpfkp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsgrhwh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2isqkmbxo.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rzeyliut.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kqisaese.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2elpmjgto.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2txquwdtt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqavluq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dlifvczo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hebjrhyh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fjykbywy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfzebup.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2owgrttsu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsbhwzs.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkaecbd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yswozxme.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2revyymfu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuinlmv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eovzzetk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbfxhuk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ynddflgk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvultsmw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzhccfd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvfqqtq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxzulxd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2eayfivxt.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pplpuihu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2srhfmwqz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fybqwlnz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ywllaltb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjnmwbf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoqndxg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdfufxg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnsqmjt.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2upjyjbmh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eisqsaej.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsufwdb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwenyehw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zxugdhcx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjjhigu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbddnyn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rerftauq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2luuswtni.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbldffr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2finuervh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wytqffkx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2djbtbbpr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2izllyoso.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2prgoaxfj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjlxyxm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwsjtaj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxllimu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2imfljzen.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpghkwzf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sazzqfuz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwvtddh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vekoqgnf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2scdyuxst.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pastnnjg.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bbceecle.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbkbnop.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2euredwub.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnivgvl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2brevddwp.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2okbdiicd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oeehcrvg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zisiacyv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqjknky.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwwuzwo.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pujkwrgx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2awkmctsr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxzvdiw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrdtaus.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dababitl.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhyiclc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwrqilu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bllpdgzb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfnixvs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkjesca.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkqiidf.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mippdfsu.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjugkrla.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2adiwuzdg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnszkot.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrxxhwz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suvzvrup.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnkfvsy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwqvkny.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2iugyzvff.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hriojyhe.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pbewejlg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2foowuvtd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnlohmv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxnrzlg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwcnuuj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2aujqvrzi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvreqamh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2retgchjs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2drkttdjc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2deofbqio.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iwygjoxu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyinjas.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfnfcdv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gfldhfvl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jleqmrnb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvhugkc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbrhsgf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyrzwpg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpirebo.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhzyppc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rysmaclg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsqasrf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbmdljn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ddywsfkl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hthmkkzq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qoscseyq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsumwlcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnxfgkc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoobwga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrbhomb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnojcig.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tedhzsqe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcmxfar.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yslienie.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2heziqdkw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhngfuc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2rxftvitp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lucajmyf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgliywg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmlhlqi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hocgjngg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2repykrdk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2szdreoyd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2blhwwzux.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoxihww.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rubhtyrw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvuwhue.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmgeaen.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kczakwpt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqtxmor.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhjtzis.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksszhtml.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2unbzqnml.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjfnkqt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2amtcrgsk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzvaocb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwvmrau.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqcvtff.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2bsepawcf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqosfazr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2poeswpvb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhebghn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ikraniea.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuhpxpo.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cooesykk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrocqal.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2szinhsnp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsceznrp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2crvbxlth.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuqvbqq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdxzyno.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2febznwtt.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2owubegqk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrtdqsp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcseeep.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ferryjcm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsrmevn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbskkky.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbmhlhf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgohoadj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ddknmfij.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2syiyffat.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsantfe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cintukrz.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfehqno.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2eeozhwbo.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyvselu.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qhddcjqm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lcovvqde.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uigxlvif.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuuwpnf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2oonwezzx.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uuziqyfy.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbeyghy.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2noympspl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaaxjzc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zdchflfd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmkkuyo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugefgxep.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hggtsujo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ntktzwuc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjmdffd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ownvdmyj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkednjk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbjzpwr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kxurhemy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmxjsgn.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2clthverl.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bbicdczb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcambvak.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzlsvoo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2emezqyam.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmsvrlw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eckfvnom.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2thcjnffn.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gajjvazc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwlsuta.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsnrhkn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnbgjti.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juzvbfzl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnztpzy.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2jxicltjg.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhltkft.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2alhgfsaq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wktydifu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjqlmgx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uemgjciu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kvywqwbm.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsvmxdw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvctdbrv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdwavpf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmesrsi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvgwxiv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdytjpl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgfgbuw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhdwcei.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfrgjot.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zghizase.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhphwnb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkxolpf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gftixyrz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmvouwg.html


<!-- 参考信息 -->