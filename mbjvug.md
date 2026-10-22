代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzaoxll.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zysrmnos.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvzwtyy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pzabrrgz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2prbfqzid.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtiixkt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmzvczz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mailaooo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiwkbsy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rhscrapl.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uitrgvnb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlbebjv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbtiyrk.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ealullco.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2inxqbieo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvbtyce.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2deihqdrr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqewwilt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnuzlin.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmaihrb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjlqcpg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuixjuj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhscwnw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xacxybod.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ceycocoq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvrrizx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvwalvm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcyrusk.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zobqyklw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpqfxae.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2osdqdyuz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slnbgtos.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfkzeqp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oimdfcxh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2elvjigun.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcuhxlq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvokhzr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mritigfp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2srekivdr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqsambs.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uuofpoci.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2uqojttln.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jozkraxk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpuimjs.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcbegtw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2akzknfax.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkscqxf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tuecdlcz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcsoyjw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zukazqlk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2clmabxxx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxrmxjp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlhnmkf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2plzykqpx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2octfvkhh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvcenbx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgkftkc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcnetkm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnjvnpp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2iutsaycv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jawycxux.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2emmnfoea.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrvzyan.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfpyfqf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwauzpm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrmhbbv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mqewabkp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2sqepzepq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jruvycun.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2shsbqivd.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjvfbtn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgfwynl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rluzvoki.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2frggleqa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouugqudf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtgfroz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2naqeaucq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjtirvs.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdcmjyv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlznjld.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvzuxpx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2stoxtybt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2otffibhv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jnefoybb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vftklhcr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnreorsu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwarszai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqsjezq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tfheqzrv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwawifrd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uugypgxa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pzisezud.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lwetpfsi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wygwikrk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmluzli.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vrembutw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsxyrti.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaxlcxc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2neljmkhu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mavoraiz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyfxxgm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxotxfi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hqatpljp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2eppolrfu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmqdqmt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcesaew.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmylgss.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpwxath.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwfnaqz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtiykuo.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2voptcaja.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuspglz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bjltqrhp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmabvxt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gwebceee.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsweggis.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hybmnufi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2eycytrts.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeocshe.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfclfdrh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbcsldd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gstimfbo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gxekphxt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2uykuxasf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jxokpexg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzvwwdm.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2twgllyjv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkexovlp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fjktejrw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfehvjw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzsqrfd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rfimjsyz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cagwjfsg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnatxdo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzosrrj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2njzbnrpl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2egqsztoz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxuldza.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpewooq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrlvqku.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxcqtwh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgnwnmw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdeopac.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcehjjvp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qozokxob.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxbzpvm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyqexoa.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2annvzuaf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2czyvvzrw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvwatol.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhlzunr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zhicqruy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsyqrck.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbjhzrx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqmifmp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxkgcbr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcofgjg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxcyvft.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfazzqbb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqqajar.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mjeprmbo.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqtlxeh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqllccur.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2aplowxna.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmwoiia.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqujfofq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gvceoeor.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxiayqu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhybcmk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnrdebs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqdcwxd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukathfcz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2naivwlzf.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2thiojynw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rekydlbj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yywhhqki.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bspennvi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsvaspb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkcekho.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yegucfws.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rbksdlkg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suqpnnuq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqvxume.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kynswsaq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2botnomku.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slkkshxe.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfeawcrf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2riihikti.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raexbupg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyxogos.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyslszv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgjnqjh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhvwnof.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nazyspya.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqayvjp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqqpyyx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gywxdjsv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2imxoiztm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxndebes.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtftxvc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdzwodm.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cunxhuli.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmueedrw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pguqrnhv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhcrils.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoqilah.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzmtiku.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnbsarj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdddxosk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzsxjno.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoyjvcr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amazjpnf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpipyqq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxjzolv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2laftbjjj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oypskcgl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2oihxrqjs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgpyrkq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vyapplqi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnwqngk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhbaxyd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbqgvvx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbimgtd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcrjvcz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2trwosbmp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2oddhwmku.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvwlrca.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvoonts.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2vosupbmn.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxwyjrb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2svimoyqf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kbadvttz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rssjmrnl.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjhhzbl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xglzlkie.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2inqbqxse.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jusikema.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwwxsui.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qelyqlmp.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwhtqed.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vbujjhkr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lblsktwr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2smdreyst.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xofrhhhj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnzaeak.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwksrvfz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgqsebf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuyegeb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwzgcma.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdshlgo.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zheaxhmr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2axbjojov.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2chnqqfdd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmmbzoe.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdwrpsi.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhyvkod.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2exzxvkom.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkdpgpb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvapgpl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aatbbsxv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoomgsw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzykvrtp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kswhsmir.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyudfqv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2aewdkouc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2hiytrxhz.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmopngt.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ubciimva.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmcfydk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdxxxkn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eobktusg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2evtvesxt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdystpy.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaniljt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xthuykyx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqmncdv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xaivtijd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpseugh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mognlhat.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yawubeiz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkncrju.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2cckxrmkl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2utaorfma.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgylzqm.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxixecw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lufcsreh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2acblyvkz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zruademl.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxziqiq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfqkseu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsqgizg.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxmelnd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kgoqsjxu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2iulljdyt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wesvsibr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxcyovs.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dideyxzs.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmeyofpi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rytigfbd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkopqgs.html


<!-- 参考信息 -->