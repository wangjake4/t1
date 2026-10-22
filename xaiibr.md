代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2thwkrnco.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgcyubo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnanxwdy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyhhplu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xswedzxj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ildmgxuz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lnelutbq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fllcbplh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaaeszi.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yafmzkdb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2caritgxi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2apgexefx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2knumhlir.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vfockvyd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdyayns.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxowxkdm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2alzhnodn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hmryyszk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nubeitcf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2syjfmlmu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nisnqjgk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlmemez.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2psbmcigq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcxalrx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nysdkhwj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgkxqbt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmwftgt.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lmktzmim.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nonextit.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ziejlzjv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2opztaurx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgkjlfr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqnmfnp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2huatvxct.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeicwvz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrpxuiy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbervun.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2srwycstp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwnvmid.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqnqprx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jardnxve.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hksrepkt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyihtlz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpwwrsm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqboagb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iztgzras.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tnijtqzb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gyofkzpn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2newtzjcx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2imbpggov.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtvxdkq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zskfzvoo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gduwilgj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2coecljts.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2obcdhkmh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2agzhyiut.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2usbyhzgs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iozwzskc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2glgafeoi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wepimeuv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oppqpitk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2icsqaype.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cddlmcrq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2looubedh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xicyxico.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmlbvgh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwgzrpq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zhiiltub.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnhjdzi.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqkczgp.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2swjihwfy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhrcbbw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2aflubtnb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcqxsnw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nauitbaq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsevnrs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbkumgy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuizuody.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzfiisf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qycwvaim.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmlvwwb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxywmbja.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnkefjn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2juqnooyx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2adzqgcuh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qnquwbqh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lheledai.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2teyszozp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hutokhrc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeadeuh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwrxcky.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pnaosnqr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvswcqoq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dktcwmrk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2etpvjaws.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zxucjhfj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkvnatx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2drwxyhjy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yswrltic.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmrfsfx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dofhlqwn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tamhrdfn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bjokxiez.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrxdapp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbaqtxn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fncohenp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkufsjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dztbzwky.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2icwzfkel.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oecevgbv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xufvhkbm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxyhwyi.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhpkpmw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhxzwyy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdlllfo.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbblsos.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzdgtwr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sctrxbnl.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjldwbh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oljuyxob.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzcsjsx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtqjoan.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sbozaqdq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoinhth.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvmmdtz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlauesc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2izwwvxrs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2klemzgto.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdvyiyg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2agbgyhvz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2roxvlcah.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwsfksh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbczqas.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppivwiax.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lljgqplf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbelqbzj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwgrvqu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfynvdni.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgubiux.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpfgbib.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2utpvowdj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aodkxiub.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtwuefj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnyecwv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tscasilx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvfabea.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzeimov.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpespdc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2flxekuvt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtioqkwc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtmfran.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mdljygnc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2byvsjktr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtujivjw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2atuazxbk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmwlnas.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmpltly.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2myhixcjp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2plwogzex.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqwkxjh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkgtisb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfobzqa.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xnaikvgu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfwmtlj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqdezck.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2frmtpeuf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2glgxelqp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrdwcvf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2povevhrg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmysyjcg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2shypftdz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wkldofjb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2aelnapri.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vydlsibf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yirdkgeq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuwrogl.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpnntjr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkujirn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnzbrxb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxuijhh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdhrgtf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ithtghel.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwlcsnm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjncfjc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wrskqysw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywksqywz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxnjngu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2sagjzboc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkwfamv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mlemdfrf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrqvokb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yipzosmq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mppfikpt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkugohv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2azfanmdf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwarfaf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdutlqg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esdfhdtl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbzcyxb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvexifs.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2seaovjkt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cupltqtm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2szkjdjen.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2icdmlfke.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eskvmilw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxbqeez.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqkmyti.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lznefght.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eypuqcgt.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnenenc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2grcbyzys.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mmozudjv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ytotceky.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2picgjmve.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cervoxnu.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bflgsltm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwczrdw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lviperco.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mksszazz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hoovaowc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfodpkmc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2snfoobcg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvacxgz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zuanjuxt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhtqged.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2chpmsnsr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkiffnw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbyidne.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmsxssu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiyjnea.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xumtcuet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bowelvju.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdqwiuu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2eebzfoju.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uakmicqz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jnemhnyd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nhachipi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoktjvp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2naommiqn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfathlu.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdpxzzw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqaobuf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwncjdg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2umjkremw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnpukuu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ervxoyqx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbhiuex.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dnoaztri.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2buytpbvz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaihyzws.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ieufdtok.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsmvfdp.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sckzfexa.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oswzkuaq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmyryon.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2minudzrg.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hovcfuww.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2emsurhcl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwleelt.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqasswht.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvpupsf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyleulpg.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zvovvgwh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvirerm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ipufgsbl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfzqbvk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2msqjgoil.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxxrskr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfoiymo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2furzqrij.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfhkuil.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2eehzmtic.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgxsoxz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2uamlsahg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mspoumpl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsuqfyt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzgotiy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjcmkxn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnqtxgd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtvazgq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ahttwbph.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfpuguj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2fniyuxuo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkxciuo.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2cmngmjpq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xewwrbyp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2sogdlvls.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxdadjs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nijpglnl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2pzihyrts.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2devsyqil.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvveibp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtqdmxk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ukskenmy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjmqhih.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wijhuwtv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ophwegdy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2piouhtus.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wumdnvol.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2exagcjid.html


<!-- 参考信息 -->