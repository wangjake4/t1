代发 wailian999

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wesrzicj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ffeolxaz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gsomsadr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeluikm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqcmltq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhyfexu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2afuyxttw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2uglpkasi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2evkgvppv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nykknimk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2aixddlzw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kymdeley.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2oopjratz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhqtxah.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpfbbof.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnotazp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2verdgmsg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpbfsgv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwcuqjj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hlilkhor.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkzrjkh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2esihesmi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcbkgxr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uagthqgg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxoeibc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wynawmmd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzoebbkb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtdduqt.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhlhyqx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhrboeh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2czhbdzwi.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjtfzpy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2viracmyg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxnyrne.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwekztft.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gjewswke.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrthrgt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwufpca.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrqjhzq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kytzabal.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zporwcuz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdgkekl.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2yetnfooh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnyibhv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yykwvtrl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2grlbcpwc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2goqxvwlf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mpltgroh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoecfmrx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2itfhieet.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvfkcij.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzzdoep.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ehujarmj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fspglouc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2piordpxy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlkboqh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjvfdyz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzbnfoj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnpkevp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwgcfvs.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2umdgbxtd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqlktuy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qizozlxs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twksbjjm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlwzxmi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2orcijkog.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgfykgy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkdpkxl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nykavihl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgatevfs.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcrqsfe.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdbfvto.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lffszvza.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwbkbzn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cbchhfdn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zumsbbgo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmjkbrg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uekdgrzn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdjoeze.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvruqhp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkdijjc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpmbtln.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmpdtar.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oydamqum.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjigkxz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fedqxvlm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zpheseso.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2riwyhlqe.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2epxcousa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuawfhjb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbspakk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjghepki.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hakggnja.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmdvwmh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2acurdebf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwhlmsz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cevtniem.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhmbaiv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrjtzwa.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcdyxsc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaprsxr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2mhveqzkg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2annpuqem.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhxotrv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbftqaue.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vchmcvkv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2izsewvhs.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmgesvn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pupdmfgm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkaxwqr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruglvhzf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzhikfq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbwzqii.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrwcgcc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2shcyjxmy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wfelthyz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2soycbube.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2efshrtef.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktanoqaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drmkjnsx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fefstdso.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2abhdfvyk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuovsgp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsllfzy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrbtitr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mexgmtzt.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ogklilyc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kocitywi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkpyjaf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsghioh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhkvqkd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yswclcgo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zoplwika.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqurnyx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2slripdoo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgurrtjy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkszfoyx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfpjlnh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2owbxxrvg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfgwvlr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fatuksjr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gugiblzn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2urqnlugh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2csxjgyud.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2txwdujkm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuyfxzd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rprynmzf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dskcrnzp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2omalukqm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziehvagn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2edyozjjk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbarxurf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2drnrbkzi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cswtjfno.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2geyywzpf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2idrhnort.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjtmyqv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuapwdl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rapgjjti.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhvfhxf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyfagtj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2okymbekh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgrjnsb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuvqqur.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrwaepo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjlomys.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjusmkw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkssoss.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jvddmiva.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cllbqrjn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdcqpmw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hurkmmdj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjaafii.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfpxkpd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lsumwrke.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fufhydpk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pllgabqb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsxgewn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yplzxmjj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aerlzpyb.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nxooyddz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjvdzzr.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nubssxtw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzkhbjt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjopxly.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtexlfs.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2araovrfx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2euyvelzv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mamxgbll.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rtehjoep.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxemjsto.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcghtlx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqhmgvl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehocorfs.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qgebyirs.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mrviprkm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsakwpx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnanqcoe.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxnghtg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rebyimvd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqphrem.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xshohxjv.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2otvrgugs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmroksvi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ftripqex.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wksgcmph.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2btokkjgm.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atkpqejr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2atedjyvu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blbyykef.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdjcjzg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyxoalv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyepoco.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psaxzwek.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxkfgyx.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2affgkkdb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aololjxj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opwghhbx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnukqvpu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2itjmdwwc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yekwosoy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkmgbhu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyummwcr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmlvoii.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtpqziq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ikekmjap.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtrsqfn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2raqtvpmx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2npddfcyz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrzrdzv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuglwtvo.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcbiynk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qveljidy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jysissrl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxihpfpl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dakqdgxz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrqgpfo.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ichzoqor.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxttfgoj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpleyfa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2caebqoeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkzpogq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtvtafb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itmdvzih.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxcemhx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnrlrnq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcwiggf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsswwqw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2abdwshbh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlhxwuh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2taopgues.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ocodnjei.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2amlvomqd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2aedvrlsp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpxjafk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2smfqvxks.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2utrjecjq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlsvbfm.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjflojx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2sjopnxwb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbpxttc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkhjmku.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fknygwlr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2yodnfekq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrzhpil.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fadocivb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2awcmyusu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgafpsqm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqwdgmj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2waemnssk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jtychkdh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzbbwxx.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jkplmptr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdlkmii.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2egitzpig.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mncvhvwy.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhmkcgi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiasbdpe.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kehbbwfj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgiorjg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2upbkrqjz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuugayje.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbxfqpc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdlgbur.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2tccfwukn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbwwltn.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jacdwxzb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmzcjul.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqdnypi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2aqamhuan.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvfihaq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uloqhjel.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmpwsqc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcqhcae.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2djvykwco.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tscynspx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vqeiqmrp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvbppkn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2rctmfmey.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jkatotid.html


<!-- 参考信息 -->