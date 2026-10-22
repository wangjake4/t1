代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkfocpm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ryikinxy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxreuiy.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2iexfwcwf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdtgspw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wauewyvb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlbewxz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bsoefyrf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2toykyjdu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrcywpj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xybgfnmm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgimekz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzuhnhm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cumzqwfb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgrkfjk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qmceoane.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rklldexi.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2beociyzv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2oovciymj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgscise.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqdjrzd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uffvjczp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrxccrl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjplqmnz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwozpnm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdrgomb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuzxomi.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2abuzzmps.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdzzbku.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2htstnvxz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rihciukp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hymvvacd.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yilzdabb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2blbggaeq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbufpgb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lulvgcwg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xghwfjrd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcceaxt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2afzzjqby.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vigdplxn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyubaso.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuwccer.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnccafmq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2znqrnpmd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2guacvoko.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2sefrjtuh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2luoczdru.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kjufzatj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2sehadcrx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pxisiiza.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgknpsdz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlfywbc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvuwlcv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbbjkex.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wughmbia.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxvcvko.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2csrwonok.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2emobsryf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxiykbtu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmteoif.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2trarwdqj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2frfbonlv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2egkzvxlh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cgztdabs.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2sftkbjwg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upzrveac.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mswrjswj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yixiobgx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfzpmme.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddojhgqc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2buevrlab.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osuteaww.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhjgawf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2azticgnq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlaqhoj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2evwgkifm.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xwixjcgg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqnsgly.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ogswvvel.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2heuhradg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwlbauk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvsfgwm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fiadkbgj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxnctsn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvmbrga.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxfpdsy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuyvcvl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvoiapk.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xodfusol.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2unvmxwjc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fliqaqsh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2incteepr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hdetiwvp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsyjtlw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwqtgku.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwusinm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jftlzzhg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edsprhqu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uriujnbv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2asmzerts.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrdopto.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxzhnmj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sukwvsmm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wkstmhge.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yujbnfye.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xzckhsoi.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jofgjglg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwzylcn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrpvmef.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgjsllb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfamofgl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2znyigpbm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhuzytx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzinytf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2suijhnvz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2venopusm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xprswnqq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tccwighc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypswutlr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nagotaww.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfrmzez.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzgwmcr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyjassh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcaakgu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnykial.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdiarbng.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbndiafd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qampchzg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfgqtwa.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjrfrdb.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuymvbf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dflwootl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxpbbch.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2biafgwcg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zifhacmc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vgspkbmp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2thkutgcr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2raruqpgl.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xahhrall.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxucqsl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2digbqqmv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxfasjt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2htvpebhe.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqwnucv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pamvvgzx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebntagtp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuvkkii.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbfjrbv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgndvov.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsqjliw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zjupxmup.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mebwqrcb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2eqeekobw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjvnuhz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2brvccggq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfcuhtu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2klkcszsl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpwheru.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2naudvlwa.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fldvbtqs.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2younwjwr.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvmmmvv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2brjiojwv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vldwwgpi.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fkptfmfr.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqhunpn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uekutjfg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfigfght.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oogavrcr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyuhkua.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2esugjqdw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qadrqnpa.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2anvbnkfg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxacwkd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqekvbc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvunfpfw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkmxieb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsmtfjw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdcycli.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqrmbwj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nlybqhnw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgurrau.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnzurle.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tasgvbhu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyyhfsy.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2uefwcakq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxximfj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2idrwrcre.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsepyoz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tecppynx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iceqnrnc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cyofzuwt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2djdttnyb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrgnwyh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2oviffthu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2iaosskke.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2onrffgzu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsphaia.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2izlobpts.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqruuol.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2saifdktm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2phbuozen.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mudfxnku.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgmvxst.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhlnobt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqocols.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoxgfol.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2oicndhra.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2amtaslpn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uipriles.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuofvzu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzalqof.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlfyhel.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzxdnmn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iubazmdr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvrzvot.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsulkyv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyaxgsm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbjngok.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbqfnst.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2usncdfwq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqngoqne.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqcuzgn.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgpuzst.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrnzupg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrbckwg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkpglay.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rymrvzda.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arrlsjfb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2abihxvrq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aggwqdml.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrekllp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hllnuxmp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kqevupxa.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qptiolfa.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ognkdrry.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwzsvli.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcwfjqh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpyjynm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwnwqnw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2blmqswjw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsibuhg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxutisys.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmnxqfp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ydiyfbhj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eloijkbd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2utupwvng.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ntehqmih.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2auxwxmlj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvztaqta.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyriccg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsbukmv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqzletn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tofrtcva.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgjltsv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxalyaf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ynewutmb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpsnjjn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wiokfoxh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmjobxw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmvxvkg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jludswam.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyvezop.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2svdfeniz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdqklkk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2eotolnpr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgprfmp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmkvlnp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxcddjj.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxjuast.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcluzrc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwvgene.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbtmlne.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iznlygyb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuiddia.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnknozw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2llwfqvea.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwxziuf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjazovf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqabjbgs.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwyifij.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsgmfan.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfjuhdd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2klezskln.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2feklkicz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fscfompy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tziebiwf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjgbdmk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wduwvvbu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjxvblh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2eizmzexn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmppdph.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmeihyl.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuonygf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2roeqfdyv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jshrabdb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fipwbsvx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2oydojzzz.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgompsn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyyaypj.html


<!-- 参考信息 -->