代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnpszrr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gdztrmgx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvlzwjh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2syaarwsb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vqizbcaf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mcykzumk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltniwosz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2klfgoxja.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfuoelt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2awxlufqf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqiuaxo.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxhzwki.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsesucw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfjiuvc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvdursf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkwaedx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2auikspsx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnovqpd.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfmdsvk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrjjwbh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2efwuylzq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkayrpe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tysyfrmf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2idybryqv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vefmkfjn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsbpmwf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2guunaerd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsajooi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooagulxx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjkrkrf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2huwrbvnd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvhnulr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2negeqjvf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2djvgyiro.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2puycnaar.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tkidyqqt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqydjnt.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqjlvtc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioavxzpx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zxapcnwh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fedoftxi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqodbcrr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaukxcq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2odkullfz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbcpbtg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2olydviif.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2yurylfqa.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2usqwiwwm.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dehlzjsz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2alcinjwb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpocvda.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxmlqys.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqsbcuu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2saptiecc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyjvfmv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzpyiwh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fyemuxwm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiwpkdr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2khdchiid.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjmaejg.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2padvaveb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2trywmhpo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mudhnnue.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuhmhfu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fkezzonq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tukjwntl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2svhzprrt.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmxrdir.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqdonft.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvdpmyr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2flbvcaly.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdpsqil.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfospiu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnfzdov.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2btbgrubm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2djaenpuu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwmrxtk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2luisfbtr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mszkgrmo.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnmejdi.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzzbqpv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbwbvtu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2acygmftg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbopjysd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnedmxw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgqzivx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifikrnsl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2uowudcxc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sokkukpi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trwvsqha.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2azmbbtjy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhgnhbq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2itofqruu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2exslqxde.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2euychiph.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2krvlpuwa.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfhqbki.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xeotcnbb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dznwmzvc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgdnvoj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxtraok.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdozita.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkweligm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcrlveg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxoamwl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsgzskf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsfymyj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fufukltx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xughavde.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vlainayb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2butvjcjw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsxtaoq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2eulanuut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrkeqks.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppenwtea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjldnnf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2flwsneyg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcijusoa.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iibyhmbe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdkajfp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnloiqj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjultsi.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsyrfcs.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjlnwhw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbvhkqt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2elepzitz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hebmdnve.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2peocsqzv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oluetnag.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoinkof.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsixpob.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwkfofs.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yozaoslm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvugluri.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqyxokg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxcqtjz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gffoarcr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktraiouh.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfwguze.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2meqzqvei.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fakurcrc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhcdfqx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yejnzchl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fohmjfnw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2thzwxlej.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfshizdx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ladaytmk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxvrlpr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbfwgsc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2anlwpurw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhsoacy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdezeoq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqszjzg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nneqknjg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2arjfocwt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycybioms.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzghziq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrflcpf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjojfab.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaauvuk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfbbvip.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjiebov.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwerfwc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngglbtdb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvxeehm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqpdkht.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bvndgslg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebersotc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cgptowlo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpttedce.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2azumpnbl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdgjema.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2shtluhbv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nttyivze.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vydkkrfy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgjrgmn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiuadzf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlziyzeo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zypsxteh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bodxpvkp.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecletoow.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwgskul.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jgekyxtg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yllxiymf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rwidwnkn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aofqqpth.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2acevembr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2szqimmzw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbjpane.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeizqpd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcpnwvn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdftowof.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nahtdgiq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2avkyxgzu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2idrqowto.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hezbqvej.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcwbkpy.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fqakstzj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sdizdzzq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oovbmpso.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtjygfk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bphpcrhr.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjwchcn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ingyiwwl.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ujntnpqy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrdkjwq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjzjoiz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwojwsiw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2amcckxzy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoxjrwo.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuvndce.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2bprwgvcu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffedrxdc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brbsbuus.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcnbbby.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbymgjf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrbotho.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vbivulua.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbqrkqt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yafvzrqt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yyczffer.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnygujj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnhvvpz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxfqpno.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnscbxtj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dyihzaom.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdzrtkw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwftstt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjngvdpu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2syoiqgzq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vokgukna.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmvexwl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbehtcd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vefunuqx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlqtoot.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrievhg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tibdogim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnlnfde.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgritjgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlutbxiy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqaqvuj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dbshavbg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjftmti.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdhsgjv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2usnhevkf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfukkbps.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2errkxcnh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcvuevd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqfdpxq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrcrhmm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nxklzief.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqlcqix.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2duweyiqm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjwdpsi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzlnqnf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nivtvyib.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xopxjhwe.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwgrcfw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmtdjse.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjjrogo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyzltlz.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wadcmumy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbinvsv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlxmvdx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqsguyj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2veqzttue.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vegjtrbt.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdddbdes.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2byrncixl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjimave.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgqgusn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxldfiod.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2llngxskk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jypymhup.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uetyxtqv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqikuel.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqvkpon.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zatrhjwu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnubiwg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2csubzdwv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmglpqn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lynoifpy.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qyippvie.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuqcttm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcnshsd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2glrietwm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbxysxo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbqoqkq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2nafuufhj.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaywakxe.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2adnqfnvz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsctrogn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmjoknn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2hifwdelw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2tswhwvaa.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2uofgwhbf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jhegxtso.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2nnopesmv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jorqszhw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyxkaay.html


<!-- 参考信息 -->