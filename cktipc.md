代发 wailian999

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmytrkx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2frjmhhmz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfbogtt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bzimmdwr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijevlqkf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wluahdwb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hwldqnkr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjopiib.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwzcdzc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtldufq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ycthlvht.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbkybld.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zceeoeem.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzkarbh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mwddlzoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snmopqcu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzpwxos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfjxbue.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxpnysp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuowcly.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tangvwbe.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jyscthmd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wizmgvyi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2efkgztsr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2omqlzzkt.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnxsiqk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rldovaec.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzfktii.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jltehxlp.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zikjpyam.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rslapfes.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeeisrm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lflvhbne.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuimdsu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2esdohaze.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgsbwwd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjcnvem.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrbdaqk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gshirkxp.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcpkgml.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiffvxe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqjgmat.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgdlgbl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ikchxbzw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmwxwha.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nwthmynf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbihqtc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqsnwsn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tafwfhgm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpotqut.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjnrlju.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsnmyld.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmkooqt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyxjykn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2elhrarka.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxztaugu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wamezgad.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ottfdwta.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxouvbyl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyjrgkx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iguvyhlo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxiyqhd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqvaeiz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqirwax.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2guehceni.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnozbpy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pojzqsis.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dizkuuxe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqydqvvj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbcghxt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeaosxe.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfafppe.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpehbth.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzmwfpb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmemkfd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuroklu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxiycgc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2swqswqaj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qigmiamw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2klpxlnfc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzklcqd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jfprlsje.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnnyqdf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tvibkbme.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvipvwe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abbmptre.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pivftuzz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyzfdzd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhmahyh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhihzyg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2spbsrqmb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxrcojl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wknhrcuc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzxpsab.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ylekaeug.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sznczhcl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fgauyxku.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzpwqja.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vxetczxz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgatari.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuokyae.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2flosqrxy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmgtqhg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jihjgmpv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzvbyxz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2loflpbqu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkfanip.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2djzcfufl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bihtsxyp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhoonkka.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2scoptnve.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syvlqxwd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gejrkgrs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzbjsqv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdzkegk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yayqpulm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjpppsf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuovneu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxuhdew.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2oujbqitt.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxowwrsb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzqrvyi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmrdsli.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdqxpew.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxzexgb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xhthoftn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsueolh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2iadeieib.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nayxveqx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpjnbvb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uanpcjqd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvjaeli.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2riibrtkw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tvukjckr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sycgrrsd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2behtgamj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsrzqzl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2urssuzvm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzcpamb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwtbqnw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2naufvale.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ulatrumm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvpwrhs.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoctvxz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfzqraj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkutygq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2npgyuwzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2opaimpgo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmgsxou.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ginkwfoq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwijwwz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dczdxphx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eobzaxjw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzggpyly.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xxehlrrz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dcisawuk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2naigirca.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2arnbcesq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2whjurbrc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2exzjyuie.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2neygtneg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvclhth.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2otwachrl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtjoxsl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yorhtacd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxapywai.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxufzbrt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuswipn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyvigll.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeumsxoc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gkspljpl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbryoubb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wsemhodc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrrkyyx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxwwiki.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fystnzld.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdboero.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qocpnqov.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2llmynuet.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqluskz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2edljlxll.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfwroga.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfwouek.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kznjxdrv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yukshwud.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmefcpv.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kztravxw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxxkaer.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gojmtxbx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2txiqngav.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrdfssm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqmnauy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxtiwvl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsejkngo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2isnwkkrq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwykkwik.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2voyvjfbs.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdhtudh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bylztxgr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuihjiv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2skhdvvvk.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkrkarx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqyorzy.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnkswzn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsvmupx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcascpwm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qhseaytu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvbnoqs.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpmmsow.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsycyxz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgxiklv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2akzmjrig.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2guvnugcr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cxumgiyi.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvudszy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rucgjbnk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2sadaiuej.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fhawosvk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2trpzfcnl.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzwqvjx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vclizxug.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2otakzeko.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iuieqpfz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxhuenm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2puczvkim.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgufnkc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2evlgshts.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tnntmdvu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oleufiqs.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qrehvbth.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhquauw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggiczglt.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ylygjdkd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbycqxtn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yuonsfdq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcwpvvu.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yuoawkgi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biythqpz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2waysbuoc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brxbciqn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2taietcyh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loxxunaa.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtgrsxf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgldpur.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfhlusb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czknduzu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zindowqv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nahhlhye.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oihglvht.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ceylrzpd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcwhqcp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuofrgs.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsxhvpt.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nbedcwrr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrbiych.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aumywpea.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yazabxfi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2izhzxmvu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfakncf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hfacouqt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgwxxcq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iutbtfoy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kznlshhp.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcrccdc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnvtfnh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqohpue.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkrsmqc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mlconmlm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2szqmhtwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bposjrqh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxctfnf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwslongu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iymigzvi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lirujdwe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hyohasbo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cznjfuih.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2eurfpvjy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnuebyk.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zugwnvii.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfaqtih.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hpoxlqci.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjembjsu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kftjfetb.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vozkonqg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmzgoog.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2aawhpwyk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oiratitb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfhwlcg.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2aolcgpej.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2llvrgvqg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jirxanwd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cljkcprv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xcejlaxd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hthuahap.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqcvipu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmapsff.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcknkdz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbjlhdm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ymynwfre.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hharpjhj.html


<!-- 参考信息 -->