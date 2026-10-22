代发 wailian999

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wehdvtps.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrsjxlh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oooghbtg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dregyzcm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yauopysp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2leumtpak.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2gttaqjgm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxszvjm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxwiglq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmrjrfq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cplvdysu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mgykxzog.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jenfoasr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2roeloqrs.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtojxuw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2frjcdqbu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyftscfb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqdlgrw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwezsdt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vplkczus.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhoabwr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhepzkys.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyioshbt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcvoqoy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmixhdx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgyilis.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmjaddl.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tszgnzgz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2odkxvcxc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmlgnnt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2avpmpshu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rnavnebp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiukifx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcajhhop.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2yuubgfsd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnigqiv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mskuromz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnjcayi.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2uaclwclo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eethrubo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxdroph.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcabnsu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2noxtshkg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2unwfmmzt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pdefudgd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tqakumkh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rpifmhlu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2timaoclq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxvbsqj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuqnrdw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqlgvru.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoetkzy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lalefwob.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ievourcf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqaelnq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nomuksbp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jjutodbe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpdxraa.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvswmhc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvipuilh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2thzqjshq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfptdfu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoipqvu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpaqvtfg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iavngukd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2apsxjfnh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgvesti.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mxptykmt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pliljajm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxjsrqf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2goghbrcn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmquoml.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzghzhi.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgesnda.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyibxoy.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhougpg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlhycga.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uhszcrly.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqgwgxa.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2legrhcdq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwbsmyl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiqaurm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2clnvmpoq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvbkbzl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2svzmiilo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdsqomh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdqgesm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2anvlwcfh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdcutlc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tawtlhzc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tordmivu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqqwamw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2urljabit.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkfihrp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyokptg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2poobdtqp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2albidmho.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucphtisj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjzdrmw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fikhztim.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2myusaxiv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2exuczwkv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2arilduyf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwkhgdu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfllvqt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2twuxgbzp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2krcaqnyo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2afepjtiy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zocqqvnj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpqcjjt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvzenpi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxiviuq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qebdphos.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2flqnmvlt.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfgoxtu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuwtciz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pmksmolt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2isqcreji.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrptksk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbddfxdu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kwblbxfj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhkftny.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2atqiadqg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hphnwwxy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2htkqcdwd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2benuhwgp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2njhafsij.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2brraksdw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxaspxr.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbpmkzm.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aidhxaeg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewudmskl.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ryheghpc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2krqerepo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuhaiso.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhazyfc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2owdhetva.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oujwyyxd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuhjfoq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gevypfia.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsrsuwy.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2swpmwjmu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xibfgmjl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrqhijz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlhjpox.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwitiqg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2smjdnymu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhupvxi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bcknodrg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvixcjqt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2udgnkdrl.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjajyccj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiquhrq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwobyuwq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zodorrwf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzxpevu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kyitlznq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2giujsesi.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2drkgtilm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hboolrlw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2otgjusfu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gpquvczb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2djwherwm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qvztlnco.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdjxptv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2znazpgro.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xikilxgm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jhktwuoz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2okrkdrat.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqppijat.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mxenfqcm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lywpmwxn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uudjermj.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrhrlfk.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcisxjw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkrfccx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uyigjnqh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2sstlxcpq.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lniwipis.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxhoqor.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtkqkfk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spkkyuzn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzjmbpd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxwbtyz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zatqxbyy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qedvglqt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wldderuv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zagoryfw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjmvide.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mopwuzgp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2djwlckuw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xubnjqvl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivivpxli.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhuldnh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngszihlm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2abzcnumk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2whvcqrxl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvvrgby.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwpawtq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjdrhwy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hltqatpd.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2droelxut.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yctimhic.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rdurrzjm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjueydss.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlbyese.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2udiwdjle.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gsanobem.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2aoikvwhq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2twexhrxp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsremwgf.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrzzgof.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2sogsqqfz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbmkqnl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwjwakd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzljmnjj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2daqzkxwn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xcukbxbf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2silycdrs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhquypnw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzpmacq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wulqdgzn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgsekfd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ifynvxtk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrabudc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqmlxzd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2swgmxemh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2crfnlken.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2npnxmxqf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqirkrhb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcovkvp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tkelvmvw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2upsdimcv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgijrsx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxlnjnj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfzfwwm.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dmclunhw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlazfho.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvxktgr.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2psffmfvu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxsbmva.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgzcofl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bogcmhbf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jieitcpl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nymtgwup.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdemfljd.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2icvgfmgl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2myclvufn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvxenhm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxrwagh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2klpbumga.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsumsxo.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2acswkcwz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2spkdejcx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtteasr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2skqpnouj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmprxnm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ryteiwvw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhccdwt.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvybaurg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmxppha.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoldfwk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2srmxsrvx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcivqlis.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2nhettcxy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjnfaao.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bvulfaey.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdiptejd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2adiluhty.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2chaazvfk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyhrspp.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mljwokjp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnqvxbw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxzjdqb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2evpwogsa.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrdenwi.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzjiowe.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqoolpu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxixnay.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkgdvmr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdsdwlm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuqaqkx.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfoacah.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqfblga.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ryznfnay.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wryilhbo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjbovvp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmzcuyq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqyjevz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dciabaqn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdnovyl.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmlrxyx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsdppvo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2krfjibgv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzkadmc.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdebvqv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgtmzbp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnopyyv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pakhwnyw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzehsmhz.html


<!-- 参考信息 -->