代发 wailian999

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uhldzctp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ysujgilo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2djlsqwzf.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzjattx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qteiskzo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rquvbthh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvlebkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjqaluq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmpmlym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqcumxv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2chkzugtq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2afczpsvo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iffadmcr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zpridyfy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkinqld.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ominrpeq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqklclat.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtccvow.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnhpafj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2emkapoic.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxbxbqo.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tivqhdpo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwukgvd.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sihcfbim.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ezulyiru.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cevvjung.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2weyxqrpr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ewypyfdj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dodkgvep.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lmclikzo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcfcsro.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2piukkasn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpoonwb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfmmdop.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrxxlqj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwyufta.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2iysijtpp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aabycwcq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nsilxxwm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oopbhfxo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ufieasfi.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjmkdng.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrhcpbr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkmsmzi.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xscdbsdp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhqybkz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qblaaltv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lsceoqss.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2badczips.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nlerbvbd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cefdtdea.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2phjksyey.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oewirykm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2edvsilfg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiqibyn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfgrovg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxgvflt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjoonrw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sywmsraa.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhycunz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeouxva.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2odgazlms.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhftjsac.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dptlcvmi.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwncaks.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqsdiwr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvtozak.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fprsuadp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdrmafz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exylfiio.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gypgpjkm.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2afujehht.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cisdyznw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2psdjewij.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqodtfo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmrgbpl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxguqgq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtauagg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmifyyg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2isfoehew.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqxuvuf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuiukxov.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2popwidlm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvylcfo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgjabfp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjfepwd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2snombipi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkkxuzk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vyspnltj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vddnwrpa.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxgkaoh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdijkmk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zilhmcld.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgtuivo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmtzolr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwtybxn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrakecw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nberqrba.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldivzsfo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hiydkwqq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ankshqzt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzihrxk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwbivji.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njbnkmbi.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcqmzoa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtqhewb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sbujovcg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoahgfn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mazmwisf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyfxujw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bofaovtv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2epmkunku.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmifvdxz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzhqdim.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvhlkks.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uymgcrpn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfykyesq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pesgsveb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gotlrrfw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbwegwx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwevkzu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaupwhv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjworqu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fkihilbi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2reucjpti.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hhriqhvb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2emnhzypm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bgodkeak.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auhcrvgv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oyunlecq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioizapkn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqaolul.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2azhnzscr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2juyqskaj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qrabklup.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtaxtln.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdhuwjo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkfaeqb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcedlfj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uyeoxbjs.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgcsopn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfduexxy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfjcbjg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ungscoll.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgbelut.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2igdqriwg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pbriahew.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oapzvpmt.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnzvlty.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2txdqvpwr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oviblwdg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gunqtzci.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dblludmp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2keootrxv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2roomgvjr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lisozfis.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxhfcza.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kapjjxlm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfbymtu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2evmnemag.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2inbmvrsm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfbmsbq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bnggeugb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcplafqb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gizwdcgc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2crsfhnaw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbvllwl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2usbfafem.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2sbujjvbk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvkckaw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cimuxfgb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqdgylp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2htdswoxs.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvbmpdl.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsyrlwq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfghinou.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkwqxte.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2natttpkq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2khhglulh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iecbxpij.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gakkbyjq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2smdplqgj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vyahizoh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjlxdrv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaukzfb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rryfwpsv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwjhguc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuxipxn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zwblxxas.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtcvqul.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2txhrpfrm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgjlwzf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2djvheuwb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwjcdrc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rixvywem.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwcvyuz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnonogz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hockgkgr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dordumax.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ductjidn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwdrfub.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmylslpc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxzyfvg.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2isductha.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgxghmi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyakzpd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nxehbcnz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2khdmbyjf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2sedkvcxs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2weeyuszf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ayictahs.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2yojhzyns.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ydylbvsa.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoinnao.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oorawpnu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkzwkkk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aenonblz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcowswn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kpienzsv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xbajakcv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mesxtoms.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgxxpyc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgqhvgp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcacjcwu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2blxgmwzg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqyrzyb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtfxtnf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nynrrdru.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yiormrfs.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwmkfnd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dftaumeb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2houvlwli.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xxukszvk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiskppwa.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vobbuwqk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2squmoksv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwldhoh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdawlfxa.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aiplgqib.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlrlgzv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uetzovrh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxectsd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zedsfkws.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqeffxl.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoenwjq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzquraj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgjwxqi.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxwbxsg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdallinh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2glswnbkb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fixnecqs.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tacbmqem.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vejqwnkc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkzvati.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2owlwmjht.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bosdzljk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgrqbod.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2weuycrsf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtxuuww.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2axotygma.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxcyqbe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gphsswtz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbapcosg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cheiapzx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bglmpyhm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2aoowmixd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hjasdfdq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzwynwp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsqqoom.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2iowscbvd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tetiezmt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhxupwb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ragnjfup.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwswewp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmrdnhn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqpymec.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qorqtkze.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xabymmro.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2upygqact.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2uomcajno.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2soaexzxe.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2swytxufn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvauozv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lavqcnzr.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvbjkmh.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqgauyj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dchnknhe.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2szxaaktt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2otfotcmd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnaqlhxj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2khxgyoos.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmzqkqz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xzufeyeb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjigfvn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wknxqymc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2iaegkpav.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2opnieclx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlmcazh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmmvadj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2amhenheo.html


<!-- 参考信息 -->