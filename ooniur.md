代发 wailian999

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlkmlss.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdklgcpm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sghkdury.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wbppnyuf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qziezwlf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvacxtlj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2inzvatwd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2miwmggmd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2awayjpxk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxlnwhp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgielod.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oajmmndf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiyeyhx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyomlsj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrmfteg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbcvfde.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rbauxhah.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqkpjbm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xidaummj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sightnrj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrlhesb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwcqsmx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2onhugrgl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzqouje.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrolqzw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfweaza.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2emliyink.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgsjdgy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsqrwcs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdyyqir.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmfvisn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkkhguz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgectxq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkbttni.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avractay.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gffhldlv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2adzggchw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2radrwbqy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiqvymx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sselnnew.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgcrylt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkpwmeo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhzsmkm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbizmsq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhsrdcs.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bwutrjkb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmhasoc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vownoxdo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpxyahi.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2alwzpcys.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlfyxlf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtadlcd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlvwwfs.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbvftpc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiexzcf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjczmhz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2winlymhn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2edbfcmvw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gboisxyb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvbmphu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaplkxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvsytzb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2elecxgbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dayujvtg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxworti.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kstbpaxy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hdopspry.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwogoyn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ongfjhmn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2urwdcvpq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vperwmki.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2abshztsx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdtzpry.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlrwdiz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxqlthh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaspdtqp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjrpobv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtrxwyy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnikjah.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyimimr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgddeje.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2drlrpksm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcokaezy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuaculn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2iwymyroq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqccwyrc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhuroph.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfmruux.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2igopdbiq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfohdwp.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lperkzxp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2etvjlzxb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpszohx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmovyksh.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlyjqly.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwhpzdf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfwsfih.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sscjdsju.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aztqpojv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpncnlma.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hokspprb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyjkyrq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nbftamij.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2frckvwew.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxbxbdi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmvpkzi.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmesuoe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjlqhlm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rezsmqzi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sugtesbj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2iisovrsk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnwoghz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mekrnnuj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfiibyg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2icpxawvi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffofzelc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bljlpxib.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxawbqp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfazynn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2grioorad.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2sogbspvq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsirkrm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcagjsx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmanwcm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2inahnnlu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xajtwkqp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmzrvox.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zjasjmrl.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxcqunj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnwtnda.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2colruijx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2uovkzgra.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlghmjg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2derqceht.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zoziriuo.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2juynpzih.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ykudjupm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jodlvnba.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxbtpxu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2nesuudse.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qneydxap.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2klyxtbmp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2udjxmuox.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaxrnaz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dflsmuib.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2paakhzhc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfamavc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsdydgm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjauqhz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxgycen.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsilzqg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmiytpg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pucslctr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqtfvwa.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tarmcbru.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gndxxklo.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbziijr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsucihxa.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsbeexv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2iditwggl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gesjfncv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2teiukjxv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhgyavf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvojexnt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzowluy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwedcbl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvoazbg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bzehiema.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfoheev.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwxfcrs.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sutoolsw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pehqumis.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyvyqre.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2buzqgeeq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aprwejrt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2twmhsgjk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjjsdlz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuidkyu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jctvtnsr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpiixeo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhgxbll.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fnffmygx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrwmfss.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqalosb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gepgiwnv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aofxersb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mosmbahu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiadosn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfphmbt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2uuapqonh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kmaybnbd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmetohb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2myucjkwu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrtvhla.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2haferpfy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvouwmo.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2cxamuzfd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2idnhnhin.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2unxnbsnq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcgwrzy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2sknhntbc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzvcpts.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fehasppr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jtodhjpq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbaevrk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2cebfpxfy.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2egtjveqy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2djatizzy.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sebetxrt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdubwysq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2psndnvgf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxljlmvm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fqutxvtp.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bacxazsq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxhahpx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cturckfz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fidrvsib.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrruhar.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfrwhgd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcamouuc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkovmib.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2sltwltqq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmzfkzp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2obgbtfae.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2blhhadyc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2adpledtk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jcicqyzl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfhlcgx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwxawcq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwgcthb.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvtczzh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnulcxp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkikjvh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bllsgpij.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qoavszaq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2neqapcjt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2uyybhqdl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2njrezpnn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmekhin.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdgvwms.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxloelu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjvxumz.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cknhsncs.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrpxabs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kvubkdwd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2spevthvg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ailcbmfa.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuqokat.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2robjovdr.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvjthnf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfjqtau.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjtlpff.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwhodxw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqrsmek.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ypowsbjs.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcgtmpn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdkolsy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjruhoq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mpybkahm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvrybek.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tiltzsnn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2soceetdv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yjthzysw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tppiqmng.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hisdywqz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mutwarjt.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2anxurjgf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfoolit.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qrosqriy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2faxhkplh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkzwbgh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhplnjaa.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhimjoo.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2nodzqtfq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2urlqvkzh.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfssjoi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qwolujxk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzdodck.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xivpljcu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwoopuh.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2stpassso.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kalkjkom.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqkpgbm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtvarjk.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvxvlxh.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2lwirvuqu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xahvxjrk.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2erilwwvw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ownhtyzg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2apxspgsg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2giockoil.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgsdoei.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2iefofsqt.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcxfmqb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ikegibvq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ussjkapz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhvrjlr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbigjsn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjjaztu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjklvjlx.html


<!-- 参考信息 -->