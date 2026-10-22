代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqlyzdd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfvvaxn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrshhtc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqhcasf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvvavqp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtyrjye.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfjezld.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qnophgyn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2swpwbbll.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2flfcvfqm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhaqkyo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pghybbkm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbdqfxl.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhrtlmg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnljlhrk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rsciocwh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpcehvx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2maxerygs.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2snqiivch.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtyofrp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbkfapf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoytbfu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrdmaom.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2imqijshg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgczhmn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kilwtgur.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzzxaco.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuoucjz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkkucfa.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsicjht.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qnffjgyf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2czwogfdz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2thdgwkkq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kcniuuyl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2noqvlbsc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuuyqjt.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqkmkid.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqweacf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovclqhxl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkciotg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2njffubpz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dosykelf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkfxibr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2psumopvv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpetmywr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fggphkmq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2flvnifuj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2opxfuzdq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkattblo.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uzctulty.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dooraxrr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2siacznyf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxhqhnh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdrqxxt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmwneex.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vqztnrea.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqxkpug.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bahsgedg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuygxgl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnjeuqf.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ftioubke.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuystci.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsjwggp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2okjnkjbe.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2btbhllot.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyliucsm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcxtuhn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hidxcono.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2krdjvagn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jczlubkn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ozltqvnq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpjlaeh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvmhnsg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2efocrurc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbzflfv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpderbvx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkzgeiv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2djllwonr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2chmiyoog.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwparbh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrogwjm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjxoymz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tesynjma.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oavnacdw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajshwcqp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2emxkfgrk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmxgoaz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2otcjbwii.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2msymascj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsuucct.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkugfra.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsfsjmm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2iykumafs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcyuzmy.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqrophu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2herntjaf.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2klxriolo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnsnszp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqpaiyo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvpevtq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaevwiid.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbimfyu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kxipvcpa.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwzlxht.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlzdwuv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnpstaq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2namqqlba.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlyegbt.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwbzbwc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kvabhaiu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzoxixb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfqmlpm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zscgvbjy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fktvmyyw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfclrou.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmgldcr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbapedbf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhajmqge.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2csxfasgj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2csxsdrgu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjwfcsi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ogilbtus.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjahonlt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnbtinp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkhhkic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ippydsxh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkzpyeb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lahwqtfo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgskoms.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkidqbi.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2womwczpn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ysucsrao.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgffjxw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbmhlgt.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qqygyzpc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2toeislux.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ynissbdt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiczpss.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxtcaix.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnudgqby.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qnksrmlg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxnaidj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2apufpdwu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpnjset.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sucaejkn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwchmhx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fkznqsds.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2foxrfimt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoezqoq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlafyst.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vlejeofh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaupcsga.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xinpjczz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2omfriudq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sdghnugz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uckqzstp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfkeaqc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwqryiq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoumuml.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrznwsa.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjxsweg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmlltnz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2czizoots.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmxrzsg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxavltv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkypvdz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfrqqsm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2czgmvmtj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpdimnd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2epbcphzw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvtmyin.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nlorxgkk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2urmzlpve.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzzovme.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bzejddmm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iycnzmwy.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2aaveuhvn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvplbdb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2idodkiif.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dembuzkh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nqckjwrh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzyfzgx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgkmqbz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzbavso.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2irhvkfiy.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2aosqtdtt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xtztfqmt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnekrkec.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iaczrqls.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpuybov.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2arrmzvpf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrsasqz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcpjtir.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2egslpffy.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vgktrxug.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yccptsiz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhinwgg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hlegplwm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlzxbhu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqeotia.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpgcfgo.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjibrehs.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2efimknqg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxzgzik.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmtqzfs.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwszuby.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lpthrtkw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhzdjhp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jeldlkip.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwsqubc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gvixaljh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2imtlnfko.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuzhxfb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tldcorix.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2swfswced.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmzlnkc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sswukrru.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sguyftrg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzzwjjw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcfgskt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xaewudse.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrszmqd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cxihdkfo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2omubmasy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfnvzsw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoselfa.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzmvrhy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ephbnatu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpqsgui.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgfqazm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2susslxsl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhhbfjm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnuwehd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkqdlro.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eppbldbw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sgydmlfk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2auzxlccq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlogffb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vistekbk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fjaigslb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrahbic.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lbudmaav.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2efhhtyhm.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmhmefq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrtjzam.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2srovjdea.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2okxwjxha.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvaygzo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2phjnmjde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owrdmfye.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nesmydmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwmfxhx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ppujijyh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lvylhqwg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqlhcjq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cknhxsep.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhqkdzj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhxwhwb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xraiyphr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2edjhzlzz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjybbws.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2loqzmxny.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkhhvvo.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2czoecuyk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyaesaf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbexehf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2whosltto.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2szdvawbd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2flrqdjjq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdtzwmd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvoqmiv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmahkacy.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dnibbfjr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2juovaijw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2caivcjvg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtywpyyi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2azfpnlxo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjzufle.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mebebfci.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2blybjgfo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2udrujdlo.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzkrshq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2amfdzrzk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2orhqzmkc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcscubi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wagtwfne.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yheaopnh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzuzvzs.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rkytdykg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzeqpob.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbjhbft.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccizfjuo.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2imaghoio.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhwomlb.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqjsbzc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2oevamonp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kahdfriq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kojxdqim.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyblqad.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtquygzh.html


<!-- 参考信息 -->