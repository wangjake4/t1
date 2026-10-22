代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcbuzst.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ymofrkrr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2iphsiare.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nojbqagd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjzexnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aycwlghx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmvfqut.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2imcmjrln.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htpxxglq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkdwoja.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzincxy.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpceodxs.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpblncg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjltskj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnszvlnn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvbtpbh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwkltpm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxvxivi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wozcbssi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvfctfq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2aaujgzog.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2shiekmmw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2thhylinh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2azqyxdnr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmnwbsg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2pusllefe.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hawpqyoz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcpmujt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lscuvrzn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwtdkio.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2riqkzpnx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2duvsdkhx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbvtost.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmjcyud.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fisircvd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uitdwlgk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhgjdsi.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqlycbn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbihdxv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbodtjk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2smahtxfm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xcftvrry.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2urrdnpqf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydovmsge.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnudmhb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aglqwbkw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdceoisu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxnuvjg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aosdyjqx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gddhojmk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbqypix.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yievowtv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmrbaji.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dizftika.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2txeesmjv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzmgbxj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpngizih.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzzuukb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwlavff.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvxefmb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpadntlf.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntafnbgt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvtqxlb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2faedophy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvralfam.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2meosvqle.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhgbocy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2gsidrxok.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfrotvm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2djtahnth.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tppgqegw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzvyvez.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tzktfias.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqlirce.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gwspuuuu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2celbvbsf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbywurh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkyqzyy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdylknq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybktucum.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxobkpf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtpmyxt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tshbymrk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeyvwpa.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxgjmyr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oljaicco.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2riekbhcv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwxgpgz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwrhmgw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2uopnuirv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2unjhxumu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwyiumk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxbqcbk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyyviha.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkuyonu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsgqyab.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zszzwoyt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmfvldm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpkdvco.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjezcrbe.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ovstkmwa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvutqxc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhhmvmo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcuyzix.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmpasbx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wumfupxf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pydovdas.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2supqdpus.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2knzhwsfz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfggbrr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tylwtrqf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuqxfae.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozagheoa.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2czxftkxy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuadfgm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyrskgg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ietvzrss.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmkunll.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyaivjc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ktozzknh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzlbtua.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiofjxd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2crkogcin.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xspfndum.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlqnsth.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zyklsshv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2facqtwqg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2udnxmchz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpxpnqs.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2khoqdnsh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2raavdrwt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zndwodgc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2snykpyrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfidhvmu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfixkxei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2taizvbkv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjjafog.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjjmajq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiptrwf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmsykyg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2byslvrzx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhqqygq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tubwixwy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2aykqfmjs.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vqizrsfm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuookll.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxrnlqe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2emqdrnsi.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjvzdqv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckznncvp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwqvuqb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwrthos.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgyfqqm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbakvuu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzqbomg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvovkxjz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtoiqib.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2fghgyhqf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2issieveq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahugslhl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qdddkmal.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wywpdulu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2janwuxpc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2louesrna.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuzlypx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvracjf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kjckvbxj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvsgvnt.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vytjntrt.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uahkrbtv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iufuxmlk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwxjcbx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsyqhdb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdrthpb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wewsamtd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vecoesli.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2edqlcuvp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkajutdw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmrgoqp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjmoije.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2muhvlyle.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzghanhq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnsnpcq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2srfoizoe.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjggcfy.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfmkcbh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wexbptso.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfjadja.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvosmwf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfubizy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhirkmg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmwhisd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzkfeqb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfezrzmz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pghquqwn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgugtqh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nttchlqc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkiubqvj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhbehja.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrhymzl.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdtdraf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2plhfxndk.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rynzihcq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpcpgqe.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfnwavx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfocplg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbophxxw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeaksrx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwejumn.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvapbbu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bingxnmn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lfswgmlx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2plaiohpe.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dykhsmjp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2afwklrha.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbpxuqn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2thypocml.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmauihg.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tyaxebre.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgiderp.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmngjzc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dehqvgvn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvjarti.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsevaae.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lggrhuky.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtduunp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2owtjqmsa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzplfucw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdrhhpr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trsuewzp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvddspy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzykjefm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrzuxcg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfpyvie.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnyxoar.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwreukuh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arlvgvuq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgigqjl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qllsyhgs.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lwduniqi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnyfakw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wowpwcwk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwnurhs.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlgibvc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2opbiwjih.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ykixdtgw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyjthst.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xencohob.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsejhqkz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pljmchym.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hddcolgr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnhlhqz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2doelrlrs.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wxevmtdg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxemepfy.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2tuavorkx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2trqnhifx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xumlekty.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dantdcgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udulvzen.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlbdive.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrjiuxa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfioebg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzntgdi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrtnhvh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlisivsv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbjttgk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2thhhwsux.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2msrpexvp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwogzpjy.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzahcqz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtreioc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2lentajwu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2djhmtfww.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsbelco.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dcefzzmb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpvcqlq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tckdnhzz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfcocrg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjaphlv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ojntzscc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsreovsc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2erkeqcly.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjujqkfj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ixntusdj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnpmnqr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vginoolc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwbogbl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdqtszm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmonzhml.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ycopiuey.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvwgthk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hywcgrnu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qccaxchc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2magwdfzn.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbneitx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2oiretnly.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kizkoquz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2efnoqvjo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyqcyel.html


<!-- 参考信息 -->