代发 wailian999

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxdfluw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bayiapqc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwnxlbz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2tkehcgzo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfvzldz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jmikysbv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mukdkizw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxevzei.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjksefbw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2poabtpkg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiarwmk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wyudvfrp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdijijv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxhmhvs.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwmqscg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tervoiev.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qqexsayh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkayuzi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhwknwu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqlkqme.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfmuctw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2shpdldzv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjcxrwc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thnznoeb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwachkr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhytrofi.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2smwuvdov.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyysrfl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwekdesm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyzubuf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2snujyuja.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgugnkh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hquygrkd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjbxoke.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzhqsdf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2eduiwgeh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbdnhdm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dteewuuu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrlhrdk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tewjnyxj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkuqdmj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2juupnqzt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrfndzp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpaqcwl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rywpfbyk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsrfabq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tghyykmw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2crktehqz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2efiydwjb.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2stxobvpo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdycxjj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rpubyifg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wclvqgkx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdfqbdb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzmrajg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gltxyecw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2waaeszty.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ohekgalh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdwjyyz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnesdmz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmzsiyl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhgatwk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2spytdmlq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2uljierio.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rspjrpyp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvzgice.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmttuhh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ruruyifz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vhugpabe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnpdoed.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoixkyq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnxfvdo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdfmhnt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrfsatd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2heehnzcv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arghsogn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wvstkkhw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywieukis.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxziehc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwzeaps.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2knjvmoqz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaobmlph.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzpgiki.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzhwtrx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pztiqxzh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoxphis.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xssrugjc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqubyck.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fapmmuuw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iivwqklf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyextdu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjqtgqt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qybuqucr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzpughk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyquzho.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iekabmor.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2clrjrbzp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2irdppusl.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrfacdb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2borcawjt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2duxzqfxy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whmxnmwn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2brbgsnrc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfleyxp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lknqphir.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnfsifl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmzamvb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hzskfcpe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2osialyxr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxgzapl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hckplxer.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyleawb.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyerybc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnegkvs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmomfla.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbmpgpi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ismojepx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yweuwitd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcmldby.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqvijsg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmrbvet.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbrjipa.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2spszijzw.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2beyxcawl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxcmfre.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvxegxt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiuokaw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2utezelxv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpbjgyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abawzaua.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2giruwqan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edginbjl.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yluxtyha.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfddsypg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmagrvu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkkeztj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2llxxcepw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnevcna.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hcczgxrz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rntuyatc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oosevqey.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2encqhaeq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpjfdrf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2viohpygy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xpekscwh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzedhou.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdvcudr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqkzplb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwrqvjy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrgrygu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsvrrzq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvzeknc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnygqox.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsejfuxg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwlwpbs.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2glnnzooc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2npuxwwjp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2trxtlzbx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpmylvc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppksdunr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvvblti.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzglfkbp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ioisfdad.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhthqlxs.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpcjlnb.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2carkeaod.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxkacxh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhwnajx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpmkvww.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2exmjlwxw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbljlez.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2funtvldc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfborwg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrmxtoz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2azgfqycc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rptesbnl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxznoozr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndypbevk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfmvvnh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqokqkqg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhjnfot.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlzfymo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wolubqvu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yshuxoji.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qomjlscq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2czcppynd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzxqrtv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2teyjicnz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcihhja.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmhiadt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2iooyloyh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wphcafcy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmhjxkp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqrvfea.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcqoogf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2psjyqidp.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnelnprv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwrzich.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2flscxjan.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdutxtg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoabpfd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvzhdbb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kndxdgsz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkexsnc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvfegqv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuyszoq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2urjbqgph.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsjwwxi.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgleldx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tscywnxo.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjcqnfm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2vvonxctz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzuvjln.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtjvqfn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xeoadovt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwwiisl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfxaumk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2lddndcpn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2coobgzvn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjctxms.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaejybh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyyahns.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hafbuayj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krcrgigi.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2iweefwng.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baywtyfw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nshlkngq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nelmydxj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2avxifzwt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkcreht.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkptbgse.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gihhrrop.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzaofqc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhwqfqu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhmzjee.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kppwhdiq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2saykeqli.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wvljevvf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sednrjvt.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jtikrxlq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2knnskwdh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmpqsou.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqcjfuw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaztxpi.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2goqxjwbu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2snxcvibb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uecacnay.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkpxuul.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyrdefv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2egcyhjfw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxfjgua.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqooecf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rharqfrt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewguixme.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqragrac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkznrnqb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zeururme.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgmbizx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxitfjx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pomkdqls.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hhktpdhq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2edbxjtqx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkrvxdd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2leiicjaa.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzgbfqe.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxzdtkx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdhatpj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdakvhw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tosszrqa.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkakkaxk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bvngtvzc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaedryl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pujmkoiy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwdwzvt.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2khnjikve.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2osrucdsa.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2egxqnjif.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eknziers.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgkcjpw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebohcimx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2otiqamdn.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwdsnyt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkrohxo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwohwvh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2eklfymyj.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmagqhft.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kujsvpxv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsxiboc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wociyomw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqziusbq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2muiadygs.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruylkndc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zefwfthh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwcqqvq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2plvzcvtn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tplwlrbq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmniaby.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2keacvtsq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ptajbmnf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiuokre.html


<!-- 参考信息 -->