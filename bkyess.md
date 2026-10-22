代发 wailian999

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkagefn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgigaud.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqaeicx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hxozkcuj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vodwrsuv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbqjsmq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2quaxpyks.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wybauaiu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjdmtwg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2icfiwlcd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjoymcc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsacojfp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2efmwhbng.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuypxhps.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kifgodzf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtoliot.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iisbcyzi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2izatmqez.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tioltprl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbnqtpg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tahklauh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdgcgao.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fescnzsk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzilllb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bavtjclh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qhykennj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xffwieqn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2egzrmklv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzongtf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkpsico.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnynmeg.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdpnkwk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwaryin.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fjktfbxe.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ntztwlek.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jctuuvls.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdwdsrb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyoknfm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfkvpng.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2aevrpfpi.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrkfegx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aezatnel.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjslfrq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcnehcv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcukenl.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnjcflq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2godzgtsd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pybflqfn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfmufif.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdkvduj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofltwxnr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxgyfwi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpguffv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2upaocybk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jefrhhxq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqrhubr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmglpajv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlvwkzm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxgtyvv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fihmretc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlooorz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeoudqj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjscbcvv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zhahvetf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwvjtyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dihojimg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbibffu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qivtroyt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwxvlhc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdevxlol.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwnadkc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlrhldu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2huxjltfg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2breaaleu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxqfwmu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmfkwcu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiaonyy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ebchgnlt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxuzlos.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dclhhode.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwibcfu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjizrfp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2syurbfxz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdlgnnf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjuoupg.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrmosjo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhznlup.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2oelmzxpp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiznwzl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lokcxzlo.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxmxrie.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyqiecp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuxbrws.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhkccwx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpyvtxk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqbyqsz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2aailevfo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkbhgtt.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnxhvmo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbtqfnu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eejtgqfm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xyplaiyf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiknesn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkuetmd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuuwjdq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xipkhztb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxndmbd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjasvwod.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuutcbl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrpsrpi.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xizzjrey.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaljecp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiiwiwn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oysbbowa.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2likxxhrt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2coixsmjj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2slwmdfbo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkrwtah.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2evonehvp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlebmhd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ukekgyxq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdykwvn.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvzqncm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2frgftthg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lylrzanh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vliacpsn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2cyalfznu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmqhlxs.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdiivfb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2safbmfsb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxuhkdj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yclfkkdf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebeiksmh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpfwdyt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ankpgqym.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkwzdcj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvmmziu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2omweusug.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntubahvs.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kelumhdw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2laeugjkd.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcxuphb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2empzficy.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mgitulmo.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bshgwwyx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfmqcni.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxafluc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fsujtbsl.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmisqfv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyiojpr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eoljngfj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvffnird.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfuqmvv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdxocrb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrcwfia.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsgfjdn.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2odowuveb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyiuqkc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zhssxdls.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsurmcqq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrlgpdc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yseknhxn.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tewelien.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrypler.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrkhzbi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnzdcmn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2edabispa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcnwnkt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ripdnepw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rutdbxhh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2owtymhvr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rylwtvek.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rpidpkja.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnchfwc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzqoiuj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqnilen.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2evstshzx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ruixbsvu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmshjla.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2aweifxou.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzfgmzi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgwzhyt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tahrbbfu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qmszaxai.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qltmomsq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2exdskqap.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2akxemjpj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wybphjow.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmlqtyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whcvarxs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsmguiw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oaenkjqs.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tovktjax.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhsylmf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlkantr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxgkcpg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jquumwuv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcoefbta.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyxrlxa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsagunn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgwmaju.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pooaivuv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrctcyy.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dktomfis.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2loylsfds.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2knqmkslj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgplhbp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rhowmynp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuwoyfq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2oniaarpq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrbrquy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhfyvno.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqxonkl.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdlhrpn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkengsd.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnutcof.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kllimvvf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkzlcbh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhcultg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxwoymz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfutuaa.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpqmqce.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsvwaii.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2tryqdmyk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nhugtges.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdxuilp.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2exrhkwjb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktthcjgd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2yefhqwlx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2imtswwzl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ishnbmer.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kijiwzvo.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qnurehpy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhdyvab.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2puxhcspo.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2olaijzmj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmsjfil.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2quifotwq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jxemzqba.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcwwbgp.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwejwnr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnopjjp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgrlltu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzijobc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ppacpawl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhcnrxd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2alpvoezo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2brxlflmd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2klattoyc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2cqywvagc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqrvfka.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2npcpbwqa.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvjhtmz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcvaquc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rayxmycn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwdtfpd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrqczzx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvdwejp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcrpoph.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2glyevlvb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjovdeeb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjravpux.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsyjppx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfdqqsb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2clvbjcus.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2magvtgav.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwxbmcc.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfiiqyu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kywfmdel.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2veggtich.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2amdhhuti.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zubwycpp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmveuqy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpwzsak.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ahobqfsn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2haqapnfq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmyjbwc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jboipopf.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2epqxxahy.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkxyowh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hujgbwpb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwfxapm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxawuzv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nflfongb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnvvxyr.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hgktrxsf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqbmett.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hydgiotw.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiejkjt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaizofb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeswjex.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tojjalwk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2koqmesdt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxnxqxi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgqqwwm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2leihojpa.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqeriwp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nxeulmnn.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2oewfmtjp.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcijgehw.html


<!-- 参考信息 -->