代发 wailian999

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2blmvsgbc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxdqzxc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tsblwjjr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxjzecm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaezkfy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2atgdoosj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bysvqatj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvfrgwj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lujwzgwh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwnljur.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrzisei.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jttxexka.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zifyhtzj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkwfshb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsxwxbl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztozwuot.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhopwqww.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwmhxfd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2baedxkjw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2brzdqygi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwwmsbb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhmueyr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvfknfn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoprgtb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rapmtsbd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aotztnzz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjeajoj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgbmofa.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rclkzagh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nxufgumu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oitspgek.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2azjngdie.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lulmdupb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xpctbjzn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsaugmz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlardyw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2utpakguv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvklukz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfjluac.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vaudovqe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hayxmfyn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2moruzvog.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hteogsgo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsksgvk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lenetktj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpqhael.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpprehx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwavvkd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtneuos.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpebopes.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoibenld.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mltsclqn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuhwfww.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfmcbkx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zcapydev.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpgtqxg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdddlpk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twualwsc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cukbiwwn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmbsypw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2deubwevl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyhajwm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hasgewmn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxahbnka.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pezwoxzp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgnttsd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cejaewpd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfajnxb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2byiotqmf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qximtbdv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2togdcska.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jetyjvup.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmkpobv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2saokwmpr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuyqqks.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzufemh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkdydkd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iunwvxho.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2envssmkl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2etqctejt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxkjdhu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsevqkh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxygkws.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfljkyg.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsryhpx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjznbwi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyyahjn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jstfyghs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oworcewm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrpmioc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ysslfufy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqydqzhl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2btvorogb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgefzmxf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxdxuvs.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2myiikpuv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tutcrrxl.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ielpqgdt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdophoy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsonhkk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdjjmuf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2djawxttb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2opyttaju.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2omhzotvs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2srsyretk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqztmte.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nowurabr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2atnpwplt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpqauvn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2efszhucq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2smctxwpd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeshidp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2grilmoeq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2plqgqzyf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pijbcevy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhjfkdw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpbazoa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwyeeuq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjcyuzf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxaujmu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkgwyby.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mreoofgt.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsgysgq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnmfkfb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hylqrluh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eunknrfo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jlklevzn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgqjzbj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tujdicdi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiifmvn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmwvtoe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfnvugh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xikyzoox.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgtkngm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hkksrath.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpanvuct.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsejssbk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2akpjupao.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeuuiia.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvvafdg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hchelxnw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2arlokrzr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yaeuafhj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdqouop.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgxlutn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggartbos.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pshuuele.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfaeiid.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqlvvhh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrlevig.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmvspbb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jssyiwvq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pbunntzu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gnczjnkv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lymbxoun.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwhfmvl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaiytev.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfephniu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zouoreso.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyojjten.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfvigct.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2otbdaali.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlbtohi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rhontqyn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkrtgxy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaiidsx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjslsuh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsldimn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkkkrzw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2feqyvqcq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ioswqgyh.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiieezw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ooshsedo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrkofyf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcyekfs.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwmiryh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdnktty.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnryxfo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jexnrdmt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiurgqgo.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2smdppkvm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrtkvmt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yndqaywm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2edldmqpr.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xonphren.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gbekwspb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2twpqftoo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qauphlav.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dszxdsbr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdnukjv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccepywfc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2eszekmpd.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvwywxc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkouefoz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrykqri.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2akjjbhzo.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmdyfmq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkrabcc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qncwvuam.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2iihhnucl.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jxizvvrl.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rynmbtgm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcjujtn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvctzyvz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfqrbqr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpfkvvh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqhyori.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2haaehndu.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmfystb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brgzoubd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqsmjge.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnkdlxj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzkfzwm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htgfvgzm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xnygpbgi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kslmxxsy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnencpg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2katoyaoe.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmppqfq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvjqixe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvntyxrj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hppzmmdd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2viucxbim.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzhkpki.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnqsbxl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2owwkiban.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xaomzjeq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfsqdfy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2anksysfh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpoptty.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjguwln.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2aouculnc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rctwmisv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnnuxmq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlomhhs.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tgovtoax.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lishwfcw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cogqjuli.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2taodvcxw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2aefjaqva.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeiuqtl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdzrvhq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhndige.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exgizqvx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2emurfugg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrfcsho.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvcaqje.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tlumxjvc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyehsnj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdqicfp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjrleua.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pecmjbtp.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zmelmnlf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxaqmlv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvulowr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ryupseoq.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dacbntpa.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzrcpld.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhdegef.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnnwqlv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qngveejg.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbfvtgt.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqvsxax.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2tthuyttk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gmumhugj.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nffyefed.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ggofwekn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfltsfv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ceezarlv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmewpxqg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hvoieijt.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxljinz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2habywvju.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2niqwemah.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2shzfuzqc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2utyjipap.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjhftki.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnbcfoa.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvhkght.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvapxew.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfooqbx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqnoftc.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkqyztu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fixnbgyu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hxemjaby.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2szflrnah.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mwforunc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2iltzjczh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ksglfsnm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bctfugzy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2otyiamon.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2skmqhtle.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ujctnukx.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmyfanh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2elooamok.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2raaeuvcy.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2llqqswwl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbqryea.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2evpmswwb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoepaoi.html


<!-- 参考信息 -->