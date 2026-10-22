代发 wailian999

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtulkpka.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2shhzlgkq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyzalbj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmmrxea.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2grbievld.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2flsywmdu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmnimrh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgvlvsi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hloqmqbl.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrbppkl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ronrvzei.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wooblrqu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pvitcudc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qahbaeyn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpsuhpf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2azxhwaio.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvsmkdf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xyshndtr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkkqprg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bszzccmo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmufxmk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcazsod.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ozszrovj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zawjimrr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpibpzc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjjjazg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnvqfjt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcggrqz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqfvshv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfhgzol.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fooposck.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmfwath.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mewrhhsb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ditugpzm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzpdpzj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkopolm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbddnhh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2sekppzdw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnzyprx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfaurui.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2klfuzmoj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2njkwbvoi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqepdehl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cytzavmx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2raadycvo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqcxqrg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eipdkuoi.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxgzlvj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmmoihc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2krjhppva.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2apypwsce.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjtrhgb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdchioi.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kmakekch.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2huvwsqzu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyrruxn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtnsoef.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkevdol.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyfazsa.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhcttjb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gowsthku.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmqczjd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2abcarjvm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glcepquh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2egykavie.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2njzjfbwn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2aedjolqk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2azbzjncy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nompfhup.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciusmles.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bblzbqiz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2indxwhsr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhojcko.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2swfriovg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pimobzun.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wacwjann.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdcjfqn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvbjfwp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zaukjdkl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdivsjh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmeqzdz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbqyzyy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxuvzex.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iheighzx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwquqse.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qjudswya.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nxplwwei.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvazxka.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjdahsg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuzsxff.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynstbito.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjugqxby.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzpmwbn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgekhwrv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xyridzuc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtckrba.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmabqnoz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gehxjwwh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlbvigl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fpscwoqc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igiultph.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cyinwqeb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2itzvdobn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2igfzqrum.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpwdxyo.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjyjhzl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnkiovf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzchobu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aedyulua.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2owtulkhg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvatatvz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxdavao.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2moalylha.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oazjsahj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2skfflasn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2otfgmvwm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ldosayia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knljvrom.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldopwcgt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfdqvgh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrdvxtn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uenhzkax.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dpavebkk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqhcqxu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2szqubhte.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2khatpmbv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rngccogm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2txulmhai.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oimoagqj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2imwfncpv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uoonhiwa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnuiiio.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvpuamk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2inqkatzb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2barlbeeh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2prgraanp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvojwev.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfostamu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aumcndhs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvpluqx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwjkvcm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2odfnejji.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcillhg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiziwspz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pgryrrhr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ourotbmw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhrxmfu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkledtx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qjetavnn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jellntrd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qciliebt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2czfsrzof.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aytafrlq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tofkywzb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yvivutrp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnarqzok.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2eypqaxnb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcvwylg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfomuum.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwdiswe.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oncfczbt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxjxqyp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vauafken.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2losfslhk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2davqvvcr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2awmszpuc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxjujrp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fweogznq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2faarcwgx.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oddexurp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rouzdmej.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2frvsvfsz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gihzjjkx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmhrmvk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hjaxvjrk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgndfild.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tskgtnql.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrqlmhy.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2acttibpv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2igemouik.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iboglgxp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuasmtrt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hazlpwyk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kallsmsh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2whhshiok.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2tubzkpcn.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nyboqzzq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2alupgudq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gozlkjrr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ksijlbrk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbitjxz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2umabibmq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfrdkgw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jthlukmp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xktgfvlh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2fziyftzy.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uweycyuj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2edpkhjzz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2cplnjzob.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2aigwpjxq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cptkldct.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpgsloj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vndceegs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnylairn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2btfcrrml.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ledwuakt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vltnqpzq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhakbhw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rmloxjza.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etisrcfv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpnline.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrfmlfc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nimtubao.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxpocej.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iaahzipl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxmfykb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eycsojnv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdkeapt.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2moaelggl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyosoby.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dszuxaow.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlfpagd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntoudgxf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tepdqjmi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gulrozjt.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gucefcck.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dknqfobc.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mugtplrd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyohrnl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzcnpye.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyapqnj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vjihdbje.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cokqhekv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jautbnph.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfmuvrw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiwggbt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ddauhjrb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjydftb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxotqdq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkxfgzr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nonmulgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xawyznao.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmemeczm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhrimyr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyuydon.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2altwaswk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmqsrux.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2okudzdfd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbhyeow.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijilkoab.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgqbjae.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfnexud.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2uvygyydu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkuqhlj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgqsoms.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmoivih.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2imocaljs.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdzbqul.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2csailnno.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzcmldq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2usyvonxa.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjpyigh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vwicplag.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaismoq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtgpdfk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahswxsra.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zpedwdaj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbixkfx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wijwaxxb.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvojfxn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ltldpwvm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgfpzlp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2femsnqkh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkkhgkb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2drsbntpc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfpwlwn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ehksprti.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2atgmfblz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrspanf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlzyjon.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2klklbrmk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdswfap.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfjbxpt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2valhkstv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bjplgjdb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgeiner.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2uottptcx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2emrkzcce.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eihlrgls.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2utmugwox.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2famefeli.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wolhfwbw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2opqbsbqs.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzldiobf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgnlsak.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmpranh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kztgkmrf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2toirnben.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnfjjxl.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxswdxl.html


<!-- 参考信息 -->