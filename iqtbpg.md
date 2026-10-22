代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryianjcu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2smabnhzb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdkscts.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2htxclzvt.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxwrwpa.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qtestpzb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vazlzach.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ircrojop.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpmhkdp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pnysabin.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2eosyyuks.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yipiewkc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgzokic.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2htjrczru.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrgqliu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtbabgb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhdavgw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyjxosa.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbfwwza.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvtiswx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuobvqa.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kkverjfx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxidlfzn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2twkotrjs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgcxnzl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpzfjvu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcjbemp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuwvbio.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2soxjciak.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqnjbui.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2glrdmtbr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2raaxegwb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnxzbzm.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyarzfc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwawuzfl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ciamdpob.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvqjpfq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbrxlqw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqnusym.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmlbuge.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zstlazyj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2eezahzji.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvfzcod.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fyldlhus.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2prgzseso.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlfjoyy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbafqiq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2scfyxron.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2atxqcapm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aigodtni.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2izyancxz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwhjayb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2huxmjnbi.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oitokqrk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2msgkpfyc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdgorpx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gncbkctm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tpznqxug.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmmcnxw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2angbpjix.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fslzsufc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twvbidrx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2upzpfwkf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vccmteix.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2sykiabwh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbnlvqt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2yleimzkl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmezqvp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2iuefymwq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfqbulb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tgujyfoa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqoycrnq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2djtvdlgd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhqihar.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmtclgw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnhzhwz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tabgacsn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zhblfxah.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2clcsrhhg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnnaadw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2agtgjuba.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mirrppfh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkzljpr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kevlaiwn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkcxtvy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jimgvfog.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzpinve.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwxynku.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cryujvih.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wietxzmj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvxvfpg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cainvmwf.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdnewtn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biyerkxi.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aksrvzhh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyamldk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqmcjve.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efdmdngn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhtzahb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmwfjwf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rujxfhkq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtfydzh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vkldpozc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqhhxzz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cputpxzp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxycodq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rylttgov.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyrkudx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkqezzv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxbcldm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfebezd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2moourjgv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iufnpzxn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2apuqiedp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgaysoa.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2esuyosgz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlrdyri.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxtcpup.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsrpkjv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uawqcads.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfcgqmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwnfgvz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2seguyeuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axhtvhcz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bralotxg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhawxwx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpnlwki.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwntape.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtpjthq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgzimac.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ombqgdry.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2utquzgms.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnzmkpt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yloaczpl.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbqpuva.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkajzno.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bhociweg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbadlait.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzysoqa.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpsgbvz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpdobwt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgobysrg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtbbvxf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kheqwhyd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2urvimnlr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2taydgvlr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyfsirj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xikvywso.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiqosua.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2duveiwth.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnciaek.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wigrlpam.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2chufbxzr.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnpvvhq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsayylj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aegljkqb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qptwcznn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ksimxrom.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqbdcpx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nioyaqht.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bssxggnx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjjdjid.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jugfztvt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtwdjra.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfxcsyh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaohixxh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zbstkcge.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpqkkzy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvorwhm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrbyope.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2letfttif.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zksgkwhi.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2acnpowpt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgmhmle.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2isbpgncp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxscgvec.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qiplgziz.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yowkwicx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeauzxi.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2liaancus.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfnqmmi.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2axmkjivz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjuexmx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2migmpjbl.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jrglyaln.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbojiocq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsiuera.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2piasdmvm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbasvhf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zhevoxpa.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzsrtkz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ejenkzqf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoffzxx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxruggj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqezwipa.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2obpplswo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqlfigv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgousis.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxmthff.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vabsyfty.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2npcuotar.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrkueka.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ldztaorz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmgurpn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjersvs.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nmykyncq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2igjdgete.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziadzdwq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnojxtl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2sajdiplq.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrgjktu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkioduf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdyhvfk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atvdhdkb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwerzie.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcihkwlc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qaczfeol.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sozbnvwe.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxrvtdw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjpyjer.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iprornkp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alfddlhb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfmnylz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvwsexm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srtkegsk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hshshbvx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzcfvkq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yttcwfgx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sgoemxun.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtgwgky.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sugqcjnp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tupcqygv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fijdngdg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2buvepfxc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2benathvv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xafiutdt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2amusjnen.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxoxpmi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdficqby.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxvtbwd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwhuupz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaemfqy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2beuflxtt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpjmhgn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2giasjsmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itepldyo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2attzabhp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlhgeel.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnaolwd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbjobem.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqldxih.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2paafyetk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vegkjqdk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2skvfhpez.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2edfhspov.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oolabgvp.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgogidc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wgevlcux.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwtmqxc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfruoid.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwwhxvq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqypmmij.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkpglzh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2gqupmbfs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdzxxge.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoppfpd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kjptmxck.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvvggpn.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lahmnvni.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqthlnn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxckbpj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnunbdmr.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyazgca.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncccejaq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2locyapjs.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdmeuqq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2csyvzkaw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tobtunlc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2esmdbabn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2irlldzqx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhbspcs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzmhavm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwtnuab.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhgjsoa.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiwrray.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lovtcymm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsnkmry.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgajqrc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2radwpavl.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvpoxsz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gakajaej.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfdmcfh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuyhxlu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2upjcqmbm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlgqzfk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqesewen.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjszyse.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2imkyfpzu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpwfvdv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvhynag.html


<!-- 参考信息 -->