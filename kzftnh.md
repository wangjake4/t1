代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2glbajaeq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlluxpkv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ikulxrme.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jfebhrvc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lbupyuyv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmotygw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdctlzj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wojkasmc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2prggkatn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qknspkny.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoccoqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udmvbkgs.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fukpqxos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2noncloth.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjglvfc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsdoyiv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zapvuxje.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdwhang.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeysdxt.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ituxqujy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjhwbjo.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zrobmiqc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ykewlvvb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fegnhljl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2prmlivth.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lxremykq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrtzrmx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvxwetr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vunmyeaz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyeiyje.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqnmtxl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfwxfbu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbgtwvl.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnlsblb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzrhzen.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvopxdu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxamocei.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvygcwz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kedeegzd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nntzdpcy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bljxougr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2blldyogb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dovazruw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jlavvkqq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2iwelbsso.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ewaairln.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgjxehc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqonsry.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyspjnp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxotwzm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2aszoafpb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdftqcxy.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xycgfogw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2akhblatw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpofwxko.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pipmfmbe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxtmciz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2utdmehsm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvscmrnp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2howeioyi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvxsacv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2eytyybqs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpyrgwb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlytztv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2whxweuxx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nguuhcqb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2resnfiwp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wklprkvh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbypdco.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2omgleaqj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxygord.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mprifyij.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uepotjzg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyerrczg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfncxpy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2smtwavug.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uabaesqo.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ssncfafu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dlypusrz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjguddp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2uorpussu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izyzilyg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2luxzjkoj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gesxzwfn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxbwzhu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqmmmlz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcafpml.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whqbtjbo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsyhoqa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oslhobvw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxcmusz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyihzdj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hcouvctm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruotchir.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeuoejr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmriknp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oezvwytg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzxnrqj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2npjfwjwm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sblggcqe.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfybihwi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2quimctzv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxhmbcm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2oxromiwc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpjmfhp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbnbrkv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhvabnk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hskmloml.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvxsonk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgdwdtt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fydgvhor.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhunjbpy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtphiba.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeecdur.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ordzeebs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdpzckz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhzxbfa.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2farzrvwj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vntaabab.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsqobph.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuemnrv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yaejuntl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsuoqpl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xvswjpvi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmowcyog.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgpsxyg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jowqmjgg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjtfuwo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvztavqt.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuxwtrl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2erhzswpx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqeipch.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfdijlg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2caxumpmk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvttxbln.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fktdkzot.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2deasjolm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2esoecgnz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2krlfzfzv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oweourpc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkdgdia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvuzbtj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlnkiob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eltzkeoh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zaletfwc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmpefqs.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2csuadezs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfsbehk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sssxanhh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmecwuw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zepsfwoa.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqevcxe.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2adrebrzd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkexguh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dmiejipm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2edznvhaf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zprypufq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdquvjg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzlapac.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2eliorujv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvndhkd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhqarwq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcolrzb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gowrdnmu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pxthyveu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2yisnrguz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdaaqeg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyfarxl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmosoxi.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcztglgk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhkudlw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsimkpw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpvfycz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pijjsyip.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkistkd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlgnsnd.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfpdggn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dwycgcky.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdzvubr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ieiidesv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpxnbfj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbsczte.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwkasfc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjttrez.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkaagxh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uohuoebt.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdtkarg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpjmdnk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvjdcdn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2evnqcvak.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2syremehp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fabphubi.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsnudjz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmeelli.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2joujokod.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2umlhetan.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhxkmuh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2foluxwqd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sqahtlme.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxhfjny.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2erigrnwe.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qahfsfbd.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvlkfwb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgoczms.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2krgtcoke.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsohcxe.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgmsftz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2atpllzbu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkrmefv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2oncxppbw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrnaing.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2djggmrmy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vyucxqds.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xwovkthl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsggcle.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2stjucwtx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tadjuthy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2objzotbg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmnzuvt.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyipztd.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aadnmlei.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvauyan.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzzvrkf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvfndqs.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2syvvpjeg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzhhvce.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tbshjrnh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iewxobja.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2akjbwlmg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2crwkotzh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xikozuzw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvakfafq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xctewjdb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxexzmx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqmmnkg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfccohk.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2stujejbx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsjllam.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwpkxxd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfdyorc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bucwftex.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdapzkg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwbidht.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqgvyfk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qudctmqq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2whhiyomb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vavlkyxs.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxrosfp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kekwuwrs.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2larlzxcd.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mspdewxd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2keqzvgfn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbaqdmp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfhqieg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrgdrii.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpczzue.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuydnuko.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzwezcu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2frqnveab.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcdnffb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoqgpaw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zctkkfkn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbvqukn.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mgquctvl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2uehewdme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vewgubdr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsrdjte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izodgotw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tnasfepj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2cjexdynj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbsvbbr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyehcgm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmmufwl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcornly.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2taciljfc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmaasxv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ewosazmu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2avowxheu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuivuwg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsccvww.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrjkymt.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zybtsoyw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dgldwzvh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2bylrakbd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2faauyxhz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxouijn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsjsyzo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlypklgq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvwjvwj.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfoiimq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oikpuycs.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aegyngwa.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hlukledu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlovgkos.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjtpdip.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2porhyubo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ttojmexy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuyfyea.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qneeqdct.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnbympe.html


<!-- 参考信息 -->