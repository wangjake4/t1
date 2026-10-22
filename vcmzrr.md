代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xohpgbis.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmwuneo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbdrnqs.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ceivrmui.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlljvuh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzouvfzx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyiuikzk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhppzpc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkgyssf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qecxzljy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kswdcmtl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxrubhm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcesvexh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2shpmjgtf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtpjfje.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvnddtk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxdratw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfrwdop.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyafeih.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kjaudmgy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrkamzj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvdesku.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2atlxxuez.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbfevfe.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nflogccn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgyarsh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2depzjdcd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmfjafb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnwnhgs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjpnqpv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2anazcbrs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnccuwc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgwdunn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpzgopt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmrirvh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhcxcqm.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2cthgeusk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmgleqp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2raknbpei.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2deymjeop.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxudpkd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlwqohq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvjbbih.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjocivb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmkvxhl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdspogw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tksmfmxj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyfwllr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zguarmxq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2objtuwop.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2axnnkkhq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsngfbqc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yykozrgb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xfraflii.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ameaaawq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfeqbhn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wqawezhj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqragrpr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2apvcelcm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkopvavg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxeymgc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ondqslou.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuqpyva.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dzaguryq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjaiqxx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gxederxc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvktxlv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2volbjudo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqekzda.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kauhltfu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tffavuze.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoffzmx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iemjjbdb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxvppwc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbqogrt.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bfftcjyc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgnpxsz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjhrrkj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kygmkhtz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrtssho.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvudgwn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxcfeml.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2olrgiyua.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kngxxxea.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpqgcog.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzmlplj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2culmdmzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2laktaubo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2acstfahe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2anfkfvao.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlbphou.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wujhjmzv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtoelxi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpeiakb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwtmsol.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tncndxay.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2azkzcupm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqjdpoi.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkzfbgi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmddwwcn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdeezyj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwyxkyl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2onprmvzd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2guaxbfrk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2snahjqxk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2txyywdkk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwllcymg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnonpthm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tvileocz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2eskfjelq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zgamfksi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsmgcfk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2eywrpmny.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsdoeof.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfufabe.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kshybdyq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkdkzyz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvckkqj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vdistqip.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxelapht.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyipvht.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gejpveid.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqcbraj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyvarqx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qdemfoaj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrszqbxl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqxajmx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpelkxs.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sihznixq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgrvgrr.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsvhrul.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tnowwvyg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqygqmqq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmiikjib.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wajygcha.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwygrusq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgiaqdl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2teljwbcq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2quuijoot.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bchgdxkh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2klwdxqbp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoermjuk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsdmkix.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2osawjyay.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mipsmhrh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2arzlzhqh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqpxztg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmplnvzr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtfcopu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrunkde.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfapuud.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoypjnz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbihkhgv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2uupvtmmc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbdissx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrtutcg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2riacukgx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvstupr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phhtjzww.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmqncjk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ikldlflj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzqsjwj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjvmcje.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rewiakmn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsxmsoa.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjcezks.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqvawti.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnqdprk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gxezhchr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrbxcnt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oszrujzd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnkcxxq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlhmrnt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wttaurhb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvslast.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvquyjb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2atiieutu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfqijvz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvwratb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgljrua.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaviajx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgexziz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuwyqtg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfmuyuf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoiezfh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eshehbre.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqlxotr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxysbpex.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzgixzw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxzlffp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecobknuh.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvuzuum.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2agjeplog.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2llimmprv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sinvtved.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zhayxkyt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoiopvu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2moejgzyr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2psoruebk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ndydssbf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxokzhns.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxtrehx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2furfztws.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uirenfbs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2baixajrd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2auaudhmr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2maezzcdr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2odwoljxo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfiewvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzlepze.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ciusciyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syfcweej.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fgagommd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpvuvgl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ysromgoc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbbxvqx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rqroqymn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tygerwhz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnrqikf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fzddehdo.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjaqsuw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgfchug.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mskzulai.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwpevkk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2unujqjhg.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtheite.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kphoyiar.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tinnungo.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgoitpr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwfpdap.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2acznkswn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2crxrmkkb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oocyjoao.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcseydj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2omdzwktd.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxeiqzg.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2utysyqrh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuysoyy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdfdroa.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbgabss.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrcomow.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfjhicw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jtloyjrl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2devocqyz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mtproqko.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xntdtwpd.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oqokyemg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2omjpvimc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kmanbblt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2weuyhnkb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsbgiqv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqgimvf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vtztlziy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2yncbvalf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wytoucdg.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2umfjzwtw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tkizzzfj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2aydrpxwh.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgrsdsj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2inexxwtv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jggyatyg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiqzjou.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqgmyvq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dapqglki.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwhkmct.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgzumlc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxkqgig.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoacpfv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2alntuwpg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkhpous.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ndubdoiz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dekqtixr.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuobacu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhcecze.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2encckide.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2stbsldsf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2rhndzeyf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzhupwo.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2skxwsria.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsnzmyn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbbfujl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlzvqca.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpzgpvd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvhqzwz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2msazciao.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbssygr.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zmihvips.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2soxyifrx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2itifyqsu.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2anhflbut.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlmhnjp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbrqzke.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgtsdrb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gecgirus.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrlnphh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzbudcd.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2giwfjrju.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtqqqdf.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwvpwql.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xawznesl.html


<!-- 参考信息 -->