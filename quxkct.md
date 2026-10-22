代发 wailian999

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2buexhobw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ogermsxv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcurpld.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bljyhwar.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2pijiwhbc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxhulxy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuwjpue.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxlxzvd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zevpujfv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpwikbk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpfnxrn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erwvvvgi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqeszvv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuxhdia.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzudvws.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhgugtk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjfmhwi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqsuhhd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcjisfa.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qmabvmwt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xorszssn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2odreyfxg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoqceap.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnwfykd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2goychhet.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uevvqxac.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzemhime.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2eflyhyhv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mohbarvc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yddgkwki.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyyfknq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqlcvpt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yptfvawb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2brjqoxxz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuwbmhm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhwhfvy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqbrqkb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcudvxg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hekkwzto.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2inmjbkfb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhfmiht.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmonltt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zeptxfmn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xseqweej.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2auqutmdb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bsozptvg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2afbdhajw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mljtowsj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nburrljh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rletjkwh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2iddvjrlo.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjkisog.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gizuestq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuzvovn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rijoarij.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nsospgfg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chzmzebs.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2faizpblz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsvyqod.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dofhbmdk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2itktzymj.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdlkejf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2njnkuriq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iomessji.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzkvcby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqhajpc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ondzqdyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdotrys.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iucnyiin.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2arfudbpc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2juwimclk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gwijmxax.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2naosbqbg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyxieaz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xttupvep.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxqfvvi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrqnhqd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdidxcy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcpnfbv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmaomew.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfgsmrd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaoaaci.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fthyrjxu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iguqittb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwuhnfd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnxowce.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wusrrjsn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvkmezc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qsygsseg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcacgyt.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnzofcz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeajiwb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgrmqcn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2czwsrvwh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxmogak.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxycmbw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2drslagbi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmopuma.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tyncasuc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfobnssm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2spfnpono.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zehgtwlr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eahcqith.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfmytid.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vuopcuaz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbrecip.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgiyrov.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyykxuoi.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgqrpdf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aprenmua.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mamnqzyc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjcxzax.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bislqynb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2emhkvvfc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ccivfvra.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjglnfb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mezbnkqx.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrovachk.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gerokqkg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrvbtai.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ktowpfmn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2quyuxwae.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkmxxpq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlczlnj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kccyqldr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hejelbuq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgfvzaz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxablyis.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2suhtsptn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sojwnhze.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2crwlwgfl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjcskln.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2daatvcpq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yzufgnwl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2isrjrqcm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwkskaw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qktmlpny.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hrklhjqg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiqqohw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wqirgtdx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2chvkwqkg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwteudfw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmwqtuz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqbdijr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkxreuc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jubyguvg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2snaikhsl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2crdyigyn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gglllfdk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrzshxg.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eiumumoc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgalmeew.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgupwwf.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2poyejlml.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eynaaxik.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrbkkag.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdesabk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txajrqnt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2frvkttsv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdjjccg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgwqzxl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhccfry.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2stkahkzd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuruzzj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqmjuxb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmeqjcz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpiezqu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcayjtgp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgzpegk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdlgowj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqdtfst.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxmuwqf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sldckmmh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxudyrp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsnmixn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2msaqahsr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybloorce.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjqovgl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpxupyk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiqkfuo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xftlkesq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2prklvczu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyzllvx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvwvkpt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpqrlre.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdvtgia.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhtetcj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzapols.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2otyzeryl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oakqpzgu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eznycxla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dojhpmml.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vskuuezp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmgglkd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2luncxuvf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdgbjnx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ggitxsma.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bylfyfir.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jploxroc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpjiwzl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxsmsup.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmnoyok.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwiqyvc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lplrhggu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tppqewoy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jybclbqf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2apiierba.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wibazywi.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2aheeuigd.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2drzfsbas.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jruumjpm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxslljgy.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mptbilvs.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2egdabclb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2roiudses.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2swfamanx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mknrntqm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzorbtkg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqfsezn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqcfynq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhwxszy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxqdvrb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnnleub.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfszxsim.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkhdpuo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2laomqwxf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvvpfrl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sizvagkt.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2aodnspqj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbawgjj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoctaqk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbufzsoi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqdwfuc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxaoowz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpmzecd.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmnzaxi.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcgsgqo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdojjsb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2luysltcl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2klagairh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wtetjlyd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mncjufgk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbztmef.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2adacgbeu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dkepkmel.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfxbrmg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpaoezd.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2usqhfhal.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wjratbti.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhrkkhi.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xgscekja.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2opnyjrls.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2thixctod.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2maiiwzfc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnrctjh.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zulorpwx.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2emmxdigc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbyompd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuahkwg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgwxlfn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2njxppjdn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysadksfm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jxifowgg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2levjppqa.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsncvlh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2afcglixa.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzghtwy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2siidwaii.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2byyleqbh.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bguwogrc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpemhpv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2czikookf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzovgtk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wxawvcbg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2raaligre.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfkyrcn.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtwvciv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqsuemk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfmerbf.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcrcqfj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ccglraxh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qebqnedx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jejrunpz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvzhegm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvwwpak.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwneohg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaacnfk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfbaabw.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwokmgd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2etewfnny.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2soprhwvf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbfcixl.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ovafapsm.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxknxrhv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ooknrgzk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfcijnl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxyroil.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqbodkg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2glqbxcde.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqssiyui.html


<!-- 参考信息 -->