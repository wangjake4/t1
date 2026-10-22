代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwoqojm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2beoiamte.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwkwliw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2krweztsl.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwljtwb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxoikwi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2acyfyjst.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmhxomd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooefrmwf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnwfrdx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2riaswqig.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgskfaz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vicdvodx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnpkeeg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2grdklwqa.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pmviszjn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwqnwgf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuydjdm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2grstrnsi.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbuiidu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbbeetm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fcivgpfv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugigtauv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2smkdjxhw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnrjzcb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzjldwi.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbovrdq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uydqetvi.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtzitcy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2arxpqoyg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ianeylkq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bzksmmzr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkslnlz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2odidyjpp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtrtgfh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiafurh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpqdtsw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wltlukyp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vwroihzo.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuggcmc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcxtisc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeoeyiw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqcqczg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdsrlgo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcnikmr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyakhdvq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2giepvtnt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtgtkhr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mimdfjtl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbzvuja.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gmoedvzd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xejqxtrv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sipcgbkj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2poksenda.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqongii.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxkrgry.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aihhosmj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvvjwga.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmdeefu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyjdlzk.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2naqmtnja.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyucbez.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hluihpoo.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvpmkyc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2chvorxuu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2meeqvhwn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ysucuhix.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nabwltqa.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mztvozcw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhskhgtj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgwuknh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqhscri.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaicjfq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ribbhjfy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvjrbqo.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgprgai.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfkpbdz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2afzaqfmf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kphutlmc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tephuepw.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qizduhmz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2brzxgyss.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2htguqwsp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqelyuv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsrauha.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcqzfeq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlfvtvz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vcybyeao.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uavufuti.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qnytisxg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfngkwfx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pacnjloq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjnomzy.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nelowoff.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrkndhb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2espbtzfv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbizphv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdwfftb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2maeovmbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asqkdltx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzuofja.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwakyvl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2meezymgm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdnfjlu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2daupborz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkxongn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jthibpur.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzssoam.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlzzqth.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dexailgq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tztfhcte.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xofnlyem.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkthdpo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyslcoym.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwhpqvi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvyhdvi.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxexiol.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmxdopm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzlawyx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxcaqtq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdqzvzg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcwgibk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2emxlwvqi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2taikdulk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cthmnywh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2usnruqrf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2paughbgm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyxferq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqfjega.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2icyvtmwl.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwytvwx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvxgduc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rvloslgh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrwpuev.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mkegdvmc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2utbbfitr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyrfkbm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyvtexi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rshtsqvf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrvpcpw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oxknyvdf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgladbvp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2blepfyck.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmwcren.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzwvycu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjnfnhn.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjmfihw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uznmmkew.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxgdutt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtijjigj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2tknbgygp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2seqztnoi.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfzetjf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlgvstv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtdfgsa.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2askhoqgk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsrwwgm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dszxaqcd.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuzpobm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkbxroz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqrhfib.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2blwjeejm.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ivamzhse.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkqypnl.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhulviis.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2uguxnjfz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2afclbhqx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2shvilzqm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pprjsmkb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfyqyfm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ainxfxay.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vvukybeo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dznkirfo.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2medqizeg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmomfdsc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2sosukiov.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2chekqnbz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdzeeot.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuqpong.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbddhkb.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bouhdtbs.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeywjio.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2txwyuoqd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2avxkktog.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pawxvzkq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvabmmgz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2swsfwcye.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brppbvxq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpdpxci.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhubrkmn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgpdwwi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jojlqicq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdcoiio.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdlsuvz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zptkswpn.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuyhgba.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqokzhmy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oygrrsyx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vruqyhzy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsclyjpu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbclbgx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2icvxfsng.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2htegwypz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2atosrrbv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpahylb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iziudhai.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdasqrh.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ittplpeg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdvyamf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mszqvkjr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxqvats.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiaccro.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhnovxu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2maxoycth.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpnvtvz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdnwpeu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2oexubpyy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwnoqmw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzrqlfy.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbxhzeh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvkhwhi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjchsvjp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2egbyrfgh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfoaqpc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbhayue.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ewodnwkc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdzdmuc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwofjcz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2noimaxih.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvepbdzx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2cblskelu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rzicuged.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdakgpf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kaflpenx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrcwgsu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2psjypsbx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrbkmlo.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvufoya.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2afobgphv.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjtqorj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmydzhl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuwieyd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2brgqgarz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsmkqzp.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzkhkln.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufncapdx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kamdjmmm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2koxjjepu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzldpzr.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgufpsaf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdsplsl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtanfwu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyplufk.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxegtdx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxyvauz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjazdbnm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mafhlivi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvcrcjo.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdnabzp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrvhupr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhpndki.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpyopic.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jknqltbn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzyxfwv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vavhexoa.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiyjeip.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2lztbqwmu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dommzrpp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsaxfiug.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yanwnjld.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqqntkn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjyitiy.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2sqchogum.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwncgpdg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgjbfmx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dunrlemi.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzayrau.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ammfiviw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqvnhpx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqjbovr.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvilrol.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvydqia.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmrwjdc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlvsupv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2abtygciu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpfqzjx.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ipahjhuw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vunkarba.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbsjhnq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjkbefv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cssohfvp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlabpku.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrtsneu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ersyblgm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mohnucng.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqsbbcj.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2swttqbpq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2srpnkjig.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiqiedg.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2levxjvij.html


<!-- 参考信息 -->