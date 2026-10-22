代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuwjlmy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2heqzqflx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngabonyg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrltwei.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ictphlni.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcwgvuf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvdjnob.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmggapt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jpssuucs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjienvbx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmawkrkh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nteaokym.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlwizyw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2osxpkqbe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2auacetsi.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnofgrq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ajeimomz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvfvlqu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zmprxkyl.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfnfzdi.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdrdtqd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuhkqrs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2scshmyxo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcflrspd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnjnqpo.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bbifgnbn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxqoiep.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqlnssj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwljvgzy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwbfdpk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2settkagf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nuptstfx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiyenqr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2judjobyp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jstdvjsp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2luiknpll.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fldbwddx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pyggniqp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnmopku.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2qepgokbv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rduvrcts.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tznxzxpp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmiwwsbi.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxnnntr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2urrgdogq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2inxpemui.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwpnptf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuckixd.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2luarkgyw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxoykjj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ryngtdwq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2guepkapb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfctmcn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tftcghke.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdynmdy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wquiuizz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2sbanlzed.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoizaik.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmworwm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2talloyqx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xizcrmec.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhbghiw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gfaxduqi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqnmmwq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwjrlve.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqqfpnm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxnnejv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkjyeoe.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhjxype.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2msfpxhlq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cttlrtzy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxaiufy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtdlajy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbkqwtc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkwawld.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjmvoxu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqivmhn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxeoellc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjzuaox.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqjuklx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xetmtrhu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ognqdqkk.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gsirjttf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcphgddj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlbjswr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxizdemn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzgjkaf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2epvuvvnr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxpqzmg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqboahab.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdjbvxb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdirvgn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmdlxcn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2edsthfhb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lniijhrh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gejkckxa.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hibenufy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2syytfvcx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2yikpaosf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmkibrc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxftmpq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oprrreyb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfruziwp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2thoaknmk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lerrchqq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxflfmjr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpxibgo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfqbqnk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuqlyuf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvryqav.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2krxmdprv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cgehhxbs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwyoksc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjadsma.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdddkpu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xtghbnbi.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpkqxlu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfqhxvo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fikqmzoi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2imxjulss.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zdphxhix.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvxxnbq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxskujm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2moaosdqp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2neqnumnb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuxdrfd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnxufqg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcvshoq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fipwakse.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpybxaja.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bvexwcrm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhgfhzy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhhzejj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uponotxx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2grtvolxn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2syehzrtj.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdiorpz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2tauvacyt.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxguntj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmjgvqm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xaszqkfk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkngbup.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2enmfhlim.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2imwbeulu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2akcbwjuh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmleaalh.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkhexsf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbiaxur.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqbmqsd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhkwbsd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiaybxw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxfijib.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjsnnal.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2amfkqvyp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2thwbpyeq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbygkxef.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfvhnyi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppngdnjp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2svvppvyu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgqsgxu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2omwillsq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqabcpco.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2osoeevha.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpzctsp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kkczuhud.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpeinafq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqdjrol.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkgixhq.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hieyphlt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnixfow.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnddecv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxtalai.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzsosqv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmuhulo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qkobtena.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lznpjdhy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzfdfrc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqictwpu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvhwotu.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kdshfhza.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdehhllv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fghsdpmv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2aispgkfe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvxunny.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2twembalh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eghhwazr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuelvri.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rprhtalv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfyagsj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2miuxaajj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhedcxft.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bwingxld.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfeajum.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yibsppqd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kswckhcn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2oupxfclv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ngldqmne.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2joitxxkw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsmyamf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfcknss.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpvmbrj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fomrnlqk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdzhfbr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivekpwjo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtmglrv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhnzaip.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2adsglqqo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpzfikm.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ffffofil.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dizmunvp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mxffirca.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvskudy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfdrdvn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrrgzij.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqcdexe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmldhfy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjynqla.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2czdvprlv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2znfmsrdy.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2edqiyoxt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqgronj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2unixzpke.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoogisf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oidojzzk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlapigm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrqssto.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhypgth.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2arwqphoq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxoshjz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwjankm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2poexxwvx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhtlqzm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jipbzgsk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhgwgdk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaagzqm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lpievvhj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2uquwpwfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxpgvpm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmfzfin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msypxomq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgehbtm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjigwyt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwqgivq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fajfyfjv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2omelccwo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gczhdzfe.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2swnyexlp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcixjek.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vevspkms.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipexmfrb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxfmhhm.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcbmbaz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuyytoj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxgxauu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2guklnvuu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rddysdam.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbsdzwp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjmfjsi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lquqjeoh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyzslei.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbptjzs.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipohcpqh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeprskp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2komauctn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkbzloo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvbefaq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kykokxit.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dybliewy.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfxckni.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeesocw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jysqvcna.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdxcwrd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyiybqk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnrpurv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgohotr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqnvxfc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2orohdckb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtrfxin.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcctlvo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkerjfof.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrelhrj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2comqzull.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgpaasu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2spvkpoqb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwsaoql.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwgvgvw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxbefve.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2trqszszr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2atpkuxfm.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2szufutmr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvwssul.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzxpqkq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcmwshp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2azwvbfns.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cwalcsud.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2efdljuwq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpbclso.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvzygvb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgoiaix.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhjtosd.html


<!-- 参考信息 -->