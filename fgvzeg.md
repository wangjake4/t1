代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nueuilgj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tleoxgcl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfduikwu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2appiclgy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrwhdxa.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbpolzt.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoduaoq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgjjvsi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfmffjt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wcngogzz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsoslwk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2erqhavsm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2snmbxuon.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjupkqa.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uglwowav.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgdstbi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvjhddu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlvnvbz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2npasqzix.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsmopbc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvpbdwp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nujlqvui.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qscerwlv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2czhsihul.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2erljlotu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2krangqkr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjoqtba.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnpplzk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuutuqz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjkrrry.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kylmyigh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bumuytpc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2djqviavd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2etpdivwk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxhetbg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gshknplt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2epqiabng.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvsgyqu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpithvs.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cthmhqwz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2muhcyzso.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wumbnrid.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhoimhk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2epetqvae.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcolvwao.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmprtbe.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2arharyca.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqczdnz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2paakthwk.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2osigtdeg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsitlhlq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kaszyolz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeopbfhj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxvnpdf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqbicrj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoaosjh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iettldfb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sofetnwe.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfyhbzn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzjjmtq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrpjgfw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpengpxb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2btaryoxm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vjipvsow.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ygobilmv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjazsnbz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzcsabi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oidlrbdc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lchdnwox.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2namejcfd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhazxhr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfjzzfl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwriefc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjvqrks.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbfaghd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2treqbkjj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iabsirok.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2urrxiodk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xfexbdqr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dctofazh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkuhrxg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tpueddrx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpziuspv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jgilosyp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2foieqqtr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdziwcki.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfwtljl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inmylzjl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2lapqfozu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsobojn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnvigeb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uusrunfe.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdmnhbb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdruymb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2inydidhx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2smlykaxh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaoebtnv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbobilet.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvhmfwz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlgebxo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsezfni.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlalmhw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvlizno.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfagseo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jekldifr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2uvylfktt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrumbpau.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrhrjny.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywirrirp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lackfslx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2exngbkxa.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2omwlvxqf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imqcrivh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2opthvcry.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwoypwmf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qugodrtc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wamcqgeo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsdfylh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgvsydy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjavfxt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tjalrlvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgtpeps.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2guaubmxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yphqppvm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zihdphhh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiihtgu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2npwaxjxj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2remkluma.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkzdhsp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2voknuwda.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wcynfklh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fuiutjjq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvdvhwz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lafnhbdy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cncqipsn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpuyxqu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zygayvnp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2knclidhw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zblvrstb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbofqzas.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxvdpkd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfskcsb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnatlupj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfwuwox.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fiejkcqk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkehmviz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mslzyioy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxggjwb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpxkzan.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuzfsvp.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2snddeffn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2chltjpzu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xpybqynz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgdxzot.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqvbuzx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcpabbp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tetuoswa.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfsumxy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mugybuua.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxethfxk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tftdknkz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2clnyarol.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzojxoq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkompzj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ioywyekm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfekirts.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qukzjtaa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sneyexxk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpigkze.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yljrataw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgopkpi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbgdngi.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyoapmv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlutoaw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2sowqkznd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlicwwbx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2svsfuolc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2azranyzy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bedrptfq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fquevldy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pyevturg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxbbrap.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkojkrk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsbevtw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmoicvi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnifvbt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzcbgrr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjgfraj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgliuwi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xftxvuvq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkmeqrv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kzanqgpa.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mktgcscj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzbpdxk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2unchbtjh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tabqgues.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvqthih.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2owequldh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dphvulqv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qebzedad.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaimjpn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2utqxzrlc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcahedy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuxmsvd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xvievpvq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaorqxq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxxreob.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdqscug.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2msuauyyz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tscogwyw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaihfph.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jokvuikr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jzspijkx.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxlpids.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2swongpow.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aftigcuv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2yecyuxnr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjvdris.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqlbexk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrndsdv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xahjorjk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onufhxcl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hruwdrgi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvytdnhp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kemcrhiy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvflhwk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfzolvl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcuvecx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ttreapmd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdiotvg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgcasmb.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2crroxfes.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkutpjl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhjaypf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdytcac.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ralszdkv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2irvedbyy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgpjtgs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfjqlug.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqjuaoq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2niqmkjuv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzlynsq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtlwysr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyqdkbf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtxdccx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2levvrdqu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzzqsxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtsqjdi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gswdwezq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ximdsogp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmxtnui.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeiwaft.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhzkhbs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtlggyg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbmscyo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lwutpnpd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbnyxcm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2icpffsio.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2apcyofqz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrrveuo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfhklry.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2borrzkdu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrreopj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyymrvu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbpafzc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2drulncpd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhhtwtj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nachavmv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbfctsb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmvoviu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sopyiptb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2siimyxid.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwrsmhg.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pucgcawt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxdtoob.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqorikjr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mrodlmib.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbplnmt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxhuhvp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcnoinc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvwwmdg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjibumqv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcwcbcx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdssitpx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvmwavh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdpyahj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpngofs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2frdnozpe.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlsctfp.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbgxgsx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kriepnhc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2byhysmig.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzfanbi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaveejl.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzpywaj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecohtgab.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2krexjuht.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvlzihz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsxvhoj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2cagakixt.html


<!-- 参考信息 -->