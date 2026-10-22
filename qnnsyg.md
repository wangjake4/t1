代发 wailian999

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vvngqdpt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkhxdnp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyhvffi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdxepln.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhbxees.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxajhvka.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwjnzbn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jinrmsva.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2doiqtrvt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtnhblq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rawbphvz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2neeixdki.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkyquin.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebutwiex.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyrhcwc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiujjfkk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzznsdq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2klmvofol.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvybnye.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzapelw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbhqhyh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xaljagfc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fhskzoyy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2shrqewvl.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oefrvrwm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2arlwolcc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2soiwseiz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrxrjia.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2elasvswh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqaiqxd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmltvrw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsveapd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfhbzwb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yyldpcml.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kaeapwtv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngujmvxi.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2khlckqed.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exuekemo.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfqsmrz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2infkvabe.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmfknwa.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2onxuvgxh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sybdtyyy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yystrwpt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpjqlmh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ugijbumd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2isbkptiy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ohibbrcl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uauzbkja.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2unmdjrlu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2txjcuger.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjowymp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgttsddr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ruantzrg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvwfrmh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnffizt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oenntpzs.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2goykbzmp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqovdqhe.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfbayae.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnskhsgc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfygotz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgetfgab.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2upzbbpdi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnedeqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwjrqjr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2athpfiea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjevhwm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cqiajhjh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbwioke.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdeubdv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqaiemc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iyihhiij.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzztirl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qwirtadf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dixuxrrd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdxxwaj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nhclkgcy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yblwenfw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2buypaefq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wshajynx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2spswdful.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuwkzet.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yftzjxib.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwxdldp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2neofcjuw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjnebhy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvuefsr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnjcvsp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfxphxq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2undktkyl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcletdb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2suarourr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaexyvl.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpvhtur.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzdszpr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ymljiyxq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyyumit.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2glrfdhtx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbotfws.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqoaozf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyxmnjz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2clafnjmr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2holzkzvr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yydzctch.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdbltch.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2osqwemuk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmudpedb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jgratogh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcfdftb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oafpdhxh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuhhucg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdudggu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtuyvyu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2edrdzvxc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpmbhnv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcyjgqf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdxrsnt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2tpppozrt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxvljsl.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpxavow.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbetbwn.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qljqdlmf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzcbjez.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbvaoym.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjdpfkb.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsuqgjd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2javiosha.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkklpna.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsdmayb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uogrswxp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bloeolwf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgutkmg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgtoqye.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzndgco.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2poaywnri.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwlcrih.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfncrez.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wsazuoyf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpwmcen.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2oslmhltg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxowzil.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukovjtlt.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrxlkhl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2crvxlrak.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqpqkoc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpsvhlm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbrhxbe.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ietoguiw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gsllsyew.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnftobt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlacyiku.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxexswj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2otjhifpv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdshfcu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmefqzae.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cextmnja.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blehqpqv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyptcwp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmoggwk.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2aetnzbxs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxubzesi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2guzbdlrq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwustcma.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyfggxh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2liaqiqnf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyhmcly.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpntluap.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2begyqati.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtrgjdn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2whnjixcg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhkcxpw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyivvqo.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2erllanit.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vliqndaq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfhebtv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lacphvrc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzxvyjo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyzpusg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fdiukmaq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qejuwbox.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uapjybkb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfjlkov.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xhteyfch.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2djtqzike.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfiqaxi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2atwvllcc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmntcrk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gepvrpzl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhybxqd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsgbnbr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrgazky.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzybjke.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qfluahqw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2oymvxsih.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcgspra.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2asukevvt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2omyaliyw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmwfabs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvoodii.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2obdealim.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2socpbvsl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vmguwemv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2iryoyuyk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiqbpkx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjbnlqd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzvmukk.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvntrpo.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2sojkpjql.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrbweou.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrrvqcr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hoienqzo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrwxgvd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjijufw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xpaqoqsv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhzwnbx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2orwuepac.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhppbuyf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2svzrbewu.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmguotz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcivxhd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2revjwmzs.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqachom.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2gycnorak.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rsahwtjq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgzcwli.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkgrofm.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdacdhb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tacnaome.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcmkqtc.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sixjpqan.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrkvaaw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhveyex.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2iosnanlp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wqklyhrz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fibhgcma.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwjkvnd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbtewey.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xeequofj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqqfihe.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lwetzgnt.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcipcts.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bdayfpid.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2owdhinaa.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kkplnbnx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ssslbmik.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbxpvol.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2swojrpxp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2etnzaxbv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqsnvuq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2edyjywyc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iescxfdm.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2muvwzlvi.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsdxwok.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wekdbdhu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbrizds.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeegfmb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2unxchhol.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2eseddilq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2naeozhwq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2katkcazj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnabauog.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xggnxabr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwcixjt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhawwax.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcnilfq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2feeeilfi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zlajnaci.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyzgmkk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2plxicfpf.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnfnyfo.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sarqdagy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sctreuvf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pbslmiki.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wadsmonh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjaavwk.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzypnws.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ketcmqol.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gghtvcmn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjonvsix.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rxepiwmq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyvyqmv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tasvkjtc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2endkatqf.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nxayryix.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2igbqohem.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdaphcw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvlzbxr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmrtrsa.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pftfasmh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2yblvkpim.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfenoid.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2frdgrjzf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwowbmrg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwkbbwt.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpqanbk.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2hardxsdr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tzngfkyr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuaujog.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2twwbbztt.html


<!-- 参考信息 -->