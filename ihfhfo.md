代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmzllla.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuunscd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmxeywh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfigfqt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2byoobgnr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2luvjugvg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdprvjr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxmuxpm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjsdjbm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rosqyysz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqkxmqg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvtottr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2slxtabwh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvjfjgs.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2aclpzsjb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ooejmfof.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyspguur.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fppeiifc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgloxve.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2muvrlkfl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjfbkku.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbmnfzk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgisrtxw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aucniwzm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkedawz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfnxvex.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2btcibsae.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsptirq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfioljot.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpihjyd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncttiidd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrqzjtd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkpvooh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmfmfnd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ublgsmfl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfwrmxr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2unxeiodh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmrwgtc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2knmyeiom.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2liowkxmw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvuixym.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2melimxbu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmptdicu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qzliknfy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2grcsyfne.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qaecxfqa.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dhikrfxk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtjagwe.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2scudejbt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khcmztvk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvzivgu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zugwpplg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2favwkdqh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yczyqlon.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxawezb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oijmsixu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yyobbyjc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqwmydh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2aoljpaew.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tobvvwvj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsfxccy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkaxgzi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mvinjvdj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqxgywl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2csxsqfkd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzyvvhv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2escergxb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrtfhyu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcnnmyf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpvvxtf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbtdylj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zumoxgjj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzoxzkp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvvvyzm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2imnnojos.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiqhnbm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdhbwxg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmwuabc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkdmkhj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqfnasg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vuukjlxg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cluqsmjn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igmtgtoj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qakmeubv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2akgyfeys.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2naogzctf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uublztua.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kppqtnjw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaobleg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2afirpqul.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcbvfco.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnskbqs.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksypbyyi.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zpptwqtx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmjsbxs.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kojqyxys.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2drnqjgjk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gbisjyub.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eylceqes.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2otbvurfy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwiawgx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxybihc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2koyijsjk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mephndfs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfmaidz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2aqexsjlh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjfadyj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nihlmkkm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dutkocmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dctknqae.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwkinxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvuxxwm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqrskxt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctplvqnd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ozflxoai.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dkubnvza.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmtmaph.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zeumtxpo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mebwyagq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2moqezihb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gzphpkyb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uupzkgzm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwudupv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfshfvbm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kovqmlky.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2msrbibew.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2padocgdx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2esiiuvuy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahewoqwk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2caitlhxg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvhygsn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzuvwrz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoqiumo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmthxnbp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qczheaxr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkttsxop.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbboawa.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcoqhvz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kyttxnmb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2whzzyudf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qpftowwv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpzqmji.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuqdplk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaxrpzc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cssfjkng.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uycgvaor.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zasflqgt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsqdocf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ukydlmym.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iosbuhds.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzrxtqi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrsgnlf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyatoqu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgaudmm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzgfoim.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqbldcz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2esgqwskq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2flkbkdym.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jttvflke.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqwgvyo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nljuemrc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2shgwuord.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjozrvn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfvofuj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxsrzgx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2epxozuxq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dcddzfbf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qadljnks.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbapyzz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgmjbqr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2snctzjwa.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjwabmm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eykrzvpk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2skjkshpo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwrzefl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2exzmxnxx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfxpmrs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xzeghjxe.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkgophj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeevhgm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2reasaofj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cmaalkto.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2noasgzdx.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pztgrynk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2akbsqzri.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cadtuapg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnfjnue.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgelqlc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zukpirup.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iprommzl.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhsksfw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xsigwfwv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oimdjyjd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2liwfrefx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2beflzogg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2knijnipo.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vksdchgk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdaepsc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgisahuj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wslfclrc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2shhwztyx.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rikpcwbn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ixywcdup.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqxfkpw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jnudfdfn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2waekmasi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwemfbh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2whauwiul.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqwntvc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mexwlugz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vyujashc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vghzqiaw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuboakw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2usxhqvki.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yatxpdvr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zoleceoz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqxaxvn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbazguz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqnvjlf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uqalocgp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvhylct.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2foccasxz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsceuauw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2amhmzpgi.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2avambicf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vobhouqx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzwpgox.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2unciidah.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xoapznbo.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rausuiih.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yebvbfvj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2edrkdyuh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyncmcz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkglejpt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2srhepiyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khxtsljy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkewwpg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2larmlbqx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dcavyihi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrtmqcw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcjafah.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlqnzes.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgogghc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkwftkn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qycghunb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eosaxrbz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mydjveit.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjsewjw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjbxnoa.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fawtrnsx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2angwcgbw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2mofxiadj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ztivavlh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2brpxwjip.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqtvjmn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2unooufbo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyxttnu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2etsigzep.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzqfwcq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pammobry.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wciiibmq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rusrldfr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbyximu.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuocmlra.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcjpenr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzpqilb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkbktpe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwhduwp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbwidqn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyrmozo.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdooonc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2implzatm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvwrfrb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2joyqsnps.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2yblcgjby.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmwhrkz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxjusgy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgkxxaq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2voirmtgy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmpdzny.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsjbdzg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpovuzs.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvlqfls.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbyrkgx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2yicakxyc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2stbccehd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqmzgfz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dilayhuh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2nddkadjr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2uygujciy.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zpewjhwq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpeepra.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbrfbbv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2duythjup.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2llsgnrde.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uahvpzfa.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2psfuhaoo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rwynbqcz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoggbvv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2qipwdukf.html


<!-- 参考信息 -->