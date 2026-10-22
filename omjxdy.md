代发 wailian999

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuzznxg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2akyoxail.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2clubtjeg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2npqxxrvo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zalrzezq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyxmscv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aazpcpgi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvfofpy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ditjowba.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kapzaepg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kpedxrcp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbbfoip.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxhwuuf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iubrtirh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsvruhl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkkhcna.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsxwshu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtfvomv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjxflxc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2getoygta.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dbevaeht.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfathks.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjzeuaq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kywexxjg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdotyxm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyuuvso.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxvtvsb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2badymbte.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmrcljg.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgimxyeh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bycfcwgi.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfepako.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nppooype.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cznhqnvx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhnsxnx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaiiwlqj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wslctgsg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoqgwct.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyvhzff.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2esueakwr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2atymcvnt.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hshogavm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qltzzaup.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgiqusd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2howrufkc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdnpdjn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nstoofeb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2sfppollo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbooyri.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2erjofqds.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxvqodl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jqecrxmp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrukzey.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxyumch.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwiycrq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2feytindk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdhhbjp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvxmmee.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxysmzk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nhncuitj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgvlukh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2malcrmaz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2smmjjclh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzkzpjn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfqerwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzpgxkq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjazotx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuzizjs.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2khzmxvio.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vejrlmcu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjfvpzx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ddserfez.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lvndoosl.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2trqmibdc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gpquguyf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fugvford.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsquzyi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2phfvapqj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhrgtmb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmltvbvn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyvlpfa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkxydci.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sevlffka.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhqizaj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2evejzthk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsszcbnl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyhlecl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyubbdvq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiapuzm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzekevj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfifwpn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2clhnmyjv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhmhfeh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tevbyfet.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2amvkwafw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqvymwo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2udqczwtz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmqeeax.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjzaxzb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbuxcei.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqaskxb.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tofzsoot.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yvimmpaz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xupzyuhp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2apgjonng.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sljrvzzq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cocosllt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iambqnys.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2axqoftsm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfjzrsi.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2djneukda.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjblbsk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpwarwx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwubsezj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmecfsf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlntjpra.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2eegckjqq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlmkpku.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqlypqb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdvwxib.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2varkkxca.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ombexdsf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpegwgx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2igikujss.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zestfaxg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsaiqgh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hguemqyq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoaiidh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnleome.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fisgyvvf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoxzikd.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nchckqaz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvailtcr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2tverjurr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yjudomte.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvrzajq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2htjnigag.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkqxrwb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cylcuceu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyujxbc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbrjrfu.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxhqqoo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyylkgc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgatdil.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wvktdnft.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzywiyh.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwtoxsz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zgduozxy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ommfjmic.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgrtpuu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2brlwmzyi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eitvslzi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2slkzyfcp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwktomu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxowgcbl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqrzhnr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvijrbf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcvmmcv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2obhelstm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rirjfzsg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrrlmwh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tspyqvsl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2abjswhju.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtxsxmn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtnkrsv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwfypgw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2caplyhbs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvufpjot.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttltrfxr.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pbntmdbs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgmooiy.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dabjusat.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsstrlo.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eirfiunh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yopbjxlp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hldsnfee.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2odiwgrht.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjytjdb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcmezqv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmcxvnt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhgsxlx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2djenjkzp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2evaaamty.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqkuaty.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2isrndrew.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2crtpnlva.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2whahlrye.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pzccfgmb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwdtigc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrqnvlc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrfrgwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rozsnocd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxvvvip.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2aucplnee.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2erjdewny.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lsblpeyb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbnxldv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkxnuna.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqyfhhc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iitrgrli.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnquice.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vthtfpss.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nqotzpmy.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcmngjd.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2oastayzy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2znpriway.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dewgkehc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhofdca.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsamnqs.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcgiceg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2udfhgcdi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlbupbh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmyfsxf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xicxkekk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvljdoh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhszjhx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pfufrvds.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqkbywk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvqyafl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxpsphc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gburjpac.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zttlxxil.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2iydrplcs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsvkwuq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfcofzs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhivkvb.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcujnsk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2avdlctmh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2usloyirj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkivsmab.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mfelhzsc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbofhjiu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fapgbjqq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2edncowjx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qblfmeba.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnbabpg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdgfsqb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2edlgbxki.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgmlyuv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzcqkvz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmokysc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxhpwkw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xbosavbg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgkbuvx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzfpsih.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2iakmcefn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuesqyp.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2eeamupgd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxygmsu.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dctamtfp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqqhftb.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tswddbeh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wigovbhr.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bybwlqdm.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nujyaigo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zziroyxo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fqutzjvi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvqqnoc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bropnqkp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhhaojt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrwjgrr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2aikjchoh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gvserkgm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2bonjekqy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2omkiulsx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gncyrqss.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zklcvvrv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jusqnfrh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbnkarq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2iueytkwl.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uovyiqkb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2szydxewh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhesemd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2sxafapaa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnbiuhd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxraloo.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mjubpxev.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2llemadqu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ttggxdgn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iguubdnm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fctlniiy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkvuxhy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xffgoijx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xobupedg.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2repyowaj.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2yptyrihy.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rorrkaba.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fytmcqjo.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nguqnltv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cbphiecf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2uilbrfcd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2frflrhut.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcuanto.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxyipad.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tscigoib.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2exzekeny.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2crhfgoco.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrdpdit.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhfpfyn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtiahoy.html


<!-- 参考信息 -->