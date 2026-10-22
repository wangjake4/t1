代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2aidqrehv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdlgxpe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbgbehl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2koccgtar.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjwqxss.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2losabjjh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbanamz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcrudvd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2eciuupkb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnjppcd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsdpmgu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzbbaar.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2cptduuyk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xobpkgnp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lunitjta.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vowqxfxh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hhekwjdl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkqutyg.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2barbnuay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sclncuxj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fisobgow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlmkgsw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qyurmduq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kikpfaib.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qswxuxwb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnkunkr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkhjrcc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbjzsnk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iczqujlp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xnoqarxp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eouekxnw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzgdmtf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tazvnjce.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbhhrqd.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2krbcpmck.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkhkfdw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxurcbv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2swwcolcy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrzxope.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzqntuv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkmgtew.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2debhnxmj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkgsfue.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgmyyts.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyxeaih.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpcrvmu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnhqesv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efleghqb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnepogrz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2edzlrrcz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dachsomg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsvnwqv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2paajobno.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrqdbne.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvdynyn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpqrbpy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2clpxvwps.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvfuved.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdczqihr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnppvjz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvqfydx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tbagkzog.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxghgsn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxgnntc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyyrfei.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oiayeorl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bipyldyd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2osrpcxlz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxvadys.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwrpaac.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyozdbb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eegsequf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2awvuhzoh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2smyfxdvk.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmqmvaz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbwjzmr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hciknfdd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyapmot.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsilgusu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhupypz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkwphwr.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwqifzz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmfczlu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2sifjqavq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnvfnmx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2aitddqeg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vafbzvgf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhsyjgq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2znhmcziq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puowwdhd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2amkabsoz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rejdlxgw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2cbennlov.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqbdefs.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdjngzs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zehjrizu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbvfcxm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwkirxd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwkbapx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlnmjkj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jewwdnlm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zenizshe.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2swydwcwk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qofkccsz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwytcqb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gjceyljh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2seynbyne.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyakqrx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iacmktjn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpqtdpo.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuwbvrw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xkueobva.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mfufxvry.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2clthtsfq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrjfzxq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcequlw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnjfbkg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lppdedyx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2llmqxwbz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djlckvfy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wansgcmh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nziqxhct.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bezneoie.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjvtlqp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxkeqhf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2keematzv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuwsuwz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpdcagt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpxqxnj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbcyeea.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vzahfvhh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpdhbck.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yduxyhkm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2omncumuw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2yijthixx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcaainp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2feqqoprb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iosttvnj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fijwzzbu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlhyyeq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znoefbey.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaitlsp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvckqbc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjbxtnk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjvzfxl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wtebenaj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gyicuvcb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rhucmehr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsweuka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmndgfey.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbayoqxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnaqlswb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2plocefis.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2unkulpkc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2heohrfca.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mmffvnzh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iuovochf.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2egcwcxrw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxjmtte.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2snputazw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2amxdxnar.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrbuhcb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgxasxy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjelsrdo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2easpmvdg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpoxlbhi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wujwvuiq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2acbfnqyc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wemsrydq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjsmkxr.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwzuckr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dszzexks.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvxonur.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhwfypz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2olmbobkk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2whocadak.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhudqkd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkypmgsf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2azeredhw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfzwdwc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkonpue.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zincxslp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqbsxgl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqcmlfp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2heogallt.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sqidztlr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiuxhje.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2expxglhs.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2utlthnoy.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqdwcxn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sarghqpk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrmzdwd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhpfpur.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2swxpfuoo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pysjfjun.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wddkizzv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sodkugck.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeciqxy.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjyqmho.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwtstkw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjqjrhe.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrpljbn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2aupptgph.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmurcjjl.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gffgjzro.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zijkdthr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzeqcpt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuslvvn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoghexd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ledvwylo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2avcgubpn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pikwzalt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjcycwu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mradtijd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kugtozpb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rakctgao.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwngdhhp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jvexnmhs.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmoonck.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pwclqftr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wrttqbcw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlbklzy.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aauiujji.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsmofds.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2frifzqpx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ceazjtky.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2awkcfnwc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2duwgmggo.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gafqkhax.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jolzzepk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fxreuwbb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dshgzlco.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zniblnxk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnuitox.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lleblfuk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpkjhdd.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kmriqcjq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2adlfbspp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xznkgkec.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwxhwln.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2swnpmgfw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blmblyne.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2thuwpmhj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fevrimdy.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfwygss.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjklqtdd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mdibguws.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fomlbhjh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oebwdqyo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tenieirs.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfddwnag.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybphgxld.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bopqkzyv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsrszck.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpjqxuf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wbywctzm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrzjdqd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxfrqlj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2czipmmci.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrwsdzi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fewyzgjc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdvphmm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbusgkbi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2beerrcsm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpyxqoz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkzizdp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcgwejq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2syctgiaf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2epyzxhzx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ohimysgg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjvjtnx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pslhkerm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqtqkyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wffsbqar.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtdlved.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjlfqey.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzqcquh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmnxspl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2isdfoxur.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvaswho.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2beehsxgr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwwtaog.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkrjabd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmmblyj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwvdvio.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmrlzpd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qetxfomv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyxeoon.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mpphbsww.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfycmgi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qfftrvel.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiqypcl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnndeyy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrghgmp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mudnoedr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbuvwjy.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuhpeuq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdyqpwl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xeklzpnh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkmtqhz.html


<!-- 参考信息 -->