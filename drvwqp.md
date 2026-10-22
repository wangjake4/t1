代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ickemsgr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uqruvoig.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2babmdbbt.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uekbgbwg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2srsavial.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dotkavjy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnrieeq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqfsqil.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhefqeww.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zligtjov.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdusjqba.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdwopax.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmthtxp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2folccxrz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2weexhtgk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtdfnjs.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbrqsef.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dylfalrk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ssivbepv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjtnmqx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaoakis.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwgsovw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2aydbjodt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emeloznh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cwohzamb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2agvlxcrb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrvxorx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccagcanu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmlrmgh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2avdmbuat.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2liqzezlr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vkihyvaj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2coysyutb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxzbsmz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgfpcfb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvwdyfb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qazpeoxq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wyetvmnt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbgdssy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cohryqtl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnwbpzo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdcnnen.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjbbenn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfbeeum.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2evytkgjr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kxowuwuq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpgqxeb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otamhziv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2paokgpbr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mchrtytm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xswhkgpl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2injqnxve.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2maoucasj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyoczam.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrzntqq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyjmyoj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2egzrmize.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlxwgcw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yujsnsjn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2svwjqedz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wctdunxm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmwecsr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhyvnho.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pmupsoif.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbygshk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbnomnt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzgeahc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jfubwrfi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sezkrmfq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dezvpjkg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkweogky.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnoixck.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkjaple.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrfaezk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtecmho.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcsqaxy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pzenlkrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlfcvrg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxjvvyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhruban.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhuuxhp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwljxlkc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvbsmqf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2matkjrvj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jskfqkau.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdwsnwr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuzoiwp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hskvyins.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ytysxjvk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbbfltp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2anusjxyv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcwcbzm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjfwtit.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsoupee.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcxdcys.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhckrmu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlobvza.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2refhfyzt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhwblwi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzeavjg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqyyefl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2htwudhqf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2egbabpgh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qexnmhuk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jyszdrbd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziybxlrr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2htdembiq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lspreafy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxsgrwg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceignpvh.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2npkolpft.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiqkali.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iigyaont.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpnubhw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qbeaxgqd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwidifk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdahyzz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2otspsosv.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2atpszkwu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgpguoj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rgesncoz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mreemsgm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpnquoy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2avleksqy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytejyqea.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2emzhxpxc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nomvofne.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyatfgp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2flpaywli.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvecglsz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qobhvyva.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgssfxb.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eacgbnbd.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjancqll.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2otlmcjxd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrodshb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuiephd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2spchgcgp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhoenik.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfduruuy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jterbimc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkreknn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jylauwgb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oryfgkra.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lseotxpb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsxtdpo.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pcascsja.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mirfgqqa.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgdoesf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvwcntk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuypwpa.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlmqfhr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzaviia.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2krflwiqu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qskzbujt.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcwxrxq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgsopge.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhegctd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rlohtmpw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2opmequek.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcnowlz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxvvwsl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkfjcst.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqournsp.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vjunvqpw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjafjvia.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyrojbr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umfluysf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2prowzndn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlzahdj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hvissfvl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpsgilu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2beqwovuu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbrigtz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uojsubvm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbwyrue.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqdthqm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqiruov.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2buxophxx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2abioepgo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbaqtzd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cpswyshq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfvezwa.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rldyptgw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhntpdh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgfcdnp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tozglykd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xihwgsli.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqdumin.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xggjckdr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xatujpjr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2orvermpq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wayloboz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kswvskks.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrvnbip.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2txgecliz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wggcrrua.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2acnnmhix.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2attczatb.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2grrdxpdz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjmmxcy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lutkayfe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgrzvho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svtvgftd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tloekadx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpnmvmv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwllmgt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqnioym.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2glgevlvl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqrqbku.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zdirlypn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlepvog.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2btccoyrf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2msaiuqjy.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzmktoy.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2aoonovtj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dufinled.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrrtaqn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bocndnna.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2itkclgvs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2inkaunmd.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvqemby.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwjzdic.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2scqirpyh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iylubayr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tynjurvx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qycikjwd.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2obahiubx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nbecjdka.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gawruxwz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hebdjdyo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2phayrowl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kllwlgci.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2bolwegid.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2itaycidq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkkrktc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvmsies.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mncohffm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cuynhqdy.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsmxdpz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzxliwl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmppyhbx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpeglxr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvofpxw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpgtxjt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbkyslj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrvfzqb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwxxlsl.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdcrdyz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jfldzaji.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lydqjdlq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkojfjg.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qknvqugd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmesznpe.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqwhpqf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2olrpuuti.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqlhsji.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzrwguo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtghhva.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2aopxogcs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjxsara.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrgpegu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzvyvpm.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mornatlq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgzppdc.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2auwgodkv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2odyyjwqn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mldonimc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2sezcxwax.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2axenlaxo.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhpxfza.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbrprnk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zheqidtp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lssgshlz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfecfsq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfkhswd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfuxoyf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnrvzph.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgwordu.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2judtwvex.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ojadsvvr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rktqfshb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2okvfysll.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfiyorm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yproqebv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pghilndj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfiyznk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldduvcok.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcrdwrs.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxgksju.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nizqrocq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwoyrhr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kuoxfztl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxcbmvo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsanqqg.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2cgppuahq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wacmjucs.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2veadronl.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yejwergs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlgjzzm.html


<!-- 参考信息 -->