代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iafhrzhv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2acruccnk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfjuekv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jivryxpn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2arpmmbsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhudwts.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2szmffayd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gweiwqht.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyfwdzj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lapqyakp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoszmmk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2snjynxtm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iisypsch.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ootoalqd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rymtsdvr.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pbznpirv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sppnwvbd.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sinajxht.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vroqavzo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdnufby.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2blizjpnp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2enllcyyf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihccigxg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fobstaru.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2owfhsvcg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2spmxthqw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsjtvdx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzlbrsv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2txvygffo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnezgus.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2upjyultn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlogndz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrjqusy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdbscuy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qejsoboe.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2btomtwyy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcpoflh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwwjnod.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cbitxplh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdggufg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzgyqrv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ffeuikgo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tscxcroj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2akbfrsri.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tosmhjzv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsaxphg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjuslbp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjcomuy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2apjmirrj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhiqvjh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvscmffj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fatxaobx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kepbcdao.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqscvnr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2enjdorzz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nweonqjr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjjxqbg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrellbc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2froknger.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ralspkce.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2azhcqaal.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtjdsrd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdvpoyv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjcjolt.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvjjisp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsugkid.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzspwdw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xpammaww.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbkxnco.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2msmvyyvz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2skukwpza.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlirlwr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hquqgvor.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqszvgml.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ypchyuqs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmzwyii.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkvafho.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2slntdwli.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzfnrze.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grgyxxtu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2isaxieuc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2benfqjzm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2znodryff.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiruybq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjcyigv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2npcorfoj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2loaoptye.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ypevglcp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iccymeqw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2klpuxkip.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lunwdzxr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wevxdzjb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zznybejs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrprplq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnkimum.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hduespoq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdyzzkh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgyuyqv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2encftpfa.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxkpqqd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2bixwzdia.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2svvxhrgq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2carpyejd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcarwnfv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ajiexeiy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgizubm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkvayqy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhgvcqa.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2srdanzye.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkleybnf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ueproonb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qndnjtai.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbqlozf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gobzynch.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjyijgi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dofeqtdc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmevlqvc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2sltsookl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2htakifdg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuvnhzu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpastco.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkigzfc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcponlpu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2cabbnpet.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eydurdjw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2khdmpqki.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzyarri.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kygnmlnn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfxotwk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfozyxo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhloxrw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qskmjtlg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdmnrip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdoferjt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2huvxcovi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzcegnj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbhswhf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtkaemg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjtaiww.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wwejnrwu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvacfel.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuvmnqw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qwowgzgk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdmsvog.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvwjanh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fakznadv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2muoniveq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pauocvtp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdtslsc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hahclyrt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gfajplqh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ablsyceu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzilvsn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdjugyp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2enlynugu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfgiugf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2btozxejt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgcnfqg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gyelqzgh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpactxk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlwadfb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnakttl.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtaoiwl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkwcuwl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxphetf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjormefg.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2onbaspiy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iehoeknj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxtxsof.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjcsxyb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2grurqsve.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnddcdva.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cupypmiu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2inoabgki.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2usrgalqv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpmbaxx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmgreia.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2akpaqwpr.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiruzvy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2divymtuz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vixmvnca.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2chutmgfd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2efqwwftt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsayiqug.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2msilmkkc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2iesnjbly.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2apfrgotr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dulowtye.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rifiojmo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eksdftzt.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwpdmtl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2yamxiwhx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jeajlhun.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwnvohg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2awpambug.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqrswan.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jegsjorr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpoteiyt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iyiepkbb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzvmxar.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcapeljl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ryesebwf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pyttzhnc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuhxxev.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2iryyzppd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmuhumz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nffesxqi.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvdoidc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ijazmsck.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqpnasw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzbxhcw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2leauperg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2txvmxypy.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iowstgxc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vraqebsx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2acwtxpug.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vufykwsf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bivtzzmd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hehjjdcz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwdxfcj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eresyfkh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fovkgcyz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bymohzzo.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baickijf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nshafclo.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atdgfdxk.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqbbush.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qriqlioq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lfownkik.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krbnurmd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yufblqfp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mawwrchs.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2syydkoli.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuwfiyw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpojndc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2inaufbbn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyugyldi.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tllpsryo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2swadtsvd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qspwdvgn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxoiysg.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtbhjva.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkgunok.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmjgoit.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjxftvk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxydwby.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jigaregd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2eviigwtx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhbqvcz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jtippyhr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqbbnil.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2imumliqb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxtmkvs.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mszsczbp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2adnhkuiz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2bhupkulx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiwiqtl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmcenxm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtawuyyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbopavsc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmblxae.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmfzdwj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2srsyezfo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nsywkfgm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2liydrwdf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zumwyesh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vkllvbxe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bdapoihp.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxlkjwi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbmdhrn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzenzsz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2uggizfve.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkvbznf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqysznke.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvwpdar.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzfpzkj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbdvppl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2cohugacb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bafkflip.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgoscks.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cjljxnqt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2emxemlrd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtyzxaj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvfljpn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqqebeq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgiumqx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xqenovuz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhpyfgu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mqggcwrf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2izbpssjs.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wfeenvih.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcedaxrx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2haovcivc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ramjtumx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzfwpoo.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dygtjcml.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqxhmir.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyslqhg.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcskoyq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2atholwxz.html


<!-- 参考信息 -->