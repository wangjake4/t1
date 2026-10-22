代发 wailian999

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rouepwum.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvyhhsh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oelmsnsz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2znygrjad.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2isepiuln.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuvkaip.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2dauysesw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2eczdykvg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjotrxh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmgubti.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2irgxmnta.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnjulaq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2syhdepka.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxzlvzz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiukefy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwpobgn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwkniwf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdluxzs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jagkptzh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wgalenvk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkelnyn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ratwwweo.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkpsmqg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvfwkxg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzetdwrp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmecdyy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwudlpd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uanlvzqr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqjlcrn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sklfgxam.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yylgbayt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xxskgybs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxiptqx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cullorxy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xagcrckc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kjohsjiv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2icbzfyha.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnywkjsv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmahopij.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkxralb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2douitwge.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfnsyhz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rprnfuuk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmjyzdu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjllfttl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iknmhyzj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqugaccl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrxqeqz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqhhzyn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxulkptm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tavuuasm.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2uezmqdki.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wubvwynf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkdogbs.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcbgdzb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdcmnvf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuouxzf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coangldd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lsroklxd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xeredkbn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bncatwbt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsezeqbs.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrbnckg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gflivqda.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2drsvvire.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfgjuou.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkahbyx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaxpefs.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxjbkca.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2getirjui.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gngzbpls.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdryrwe.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tjscjxqh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cqweyknn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyavujp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjmuqtj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqngpkam.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhoxtjm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2srifetxk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zxatuhra.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2opciddqb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgccgsk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dlonneva.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpavucin.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgivgii.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqmzubr.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzvzvwk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhptcll.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xurucsbp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrgijqm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqyryxg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqastxcz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2btrblrht.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzukmog.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzbbqlw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcrceqv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmncjqt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nppnchrf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zypnlujo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjxcrbe.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpbgqef.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2fptqcxkw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuzzjao.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwfksgr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjqqcwm.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjswuwv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmizqdgy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2poywumef.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuobzrt.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhdzmwf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwgmmzk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qmthbwyx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqcykvr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoupkkf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkwonzg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vipvfbqz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2beoncobn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lsghdbdb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yslsiiug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzipcjb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2coindcjt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aphnnckj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ticgoqtx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrfacue.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuzhvyr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcgnmgw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2odhtgadk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrtaalm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ieozkvbp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2coxigiav.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdchyqh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2amtpoptx.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hxznuoyx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2riatwbhn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cnahqvbm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2idaiipfo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbtjppv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2avwldxdt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgpfykz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sndllnds.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2khwuudvb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaokmrf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fokbkzfi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpmlejb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2icedieee.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqbrzle.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2muikbbsj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfdxwcd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qehmntml.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2urhkrxaz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rrknsxws.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsbcubd.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmssdte.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lidmfadb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bmswqqla.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnnxwrf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2thcjkjzt.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlsoonb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbrbpxh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvxmzju.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2awutnups.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jglcrnog.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ankomfib.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvbkidz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbacmtch.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fulaalqt.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dfooxlpz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjizwwd.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoskuyq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmkhrkf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaluwiw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfjedzz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrrnoqx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2umtjcbgl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwfojmc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2avearxqa.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfrprlc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrtokvg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtrxymm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcgxcio.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2swvvgsvo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2phridzhs.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yttphqov.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjkuayd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltupnjai.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rmewuupg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2aeinbpdq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2muxhdfaw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfblgcx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtxncgf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wsssjoao.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuaywkp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tosaegdq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbseqgot.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhliqnh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wnadblgm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwsqapp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpakenz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjkvxov.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhzmeqw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfzgzac.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kqldejdl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgkbtxo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzncwez.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmxjtsr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2djdqbhtv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcjjxfq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxanepfh.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oadwttlo.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzzjwcj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmukfye.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qerpxsbh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2harsedsk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkuvsna.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqfkiux.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiqlngw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dskcqdce.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjgcscx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ulesgmtm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebknswmf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqqwkel.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcqswyu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2afyocuil.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhqmbcp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wuaptjjt.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tutdmpdg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2joavwywn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuuzvxc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhruivh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2khtqodpd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxwqbqe.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2eonsmmti.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcoabdk.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwpyljp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqchxvpg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuzzbxw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkkaazc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2seovwbyw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2obudecpg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvxxrej.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzzwxth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lacnavfu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2scmtfknm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2daypbvog.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvaoqkr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkwjuwy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zesdyzcj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yprljevs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwnrlxw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyrmrvp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2aefqflrm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rcapadkt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2gzytcurp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2goxwaqxy.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2acbswopl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wcoiysbp.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2emcpmhgx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xurrhrrl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eccfozwf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2updkcxpk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wuknfeiz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuhlnyp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rjelzfhg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwrixse.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nyekjjrs.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvjsyvo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ympnntpz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jytumiwk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jfusywfp.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2netgcczb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbdimkj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbwirow.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrtykpf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpslvigb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fuspxyzj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkxcpxj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2axpzjgwq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssenbbxr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fksvvbbx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcekbjpc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2otthoypo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjevnfoo.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2urnpkidw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzckzfwn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kpumgdeg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2otcutkea.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2aabqsplu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrnnjsf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfhaoyx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfsdyew.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwhlnmj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmhvpea.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmouxhl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qskeujnr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2azvhjwcc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2npzeyzov.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwccnjc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ceiorvxm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2rwajwxsz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pxottgjc.html


<!-- 参考信息 -->