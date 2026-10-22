代发 wailian999

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwhkrvv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjjvmpe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ropygfph.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkexoze.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkaurkwq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtojmza.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iinmgoww.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrhexad.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2waytdpgv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpirjsn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuapwmxk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuhtpxc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yatpkift.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmhxoym.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbciyua.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyfapmn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcgwban.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfbkfgb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2brkjmgku.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpeirjp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkznzlx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdyiocb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlsczyo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2laosjnbi.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsoglish.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gksnhkms.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jseslgdg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2enxpffsu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlidpip.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mswyfldn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkkcoel.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2muywncmy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2psxwucgy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igpwelyb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvwvsuj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jamuohzz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2obpemtxh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wulwpacr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ckufpymq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnibhame.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2acrpxrfn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2emrommdv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoesuoj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2halsjuvj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2omhqqpam.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2crbmieho.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhtwsil.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qungutfp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhovqeh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbwcuvh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yxigopwk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvhamyb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ommbioyx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrkpnzx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcbpkaj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhitjph.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fopgoglp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgkathq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2oovdsbma.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fauscous.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pnehosxe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlmxvxg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2czutvkvx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmxqnff.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxvjinb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjwqvjb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqfvjeo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiudmcfu.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqjaiks.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zugvtmlv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzydtki.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bnotefol.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqaftsx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdqjxeo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmutlqu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ozumkxja.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2armyzfhf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlxpdis.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyrcphz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iagfdqxx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiytxhev.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2juldgpth.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2khgludys.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbagrez.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gigldljj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaylrfz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebameokc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2recasrcw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcmefjf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkomffn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgwrsgu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wthpfktl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2iisgbzma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxpksqs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgrfbya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbitqibk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2okmtieqx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2flgtdeqk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtrsxux.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2adcjyexd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gipmyado.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wawiugxm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoljcyl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqktdmb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lcczofzq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fmctwsnq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2opnmhktt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikaooijh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdbnvba.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdzwcjx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pvshlzzh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rczlotxo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyqwnuz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnbaivm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nghflner.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjohgibo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfiedpu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2aomhdsid.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nebfcewf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2czkpkayo.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqtvygo.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnacjkr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjkkonn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzqzzwk.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2saicnnfg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbdqwzl.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzptnvn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvhhndc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2svbxfnvh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2itgdcfqd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsevkjw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2eobcihap.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2paliliat.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yajrrvye.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ficcwukj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjxwwii.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eczsuyif.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2efucvlfx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqcpcem.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bkftdagr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmythuh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuylubi.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xeksbqhr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsovthzl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zufzewdj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmubybu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnvbwnx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2embkbisd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eweapzme.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeadtzhk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pzaksjcr.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhvukwe.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ovorlctc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsivlzfs.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzbiuid.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqoehlo.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gryijgqh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhraoghe.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2feesvjvz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wljgfors.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdelrcrl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2chffksav.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzexhvg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyylzux.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2muggmnlg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2clwyydkn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wznwbaqg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fpurjmft.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuckwua.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2liybvijt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oubobrhz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2obwojqrc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqvfmrw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqttlye.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hszuzlrh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2pssxwvkf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jaquxgok.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2agfitqcm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxnqtsh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oufzqmnd.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbqgpiz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlnvmib.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsltdhp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auoiwcjz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbyzlvh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxunfkqz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaggcoo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjgebzj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyrgghp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfngryor.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dthcijup.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwppxel.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcaktnq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raomxtju.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2domehlmv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxevdejp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsicqvld.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqjhnun.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gevkugol.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gthqnnlh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qitgkjxj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kziriaye.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgesxve.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhjgach.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbrgxyc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrpwijl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhfjlbd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rzefiqix.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgtquhg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kspecgop.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bamgtzxv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuopzfn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yiagihzu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjnynrp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gemhwbct.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2txkdknhv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbostqcm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eriubcil.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwykhxec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwulpvyz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoijeqj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2auaynlrq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvofowa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sakxxjzf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwdrxmb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nirwxdrx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdzrozv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tmegtxhm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuicfso.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmzbhbe.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2onrypspi.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xofabxti.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyssjof.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjnvvih.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpxtved.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xlazjcgo.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2icihysam.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2umgeyqob.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzammtz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqiblwi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wflnfsit.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkedzecp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uwatvrre.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xokuqcek.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2obkuitss.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwnllmz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgpkitq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgbltsn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2utrgaztq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gugwvodk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nsenhtlb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2urzstpet.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rzponmvr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gymmhtth.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2deamowgh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzaqklp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2huulcwes.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpofnye.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2aumdnfec.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2neljqosi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wozzcqaj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqerrtc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdjbihm.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2oznancng.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2reelrsfq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyyjzgq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgqshys.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrdinjw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wrniplom.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkjtbbi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cswdkdne.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhreiuez.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmtbxsg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2hyydetfw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdfusqh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mcygvjlv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrkdalw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yclmfutk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpiobrb.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoctpatd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuwyeua.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xepcaufx.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoqwthu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyogzff.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2csordsps.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvummoue.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmmxrci.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvcupss.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fuengoie.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzptnitt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yhisdose.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcbkqiv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2afigrfxy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tujtnkhl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eouwpdjr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgtkkan.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mzymqzjx.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhebhetr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mxszxclt.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2htizfohh.html


<!-- 参考信息 -->