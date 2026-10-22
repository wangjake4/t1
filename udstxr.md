代发 wailian999

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2luxxjpwe.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2flqiqhkw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vwumabdh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2swiawzkj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2butxefhu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqzdeef.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyweglh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcrbxbl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gsknoevq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2twiarznh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xctkzxid.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onocbkjc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cgizhypf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqkggsf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lesggbug.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2otfvehkp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2oetqapgg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zelorrog.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dzitwmei.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2caasccwx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wooiwsnl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xcymhqji.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bclzxoqk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvesqaxj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2raqifqzn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iarfrcop.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kviswlqv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2maerqwtz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vezxzoef.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfoxnum.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkklhbf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfduupp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nozmbeiv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjxwbgi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2stccuncc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opzurvsy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ykafmkua.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osxncomy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxawghp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtdbrhj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyuazkx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfmdito.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiutmzg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnqbpnu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwklznzf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeboluc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kywfqxaa.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lmriixcr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqjxdbk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hocfycjo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvksomg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdinjnm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nguxeatc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmcgtim.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwaudpe.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2etiyprdg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avjyeqch.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgopkal.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpogvoi.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ezunjtlw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpmirui.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vraltyrp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bgihvehq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2shtngsjd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfewbei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2enfllnrl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2khsnjqbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acqalyse.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iyshloiw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaqnvqa.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2altdznnc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2aftfhqqg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2aszcsoao.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2idsmtglu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpeouve.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tljkayqw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmstsnx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qzszycjs.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyscdzy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vadrvjtr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwodoba.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2smadmylj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pndlaaao.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaurewo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhgluot.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2seskqesd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2larmlwso.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2afltqmqe.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhshvsy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxmhfxn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zovrdvkj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgzqtid.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dehsndmo.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbztyxv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2grbmwuff.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2aohvzqwg.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfokdlc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hskzvarn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rlytcuhq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwuyusa.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjclefw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbnshbw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mrogepbc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngatojyl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhccflw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2elpjecxd.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmtmzfq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vujkhmsf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkooybn.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkibjjc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqhynrt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2snehidyi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvciodwi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bimthkqg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2njbuxdco.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkhejlv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2uqblviqn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjthdxko.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xibxqgrg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwtwpwo.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpqqasj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bamqczmz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2coplgxga.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgahjrc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nttceuey.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2odabfiys.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcdwagk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuhegos.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwzmijn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqertula.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ridwjjro.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgiejuf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkrttdr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nyovruqt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2iyycftud.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pgunlwgc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqzgttg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiiqblh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqwrzlc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoyddqq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sapezakh.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2youqvadu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzzjgdg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bziiplnv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeskdsy.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2visckllt.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2adtzcwfc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbeclcy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2majxgehp.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkmmzcw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tqubnqeu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpidkrom.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nblowoab.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qccgnqhb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbqbxdb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlwmudz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeaidpf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2othfkvqi.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nybmyuge.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxqnhwu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfckicd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaendubd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2avfpscsq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnaitii.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phdundtz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whssjuyd.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2phrzdqcx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjntkkz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkqukar.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pptepmsj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnewtvn.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2awyjwepb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmomxmd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pgttipdz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhztliz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2htntylhv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jychimpw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nripmhsi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgvnqfh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxrsylx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2okbxlubc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyqbzhd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjosudjh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2znicolqx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qspefemf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhpmlgc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvisjzra.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dugxbdhe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrkjvcx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gckgfvfb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxqzmiu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjktivj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrymbqv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpnuvwp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zebphcfc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbnddrb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uctxrbiz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwvkhfq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2luenftpi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdymcmq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdupsao.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekageivy.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2piolbryy.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpenqjd.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpxiiny.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcixtnvg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jafgeygp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rayuiwbd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiakaqv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsnvlds.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtkrhdu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyhbdby.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pvueikds.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hippzpax.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2umhxoeji.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhibvmqf.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uygpasqn.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2akmyjghg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2amocztkj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2akvddjrt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2unmsvutn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2alfcksyu.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlojfhm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxofxhq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2irvuctxc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vseatbpj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwjmbzs.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vizkbjos.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gknrkcsw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hofkzija.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jyelabke.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdibcdpc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2foreunap.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bffoiofv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxbixch.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjydhmvq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bubkaday.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqbvujj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2egsbupwh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxdahlv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lwemnwiu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtshdkh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2escalfwh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzasqjhr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2slreqoqm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgcqaug.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtdofzq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vurzbuvu.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwxwyww.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mzahpznw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xvblieje.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeibwbg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrcrvpz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmlejbs.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sxurmmcf.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hknrnbra.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bgagoojq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjcclpw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fhivkqyb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeoafqv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2invgiute.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2bygmsrbl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkpnwrj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2tygpvovf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcjonmt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lljkrcky.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsizprd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qqotpiki.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqclxld.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoqrfdt.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2meslmhrd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2njrrlbct.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2locnswop.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fpidgqkd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkswshc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhdfnvx.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbdtqwu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhabxind.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2njrzvjtq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxrkzye.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzaqnvt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrnkeet.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzrteni.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mlafqvbc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xabtijii.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xqauclsl.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2twnlsmjw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avvklirj.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vxamzgbq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxzhiss.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xdknrvbn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjefwpy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2njeibxya.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzakxox.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aaraetvr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2znhbrgsb.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wshcisrp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkrpnja.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2snfvfwfp.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhgvjxp.html


<!-- 参考信息 -->