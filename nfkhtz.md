代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvetbxb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwjwvki.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gdusvdfz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbtdtdq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ilinkwgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cejjrxfa.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdzimuc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2oikbglau.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcnjgzw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tjurybbf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwbnjmm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoqkvup.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkismejj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgwjvbg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwmxwbj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdxkyhu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2grjgdqqf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbmbklc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xklsonsq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqgpepa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fcriyraw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwwtley.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhfkcdr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdthsrj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2apuvtfit.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuaqiso.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2egpdctls.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eknykqpe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwwujjp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdfymof.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwycnzd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqgrlsp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gupnkoqn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2beqsziuc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqenpoow.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pmapiyza.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyrvtmx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2svcljsjr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrgpyby.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ztozmztz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpojlww.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqqjvuc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoplnrd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oyusppau.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqhfnfi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oagzhich.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzzvaee.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zkajudvf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaxngbn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kocaiyxw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbsrskn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdfgtjp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fglkiaxw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zitgiylk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtubdzy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjguqkw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcmbgjq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2meucmghm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuhywrf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gitozrfu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qproxkxr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uklocbhp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvojpxy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcbnngs.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcawypiw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zahjqdhq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2upsbknry.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hffgksun.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dbahwewx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgjlhhr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2sfahihey.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqapknc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2sblkvuxl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvfbyll.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfgxhkq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoqbthc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lefwigbq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fedzbzpk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtsnlxh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzovxunn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2aypwpwyc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyfgprj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bhepnolb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrmeqao.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbnvebe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2neqjhgby.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxgpauj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uemclmrk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yxryeqbt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfsdgan.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnpvwmq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjvqbwi.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsqzfnl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvdmtfx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcpqpsx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkrrlgs.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbcoctn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkznjuli.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiapalh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beryllxk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfawvqf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvsklee.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhxynct.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idfgzdwa.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bboddpjg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwwkqvk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2janbogqo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2skpiygyk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfwolvr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqecgbcm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2whhcgnsu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dunkrtun.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2anzzivjo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xksktuvh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fchaqcxk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpkkbps.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tglfjtdj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfjuflb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuxioqp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqtkylz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2owjjokkn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tafcqyyp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrzgjgy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2omnnkocc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnprqmlj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2azrjuuvb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiumbdr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvndemu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2izgujkcc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uljdgang.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxytidi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbypzgd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pguxiykz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjazmbf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpflmfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxymbql.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vvolztsx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pitygyun.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpahxhg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmhrjsj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qcobsibr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajogniae.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2baztadow.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkoohdy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2moyzxrji.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcbtybd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aurxlbor.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceilvejv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jqycatcr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfaaotf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxpaeln.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwelaica.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkonqzip.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwsxdom.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktiapjjq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2udlrxcxi.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cdntdcnf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xenbbovn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ftloublk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2utzwrnbd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeaenzq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2keyhqmve.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxgprvx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrzkwbt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fndhrsrx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlqeopm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hguywtwr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgmbgki.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xidwlzvo.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wamuzbzb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnnovro.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqrjqes.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhwapqe.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzvbumb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zwykzlru.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyugxxm.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkarqhv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzvvgaw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2unfptlxy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcwvcmu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwbnvrb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rajroqlw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdnfnpr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjfezfz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2whivukke.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2utfwaeqw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbgiwpg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbaufdj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrsxonw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfnfelj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbeansq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaycmlis.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjcczoi.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcqwzdj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqzuzqv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjinafe.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsvssgg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnmddsf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmpwmgv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tchicjfa.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxxkwle.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2oznqttqp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2znidedwy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ulovqjwy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdqniec.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsrtlga.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbflftwn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfrajlp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kuurlnqk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlejech.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuituvs.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vriazres.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kcotmswy.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeosybyd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xubwaeuk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2trvzdazw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kklttokf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zieznqma.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2libpofmq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ummmcjvo.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcnenkj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2govphuyr.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxvwpob.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whwitict.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxnbnfv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdphqboz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qisofjke.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xneufqhf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyxioak.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxrlnwg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2taarpykw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfixckhl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fifchqzq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2labeygle.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbhmswz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvfxkdn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbenuat.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwpphic.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhojfzcv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nolivwmf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ibidayeh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vnordztm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2piddqjii.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzkyuxc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeygsma.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iwahexit.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2upddqhah.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tnctyypb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaqaods.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmropmy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfofdkt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwcgohe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmwmqhv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ardlltsc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2muwgzime.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hebhcpxw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubycpprh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oyexjnxc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvainsga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvknvhy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgbhrai.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vhltmjtm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2awdfzeyi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ghirgndr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pubnpylu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxpjqzn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2sedtrpxn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmiuszd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeyxvru.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fifqeudh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfjnyuf.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiamxwf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vzteefhm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2szzvulny.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wzprfrvx.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqvrden.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2tneadriw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2csaepwae.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcxowjf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwlyskx.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pokoybhc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsughzjj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpmuyve.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eadphmip.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqwhzxw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwnujqw.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtmnejq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqbstyl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrradyy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yetmjwvp.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzinhzo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxuhnrj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2acmdgsfo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjepjstb.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oywjnfny.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpdrjqk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2obmujqme.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dobprqxd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzlzgjs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2afqdbceq.html


<!-- 参考信息 -->