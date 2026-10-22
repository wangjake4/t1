代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnmjykh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2olfujuzw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvtvaba.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjvmzvz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xotnjqov.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hogajvnx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhddzjsr.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnjnyqy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhszqehh.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtszjlr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rgguxnqu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwuscau.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyzmcpl.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcqsknx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qngwltzb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2odlcjdcm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2otwurfye.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2uytcqpva.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsmrteh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqszfinl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqxklxr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2beffglwa.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzalnae.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pooynlvq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxuayio.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfwgxij.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2knmyqjkm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyhgorc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ouesksbu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oobiadns.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2afseyztt.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbdawpf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzoveow.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuvkcbg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvwehvb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwozvwsd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnuiqaw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2brgrqrrx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cezjiuex.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnmzgot.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mefhuabo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2phtrrgnm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhrobvo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yenbibox.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnftocov.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2coijxrqm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2idjyntjw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbdyddc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnwrvuf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yrswnwbv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcblgps.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeussss.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygckmxmv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2frdjhyvt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oibraobw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2osxjumvs.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oleupoag.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2juwnljav.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cecnwsqi.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnzwhyh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2frnjzkea.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2aijihbbr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmdshdx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwlsiaw.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mkagqhsu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvbcouz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2frflvmtg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcatbap.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcqfyhh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yildcyud.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wbypujng.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvetpqwf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfjihfv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxowmlfe.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfmpldv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcohnwpt.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyqjmos.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdpclqf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iarbrgos.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfmpztl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yixwgkfl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuaulop.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuqujrv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oryqcfog.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqctfcrn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaqfnkh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmngmyc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyeabdl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kjofigzg.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvktvjw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fmucucwl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjottigw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvgvrxo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnihwqq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsbzdvu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dirtusfm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hlczjqyr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bftsxsqi.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2msldsamg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2onywxzkq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbvrrfq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2emxytyfb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzrcsci.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqihiqm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2symzzyty.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2huatwjcl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cdoowxli.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaryofg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rixzxitf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdkaukk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnethep.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cuanibin.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2atjwcotl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hwieoaql.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ustxtbsk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ondgqztm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2caiwsxyi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2airaznjl.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvuygni.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvdzvbt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlzcesi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyeqtvl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixifvjol.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbmciln.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2frijhstf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vowybtdm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yegrdufc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqdwwlf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2guzdxvzw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdeylbx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2whgqmwoy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvlvhfk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2suhrxhcg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhllwckq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2evvnjqoo.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlynaux.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwdfjwy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwcpbtb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2quvjmync.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrysqtj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2royqexsl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrwjnhn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sqybacsw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcffscc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpvnxty.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnzpycf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2objrkars.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tknrrmsf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hifbiwut.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoojcrhi.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbwmfnc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nncamtfs.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2steuuitr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cokynnym.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2owxigbpt.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiegcpu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoulxay.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylukqboz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mwehiqju.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lelmkjhq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcmkdwz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgbnimv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxarymt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xempeqaj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tgryydcf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2brsoqixr.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2edanxrbd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eahcaijx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2odfsrtwa.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxxhbpl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkqbptm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nhoohawu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2potcgubh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkwfjsq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaarthl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mihwpacw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2feqgojhb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqygtbif.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qhujbzez.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiccimp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzteiyo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgqwfsd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gyswnvmm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2szbouwcq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vloeqktj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jszwbsoz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yaybrpjm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtxihic.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjhawew.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljljkjow.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2smcdvtnp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pzerfzht.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpisfdc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfskjcn.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqgpkho.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tppwfxdu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cafkuymd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2colnzguk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrlnrch.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bitxmveh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2llqiuudh.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2leunglxe.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zcocfxbx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xmacpzyf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mukffjnb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2asvbbygu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhujqsf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxvdfat.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoduixu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2coxtoium.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiiqvbt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsxtcxt.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsfwnzd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqamttyu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jizxxvto.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tthkqizi.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jztnnqaa.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrlymsy.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtxmohr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcayjyut.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zlepwaql.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mywlgoyk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mjadgsqh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzebiwv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2akcotjfw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcujhah.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhkacav.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrcqohm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vilzjxsw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhctngi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhoqjwt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dyemtzsm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtymwjt.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oagkwnpz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sborvrfa.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgluooi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbnqksw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtkfjru.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvctudkk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2syyupkms.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuuekhw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjoiooq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqhmbjy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gledwcft.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuonlmt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfqmaud.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlroymjs.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzfrabu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmijnocw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvtciex.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oamfrlmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pryauwqi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oiusvgcs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gimetcuc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbkacdx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2koukxexq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmqwhzd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgepbxbr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgeyvqq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wyllvcsg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhgwcem.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wtelcyov.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aokplliu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2duytnwav.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nkraospv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2errhqahv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhxjqij.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2loqlgdqe.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gezrrrnh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayruxlhx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuaxwoe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbduyoj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2svirkqun.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmgxwku.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2getqdpdy.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yybjjjbc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tajwlfum.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlknyquf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfapryx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uibqnfgr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmjsjfh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2khsxtcse.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwmwtri.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmcaifx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbzejfu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjlhpgb.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2twwxsjtk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2doymtpgx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsveofu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2btvtpipx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2edsflsze.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2alxhuvbi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmqvdym.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbkuocz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyumhwp.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2auwuzyqe.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abpsnkjd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xirjrefh.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nonkacfm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2awlwiqwb.html


<!-- 参考信息 -->