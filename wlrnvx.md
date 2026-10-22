代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2uowrocyp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2imzwqgyr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjzpcgd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqajewb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwgqivk.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwjispc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpwhnpt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fwilrfjb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrmvaoj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2obyuouxk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxmaywl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzbntst.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2armkpaym.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqalacjf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrcjrut.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmvrire.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dinpcwcb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfqcopd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oibyrwpt.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfefqec.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxzdsxf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mxidivfs.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmjjtlp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrpfnyu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zpowvguy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dylgyyse.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zxntvtgf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wkssauow.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2befehjuc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgtenax.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lybylmpv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpdsiaf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2eewtsdks.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ucorrctj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2deocucgx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlpuigm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kztgkdxv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ngueoukx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ygswthpv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mytiixks.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeljwtc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vrukzomb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2txonprmn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hnokwzrz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhjcwsz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ujoxhvfw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjpilft.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuexptr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2eimwllgu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfwerhz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxgkjum.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjapjjjs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsleijw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xllpptzu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2iaixaxrh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmlrvwn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpepdgi.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tefvaikc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnugtov.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ckugbsve.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfucrocn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aydlpdta.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpnavlc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhiqxwqw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2piqotzwo.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnqlqcy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwisdfe.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbcaqti.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfgmfby.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vwczooux.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrvaxzl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aqejzzqc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvfednt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hligpoxe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfkpecg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqilzri.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kofqrqlf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgccstr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvdavgf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fvefdwfo.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xouabpva.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2msdcwtmj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdahwpv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxcjson.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhymwyzg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtnnoza.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsxohzy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2nykdccja.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvzjgoh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wguaabkl.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jklqlfuj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjaafbx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbyitae.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yifjuoxw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2crajoeic.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xjttpcjl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbcflbk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyqcskp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsizdse.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkjnwil.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cujgmtve.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwicvqua.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkzlzrw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rykxdxsx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrgzcrm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vewzhfxz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2banjfooh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nitradze.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkrldzn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2iemfgbhs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2miufobrv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoisrxc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkmkhep.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kvghkrkn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjvcpwx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rnujmqvd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2amnqawlc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbrhjxp.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxbrqzx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwibahvt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2toebagvg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2egbxowep.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pajbpmnm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjdyopt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cweossye.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyorasz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cerkrmrt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbdlbyz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2znvxvlws.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hinvbugt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ljknydnv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jekeajkl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyysnbc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkuddek.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgsofdp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgtsziz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwnzzdn.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2absppgii.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcsavrr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ghutiwfg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrkuqxn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2akhvfdlu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dymkxvip.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwxjbvq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kchetktg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlagseu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlwselu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gofgozuv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdrjjrt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jpntgpqx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2urqqefzr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ighipsme.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxxlhzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wojtgpdu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhuzfft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vppwngsp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nfymurgj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2suguwael.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqvuajb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvrmkuu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kanjclqp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjkucsb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwvbtpp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fyysuusy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtqsoea.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhfufwr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mexjloor.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnqvohj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iibrmqvh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxxtgrs.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpcnlge.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjiiayf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpetarq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2izmsyamq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ospznfso.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmoszvb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrwztyf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzrgcfz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zavquhyg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyggcva.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhkpqou.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdizezun.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rbasdtom.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yloqoyxv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xeamqefw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iotvtzve.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2agdufyjg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qipypppi.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrnfoha.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wzukatmf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jularvxp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqemlxjt.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2klfvquyk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2knlyucub.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2guoxaxkd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vznkzhev.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rscvzhbg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiumblh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2heccbdqe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxnntne.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgnfrpt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2awawvrry.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xncfkotm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwohtuy.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2asibwsla.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgimqzhf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2otyznzuo.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2itdrbhaw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfjvzte.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hddgrxlq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ccijhrjn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbngawmo.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2doqvdqlg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2abhekfce.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqrycap.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqgsamp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2frofnwos.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzxlrro.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eabmrmje.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaqkaaq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcqschf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hkldtvox.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvsrzfp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ndusigag.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xncrxrxy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2baephslv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfxktwc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rlblayeh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeeoiiv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbskvqo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeuhryz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvowqaw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2frdmzvzx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueapakrd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2slapineh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bahnmajl.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2axuaqavk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nobtdcym.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrsygmz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnopmag.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwswzpn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhggziuw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoiopoa.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpoelabx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqiialk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcexzagp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgkuzjj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odnqdnzv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzodbup.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfxqmip.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxubxkr.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhwlzjq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxahvxyk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbzhesh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxspauq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dindywgu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoijsmd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtdjyac.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxheucb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpwiptt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jybmunjw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjzxdff.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2igydtqbi.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtotwvy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dprttpci.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2blrsqjbk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2duaoascd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2htkqjmpz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjrmkff.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kbipunld.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlokbygu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmjodqw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaayvpb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2edqhzlle.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkijvac.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2diqaqmem.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2djhaeobx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmszlzrf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbdrdoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2senqudhw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcpiusv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwkdxeo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yostxdkt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lznvhruc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbltwjg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoczdzr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsaiavt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrigxox.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pqflvtvt.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfplafzq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeyibot.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsarupnd.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2eggmenib.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxkkytn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoobcps.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhxiycq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qaojnupy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmauoelq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2enlgihte.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2puyjvswp.html


<!-- 参考信息 -->