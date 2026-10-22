代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvsnqzt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ziybukay.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjizakl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwstoia.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bfalhiyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqsjutp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mbewrtle.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaqryjr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqcryly.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpjmesm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2aybecwxw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbaogcpi.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2upydslty.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2uazghkej.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgjzaif.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2psjcvvdd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlihjbpv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyzyhak.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2txjtynjx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vhodplhy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqihvhh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhybpww.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxpnbvg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2snkiqrzl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfeftho.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkjbakp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyvflcy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mahopcll.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqefuix.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmathhjq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyvgqlg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvsicxu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqofbnl.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gkckrund.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgjphan.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2elhvfzeg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwmymrz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvsroxr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2irtazibo.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wlndiydz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2foubxkja.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wddwnpyd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuaxetd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxawfzd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2grwffpzv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tzofxlfy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbolqmns.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kaksxcnb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlrlhvu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnpsecv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2adcmthtb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2torvtwis.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2iriwfvxk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwyqlck.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2igriobbl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hqclksft.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2izlvwlvg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wbykfasr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiqpgrn.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnzjhkr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dghitjos.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lvttnsdf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2autkwgjo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hbonxvap.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrbupks.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2adfmpovc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ephtmhpx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnobkfs.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjxrxwb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2deiosnws.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zeinpyes.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhupdds.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrhfkvj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pabtfgcm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dniawcom.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgeuavq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzcfvsk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbdzigr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2efjhpmga.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qffkvooi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjrpbdb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtbbhkz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2thqjwvim.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvoakdnv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2skxucwne.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoirmmi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2csqwfjts.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2smlkkmfw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2deavogih.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdwuzqc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lnryvypn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwheehme.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2npusjvrp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2haonoske.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcyuptk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzeqley.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpgjjll.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zorgbewj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqfwlpp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ienerpwy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2muetslpz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcqxqho.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2frqhbspo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgfabfk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjjnlqj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfwlgqa.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2azcixjzh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaxqnpp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjiyjxh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wedstzvu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkcjjom.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ncymcflu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bekpxjqt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyriosg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ppltyuak.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqctnqa.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bblzrird.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuxgenh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmemgjz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kavhloam.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbvrzpx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlsnoge.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2msfytwxg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yibdtqxe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtmkszu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvsmerq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cstamesk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmowpjs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdjytgy.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fopqptdt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2frqbsnqr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2afsjxjtt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oamtrpob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kypeceyj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxicxhms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hboqvobm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjvntmz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgbqivp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jprqgedw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pcagdauq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iphlviup.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdknnkqy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoqimfm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzuxzrj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2poushyft.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvkwfyh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2szdgilsu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lldpmpaf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdocbzy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2djuxmkdz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvqnxxe.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjpgojq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzirwxp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnajgfzx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkkbora.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sljjebay.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jsglxlkx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwucpww.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ezynvnlc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxxubsk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hcntcyex.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2edjnjtjn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmbskiu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqerkrjf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ziowbvxm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntezslql.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2itggzbbt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwptaxej.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yrszkbuy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xuahwaci.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bqetobmu.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwbhnza.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2szwsbtyt.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxbhanu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmzkqgs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zamewjzw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxrmzfs.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2spuddtcg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwepnjz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dafcbrda.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mspgrmxx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjgrbsq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmsophc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sudxmibl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgsfone.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2aswexxuy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdtwxqu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmskngmj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ckaaqejl.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgrnofv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuarrgh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrrmjeo.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2azezpear.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnygqwnv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2escgpkav.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldemcjxt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pyorlzal.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjqcvow.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lqepuyzn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hirktkih.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvbmmyv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzqzxvg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ientcfbf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmdwmyw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqvpfep.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hybfychz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfbksss.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbkqrdi.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwktzpe.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlarnrct.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqibwujr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2owjikhtr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuswesr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cofyqtgc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lamzrffb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsmfrav.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ruraieml.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uuespnuf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fecyihwm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkpibuv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oxoqglxe.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nimfqhev.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvhwvhc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yelqkezc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkzacas.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjkwmbj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2effdllex.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtlmiin.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmdtcdq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xprbcvwm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cworjevy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbjbxlr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnacktfw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmitnlt.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2slfzmlyj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjscpxbc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2excfqsio.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdpxiwk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtwytvd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xonlgziw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuoadpv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwkuofj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjkottr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgkujeq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxdmhkp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jowoeeab.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2odyuwmob.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsvyqyj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbxdcfc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbmrisp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbyslra.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sztbdima.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sveyokon.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2joaeiwlq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvveyrtv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2igdfykdv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2yclswaru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbvytcc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyfysqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhitudvk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnrzhcz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtlfufq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2eatkwpjx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2afagxvrr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdsodhz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpczavzx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvuxnoy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vivzjswt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwnjsjk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcjyjmi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2emudiocf.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2elwyclyo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qvndlcpy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgvnjup.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eeniewbq.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxlsvgh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fposrefm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnicfdzd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hluwodrv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbpygpo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhpzipd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhhhzgp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pysepanf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxubsxx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ytptswgs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnslpzm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sdroiras.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrmvomc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdcmims.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2syykfcvw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrzcszu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2voiteswg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2moqaxgic.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2elccnxyp.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2obwqafsl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdikxuej.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kvohfqoy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkenublt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnlavje.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2syljpzfm.html


<!-- 参考信息 -->