代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwhbggs.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaoylvk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xljthoce.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nphyjsjx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vltiizoi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2txkonfao.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkuybqv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuzzmqp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tersjqly.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtlbxnl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgsftdb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2adqlbedi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pltgbkgc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnqfwqq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtvvboj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jukjijsf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2leikbfse.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pyobbexu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2llvmyvgd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2exdquenc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieviexoj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsnmqmp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2byhpxcfd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2spwrclir.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzymrhjm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxoixup.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuvghaq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2piypjiol.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2eckcfiui.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfxxefb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqlbujr.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgphlyt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fidfxmfn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ltphkeiu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaovjhe.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzmlbhx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lerrzrat.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ezixnupm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ectctoyq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvlrqxu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwacjyz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyvhnmr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tahbhjxj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxushfz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzgqkxf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkyusuv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lnafxsik.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeqmkpl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dieznkrc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhpjotg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qptrwuzu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rjialtbd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtqwmjd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2erovuhtk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtznzqb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxiqffdf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2stbdyksu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xflfvgjp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqrfedt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2szhvsxeg.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xorrztzh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jthrmtcr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2krpsrkld.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xyeunwsq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuzstud.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdqehug.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eddjqreh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdofbffk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyyjcwq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnvkupn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2saayfbuh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmufpsl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jgszuiqc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2godccnpl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsuyfma.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrhkefa.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2bamhuhas.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wmztzoig.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxtejtc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slzuvyar.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkgstge.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2witoguqg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrretfmj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2cubbuvev.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqnitea.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoynebo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2plbraikp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwdmxsp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcrhtkd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iwasrspf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjoepvb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyfppfj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rltbvndi.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bshntick.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrmeykg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqicsrx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpirfvb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pqirpnhi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkykosig.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjxnprc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwebxyr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2habqoucn.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2akhssain.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxntofn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xswqcxfe.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wblshenl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2llubtozu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmppzgg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gejlcfsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yeefvcet.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtkuhbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzyrxrq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlpdors.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2voqhxqdc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzsvmvl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdrfzko.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xkisksnn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuhcmwd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2czvwqmnw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uujgyshm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmkihld.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwkryjg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfwclhm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjgsjic.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dntkhewf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2leclbupz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jnewcfpm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2evtmoamk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tichexhs.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2abrbfqxz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnwgqdr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eagtcpha.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2etdzyfsc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyzogmb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmlcjfi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxexmtv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjwmisk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvozgdo.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tzopcsju.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgnkaml.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2druviivr.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ureneinq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcvaslm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwpwsio.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hrymzaxq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nbehnhtj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjvvmha.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoioxis.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmvzmba.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpiqpom.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtqxdge.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2srahypoa.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vwaenhno.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhzizuk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ppctizap.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdpeyro.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfjolfb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oedrgwxx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzdivam.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvockii.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfzxbpn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcpmkon.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtazwpk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjcsnbv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vaaollbh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2geemvymj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ybicxfdb.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuyjpws.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qgimsxzj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2adfgzkjh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwmrfif.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yioomzer.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2apkanmtd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrukdzss.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzywcem.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdvypin.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jscvhxng.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxkeiyo.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xijohbmh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpuwewu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2stzvhgpl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyqcayi.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsilcre.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2azndvnig.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2waiqskyg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2owdibnun.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zenvxznt.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqouzep.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qhplfhii.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwutxhl.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2oimfmpya.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwwkrcm.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmlzirk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2haoplyyj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kqozvyub.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcozhgc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxkwoqg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmgefpu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nalhhdbt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2houuxysl.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwygshf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtoncjch.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkkpdgq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpkwelr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjfqeag.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njtdeeov.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvxvozo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2djhqlhlm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ellizebh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fntywkuu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cocbdmyu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2aomyefgp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twjcmklw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdeqwqb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzebkspx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mghkkpod.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oizavfle.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkrmayk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmfireq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnlywoa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2voynahui.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfkmiwt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfapsmhw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuhimoz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfaihsn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjnsybo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2okvwhfty.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwcjhss.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvqejvv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzjycbz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2whxnxjux.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ouekfybk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fogkmoov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgyxjnv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvicwkit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whakkabl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nonfdzlb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnxxjtf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvrilif.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrolhug.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjuzyfl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2floytkej.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjennpr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2synrwszm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxhizvv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tggsuknk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lqljqhaw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkifrbx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tinlqrld.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvpiadj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qqksfsny.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyvvxzw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdksbau.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lssqwrcn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lrypttwz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2htbjgshl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkmnwcv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2todgwpso.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2biedkbfu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssovoeha.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbppuzb.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2snmuqztu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qwiixklr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzlmjjr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2elxnwmua.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucymwsxi.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2cplqordw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbybfmok.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ydngriqj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmddmxgv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbcoyua.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tocwfkby.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2etghnecw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2upfqiqmq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vaploqza.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2llckdxeb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zylsqygk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlspegj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjktuxa.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2haqpexyo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwochest.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2uucgxttr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yxefcjor.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2glwnfrcx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2amucuhfv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpraisr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtsutsf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtawwbea.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2btujtwer.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvyazkp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxzthzq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fotbzlam.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2skubbynm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqdomue.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyhiwjj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqnqufl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbyhaph.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsafymy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2widsfjqs.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2dmiryeud.html


<!-- 参考信息 -->