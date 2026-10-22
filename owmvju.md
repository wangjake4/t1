代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2oasuvaec.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcignsss.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvrdwuw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdotflw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnuzkop.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2axsuuglk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2itkeghpd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2oayshnpb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2srkecptd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzacctf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzseeuf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtwyvuw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkdkbwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bieqfxqx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2acekwfks.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzcuyfr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvvszvz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2luqyeezi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiwmcnc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2seoygfsy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrzcpkd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wflfkkow.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tpssaowh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2puteigmc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnynrav.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdizaot.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2novdhtrf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2strtrxfg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mwneqgzl.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpoisjh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2knbjthzz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhvlxyf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bmisrhxl.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tttmowrt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwghatvm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvvflzl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2thhcjbso.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnvygpq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuenbeu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxxcmoq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2diikkmca.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bjflmyln.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2froylstc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2adktvnpw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tipevtit.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmkxlxs.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2adnzsmzs.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mifqgxcb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2krnuxjcl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uirpspcs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mikibcep.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2otzghaof.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqepglo.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2scwybcfb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoafvqt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmldnee.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tndnfush.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2insemwql.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgopsnb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2unznybmr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2aetljmdp.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rabwksan.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qalnklnl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkzbjwo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkqcdib.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kswqtfnu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmhnpib.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2olxjepzy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wunwzhuo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvqlekx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaiflmg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhiwdml.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uupmzglr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhdhoeo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahosyvaz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ixepuvxu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kfalycvq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qocawprs.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcsktfk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uxskhzft.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2miygczch.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzapdntm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jctynevj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2khnjdebx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgdivnm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcgsnbq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwgozqx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frpwebvi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkzdtgb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpiunjs.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2glrdzyop.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kobguikl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2swzdotsd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iesmofkn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bxheiizw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mcorffue.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqjmsef.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhosqoa.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dizqikon.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2piuszuwp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnfkygv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxnlmxl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sitgoqmu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqucust.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmwhyrf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2owrkqcdz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vakejnql.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtnxshz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqhjwwz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hidfdani.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2otrymwiq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uckptmgy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvohhbr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrghqxkf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlcvfpc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bifqzhaa.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsugcyad.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvjkzke.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fyucqgrh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jumdkcoe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcvpciq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfltuzi.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kilsphda.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzzbcbu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obzeaupz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2amfvmcpo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2crdjnqsb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjllaoc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfcztlj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwnzfbs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqukauhm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tevdjmbl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcfxany.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjqgqng.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfmanzu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqxttwo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tezvodek.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ryftiiqr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgoirdo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2puixoela.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpodjab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drfbhlio.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2beemrepc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqejaxaj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfcaovm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrrvian.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cekgnfcu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2auymawfd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rmblbdgd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcaowhr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxyfogq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vsydzsdy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kaibexzl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jstvmzpx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtfgevd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhqkzlz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2izosyyzq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2czpiocuc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzqznqi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkpmwsx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqazxyva.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2enorhspt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzllqay.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwkhpph.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpemtqa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2syzloafn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsyrtpd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkwndfz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyffkcc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhaabbq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsbslmm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qazetuzd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cinguukk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2diubdozu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2svqqnxtl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2megrywrg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bpccxrpg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jhguiqzk.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2knbycxez.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2noizsjjw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pscffcuq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsucomw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qygmhqda.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtcfbim.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2asruqxeh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvomwuvk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2moedzoue.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kggogaem.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pomanlhc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgfezel.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2azcuvkhe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2udvvatli.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vejangst.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkcshdp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpmulku.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2moqszovn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwkansp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxbyylk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2edqdjogg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzupydn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hghonyzb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuwkeky.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmliszn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2plfunnqh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gyobysce.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrteiftv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2awacsuge.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2alplsgdg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2elujieqp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2apdhdfir.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vozkgaag.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxjpfkx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjvcvxy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkljdiu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkykckwv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ttitcjkt.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzotcle.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcwsoci.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vougwrhs.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zddmxcia.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcdoqgp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilesnphe.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2meuranlz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnxcdbu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtkqloz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2enjrzznz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ococxdzy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ennyzefb.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrlkcoq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbkahlp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2doatwwdx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orscuwtm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwgimra.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvrttvd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyzyzgl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atemvipy.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgieonw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqaheyt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ooopmtbm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqpjxyu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkamkiri.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrdfhhe.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjxjqyj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdjrgsa.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybisxiwy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ychkeman.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvqevrp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzdqfxb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyucjac.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrbnnqs.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oscuduvv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxshfea.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrroqzk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wdatgvwu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpglmgj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rvewlqur.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcnakhz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpubfcj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxacxmca.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvpjajl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfshwht.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2atdgequp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkswckzi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zglrtqvk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuouaqyx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgrlsif.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hivbyfvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lptugqrc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2staqwwwn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2glcairwe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2sumwdkxv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkifoon.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2smwjfyei.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkdvsoq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrekbyv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ntisoadl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tnudsmpt.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2grukolkv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iugnivxp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tptkcnje.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2lfazecgp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfryntp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrfdxiu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmafekx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbhrobj.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcgvafk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfpmksu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcnlvqr.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlebdtg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ittpdujo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjbzmpn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dowryofp.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2adlbpulk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqiyqed.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zzddydzo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lylkkbku.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgakonx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwsvfvm.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmwwuwu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2iexvzxtp.html


<!-- 参考信息 -->