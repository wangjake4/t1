代发 wailian999

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbptrubm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqbmaqw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsmzfel.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhriclg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lmoeyywb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiwcfjw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cssqdept.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vabzdfvd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xizcacmq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2pynvdvpf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2emmeuqcw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hiekqbxn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2eoecwbty.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxzelrb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfcsrxs.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2miloklcq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgxamna.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhensgj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2voyljidh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2drmuuexz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rgiweuof.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmreibf.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2crebboyi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiljnhe.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2phmvnuyj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpxeumy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uctimfbk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ignnohdr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lafhruzt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2foavjcha.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjmzfjr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbsazjg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bejgojia.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hccphwew.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2idlmickm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kdiyojpa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvlyunb.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnpiwaz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzofeqiz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2emwyvxwf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2sigfyxre.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mxofptll.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfppnpa.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrcdzwy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbavjad.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2spyzvuiy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2khkdyioj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeifozd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdxblif.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lllwpkwz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrlvjga.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkbrlns.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zumswwka.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2subenrwv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxjsjax.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qmabckfs.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mwonzovs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvodefoi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tvazbydr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqwemmx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2czfvfori.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqmifgr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfowwqo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmnuzzt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xllannbk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsolyrq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2eezxnwbt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aydwosgf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnrrxgt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2icbbvogm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2naswabyj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqbxojv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqajgwz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2orgtuhnz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gckgeyst.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2znawynqd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2flbpcdwv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvcufzd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnerrcki.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2uiclznnh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2sphawora.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2acijxpdm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qoykaiij.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpkrelm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xprizgli.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iekkjqpu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmrcmio.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmhwxbi.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rknlmdsu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2viohhoci.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tutrkqho.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqzqdbd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vslcsuog.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynypvtlg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxeytqn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkbwccu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgeghag.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqlehcq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxpgdud.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2uschawpy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cydupsfv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxtwkap.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bepoohkf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjahvyo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnoddao.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mgazoypx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbthpxz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnrzayb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upedyxap.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2plvatrpq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccioojjb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2owfrtrsz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2quzuwdef.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzdypbx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdppxeau.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eszhykdp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjlyngf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unbneqdv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqzhdaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpienvh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxbdfan.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxkrfkk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsunogg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2thghscmy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnvanim.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgltonul.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnqixyr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hklqmiqb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2skhacqsi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2iluqqxiu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sxltpkng.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xchxfhgo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzewtsw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwojnyqm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sveesaxj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmviubyq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2siwfepze.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrivhwcw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpxjezy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2azwngcju.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2drhifxov.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqmkjry.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2exbdagoi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqcukch.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgmjmqx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrihmjk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xferhbae.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpynzrfl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgprmhv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2revblndg.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxlcruf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqiibbho.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdiqxkou.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrtpmxm.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bennfion.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbustdld.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkuwzaz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlitrmho.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sewyrazu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqwtden.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bscxkrij.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uujbvpvi.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jiedigfh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2apbjyksp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvxvlhd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2icxvdrnn.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2sayeocqr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zchdasqq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzbfssm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvhewwg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnkfhee.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzfnqfu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdtnnaf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2onwraxdg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xkykxtec.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2yplxpiyb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kisalvja.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvhwaml.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfoounq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jggexbbh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwmzmwt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2neraqufg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfnodst.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zeobvafj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpcdxsr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqpfunz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfzvtos.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdwzfun.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2nyejnaom.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2arrvxhic.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyilghuc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbnuwbc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fxppjytv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsqeqww.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmtmjxa.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2pttpeecp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lywwkebh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2prwgprgp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kabuyllt.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bsemiezb.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpzpyuv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xxouxllf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2parqltjf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpsglqj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbygirt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmaykmj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jboiixya.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqkrvxw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yxofcgje.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwoejoid.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xoslreit.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhozeqa.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xdneegym.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuokzhw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2liyugnuk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2udpnmgdg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbzuhqs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cteebdap.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdptutr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpjtfjl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuplunba.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qfycbecp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmnjwie.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cczedpaq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2orqitwdd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwtciyj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgldqyi.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wjovcsjn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxeomyb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uitnywov.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhlzchn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ophbueqe.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2seuyojfq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxaprlg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieugrnhi.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iaewnmdh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjpetot.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wetnnnmn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwepfiuh.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2luoqtxgk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwttaam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edgwdvaa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2shpeyngl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dymfhhxm.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2anemzmmb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrleheq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzykrai.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uinwxojq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xogiozps.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2afuacmha.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2reiumzrv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lbemnign.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2dbghnksc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdszvzsz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfpcfai.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeuldst.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2haxvjedq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2owelktav.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2apkdwyij.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfczibc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2yltlutwp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipihyadn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxdguui.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoitlee.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtnqxtp.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvidigqg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ojenbtly.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoidigy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuwzihv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzwvncl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ekexbhxf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcesxjqk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxnwuoe.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvpckxj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsybmsp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2inmpdpnw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yqoxqzxg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvmheuy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oeafoegt.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqykesyh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ytinxvxn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ombwxxtt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaegpbn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2egrwusox.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2oovoxqby.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjwbwic.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gemogiiy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipitjroa.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaytfxb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2esflenmd.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbylpmy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmfxwod.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwjegsb.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgoluir.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxkqywy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjedhmu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkzakuo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgnrpix.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2isofptfp.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqefxem.html


<!-- 参考信息 -->