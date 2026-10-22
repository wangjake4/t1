代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqsgwgn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzufbxa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkjovmk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoewall.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgyeris.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqalqce.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoamiaix.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmunulh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeunnplm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vddbbomi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvysawt.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjafzmd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyowurdz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vuamodsz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlxrgff.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wdimqhoz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjuatwb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qiizvccj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjdmapd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2sovhcggt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwklppe.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhdoiuu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2brobfqol.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeempdy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ysehosfe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvolmzo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zehwtfcm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdugxva.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yepfttlq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaznfqlt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzoifrw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjudiqk.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzqgpse.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuuprzj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ierpfgnw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnjqtiu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvnkpig.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2htlokhgk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2agqduhkn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tqitedru.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzilsov.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsgxxkz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bojkucrf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzuqlpy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfkeaja.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfmtdid.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlgbqdq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvrsoye.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fmibaenz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nstuodqz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ekartshy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqblxnc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyjtwzp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2varmnufn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsigfyz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpoievc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2maktpnvs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxqjeys.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptviqqju.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwastti.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzgkzso.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoeajxh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nicvdmrv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tzipbxce.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvszozfg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2srcqpijj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xeupfgme.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zxusgnra.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gldbuddj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbjvfwn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qctgsfjv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aeudttkd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxzqkxh.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuswtlc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxexgik.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zfresxmk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmveqalg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbmefrw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2owblflei.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ysujiova.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lthvjomd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmtoncj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgezzdmq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjstooh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ioikkhuj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qphcfygy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnriurn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwtmllj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2frdfqtud.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cngsevlo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lwecdjcv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2adnodanu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gfycgqdc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcajcfcm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lvypqmwp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnikpvl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcidxaq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2houwmdmt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mxomkppp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xckhbplp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nvazaqcu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxxvuzi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpoktpa.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wswmcdmu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gehmurzt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjzhgcp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nliumgic.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzklhtxf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2elceoluk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjrqqys.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfmrozs.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jigjoono.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dbynaaqa.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcpovbh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lahdhwys.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoohnjd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnvvqvc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjukahv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwfzkab.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuimwxiy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdrrhin.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzjigfe.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ormupvzp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2esdrradw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxwbgbp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrbzilf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhmzddx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkscpob.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqjiqbk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbipqqs.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwqygvi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdgerjm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbgpqgv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiczbzl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vqufcoie.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwxrqmk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwchqrq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjelayj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ieutiupj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2squzadkx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tdampagx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgxzvdo.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vaheksae.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpeynae.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2himmstxc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2umeurpzz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nksqylca.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqwgcww.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oukcosmc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwgofec.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mlluvori.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vutpudqc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtfkrda.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2iragoebm.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ardgyvwj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbmiker.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsuzyxm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hitqxubr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrbjkjn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvrlhvl.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyrvenv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbwszgd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpoavss.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrkwgbm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kujvzqla.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgbzaqm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsjagsl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhkncmm.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2alhkvtzn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxfjmvz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcqlsrg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ircfxeww.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wfojnwnr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsihkzij.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvmbrqe.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqojfoo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uueqhwag.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2viublwec.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgsfoxt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gddpbsti.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lefpobor.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axhcyrhr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtlsepu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgpbizq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2byahjhat.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmxysau.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqjonfr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2firjuykq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfvagyg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2enukmoge.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrgljvo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaktcnk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnrlimp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zqckxmfs.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqyjwts.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dnscwqho.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzkblxc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2flnaozxq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqxgeos.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2onztxowl.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvgdchv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2etedadwh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxdjire.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqxwdto.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sebqsnuy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gqamfdfa.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmifxymj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhyymlh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyofwcmr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amsfwxfy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmiirig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csentaqt.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pprtwvpr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsnqsri.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuqhldm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ldojyzfk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzbyqxh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yglqtxmy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wimatpht.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pgufpbrj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tfteeeqm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2croqinuq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtiozec.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2grffhexc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxzwlih.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhnimfh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfxgkog.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2blynqrhr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2batjxetk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2fixoyzqw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2flepyfqn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipifkndh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sudunimv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptduvbjb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2adkgedkc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwvxknq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfyorxs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlaoqpd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjjwikj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2acpifjep.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rawmtoxr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzxidej.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfavbqj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjojnre.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kyogspbw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hodutebw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvjyegu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqkfphj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkptprc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqnqdhj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdhujtv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbgdsfa.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2imkieojv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnoijtm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2obmpulmi.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhvkerr.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elokcmmo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kimnqlaz.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbksgbz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmplwkml.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfenafk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbxqzvc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zykiggpi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsaocqf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxwjmbk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2odwvdugf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qegcjuln.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxyiqqm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2upaipjho.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwgxmfs.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2igbrifre.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqizngab.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ejefhciw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tqahbjhw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnhsimw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsbhcfk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2yzducruc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dodvqswf.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qymkhfwi.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yksvrqqk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdlxamg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2gikhbkvp.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkozedj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhfjcwt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcptdsv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2iswybqad.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lybvwcop.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qbomlqxh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2msnipuhd.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvlvthn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmpjebn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwhrvtb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2slgujfwu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2slamkckc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2obbantsm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoailrc.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlwxyza.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zggmdgph.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pcygzylv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkemztw.html


<!-- 参考信息 -->