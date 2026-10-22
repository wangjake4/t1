代发 wailian999

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2efctcgrs.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gtukfcej.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rmynstbp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rqccvahs.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2etrcfenk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksggnczc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gniaegdx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjxynlg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2adzwxhrp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvxbctg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfaqsjl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssykqmqd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvxzpsg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyqkupv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2thhesejt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtslcbqz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcdfxkl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohybgcsq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjfdvhe.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pdetuypa.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2etfbupun.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2okqrlfwv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2plrikdzx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvobqdha.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fruvzxyq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2elritumb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkvqlww.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2eaayysvd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzzmlur.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdzozqt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zadpmkaf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jznfocfp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wttaqlvq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqlftvl.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdkngdr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgpgxej.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mrihpxcz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnabgzbk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgerjpug.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcgirbf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxeymii.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcrklfq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2prgmnyjs.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbenptz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwikfafc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvunfvi.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnbkpzi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtfyznn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bucsdvuu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wevrnhly.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnmsnbh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnnmpbk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2godgkqft.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjjpdpg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhoigdv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjyxqcc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hywdakzp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqkkbsi.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihawrxye.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ijclsboj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrvjwki.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hjczgfou.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoszwbp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pldkolsy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vzypoabj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2luxnvphg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkulyve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzsqiyv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxczoha.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xclzsfjj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgkited.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wiknowhs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjcfxeg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfomyka.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fupperzy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nkamwjqf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgbbsvy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkdgitl.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bbljonpf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzsbifr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwkvlgr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbdkbly.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oyprlkon.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuvwvyg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oegxfohe.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlvdaso.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2txbqiwbm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zabcxqzu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqfjgph.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbjsoaw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dqafxhaz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2irgezxiw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbjoyhr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrmxbhd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2amtueyna.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyaktms.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2noccedzb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfihblw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhemsfl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlsyeaz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjesvuu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hvigcxgd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2upqaakmt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdqporz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hukdsghg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdurxzuu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlhcvmz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mepvwhii.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzkcyxv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqvjmvr.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbcgbfk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oeclalnj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgytqnq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjslwkrc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtusofp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwecumdn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaxbtok.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlhlbyq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfklcat.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jphvdzyj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vfagathq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gproxqai.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrndfvz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2yplldxxf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjlnlov.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfvjtdg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsorirb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2enpcxhtk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nvppwhhc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpewdsql.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2asunmcbr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmsphna.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiofoof.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zxinfvhy.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxytmfa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2exzqaeog.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqmyjrm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ugspsxlh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uagqhkra.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kxprfdrc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kspuaskl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhobfboi.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdxvqaf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdztzqm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjbvavz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tylcafcl.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2oqeaepmq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zrneubdp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hbylfyjx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsiplnv.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ampfqwwy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieadwopr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2syrawewd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjlhbzj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcxjaay.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2roxwkwsy.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yknnhiuv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvbrdgo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bsutvhlv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbxvidi.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvhsgfp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrfsxhu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2odlvxlxw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqftokcl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsxrubo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tintizgh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fomgycwa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2waswjcru.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwhoubh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcypkpy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tchqrdyf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2geglydvf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtrbdjp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dzombbkc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzpmvuf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oreyjngj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovstuafg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsytmmz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwytpwsf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2abgcuozm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzcyjro.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2imhotlae.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlyrxax.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fdofphjq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuayqvk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tumqmeux.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqzcvwt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhhoghg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkesiqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2awksimdu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cygpzxim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdevrmw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zsariowu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2epfzqyxf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pbaubafm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ltusukhp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tapumbph.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgajcxtj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqkvjmz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tfetpmqs.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2berrdefs.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yebnvdql.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wzibjkjp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2saahrwsa.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2msohijxa.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2puvdhank.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrzgagn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2sggxunee.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xowcitjg.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkpsksm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkxxyro.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rplapzow.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vllpoczq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzthqdc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmlttys.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2khysfmeb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqfvdoz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2csbzexrd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrhzhup.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdcldyq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fopeqjep.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2slphnlyz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkuxtpo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2uoowgwmb.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2twwrhyhi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2stetmgva.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mafpkblj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiwvcag.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjogjqi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2scygtwpp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjfikoh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqugjffp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2phyjhxor.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2adzmprnd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdwvypb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgiyboi.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oywivtmt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbwbejt.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wecuvheo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqspgrpz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbokveg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2azwcflep.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqedpzf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmoisoks.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsouiij.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwfskba.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xpczoxkh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdkmsbp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhodolo.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgjnezt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vodpodsn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnmmzqz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiqokhm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2uvisqnaq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqqmmsl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2snxbxmta.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsjikir.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xntwynwe.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqcllap.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jryylzmj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkizxoe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvljqduq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfzvvbq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2unopvzvj.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2syfwbpit.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ukeynyxu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2apeotvlk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2idymejlk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkncvtr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiatbpr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hqklfigg.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvoujrq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mawkbzdd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2chfniwdb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qdppjqjk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsfifze.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzxlwlu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2epqrkpbl.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsgijqx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpvhtli.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrnircw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lllalhqx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2idfsobsb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmhpueq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2btyuujkd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxcowdf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjkbmyy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpgnsjf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gopvahtp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2eluzqzer.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbmryrq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dldelbel.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoqzcwk.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeshdux.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqjeige.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjzrebt.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzwtanz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxtqlnk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnpkrrd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2meqpaeiz.html


<!-- 参考信息 -->