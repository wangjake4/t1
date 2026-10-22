代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkndoesv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjejdvy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2paclqdjv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2geqvfrmk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbxwozu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2opkxzpdv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wxttnejb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfhuegv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oisfzeky.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2moqxgkme.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2iznpgjje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2akvsjxjn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2apvvjxnp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omgkljtq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrdknzc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zijnvsqe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbwifrv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ndejmifi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2buaspmwx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zumihsmb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmtgtqv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lstobkiz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbiaqryk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuzzahl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eikcaxfy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlqlyjt.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tynzfdlf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2duhzoivq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xebumtut.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bwphahiw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cleimwen.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2sntplpar.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwaeiff.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwcolqx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjygvgld.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xszafylm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vguynbmr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jolnviee.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvscuns.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiachsr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdoyxnbb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkiwevg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2iskzdwnt.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjgoeor.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kflqpwsi.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2smduflaz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2svkrxqco.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtfsgdt.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2baofwcsq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpoilxf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgpbpcx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nusvwgrk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2chgceysf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wrylmcak.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbibwdi.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2anxsvcaf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuouwpq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfzqfah.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2byamolro.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qsflweum.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2akqqvjko.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcedsvfe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbejmtfn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gesqugec.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfihcvao.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eakwntav.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzifdlk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrhprsg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhruslo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2seplfbem.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsevxwk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtjkiqz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxeekoj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uutbcjba.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbdmekr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmekshi.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hmljbmyl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2swdflmcu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2blnefyub.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlobxgl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjekzga.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovppelkb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2walcevpp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmtwtbh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ulerdfuh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yffcdagg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2oraafyuc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knrglfzl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvlfksa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbclglhl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tegqusin.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zttvmbbh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2erxyprse.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yajelljs.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuszrun.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsfqjuq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ittbvbws.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2skxyfjal.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpzdrhc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwfuoco.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwyekqx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhnhyfn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2znemqqil.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbbtase.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgodlax.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnogjfa.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcfhnvr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vygexold.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dtieaaae.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmitouj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqyhpib.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnevbzj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2koejsfxi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtlemnm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mdacwrsv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxentyxm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjwxwia.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhifkyik.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxgzaym.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkmuqka.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiacnjks.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xefavnpw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfcdkun.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzshlrs.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eezynjpu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgqhxqa.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbwcxkf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyofkmn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaqierr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdwsese.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2giytbdpw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rkypnyul.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzzopip.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmpjxfz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbopfscu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxunsyj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvczfljq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ghozkycg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjkdmck.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2talmiddz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ouifucut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knbzmkgq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2oibqeqli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtckcnd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtbshkn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyjtrsl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjzqpfu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dwslaxak.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eipmsege.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2girpjnaa.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2iknmvriq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2glqgsrlf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmqfqou.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lestoqoa.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2obgiezro.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuqngtv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfzpprd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2runqovzv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2aizmukcp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsipflf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtglfbj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyebakw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugiwexkm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpqmokd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gmicwsqb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lijnkwea.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2swiwtyku.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oemwzlig.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcpinui.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoguvpmw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2enyiuyxj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwyuthu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2peehbaww.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttttywlk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oesfhtnx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbcyysw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2atppmbea.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdkfjuw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiofmra.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbjypkc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sexdoidy.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gztvroux.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cwddbwqa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmzyrub.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsehrnd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmlorxq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xiomwcxe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uvefjqir.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxixazlk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvreymvl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2orurjvgo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2drhjzkty.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bgypnmvg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbkvrbr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpsthce.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeqgijz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2locghziv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvycdrf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2efbzwwfw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwwkfwo.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2virzzmsb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlywnji.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2cakanzgo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hipfapma.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wuamansp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuapmtqn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkdjanl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqcktvn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cradrkdx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwavczu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bwastybg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzfkshx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgibaem.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqtibpm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fazjwkrt.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2yledhfdf.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2amocfphh.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2byhvsfui.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrlilai.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2evbdhhcw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dezpkpft.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvcrhnt.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vyccsgle.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgzfvpe.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdkemwu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fvevrkmq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2meplwkhz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzulizoz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2edvkxjrh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvnyjlv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgskptao.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjfygry.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmmjbzo.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xidavhja.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfljeoh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muqvnbbu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnhttqg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erzppggb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwudzyt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wldbwpji.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cregcsbx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqcsrxm.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfkutag.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzgicfb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlkevvg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ekognqqd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmtunir.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfwkbwt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nluxoobx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsnppdi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnnpahm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mapuqgej.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrsemkr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzxffbc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2owybogkg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwwxchr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvichwyp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gpujulgn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoftper.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2utngtqfw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrhlscs.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlhfxsx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhxexdi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qdntmklp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywctesmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cofzpxti.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqqqxse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oepflwed.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbmurox.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqraixr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbldvsj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzeqrnv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tevjkpia.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbdhdgg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzyxqct.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iohkyobd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmrhmvo.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nshkqihp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsnosmv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkanvke.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2iyntfpmy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyredcp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2naepmzwu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2btotcldt.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmgbgoe.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2moizmscs.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdhqnhr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bneolbay.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2svorrknv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aktplsba.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwazkmx.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgnnbxn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkqlibz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxvtoxw.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqpbvus.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnzulab.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2neinzegm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2emdebowx.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhscqge.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnozsnl.html


<!-- 参考信息 -->