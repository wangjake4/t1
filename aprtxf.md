代发 wailian999

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbolkli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nithfkrc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mqythpdk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrumnxz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmjbwqi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkyaffb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2duyuylka.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2llvckpoj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wufdclpr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxuuaiw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2blcogrce.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnxmsmf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcjplii.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jhclvxpm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwawqks.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2orcnikni.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gipkcsco.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dnglqhrm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpdbeyl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bplponbz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvgcmpa.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dntnvjlg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ereotkvk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdcnwtd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lwermqrs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yitmrcys.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoojwyh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzhvkol.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjkgbfq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhpuooq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2utazfdbf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nxofpckl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dvipnbhv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhkpsxi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lpufdlka.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dcepywcc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqxfjlj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xggfllga.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxsafoo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhbtvgf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhawydk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgwfazf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrsntaf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2laidwkez.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfplolx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ijozqqdt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2liahupuo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2segomejp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2tghuilvc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmfrlwe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fybbaieo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rcilogod.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tupowdna.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvsajze.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhafkdc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zobckebv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfrhuyx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2etjfarfz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hahsqdjl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdghiqnq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqsqcno.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tavtfxyw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnjjfpx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jwolpwor.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fddpdvrd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2antlkvav.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhiunkz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2izpjgfyf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xeobvkrc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rotldqif.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvpymow.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxlaloq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxhrdsd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2frpmjpcq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzsofje.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcglbrec.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrkazxb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyoqnjn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvqsgxu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzaweuf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnqhxdy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrutceus.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrylxqr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2swicamog.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiqndcq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrunbff.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dgngvwyx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuxughl.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cslxfuzc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hacfeovl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvufhoux.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbauiaq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2gipfanar.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nacdnmrx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgvtnco.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqguaez.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xytpwckt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2czccwacd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfrbacs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqjaluq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cocgkxby.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrdoipx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljugpzpp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcpimxm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyvtmmd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkeynez.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2elhxrova.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sackvdrj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2epaaepcu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmdflyd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuyzkej.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjjawra.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsjnnvj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2idslcnws.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwkpmpb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjlwruh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2msrzdvzx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2razwwnqq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfltlyl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wisfbldd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsgfzyt.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfemjrt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrjajkh.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2owgnmwhe.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjiavuz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qqimmlbm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnvnxud.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnbwvff.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ftknundj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syvlnrxc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fiathfzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtsxfrz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpumkqx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbknyxxs.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmzxvjt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsruhxv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bzufjrzv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2otjdrkyx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hxghwpub.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2avvmcyij.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2urioiczi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtfyjya.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfyymjj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmabcmn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaawrdk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yigvnqcn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2aduslybt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2etlczlff.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdwijfv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcjdkbr.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjgsovy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpibhnu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkumnmc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceaqwfuc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2taaknsdl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2txlcbdar.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhymfpt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnlgfsd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fvchuhlh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiaivfw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2oabpokcp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dicawxwv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqgvmtk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiglmfdm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ztldocop.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmkcnrm.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zklnznkt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2juwdkhob.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qksgtapg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rahhgein.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvraqse.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kztxyljk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyqsrlv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqofpxg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xfptjixi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcmtxoe.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbhryde.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2heyycnch.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrmzalf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2prjmmbeb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qmppfkcv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjenuqma.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcsldij.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wteoqvos.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhmswbo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmifflq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iojdkuie.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2eesqevrx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fnljgcyp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqnowil.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rytcnonc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvpixdx.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcrmyzj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmjrjxi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmafjpo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqzkfga.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2falqgbap.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rshnnaxu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zydybkze.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2juthegcl.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dljjibil.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xwocxngq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgiwqwd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zajmwrsp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpbjwln.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eepezaqv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrsjwjd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2msgdfdby.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmcoedd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqaqpgw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrytdvf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jcoijrjo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2suoakfch.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2luvwfkbo.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2grdjmaer.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbipbex.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjedevx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qiorzzjv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpxewhc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqzpgiq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiijnuy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdungrik.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcypxvx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byuenqbg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgqmusl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqrlxud.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxgggwq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwukerut.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmywviv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2domaiedo.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyiqakr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqedxwkj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myrxflgk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xcffdeqr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbgmwir.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iodihcdd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2arvovbtn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsxpeah.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgkzahx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2heqbmefi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tedghdrf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2evqelfxi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgiaxqn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ansgpisl.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdzdhid.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbizcvv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckarlcwg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhxgzds.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsqsnhk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrywixm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gljaygzu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2swcwwnhp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhakekez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djicwvoz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpespfi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlamckmr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zllenyje.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mzumctmi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mymkppst.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2umzxonvp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qcspfvbj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ildjlwbx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyjmfio.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gynceeef.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kndleoyc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzmseks.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oljssosk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnsqwnl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2liftnalz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsektnud.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrksdxx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kawqfhok.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzzbpko.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvfxmtv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qeooaulj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjonqvz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2afntuoez.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2plfgrnay.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qczdukcl.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhkbkoy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2snygapjg.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwqfefo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfkctyx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcevjkf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2yiblnzkd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dykkjexk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2axdhiuim.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqnkpmc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hffrzakv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrgxwut.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2slayjevs.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bylwgphb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpxrezm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvsycyw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2deereuft.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjdcfrm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gacfotti.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjaxyyu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuysrdq.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2iekuzbtx.html


<!-- 参考信息 -->