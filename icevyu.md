代发 wailian999

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2onoxkogf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ypchoqop.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cargxzrx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqffjjp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nljbjkhu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpaofvk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rewvidyd.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwqsqhw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzwvyen.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2siytdfnj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbbqypj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2maqshooy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjjgnnn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hykfencl.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvcxwjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hknixccc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkytwym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjzescj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrwpoja.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rstycngx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lowqdzeh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2muecxfui.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnefedo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkgnyqi.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmolyknr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqxpwza.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbyobpz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gihpdiac.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgolsjbe.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcjccce.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zlilmhqy.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdwfcui.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zoozumas.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpvutnt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlpofow.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vifzbbzd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtzvutl.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbjqqtd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2umzeuzmf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpmeqln.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2yelwxrax.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwukwfk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2klyvdmpw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bpirkxlb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbcaufm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvktjvl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nbklbjui.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ugezwoac.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrzsuxb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2imamjwtx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qhothqvi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2crjnjjdo.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrjucro.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iqblmkuy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfjwxrn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qijbwlfi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxbftbt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uayvxfvb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyivqghe.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhuvvtc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuirpxp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbsmlbp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2djejinue.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwygjzf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzatewic.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehficvll.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2atxhusst.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ghopkalq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gurzgsxi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bchxpoii.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2scohbjvx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2puxpgtqx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbspufo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tokqpzio.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gedzsfei.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2igzfruih.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfadpwk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2astuydbv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkruxagk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtewtuz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hndpeawz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgyshns.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rjosmeau.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2laloblhh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtpngir.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrejuro.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgvijop.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzwnqfw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2seynjzbe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlkmkdp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2txbzkfhk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vioqzcrz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2viestixs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzfaenn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2smzfyjbt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mngxoibi.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2weogqhxa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiwffqp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zjundmkj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwwajbn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rmajfoze.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwvefkp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vuznxfej.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lctpsdxo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuutjcs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iuawkecv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qktltnbz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdlgiqn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaoilsa.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyntrzvx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpocibw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmjthbz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vaemmlwc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2frvzsyyb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2afroewmv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhuuija.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpecwqx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wboimldy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmshldq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnhauqy.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmfewcb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsdmict.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nwedsjwf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxxevyi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfybyrlw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvshzmj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gpavwkap.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoooelk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmtklzw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwsluje.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnawzksp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsdakkq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2splfjeku.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyalumx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2femzryix.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrmgkjt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgmgtgg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gitcglys.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrqevyp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hpatdbhc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kydoyntr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhwjcpo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cervsdxx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnobdpp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyzlkpg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrofsgv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkrytov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mymtorfc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvfqckj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzgpnaq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vdevqacv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2toduxjno.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgvptes.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2etsmvaqz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nepwbkaw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2spcxxhxm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiujkgg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2expzqrye.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hzctncva.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2umeedeix.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmhxzsa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hknfkhyf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uzghsphh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2decwdkbc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2szzvmevs.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2axvzseor.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eommsuxj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2funqakwz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmtzuyz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaseccu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ucigyqsi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pntbqjbo.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jengmnzh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgciicrz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rfregwmk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjctvkcp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mlriesqo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzzryka.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2grallgen.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdvkpor.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vblreoee.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrzwohz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmejvwc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmhqmbf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxfrohy.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzsjxij.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wanonafm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxxgwav.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mysnxbvj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dopibrkq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2biwkrlqr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxljwwa.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrmctnu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuqtzka.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmcnecx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhdbnuq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2osqbghtl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoqnrqq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2orgbvlaw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2boqwvces.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqjawho.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycycbtld.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lowvevtu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bajppqkd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtkeubx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqlkvme.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yaffkfxs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkpfymz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbskwuu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvelejfu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlwgbwf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxnjwuo.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tndhejzg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qiewgkyr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cxteycij.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zufqoakw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgelbuz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xhapgqcu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2txouuyqb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyzatvu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2oojsuwrr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrlcmaf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxwjhmg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvvefzz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gydgkudu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyzlfba.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzxlimj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2grvahfkt.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkhgzhw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2glcsxqqn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cmchhdst.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdqcryr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gzioainc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucavjejl.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqeihab.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrfjjnj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlhsrvz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oymscusv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qcduxvqu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eamhdvrl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwahjdh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adpbnjez.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmciunu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vawbusax.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzafqqmv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcvwmnl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2flobngja.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmocpbl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqqttuq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqrlkzh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeyqpli.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dprizghd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cmadmcql.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lzybcwlw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqgintn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxlgzmz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmwseqz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqvjikt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2flunxdet.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfwsscf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtheiamj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2exteejoi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqszzky.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2chxmbqdn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hukihusr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iawdnhtm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvedatqk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxaqqpx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cstewffe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lslizjds.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmdqeyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmijoqv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2utatjwgy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2oseqhjrd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbaqxfg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnfijwo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fqubvmmq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjevpqg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2exfpbxze.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jffbexrt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2uovoqnhn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2owijpkmq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbxlvme.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxgdmgd.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmbfwas.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2uywtjskh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gempndhe.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxwhmlj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2piazyizo.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hryfwsgx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pxucdfab.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwvvmop.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uzctbatf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcknkxct.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnlhazg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xomlytqd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mbthepce.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2durlnlag.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnboflg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdthffi.html


<!-- 参考信息 -->