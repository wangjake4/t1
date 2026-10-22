代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uosrghgq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hixywvzj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zthkyott.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elwoddjl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2liqismqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgtjcok.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrogmqx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2whtytxfs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjqgxbp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gepguvak.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqehxjik.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghijeqwo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlwykco.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwxlgsf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgwgbxs.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kipjibur.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmidfdw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2shsngnqs.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lypzrvim.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fxarsuht.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hitcgcfo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ltebbokw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2umdivydh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuayrcj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2coemyqda.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2clztstwp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkxsprq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2atltfifg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2urzsqxgr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2syjrxtof.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxikeln.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2brvkofzf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuyrjrk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pascvvxh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkaghto.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2smwacvij.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2snivbstd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfidctb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2evqoymhq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuvhtuz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iovifxht.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rotebedu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxewgmk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wogoohoc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtvwsic.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2agmyxmxm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zklhxbkz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qblywwbo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pngoxudf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2amybxvnd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zodqgpvz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbpfswi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2udlvgevg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pauzqdfk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqgprqb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hblbgadq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lckbtdbc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iegxmhkh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2aviyzadl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpqsllp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtylvpiq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2asjhucob.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fntalevh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfruhok.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qticjapd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkquadb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pypvnpcp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bydsyjhl.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtowfnd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjuyjfw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fwalvcyn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvjlyjh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2oucegumo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tktrrhcf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2evyymcwi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmjchsu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2houzemib.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiijjgk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbpmwtq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqnvzbo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuovjkp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwipbxse.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2evhqlykp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhylfbt.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzrvoty.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kciyfhqk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hswgbxvj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyhyrrm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eckwlgbm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xylntfhp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vwungbto.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oogfyttt.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjufzdzt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoyulvv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbicocj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vygpbuqz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyjokex.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2epciceie.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ueudgknz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyubvbt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2olobyodm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kappzmyh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bclbasyc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efumymob.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dixetdyx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkournkc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnfgytr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlaytma.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tptyfahg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiinjce.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mshnsydj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cimvyxww.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tprbteky.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uivpohee.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2upgdqxvq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqmrzfd.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjxelub.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2olnurqok.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfimgqu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhhfjme.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxtaqxa.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqzehnh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhbacsb.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2htxdopks.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxglylss.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzanazu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bifxmiun.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvswofq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2luemnpiu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bizvxpyy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2isckrwra.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwnybpw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxkqocj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twijlfdw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tinjzwdn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgqsjir.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkohotk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2byircjmh.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2isifvpuq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhqcvuz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2agzfyyon.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiutrti.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2njxapnag.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fotnqacn.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfxvmfr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kunrkygy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyhooqk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ounuqzsc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2znyvimai.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxrxuwj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfdkybh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpbeixp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnkiuqx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqyhbeq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fevyorqk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkplvmpp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2phqfogvh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2aipiugvu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmqoysu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiddijm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlgzeic.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jflfjroj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxlqthp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvjwzjk.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpcwjfz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2efxvoseo.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2weifhjok.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsaumip.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgkqqpv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oanmacif.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jrchtsee.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2pavjduzg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2clnrhnrv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlwmyzr.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmbmobo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhrfbwp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuvgmdh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pihmbddu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2obyefxtk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqmfrtk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyvyder.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mutkvapm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dittltwm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqaokha.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rlajxkou.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfcuplc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaxgwvc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aichmjqj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcmkmvi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbwuozo.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwfvtox.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vegjlbbh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcfndkw.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kywufegz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlasgdh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xveunohm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgmlibr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhjiyii.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrcmkiu.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sopfkrmj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2egnhwlhk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2iberuaha.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2szmbucdm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2blugbhlg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2lfllybik.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2arwmyrqo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwswhvrh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwujzsr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kzicsiad.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2epihshtr.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbjrglf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ndokddvh.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyihval.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2trfbmlej.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvsmpxh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2acgxlonq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzvnkub.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nmodlnjz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqoiooq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nusxmhbr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjyfchp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdpuygx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtajltq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jidanphs.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsydmlv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smtkucqm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2elzmxwzh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxtbulo.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qofexchb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqkawsf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yurfgjbd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jusspkkf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kefsvvsy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jerpwmxq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avgjsgoc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtnvrby.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwgrcog.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2afoxotwm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrffibj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsrslya.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tjizkjwk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uylruhel.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaltttp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqvhwwu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2niuodqjf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbbssam.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvvpern.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrwtvrp.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2psgwkfjk.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqqxcjb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpighjg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2obfyujyy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lckkkmor.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pareiflw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2opopntmv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rcivlpts.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2unpznzqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmdcuny.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyxlvcy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yavhrquc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iyafieia.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwlqavs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gibqxqeh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhbwdkt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2plkkrfvh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkptcmr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wvolaimf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvwgyef.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qtslbcxh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xadmemfb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvhnllt.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdorceg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwawpim.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsusvru.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2frxynuiy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wekepjjc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwtjmyx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nofviltg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gorpfrvf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwujnau.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xjouwrsh.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2izfbhexf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqirslq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2irtmjoci.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoycrlb.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoijkfw.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnvytkc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqucuqw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbfyyti.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdctbhj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ujedohjm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeidzcw.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qkigthsh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2sefykrjc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kffmyuhr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2shtvuibb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rewiblai.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeklxcdb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmdnyyv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2enqerrqk.html


<!-- 参考信息 -->