代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2suvmbist.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pitfrzle.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkvtuxb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fobezboc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2eljjwwfx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsswwkq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzmuflu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fazucmxj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwonsbkg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dczapxcs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vbunptfa.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkkiufm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeewwhb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2awvkgthg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrslgew.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2awofhzbj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbegeuo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2uuymhlxi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jhquxbgz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oceimppf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jmovwmrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtpahtx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyuqnpn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wvunpspm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axlhmnuk.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lthqzggs.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwccrivj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtadyljz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrcnzrc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxtbqff.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2efiqbugs.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2naeiegsx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttymenuv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxxalay.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mozrmncp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2igiulltg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2exysazad.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgafttx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfezttql.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dfowerni.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtueczs.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2yxouabzd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2okmspofp.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iocxpgzz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvowlhe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnebrrbr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgwdfng.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbxkhfz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kditndvu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2boslpltc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvdgraf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tjasfroc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gfouzmwm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrdieqa.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cchcvlar.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2axuwnlvt.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoktisoo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xczwvtpa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2otoahbmx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyyphuf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdsvfog.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lbucpxox.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsrqvel.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oglllfrq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwdlqha.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bthqezjw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qisdzfez.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwslnpf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqisgzix.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2clovuywm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqxfesy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yaovojla.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjzoqip.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxldrjm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvipgqf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkfwuye.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2saaameqv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nkddsfts.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzqixmm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpquvky.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzctfdw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxdnoam.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mufhkuae.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pifiznzo.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhgkliq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iopcvqrt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzpnxtm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrrpldj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnkexxn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmwitgy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2muupncww.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiqdgdp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ookjgpal.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2adixgbnw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcwvykd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnxafeq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvqnafs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuevlngz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2obcvveqb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2djrrniyy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2utmgixnc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaesgmr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvqedyy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqwddug.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmpchxb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzotzws.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2isgphhky.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkvlpsf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtxfewx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wpexvudh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxsxcfs.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bowbvxxe.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqcxvgm.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfnesyk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2frqsqjgs.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnsgrws.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vatxhjqi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2htcafmlv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrwokeo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pecvavab.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lgswhysh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eplggdpt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhyjqma.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmjxfgg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjzawbt.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzswildy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsoridv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpywfin.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkyzxak.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2voumtrdp.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxpulow.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nylsehqx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnjemft.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2iauoabqa.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqjehej.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nurxzdke.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsgiske.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfwuvrg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tedggccr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2juldmqjl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuaouxf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2njabpqyo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhzguly.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hzprnhoz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjztiymc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xzksewmp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fonaoiwl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcrzjdd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hodrinpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcbkdzk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaquypa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2geehttpd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kuywiten.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkaerdm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2plizzzsc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ehciyjct.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yaukuqgn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fetnysxb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlddxmf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2trstgwpw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcvbdbj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dsksfcjt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2azgczufo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkrwdtu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hlukoaab.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtuxptf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgxnsmg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiutztjr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdrycqd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmmkdkw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hheqcsdj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuytnwr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzdpoyr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvijtlf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ostmejlq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkljxbm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyhmlie.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2awjktjke.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2usmgcitm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pffatpey.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2riqtxwtt.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaerjwds.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2befflrql.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsldryct.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2totqkwpy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xzakrkwx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjhmccx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2keitdnuu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrzvylg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqrluga.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wprxqetg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcoxacma.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yipciiic.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mneetbvd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sxorpgae.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcsluhb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrwljbl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfezikb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuotwyy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtcjqgn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2iifqimfj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tskwbigu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgocsvn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqfqyjl.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkclbgt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2atfpevqa.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpjxlno.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2viiwdcuy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ommtwimf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqljbzbe.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xkztktel.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lopypyvb.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhqnrtw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjxdmis.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyrajtv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jigwlwqb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fssotukr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xthvfolc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2uszcrfly.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2facqqkbg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2nxckaial.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfccefx.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cifwscbi.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mamelmnn.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iznxnzvm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmellzp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgdlmyp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfitasq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2srmofjoz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkoegqk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tehqzfyh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpqjats.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmirnun.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlzziyi.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ksavaorz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzmlclx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjjlxyo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2eeaykvli.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyzjbpi.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcpdzxy.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2blzzuvvz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2enouumzn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yymzepeh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utewciay.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtvkvwn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rufghzbv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2meqjjqod.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzzasjp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwoewgfi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fditnlpj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afwzzmjh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwegzgzu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbmfwxg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mzneyqea.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkohnec.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwtdywn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcrfbvy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvchikw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpmeuvf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzptbkn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyobstnn.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2egieoawy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwedrdz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2llaezyql.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xctnktbe.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqhitxk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2trjborbb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2esvatori.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2atocvuvm.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2avcaipuu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nifmnhkt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqsiwks.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvuqals.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2guwgugqt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbhqovn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wurtkkbp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjritsn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2muvikcyg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fgztzkpd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2onlxzutj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pcifxipf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlinjbqe.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbziggz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgcppye.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jryseijn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tignatdd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyzwleq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktldjcua.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2sumgcuuw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yarhvphd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2flhuedjd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2uatanqfs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gefqaqal.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tikimtsm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kvknmsah.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2aypalyav.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ugffbntd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2spdonlpo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2weojlldq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsgfknr.html


<!-- 参考信息 -->