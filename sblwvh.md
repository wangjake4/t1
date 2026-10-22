代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dogjtqyx.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljisstva.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjzbcfp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2atmlxadb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mieavinf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdoiuxq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wawkiaeu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2yurjshys.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwoiveb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkcysxp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2impcjpih.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wutdwbpu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhbwggp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yngwdnmb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbauuhi.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2khiksupz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmmsfnm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rajysbra.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zfisaene.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eetzosnl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjlygpd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpnjqnt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vtytvmsk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsptnlx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpwjkxl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgziczkm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qanfnpuo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvpilrm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2kapwhara.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwkzqth.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2oggtfzup.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlpckvq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsnwqqv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2irmpctot.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrnajey.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkmjcas.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmxgjqn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2isgpwjbq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2idnuvyjo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlafzltz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aluojeid.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2klwdvhua.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxdoobm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2npjqcxdy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcmbery.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2srnnekkw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nnndozwy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iejghkzj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jocfwcpb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwmgwem.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ywolphsr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icnhgnee.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2berbzvqh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhmgkto.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2amzesheo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmciwjo.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaghiwo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2swxngxrh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rmovdobz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2amuyvhth.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbaabbeo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2codbrarx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmjlqxs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2khnjfiye.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgygwpd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgkmdew.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgqglul.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmxjqnf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbzvmee.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrcqzfo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2owdahehf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xthuaasc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wamjkhfq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vmabgskk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sojnfeto.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2atlitheo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbjugzw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdnoqqs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmrbwjo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkibnla.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2irbjcxyw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qllxjyom.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2psacbpbb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pueogrdz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbuhyjy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsylsvbl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lbixjnby.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zihknoxm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2igsreifm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zirkteaz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kenkykac.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuiblks.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uubshsck.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2diyonlzm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vhatueqr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsewpcms.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2trxabzxx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkghkce.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjgixmn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2euuvhxuy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjwfnpa.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpizoawy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bslxfein.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvudqwy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2offgysrn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdxgnwh.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ogeozeig.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdjjcpz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxcvflb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmryozem.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yjusnuwz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ualmwaga.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxujjru.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpfdzyr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lzechidv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rszlsgjd.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmgbdeq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2omvlwvaj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2giffcqqt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwhqsro.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbhxfuu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aybkircv.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tntehoks.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuzhuil.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zdocvbwg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmseupt.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sggrubdt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwzbwlh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgalwyd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmkusqk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2asbjebxo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eumycaol.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pwudkzcs.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkitmqsf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2eugrsgyz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tprabfxk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvveibr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcbyjqk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjjyojq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwbfhob.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ntycyjoj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hunnbhkf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zualdwco.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndaieqkv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjtnctt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbehixmv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2burvdvog.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2spuuguzh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzevxrco.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmjymal.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2sphcegmd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2asisbgto.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2agnyamgl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxkvpyf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kyczkgtz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqjkvzy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2onzbtbdr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxexrgk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qntouhsu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vzawvaoa.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tmiwikfe.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiufdefb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bdapvaqd.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgrjknj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zlftdnwu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2izehpyza.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqjmkfz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpoyipt.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkjpjok.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkikgzyw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aewksvko.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwdasjt.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2idfgrwal.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfezvuml.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvsbbbw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekttydiu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2aabtyhpn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujflygbs.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcyeqzj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kydgopum.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdflobv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyisoun.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvespou.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnorlhfc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbzzzxs.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mschpfbc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2elqvsjmi.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hncfeeal.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qextsmso.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzcgnkc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxwmxnf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tehznhym.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhstaydj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaldssb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxgaaps.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaypaca.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljasdhwu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrrmpnq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2exwyxxzt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjmlsqo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ledevnio.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2slwwrdpi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2irrzkjzg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgfnxos.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfyewhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xayungab.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfftrgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hutltryd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2roeqggku.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2drwvpvoj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gphprxny.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rsihmzcc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpwsono.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjfhcwn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiufxgh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeqnwsp.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2friwppas.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkfwfna.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2chexrodg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2laspjwqa.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpnbbiz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gappejkv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbosuqj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jahujrmr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hntdetpd.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfngqoxy.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrvjnjw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuigzig.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yapfylba.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2easojjix.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgnzswf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fynjqcuj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vsolbogw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sisfaohf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2davwnlxx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgjtzmi.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdaopfy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkrpckw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2iawzzrbw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lonuywlp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpuqyrh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqjkipk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ceatoqgi.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbibdke.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2iafvyzrp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2obwoyyvl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwhmuro.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkkeavw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvycuzh.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkuevqj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ulirgolz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkbuuaf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2csbuabfj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mucnfsfp.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kcogdwfk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfsodjr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dpngzurt.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyutzcqr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2thawooqa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrfxgtv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fceklrvo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vyocxctj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2asznylaa.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxbffqf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhqaojc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwznxvd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzrhxmt.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcixhuc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuelccf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ivupsiwe.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bkexsvxl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeydbeb.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nhacponr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qusuguyk.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnzoygs.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlhxrxu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jydttrsw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyffqzx.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ndktztuu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrmoraq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rufupbyq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xrblnvza.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdwluco.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdmegcp.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nyizstzy.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaturhk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaquajj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpaloniw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjrbzbu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fmeapeqj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hiquiyrj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sohcfyqy.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ztppciea.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsdbacw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgyuvft.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2aviagvha.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhgblmk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydentbcy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ossbwhyy.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hqinugcy.html


<!-- 参考信息 -->