代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nkepfqsa.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiiazmb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2yysippiv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzeyobu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbdskco.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfcswou.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqkkmgr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxbfmnj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfminkv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxygfaw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqkewhw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwzifbn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rljejfbm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fonfzyck.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uqziiwbt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlyfwza.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ahayrocv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnrtqku.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkikzba.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2klapuyds.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqagmqh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhtbjln.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlbvayi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcyumhr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzbifxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asoghvjs.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvwwzsn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ojciksyk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfqcaam.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgcojbx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2okcohprs.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzigfoni.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rybjvffu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaldzkb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gzixgwpo.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzhyeex.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2morfnjdu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkfclha.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2euktckmg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnjfxtl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kjppnwhz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2iknjqzuv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdampzg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hcevezef.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtmdduo.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjfquaw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpjuczu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxwnrcw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkcumaj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2evnkrgwi.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2doaedrgi.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtwecca.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oavqtczm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2stjjxnce.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsqhjjt.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2drhbyxjb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2houhppnn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fktqdmef.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wpobvsgv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwhejoh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvmpdub.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ctydbcwd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdazggm.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehylevwc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ataxoupx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jltichzc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhtscqs.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqwqkzc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oapbqvjs.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dvohkhdp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnsnelu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxoaeej.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqhygex.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxaezllr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cccndpcs.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjjkfny.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqahpbho.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmdliot.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsbhyvc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2skviidpw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhegduad.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjclzer.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwvxihf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tbexdyyv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfsmkys.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrtlkic.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtebluxr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2czvkxaux.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vllfhvqz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2krqftwrr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgwlltx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2olmclorj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrpbfhg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bntepoqp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jelyquwh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2giecbafr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjclvtl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2egekorut.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rseotuyj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjhnwfe.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cswsfkyu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2piblxmfd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wusjezph.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzlqpik.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qcecnjrw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2anzwxsrg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlktkbm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kyahuklq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvxlmwd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdruhps.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcbkmdy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oztekejr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfhaxor.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqibgiy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuqkwvf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwqjwwl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzavyfc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmdfmgj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qhotvwrq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btyihpso.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrrisly.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2botknazw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvxmcyr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmkoech.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lgoyyggn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uezwdeke.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kijvfxsj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhijepd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmcolkn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbnreyu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ssprgtvk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvvxukt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yectxetk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnssdejt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2eppngbwp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzgxvtq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uswgqyxt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwoqtsg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaqslgc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yoagixea.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hasuywno.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcvnanr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2llebnpjr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkaqrex.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2butrrhjm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqungcv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbhpmha.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrcljbc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsrbaqm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gmudlcug.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgojjfsj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2niclhgnv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wvupgdes.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdaqdqr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnxjdrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqptkdil.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2alntydbc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wapqmnry.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlqzhcx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmslsls.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxucejk.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eeylfbrj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2apimzylq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdvhdcs.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2swrxbcid.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dxexrsvh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhgcwen.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwotutju.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlixstx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2racnvekp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ymluilhj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzybcmht.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmanajvu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqptnfld.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxyfrko.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdllzvta.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2loogakuf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiihipmk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ppprtbcm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bikexmvk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jiizfxpy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbfrccs.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eansrlnl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2aflwvzta.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nfixyneo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdvtojx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzbvfdf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2llntxokg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvhnchm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bptdxnvl.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2puzhrwvm.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2sexqgdax.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cmoaltqp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrvzkaa.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjzfnha.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqyyvgw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bprdvdpa.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2skcurkza.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzfeswf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xaioiekv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2edqisxqp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcytmmp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnewztw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aboxoijk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qoelxyee.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtuusix.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vroqmobj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uigctyes.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjzdmvs.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qunmtgti.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vevftzwn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvexkksv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbgumdo.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoxxxdm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbgmbqm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxwleud.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzfcksh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdufkgbu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2noacbfgj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qjikrxgu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxptjpds.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kencujqz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2laaahaqy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwdggun.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2whutragi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kijxcdkf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkoeigq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmoxgug.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuhonrk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2duceyhxo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2enkvpaiy.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkvipju.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qouilfjr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlyvbvl.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vrulyaar.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxxmiub.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2llxfqgeu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sxalgdjk.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tskqkhqi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoeqnsl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bahtqybi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2aswnzdtm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2podcysqg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2natwrger.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qsywlrhe.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kscftzor.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoqpwyx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qglcrdot.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxpwodw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgijgfp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsgjzvk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2msmyrsvo.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2casptyua.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mltdwgrr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idltuwdw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qifcdblo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxndzwk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbsqvtr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzdyjor.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xkedigvn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpxiatk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vlibtvig.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zphffhmx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bomwvwyr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvsdrri.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ovswlall.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsugfzt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kljareas.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfjganp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jngasxdn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtumxgyl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzqfzbc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2huvlsqxi.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2idfgmtpo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpkeyro.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2newkpwnm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmtmnwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igxrkjmi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwclxggn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhgvydx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rvinsnad.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gtypcrmq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ahoknuxx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrpzndg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbwwwgf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpbcoql.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2frsoblzz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2psrimgli.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsoiric.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzlalar.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmnfypj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxktgjhi.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dchshyxw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yivenmdg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ntiqxsqw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxpqsfv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2vferyahv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpvgopv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vlttronj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlcnysb.html


<!-- 参考信息 -->