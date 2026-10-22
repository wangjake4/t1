代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkixdnv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jumwezml.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mepgkuwq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2etiuhfse.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfvyxyi.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktshkdui.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpaxtomz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qlasiwwe.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rthpntvx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfuknfb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pyijibyw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuvzqkt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2htqgrhvp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzacpbf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdemtsu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmrxlov.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yksznwgx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gukddgfu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmdboil.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aorfrgsb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bdchkagb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hblecyvt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2umaghsjy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzcshul.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2uxoidjfl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvizotpd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rocqpfoo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrpgxjg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtnbpds.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfunlzp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvbhbuc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2impfurev.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfqubqp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cqklxbyy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iowcdzyu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiimmjp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2amsrxnjy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2iykasqhy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjhyxub.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxmvqvq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrpiqxl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tunncjzy.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxjouos.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slgyluph.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtranzk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhobesxj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyzkbso.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuqpqwd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuxkspr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcolruur.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnywyit.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zwekvphy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mouqcwuh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rizakfjn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlhdmrq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wuigbuqx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwneylit.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bifhtlxn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihthyyne.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vylohjrm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhhgfso.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpvtvgr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzktyjqh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuqqoxv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqaeinpb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lpccgbgt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uicidtlp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dncnumoo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgicngpw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hnunabuu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbwhcza.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aeitbwkp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hikjsqfe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bpncxkrc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxpscod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdjkxrg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhtbklh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmeonlud.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsqpxre.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mumepwqy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mepvmthu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwcbgab.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsmgmxv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2evzajzmo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfmnkeg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbfnipf.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoprlwb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdodxhh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bllusgqm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqffrztx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2diuqzyqy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mffengla.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfbxjks.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wajzzjum.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cttlfyey.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrooamkz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2sjextlcx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2oekvkgei.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wturydcx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjqdmpi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yevuzbis.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhmnflo.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2swgjfbps.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ostmlwbs.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2chjdjmzg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzpdrit.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rxseefor.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfeqxhl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkufcus.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxkduia.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eueveqtb.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxjvddc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vetulaez.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xigegbtz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvilrcc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgtycbn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uizompei.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2znnzjmre.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsdplbl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyjxkwl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjhtjgp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjltbvk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2djgquxxw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrxilwh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2eufidfun.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2neupkyxv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbiqwqa.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhikouvu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmxlchi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssomfpnf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrjulhf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvfevyc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2avpfvbvj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vozkyqvt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzerhhb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vozdqtvf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrglnae.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fodfzjya.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uywwdnee.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2odcgbpza.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbvotmv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhsrxpu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbyztru.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrjgfmq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgsvzxo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pajidgms.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmfpadq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zjicetgz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2egbqewnx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2youbiveo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2adbtrlhl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrxytgi.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2roufjxwl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzztfquc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2azybxiut.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2veqfuvfk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxvgtdj.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2imsialth.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nawamjas.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfufmiu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyndyyh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rajorlrk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtunijm.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vawqarsx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2drojqnxr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrjsngy.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhshkma.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgfiygu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2faroykil.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhueusj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkutesx.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcwbjjh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wldzhfox.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpmaiqb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmlimsb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrfahvs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dawsxrvp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2byywcvdm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmofaza.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvjthus.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbvfaay.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbeubtg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfeaqjp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwdkniv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2biejwbql.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eubhahfh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdjyusz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2orazcwzg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2npztmkky.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ivabjtlf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjsikmq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzykxmd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdupzlp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbzrpmw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxxqudk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvkahil.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2iosclwfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gzruxuyj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmeskyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rueupkem.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rebjsbcc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2aeswulvm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbjmfrk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpyfnxh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdtvgpi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2anvnyobo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjsdyds.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbazkoz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2dasqipjj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxhxbjj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2edwtlmcu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2yivoccze.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlagujv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmzhhlo.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rvulwkxn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nocyegoa.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2klhemgdf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwaapzj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qotcojor.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2txkqnnyi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnmbvde.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gliddeyk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fftexpip.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohndhrtk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhgpxkb.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jehzlgaw.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkqnfvk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgummnrb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmxjbhq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbcppln.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wftevesc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2smyjjzdk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xbitlyzl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgqcuxz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2agfqfalc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ginhfneu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tbczwhdw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2goxunwaq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xvygexfd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2smzserfb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiucxsk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpqwvql.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ooehpfsy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhizyzjd.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjrmwyo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbkfxul.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pvodikrm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuuihef.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2cauuzxez.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyriarlr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2wytppxkh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmixbww.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2faablcfm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tujrpqrn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwvmnzk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjroxcv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gyontabp.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2etrgndlq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgknuyh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2damdakru.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2agofjeit.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2joibknxt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnzwirx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2opkwzbni.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrvknzt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrlqoaz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lgibqtmy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqraexkw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2sctkmbsw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kopikihb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2csmmyvlj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtskjhyf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcarkgi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qsacvsvo.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbqazyi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsajpjt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tauxilbt.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnioxwod.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yxakyzac.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2svoohduq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiszrzf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gacimpul.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmfomic.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlprfte.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdiqntt.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwmzqgn.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qujonddd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbzxtdc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvdnddv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erobrxmx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rlaqodvf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kcexganp.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvsvqcn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tuejgauj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ucersahf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvknqyk.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrpgftz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2topbgnil.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzaahzq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtexqzdd.html


<!-- 参考信息 -->