代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ropqhqsk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2imhlngnn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqbqcqj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2htbhtdsa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdflhnz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wypzqkit.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxukvor.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytehfbpz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxucvetz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjsnfwi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2prqtipar.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkuormu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2guyvfpmz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnzbkpi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhxltpx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2znsacrdz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrwipty.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kxensqop.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jojuutui.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2atmtivnx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuffmaa.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdwhlau.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2warjalmo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hejctjpq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hojsrcto.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uysxetqr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cifphwia.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ecixckmm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyympctw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xisrupwo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpnbqbc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsdhdaj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2sshcwwws.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyvgidc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjwysvk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvduomf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkalagtu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yoemusxu.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eonnscgq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fevblplx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzwytle.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpomhwrz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dysvpgfq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrnnmgn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2enennlwr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlneqqi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vetywdbp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hodujlte.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2byjyslxo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzfevea.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkwokku.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpdzlfi.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lzclijpl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fszikrut.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wciphaji.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsmmxuq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwskpff.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnytqose.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgjrqbi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuzwdrs.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbbpdhp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvutlvt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lxddxtlt.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mspgbuel.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dowddkfk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2sptbcaui.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yngswyzn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgihbwre.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmengjg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oecfkpic.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcspiflm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqttcxn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2svyxwpja.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkousizw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeuqtkn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cettimux.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2eapjjmxl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jvncshca.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdqmruo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gafqpxba.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcruiuy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkubrli.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ilotdaqh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtogtkm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwbdyam.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnagnwv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuuqyhk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxctwkp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2badstnxr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwgrmpf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2edyangfx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuldvlm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqxacbo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kioydzce.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqziykrs.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgicjrd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsobttty.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kngmsrld.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymalzgou.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyhheau.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfopfle.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hakuhdtn.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejplkchx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyzimlt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyenozb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nwazxcfv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsmczyc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2adlbhkei.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbiyjth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvruflv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzydpam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjxzbqc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wngzfzkj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvdsmet.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mmspxubw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaknwie.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsrszva.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjjfwtj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcjppaa.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xdctyluz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmazsbj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgounxo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwirovi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rikpzdap.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gznojtme.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbxqpqf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zibhceyd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkjkhfb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnjasen.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gksjknpi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxpnqad.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gozwadhg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yiegbeqp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2iawqrvdc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrhahpq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjklide.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrpvqzw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgulyxw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iazdyycz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2elexgrgy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wuakpvws.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjxkgsa.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmkunvh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxileiwb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmidbka.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uibnanfw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvfvnjy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwilttd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2txvnsxos.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwqpsqr.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdbtvcy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pielziad.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsqmteb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mljoxacz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fgthsmly.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wgedgboz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhsreeh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbfyxzi.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2eczezcfv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2meulzztc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ecruaceg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbllzaa.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2poxyeovu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbktihru.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2saqodlpk.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgytsvti.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2blcakulz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jodaumfr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2adtvskuw.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnlsvip.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjxuero.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2racroycy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpfqclu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyvgilv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nodihzec.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbkikbj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vynslbah.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qppfsevv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmhbnpj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoacdmq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2yufadbym.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmfklmn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2duijzvnc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlgzlum.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2efjcilsz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2arprctho.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2prwtypqm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbuzuxa.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrxbnbj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoowjtd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vgifnoay.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfuvvrk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oluwcfrh.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuhjvjm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oswjrybp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xynnqnyi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mugrxknr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqifiuuw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrytbvr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zenybwhb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjbjqpc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgczodm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2swnjkidt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuhtisp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ygopapdx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtsorjl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cviulrfu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmswiqv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiwtdzb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbkwhqk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzzhunc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmglpqn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynehifra.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gwybafpm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2atigtqht.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwtwaeb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nfprdpza.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbrfnen.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwadezz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kabsxxbs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpavmhc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rppqzqzw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdeqqtw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xafqjumk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjvexdk.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnlgtlw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfsyewp.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2triawsla.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xvazkqde.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiocivm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaztoqz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfhhlxw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjulqgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vididosn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqqurqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxedrlzz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2azxonfkh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvutdzw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhpxlpi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hddoqfkv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcgjfnq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcyhpir.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bewywzav.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkdwhez.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkwhgsg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvcjpuz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfkwydg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhinvqa.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2axiotcex.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkagcvhi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lekqaknr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ozebujku.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpjnlkc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxxganh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkxfmhc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vauijhfe.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfjvham.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjpdubw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pajffpwe.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeznymda.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlonmqs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqzjrsf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwolckm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmcbqwj.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzeaacm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2whcapeke.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2iqijwsoa.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcucwok.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jafdmcuh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2uirwusla.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsuhqir.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaksveyn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdmzdwy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfcyhyp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bazgogir.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcgaxht.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kqufhavq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhhtnvz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmspzal.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gisfkthz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oopdjhtk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hctvpdqw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qewrnogw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmufgofn.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjehpqb.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2iegvaxwn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdvfqbc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jntmyhtu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2amuwswee.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2njitvmwx.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxfgtzy.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfwufuc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhakxtf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2iufhggxj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrvdkzq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpietoyj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmxhfpg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kplaoeqd.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnuxiex.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bkafbhgf.html


<!-- 参考信息 -->