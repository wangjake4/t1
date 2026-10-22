代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tutheqqz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkgeioq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjkskmn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxflzer.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2meyfefpo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xomfnnaf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2grwxsolt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqxuctl.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2amvvfrtn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zewimcvh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pygrvmtb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcxqvrs.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zblhixqm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trcirtjv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tprskuqf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qlofotfk.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwndlut.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mijpeovc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqprwid.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcifoye.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2exidgfgb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuozorir.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2prkcuxex.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgluqspo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2foyeasuh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2audjrndg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbgetja.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpprhax.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wqehqemg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fyovumje.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tpibbwov.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcepwxr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yosfnmsr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lyihlyjx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjocqjdy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zczbffsn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlnjmqt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2iijklyif.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xztjulrn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msjuvfhr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2amhzlvhb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ypytwxsw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqsorzv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzptqglb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbrosuy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciduwdrd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2olkqdjgw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2grnmjqdp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gacyyciv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dufbpknw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhgcuxh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dhskkgnd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrzztdj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtuwyam.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rxayfgpw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbsucmq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzydzwwf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgslddp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2czgawuxa.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmeuhgn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2thdsjwpr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrefisq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpdsley.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yyljhqir.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxqtbos.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aggysbgo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2blztuydu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmfzxiq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2unplihib.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjhzywz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvogfbd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpxnahg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wynhmzrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chjwmsbk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuandfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qynygzrx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2codtgmdt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmjvnsw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvcggox.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2opdozcyh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmdeqxe.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2leuvunax.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fssuvdxe.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2crzenozf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zguanpso.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hvprkbji.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxkfqny.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnusaitx.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyzitpo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnumyied.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnfvbcz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2scjdxcls.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2surmloxc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsinadv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bskgbpyg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2chhbhkfp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lziddkhz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rginvjhs.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjpjymb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2varklaew.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgenrey.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxkbqqi.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdvrzmk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tchtqefa.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2egcvfufd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwqcpvj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aqregldp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaclson.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxkndfz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2felueixs.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dswfiphg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2indartaw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tydtcins.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzgukxg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qwstlsih.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkybvrx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wybjkwoo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjlfqab.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxutpks.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2imnnftgm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvtpirc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zagvcujz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnuekpq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrucueud.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvclzfe.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbbldfn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pezeqxsl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiygqtx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jysphjgo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjubded.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcxbmbu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2aypmtnon.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2heyagwcq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrbxstd.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhvyzli.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2anckdrvg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvhznxh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2isgnxrhz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfpxqgf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlhpcxu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtafeps.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhkggwq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ubclfrtz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvgtpwk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbbgmhq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2csnbvrro.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdaywas.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2yxluayxo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lestudnc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjacbcrw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgnyvse.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2nadrkweq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkumlyt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2studhfzv.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfdvygp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkmkfxt.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtrbzqd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vireisjj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhvioui.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkyodhl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkzpntn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzskpmdx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nchnxywg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvracgzo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzmkoag.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxgfleh.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lhplixry.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpywluuf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2obezzdid.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrwvvrl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmgpwfd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mviwamdg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzhdjfr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaguvcq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeyvykl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjjppyj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsakaaqn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iihqqnyj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qalkoihm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ummzvcle.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyeasik.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdqyoaa.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnitaitm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmasmec.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtcprjk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gnozorta.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzjgczg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqbzdss.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoowetg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2llobpaua.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzscbhb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfcjqld.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2klvxjgbk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2myukwhyp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2parpitgz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcozcsm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxkwmlb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbyzlqe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dslzsfsx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uermirsm.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kfszzbaj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bkacqllr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrphjlb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqwtxia.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxyhdmy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgevrlzr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nzarolcq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2einmohgq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2utxfjzhq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2noxhylpl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwliyei.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zspgrfmw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrusdgr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzdcsjs.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxsrclu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2pficnabq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzinnks.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdemenlu.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tiafrrqs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cowzageu.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxdwxli.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2focomqfv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zgaqoker.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzeknles.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uedsvsyp.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmuptji.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzvirpk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2oytzrwgt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzqclfd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2awbkfhix.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnvpzwt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjufeaiy.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qjygpdqd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2pytqogbi.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yfblkppo.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdulhhd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2utvhrrrp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtvyigf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdixguc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsjplcx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsczajj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwwwfdw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyqgdwl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2kbimkuzh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2suozvlrn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsmyrrm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jedpnwnr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuithuv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuyihlq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2obndgcem.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mokgoxsv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjnmqfh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbugayl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kchsjqbq.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mplibizb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjgoysq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2shdkebfs.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2opzaujsa.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lsolwmau.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2waidbmyr.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaojhgd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bknfawbf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eohhuqft.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxqolli.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcfqofw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2llyrpbgn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xwiltaky.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2belyrkxa.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2clpkayvk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ootyskql.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tztbsmog.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qorsbpxh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lujezwuy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxbuwzk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgfhspd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmeqfdy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hfodpzxz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqabdndh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ydltthji.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpjyreg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yznooyfw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmgsghn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ejumbrot.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2chlvvodx.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wjitmppz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbejhwb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnfwvci.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdjllmr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bjugqtli.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qakvbapd.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpgxgii.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbqcbnu.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyxmfhn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkdmssl.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqbgfpm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mghiigad.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xporyziv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2axdbjyhx.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lyikpqpy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxvadid.html


<!-- 参考信息 -->