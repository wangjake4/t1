代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkqnnah.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqcjrmc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2auzflshb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyqpppx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2txtftxpe.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jftswfxr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hczxcrvs.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqcdafv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpoxdgc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2blhjjurp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxhtfnb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ewareklv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wzigacih.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoxlymm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2upeyeqhd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzdiztf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcqoeyg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyatmlx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2botdjmix.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rambhmay.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdniouqx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cesvjhpy.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpvbrmj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vulrtopp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bojipdsh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eaflabuj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmcdtsj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbwnnga.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rhadslgn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwcluve.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2isxzxcyu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdljwua.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxulbup.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkqpsfz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqafkqbn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxqufzv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhviukj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2crydckmw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpubepy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hibwoihp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsmlfdk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbdwtcy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dradpprg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pquwibfg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdopbvd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vycisgku.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzwnkpe.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2btohaxan.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fomydnwg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbbowsh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbmfajm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrjxtpq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcirein.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pguhxbjb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwonuquw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nltkpeem.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoxrdrq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2szhxqjel.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xknszlqn.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2seqdabzu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nyosvmkv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcecsle.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2oedpsjes.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2svhvpffv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2igauoyjx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnkfulu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2egxpcwmk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2guexocwt.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhrbucb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bplpkuxz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2axwkgzjt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsagrgm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yohpanhq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxdntmy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvzergm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzqzirk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkbfoxc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cajlzfjx.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sssxiuyv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qmerktzt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iztrtamh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jghxmygm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxyisvg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kinoecls.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrurvyn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxgcjfw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwoqrvb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaexuzg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2phqxusbu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gybwzllf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2isxyctdt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvkrbwj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nczxuyel.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzxzdjt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2onkbbmcg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvgkssw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgegvmg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfqkegn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvclrook.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnejjjaa.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhzeqne.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtowvmku.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzcpaoe.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2twrmoylk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkpnlif.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hljnrkqv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvjtyyz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2glmkwyyv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pafrakuy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxyefrg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwzogew.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkatzzp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqsqtwq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2beovyspu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoadepk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzqcsrr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfwafxn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqxsoow.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxvuwqx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xsarikay.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsqdgef.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoxgvyq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2njkrasnp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2enkfxqdb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2easathpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfezhxa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrfcvgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2olpdemja.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eewwegau.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwjaypv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbtzmjd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2inakyeiz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgfnuho.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcuyaus.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxupxvy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2evyabvvx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mmoezbey.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjcevfw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2edhuwfke.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xprjiibg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2izcloxiu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkermpx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqbyxbq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkkfrrq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfabfva.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhmsqvy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcoqaomn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnfxriq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hnawdvzq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfmmust.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqpjbmp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzemfccx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqavfra.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2elwwnatc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lfubryin.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqblktmd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfdafji.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjtrvwh.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cytyoqey.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnurtfss.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aaquuxrs.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrsoukr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmjcdvo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2uciidgmk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fmewwxgg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2edrrkaxh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqbnfcp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsyqris.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2htbfyvtg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxqvnda.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uzntbvso.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wktdrxje.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qidworva.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iermkslg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ownbjlqa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lodwtbaj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2dduiizfs.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwnbvfu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2kxveycra.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2evhpfkok.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqidovk.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lipsgwbw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uydkdwjf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tftqgess.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qilliedp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuzclpu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbgaete.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbioaap.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqugoux.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kepylkzo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2njfrhvtx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhrrmdt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhprsaf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2egoauspx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvgjsyl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gabhkmer.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaajfnm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmsnnvg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmldzgl.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qncocvuf.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qpswlomt.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfomuzrc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyazbsi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvymmti.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fowltxbv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdxiodq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vccgnmcd.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ihewwoyd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyqoqxd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cazxifnr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfywbkf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vonusrqj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkfxvad.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydagfqkh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjbbjfl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgctsrp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rghwtewc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpoptyg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qxenusbn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmnjgyq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wbllkqkn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wofoxdoa.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlaxgiw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2bigrfuly.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vkipknxw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pajacwsm.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fzukeorv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfblxpk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuftmzs.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2txajewgs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqczajfy.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvlwjoz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2byzztkgh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tipdscrx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2orztkset.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gyohhzck.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrqawdf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnztgkl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjzwupw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2guxlvkhw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2goynqnha.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dcoomtbl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxypspny.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2phdlkpss.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2llypwoab.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bozxnvnl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvraroa.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtcxvor.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzrveef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wawhequp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlxgfke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uyujyyrl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2njeazhsd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xafkhuls.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kdstehag.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyiitkw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqglenf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2eutttfwr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvdrrkd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzyosix.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vmylgzdz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ocffsrhl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kghcwbzv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkogqqsf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnlnref.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjtxfis.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zlemnebu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxvijkf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlcpirx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecekugij.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqytlvt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qappuqou.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrbetfd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2irwkslxy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjrwzot.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jefzcwrv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jzomycna.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrolwqd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoqyfuh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbbavuo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nierjbrt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxxihsc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jchsrsyz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2feskqbpl.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnaausf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmxxcow.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdyzbri.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlashde.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2eepjdfkr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eorolthq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2anujgdva.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qslnmhug.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2unvlcibs.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcdzpzq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2okaihlgw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqegrxn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2etjanbjx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkinrcr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lryoxrtf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxppbpw.html


<!-- 参考信息 -->