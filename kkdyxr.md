代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwoockce.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wmndhlaz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcelocn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2oysfsnah.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxboala.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2iuobcrif.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzvijoz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfgyhsd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpmzkdh.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpiiamj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hupuphfx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqhzxcg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wifrpvim.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzsydqx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwuwzwg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzasavi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2szlgklsz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjqqlkp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmegcsec.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkzsfyk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pntviedx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dudkramu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhxwzao.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkzqvca.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsedersx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nuttzibs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jifjimvt.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yocbzxfu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dijhudns.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ignoosnn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rvadksvm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2fwohnrmz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eokukbwx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2snfvnxoq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejozumrm.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2itlsjenj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2trlortlb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gaycvegv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnzyxrh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2akzluqsc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wighlemn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ftasarpc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsklcnb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wpagyksq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2hehwnlvf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbguolf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtreyadu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjgilwt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2anfhtxbg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2svulyfvz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2llmutfxp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gygqkdtb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gchrsdqz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2baltpmhg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpqczbj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoofahh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjytgvl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtzvlbc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxbjlot.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ndeskpas.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rkivyfek.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dysgemij.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdoeker.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kfostrdr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyshybb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvulzbop.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sixgmucu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpphvyz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwjtane.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvmflgi.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cankhkna.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awomvkwn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqbpxca.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhqdrko.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvtpdpr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukljbvii.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcwddzs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwzqjkr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ulezyfke.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uwojjyje.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xibdqayu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2sonhsiai.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2czlthzpx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsflotxe.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqrndll.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbxlwyn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzngolvw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2quigfntl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrjxyfh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhiajfu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxyrrdb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvfyxvv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2chfyuqgo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2udrtpfre.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kyniatvv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjqkmrx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2poprgnbg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqitqlss.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tdepsybe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bosrlfsv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tchwxjvx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iicipisn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nvogjyki.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyguplg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzubcyor.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lcthacpf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsxwqef.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvuczlg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlvsglt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxejubb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyilrakd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2morycflz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cstvrtro.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vjetquvf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmszibpq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2teelxria.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuefpvi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oybkdkro.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ravvgogv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2akyfvysr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvblsfl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2apcvivjt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzgzwly.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nddpylhi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2drypwaml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhekgjn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgimdop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdhwtmv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcjrqml.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtfvtrk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlhhkfj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pfztyvdz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxkqnxg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2scpbdofc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jtaxnxzy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkjfdax.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfjzwps.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cwokcvtn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tymaqtpl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vepfjhrd.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pokjzuod.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xepyerhs.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2laoykflm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2svtfmpik.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2shkbbudv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnuxvfu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqxzimw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzworbjk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bexkwuid.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzudkepj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jzekdbsd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxrfaha.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pagkerig.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyuzkvp.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlvtebv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnacqdnt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2eazxmsku.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhbilsy.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zloqvucg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcqcqgi.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qljhbyto.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpbxknj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyqjazv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxiyyuz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2umlbsrmw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2upzzvhcy.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dhenybwa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdejfrrc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpdrrzt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2edwysosa.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ppopeimo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjrefdx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjhxspd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hflmwkhn.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhoktbb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezehlodi.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2chmtqypo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2crqinueq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsrkylp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrxkllg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hkquqxwn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xasrxlbm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iomldnkf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrnqzfs.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hehanmih.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsalises.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qusmqrnd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mckeyfrj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kreaolie.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cktogego.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxhqmif.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhtymud.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqktijob.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2aiirvejm.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2htfvqqdz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqkjlcl.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2drbneisk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2umwrhmgi.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubswjbxt.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2aglhkivd.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zivcpubf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwendiu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2haljrwkc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mlaiayim.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfyljgo.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zajmttjx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2weifoucs.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tojrmkuq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kxybsrwn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqnkrky.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2orhyimnc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrxcztg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxempki.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufurgprd.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vezmpfhj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrqzzio.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcbslop.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qundsscz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2esshfjoy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfofcmd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cohzyzfx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgkzekb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qkncnsng.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhfocrw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2djcfqctq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uenwkjwq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypabafrl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjeredh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxyjofk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhrwomb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmywvzie.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbigius.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmhkcus.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rosgzvxj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdjasyn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2neudyehv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2prssrjyv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2abdytnys.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooblctuz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtnnlyp.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmifxeuq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2imnylolf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtztwklh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2khwpjudu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bprlsqzi.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyuipfk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksaubmwu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmvoqjg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmamteg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlrlnho.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdbhqso.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuonsov.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmyihtu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2huvntohi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2prbrvgbo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfichhq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlzixme.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkjosfx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2picjaoog.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2haccleac.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2puglipbx.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtidfzw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcxaqou.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjzuabp.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgcslxs.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2evpijmov.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2krwrcvom.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyorzsg.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbworzb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsofpmls.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqgrdla.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kcavruat.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fovgzgdy.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkycljn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyertvz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxbqcnt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfntuoa.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwwdgrs.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbdritd.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pabzemcn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2txadhdsr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpguuadf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtgbypb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzpwxta.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2imsqikit.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggljgpfz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qixzbdrz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwghzkz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbcffmp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2loltezpb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqyzpfu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdnmrgg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpmpgzk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2znoorkfl.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pjblntwg.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2eemwxgtr.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2paclqgvu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvmarhb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxjntgr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cihoycjn.html


<!-- 参考信息 -->