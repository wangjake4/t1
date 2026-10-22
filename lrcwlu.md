代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlcddgm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dwiutltv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfclvkn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcpfgmv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wycfmrzu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2htnrxhoj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuvhdrw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2awxbjbsj.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkvkuqv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2puqzthjy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2capaedak.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfafrfh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hvctbwle.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkwqmfp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wheyivvk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbtxhni.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ymreveaq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2phuuskwh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2heloqfae.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2voyzdssy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlraxos.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2owguctgb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yazybeny.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lghtgryg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jonergqx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnrisqb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vebzicwx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxilnks.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdbtfpc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fmszlmsa.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2oldbzrhv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vsntvbax.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgexbfkb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pulygkcl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqwitbl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjdpijw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnqumpt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bacjofyz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgimomnv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2knekupwv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqaxprt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hfopbjls.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrunxgh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvhkxvm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrnzqkt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuvflgc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ropstgei.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2miqznytw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2malhkpxb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rslkkzno.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsqndhj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwohxng.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjqegcq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aitpjapy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jplkmqpk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlljsxg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gujlukxe.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eswfcwui.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuekplgk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2opkoqchl.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeuwdnn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrbmwwx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgomplm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwdsxct.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrgttfe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyfewvi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2knkxdfsd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqshptt.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rynfskzm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yikcvpeu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uckxqwuf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2piillopr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pochjane.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmayyblh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vibkkhsu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtziikvl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkkwcws.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrfwtod.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyhiolk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ejesbror.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgnembl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjrjswx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdqxwmo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtjvcdm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lazzgboc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmjthdr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2euiexojo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfuctye.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxwdwjv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fewlxxio.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdybfnn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxcbldr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fsumacei.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxohzvp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhvlajx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vojiyrfd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjvswtd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwplvsyn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuyadah.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxjkzer.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkuenrj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ongclthh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2aepavfhy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdxbjes.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2owogoduj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aocfcrag.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqnjcwy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkrrqtk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guxuxdom.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2msaohfxs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2lizqxssr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrvovzg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdkxayo.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2soaxfmag.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgxescd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvzegsg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzekwcn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnqhuit.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqatacj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kstuiknf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeyrtfx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zczrrmzq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgidory.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcopwzh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnixmzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnfptil.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2olwikqtj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbjphrk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwuyhmj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyijmdx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2esevozts.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeoerff.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2socaddvw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkojwte.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkosjlr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyhsbvh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bkexhvea.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2teooluno.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqfwikd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdnmnsy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhnduuc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzdtwzp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrldtcf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgunrlyo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cefvxzba.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqpghyp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2htjjyhri.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2stcdfhhx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2uizkmwwj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2etzvxjoe.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2whnrjour.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtopabqp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hegtljkq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwafhtcl.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eliyvfva.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2asuvsciu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hamzxrqi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2usgceqhm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqcjmkl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tczcpoxh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zscpbpvx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rlztpjwf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yymnjwac.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqpreyr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sddvcdgb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfqunnb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjtckon.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2agmkhjcq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkzsejw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2roieafbf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaqusin.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2procrzkq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcavqap.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjympgr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyghjte.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlawjkvu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvjlbpo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yewwtaql.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfxglkt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzybngzd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbrmxfr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcgvmeu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2avqiwsch.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zugusuvy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2txywitfe.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzajzgfk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vklcnyzd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsccefe.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcysbjy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxdnxxo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqmaajc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqisfga.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzqjwzw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qschejus.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cyckabwp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rnelhddw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ujibbgiw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mtotlgje.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwgctax.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2csxplnvf.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmleewy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2psfrzeal.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2izjtiphk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2taqeugvc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wskbetqj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yimtzanq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrdrzmg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2wszlhbqv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwxlhnx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fcllksyy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsuuhpb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyaxxtn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkmfuna.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvlnepw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnloqlj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oebtqfcs.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2okxzlvlk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdolbaf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rudxxqyd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvrfkii.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ozubfqze.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgymkum.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxopphi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcihjkw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpulcgs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgkbmin.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrejpyp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2aglkwdwz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioswxrgw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2haeyaici.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujctdhhv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2djjdanni.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtyydgs.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxtgewh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxespcjl.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2emxzzros.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgecalbg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nxojvhnn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vypxsndg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2txttgkax.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhacevwi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2awpanczq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfectje.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wsklwcbs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nwofbwnw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fmybcfza.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqrqqeu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqhcvnj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzctnhmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbtnchf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkpctgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2haltbwln.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrrxkbo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dppspsxw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxjfqqx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bohmfudn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdrdajq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdtgrur.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhqwnzf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nspplhgi.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bfilxjtp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2okzfalvt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpwpbij.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2anengjel.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2phtdfbin.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgvflic.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kssckwyj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2yafmuvrv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gyihwubp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2aviqemcm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wburpsho.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkpcgsi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfagwym.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnefmhad.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnkbhut.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zezjpnog.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bopdccxr.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjbrjfo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cstvhuyv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbfrdnh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwnkyim.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqbnzii.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmeyxlu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgitnbek.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yigspbbd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2weviryqs.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiguvkh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfqbqmu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2opkacuvu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfncgymk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiiflbm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdfsvko.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2trlzlafn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcdsndq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2sovntifd.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnpmqtw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoplflh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hvajmpoy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2puzqmymf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnwsdmq.html


<!-- 参考信息 -->