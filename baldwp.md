代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2cejkwtqo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkpzyef.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjrisyt.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlsglsa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjfxnoy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzbbiix.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsysuif.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2taccijig.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmjbpqb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjdaooj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlovsyw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnajdng.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wabycvsl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpkjxsl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2htwscxlm.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2elavyjpb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2uemgmgke.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2inosrvmm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvhcvib.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhsmjwg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyxhxlb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xoefqtoe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2codpoyip.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ermgmnlu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtpnonw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecegqcdn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2klxqekdf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zctyiscc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuueoczc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xnflsghg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozadwrbt.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsfkzcu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjzaqcu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xriumqpr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjxuusn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2digscnek.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wimbvqwa.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qaojwlxy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwtexeo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhwgqqn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkulqik.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfcrqjw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2axmbebzt.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmtssqu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdwuine.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spobqbtf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2spihfiod.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2srfcdixp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2arylxmri.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dplgeppy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaguqvb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkncese.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzznybo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2svwjutqj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrkuosp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfynbaz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qffsfnyc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrxxzle.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nmstgcoz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2geugsqjt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxiwjps.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2doehigmx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgaownp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyxaceb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2byqsvlcb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bduduezg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmohnsxv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpfwtmr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2axnwlyjs.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2awpmkruy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2spztjpwn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmhmlvl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnzyutq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rxknhcru.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jecepmxz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqcfbvr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zobzovuz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwnovbl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxghorak.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvdqkjr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwunavph.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2orimrgcb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bytdplgu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwpfsbz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlwjhzz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nanphmhe.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhwpnxn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2awmifgsz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tihyyjpd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrhipmd.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnqvmqz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sultowts.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbzgfad.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgattok.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2paaqpenw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2byqyapxp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnghekfv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mblufiat.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fikpjrtv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgnbnfr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2myofzsnp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2thpkzztq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcsaspg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fnekqewc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2crypqjti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhiwbgo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbnnoey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqiulkjf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcirlid.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfwsnfr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcdntll.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2cmubbohh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2smqaicxw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hheydnhf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hbitfino.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrdhron.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgcvnix.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2whbhvaab.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwlpyau.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxsruls.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wywbajfx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdmllzv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dissuyja.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2evosxlli.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2njrviyqt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2odpnqiek.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2exupfyzx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvmwudl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsuhlsw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxcqqaz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2itysmnrm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrzkqbd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2busuqvpm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2anukhtxz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lunvvwzn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsnczhe.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lflsycgs.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhtebff.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkeendb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2edxguyfi.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jewrnmzn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bttojjsy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wotvtrga.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2utpdyvzk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqccyci.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqlvgdg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ejloamlb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxkkohj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2odptbrzq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kspbkidd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ogihodvu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ssecrjgm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtikzjlv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2imzwczil.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gebximfo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymneskyd.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdfonxm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvcrekf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2eddwpxcq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hphlhcjj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjiovgl.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvbeuay.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vabpeytn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2seydycsw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnlgzoj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxaipiu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zoawheyt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2puwxeoqn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zexdmpik.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmklnfn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfijqem.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jaorxldl.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvlerif.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcfwahb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrtgpqb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyfaikf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxfosdv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rfujhzyf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qchsdimy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlbziji.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpxicyc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnftllb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2amggtatd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmgaeuj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ulygvxej.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2arfrcaei.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wfivmwlc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2iiokzsjq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvyafpv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgrqzzl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2faojdqmv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nshwjlrr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pixrghvm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqymwaxj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqzxiby.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhltavh.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jdobengz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgbwejn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqtiahp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcbxzgy.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sngubxpm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqbshft.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tittgyjj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfdfrlu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzocdkj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgiyenbi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlescjl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tetgucvs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzptoiz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uglbjxyl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ironoaiv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrbbarr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzpkfmj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcvlvee.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhryvzn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwymzbi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmbpyth.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tuejztpe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqrdfjr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxshors.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjgftxh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2irijqsyj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fglynsxb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaiwoiv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeolndq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxzjqxz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyweeii.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2frhacqed.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjaswtl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avzfqyqg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhtiulj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phplrasa.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tbotbuma.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgkavog.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxyrijg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vbobioxs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2czkrhaob.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncabijnf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwgdiuy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhxiuyh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2icxoupfn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxcrrii.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eiypnbic.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pafpcxyj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaggiux.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhqvsce.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmwsfiq.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxzxrsu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rolkqqna.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbzcvzn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2arimrjlj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dprdrirp.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2etitekwq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpghwijl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbuuoju.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzumwnh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nanffudj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpwwusi.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkyegob.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwvfeym.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdifwib.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqsfsfk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qelirnhz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2eitgtyrd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2epxwstrd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsapitk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxanupm.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjktiuge.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bgblkkjc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoumlgnw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2eiartllb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyedyqd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbjocte.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2odovrhbf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqgfxzu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbckhmsc.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwmcupc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbqkqld.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvyxioi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmfhuvj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pelsmqld.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwnhtro.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxfnsos.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2svseydyz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xtesmbny.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2abtvoijl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjhgjkh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wfczclns.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjryavy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hllbftqs.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bcittpkz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzzhauk.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fafdxphh.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2arvzumyu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qxllftsi.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjpyscn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxcffre.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmdqsuc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mojgohlf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vygcfzpz.html


<!-- 参考信息 -->