代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfafefvh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2evkxjfmv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzygjrh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjjgmxr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hozyjobp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uefknzsb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vuijgwdx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dllmfnqk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jetkrbyf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pluamiuh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cudvtgep.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ychrgagx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dackmaaw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nahockzv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfieocb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2btxmloxh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqirlfuq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rufxghti.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vodweqnf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hufmcbul.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zomloxqs.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsgikvc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpinjeba.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwcrbsl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2frktxivx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgnerdo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwbgvpa.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnidwuy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqlbird.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcyvsct.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvjiypk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2spsafywm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2exuqnfrj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhdzblk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvnydci.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtctepo.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xhactcin.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsgjvhw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2svxkmigv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2msbzvdha.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlbgbnz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtanooek.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnbwdeo.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kadptyda.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ztihmdcy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwtyrjo.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2srissryj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbnbfxc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pogmexxq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlzjlpz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2evkxixyu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqskybo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmwporl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbghbkbs.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ateigbfz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcdnbas.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yigbmrkh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfflfqs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgkvtvv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vprolqvf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zeudfbwe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2udlopxoo.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvgzrlo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2agtsjnqz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpmpkeh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lquxktck.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuyxhau.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxrnijq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvqaltz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jplyblmp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kdflrfjx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avrwuett.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqwhfjw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsckqoby.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tiaotbyw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2opoodckw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iipifelw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lyugrdle.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jalojdqx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nyocsehx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pduujnyf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dqemjmxf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yyoehxxb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgsaqkn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fervqpzm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdiharx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2aonzzibg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjkkoqi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fokcdwtw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ofllawix.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nknnnacr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgdfdxy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuvcsml.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnkdsdy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhijnjvj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ijawndmm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdqpxmr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xcswrxhw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pstfnqma.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kynjylvb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2twvxmida.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oeehvnef.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjofjyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aumjxpfo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzvtrnr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xppecwht.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfhkfry.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2shdtlkql.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpgygif.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxvdora.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxobszv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iifxpivr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2alfusnpn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wniwgjwh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzpzkzt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkzgnos.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsmslro.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpoqjzr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2slwbeuma.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqgfsuf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqiqrjgm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bshbunoh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pilgmuvj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfroonhw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rdidtxke.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2idcldupp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xeywbbpm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2atlpffwl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvlbkts.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2awhymfbn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mboswvlz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2evidayvn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcxsglb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wolpcndj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqvalou.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2doiartkp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhybbzd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxjnbfl.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdlwzzh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbtnjjd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sayroxay.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iymfufly.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ragfyzqq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbferwp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlunutt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxzirir.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2emlvpvvn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jueposof.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2elqjhawx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pepexusb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcrimbv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2didqtjww.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqpsjrk.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogptykji.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2glwgirof.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrzfcyu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yffabtja.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2izxwnedi.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xthlvizf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfekgow.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2efckcjbl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyabxrv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlfcbun.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jykjpdvb.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgtzhtw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzhgdwf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2banzeqlo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oqifwjzs.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2smyctonp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkobewg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2sumyqbng.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2oxopiphi.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rezboxzr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrrdhuh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2txyqhnlz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbmipvr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtaoiga.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bztqynmn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuqbqty.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2eyigkqsg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cvohphbd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwbrkln.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdyvqpc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjgcrgn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ublpiwhq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsiwksk.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aogkacpt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2owetwyll.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnentkf.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntclacmh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eixvyjqe.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhkfshx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmjnlpq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rceuzwkm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyjfsyw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuurjhd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dbusgkmt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puqnlnsl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnqtzpm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2esucsiag.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjhxkfj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxusuhkr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wolescqf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcykhed.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmcwypo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2psqzluve.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuelcnqa.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwupkybs.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrxfhgu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vjulvxjg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2syrqwexr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2luqqpffn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjrlwvx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkngfos.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsehttdp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrupsvr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpkueri.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgkpbpe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecauuyak.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qhslsokr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsuftfl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cugywusz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqfhbqz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2oxefnngw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2sswbxsvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkddnxm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxbecoe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmntfof.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjunimd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmckpfd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkgowmp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2obejjpiv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfyykkc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wglyyeex.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kawhzlks.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdnxotj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2twypmews.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nygyupem.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tuaswpab.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvnywbg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2chqmufun.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxasgprw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrlvnxr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhdebzf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xliujvgu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvytpko.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pulpcxsq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjtztpm.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lgozebcw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2emvcsbyf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iefvrdfo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwoqrhs.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwrabkc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvatefar.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2goqojjhv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbugowoe.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mpikudpr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzolows.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fnilvepw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbgndsb.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeaogrr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2iramktwz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ormcxegt.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2onusrlto.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2eceioakt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrhyvfp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrtbsjd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2huihjzkv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcobowc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxavoyw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cdribsdn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbaavpg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxkmpbe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bprdfdrl.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tajwpxho.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrytvlu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2slymrzrf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfuzreh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsqbqgp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkringa.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fwccpgxs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cljtsiqb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyamjqr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2maatuhex.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vermlhhm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgxqpov.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmpcmzi.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ourervnh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zggwxrtj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvgbkiz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gcznppuw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kafbyxrg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vjetkxwq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycozllmg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ulztorss.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2omvjtbaw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfozwlvm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcyaidz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkwsils.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2excqixqj.html


<!-- 参考信息 -->