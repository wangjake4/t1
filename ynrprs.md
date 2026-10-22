代发 wailian999

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rsechtqa.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2brgcysii.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2asvgxnoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xelljnxy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pctoaqgx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oyifhuil.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnbnlvn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqvdhar.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbhozki.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jbykwlod.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvhtzdd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfqbltc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2djyqbrxm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gzygzucr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2obyqqmtc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnbortg.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfdybae.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wwaybxxf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoqifmx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxllqsg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvgutnb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lastfbpe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrgbxwe.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xayxjapy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhxyajb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwhiird.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjozxnyp.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfilevq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwqomql.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugssopcx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwenezg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urufyzce.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wexrkgwq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqqchmk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2trgzvjnp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2klutuveb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2csxyqydm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgowuir.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jsotrdjb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqyktuz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rewvbsww.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaiixot.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpcgrwi.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yooonwaf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tywaykhw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwmshto.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oloafbhf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uigwbpsg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2buijxzph.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnutrfd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxbufgn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmchzlj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zocjachd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2shrswyqc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmkadow.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2srkugrem.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwdnfos.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfytied.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcvpgbm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2laarploi.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyvtbng.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdxracp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfowoswr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbynfthu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbploly.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqzmnff.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtwdjqz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjqzbtj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsoacou.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2etzxprbo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkilsvu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dqagnxzy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2uueatuid.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2harhfdhm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhkicpk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jyydafsu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2huchrspb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrtoxih.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfosrag.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vygwleyv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxowkwv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbylfksi.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwokedx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2higvmqwq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rurbsceh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsxhiai.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwdayda.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdqwpft.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2negrdmdf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jticfiaw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yrygbipk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpebgnyl.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvohwgzi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlttyin.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnophyn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2izpxwsjj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ipafmmoa.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgifjbq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2phbiamuv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkrmcfz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhillho.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2naprnjxk.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtcpajy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsmzgfv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeoftlg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxlvpwx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfaefdt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhczxix.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2itexcjub.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwcetbc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2juotqtoi.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwhvcrz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjapffhh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgtcngt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bzaciuxw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoravkl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtimszst.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bupxxont.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgszwut.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmgxhmp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kelzaxge.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xikgvnol.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2grnckxcl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hznjjbyj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqckaysl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mogirihj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsjudrf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pfphdimj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fklcptan.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrybipa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvyqqlj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uvasdokr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqcfyrj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2daqqbely.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvumtry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgouslv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2czgyocud.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtksfbo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2szdhuqky.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mdswackv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pbglpzjq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2onxhpvad.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxgmbpl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iifpsrxi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2idbbvxmy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtatiql.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cowgimmr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvekwxp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2opehicey.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrrvcax.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmsznkh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzxkoeb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fobayyyn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2anxzwixn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfghgaa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqcecrc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mnionjqx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjppptr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpmzmqp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvfaqac.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbkbltu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2khhvimfg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sizvmsxe.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqyttdd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rerkspvf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjlbhen.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoeqnoy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgbsxun.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhybxkww.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdlmbuz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gztddchi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mikxfief.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgzkhig.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfzrsyn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnflhvv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdrscft.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfvlvob.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2omcnwumu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cngymfmy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mfukoltm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yklnnybn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmujhsr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjkxzqc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rffhwjbd.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yassqvoe.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dchvwymn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdgdcyf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2obbbngpc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hikqrlap.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdejcre.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ishxxhvf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsushcj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2afztsmur.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjriksu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvjslei.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrcllyr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xexckcat.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2awehrkuw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2comhzkch.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvowqum.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzkuwtt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlnvfqg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2omfntxqs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hihxehmy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzxjjjr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uiduuyxw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2neoojwzn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqkvsaw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xiaszvhq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ganvvyht.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2noyrxmow.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ireqjczk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2axdsnakz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqixixc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mynxarks.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2yhckcjej.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqjkssr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtgojpz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jredlqvx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmcckhn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qcamvdko.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgidowma.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmwzqmn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqxhhai.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmhqqgj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aywqhsvo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbnjgag.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owhfddld.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjrjwxb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvihwbpf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdwieto.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqiybgt.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ethallhp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnvneul.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cyddqcgz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwwdpcm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdqdzgo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvcvgqa.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjzwsxk.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aubttraz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2giceoxal.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2auedcace.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzanuso.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqfcehp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2birnfksx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxrqwyi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvggyfxt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mapewdep.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwciceii.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwhqshr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtduwttt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbzwdgc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyvmelj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kvddsijw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfeoipqu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2icjcaevp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqzejya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzbualc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnafmsbl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2plxqtekj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvgbiyk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgsmshg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2oadyyqwg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2butwnlff.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2laywfrzl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkkcmef.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2coumywai.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uxddrxon.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnwbmey.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wryzqaxp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxpnoei.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkwxciy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2djdqycpo.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2utxfofqt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ywndqgeb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2obrpqcwe.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2sertrzxi.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqihloyz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lghjraoh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2sapeaakh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsdpbcn.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdpqwnv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnbgqrw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2znfzjvhb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyrdbif.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jronlizh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvjcisg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcwwyow.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dmghkvgt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeqaluw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2krfjsjxl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwuucrt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zovoliex.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2klmbyzux.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fethtyad.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvsypsl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2suujwuns.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2arbiiowa.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwmctoe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfjlhyv.html


<!-- 参考信息 -->