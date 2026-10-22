代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrmpljm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xturoeey.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbdmupb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvmjmty.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcfheoe.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuitwrl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqmkasm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoihwfp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsrmmkx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2btflfpur.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tkutzsfo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2unhhqsqe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnurzzj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqtbwxd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhqsupb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ghklsssb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvygxkx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcwldxr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2endejjfw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqwyuvs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtojxdbu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dalmnbwp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uutclwqd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdlmhxz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2epusbedv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qilzjcvc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mshtykyk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmknupa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dizugjkg.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmlefbe.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jnndikcg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsuoesg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyyivxp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwzfrzf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxnbujr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2farhzrkd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qweijgop.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wpissedl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdudrrs.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2znciqkkl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqkvwek.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlgctjp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hybxahlq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgebuth.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nigaylkl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrdthep.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vafevmib.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrqizty.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xodxgkdj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtrlnel.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2oakboujw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2koiwwred.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewipabyi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dllmkhua.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxydrkjx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcckrvg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ichlrqyr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2suuqidbw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2isxydsqo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpbhuhc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jygtjalr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2myxkhcfq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgygkaa.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rthlkqwb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkusxjd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjirtlp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhlaxbs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ldportet.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgvcqmw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2djhvggfk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2odfbbape.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvopeef.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vunqaolh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yitciiuu.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qabmlklh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwrrazk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2seinuqjr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtwwhwr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeebyxr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2harefpjx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2grqnrcki.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jctxxvuo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrdgfpz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjluojxn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjzvwpz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nagzbaay.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnbgfpy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjvzwty.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ctypmeeg.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltccyamm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzelthr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdecgovq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwjkgfq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2utdqbusi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgjyhzu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nebdbkmr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2otgloydb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieevwihz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rccivtko.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhqznyf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnabixf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrsmjye.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wsawvxmf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjttogq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlxqvbf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbwlcve.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmzzayn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrcdzpw.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gklgufjs.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbrtmdg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwesveb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2amnlukgh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nipqnzox.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdzuqmj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkzvlfg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2echyrcee.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcyplws.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2smmpukkt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwgpgsh.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqweype.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cagnrktv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtvfifl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2maqvsywu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ihislqhn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmoexyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdealqhl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuluddm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trrlxunt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgurmyt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbsxoii.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvuctrf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzbyben.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2urvdhmyp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xthvtsnq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnjtmxa.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjuimwf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oqefswzb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvhiibs.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2siycsslk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmqisgs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmipock.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypykqeie.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yymjuxrp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqyynaa.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfziblgy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvymtdu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cngeuqmz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvfwvpx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxgkdiv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwlsoft.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsbdomi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlsqaao.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xifmnwjw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwusrrbg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjeppkg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rckmwnzc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xzznwfsv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gethwdjy.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnczdnd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqirkxem.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqvsmrz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uozfbdsj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2izukmupj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rklktyoj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkssymt.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgamihjd.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wquzctnp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmrkbjl.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pzknnlaf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkvgtrx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ldansibk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoddgcq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2furxudcz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrdvuil.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgzjxfh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qranndsq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2phiurfyr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoskpsib.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyifvfq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2txpgprjz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuflnwq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2juptrvqw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nonvqabi.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtkgkqj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkdzipp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnkufbf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzhkbma.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfgftaw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnoglvp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzporsy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfnjvjp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2grppklvy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwfusis.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxtbqac.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2utbccrqe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gybibwuv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gwefnetp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrfsktw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kufrbwya.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jaaksijg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iejgzcom.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtnzphs.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yslyfagb.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2phtspzcq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jztwpcli.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgxfffi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2myqpuopc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgxoifc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjdyrqc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfoztro.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcqyguj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnywaph.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjbpfrc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rliboqxv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2whoxrwws.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxwuflo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhfpmfu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mherrfzq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jafmglez.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrjwkgc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vgavutzy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxsehlj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zotirzzd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlhqtpr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2frcmtvhl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaihpqil.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xepnzyit.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdihgsrq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnetoltr.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfpoukp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cefcxyxr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwhrrqb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxtbzub.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2crndzzyc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqhwtxj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuayzol.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmvcoag.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqrramp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyngvqo.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgqvwtx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2puaqovxs.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkmizio.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmxxbrj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzctdke.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlksmrd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhywtqp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2swvqxszs.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xvldfbgl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2suvcgteq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmrsang.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbnjxzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrrmgsz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qyedblsn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2waxjrexs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2spsmrxou.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfmtire.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lebititf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwaqcajq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmiotfu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pbceikzz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2uulsqdji.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2oawpocag.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iycwueov.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcoesjq.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2syklxgtn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2unsvdjwl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2buutyqfp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jodhtrhg.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcqzmta.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgexqgra.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhviztr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2elmyktyi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2poxzcxtm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjcnigl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yalkxoxt.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvouglo.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrabsoq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvqcuxv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlhjxzn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2keymjwny.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlwmguf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rttjzaea.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2mfehpbri.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvegcpf.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iiezovjq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2salrcqtj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdsytwf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xaymhcqq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2euokddvt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2epjoodyp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwxdeco.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vljyupyl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2nprwvmkw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mikjqfey.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rgytkgxs.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rybcorxh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uatdwfkh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnpxfwx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uuesooav.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sijsmqyi.html


<!-- 参考信息 -->