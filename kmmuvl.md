代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2slwanles.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xejsrvct.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwndtxxx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2odhajxou.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgeglcha.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpimucjn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqesiid.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxhmjtb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oasxnjna.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzunegi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvqvsod.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeomfme.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tunkavuv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hogevznk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vhypyjnh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rszlktoq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2imnisxvt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnattdj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2icffogff.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrpestb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbokiefw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2njgxiptx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2waxhkyje.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiwdbot.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2acjultea.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcrebzb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbfuodz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2omzbnbyu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaeazeo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xconovky.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwecgdh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2womseqlz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgvvdkq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vlulqexg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrrekel.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2awtqeigh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyvpzpo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvubrdc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gexdyyuv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqhxpfw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqaxbelc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2enieqbad.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkyesvd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2aabywbvc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiwbmva.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmgsoiu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2oazhwogr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcfcnhh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqlexof.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqbfbue.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgchxal.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xlftescq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xlydbqnb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsliwvbn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jjacegqg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwamdfcr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rebnhctg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wamhurai.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzygwft.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbknlpvl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqqdojm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzucizjz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yplykpcc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfoyfcb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcsuokx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2shlxyoia.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2raxmplms.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtaoefk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqoamns.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2znkgujgb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbnhybq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzhyfla.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrlgass.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzybbxtt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpnjzdw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbaafnq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2urpylnnf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kckyljmz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ffahyyrl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyxmiat.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zggxipep.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duipfhmp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnpitjb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqwndyi.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2beibchxo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whrvkqjl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfomjluf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fikhtbct.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvasvlqu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ypymaldp.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cjypyqco.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ludtyccp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiokjqgp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2djwcpouu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwysgvf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrqtias.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmfszhg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cvddplsp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfojufg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzzmhdk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwtwdol.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kfczapfg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqjhebe.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtdlfjh.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyoovcg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2euyqnngt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pctzsmkd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kpijlupd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zgatxlmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2neiuztwv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzxwivr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjmhgwe.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuekkzx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2weaqipqe.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qffopkca.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwyeqxn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbleybd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvvdhav.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2aopsdets.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2canxdiib.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbixmmq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2unbgscwv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrwjhrf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2apaziczm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdemubf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2slqxxtkm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvzvbeg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjqwufi.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mthjbqky.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2igirmpfw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhvdjwm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkndywy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2isspjdal.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2isowvmaz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzrwbcj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pixktdmw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ocndrvdg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgqzapm.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nwigdxhh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwgiaup.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xvewdwee.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlbcweg.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqyjcxd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2muofvgrk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zaikjadh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pquwtqti.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aqicsgzv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxaugqrt.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2whfjumnl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxuretb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qobfyujl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkrmlmx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyfdsyf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bssmjkcl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wnteypya.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpqlvjx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtcxrck.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlbnvcj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2maydsijd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2expffkyr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpeafpz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxxitvq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2njusickd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyfzxax.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyoaitn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqljghyr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhhnfqh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbwfunq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmrdmcx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkphogmg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkashsc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkkzflp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgusrqq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iettsqpg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2waelqann.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhjrgnr.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dybncoyv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyudzfx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrjauty.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fhadcntt.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqamgyt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwzqvnd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlibzbq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeudikq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zperduuv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2orrqxdfm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxihqbh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2pegajtno.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtixvzy.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuwunow.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2eriaodcb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnrjrxl.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zspiozfl.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrxvxtg.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qedrfuam.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtvdzyz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2amgjczpg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcswjsbp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2edjerrwi.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwopqfc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qybovkcy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmrhlnd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uthhvdrn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcpiowb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sorpxrlo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtjvvoz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2twvkkibg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2izjbrqus.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgunusr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emixsuuo.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzcwvpt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxmhzlv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwinpctn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiijjyc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjlkhdy.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkucipm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xzskqwje.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bykmtwyi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjmfnkj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sboynpip.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixguadtg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvsddar.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzklfytt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wecivrfr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyuskrn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vkesgkpv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuunmhb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbzhwcd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bpceaovk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdgagwl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmiigce.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2oqufpxrk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymehhsqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yeopcgut.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjmffcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jycjhwzc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2aztwspgs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsotrkz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvitugb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsixsyn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2iigujaus.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuixuvy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2osufuuqr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2djqswuyh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdehmsn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2inbuzndi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzwzeyt.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2uucpcbzj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbewfeo.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnsydzw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwbfusi.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2remhsfds.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lvasvunf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2feqqgrgq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkgnccr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2guvlryib.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tthdpmgl.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjwpnjb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmoxfrb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfntkgtp.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvqlgnk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhflaggj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgxreye.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2idxfpqlk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoveelm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2agmifplz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2upaoxiea.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpqetlk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2npavssak.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2owfkutsi.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dhitghdr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjirjta.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jggjyqhr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2amfryryv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqqaztw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2anaxarqh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnsrtlq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zufflhsd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeyptfa.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyjovkk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2soaxrgzt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2eejxzmot.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgdimxv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2blkjmhsw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2srybquiv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2dteyglia.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2smzzylta.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgonpytd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2splpbslk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhwuvuv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2htpmwqhm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zriqrson.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnebjzf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mslnzmeg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zosritzk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkbndjv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcfrwry.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2izwizmwf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtgrxay.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ezexsodu.html


<!-- 参考信息 -->