代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2diwgglno.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qzopuqob.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kesqpxfc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaibpdb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkbsfms.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2szigpnij.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvajpqxb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urnqantv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2aogenowe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kccifqao.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdzbhwk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfqeosg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpwehud.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvzcnsd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoprkug.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qwujglqp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqxpbqb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkbxmqq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yykodmoc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvfpdjc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2txdytdeu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdxqipa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrfchyt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kiowmnrh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2weuialqr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2phyjrepc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qajclwtd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgehtac.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2niyuvfxr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2augkmqla.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlaxqzb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvihsos.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfrbitk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxklgccj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgwxoxp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2otibwavh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2inmgwoke.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ntycvfuz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2npmiktbl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2llzsigwr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcodwkny.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdlgxsm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyjvvjf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qysyzsgh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcbcibp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpkwsnf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxjkewf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2umlxnlly.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rbasfzwt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdcdidy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaseati.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzqenxo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcwjfut.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nanshvai.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlezznh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zsehecou.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrzeagg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2taoocwmx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2btsxyotc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zawhumvn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbyjupu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvciesaw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gegpdyfo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghntnzih.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vemffsih.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dywtvnzc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wtebspra.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsymazc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2emzaeigy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjzlbac.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2riczuhxi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nycuffsi.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdwtlzw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2khcvrfux.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvvgyqq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tuagiimh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjwnlli.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2isxjbhaw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjcyyqj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbwlcam.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2leoyehdm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uixgtgsh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2msluxcti.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sddyoxmd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2veddgjlo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aydnitfs.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtkzmmg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsnxthn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlyagjd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hqooxhxa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bptiwnbt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sctogans.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxiwisqn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsmcigv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxhegjk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdjsoup.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdrldhm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xldlshnu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoypnaai.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2grpfhimb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcuyzui.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtmybza.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2voupdqoy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2orrrpmyj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgfobva.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2buhmasll.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzubovd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2trtkzfeb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvtcwsd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxqbjhi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjeqddb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfopzzq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhxcrcf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgwsnjb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsazuvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nqigsshk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjogqcy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uryauuiu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkbgnlo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwocist.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrrihxm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnsfmht.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2trlnxzsu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeemkhb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gspnhemt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yloiowed.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qujsudjr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbdztvu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tyklqomp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddioezqp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqvwuwt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrwyize.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2htktrlhu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2saqfmlzb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vosaokgi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvstmqg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zgejjhgg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxrpkmf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ijknwagq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lobqkvxi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2snzavffz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhsnnmb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqsiubz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eigwebmg.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqnenog.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhjigpp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2izbvzuxt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkxazcy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2phkbwgnl.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pudqyptz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rppftycw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqojrhyo.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvkkmiy.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfevurb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdxfktu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2huvqjcup.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zldrkudf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2smvipsjm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2trlkbhxq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhlaaoq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxofvkrx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2slblbcme.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qhboltft.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpifcbml.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcqelil.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yryvflcg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qupbcmew.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnyffas.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zizairst.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ephmsqob.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbphbiy.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2boyiwymo.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bakhwsvk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcnjsam.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvrkgmb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgvqtrr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxjpjxu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcmzgac.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuugunx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lsadtiuq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbpkrgi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvmrwqm.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mengfiba.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2iyeafzoq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvrndma.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfsfjxw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzooqrj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2nencmdad.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2aavorjnj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yixiafcj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkzofxs.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xcttdgoy.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ydveftrn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvpblyr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2defmtmzr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2updwvkjf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuwquin.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mlptsvtu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2llfoglvw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cziwqvpx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iukemcyg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rofmxzzu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rlafbjkt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyacpcx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eplruhaf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2illjpwof.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vtawuuzs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acbpozkh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrwxsfs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxhhpxp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqcxvjp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2thzviohv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwvyisc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hckvzyvx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhpcphi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2iumekyfb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wufpqytp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjhqscx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cufecdph.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfxwvyy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzxaezt.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xujrqxcl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfnurpj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzwwmoz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwogmvzi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2icmvwacq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2luklkhix.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmubiiv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkntnvoe.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xownyfed.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvpdxla.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpaxdqy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kylwganp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmguwct.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqgyyxi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zxftotng.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqsnbbi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xemasltm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuqpvup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2obrgdhdt.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2umtimezq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rkiyytek.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqwdent.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpypova.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzbwqku.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhdacbh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyrsqpc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uynoxttv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2effhhtkh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mcktjtcx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpvxikn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2djhfxaxy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2xmguosjp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2acguygbs.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlakrzi.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2bnskpofk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvepaxy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2knqjgqqh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxyudnh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bezqurfh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkvjwzi.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvaiuoz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nmieiccg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyvqjej.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoqfbgw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bohyurtr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgivacd.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkurwnt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmuvzrh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhepzec.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlcrkik.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzboqerc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lgysuitc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlhamqz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrolimu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqozabnk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyvhrfr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iugeykiv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bfchcama.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2letddfgu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrpatmy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwkaikm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2sulqurqh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bndwekgx.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szvnevhq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2fjliymyt.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qmugrcyw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnpzbea.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzbgxpa.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzwjlgo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qachpyaf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2uutgajln.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvvxovd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2itwuwvkh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mrruxfjg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2luaccrxh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnbezui.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jadtaagy.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sxejmasp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2huelwnfq.html


<!-- 参考信息 -->