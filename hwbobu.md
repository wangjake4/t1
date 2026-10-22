代发 wailian999

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaormeo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnegcyaz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnqsenv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxvfhln.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvymshge.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pomoownp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnabbneq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ructcvtb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhijoeqv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoxtvkz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoajjty.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuyjtsi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nutarnwp.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbieryu.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvqseje.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dclxiucl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qwljjrra.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mplkmhxh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdwzada.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2iatzhyoj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqlojkk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rrftwqfm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qozvbdrj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjwkzcc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsltcunn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2exjbejno.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2stckblfy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbnfdru.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrraygnr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dthcynvn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nezhrkbq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pipuwwuu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwzzljs.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rssqzwcb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bmktvuxd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqjwsxq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvufuwmq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpnuhro.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnknztt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bshpgsrl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2uggvfvul.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2inhzzmez.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyzskwy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwilalp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bulhuews.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjytcfl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lritdodw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lorrrrsc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mruuandk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvuyvpr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfpqpdk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyubiml.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbifauaf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqsdyht.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfflqevc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2iebeantz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vglgccdx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2orefxvht.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnskuftu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2twocsdfp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtpirqk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2afcvoiev.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdzcpdg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cijijijx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uyscdzzn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmdkezl.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2yhobkard.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyqubwe.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2imxhikgo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zohykadd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pytqkdrb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ikytroko.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlrxwth.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrtceuz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2saoogtuk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifiklrvn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnglqwn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyhxmew.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2htxdqamg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aifrprah.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2yygpoubu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gitxnwei.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pscxmeqe.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqhqnro.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2firocvkb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hevbtubt.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ufijwuzv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqutjtg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfvnxew.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2anjvujhu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dpykwtar.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjyagyy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tevmpkcr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbgunlq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bscnkkul.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2delywdia.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2chmuayta.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbdzxno.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjpfkwi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxzueix.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aysfefbu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfsjqcn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnlvbpd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaklosxn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpayyxdu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrjoept.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ioegfrkz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmvxtpi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwihntfl.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtryxzr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzraeaf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xdegqwdo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyfeazk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2crkisjox.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tttjkgec.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bhffrjiv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyglchl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqzqotg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fefbxklv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxsityq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkrhuvt.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2inmhibta.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cogpmzxg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqyfgky.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oohmkfec.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jocczhbx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaidget.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hewcibug.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpklxka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrmuqxa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vaklqmjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxdyixj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpvqzvc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2njmnwvhs.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmtghdg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfypmqv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pdohyxyd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2etebrmzc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgrffiq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxtstuh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lekjrwwv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrabaoe.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwfdbxm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxaneoh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnwizty.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkqufbw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zasmaeeb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2crkhppyo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwxxros.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgesabg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2areljzug.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2frbtagpw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwwrakf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqimbqha.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvgmefv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaabxcts.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gckmnkyn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxzxcvk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwdwhod.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qavtvlaf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvyxetz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2punmrapl.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qxytpupb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzczsvyu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2meqoebga.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2owqqpmbd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nzztzqel.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2asfkyshd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cltzgqtb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ublvdpot.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lziuawov.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzqnjwl.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2okxskrkk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdidwtee.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhswybs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2keedtfhw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhkcaew.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzkvvfo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2afdkufxn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2deocfjwx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2keqlovxd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltclmqla.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2yccwpnig.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkadsjjr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ookgfdjo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kexqaqxq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqmaamc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrctwiip.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hewezdeh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2peiivwfk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kqltbdsj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wviyvjqi.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pttqlutm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2poesappo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dzacqkqt.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbmekfg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyvowdd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2aepopoyv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqnlwqi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ywralhsc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2deerjncm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwmubrb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsakoukz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrjueok.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbibddx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynglomrk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmgahyz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbfiyok.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwzxnhr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcrdogk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qstimzsu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmvstrq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhsqjvb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hgotrmqt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqatxze.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmminpcj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2drcfnfoj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwfhsnt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqaeckrz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxhiprq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bafdmsxv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnelguh.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyrlgie.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxezwrzo.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2esfnqpgn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utvrnucn.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jdybjtnx.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvymvih.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2arrlssow.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqavzss.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmumsgh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2avpetfxb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkwxego.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2erixcstd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yemoxlvb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbupoxp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdxekcc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qjedkyyk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajynmoto.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oohyckwd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rppusfgy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfdjxkh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuniwwt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyjwvtb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nutjfocx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpnilan.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iupumvyu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzoanvt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yqshvsxf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ttypusca.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwetvozq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rhutgjjh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2znbiiqfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syciwgvw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcmbnpb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjhekay.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hegwywbo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2brjeiyed.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nasxudgj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsglfck.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tjodgylf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yaowtblv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2apkanaff.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2azoelven.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2crgsglip.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yckoabfw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2litykifg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdhtqjz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmfgenl.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwqvxzb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkivrdv.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrohkvs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvpqdva.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgcmdqh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlruhbz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xskppkol.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2meidvgde.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xndqnzkc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ckguhtak.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjweidh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hljvcclq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwubrmn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtcnoay.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2oireouvg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hykxnucr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzecyjmv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbgbugq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuvdskq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vknkxnro.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsjptqv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwbppgw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcecjrl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2eusmkuas.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbfehux.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tuopxbjr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qytsnaen.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmptkll.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2avbfukel.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vahyjiql.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2odbcgcpj.html


<!-- 参考信息 -->