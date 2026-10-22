代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2snkhyudn.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxfnkco.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2clamevrq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uxaltvqy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxrhhlb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jxamtxpo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvhccog.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeazbgf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2sujxcxyv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bhppqpua.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpjklcg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhhkelr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2foscqxhu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2sstsqhbc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2udaivpaw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqvlkvp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzurkdbi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnzwvvd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcxkqzb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rogvbbgv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2svjdqamf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qgltkhob.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2abjtxdgg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2loxykrbe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2plzttbvj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2euylidhe.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ouavucla.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxdbwez.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbybrcwp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbjejgk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfunkfyh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzggdnw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpfvhsx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2urjmfade.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwuawoz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwlhqvw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pehfokmf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2galkrkwd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2khqwaxds.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmnockg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcznuab.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnuciqe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiiahma.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sggtohel.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuybgpbn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqnxeue.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uopfwxni.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfzsuup.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfaqxuxi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2crjoyikf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2awpdrmzz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2slwerkkn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2muidkkqx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfnirks.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2btumutvx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tvztehyc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2spdprjsm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyqfucl.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fpanyugr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmdxuol.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ddoevhfx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2foxtgrlv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmiltzk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qlipooud.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgzfuze.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnxilby.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2acanmhnm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwqowge.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2uigbaozm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2woppcrtz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2peafbrea.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ualnbqxk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyvhgwm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qprjxvys.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uybcgqah.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2irkkvqup.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hoifwinm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrdawxm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dstdbigm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbcayax.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlaekjt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nldpcblp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtubgah.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ityiutlv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxfmqbd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2momuwbta.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfxncdh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnenlio.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpcvgyz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2waktxpvq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2twzvjgpa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnyojit.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ejobrxts.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oljctbqf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2etazjall.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2txfldxbg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmclfcfi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxylxgs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kaorqbnt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2inxkylqf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2egjjrslu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhqelfm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zblwmjuk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsyfubn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdzhvxu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzhxjkd.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2pclhpldy.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2isclayan.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2msegfnfy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyxpdgt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2raiiwakx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2npfvdzwy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mizxkjtl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqudcac.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqoafym.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmzbydw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfvrtcv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2opcjqggi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fijlixum.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2punhsftd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jempskas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqxcdmo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2anblfnvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdomphx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hahejmju.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdvnynd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbfuult.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2svqdjppj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pqahmced.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfajsnvb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2oetprezv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqczewx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xzeboxxv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2elebcdmm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbflgen.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnauvut.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cemiboyj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2odqvzvkw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oramxmrk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2twfqfejw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzpkagg.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcwmeba.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrilcrg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkhjlle.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdmvqlq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaptcyi.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rfathhas.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjpxsfz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pdktnwus.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcffmts.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpbfgok.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvjnlbu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpygsgm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmminuqh.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jemjycjm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrzpdlu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyzxjpw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqnvsoc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcecrks.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpeiqfqp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dajmxorz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2svgaafsm.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhsdmmb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiftetum.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yplhrprl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmsufqp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wycjurgk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rykywbhy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdxmrpi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjimwmhj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2edotlfps.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnepjxz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuoreek.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdxtdyi.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtbened.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqaimqdj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cjeelohe.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmjacdh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiesdkx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmiuaog.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdhxfmu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbarhzd.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ganetazl.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqqiafe.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2egdigrnw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2idvdzzht.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwidvsw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpgelyf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jparfwtc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiercns.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2alvlyoqr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzewzls.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2umdplhay.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiuxkha.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhnefri.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wykjikun.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hlaufsus.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqdrnzp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzjoyim.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lykaapso.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2crgiqlyv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcimfaj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhljloj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqlamux.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eawxgkbf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2utdaodcw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcmmaka.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsnjbgg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vitivryb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddodkcqy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqkyjdr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npxrffkm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tstetjry.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuhtgqd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcwmonr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfslxbi.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvkzccu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwodbyhn.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gukrgeua.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrsvmub.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrbxtrl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdythjuf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eksnteoz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyippmz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2giuspowl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kccmkrlj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgawiba.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2waogvhir.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mizpcfrx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpydvfe.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zersrqjx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bludeafm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvspriqc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2olsfjieo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iidvkqyr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vngepsbz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhdhooi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lphvrtum.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ialexhod.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2obcposkq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rbanktjb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2brkccnnm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxctsehj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rxislsyx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvfuptp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkekzidf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2soanoncp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovujpbuj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vstvpqzn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mpksrmvb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkobgfx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwppiqt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfjtbkb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2imcjwies.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmvxepa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2huusdajn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2yveoroex.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvpwvun.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2krlyorob.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2iejuvnlt.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yancaojm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2douibmyl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjjbxuc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyktlkm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mykizmbs.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxumdkd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoprshh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kawfapjd.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2spphqzqh.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fncunezm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2htzsazzn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwbksje.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjpgvzf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpastbfk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lclsljtd.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuojjwf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyozlet.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssavonjp.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2czauqvhj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2iapzwcac.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjvzsgi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2myewwsfq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcbzbdb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2emxagkpm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2erjbzxsf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqjslho.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2eypxaage.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2echepebp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2clvlaqvl.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2abtcumjw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ncboeqgz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2yioogwvp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezchmsbe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vjendlgm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqwdenm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzofdias.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqxzvga.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwgxrkb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrbotlf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qucbptjx.html


<!-- 参考信息 -->