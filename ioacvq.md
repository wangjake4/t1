代发 wailian999

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuytaoqa.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tkabifvh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tudaywpq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pojysyqi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pebuhefd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwpftkg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoakaua.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dysqzukg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxqujbq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfdyhuh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnsolhm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhudxmb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcdedut.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcploxb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsddyys.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuusvki.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmlxkwl.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxuxmik.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bitiearh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkorvcd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2weyymrwk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzntyqq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxalzed.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tdltakox.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwzuqgb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqhayru.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tefqdzee.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nudybogv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqonpzy.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gklgdeeo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhmyxot.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwukilj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfttppv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxroqpc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yowcelrp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoqgdzn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pokhsxeo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpvyasy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cehuryng.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwrrngs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2afdcuxgv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrilmvz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkctvwts.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2iaagfmxz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2enrdhohi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkorcjg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbzpsbk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrzlpsf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrtirqc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jukamhuo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqplrgu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fskidtfc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbzjrrs.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cergommn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpyuldl.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyqrjyg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqorylm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qttyfyzp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnsfvnk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiqczvq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2pokngiug.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdektjtf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmkhhin.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svypjuww.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2paehsdsv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmmoign.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiyebel.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbkqvmo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fahuodiu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiejrzgg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiprsak.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlgfkah.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iruszauw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ytozwmki.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjazeqa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpakdem.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmxhpxu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmsswjk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjtefns.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ljklcpul.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwqhvog.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tliwcuot.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2czygslsb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egerttit.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaqpfpy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjaytgu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2srhgmuba.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlapjbyk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrvzazo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2liqribap.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cprsbjjo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gffdxbvt.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hasbeyav.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2flmciyps.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrutrqk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmwlmye.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2klorqgvr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2blvzwbrq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgakxnu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxmpldf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psybvxzy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtapmzk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrlscps.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mlveovah.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyejckmq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bnousrpq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vftfqbpe.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xafnpspr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgikixl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwcxaqi.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hihzlgsd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cibcwcoj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsonjebx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zlemudmz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbvkztp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2waadmihq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2etdfmtkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjomrgq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbsvhdh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zeexzsil.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlhxefp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuixnbr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgwurxm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqeeedk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ugredova.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlubmon.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2swinmpjx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqasnjl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qtagifzo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvuhafj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lrswjfsw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkrmder.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2joxtvjdr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2axmurefq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzooees.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xezuiaae.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vngwvupz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgiyxsg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhofmup.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2evwuwfdh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2huxuzuvb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2axfawsyh.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2repvczec.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrifzxe.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zhocsrjh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2avbfcejg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpmpaem.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkcbkde.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfwyckv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdsszxg.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2glpvrbne.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzquords.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcblhxy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2utyobagf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xxltdcww.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wierqelf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vexnsqsz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gywooyno.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxwlngf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2evirswwi.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqdxlzr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2llzoowdh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cccrpxzs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcyllbg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwpaebc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxieuyl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdivpli.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyzbfsf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2otovclai.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgftfkdn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrhqpdp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sawepatn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2msgnyrau.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqqunhp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xhufcxpx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvltiwra.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fxybkxmm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyomvrz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnurivu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxobxgy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxqfnta.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbfdcjd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlgplyw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnnvfta.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2srnrxpni.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bleppvtz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmhncvq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2slrmshrh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2avtmakvc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kslqnegh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iajsgcza.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lpardfjh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2plzgkxaw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yapdopkt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wggcjjvf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2txwmeyez.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kaklerye.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwawpzkc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwtcncw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tltixtgq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sleoqnpv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgdhxri.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2naysvxwl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrhcubu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjmgqwd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzygxwln.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlyvjkb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lswuepzv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmxldjo.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lozqetdg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2afxngruf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uptgzvhi.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rstjhwff.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxxsnpj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqwmxwl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyigkwv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrflnmao.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjshkrl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvyhmgg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkgarql.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jykmxsfg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfsoyvi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qedwikdq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oltuavmt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgfxdwj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdeozfu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qckdeqrg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2clhkvoqo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgtwjhc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdrghsr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqirkgzg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kedhthkf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucomwrvc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsesvku.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vltdgajw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrsrwmq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrthkzs.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfnrtks.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwbqwyi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqpohuq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqluqnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pczzdbyn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcjjvbz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qunmsckc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmxtoct.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjwjcwa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qprazrxe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjbtujq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrmyrhs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpssodjo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zugppjdp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lofcvizm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdfocow.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvwzmai.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uffhhtzs.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vndlqfva.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlyfdyi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohretcqi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkmvrro.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgrapdz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2klsmhaxv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmguzuc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsvvnpd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgimsnv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2crpdlhni.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgbljtk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2odvzdfgo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cledxpxh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbeskpg.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wurjnxtc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjglkcd.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rehjjouh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nblwmhsr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjaeahgx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrsylyr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzscsrgg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvghilv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hanqogac.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuwjmjv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvegasv.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dkahnvdu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yadbamju.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2komrzbua.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbqgtms.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbprcuw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzxbfjo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtzzzuk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2siugmara.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxetoxuv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cohoouck.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkhchrp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyownkzw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2sokfvmcp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2azyofgcl.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rsylpfcq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tabrzgfq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2afvampol.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ldulswah.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjcdcar.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2puiozwlv.html


<!-- 参考信息 -->