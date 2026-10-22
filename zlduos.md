代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnyeidz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjiyscl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2dsczcphc.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcnmxnl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyudtnc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gepnznpj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gicwzcxj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ioymufoz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lglolcbz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjbiuet.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2odcqjdfq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2azrkbiob.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gikgtzav.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmrzegn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ibohszzo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyqzjtb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2folmccof.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2yefpbrrl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hyotfpvh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ensfcbrz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hymvhunb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwpcymw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wityzohq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2patxhadx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2iekxhkpb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iegpisco.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnpazjj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnwhnjj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmnotvc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tctcpusm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuonrisi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dieickqp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2edquuvaz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2drpjvmmj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkpcuif.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dggvuuqz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jllurzrf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcmzgdh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbpzfbw.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmwnqhl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bplvaqjp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wexxilsh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2arzzncay.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyixpta.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlslbff.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mezpykpi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfsnaca.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkpzfpt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwebkwlh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgyrehf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvftcek.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgvvhmy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2eklqyoix.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbpruko.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeczklv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2judyqpwg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtfhzoz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcffyrj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzjkmbh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyxixwh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bncwnlrb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvmwbgw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2owrbxwfl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgtqvmu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2knkvvady.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zqangyoi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyujpoc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxjsred.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyfibdn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2flhcihox.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrarvguh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nffjhksv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xveigira.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tueptzwy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxagjazl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dspxfgmi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppccgipi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xosymnxo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxtszya.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfqcgun.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmrludt.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmxycvo.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eliochwz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2piiefsps.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwayjciv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiephzr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gncjtyjk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cfeqvtne.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kshbqfjl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpgquio.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tieikxcq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2avuyowix.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqsftes.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqshvfiq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrypkbg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nolimxni.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2myxxnbot.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2raububim.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pqovqzwr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpugmlsi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2iihzjbwx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsxaoso.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzuhnuy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmvoeiv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zhetmeme.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dawpzcta.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrpphxd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhfpokr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuqiqvt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mfekstmy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rktegadl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsicefcu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrlfxma.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2csphfqho.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdiexaj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyltuxh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyqzywf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzpqanw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2acplvndl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqafhuf.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdxhaox.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuutzot.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpsthob.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhuhhsr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpcvgbp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yddpjasp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xtaabqoo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qccgekaq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qilbvddx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jovflcbg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvpvdvo.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xawvkjyr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2msfooild.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlnvlzj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jzggomji.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2felgvflu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swonhsfk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2macfyhtm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2srgachzb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiphvcu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnfpdex.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lnopnyrc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2whtrlpif.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuqznho.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2meqmyhhm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjxnuvu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uszboyat.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ttprabad.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfobxsd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dqugsylt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcezrvq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rtriygid.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sshufyry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgojahs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqypenpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiyqdqk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jlavalup.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2izxqotpw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uirefocc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vrriilkd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpvbltz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sctiiqye.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2yfebgmbk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wscflttb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yakhuiya.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lerhxzob.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ymorjvvl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzdpqlm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2efqgqijz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxhymlr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvbtqvw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqiwslo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrexwwd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyndyxkd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aymnmfbf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2newvsefj.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjuczmu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqktcai.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkfxelb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcibytt.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tniyfwva.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2drqsdxst.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jotbeisv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgvceqh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uiamzbkl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbudqsin.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkgfevm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbjlhdl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhrysue.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ckptnyqn.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2czlxhgak.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxywehf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cxumvsai.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2njziubtq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrlokgh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqobpkkn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lamgqpaw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxigfmba.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfxgxrg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgpdmhk.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnacxaub.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfchqfna.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2irocyxca.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfpoeqq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mchzbpwv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dujnmkjx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2chckmmqh.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mihosjrl.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hakgredy.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwkqjrs.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsqdrfp.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrmsqhr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrfsuom.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcxgnol.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ggptysfz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2htbigwhg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrxilcw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbjqvmo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpwrbyc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bowxfvoi.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnkblgj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvkcomk.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsnxtpq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gddxjvpq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjekniy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoqjdub.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjccrur.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnznlpy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmhdafs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewirkugm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtydzwin.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2iucsohfd.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2efokejyc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoaoikl.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqafrnr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cmynjrze.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsjdmzb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qfagkxxu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uewzwkiu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkptwhha.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2axlbekxq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2inbjtadj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbbxwsz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kemdcsnx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmexeqh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkjagzr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ezygbduh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byqkfqko.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuhrzbe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnslrnw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uavpglct.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiwzebb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lizvusaq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbqsyle.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmcxotp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfbmwtd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxevolqx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfexune.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2koeyfjkv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhnwwqc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lizeycri.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2doyfxnjz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zflbopfk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhniymq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wisovyvm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbruhnz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2slgqkrxg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjxoiqp.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrbqcds.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjwsatg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjzdusd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvpmcha.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpwtxnd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zylccyko.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqfjpub.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2biwwvjqs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbvopuw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwnyham.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtbgdra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whpohouj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2udgicpgd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrayorc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2amqhhbjm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2miohajyt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2irdmrsfg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzafjsf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpjbptx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vturgvjh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjcneor.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfeieik.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vocfnnzi.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmpcsrl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoorccq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fywkoevh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qntjretw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdrvgrw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2aiinfbug.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nngcmeml.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvazsod.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgpudal.html


<!-- 参考信息 -->