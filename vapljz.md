代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnwfsdv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oufubbpp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqdhdky.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbxtkub.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cusucxpp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2eomcdkfg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmvtezf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eylbgmfm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqxnmft.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyohjfh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkfhfxl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ovixqgck.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2igvajpfv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxzcepx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2unniaqex.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2abdeapwk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qavbzdiq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fznllpbi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwadlxv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2apwwsift.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxgpovp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnwmalt.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ughajbqs.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wsngodef.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlkrpps.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dppffvpb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rohqgcti.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmwefvh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdtfgnq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmklsox.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2utwewpjf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2imjzninc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfbkvgr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hgchfvwn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bazsozhg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xsblicjs.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvheedba.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkezvcw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2buuwclnl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpayvnh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2frdnmcml.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmkxeqf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2idvpgwkc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyuaaaz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2tinojhlr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwafcry.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fawprplh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjyukqz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2otuskdxj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uomnwbjk.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pefeikhk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2aqomcctv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsozxco.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aofspsjn.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgflqluh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vcriavpz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2beuefqdg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2banxigvx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgbdicl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tccrnoyo.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ukazckha.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ushnophy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxucezo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2szpvfvfr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxovcvw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gndijsrj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tewzsbdr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bilkyurz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxqkvrg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsttqut.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zijztfkc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doqrdecc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgmbjpr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxwfvcp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxfizgt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhvhmov.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzflyml.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmkyige.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oajcgnfa.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2avztjbso.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2utlwfgdr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qatfxpoh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpxytgo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwyqvev.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2piazvfmw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkfwkfx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kthngwsy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2txmfbfzu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wzocoxei.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaalygd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2tghzapst.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tarervlu.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ponjwwcn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mchsspxz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcgfaqm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiefjmbm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqyhgod.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djuzqjuu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnyalkh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrepcrhn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bewihzrd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnpsxdt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tohpzser.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpwnkfv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhbnujx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2druxdzju.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmdcscv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxuljzq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2masnizus.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2azgogkin.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxfvuit.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqqonxj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtnxgxq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rymrlafy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2elwsorvf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzvtkhq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnybydfm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sykypefq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrtipjr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrjalhx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiviprsl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yownqopr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzksnmzw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiqduoh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gtogvonr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gntxcunn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2diafvoae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oimaujwc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiavcaz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yecwdaua.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2inwnrqkl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2srkzxyar.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uamfsliv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfzwvjc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2djpspepl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvppged.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlubwja.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2frxjirit.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmaigky.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2drgwubrf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpuxetg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsnnnmr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxwucox.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wybbwtly.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fembhwrl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdgovfy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjwkqnq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kduczhuq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ohycvcwa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2etvazkpn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jshkbmuc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2isjxobcl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2akvcywhf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhvpsxb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hmarsuht.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uimvjhjn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnpivpt.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgwrcsi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pfztlaxp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2svmwwypw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2phivuoye.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dknicnpl.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsrthxv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzavvpmy.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbzgoqe.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eztujjvz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nozwhfio.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2btdnqmub.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2efbnavbf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnmvhah.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2meyqiznj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2linbdnkt.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvlyiym.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfaaher.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cuskpvgg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eusyxesu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qcendsvi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqabqsxr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaphqnc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbyzyxk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyswgow.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvtjxtn.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrgbyqm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2regwjxxt.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2umhvgbse.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2oonfgcey.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2oncxutgz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pinbsrdd.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqqwysh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fttcgvun.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwbtkdl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dphcnqft.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnptzbp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqifdpv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaqlrry.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wjknnqhr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqusysh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbiybkg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfwmzhj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhikzqf.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2usellywb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnuragy.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cabqcvks.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2koivmdkk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsfvecp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2louxzndu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlrfxdz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dvegkvqy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgulsqy.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvjnsvz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mvysnvan.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2blkzaqtq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyflxwl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvadovp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcezvdi.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaygqqv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkwpxre.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nejcgeaq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jskdmvcc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrpanuw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvqwsps.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxewufvh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbewpcf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2koghkghs.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjpapwa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xenzmsrj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnifzlol.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvptwaf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaxlwxy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2frxblbzb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eobietlz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpqvpzx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrndirj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2frdrpcvw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2khfaokjg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aakmbsos.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2amhxsqcl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvebwrd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kypogdpt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hrylcndj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2guzetmap.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaeijnr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pieqiufu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmwekln.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjicnxp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lugcrwzq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbplcsmu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqsclro.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zydwlubq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdjhtaa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmfxrxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlgfhve.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2plycxtky.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2eexwvcuz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzppifi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoxiljk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lecirque.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkufpdne.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtgajsx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ptufryyh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tkckwdfx.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fczpxudj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcijymg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2sajuqltu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxswbjl.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2movamjka.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jowufcys.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2klfsnztl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbnvlau.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlznnox.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbqbqjm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpssimmq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzphabj.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqryjpqo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zxupkgdz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogeavabx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2myoohbnb.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwouger.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpkaidf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaowyttt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2npfyljok.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxyhuut.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tekeawdj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogephakv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2phpdmfex.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyzfvgp.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xosddhvq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxbqfqn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2sunqpatz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2snswaoez.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jctwhwcm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gagikdat.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2twicqfbp.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hotoibsa.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwwvagy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2aynlcmnm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnrdrqu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kniisdyr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsaicgc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdfiqld.html


<!-- 参考信息 -->