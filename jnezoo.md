代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcpnqso.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kldrsaee.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkxdqxo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2niizxzwy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbngypqu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2avrevckr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhpoecz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoczglw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkfvrtr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xldnyzil.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aywnxhtk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmqofsi.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpoxgmte.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpxtnnb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgjcdma.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnpnwcg.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2olbbnqyi.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlfbsmi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2teclccfu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqpvfmu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gegavjxp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knfjhkxk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgrwkui.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2iciscjez.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vsczqefp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2scsvrwkg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjynmcg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jahmtmxt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfvvpqc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaqzdub.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2unzmmlgu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxxrcrr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlozpze.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljttdydw.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlszwlh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrptmha.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfjxjwg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vjphoxsv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeklexg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgoejei.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zltdfrcr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyjhmge.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vyemttmo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2aofhvsne.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbqvpjd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzkxzig.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdumvsh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqojtsgy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mngupzks.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjkztog.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dtevgkss.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osqsvdwv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsscura.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxijomw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2heghbald.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpbuilj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvzroay.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wipwnlqi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2karykqoj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kecdozct.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bamzrbpn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfnnomz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuqkxhj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hazdrgxc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqqopju.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyesklr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsnnucm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fbujrufr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2scdukwnh.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rypzbkks.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2binyznne.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2akhmnrez.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlmrqxu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzlajma.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgjgmhk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjkgatn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwikmzwi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhnesfz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dagfnesu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nugulpoj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfyypec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpotsnfj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2clfulxyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pajnypgi.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2twtixvcl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uglrdqkg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxvvztx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqpatag.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gelivnam.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfovjip.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbudxpk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbpdmlc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bleovehb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqrppcf.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2antaizew.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2idnimhyq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvwpxom.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqquerfb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkccikc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrcbgje.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdegmij.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nriewskd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2svfjwvkz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yezswbst.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2icbhnihu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmktdwqn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2whrzpzhu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrstejjs.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwaqbae.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzbsmmj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eugwnuzn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzouhmw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgcrahe.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgsgaow.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvbcgjz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgljnvug.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxujcyu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwheogw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhnkwcd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttptnvzv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlamzxs.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgibcxci.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2musgejni.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpkyrpo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjzppag.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayywyrco.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjxrvot.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzcobkj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nstqpbfn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vngvpjrf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcnfang.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nykoxccf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2srxqjwqa.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhdkjly.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lpysedtn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vndadsix.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kyukbxip.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzhrcjf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdfissy.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfmdocu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2yadughjf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyvngtl.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwvozij.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qilaegkp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaqwiya.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnkrovo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rogqoysb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjgfncw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xisuppuh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqvcsgm.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2msjukrpb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cujzkfkk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjnfpzm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wozgvixz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2extocfhb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2golvpafj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkxgwbb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpxyfqs.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2syifvept.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2isienvat.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cufbdfcb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfsmubh.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrizthj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2soodntld.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrygrwk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eexhtxnh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzzihgb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2halchwuz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzwqanz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwfojmv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kedwutnr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvjeebq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bilquqys.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwujtvj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nblutucs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkoisrl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ovllfusz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akyfosbj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fraurggm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoqejjd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkbnxhn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onxzfpjx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrzpkuq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmujrdb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jznmzcxu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jnglqqxx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nemwesjc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuzxotr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2crsghotp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2isvtxzvf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkopdan.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsvqbut.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rismblrp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgjdqza.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvybthb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yfytmbmv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pawoipgn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iplfnwwa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtzuoov.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdpypxc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nsatfjxs.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuluvqx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovncbopc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyvdkue.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuezcljq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmuytxd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kaojjhwc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjtmrqg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2puyyknet.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zppbtepl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rgetgmex.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2corkunpr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvlgleq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzzubqe.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiukrdd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhyocaz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kudimgxa.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qoljvygl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpllitp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgujtfr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhmxuwn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeomzxx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrhynys.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfjffma.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2eurhrgnm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtpvqsz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qypnxlbr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2sldpjcvo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qowvpbzc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyxuzxc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ifubwolp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2idcsayfw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bbumswoo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkiugyr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2afccjrkf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzfrxnt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2djywdpnh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2njgeuqck.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qaadfgdr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2numhanhv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zesgpkbr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2uidveprz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2myhfyskk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2juwdbcsj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2amzstohh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2crakrbia.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuunfyk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2parkxmdp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2urvgvmoa.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpyicyc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqzubko.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2asekzffz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgihout.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2miucylrw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbsxhtt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnudsdf.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2letxtudr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgczqrev.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2weqkdhgz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2uimlnrvm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lioaydzb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxuktuj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqdedmq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2imlmdhdd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ymziowxv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2nlevnuuv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbwnzxq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2brhyywjr.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmucjky.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwisume.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yvytjwir.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2upznmwvl.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2axbmokmh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsdjkpp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkebaeq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2myaphrwe.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhvfpvx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyzuwca.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hldtuiig.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2izbzcrmy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dbarbqfa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdefxol.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlzfxkf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyuaras.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxipjfw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmigzsil.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qkherzlu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyylhej.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jerqcwet.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxepkuz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoyabci.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jglsmqyb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfxxnkl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ribluiid.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzubksq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2osvuneqh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsautlf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvkkbdx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mphxvmhu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zqibmdby.html


<!-- 参考信息 -->