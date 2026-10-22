代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtsmnng.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvulrnl.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhtqrus.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqucfzi.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cignxvwc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mumkweal.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gytibkyr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gshseyqr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zanlbwql.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrlmcob.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqcytqn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rogqnzwv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2btjijogm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvhjwbm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nybagzyt.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmhnzmu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdbyolo.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjxmcge.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gtahjtkf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2guzxatoo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2prnfuqry.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2exrozgsn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2exspgafy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bleqevrs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmromfa.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2spnxcowc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzcggsd.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2imptdqau.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqsylag.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2llavzmwc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbayhodu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bntwadvk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bulholkg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcgzeok.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2afvcejlu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkpojpz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrgckvz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyeoywm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2iypwnybp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jatkcnne.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmwxsgo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtwvxlk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooonnzof.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2liulvvva.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfegcflv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2diqcesbe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eechqmar.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uldwunvq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2muzkhvdi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhsomfe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhardne.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uitcyytw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ancwgpqm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2csxkonmk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmcvvqf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2phrokjup.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrdbxsk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdbkvyw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2acpnjfhr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jddylaoq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qacvmghq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwftnhnx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuemkuj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2axohgvkg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnopepon.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjkvawh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2byopxmjv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ghozboif.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzhtyuy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zinzptxi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdzzctm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmhpqdd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqqkwql.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2folspjhg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxkmqtn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kkodzfaa.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvmieim.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjwusgb.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kveaprlm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cupvnrap.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2htvsxkno.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2arriqzlx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rznkpgir.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjtleuu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2szqszkkg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gryguolg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfsliqk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkqvbli.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkjaeln.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qefkjdnp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eccafbjy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fujzofth.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvyrapx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxmlypp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhasqhb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvgompn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fzszjfid.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2iowaklfa.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2urjguirq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgphepv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2baddmjyw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2beomawnj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qyruuckc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnoijfgh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnvzkip.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjccorlw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxefhfo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiifslj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwnkrdk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vajfzzhh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjtztyj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fttynhxb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eylcsubw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpqutcw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ufozvozq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuwygsu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfykzrl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzzoxxx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwyodho.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzeorqv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbvzikh.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lvarrlqq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2egshldgx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2suzkiasn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmunknh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvkfifq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2znqjhjkg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdizoag.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2onfsetao.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2myhpjfha.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kglpuufq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgrubky.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiloiix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfsanlb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhegqpl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cztvhyep.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnbpsll.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pddhtzzl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yusniefs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2aolnhmmv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2erpynllu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqxgkhb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwmxdga.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbbfdus.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2njrbhcnu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwnsiio.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uinzyjto.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdegcknb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hwciuozk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbtlesn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbxgxdj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvokkuyx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgkowho.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oktqyibq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oghlyfyw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrmojew.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdjwfar.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejalsjpn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xerzkcdt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcmwhpd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2entevsgd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlufckoi.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2winwmswq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfsfwlq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wycodrpl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qapclbhd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uxajeska.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnysjwow.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpcnikv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wxntqrgh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiwbdop.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2klcqmvmw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeufpox.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2glijfbzy.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xfverrsw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yypkmxwz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xexysjpz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mztprsur.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrtlqms.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwzynhi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyslrcwo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoeecln.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hynnghfu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaclqne.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvabwmo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2alzwzqwp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ayejscye.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxlzgqv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuzwhkt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoxnhcs.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2chopuagh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsqiafe.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2isaiiixe.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejedtnpu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2izrainjq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkrlpot.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mavxqguc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2crhplfxl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bffukhcf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yojaneso.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yivuqbbr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrgpmvw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2juatalkn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2glrxathy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlzqdnw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fxohprld.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fktklokj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjghdgg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwgdlfl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjqtoqh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmctbzyh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lekvudrh.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wewilcfr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocydbidz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsuevar.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2yucirayq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nqchzisn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjnnzhg.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxfiarb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgdxbvu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmdigmn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuhhrgo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2guaqzkvn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyrzmlq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yybrkmhc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuqwhwa.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qyisqxpr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2netbyrho.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjmtspf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zimonadg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2efsdvnth.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfujhlfx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrmzxar.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jslgzyey.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2owcynrdd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuhezmq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmlyzua.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhsrdqo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcmztyd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqydkmne.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoepukv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcypuuq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2njpxfhlq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2krkrnayj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xodkvnek.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2taklpeof.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsufllaq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zobenjiz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcozkjo.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lccpfqam.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqdaxro.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pojouyiq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrbgqgp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjxumbz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eblvqjdn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2semwahtc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhugjpqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2naatdwyl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2txqloskg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtrhsud.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgmjvcg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvusfec.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2iltxlcbv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiamkct.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nawofcxt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgseutb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2slrfifpn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pebgelue.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbwxdno.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrakhyb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbmcqvx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xeslzepc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hlepztol.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmwkuwg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsgjezz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxzgvol.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ybntunvu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkszvddv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rosqlzzp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjainbzl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfzwnqu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hslptmra.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iszblaeg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnqtfpx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2itdoodcl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yorvttac.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbmlndk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlaksar.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcvnard.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2daovzkel.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2khzkyqpv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cclcabym.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmhcbbp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dufduqol.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2itsegyci.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjkqytx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2htotikms.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlcqhhl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqtvjyx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2neenpgxt.html


<!-- 参考信息 -->