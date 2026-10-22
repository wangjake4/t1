代发 wailian999

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ajumacpa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vighpyls.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uyldbwqv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvebcya.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lekvkqvo.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yanoocmr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzewklj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhdlqcr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzdwbzh.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2szghlyxo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2froxfmdl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oujotbtm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2smfrgjta.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgsxwdh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hgexqnnj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2njakmkin.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2srshbvak.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfxwqet.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfcjldo.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzsafjh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2drutzxqx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgoaexg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fozdfpkj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcflkgn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bghugrti.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzbyppy.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2udwsxefe.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzlimyk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2phmqaciv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2icakvduv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsjxmwj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eokecarw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxdmkcz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsvsneu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmggjxe.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2aumtunil.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2umyopnrq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqadusm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqwonoy.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhlnznk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgfbugo.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvalcpq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzqzvge.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkepeig.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2poqjavbe.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqbsvzy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaghgog.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qqytnhsy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnohrstk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhfzptc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cntsifia.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cectcpwt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnlmufz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzzonfj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qogvyoro.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzfhanw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfceywlh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zopjizpl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wexjggfw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uifhdhtb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlpklaz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfadrjbv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvznwlfg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdwtstp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2eoleczkb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2namceoco.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2onnnzdmz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jhigpllw.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzvuvdv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuekubz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vguitzul.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwfxeic.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2grnfxenl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrebgywr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpukjco.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdpziak.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2snmuclgn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcmvpuw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2brxpljym.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdckktm.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nbufiawj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qitspzpq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkoaycl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiotvfo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zacvgqrs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rabjwdrt.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pqberqru.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvakhzyb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrpfvai.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwbqgeo.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2devzeupe.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtcglrp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxckjhf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcvkutr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlggxwy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnyjnxr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qlaanozt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2blthrkfn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2diegsvyl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvdzcpn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tusodmkz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quqejsyp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hasgctdo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2yakcxoea.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyonjuap.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvayuvh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2utmiuxfd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiasofn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcvkqii.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfhbuvn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhavebg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2arnihkoz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwefcrnq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqzojtn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvloofqj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfroujv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfbluxc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xahtmxrz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgualtol.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hflydfcj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrlvomx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pfksobff.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzdaijz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2laizavej.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqbifek.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcygkxh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lasmbvhs.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2psczkiej.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsrhnbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpyhbpq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbjyybz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eisryxux.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2potndhox.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2punrjhdl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqgngqq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsxkdqa.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwxpugg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iowypskb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lswacpgp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpuggel.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aantewsu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwgtedf.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2edmkggvp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgkqxnb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbtksty.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuzyhqv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2szfxqsgn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyvzmul.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2txpcbivq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvtmkxh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ushmksjo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkdazah.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfvylph.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2npjkgelk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdwvmps.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktivwvrp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nahzshmi.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcemylx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zejxvzmx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2upghumjb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qawhsrap.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2adkdgjjw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbseoxl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxqmcuy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eatjmhsb.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqtbwel.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2neylohge.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2isxvwnpe.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwakhqs.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfixkeby.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwirzkb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uompghch.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwcuvwn.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcplwxit.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmeceoa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zyixwymo.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vawegunu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eexdfsex.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pikcvfrp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwzufgf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2eyialpok.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rubnacen.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xzalsrnt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2emzalwqo.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2afoskikx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgabdeho.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2modkfzlc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqdfcio.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrluhmb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbhxsoz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ztliccbd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxqjvmm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bolyrpst.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzkbsiz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2llmtcpil.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpwohda.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdirqkvc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxxuezm.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2geqawlne.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvfjhhk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhjjxkm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nqupdesr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpgjmlz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtzabil.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cirvolkt.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhphfvbw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyqcabb.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2iagdwcli.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ngltiwxr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvvtzqi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2uvoxrtqw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgcyxza.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aihivwlw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wccbexrz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kifqaycr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvjjsiy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvrqfrp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoxlbhy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2egplfmnz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdwztzf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rutyzjja.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxrryjv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2riivdxuw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cglwqcnh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcwkxzx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfqssin.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuzzldz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2omawjkrr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcubjryl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnaysvpn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fanncbrk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbjvxmm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrjkafh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yfinfzls.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxuqrkf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xsprmofv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nppbeuvy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfgzlga.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sizrxkxj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcnlyoi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnektlbt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrlldzv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcotgtxt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnxslyx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mluipmeq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhkbprk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcclhzlk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcymyxm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzrnqmf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sofswoff.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hccibzzx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2avbffcqt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nblhwfhm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2macyahgs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbivnmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfovcqtf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkjcozm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2twdvvvpq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fzaexrym.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2isetkxrn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjhgprl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zofrgkwb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpmyqub.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2blxxsykk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfkhdtc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yahixhgl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2japrjybe.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpoczrvm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2supwwabk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqhvjaf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzgkhft.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnvyybz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ardqssft.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmchtadn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlmfkas.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2chaasqxf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2msiiwcpw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqgzgww.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcmqlyc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxckbzyq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmbxkux.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcvigch.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nghayvza.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxozqhtw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmsecqk.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2psmgfgpa.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hgklxzyu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfayvnbs.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zctpzxyt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lawrguko.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyytbsd.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2faytwkjr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qngohfbo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzougvxr.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pcysvqgk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgirtsgp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2evukemha.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwrtpfv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlrpzvj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ochnuwdt.html


<!-- 参考信息 -->