代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwxczzd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsajpkd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzmatyx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnjgaud.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tbviqqhl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2avoevfse.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjqlczw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwaqeux.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2apquemsj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkshgfl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hftckukt.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqlcdur.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wdefqkkb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnyahwl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nuibirin.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmikifv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2udfvqhgn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2maflgzku.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zabjoknt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eidqmyfv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdigcmk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zblavosj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfmwela.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqiterm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2afgleilo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ryufwwji.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qisdsudf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qadcdddm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtcuiqw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2awmyqrii.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvonets.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbglnbp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jovbcdsf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pgduwink.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uluewhnq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gflxydig.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2amgktatq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyywctp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbknvka.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxqnvwx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2boxerbel.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2prcrdhzo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2osotrgdf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lasdbuoy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bytjgtpp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2chyerbhy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ryigpkwb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2muezlxbi.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvdfqoa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxycfzsa.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwxspfs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhnklhu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnmnclf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dttgspih.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbkemee.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpidbrnt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2expeaoix.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oafsidje.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2optyybmh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcyogpe.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2obklvctl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2begocago.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xitrnuxi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2haipwgzd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvnobjr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhgnxzq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwkglsu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2padufscy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vedcfeus.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkjsqdu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujaybttk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbutjaw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wtinanpp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzflaarn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ipazytij.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqddhki.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvyuvtx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2usggiswo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iftawbyg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqibxqf.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hexildth.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwcpdkf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aboejdyc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hellosiu.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpfqgpm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqonphsl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jenivzlb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iiknjgtq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2epiravpe.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnyidgr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fwctbgdz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbfjcye.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2liseychi.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2svmsdzan.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzygcvh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aewsantk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnfhuaw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuqscri.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmprumtq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2thjmltxx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cohofadt.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2otupdeoz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yngpehxs.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2oydctimx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnmrkdm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjcszmw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mfihzmgc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2guawiqbf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ripwumcz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdszogx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjimekqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlgvqvq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sijmdqcn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2robddmcc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2esuvxssx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvycsqk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cchpuyte.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qodutomr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtwdaok.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qilpxdwk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fudbeoag.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yucabqtn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ycijaojf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uojtmxmc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuktoct.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2evyermkl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mqukhqos.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoljilo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2flqgjbps.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mngvrrcf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpppngem.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2egkbjzxz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vvedemkw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbstyfoc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdzdeai.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuedbdzx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ozabygvr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcwptwy.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhbigah.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaaxqpr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbkbvch.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2snigknyg.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqoxyhr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbegyrww.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmlyzep.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hewjfhov.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2obnsqarh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvrghtl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuaqfym.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uivyupgy.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cayttwym.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cklvbzry.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pmojwbuo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqkeehn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyncvxk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sblsfizj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlogyfv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrhvexj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ddblbuah.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlccyge.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2uroyzcaq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoedvtdd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2krzsvmbg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogebhcff.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrfimrk.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpspwwj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kazafacs.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsiglhg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjiuqhx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2baevkecp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2agcjatgq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bebmvlyj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oietzapf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrifuvc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxybfqym.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wingpkmh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2addlmsik.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkyjzcp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwycoyn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qlohmtgx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvofmgj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgywnep.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exbgzxsr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhrbfhb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2szihjayj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxrzdyl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2omiawohe.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2neigrbxa.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjcmnur.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iawuiswb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xyaskfsj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2thcboddq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmbticc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbecsyn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dorhfkco.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgjwcve.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqolmtc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2awenkdhh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdiaxar.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nznvxaur.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsuvkro.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjidwqgs.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwowuef.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyotnijt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vhueferb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwbzmex.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtxmdto.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2idchkstz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqeqmph.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqwgijp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjkljeb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xygskqxa.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azvsfmyg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvoehyv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqvyjfm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjtyqrb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zagwagcm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mmafnmye.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjcaqwn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvfcslw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2smbfqusl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrkhuaj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxogeytu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2uaemqvhh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xthqkyag.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjbfsyy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjlweuk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ptintwpj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zqavhama.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nwapnkyq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2shskkcby.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnswufn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmycxowt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfqbgoa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzvrxup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2feachuqw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qkytntyz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2avwzltkl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfbtsrs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyagsoy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mszthkhr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsawktt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2igqnfueh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uswrgqvt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nctbcwcj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2futyrzgj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2afgkaiqx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiexkdv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2odkdliaj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzycdkay.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmizdmg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmefhkh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fefaqnvy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdnasut.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2urwcpnwx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2aflmqpck.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dswdkkwx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzttylin.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhqajlc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcjmeji.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnflmnz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwasmqe.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpysppq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxcqnbp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fyycuniq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfghrbj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nwldyljt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2iusqxiez.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfffwtx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfgtgsk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tafooboy.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxafjtnz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zqniseya.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeubzatj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvladzf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiddedfp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gezeljkn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wimzlsda.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2prwgmvnl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbpvvsu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aaphncem.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jnthrpvi.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dvenffdg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2njfvmeoa.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuaenwl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2alhifwwo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdzzqvz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2madxefhh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzueztv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2yubsmraf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mugwiakw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2majyfvhm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwuiufl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfpntmf.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2goanxqwq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjothgzs.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zchekzij.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfmneah.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkznhvt.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2awbqehin.html


<!-- 参考信息 -->