代发 wailian999

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmlwuju.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owpicfir.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ogipwdzq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcpeeoo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2brodncuw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifypwzjv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mewrxauv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2retyjokd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsxjehg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrxpads.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qtibrbfw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2njlopgsb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tikjwxaz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqnibmb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tqulrylj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2syykfyai.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcqpbzw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2iaeqrowr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhvjqxm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqznvhnn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2offqgvvu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jogxokew.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2epctbfez.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyxboiw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmkiytg.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjkkpsd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2skyqnohz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phlytwew.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnldjia.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pqilsoro.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlsjntx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvkxvcd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lycqpvvn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psbkozpk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsswzkoi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyvcmak.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlwkgpn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiiosrs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2olylzkgx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbdcezl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcocipzk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2psdiafim.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvpyxom.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2czpuvnfk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imwcvzvy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtnlwhs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvtqbie.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrsksxt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhhqxfg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwfezmz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuxbtfo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fumynxvz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqifdgc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qolpdvks.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pifazvnz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlffsqf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrwwske.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2phaakslu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbybdre.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xseqrxiy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2twfbpgjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrsnxko.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhwdxhk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drgaanob.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2clpjdrzh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwisjwfd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcfafyp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xamwggsj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2shrqqkaa.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdngzpcm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhoemko.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrqhfwi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjkrjgr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2iqihqdlk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kluvbtku.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yonaprqb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlukwbo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvruyjq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xromygyo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyqiejj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2etqnrgqj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wabipmyh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qufqvvww.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjirwxup.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bwengjzj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2liggjpej.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpllurn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvgrlnw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2umxuqtrg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rntxjpxx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrfpprp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjucbll.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qaziwlmi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2izdzwwvv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmudvza.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ianhddqe.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2czowvopi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsoyief.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2emdxzxib.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxygdka.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2txzanpuc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2itigvcrk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kudmhimu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jegsroia.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbqmcea.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjrnrjp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fglwctus.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lradgioa.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2etnkuptg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jphlzsre.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yromzhgh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjtjtuq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pliamqvu.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmywgcg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzhoiia.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oozummwb.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xltursic.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxefvlgj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fgblvfpq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdtczxl.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jozzkjtr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2czyeywrd.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kftezzxq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2eipbpjnc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2utwmboxk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtvvuwo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkjkdqi.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uynlzqqg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fimdteks.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gawgjlgs.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdxbspb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkstqqv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqyunou.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrrvcke.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mehcwpqg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fblsnpld.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzybzhl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tigwnsbr.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dghjntuh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpxnsjl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2neybqzon.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2psvfevbq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fxesbaip.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2acmmexfo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xjakpwaa.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zvporwlq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtobgiy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaspwfrs.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hwneqvrq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2egfuwwvo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbdcufo.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfvxqhp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eoizbjby.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxzqkmg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kgftlsxt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtsvwda.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wfheosmr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhuoskd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2krhjochq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfbspnn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dftofhet.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etdjqmkm.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2unefsjyl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2smpwmaor.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wexpxtac.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnqszgq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmvayst.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xtogggid.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ptacbfbd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwgdhzx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwiuyiwe.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcsdnsi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrkfdag.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpjtwtf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwxbwpx.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2boerjldh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzffprym.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dkytgplu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqyzaql.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2urxmjdwo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgfzcwh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2svpotsbv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqepgpr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cmihbufk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfhcmdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjhmxhs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqkkoqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gajszhit.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqkdsea.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgedzea.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmahhkl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyljvcg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdbljjl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2btzhelon.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zubecduk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oncsyzbb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwrfrmo.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yggaqcps.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmjniin.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2imiqicqi.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvqznnz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqiiyrnl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvrtlzp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2imlfpbyb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2latezuly.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcnoxrn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdmagvb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2semcvpxr.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sydwczth.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zopjnyod.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2spansazm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvtoyms.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvsrysy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzudnyi.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvzitfg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2udxkwtoe.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zeojorra.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmyrxth.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwsqynr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmetaxw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pesijpdh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2irkooddl.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbqxade.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvorcso.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwawpkb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2psnzcufx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2stxilqlq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2prheclea.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2uguakqzr.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwkhdbl.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pertpdmk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsfypfb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ensybsla.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwzgxce.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2caubhggi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsdrhwu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlkttis.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgqhbnt.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvzgrrx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgiswgx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2udrhttwf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2iilbiasw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pfiamtvl.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hyejxpim.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2trxuwpfr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2erxkpyub.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qszxpklx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjtyoxn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wihwjboh.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwrxozq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnpypyn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kbngwqok.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyguage.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2osjftegb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbpqtnv.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2idkyknqd.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxokzkjp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qivduqou.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cvysikfp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyxisiz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzkibus.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kytukjyx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2whmdmusf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmckcsl.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpcvhia.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2drryeubx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lphxgiyn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gagzqhzh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gytfcuho.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fldzvliy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vekpeqxv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyfksmt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yiywgdsp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2potqmvee.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pshpudgc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrlgitw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wjayiqpj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvgmntj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mqaandjc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2oybxxyhd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2drewddhk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyvjlhb.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nztiebwl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbvmboi.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoikbxc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nvexvjwd.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjihwkj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dyprnmqp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vofyvrqi.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxjrxoy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuphhhg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvromsg.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcjvmlt.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tghemvkm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qguxtdgx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jggbocgk.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhivwwt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2acoiytkf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aehauldk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfljmefg.html


<!-- 参考信息 -->