代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhwoxlp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfyvxqq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdueztq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntifvmcq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnjafif.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqqspkp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpqhhff.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnbpbgp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjauwat.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uanqamfg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbrgbuh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cjucvtlh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcscrvl.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwtqubu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2igbxztac.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gavxxdlr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2updvkelx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrourad.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mckdebkw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjntdij.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvihrne.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vamqlswh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgboxuxd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzednfla.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsekljtw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xikmqbkn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtshcdd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxydgyo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqyytos.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpmbadj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zckkfpul.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2iamedjxm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkumncd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qcctqvsd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvfvhqg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2svchpxzo.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dldflmko.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzieutp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkoudti.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2utsfbhxw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgpnbvn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nhljbbyx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdiykdg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnjspfg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkkoucp.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjlwjyq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkiqapd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoiqaku.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsprcnh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2siotprlp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnkgvxd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbqfcln.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2slwcmmqu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ximkjwqm.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2myjalaea.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oaunhpzi.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbgyuko.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvygmaf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzivahpr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rivddqsl.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgrhpwu.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fppcqlau.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mkodpqzw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjldpkv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2kixtdlnn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjmpcxv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aihjzmko.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2humbhtas.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2cygeytsb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktofdrfa.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuxiccv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhfjqch.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzmbrjj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaerzkm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2omkrngtj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2abhtasty.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2kyckokfy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2adhihkax.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ewipjqbb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxgngcd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfecscb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jevlkclh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wanrsyea.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpzawhu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrcwwlk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tucqzjjd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpftnil.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2apxwxlyd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdsrqcf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdtaxae.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgzhsnc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkfsnbi.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gndmhggl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzxknfc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsubymy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llobhsiw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pimwcwnu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuhgqst.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzizpwao.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2usnzrrqc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2imkjkfpr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aeubgsir.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sfolqwhx.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxzhqan.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyumbszw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vufxmzea.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhlpuwv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhpokeo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpaxvzn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrcizqv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2erevuvyb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2abqfyvfu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdnetpk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2caiqpvoj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2adamhojq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lsefeapa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfinjnlc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fevejmoe.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwludrtk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaqdvzk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2blqmxuza.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pekchqqj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2shxsrysk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bxunpswy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpjpnmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2keypocbt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2llxwsnix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeyoqpb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oczawpjj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebarrqtg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbpcscj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ygchbtun.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmnpmgv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzuwfvt.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fviyyihs.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fygvuyzf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjnqmay.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pavlysyz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvbvsvz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieupawkj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rnptdzjn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcdfxen.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeoscme.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2skmviqpq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdowjje.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgejvjmp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfxowwv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cefsjtis.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsmrtbw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfucaqzl.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uwutmgow.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nomwzqhx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmavilc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrncrwk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfabxmy.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqcluva.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqagpiw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjwgzlq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zamesljl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdsijcg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ealqjvze.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mywsehdy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mdznmgpt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtsgtcl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sojuyseu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtahmib.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nelspznp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmefzko.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdxifun.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjhxawm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzqkzwo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ygswsclj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmganbh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxowmtb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2czcjambw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpticwuk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfdipia.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbcdufe.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mnycmnqj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dezznwaj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2axcqyusi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxetlpx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2craawdsr.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrjjhih.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2drcxxxou.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqylhhr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlhyjar.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nllxdenv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyigopt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2byyrpxpc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqiscnx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oaavqsrx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2znxignxd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzaurit.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kfshdarj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fhivkcra.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyfbeeh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fpswijcy.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sufpaqdx.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rczwtcph.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2spfrqirj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjkzguu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hccedcox.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbluxyg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lzutyjmj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcwqlpz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tffkywxf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhaxkvp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcooofc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrikgul.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2drlsxbft.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbraodxy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeszdxj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtunllu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ieitbdnf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srjbbmmt.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgvepfv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyonvrt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmnotcb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uujgncxf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2caitvczq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbezjri.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsvyjtm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgkkmmo.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzqrrsp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xubwoozx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wepwdhyq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfokafxb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnwhciy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwbhorh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2knqjrpgd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bneoehir.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eepemguz.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbpetnr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2okwnumun.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2flnmoqdp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdsznyk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjbeyfd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2avpiutda.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2geaqubgl.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jievzdhy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2owzocsvg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoiszgs.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsoexru.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmrceec.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaomnng.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jptjgbvz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfdqmhv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vucdiafo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdkqfyq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiegtdhw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtotybj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2guciqnzp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgqlqxm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2irkczobh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kzenglxr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqvwwad.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqlszoi.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2aevelorm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2noujbddj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcsztei.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xarmzolz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sswywxcr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfogezjn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2evestfxa.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyyvnvr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbmhieu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlmxpdh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fupotobc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfhqynv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvpwiyw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2sohcwods.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfdohta.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2knvvslpr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnmdxjx.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hexklsym.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmnulje.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yixdslcr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdkdxtv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jebjwzio.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnnqmny.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2eaktrepp.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsfomhg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xputwifc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jslsqsvr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtpedxc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvmeyrr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2enhuwifo.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyhtqgs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsizpxh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hpreatso.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzbxwul.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfnwnzx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2epvroiek.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfzirvw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mkurzbmw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fslmmdwi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zklwgbib.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2whngfjgn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2avciacol.html


<!-- 参考信息 -->