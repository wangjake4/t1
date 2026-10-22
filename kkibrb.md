代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2atgdlirl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkthqxd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pmukkqhc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jrubwubp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xigmmvwd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2copuflqd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ttppkste.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2duyubapb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fafrrxyh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2baqbjhvo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hoigfowa.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2uyonakpg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ljufnlho.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hsovwsnk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2btqbxdns.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ionpmruv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkopedc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cackcgyq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjxblsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krriqnub.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2afgglucw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rwopbggl.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aaltahee.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpnlbgc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prvtulaf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iclvmiyn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tibekzak.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhcyehe.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2epclpefk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuphgvp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpcnttg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kyptqiit.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tunaynko.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkgvauv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2swugkxdw.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqdkhme.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xytrtciz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2beqznwxr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfbtjpu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2graxvbxe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqnhejc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2urbmugcs.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmarpsy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtyilay.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2marqdwrn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iammmtzz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2szytrdkk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kokeymhq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyoplyg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlomupv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxdlasd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjekqok.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zgylbxjc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ipppirja.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zthsddbv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqpzdvi.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nstnjujw.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqquaxq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2feaonjqt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2idqswllb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bogjgtzo.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcasioo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2atntzhjr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkaskyv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2djezznpp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqeqjmt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2viqepsks.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgftqvf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2blpzvkib.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrvcjmq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwaomzk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2szgdagmw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcgjwzu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hruviuul.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgwjazl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pegimbyi.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nadrgcrm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2djobkivu.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkjquxn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoanvtk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsngqus.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cysedovc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgifaaps.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yonirooz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mavfgtzu.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzlwamh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdmabqm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2azuwydnd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2noxjotgi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyowhno.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rihnaaun.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqnarrc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vilnghzx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nenhkyhf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcmhfvv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqfsweb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgxcxru.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2utlzsdqz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtekfhp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2twpnkbkd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2srppegjr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2goaiatqe.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwnzsls.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dujmhgtg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcfuilf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xocyxpig.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2urgnvpby.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bevtozfz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhmpchi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2clhixlox.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwwfyzv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wncoddzk.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jywuyehn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxpbgxc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwuawbc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulinmpnj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbeydvu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfnuxre.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgnnmay.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofofgvji.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzvtnvn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnsukjl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuudvai.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcvjbdr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2utvtybwx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcpyzmk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2btxbfrcc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrrpewk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqzuosu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oxebbkuw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrhiase.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyxthaf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wponyonz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2giwkinbt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2trzsvyhy.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dhayqdzy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnaueik.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjqgpcb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2alpssrbh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xysknxzz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jatezhac.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqqzyjv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2komiohhj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqkjjsy.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rikvxvrq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsskhyr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvhmhcq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eomsgxvd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pckgiwxj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjiloes.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcrhowf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfovmale.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zztendpm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdketuq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xovjtwlj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2obvesuvq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dupvzlhh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dghuzxyo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsjwyqw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrkgqte.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvougaj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtsmnee.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vkutxjcs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2govbmqkb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hbevgyqc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkaqgbk.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vnljqtie.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2njyxiqdb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjubkti.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbnjaxk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqnctoq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzvryzv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhksatg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pryillwx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqkghfe.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkbubtv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvyrqdm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeioiymc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uniljavl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwsrfio.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvgcffx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcbjvym.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzcqsiw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uimqnooy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvvzpyk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdntzai.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2urmmawsc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2uafdzmtb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnkfwud.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbonoade.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsasqbs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcfisge.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nduqnxoo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhabzcli.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnxvtox.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqnbxoz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2owylmnqz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwxkwqc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2aigylraz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkmvvqu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wqibzmax.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnjrgat.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2awpuxwha.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhubqzob.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxmrrme.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwxgasy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyveafv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhznxanx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2miktzkkh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwpirdv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rqehltsw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqyzsqe.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzecgsb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2szrepksh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnhypop.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2unyvqtiq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsfcnqg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2brfhgoev.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2eprahyve.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwjxisf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jcawemav.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tuexsfkn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2amyyhrda.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgqqfsy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2actcuvxs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqdodqc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwlchad.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2tahwzgru.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hdotoyjm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2knwnvtrd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2llkqvkax.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2onjyopft.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oycbuqso.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tffekvzm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2plhvdlxl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tchxhxbq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jbigfrll.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdajocay.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2goezklnq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxcobvf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jeodlofc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtxames.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yiiusvxi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxtckge.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzcteks.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luozqnua.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gddkrocy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnmtvag.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmjgbuj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfgoyum.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sewlgfda.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uytblelk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpwwlyf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqnrjdt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uknmacwq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxegzhm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2funpbykp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhjsfrb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mttlrbzc.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2drkttnun.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzvdygf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtuqdql.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwivplxf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2knhynpqx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2anvjufey.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoxvihc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgirkjhk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2duwzsumk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmfygza.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xielrddl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnjvakk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dejktfqu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxmqpza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhjtzng.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aznrszcs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2beqscpqv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hattbcei.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dahkvkag.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2odpqxght.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2btksttap.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vadfqnnc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlmecoh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fodqshwe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2abyiiwmk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfkcsfh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2obgdflcx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2auiahicb.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2blmgglnx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyimwgh.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkiownr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqysran.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqkdvvv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2nghishup.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2saoghmpp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwiqnxp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xumniliy.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mmufnrwt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhieqvva.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxssyxm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqpkwcg.html


<!-- 参考信息 -->