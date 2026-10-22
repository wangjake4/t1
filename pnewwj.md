代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zvahookp.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fovelboq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nouupgrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oekjlijo.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwhcvgx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcnpfza.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vudulbbr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgexkyr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqokdwux.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmldtwp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oglnryao.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2guqtfnaz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzusutwd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdizmfo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2newegecx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sddeqmhh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmblkvia.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uaglcmqb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxatklo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqxfmpp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2aofvgkiy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqpogmr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqctmqkk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpjupnn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeuthve.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kckwjvbw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhwonvs.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2okpnozic.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyrwdiy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vklylhcm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2etitxlne.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cniuuhsc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsvkphw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2curuijyo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsvazdz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2umyvurwm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoykecv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcmzrwl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkyvqnj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwgphln.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrzmcsh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2twjrweth.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqhnuld.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrcolpr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2okwjrqac.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxwmyem.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgeubrv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxieeqo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpomyqv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2courkcfx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2odaxvjok.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iykaracq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvbbuqc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoglrxm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrlgiyv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pevanjwq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2crukwycp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kjccaisy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdtlpji.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwrhphg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhqyyen.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wijyukgt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2znatbslc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjgpabz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2stswxojk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bppnqnie.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2czyduijw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzsxebo.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtqxeqw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2seawkfar.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vscrokzu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2orxaglqs.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzlxsvu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwpjdps.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aifxwmke.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mocnqvmm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fslgjudt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xitqleal.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzxzmxr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgebsrwn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2csmtbbol.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2atspujvd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lupzauzp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwlomkh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcifcwj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqngnno.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rduxnloe.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oihqksah.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dzotuddr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mntdwpnq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2shvwapjm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwfkuff.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2polpvzvb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgzzekr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnrbvcl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wsddfqog.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxaafih.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2udvuoosi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpwsich.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpblikl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuibplm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgxuyjz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoizoiz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqohwsvr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gncgodoh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hswnjfne.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2msfmetxu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjttilj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2edbrvpjf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxjyxbx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkrpfhk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2phyhgijt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhozephf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpktncu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyobljh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2njpgdvie.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hysugpya.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2klqasqah.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgpftft.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nejqazpz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yidbunxg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrhmgpf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2csyojpth.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xmshmqqx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjhavbr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqqnoea.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2owzbkgtg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfcosua.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcsvkdi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsacnfq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeurtor.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbhhkxl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jtotaaph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrzrjpm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2niytsnrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgfvrun.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wliecnoz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbhkzwh.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ginlewph.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rugrglqd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qbggltzu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgsrdrh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyotmpf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyywqdv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lelprzrb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdefgrb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfsyhqc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyrhvfb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtjwroq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwydvqha.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2aonbiwsy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2euqjqdnt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtbphqq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzrsxql.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfjghoo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvqahng.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmzbhew.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtpdmpl.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkzmzlb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lobowwhj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmpmkip.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnxjsne.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2appjvbvf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeqifuc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrpujve.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyezbjus.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yayefywh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjlucsx.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kzywkgny.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yimsbgnh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pidnyykd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbanlveg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkwfqbo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxkdhep.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2crihbhwa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gagxgdeb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2evreimkq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyfwmfa.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2glgdkqul.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqgekgw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2acrupkrh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2egziebwp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ietqihbl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjfbndl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tycbujjk.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2edcpczdn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vmatnrde.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcimcbdg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsbggqd.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrsupyz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjxbwlu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvdgilm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvftmgg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jduwfvvk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdrhgmn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwenlhp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wgujdeiu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2icaocbqc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfkukzr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnvumrn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2atxohuqn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbzyobe.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vubotgdd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgwgtel.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgujuuz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtpcvcu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyatiuh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gqclranl.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qkthrjcw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhilmnl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnddgnti.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2eanghthb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zgomujfv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcusclf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrbrjfz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2okbrfvvz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2djgdvqoe.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uaefvjul.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuzjpch.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2utmnzexa.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkuwnkd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzrsvtv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aridjhxe.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtluqzru.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sozzdfgc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eegddyan.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2csvhshnq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcrnbsz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ljndjjew.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqhfobk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ggenpblr.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkpnapg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvemucpn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrvitcd.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdrowrb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxluany.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2habbrgmw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnpmwwc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zivtjxfu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gkksafaq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mopwiyfu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2irucbpmu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwnxkhe.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kshqkerf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxmpuba.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hflictbo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yercmyhk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwahukr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpwhjsg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xjexflku.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yolcwjso.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhbenhy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2uaaeciul.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2smzkjkde.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2utzprcjl.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2yokvljya.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpbmzmv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iszjojbj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuceapd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmtjest.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqybbiy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zcebupjk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuszzcp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsimbkg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zrndicyf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfohyhkv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkccmiy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzcskdp.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmeljix.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2agtohjjs.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyjgqqz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwaycwb.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkvpqcj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzqspgj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmjlhma.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvhkmci.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyadhkg.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2thutwcap.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkhacwe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmcfgcc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcgetlr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbynytq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfbiupc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzaunmv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzbjbkq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdmgqzk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2txckotre.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxqhovx.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwrejnz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwrxbhi.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvxrtwa.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2kodyluor.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qwufduwi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2oykrhsyf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvngvcc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lddoaclv.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzhrops.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlirqzh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rwophygl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsrepcp.html


<!-- 参考信息 -->