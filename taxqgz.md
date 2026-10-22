代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2upapbiax.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgqdmbl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqjoexa.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gloczijy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeikxbwo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbehaipt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdbybqh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgvgibj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfuztrs.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yizwlwll.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2iutonmnw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vbizcjla.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjehvtt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anbgngwe.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxmxfbf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzajlvm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zcortfia.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwjxbzc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lioozpyh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stcrinkh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xcoqzguq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sljinsup.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vewxsrwy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgdwqmx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2szzctiup.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnvlpsh.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2obkmnzaz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbxanng.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gdozppnu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2buigscay.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ydodomls.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2irpbvkcu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cccbhiht.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqfasbl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfejwthb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dksqxscw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kkikanpa.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yllqblsy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxxyoqj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcebqiwh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2aewrhrrg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbsvowp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cflzyxaq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acpxmier.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkonode.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nftcdavl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdkqtzs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2okojapni.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sicwrgby.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpnquml.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2iowkuzqq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2egmgxzks.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2htzrgnlo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yepvrspw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsuddgh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuaommu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsgznzk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bfilxozm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsrbtfx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeddiud.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrywghq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuuadzl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbsxnud.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uianuzro.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpcjnje.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2laztduwm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eizsfzhn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xpendxio.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2scbqvskh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrogohf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gazpshss.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uknsdutu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nkprgbli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkolxes.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfhhpqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbxovtk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2drwgeetw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmshvyn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pggjdkle.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2atxcxhph.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpseeih.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjougvu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhbqoke.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpoapoz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqddwei.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxldbki.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvgphfu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrzchfc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlfmyod.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjpfqjf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eyorqtxw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwphgzm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjejujof.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmegqbi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2skypwsjz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiujleu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwuqziy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdccplvf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tommmonk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2axwstdei.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2antmatxw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2obnqhagt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ttztmjxn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsuyrxv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxcsols.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyavnin.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgwcxpz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbvwhna.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2phsjqnfm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ralbaysc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bwthbhvt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxkfwoi.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhwtvje.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrdyzux.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhxokiz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bngkhaxt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcmvekz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vczawbpx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zulctlis.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvtpgmi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pstoatkc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwfcaia.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gspppsao.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ropntaju.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlkxeag.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hargomvo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqnovtn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2utztrsom.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ghadpdqu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxdxlgr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2easifkpu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnypueo.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bowxfuml.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvtzara.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sozoodkx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jatckqin.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvcjplk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2angggiap.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iybdwuvx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2shwucccj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2djyfguxq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxwoche.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkmvjuh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2budfklpi.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zttjmhom.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoqpyop.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvdylnc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwptbvs.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xchjxoeb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eolhbgjw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkwqcet.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjeouzi.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qhirqfpo.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvyypkl.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxwfrne.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tzorgpce.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlylqhh.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuoyket.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fuclfrhr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kemvyuzf.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vonjaajs.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2yddqsppc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwriugt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmextco.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kokicbhh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzgovps.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2clxqqeiz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqdtkgm.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkwbklg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jigbsalt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbtlfep.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dozhmpkb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdolmxdu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skpslcgw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2timsvhro.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pevthkkf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeddvkp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2npbqmbym.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtwnsei.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwblymvc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmaltbs.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmkbgly.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zscwinqh.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxuzszc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjiasqk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxzmgfq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmkocjc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzufkhe.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvmvbad.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rzizbfza.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiwgfzt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkofzsl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2csvtsrgf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lamqebvi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkescyjy.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlujesc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2iifrcsct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2beiqzpit.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzknqdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2reohnrht.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvgudgi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjamhwj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaitsyr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hktjxyny.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jhytdxms.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnrkhwv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tammshvn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2sssokxlu.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkdedwd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpupaes.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ahygnmnj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqdcbyf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hdslkvmv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgchwwmm.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwfweow.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcivkat.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzaxkvm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyqyxtm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iidcwikl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2philcoii.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ddctwvri.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxadgvsm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwwmfbo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wujqdgix.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvfxomz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaiyfdil.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2olrsaivr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bracxsnc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2swahpibf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsrfuua.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcnxugp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyvgdyx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqqetzl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwtntqk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xgriomuf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rujbfkgf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwulqdd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbzdntt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rnepaxsc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyyvurq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2oalxggsw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wutkcsfc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuqjlcr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpjyqud.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnrwpqj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwfsvhx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwucqdv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqcshne.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2tblyptfz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldejzeqw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsxauir.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhajufsn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbcncpt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlhlaih.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wmezhclg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgjkyiu.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuyejym.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqghepk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2urztqsho.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhagwyrx.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zhobhrbo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhoobzv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rcoauywc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2afgajfak.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kymncgjf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyqocxw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2moiclvly.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkytblhl.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgsxals.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnujpxwk.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqljmoe.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjlchdl.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxqqarr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ripavinl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2doygsrkl.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rplumqwt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jlretqrt.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdddwdht.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lyacuopm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghksrzvb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rcklsnyr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzproyb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjqxfsp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2myzsnqbi.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzyyhfn.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2luaogjlk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bxafwkin.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfebila.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaaoymd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpsfynp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdgtkmt.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2biyjlwwz.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gkggmbke.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2koagopub.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfqhhwk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqmyaiq.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2afaxurjm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dugiebbg.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2shhzxdgb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkwldhu.html


<!-- 参考信息 -->