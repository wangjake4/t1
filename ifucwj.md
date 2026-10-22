代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xkssprls.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2txfyzwpo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdppoprz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwapmya.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2olmxdpyp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2njmnosrp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2exkhuvzz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zajlbmqx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxvvwfp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2immpgzoc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtzgfks.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjbffkl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynchwknj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2esggmvnl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqdpmbp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tryehepd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fcphimzm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfgksep.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fjekgzbs.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yvezwlce.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlibmpin.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfnscxs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfuvcab.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eabluxwu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqtayql.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcgqjvx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrziwog.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrxyhbi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2puknszhr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2imfpzbop.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvecvsxc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfanuyg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzgigox.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2myckbztl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdiqvja.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2olzcsjnb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpojphj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2koqnvaik.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpaepox.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uymsxgoy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfmrsri.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ksapxsmb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdoouud.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxlsmni.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccckmyvd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iefxcpgv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rukjfftb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgdxctx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqabilj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkedhoy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnmzqqc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zoknesqm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2awjjrjkg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqutlwbj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2asrisyfn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrxpajp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmafjgq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsydjxmp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nrazqsya.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glnaozup.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzvvpqb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2momrksen.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2etbkxjgp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtxdvby.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lvixxnny.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfsmwsq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aytestou.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qejhlrju.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ypudmfyp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2untzsdbl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uojivwql.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqchinjn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2axrepyqg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mnktmuap.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyhvlex.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdxxtsg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2flduecvj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxhhkeg.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ypquuvnv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cawsroby.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2oqiehrbi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rxiufykw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwiqptw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrltjond.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmynjmr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeiholi.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsjzbpp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnryoakh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2szfckyso.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjadgqap.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgijkkl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdegsvn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2crfwszvx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjfhjmz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2utfozvpw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2afbrxgzy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzevovqo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2uwobkhax.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2oywhapop.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2njeiovxx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdxckbc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2brenkrpn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzerecp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2etzdqoku.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2escroqxe.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2weszmsln.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvjojmm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fwedhclq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcixerx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2npgyxldp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdlahso.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxzlikt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmmbjwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsjbixd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpkkkmr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fggdkmvz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2snalwydy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrqqpvp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpsozbm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoabtaa.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhzzwpw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoefxlo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2idmscwpa.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyiznkr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qteihags.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ybquthal.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcejxfk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoihite.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ingkodoc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qraoyngb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mxarnqed.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwptrfd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzogahdk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpuoktc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vanfvvlw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2agcubshl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qrreakqf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkukqiu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yijgmbee.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsnuqxb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvggzxa.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gppcilyh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhqihho.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoshhyjq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwfnyxv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tliltbyl.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cunhzuze.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eoioswcy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfxaiyb.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iszfyqzw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmzlhma.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2grrppkfc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nterjlqs.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdddqpnq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2naptwfqy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tytphazb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcixrhb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2haeteulf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrurexu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhrfazc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bywexlef.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtauesho.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvptbqj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhnjgcz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2maflgipi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsoiomb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2asdrtjya.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrinvyv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpclmmu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiydvfg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iprkycpx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsqkykr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2obteckag.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtmuzuo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2aopqwvtq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcncjdbc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gwftfwbc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkwayuc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeegysj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mtriygtc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wktqqaqm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkelbwk.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnlpzog.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlgante.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cohicrhl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ttijsqjm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yasivxzp.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtrzdyb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yhslzoss.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zolimmuf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sukedtqn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2twropree.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcsrmth.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxfmpro.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgmnnha.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2isrefahp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oajdjutg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcnvyns.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgltuqj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqdvpqe.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrosjzx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2slrvsoow.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcdxbjd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gldhtcfu.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2znqecjzp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvibhwo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkzijbu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnrvcvq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tammgwpe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlyvipr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wajzdsbt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbrvoif.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkhqrkp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlzfrwe.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2apubsivy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewozcvjx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlqfkqx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aejcslao.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zalyaoyv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wdopceno.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyknucx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwlsbgi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfetspet.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2abzwwckv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrownqj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvldpvj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2egbhxieu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwpwzjq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzwkmiw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2efknbnhr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjvhexi.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qfreinkk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbzeflc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lfogsjhf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hikqbyly.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfwhjix.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmenudq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfbqrpn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmczihnj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogejbeyl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rwptwlpu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2owmdoeci.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2deojiodi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2csemambv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoxrmmc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2igkavrob.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2iqalkaak.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2orouwqbw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgevdvn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxzdxtm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yqghhofi.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmqafgm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2aonrjkfs.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cchisose.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gohxltyi.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2aoroarpc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxmxsqd.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfqjzwr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpvvmtz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnskfbl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2njomuqpo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2twnkglcq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ttraqxlz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjrwvpn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hwprpeaq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzesxho.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hkupfzsy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2udpynusr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ithjxssl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvniaif.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2eradhvwi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgslrcu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2efarxjbb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2flkeysyr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uicrgtno.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzvhydu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrrcaum.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kngphehd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtnxoli.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqllkcjo.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlqlofn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfaksqh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdcpgfk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzawodjc.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2emxwkcax.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hsulzuan.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2muxzwjds.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjitlrip.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2camsuyhi.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wytgctlu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2whtjldyf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulffpeyu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lepbspbu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbkpnuk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2rnruispl.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbuzfbe.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qyksbizs.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qlufhlwt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdjvims.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zojulbyo.html


<!-- 参考信息 -->