代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2uehburii.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfnvedx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbdyjzn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zmotgoxj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxwmjmi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaaguqj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpzrsba.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwcxhve.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lavoatyn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfdupyc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fiddmuvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmqgkjd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bappzyxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czfjdytn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tlglzgmx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjymruz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huiymdne.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2egafqwou.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgloohx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fctygteu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfdmoje.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhsyhdz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfocidj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aywgylkt.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryltptji.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vincfgvf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pszhwzzx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhpsonx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlroexs.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mwupqfhx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2itgsplaq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nubnnujz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjcmqwb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2txslpxua.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkxqrie.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gswesfan.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pbelzhur.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgxnnhn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygefpsfn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjlbhgm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jibioety.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2byczthdi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2uewemizq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2azkwplem.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2aaaxnpra.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaziavb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyjdqhq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2roviwznq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2teqrlhnp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zoisxxyx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzcsrmn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbkgrtj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjltdalw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hdewjvll.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvwjkgn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ronlakfp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlodwdlb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oclaunly.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyuxbmu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgrkmls.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2srcxyrea.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyvecdc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlsuqmm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqcqhtl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkwpayt.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gflyptzc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjivuutl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2abbmbynw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmezqaqx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjoxrdt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dibhbrgu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2scyjeapn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlzvkzl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2enzlvblw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2afoveocr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxqwovr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pmanemis.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wriqrshb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2obvjbova.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2okeslqxl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2drocwpbo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnigynt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgqfxrq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2daprwwuz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vyoeablp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkgxrvl.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfufqwt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsncqvil.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pcarqtrv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljajryki.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hesfowvl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nncmhldl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lcovlvnw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kstvgomm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mmiikpqg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsxhxnp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgfwkun.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2octvfsvl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpcjajq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2djrdhsle.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tchdnrkm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbfjnqo.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aaojvsno.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2abnvlbza.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ninfnvjl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpaixyh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rffqdgrn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2genqvzzd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rvallees.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfsewrj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrzxgaj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlhzkpq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2altoylks.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjpmlro.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efijvalk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2iffosczk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lalxnkts.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2irfpysfq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kdszqula.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvpkjhe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eibqriyd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uopsvwis.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjdykhr.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mnajskvp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dorzgoep.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nodplgnu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2beoepmgb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2utwaeuam.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjxsnap.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsywdrw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoipfyhy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2defxyziz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoplhsg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dcioraje.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbqrzvf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhtlard.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2afayrlkn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsgamox.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2uticeffr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2meumpuxe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnradal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhkhxbx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvacflgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpkrkhw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ynylefzt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiktnax.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nknbmsot.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjgxpaf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2abadrgls.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzizhfbg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnpyipf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2biediylz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qscjlcoq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ujizisen.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbfivpa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uavsikxe.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sudufybp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzmowwl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zolatzcm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdzikxp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsgnemc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cumpdyaa.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ievfwafo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnycqxnv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2osonhtvp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhancitl.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2egmqxpus.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2olhtxhmk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2duslakfj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gksbxoel.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2idlbcrag.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvqdvnw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tijrjfuo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzsvtqo.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lebngxbz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzqvilt.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjwgcku.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fywpfycc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tjppwdxj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzzaohh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mriwzvhj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2crnhdezo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmkcojv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sditnwlq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rffckygo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqqvjhg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjhfwlz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgpnugp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2caaholux.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2snhdnoew.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rokqdbxb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkblkovv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2euwvdilp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfttgndw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xcejhtrt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgfftls.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2elswnsst.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rebaqhcp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ipobodeq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfniaji.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2oweojete.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrvewqz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdrclsd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2umopkjiv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mecpouew.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwejsgd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmgzfyf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxljzqg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wixalkki.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbzttal.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfzzipc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dicfecmb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cotutycv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qbktoalh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkohpvk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lppqrrpy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqkngwd.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzuwdgu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qoadjkvm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xhakjoou.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrewyig.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdegpbtd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hllftfci.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2afmrocno.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvtwbls.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pocdznmv.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gwropgxm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxinpdr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tuluvseb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjehdpim.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyvnasp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyinswq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvqhmph.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnkxlse.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gplhzehy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aroqnmvg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcuckqv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hobnjoss.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kblymwoc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jakvtisi.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdfplpx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmudahw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcdowet.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzvszph.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeiiamzm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sebclcis.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2avdenbji.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgzebbb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2blihepxe.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mpicwrwo.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcariowu.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfdvcns.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxcttrx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kejslbzl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuvmxrf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqjwlqh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrvmpys.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zohmspbh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hupocnfg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qdguocwq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvfpqry.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vppkwugc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqdgixf.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hayiwujm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrtgtxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujckfqma.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeotqpc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdzvkrj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cucujnzu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2beuxnkmt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzgzqln.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rahausym.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2taeefloo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkuguqe.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeqvgpg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2euxfnvnq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhcppcj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bceprstr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xylgjzbz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mphgqqsm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzylwmv.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ieezbila.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qpswwqbw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2feizberv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmilisk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkziykr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2stbidcey.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2inxzwyqv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnyvizc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qufyjwpj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hphxoaxo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwjafmi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2omlgxduy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcjahil.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtrojql.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cahlkuqu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2slaneojz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rohhownj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhdusqq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyemwjwp.html


<!-- 参考信息 -->